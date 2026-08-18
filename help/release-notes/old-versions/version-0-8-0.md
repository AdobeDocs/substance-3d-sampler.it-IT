---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/release-notes/old-versions/version-0-8-0.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 0.8.0 per informazioni sulle nuove funzioni, gli aggiornamenti e i miglioramenti.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.8.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 0.8.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---


# Versione 0.8.0

**Aggiunto:**

* [Risorse] Collegare e eseguire il mirroring delle cartelle dei materiali sui dischi locali
* [Risorse] Sfoglia le cartelle dei materiali e le relative sottocartelle
* [Risorse] Scollegate il pannello delle risorse materiali in una finestra separata per visualizzare le risorse a schermo intero
* [Risorse] Nuovo layout del pannello Risorse per supportare la navigazione di cartelle e sottocartelle
* [Risorse] Utilizza il breadcrum per spostarti tra le cartelle
* [Resources] Forza la sincronizzazione della cartella locale con l&#39;opzione Sync accessibile tramite clic con il pulsante destro del mouse
* [Resources] Disconnettere la cartella locale con l&#39;opzione Disconnetti accessibile facendo clic con il pulsante destro del mouse
* [Gestisci] Visualizzazione dei tag incorporati nei file Substance
* [Gestisci] Aggiungi, modifica ed elimina i tag dei tuoi materiali
* [Gestisci] Valuta i tuoi materiali
* [Layers] Supporta l’output Panorama
* [Livelli] Puoi eliminare gli input di immagine nel livello Importazione immagine
* [Livelli] Selezione automatica del nuovo livello aggiunto
* [Livelli] Selezione automatica del livello sottostante dopo l’eliminazione di un livello
* [UX] Mantenere la visibilità dei pannelli a sinistra quando si passa a un altro Lab
* [UX] Non creare un livello base o non aprire il menu a comparsa Flusso di lavoro materiale durante l’importazione di immagini in una serie di livelli non vuoti
* [UI] Nuovo stile campo di testo
* [UI] Nuovo stile SearchBox
* [UI] Nuovo stile di intestazione del pannello
* [UI] Nuovo stile indicatore Occupato
* [UI] Nuovo stile di sfondo della serie di livelli
* [UI] Usa font Adobe Clean
* [UI] Rimuovi il segnaposto dell&#39;icona del contagocce del parametro di input colore
* [Prestazioni] Ottimizzazione indicatore di attività
* [Contenuto] Nuovo filtro Generatore pattern
* [Content] Nuovo filtro Sfocatura

**Corretto:**

* [Ispirazione] Risolvere l&#39;arresto anomalo quando si utilizzano più di 10 colori
* [Vista 2D] Correggere la barra di scorrimento nell&#39;elenco dei canali della vista 2D
* [Visualizzatore] Correggere l&#39;arresto anomalo durante l&#39;importazione di una mappa dell&#39;ambiente non alimentata a 2
* [Content] Correggi importazione PNG per pattern personalizzato di filtri in rilievo e perforazione
* [Esporta] Correggi normale e height 16 bit per esportazione canale
* Correggi un ciclo infinito durante l&#39;importazione di un materiale con due predefiniti con lo stesso nome
* Correggere la visualizzazione del percorso lungo del file nel livello Materiale di base

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al height può bloccarsi su MacOS
* Può verificarsi un arresto anomalo casuale quando si esce da MacOS
