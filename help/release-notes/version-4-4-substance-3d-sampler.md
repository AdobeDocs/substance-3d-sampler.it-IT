---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-4substance-3d-sampler.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 4.4 per scoprire i flussi di lavoro generativi, tra cui le funzionalità di conversione da testo a texture e da immagine a texture.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 4.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---


# Versione 4.4

<b>Substance 3D Sampler 4.4</b> introduce tre nuovi flussi di lavoro generativi come beta: Text-to-texture, Text-to-pattern e Image-to-texture.

<b>Le funzioni di intelligenza artificiale generativa sono disponibili solo in Adobe versione</b> poiché richiede un account di Adobe. Pertanto, queste funzionalità non sono <b>disponibili su Steam</b>.

*Data di pubblicazione: 23 maggio 2024*

## Text-to-texture

![](../assets/textToTexture_whatNewPanel.png)

La conversione da testo a texture ti consente di esplorare un nuovo modo di creare materiali con un <b>prompt di testo</b>. Potete generare una texture su piastrelle da una descrizione di testo dettagliata e continuare a sviluppare il risultato tramite il filtro Da immagine a materiale o qualsiasi filtro Sampler per renderlo personalizzato.

## Image-to-texture

![immagine-texture](../assets/imagetoText_whatNewPanel.png "Immagine-texture")

Con il metodo Immagine-Texture puoi creare texture quadrate affiancate da <b>la tua immagine di riferimento</b>, indipendentemente dal fatto che sia non quadrata e non affiancata. In questo modo si ottiene più vicino ai risultati desiderati senza dover scrivere il prompt perfetto.\
La conversione da immagine a texture consente inoltre di risparmiare tempo creando variazioni dai contenuti già creati.

## Text-to-pattern

![immagine illustrazione da testo a pattern](../assets/patterns_whatNewPanel.png)

La funzionalità Text-to-pattern utilizzerà il tuo <b> prompt di testo</b> per generare un pattern di porzioni quadrate. Puoi quindi utilizzarlo come colore di base con un filtro Tessuto tessuto per creare un materiale di tessuto originale, usarlo come input di un filtro Pattern e altro ancora!

## Nota di rilascio

*(Rilasciato il 23 maggio 2024)*

<b>Aggiunto</b>:

* La cache di capture 3D di [Application] è ora memorizzata in una sottocartella separata
* [Intelligenza artificiale generativa] Da immagine a texture (Beta)
* [Intelligenza artificiale generativa] Da testo a pattern (beta)
* [Intelligenza artificiale generativa] Da testo a texture (Beta)
* [Scripting] Le risorse ora hanno una proprietà &quot;resource&quot;
* [Scripting] I livelli ora hanno una proprietà &#39;output\_usages&#39;

<b>Corretto:</b>

* [Applicazione] Arresto anomalo all’apertura di un file di progetto danneggiato
* [Applicazione] Arresto anomalo quando il progetto contiene risorse danneggiate
* [Applicazione] Arresto anomalo quando si scollega un monitor su Windows
* [Applicazione] Icona applicazione errata nella barra delle applicazioni di Windows
* [Applicazione] Il danneggiamento del file di configurazione principale può provocare l&#39;eliminazione dei file
* [Applicazione] I pannelli vengono visualizzati davanti ai popup
* [Content] I generatori di texture hanno miniature sfocate
* [Esportazione] Il canale di opacità generato da un’immagine importata si interrompe durante l’esportazione di un file .sbs/.sbsar
* [Filtri] L’ingrandimento può arrestarsi in modo anomalo a seconda dei livelli di input
* [Intelligenza artificiale generativa] Possibili arresti anomali durante la ricezione di risultati imprevisti dal servizio
* [Scripting] Arresto anomalo durante il caricamento automatico di un plug-in dalla variabile di ambiente
* [Scripting] Possibile arresto anomalo durante l’assegnazione dell’utilizzo dell’output con l’API
