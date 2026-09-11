---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/release-notes/old-versions/version-0-7-0.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 0.7.0 per informazioni su aggiornamenti, miglioramenti e correzioni di bug.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.7.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 0.7.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Versione 0.7.0

Data di pubblicazione: **2019/06/13**

Aggiunto:

* [Filtri] Accedi rapidamente ai filtri premendo la barra spaziatrice
* [Filtri] Nuovo pannello dedicato per gestire, sfogliare e importare i filtri
* [Metadati] Fate clic con il pulsante destro del mouse su un materiale per visualizzarne i metadati
* [Metadati] Fate clic con il pulsante destro del mouse su un materiale per visualizzarne la posizione sul disco
* [Cursori] Animate i cursori quando li passate con il mouse premendo Ctrl
* [Cursori] Interrompi e riavvia l’animazione dei cursori premendo il tasto P
* [Esportazione] L’esportazione SBSAR è conforme alle linee guida Substance Source
* [Licenza] Attivare Substance Alchemist utilizzando una variabile di ambiente
* [UX] La finestra di dialogo File ricorda l&#39;ultimo percorso file selezionato
* [UX] La finestra di dialogo Cartella ricorda l&#39;ultimo percorso cartella selezionato
* [UI] Aggiornamento dell’interfaccia utente del pannello Risorse
* [UI] Aggiorna interfaccia utente della barra di ricerca
* [UI] L’icona Crea nuovo materiale è stata aggiornata
* [Guida] URL aggiornati al dominio [substance3d.com](http://substance3d.com)
* [Trama] Ora è disponibile una trama in tessuto
* [Contenuto] Nuovo filtro per corrosione
* [Content] Nuovo Filtro Ossidazione
* [Content] Nuovo filtro Moss
* [Content] Nuovo filtro Dust
* [Contenuto] Nuovo filtro pattern Brickwall
* [Contenuto] Nuovo filtro pattern Stonewall
* [Content] Nuovo filtro finitura legno
* [Content] Nuovo filtro finitura Metal
* [Content] Nuovo filtro Snow
* [Content] Nuovo filtro casuale
* [Contenuto] Ora puoi importare la texture direttamente nel filtro Materiale di base

Fisso:

* Correggere un arresto anomalo durante il salvataggio della Pila livelli
* È possibile aggiungere un valore superiore a 1 nel cursore di rotazione dell’ambiente
* Non perdere i parametri di fusione quando un livello di fusione viene Trasforma avanti e indietro dal livello di fusione al livello di materiale
* Correggere i duplicati quando si generano più volte variazioni della stessa Pila livelli
* Quando riapri un materiale, Alchemist memorizza gli intervalli modificati (min e max) dei cursori

Problemi noti:

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al height può bloccarsi su MacOS
