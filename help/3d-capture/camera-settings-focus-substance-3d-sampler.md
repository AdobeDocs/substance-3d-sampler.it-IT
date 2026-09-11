---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/camera-settingsfocussubstance-3d-sampler.html"
breadcrumb-title: ''
description: Scoprite come configurare le impostazioni di messa a fuoco della fotocamera in Substance 3D Sampler per una qualità del Capture 3D ottimale e una nitidezza dell'immagine ottimale.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni fotocamera - Punto di interesse
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---


# Impostazioni fotocamera - Punto di interesse

>[!WARNING]
>
> Il supporto per capture 3D è stato rimosso dalla versione 5.1 di Sampler.

## Impostazioni fotocamera - Messa a fuoco

<b>L&#39;apertura</b> è l&#39;impostazione della fotocamera più complessa, quindi in questa guida utente la spiegheremo nella profondità.

Preferisci guardare questa guida come esercitazione video? Puoi trovarlo [qui](https://youtu.be/kFZ71ZWuap0?si=MDuvyO9w96rFpsQ9 "esercitazione su apertura e messa a fuoco per video Capture 3D").

![](../assets/focus-manually-3d-capture.png)

## Messa a fuoco di un obiettivo

Per impostazione predefinita, il sistema di messa a fuoco automatica della fotocamera controlla questa impostazione, impostando la messa a fuoco automaticamente. Questo ha senso quando si fotografano persone, ambienti di grandi dimensioni o qualsiasi cosa dinamica, ma per il nostro soggetto statico e controllato potrebbe anche causare problemi; l&#39;autofocus può commettere errori e rovinare una foto, anche tra due scatti.

Ogni DSLR può passare dalla messa a fuoco automatica a un <b>fuoco manuale</b> completo. Ciò significa che si ha il pieno controllo della messa a fuoco, girando l&#39;anello di messa a fuoco sull&#39;ottica. In questo modo avrete la certezza che la messa a fuoco non si sposterà tra le riprese. Se leggete il manuale della fotocamera, probabilmente vi saranno impostazioni utili, come &quot;focus peaking&quot;, in cui viene disegnato un effetto colorato sul display della fotocamera. Questo aiuta a vedere quale parte dell&#39;immagine è a fuoco. Potrebbe anche esserci una lente di ingrandimento dello zoom, in cui il display mostra una piccola parte esagerata della visualizzazione corrente, aiutandoti a ottenere una messa a fuoco perfetta per i pixel. Specialmente questa lente di ingrandimento è fondamentale per rendere più nitida la messa a fuoco.

L&#39;utilizzo della messa a fuoco manuale ti aiuterà a vedere e capire meglio cosa succede con l&#39;apertura <b></b> e la <b>messa a fuoco</b>. L&#39;aspetto negativo è che dovete <b>regolare la messa a fuoco ogni volta che la fotocamera o il soggetto si sposta</b>. È facile dimenticare e rovinare una foto, quindi è meglio prendere l&#39;abitudine di controllare.

## Scelta del valore di apertura

<b>L&#39;apertura</b> è complessa perché influisce sulla <b>messa a fuoco</b> e sulla <b>nitidezza</b>. Non vogliamo che alcune parti del nostro soggetto siano sfocate, questo causa problemi al processo di fotogrammetria. Ciò significa che un&#39;apertura ampia, solitamente tra f1.8 e f3.5 per gli obiettivi standard, sarà un problema. D&#39;altra parte, anche andare con la più piccola apertura possibile, f/32 non è granché, le cose diventano meno nitide anche da questo punto di vista, e la quantità di luce che entra è minima, portando a problemi di scarsa illuminazione.

Mentre la profondità di campo si amplia con aperture più piccole, si ridimensiona anche con la distanza focale. Ciò significa che avrai una maggiore profondità di campo da vicino e molto meno, fino a una nitidezza completa, più lontano. Questo può essere problematico per gli oggetti di piccole dimensioni, se volete che occupino la maggior parte della foto.

Qual è quindi il valore di apertura corretto? Di regola, individuate l’intervallo di apertura più nitido per l’obiettivo e iniziate con questo valore. Questo valore è probabilmente <b> F8 o f11, fino a f16</b>.  Controlla se <b>tutto è a fuoco</b>. In caso contrario, riduci passo dopo passo fino a f20 o giù di lì. Se l&#39;oggetto non è ancora completamente a fuoco, provate a spostarvi un po&#39; più lontano da esso. Anche una distanza di 10-15 cm può fare la differenza per gli oggetti piccoli.

Inoltre, tieni presente che la tua scelta di obiettivo può fare la differenza. Gli obiettivi kit forniti con una fotocamera solitamente non sono nitidi o di alta qualità, e vale la pena investire in un obiettivo di qualità superiore. Specialmente per le riprese da vicino, gli obiettivi macro possono essere utili, in quanto permettono di mettere a fuoco molto più vicino all&#39;obiettivo.

## Messa a fuoco tra parentesi

Puoi fare un trucco speciale per ottenere una nitidezza perfetta quando tutto il resto fallisce. <b>Il bracketing della messa a fuoco</b> consente di scattare <b>più foto</b> a <b>diverse distanze di messa a fuoco</b> e di combinarle in Photoshop. Richiede <b>molto lavoro in più</b>, soprattutto con la serie a ciclo intero, quindi deve essere utilizzato solo come ultima risorsa.

Se avete 2 o più fotografie con diverse aree di interesse, caricatele in livelli diversi.

![](../assets/focus-differences-3d-capture.png)

Seleziona tutti i livelli e passa a <b>Modifica</b> > <b>Allineamento automatico livelli</b>. Premi OK con le impostazioni predefinite. Photoshop proverà a eseguire un allineamento con perfezionamento pixel di tutti i livelli selezionati

Passa quindi a <b>Modifica</b> > <b>Fusione automaticamente livelli</b>. Di nuovo, scegli ok con tutte le impostazioni predefinite. Photoshop fonderà insieme le parti più nitide dei livelli.

Se tutto è andato bene, ora avete una fotografia perfettamente nitida. Vale la pena trasformare almeno alcuni di questi passaggi in un&#39;azione registrata, per farti risparmiare un po&#39; di tempo.

Ora che hai imparato tutto quello che c&#39;è da sapere su Aperture e Focus per il processo di Capture 3D, scopri di più su [come creare un&#39;illuminazione ideale](3d-capture-lighting-substance-3d-sampler.md).
