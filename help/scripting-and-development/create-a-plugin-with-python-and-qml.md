---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Scopri come creare plug-in con Python e QML per Substance 3D Sampler per creare interfacce utente personalizzate ed estendere le funzionalità.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creare un plug-in con Python e QML
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Creare un plug-in con Python e QML

Questa guida descrive come creare un semplice plug-in di salvataggio automatico con Python e QML.

## Struttura del plug-in

I plug-in Sampler richiedono almeno un file Python e QML per essere importati, ma è possibile includere anche altri file, come le immagini utilizzate per le icone nel pannello dei plug-in. Nell’esempio seguente, sono presenti 3 file:

* **autosave.py** contiene la logica del plug-in e ne determina il funzionamento.
* **autosave.qml** definisce l&#39;aspetto del plug-in in Sampler.
* **autosave.svg**&#x200B;è un elemento grafico vettoriale utilizzato come icona per il plug-in.

Una volta che hai i file necessari per il tuo plug-in in una singola cartella, puoi aggiungere il plug-in a Sampler tramite Modifica > Preferenze > Plug-in e script. Per ulteriori informazioni sulla gestione dei plug-in, consulta [qui](manage-installed-plugins-and-scripts.md).

## Python

Di seguito è riportato il codice completo del file python per il plug-in con salvataggio automatico. Di seguito è riportata una breve descrizione delle operazioni eseguite dal codice, ma il codice include anche commenti con ulteriori informazioni:

1. Importare i moduli pertinenti.
   1. Qt è un toolkit di interfaccia grafica multipiattaforma. QtcCore, QtQml e QtQuick sono moduli utilizzati per comunicare tra autosave.py e autosave.qml.
1. Definisci un metodo **save()** che salva il progetto ogni X minuti.
1. Creare una classe di salvataggio automatico. Questa classe specifica la modalità di connessione del metodo **save()** all&#39;interfaccia utente del plug-in in modo che i parametri possano modificare il comportamento del plug-in
1. Definire un metodo **register\_qml\_type()** che esegue l&#39;installazione del plug-in.
1. Chiama il plug-in da Sampler.

### salvataggio automatico.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

Il file QML definisce l&#39;interfaccia utente del plug-in. QML sta per Qt Markup Language e si comporta in modo simile ad altri linguaggi di markup come HTML e XML. Puoi [ulteriori informazioni su QML qui](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings.).

La struttura generale di autosave.qml è la seguente:

1. Importa moduli.
   1. I moduli Qt importati sono necessari per gli elementi dell’interfaccia utente utilizzati nel file.
   1. Viene importata anche la classe API di salvataggio automatico creata in **autosave.py**. Il file QML fa riferimento a questa classe alla riga 20.
1. Creare le variabili da tenere traccia.
   1. **autoSaveFolder** è la cartella in cui verrà salvato automaticamente il file Sampler.
   1. **intervallo** indica il tempo in secondi che intercorre tra i salvataggi automatici.
   1. **textColor** viene utilizzato in modo che il colore del testo nell&#39;interfaccia utente del plug-in possa essere aggiornato in un&#39;unica posizione.
1. Creare un’istanza dell’API Python
1. Definire l’interfaccia utente.
   1. Sono inclusi gli hook all&#39;API python creata in **autosave.py**. Ad esempio:
      1. La riga 47 aggiorna il valore della variabile **timing** all&#39;interno del file QML ogni volta che viene modificato l&#39;elemento &quot;Salvataggio automatico ogni (min):&quot;.
      1. La riga 64 chiama la funzione **start\_auto\_save** dall&#39;API e passa le variabili **timing** e **autoSaveFolder** come parametri.
1. Create un metodo per ripulire il percorso di file predefinito.

### salvataggio automatico.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

È possibile che **autosave.svg** non sia esplicitamente chiamato o menzionato in **autosave.py** o **autosave.qml**. Questo perché Sampler cerca un file SVG con lo stesso nome del file PY e lo utilizza automaticamente come icona del plug-in.

>[!NOTE]
>
> Se la cartella del plug-in contiene un SVG con un nome file che non corrisponde al file PY del plug-in, il plug-in non includerà un&#39;icona. Questo può creare l&#39;aspetto che il plug-in non è apparso nell&#39;interfaccia utente di Sampler. In questo caso, sposta il cursore sulla barra destra di Sampler per evidenziare il plug-in.
> 
> Il browser non supporta l&#39;elemento video HTML5

Se la cartella del plug-in non contiene un file SVG, verrà utilizzata l&#39;icona predefinita del plug-in.

Di seguito è riportato un esempio di SVG che puoi utilizzare per il plug-in di salvataggio automatico creato in precedenza.

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## Limitazioni del plug-in di salvataggio automatico

Il plug-in di salvataggio automatico creato in precedenza funziona, ma non è perfetto. Ad esempio, se si regola l’intervallo di salvataggio automatico dopo l’attivazione del salvataggio automatico, non cambia di fatto l’intervallo tra salvataggi automatici: dovrai disattivare e riattivare il salvataggio automatico affinché il valore nell’interfaccia utente venga inviato all’API.

Se è la prima volta che lavori con Python e QML insieme, correggere questo bug è un modo utile per costruire una comprensione di come le diverse parti del plug-in comunicano tra loro.
