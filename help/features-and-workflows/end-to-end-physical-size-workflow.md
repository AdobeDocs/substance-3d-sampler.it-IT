---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/end-to-end-physical-size-workflow.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il flusso di lavoro end-to-end dimensioni fisiche in Substance 3D Sampler per creare materiali fisicamente accurati che corrispondono alla scala reale.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > End to end Physical Size Workflow
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Flusso di lavoro end-to-end Dimensioni fisiche
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Flusso di lavoro end-to-end Dimensioni fisiche

Corrispondenza della dimensioni fisiche reale dei campioni e delle immagini scansionati in un contesto digitale per creare immagini fisicamente accurate tra le applicazioni.

## Importa scansioni

1. Selezionate il modello di creazione del materiale.
1. Selezionare la casella di controllo dimensioni fisiche.

   ![](../assets/screenshot-2022-01-20-at-16-15-53.png)
1. Due approcci per impostare la Dimensioni fisiche:

   3 bis. Fate clic su misura manuale (Manual measure) - Lo strumento Misura (Measure) consente di calibrare la dimensioni fisiche tra due feature del campione.\
   Traccia tra due punti -> Invio

   ![](../assets/screenshot-2022-01-20-at-16-31-26.png)

   3 ter. Misura automatica: lo strumento Misura automatica consente di ottenere una dimensioni fisiche stimata del campione in base ai metadati dell’immagine (dpi). È più veloce, ma funziona solo con le scansioni, poiché utilizza il valore dpi memorizzato per calcolare una dimensione iniziale precisa.

   <b>È ora possibile elaborare le scansioni</b>
1. Aggiungete un ritaglio e regolatelo sul campione. La dimensioni fisiche viene visualizzata nell&#39;angolo inferiore destro del riquadro di visualizzazione 2D aggiornato.

   Visualizza con rapporto fisico nella finestra della vista 2D per visualizzare con precisione le mappe su cui stai lavorando.\
   Potete impostare la vista 2D in modo che si adatti alla dimensioni fisiche in modo che il valore DPI delle proporzioni dello schermo corrisponda alla scala del materiale. In altre parole, potete posizionare il vostro campione reale accanto allo schermo per verificarne le dimensioni.

   ![](../assets/cq5dam.web.1280.png)
1. Aggiungete un valore di Equalizza per eliminare eventuali sfumature.
1. Aggiungere l’effetto Porzione per correggere l’aspetto della porzione
1. Se necessario, la trasformazione dell’alterazione è utile per riallineare solo alcune parti della mappa.

   <b>Pronto per l&#39;esportazione</b>
1. Esporta come

   Selezionate il formato Sbsar, in cui Sampler inserirà la Dimensioni fisiche come metadati. Consentirà anche ad altre applicazioni di leggere e utilizzare queste informazioni.\
   Potete anche esportare le immagini, nel rispetto delle proporzioni di dimensioni fisiche.

   Per utilizzare la dimensioni fisiche in qualsiasi momento, utilizzare il *pannello Dimensioni fisiche*.

   Durante l’esportazione come immagini, è ora possibile forzare le dimensioni delle immagini per rispettare le proporzioni della dimensioni fisiche.

## Esercitazione video

Potete inoltre trovare dei tutorial video per aiutarvi a superare questa funzione:
