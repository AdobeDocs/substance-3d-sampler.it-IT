---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/processing-advanced-3d-captures.html"
breadcrumb-title: ''
description: Scoprite come elaborare le acquisizioni 3D avanzate in Substance 3D Sampler per ottimizzare la geometria, le texture e la qualità del materiale.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Elaborazione di acquisizioni 3D avanzate
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1339'
ht-degree: 0%

---


# Elaborazione di acquisizioni 3D avanzate

>[!WARNING]
>
> Il supporto per capture 3D è stato rimosso dalla versione 5.1 di Sampler.

## Elaborazione di acquisizioni 3D avanzate in Substance 3D Sampler

In questa guida utente esamineremo l’elaborazione dei dataset di profondità in Substance 3D Sampler.

Preferisci guardarlo come un tutorial video? Puoi trovarlo [qui](https://youtu.be/vJQ756Up55Y?si=GiAnajXRGkb5gyTH "Capture 3D avanzato - Esercitazione sull’elaborazione delle acquisizioni").

![](../assets/cloud-points-3d-capture.png)

Quando si esegue una Capture 3D o una fotografia, la maggior parte dell&#39;impegno consiste nell&#39;acquisire fotografie corrette, i passaggi descritti negli articoli precedenti della guida utente. Inoltre, tenete presente che abbiamo progettato e focalizzato l&#39;esperienza di Capture 3D per oggetti fino alla dimensione umana. Potresti riscontrare problemi quando utilizzi un set di dati molto grande (che significa sopra 6 Giga pixel, che è 500 foto 12 Megapixel).

## Avvio del processo di capture 3D

Per iniziare in Sampler, dovrai creare un <b>nuovo progetto</b>. Vedrai una nuova sezione Oggetti 3D nella finestra Progetti. Fai clic sul segno + accanto a questo e scegli &quot;<b>Nuovo oggetto 3D</b>&quot; per iniziare a utilizzare il capture 3D in una nuova finestra dedicata.

![](../assets/new-capture-3d-capture.png)

Seleziona tutte le foto nell&#39;esploratore e trascinale sulla finestra di capture 3D. Dopo un breve caricamento, le foto vengono presentate in un elenco e come galleria, con le proprietà per la selezione a destra.

L’elenco dei gruppi di foto a sinistra si basa sulla fotocamera e sull’obiettivo utilizzati per le foto. Se mescoli foto da più dispositivi, come un cellulare, una fotocamera dslr o un drone, qui riceverai <b>gruppi separati</b>.

Con il gruppo selezionato, viene visualizzata una panoramica delle sue proprietà. A volte le <b>Lunghezza focale</b> e le <b>Dimensioni sensore</b> risultano mancanti; è possibile compilarle <b>manualmente</b> se si conoscono i numeri. Queste informazioni possono contribuire a migliorare leggermente l’elaborazione.

## Generazione delle maschere

L&#39;opzione più importante si trova nella sezione <b>Maschera</b>. Poiché le foto sono state scattate su un giradischi, lo sfondo non è cambiato molto, ma l&#39;oggetto sì. Ciò può causare il fallimento completo del processo di allineamento. Per di più, lo sfondo non contiene affatto informazioni significative. Per risolvere questo problema, dovrete mascherare il soggetto di ogni foto.

Il modo più semplice consiste nell&#39;utilizzare la generazione automatica dei batch. Selezionate <b>Genera</b>, quindi <b>Nuovo batch</b> e attendete che Sampler crei le maschere. Questo utilizza la tecnologia Adobe Sensei &quot;Select subject&quot; (Seleziona soggetto), proprio come in Photoshop. Con 72 foto questo processo richiede un po&#39; di tempo per essere completato, quindi è meglio essere pazienti.

![](../assets/generate-mask-3d-capture.png)

Puoi verificare una singola maschera <b>selezionando una foto</b> e facendo clic sull&#39;<b>icona a forma di occhio</b> in basso a destra, accanto al tracciato della maschera. Mostra un’anteprima in scala di grigio della maschera. Se la mascheratura automatica fa un errore e mantiene parti dello sfondo, non preoccupatevi, alcune maschere errate non sono un problema.

La maggior parte delle maschere dovrebbe avere solo il soggetto. Ecco perché è fondamentale scattare foto su uno <b>sfondo uniforme e uniforme</b>; per il corretto funzionamento della mascheratura automatica è molto più semplice. Se la maggior parte delle maschere non è corretta, potete correggerle tutte manualmente o riprendere le foto con uno sfondo più adatto.

Potresti riprovare a creare un set di dati più volte e vuoi evitare di ricreare le maschere ogni volta, poiché Sampler le elimina una volta chiusa l&#39;app. Le maschere vengono memorizzate nella cache in Documents\Adobe\Adobe Substance 3D Sampler\3DCapture\p1. Se fai più risorse in una sessione, otterrai cartelle denominate p2, p3, ecc. Si consiglia di <b>copiare le maschere memorizzate nella cache in un luogo sicuro insieme al set di dati</b>, in modo da risparmiare tempo se è necessario rivedere il set di dati.

## Allineamento

Con le maschere corrette, siete pronti per procedere con l’allineamento. Premi il <b>pulsante blu per inviare</b> in alto a destra. Avrai a disposizione due opzioni: <b>Precision</b> e <b>Ordinamento foto</b>.

* <b>Precision</b> può migliorare l&#39;allineamento: è meglio iniziare da Bassa. Se si verificano errori nelle foto, riprovate con Alta.
* <b>L&#39;ordine delle foto</b> si riferisce all&#39;ordine con cui avete scattato le foto. Se avete camminato intorno a un oggetto e scattato in cerchi a spirale, potete scegliere una sequenza per risparmiare tempo, ma di solito l&#39;impostazione predefinita è l&#39;opzione più sicura, anche se l&#39;allineamento potrebbe richiedere un po&#39; più di tempo.

Fai clic su <b>Elabora</b> e attendi il completamento dell&#39;allineamento. Questo può richiedere diversi minuti, quindi è meglio essere di nuovo pazienti. Al termine, vedrete una rappresentazione point cloud del vostro oggetto, con ogni foto rappresentata come una fotocamera che vi galleggia intorno. Un triangolo arancione di avvertenza in alto a sinistra indica che <b>alcune foto non sono state allineate</b>. Se non lo hai già fatto, ritorna e prova con Precisione di alta qualità e Ordine predefinito. Alcune foto potrebbero ancora non essere allineate, significa che la sovrapposizione non è sufficiente o che i dettagli non sono sufficienti. Per risolvere il problema, dovrete riesaminare il processo di fotografia o ignorarlo se si tratta di poche foto.

Esaminando i tuoi dati point cloud, potresti vedere <b>punti isolati fluttuare intorno al tuo oggetto</b> che non dovrebbero farne parte. Questo di solito è dovuto ad alcune maschere cattive, in questo caso alcune maschere cattive hanno fatto sì che riprendesse su alcune particelle di dust. Puoi ritagliarli<b>utilizzando l&#39;icona a forma di occhio a destra accanto a Area di interesse. </b>È sufficiente <b>spostare le maniglie quadrate</b> che sembrano più vicine all&#39;oggetto. Eventuali punti all’esterno di questa casella, visualizzati in grigio scuro, non verranno inclusi nel modello 3D finale. Puoi anche utilizzare questo rettangolo di selezione per <b>pre-ruotare e allineare meglio il modello.</b>

A volte le nuvole di punti hanno punti molto più densi di altri. Non è un problema, meno punti significa che la superficie avrà meno piccoli dettagli geometrici. Deriva dalla mancanza di dettagli e contrasto in alcune parti dell&#39;oggetto, mentre altre hanno più dettagli.

## Dettagli della geometria

Rimane solo un’impostazione prima della creazione della trama. In Dettagli geometria (geometry details) potete selezionare il livello di dettaglio della geometria iniziale.

* <b>Raw</b> è il <b>mes non decimato</b>h. In realtà non è consigliabile utilizzarlo a meno che tu non sia sicuro di averne bisogno.
* <b>Completo fino alla bozza</b> è costituito da <b>trame decimate</b>. È possibile scegliere opzioni inferiori per ottenere un risultato di test più rapido, opzioni superiori per ottenere maggiori dettagli a scapito di un&#39;elaborazione più lenta.

Premi <b>Invia per avviare l&#39;elaborazione della trama</b>. Questo processo può richiedere un po&#39; di tempo, più a lungo di qualsiasi altro passaggio precedente.

## Anteprima e post-elaborazione

Una volta completata la trama, la finestra finale ci consente di visualizzare in anteprima e post-elaborare la trama prima di aggiungerla al nostro progetto Sampler. Questa modalità ha alcuni pulsanti nella parte inferiore per visualizzare la trama con <b>texture</b>, <b>tinta unita ombreggiata</b>, come <b>wireframe</b> e con un <b>materiale per il controllo UV</b>. Le impostazioni di post-elaborazione sul lato consentono di generare una nuova versione della trama. Ciò significa una trama ri-tassellata, con nuovi UV automatici e texture ricavata dalla trama originale. I controlli principali consentono di impostare un numero di facce di destinazione e di attivare/disattivare la funzione di cottura normale, di height e automatica. Ci sono molte impostazioni avanzate da modificare, ma le impostazioni predefinite di solito funzionano bene.

Potete anche eseguire questo passaggio di elaborazione della trama in seguito, una volta che la trama è stata aggiunta a Sampler. Una volta aggiunto a Sampler, puoi assegnargli un nome; ora viene visualizzato nell’elenco dei progetti.

Puoi modificare la trama e le texture, ma puoi già esportare il risultato utilizzando la <b>Condividi</b> > Finestra di dialogo <b>Esporta come</b>. Le <b>impostazioni generali</b> consentono di scegliere nome e percorso, le <b>impostazioni trama</b> consentono di scegliere il formato trama 3D e le <b>impostazioni materiale</b> consentono di configurare il materiale della trama. Potete disattivare la trama o il materiale per esportarne solo uno singolarmente. Una volta esportata, la trama è pronta per essere utilizzata in altre applicazioni 3D.

Scopri come [modificare ulteriormente le trame 3D acquisite in Sampler](editing-3d-captured-meshes.md).
