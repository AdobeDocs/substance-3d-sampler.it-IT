---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/release-notes/version-3-4.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 3.4 per scoprire le nuove funzioni progettate per migliorare la velocità e la qualità nei flussi di lavoro 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 3.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '838'
ht-degree: 0%

---


# Versione 3.4

**Substance 3D Sampler 3.4.0** introduce una serie di nuove funzioni progettate per migliorare la velocità e la qualità nei flussi di lavoro 3D.

*Data di pubblicazione: 6 settembre 2022*

## Funzioni principali

## Parametri esposti

Modifica i materiali parametrici all&#39;interno di qualsiasi software che supporti i file SBSAR, come CLO, UE5, Blender, Photoshop e Illustrator, tra gli altri.\
Ciò è ora possibile grazie alla nuova capacità di Sampler di esporre i parametri delle risorse, che consente di velocizzare le iterazioni e di eliminare le differenze tra Sampler e altri software.

Esponete i parametri del materiale facendo semplicemente clic su un segnaposto.

I punti colore vi aiuteranno a navigare nei parametri esposti e nei diversi pannelli.

## Python Authoring

Ora puoi creare plug-in e script, con la possibilità di personalizzare l’interfaccia, semplificare l’integrazione di Sampler nella pipeline e configurare il flusso di lavoro nel suo insieme, come desideri.\
Ciò potrebbe consentire, ad esempio, di creare uno script che consenta di automatizzare attività ripetitive come l&#39;esportazione di più materiali con un solo clic.

Scopri come creare il tuo primo plug-in o script [qui](../scripting-and-development/scripting-and-development.md).

## Proprietà fisiche CLO

Ora potete creare tessuti che si comportano in modo realistico con simulazioni fisiche. Ciò si ottiene inserendo le proprietà fisiche del tessuto, come Piegatura, Inclinazione e Attrito.\
Con questo aggiornamento, SBSAR conterrà le informazioni fisiche nei suoi metadati, che vengono utilizzati da CLO per garantire che il materiale reagisca in modo realistico.

## Da immagine a materiale (basata su IA)

Image to Material (AI Powered) è ora disponibile su MacOS ed è eseguito in modalità nativa sui dispositivi Apple Silicon.

## Note sulla versione

### 3.4.0 Arancini

*(Data di pubblicazione: 6 settembre 2022)*

**Aggiunto:**

[Parametri esposti] Nuovo Pannello dei parametri esposti\
[Parametri esposti] Nuovo pulsante sul passaggio del mouse dei parametri per esporre e rimuovere i parametri dal pannello Proprietà\
[Parametri esposti] Nuovo menu di scelta rapida con pulsante destro del mouse sui parametri per esporre e rimuovere l&#39;esposizione dei parametri dal pannello Proprietà\
[Parametri esposti] I parametri esposti sono elencati nel Pannello dei parametri esposti\
[Parametri esposti] I punti colore e i dischi colore vengono aggiunti in diversi punti per identificare facilmente i parametri esposti\
[Parametri esposti] Le etichette dei parametri possono essere modificate nel Pannello dei parametri esposti\
[Parametri esposti] Visualizza un avviso per i parametri non esportabili\
[Parametri esposti] Visualizza un avviso se si sposta un livello con parametri di fusione esposti in un punto qualsiasi in cui diventano nascosti\
[Parametri esposti] I parametri esposti vengono esportati nei formati SBS e SBSAR\
[Metadati] Supporto di modelli di metadati personalizzati\
[Metadati] Nuovo modello di metadati delle proprietà fisiche CLO\
[Metadati] Aggiungi icone al passaggio del mouse per aggiungere/rimuovere metadati personalizzati\
[API Python] Nuova API Python\
API [Python API] per la creazione di risorse\
API [Python API] per la gestione dei livelli\
API [Python API] per la gestione dei parametri\
API [Python API] per la gestione dei progetti\
[API Python] Un plug-in può essere abilitato e disabilitato\
[API Python] Documentazione delle API Python accessibile dal menu Aiuto\
[Scripting] Nuova sezione Plug-in e Script nel menu a comparsa Preferenze\
[Scripting] Creazione e importazione di plug-in per personalizzare l’interfaccia di Sampler con i propri pannelli\
[Scripting] I plug-in diventano parte dell’interfaccia di Sampler e possono essere ancorati e spostati come pannelli standard di Sampler\
[Scripting] Barra dei pulsanti dedicata per i plug-in sulla barra degli strumenti a destra di Sampler\
[Scripting] Crea e importa script per eseguire un elenco di determinate attività\
[Scripting] Avvia gli script Python dal menu Script\
[Scripting] Plug-in e script possono essere eliminati, riordinati e ricaricati dalla finestra Preferenze\
[Scripting] Aggiunto —parametri della riga di comando run-script\
[Registri] Nuovo pannello Registri\
[Registri] Abilita il pannello Registri dalla finestra Preferenze\
[Registri] Nuova barra delle azioni per cancellare, copiare/incollare, esportare i registri\
[Proprietà] Nuovo pulsante al passaggio del mouse sui parametri per reimpostare il valore del parametro\
[Properties] Nuovo menu di scelta rapida con pulsante destro del mouse sui parametri per reimpostare il valore del parametro\
[Contenuto] Da immagine a materiale (basata su IA) ora funziona su MacOS\
[Engine] Aggiorna il motore di Substance alla versione 8.6.0

**Corretto:**

[Applicazione] L&#39;applicazione potrebbe uscire quando è in corso la generazione di una miniatura. L&#39;arresto anomalo dell&#39;applicazione può essere eseguito\
[Applicazione] Potrebbe verificarsi un arresto anomalo dell’applicazione quando si utilizza &quot;Salva con nome&quot; all’uscita\
[Applicazione] L&#39;applicazione potrebbe bloccarsi durante l&#39;arresto di MacOS\
[Applicazione] Quando si salva con la finestra di dialogo del colore aperta, le modifiche non vengono salvate\
[Esporta] La convenzione di denominazione dell’utilizzo non è corretta durante l’esportazione\
[Livelli] Se si trascina un materiale sopra un filtro si potrebbe verificare l’arresto anomalo\
[Livelli] L’aggiornamento di una Pila livelli obsoleta potrebbe aggiornare Pile livelli non correlate\
[Metadati] I campi vuoti vengono esportati\
[Metadati] Quando è presente un solo elemento di metadati, l’interfaccia utente consente di riordinarlo.\
[Progetto] Il calcolo non termina mai dopo la duplicazione di un materiale\
[Progetto] La risorsa del progetto viene duplicata dopo il salvataggio iniziale del progetto\
[Progetto] Calcoli non necessari quando si cambia risorsa\
[Rendering] Alcune Pile livelli non vengono riprodotte correttamente dopo l’eliminazione di un livello\
[Sicurezza] Correzione di CVE-2015-20107\
[UI] Gli output 2D possono essere sfocati a seconda delle dimensioni della finestra\
[UI] L&#39;anteprima delle risorse può rimanere aperta in primo piano quando l&#39;applicazione perde lo stato attivo\
[UI] Gli angoli arrotondati della schermata iniziale hanno uno sfondo opaco quadrato

**Problemi noti:**

[Selettore colore] La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare\
[Contenuto] Il widget della luce della forma non funziona in modalità proiezione sferica\
[Interoperabilità] Il materiale con spostamento inviato a Stager perderà i controlli di spostamento
