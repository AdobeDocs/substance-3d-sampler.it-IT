---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Utilizza lo strumento Da immagine a materiale in Substance 3D Sampler per convertire singole immagini in materiali completamente PBR utilizzando un'elaborazione basata sull'intelligenza artificiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Image To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Da Immagine A Materiale
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---


# Da Immagine A Materiale

![](../../assets/sat-icon-image-to-material.png)

Il modello **Da immagine a materiale** consente di generare un materiale PBR di alta qualità da una singola immagine di input.

Questo modello dispone di due algoritmi principali:

* **Basato sull&#39;intelligenza artificiale**
* **B2M**

Per una spiegazione dettagliata di ciascun algoritmo, vedere di seguito.

## Esempio

Di seguito è riportato un esempio di canali di materiale generati da una singola immagine di input:

![](../../assets/sat-image-to-material.jpg){width="500px"}

## Algoritmi

Per modificare l&#39;algoritmo del modello **Immagine in Materiale**, fare clic sul menu a discesa sotto il nome del modello:

![](../../assets/image-to-material-algo-setting.png)

### Basato su IA

L&#39;algoritmo <b>AI Powered</b> utilizza l&#39;apprendimento automatico per riconoscere forme e oggetti e generare accuratamente mappe, Normali, di Height e di rugosità, nonché per eliminare l&#39;albedo da qualsiasi ombra o luce.

La rete neurale è stata addestrata su un&#39;ampia gamma di materiali come tessuti, sostanze organiche, interni e superfici esterne.

>[!NOTE]
>
> Il calcolo da immagine a materiale (basato su IA) richiederà più tempo per le immagini ad alta risoluzione. Per ottimizzare il flusso di lavoro durante il lavoro, si consiglia di utilizzare il sistema [Layer Resolution](../../interface/preferences/layer-resolution.md).

### B2M

L&#39;algoritmo **B2M** utilizza il metodo Bitmap to Material basato su Substance per generare più canali quali colore di base, normale, metallico, rugosità e occlusione ambientale utilizzando tecniche procedurali.

Questo algoritmo può produrre risultati meno precisi ma funziona su una gamma più ampia di immagini di input.

## Adobe Capture

Questa funzionalità è disponibile anche sull’app mobile Adobe Capture (Android e iOS). Puoi scattare una foto in mobilità e ottenere un&#39;anteprima del risultato direttamente sul telefono.

Invia facilmente i risultati a Substance 3D Sampler per ulteriori edizioni.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> Questa funzionalità è disponibile solo con un abbonamento ad Substance 3D Collection.
