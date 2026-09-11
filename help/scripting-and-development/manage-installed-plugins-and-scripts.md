---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/manage-installed-plugins-and-scripts.html"
breadcrumb-title: ''
description: Scopri come gestire i plug-in e gli script installati in Substance 3D Sampler per installare, modificare e rimuovere le estensioni personalizzate.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Manage installed plugins and scripts
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gestire i plug-in e gli script installati
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '499'
ht-degree: 0%

---


# Gestire i plug-in e gli script installati

Per installare, modificare o rimuovere i plug-in usa Modifica > Preferenze, quindi seleziona Plug-in e Script.

![](../assets/preferences-86.png)

Dal pannello Plug-in e Script potete attivare il pannello Registro che visualizza l’output dei plug-in. Ciò può risultare utile per la risoluzione dei problemi e il debug. Una volta attivato, potete aprire il pannello Registro dalla barra a destra nell’interfaccia principale di Sampler. Il pannello Registro può essere ancorato come gli altri pannelli di Sampler.

## Plug-in e script

La differenza principale tra plug-in e script è che i plug-in includono elementi dell&#39;interfaccia utente, a differenza degli script. I plug-in richiedono almeno un file PY e QML. Il file QML definisce gli elementi dell&#39;interfaccia utente, mentre il file PY definisce il comportamento del plug-in. Gli script, d&#39;altra parte, consistono solo in un file PY.

Gli elementi dell&#39;interfaccia utente di un plug-in consentono di modificare il comportamento del plug-in tramite l&#39;utilizzo di parametri. Ad esempio, il plug-in di salvataggio automatico di esempio dispone di controlli che consentono di modificare il tempo tra salvataggi automatici. I plug-in diventano parte dell&#39;interfaccia di Sampler e possono essere ancorati e spostati come pannelli standard di Sampler.

Gli script non consentono questo livello di flessibilità ma eseguono un&#39;attività specifica. Ad esempio, lo script Esporta tutto si comporterà sempre allo stesso modo ogni volta che viene chiamato. Dalla barra dei menu superiore è possibile accedere agli script: il menu Script diventa disponibile solo dopo aver aggiunto gli script in Sampler.

## Gestisci i plugin

Per impostazione predefinita, l&#39;unica opzione disponibile è &quot;Aggiungi un plug-in&quot;. Viene aperta un&#39;interfaccia Esplora file in cui è possibile selezionare un file PY da caricare.

![](../assets/manageplugins.png)

>[!NOTE]
>
> I plug-in richiedono sia un file PY che un file QML. Quando si seleziona un file PY da importare, Sampler cerca nella cartella un file QML. Se non viene trovato alcun file QML, il caricamento del plug-in non riuscirà.

Una volta installato un plug-in, diventano disponibili alcune opzioni:

* I plug-in possono essere riordinati trascinando la maniglia sul lato sinistro del plug-in.
* Attiva o disattiva i plug-in con l&#39;interruttore di attivazione/disattivazione.
* Utilizza il pulsante del menu a destra di ciascun plug-in per ricaricare, rimuovere o aprire la posizione della cartella del plug-in.

I plug-in installati verranno visualizzati inizialmente nella barra destra dell&#39;interfaccia principale di Sampler. Da lì è possibile aprire, ancorare e spostare il pannello dei plug-in proprio come i pannelli standard di Sampler.

## Gestione script

Gli script possono essere gestiti in modo simile ai plug-in.

![](../assets/managescripts.png)

Una volta installato uno script, diventano disponibili alcune opzioni:

* Riordinare gli script con la maniglia sul lato sinistro dello script.
* Attiva o disattiva lo script con l’interruttore.
* Utilizzare il pulsante di menu a destra di ogni script per rimuovere lo script oppure aprire la cartella in cui si trova lo script.
* Gli script importati vengono copiati in **%\AppData\Roaming\Adobe\Adobe Substance 3D Sampler\scripts**
* Per modificare lo script, dovete modificare quello copiato da Sampler
