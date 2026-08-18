---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/your-first-capture-step-by-step.html"
breadcrumb-title: ''
description: Scopri come eseguire il tuo primo Capture 3D utilizzando HP Z Captis in Substance 3D Sampler con istruzioni dettagliate.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: La tua prima acquisizione passo dopo passo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '1267'
ht-degree: 0%

---


# Avvia Sampler e attiva HP Z Captis

Una volta avviato Sampler e collegato il dispositivo HP Z Captis al computer, fai clic sull’icona Captis/cone sulla barra a sinistra.

Se nell&#39;interfaccia utente non vengono visualizzati i sottotitoli HP Z Captis, fare riferimento alle domande frequenti.

![Fare clic sull&#39;icona più e su HP Z Captis in Sampler per avviare il dispositivo](../../assets/5_1.png)

Dopo aver fatto clic su HP Z Captis, si apre una finestra dedicata con 3 opzioni:

1. <b>Sfoglia contenuti</b>: verrà aperta la finestra di dialogo Esplora file per esplorare lo spazio di archiviazione locale del dispositivo HP Z Captis.
1. <b>Avvia la scansione</b>: inizializzerà il dispositivo HP Z Captis e avvierà il flusso di acquisizione.
1. <b>Arresto</b>: il dispositivo verrà arrestato e la finestra verrà chiusa.

![](../../assets/captis-captis-welcome-window.png)

## Chiusura della finestra HP Z Captis

In qualsiasi momento, se si chiude la finestra HP Z Captis, verrà chiesto se si desidera <b>continuare il processo</b> o <b>interrompere</b>.

Se si seleziona Continua, il dispositivo procederà con l&#39;operazione corrente offline e si interromperà alla fine del passaggio corrente. È possibile ricollegare Sampler in un secondo momento per passare al passaggio successivo della sessione di acquisizione.

![](../../assets/captis-abort-capture.png)

## Passaggio di anteprima

Sampler inizializzerà l&#39;anteprima del dispositivo HP Z Captis. Si consiglia di <b>non interagire </b> con la visualizzazione durante l&#39;inizializzazione.

In questo nuovo aggiornamento sono disponibili due modalità: Automatica e Manuale.

### Impostazioni generali

#### Modalità automatica

![Modalità automatica Captis](../../../help/assets/sampler_captis-default-interface.png)

Ora è possibile avviare l’acquisizione con un solo clic: Sampler:

* definire un nome di default,
* definire automaticamente la zona di area di interesse (ROI)/ritaglio utilizzando la retroilluminazione,
* focalizzare l&#39;attenzione sul ROI completo, e
* modifica l’impostazione dell’intensità impostandola su una adatta al materiale.

Se le acquisizioni sono state effettuate in precedenza, la categoria del materiale, gli output e la risoluzione di acquisizione selezionati saranno gli stessi dell&#39;acquisizione precedente.

#### Modalità manuale

![Flusso di lavoro Captis in modalità manuale Substance 3D Sampler](../../../help/assets/sampler_captis-manual-mode.png)

Potete anche scegliere di definire manualmente alcune impostazioni:

*Nome progetto*

Potete definire il nome di un progetto di acquisizione e il tipo di output da recuperare.

*Output*

* Per impostazione predefinita verranno salvati solo i canali PBR del materiale (Colore base, Normale, height e Opacità).\
  È possibile scegliere il tipo di output tra LDR (low dynamic range) e HDR (high dynamic range).


*Risoluzione acquisizione*

* 239 px/in - 94 px/cm (anteprima: qualità inferiore, scansione più rapida)
* px/in - 142 px/cm (impostazione predefinita: alta qualità, facilità di gestione nella maggior parte dei flussi di lavoro, equivalente a 4k per l&#39;acquisizione di 30x30cm)
* 718 px/in - 284 px/cm (risoluzione massima, equivalente a 8k per l&#39;acquisizione di 30x30 cm)

![Risoluzioni di acquisizione nel flusso di lavoro di Captis e Sampler](../../../help/assets/sampler_captis-capture-resolution-6.0-1.png)
Nota: in Sampler verranno caricati solo i canali PBR.\
Le cartelle di default in cui vengono salvate le acquisizioni possono essere modificate nelle preferenze.


<b>Categoria materiale</b>

Impostate questa opzione sul tipo di materiale che state scansionando per la generazione di mappe ottimizzate in base al materiale specifico.\
La categoria predefinita selezionata è &quot;Fabric&quot;. Contribuirà a ottimizzare il risultato del canale di rugosità.

Se la scansione contiene diversi tipi di materiali, selezionare la categoria del più grande.

<b>Ritaglio</b>

Il ritaglio può essere eseguito automaticamente o manualmente.

![colture potenziali della regione di interesse, tra dimensioni fisiche e dimensione delle piantine](../../assets/captis-51-crop.png)

Il ritaglio automatico utilizza la retroilluminazione per definire il contorno del materiale e posiziona l’Area di interesse (ROI) attorno ad esso. Non viene adattato quando si digitalizzano più campioni di materiale contemporaneamente o quando il materiale è molto trasparente.
In tal caso, il ROI può essere definito trascinando gli angoli del widget di ritaglio nell’anteprima o impostando una risoluzione o una dimensioni fisiche definita.

<b>Impostazioni fotocamera </b>

* Intensità: consente di regolare l’esposizione della videocamera.\
  Facendo clic su Automatico si utilizzerà il centro del ROI per definire l’intensità migliore per il materiale.

* Messa a fuoco: consente di regolare la messa a fuoco della videocamera.\
  Facendo clic su Automatico si definisce la messa a fuoco ideale utilizzando il ROI completo.
  Questo nuovo algoritmo di messa a fuoco, che non mette più a fuoco un singolo punto, consente di mettere a fuoco il materiale digitalizzato in modo più uniforme, fornendo scansioni di qualità superiore che sono più facili da affiancare.

Se preferisci, puoi impostare entrambi a mano.

<b>Altre impostazioni</b>

Altri tipi di impostazioni<b> devono essere modificati solo in occasione</b>: la calibrazione del colore e dell&#39;allineamento.

![Calibrazione degli HP Z Captis in Substance 3D Sampler](../../../help/assets/sampler_captis-calibration.png)

* Calibrazione colore

Calibra il colore della mappa dei colori di base grazie alle aree tecniche di HP Z Captis. \
In questo modo il materiale finale sarà esattamente dello stesso colore del campione aggiunto nell&#39;area HP Z Captis.\
Le aree tecniche con i campioni di colore vengono rilevate automaticamente e utilizzate per la calibrazione. Essi devono essere collocati nel loro spazio specifico su ciascun lato del campione.

È disponibile solo in modalità Studio. Prima di eseguire la calibrazione del colore, assicurati di mettere a fuoco.

Questa calibrazione deve essere eseguita <b>ogni pochi mesi</b>. Non è necessario farlo per ogni scansione o ogni volta che si utilizza il dispositivo.

* Calibrazione dell&#39;allineamento

Questo allineamento <b>deve essere eseguito</b> la <b>prima volta che configuri il tuo dispositivo</b>, ogni volta che lo sposti fisicamente e poi ogni due mesi. <b>non è necessario</b> eseguire questo processo <b>per ogni acquisizione</b>.

Assicuratevi di eseguire la messa a fuoco prima di questa calibrazione dell&#39;allineamento.

Per effettuare l&#39;allineamento, <b>posizionare qualcosa con informazioni chiare e nitide, come un pezzo di carta con testo stampato, al centro dello spazio di acquisizione</b>, chiudere il riquadro e fare clic sul pulsante di allineamento. Una volta fatto questo, è possibile assicurarsi che tutto sia in posizione, con le aree tecniche in loro posizione su ogni lato dello spazio di scansione, un materiale posizionato al centro e, se necessario, tenuto in posizione con i magneti forniti con il dispositivo HP Z Captis, e si può iniziare la scansione dei materiali.

Una volta impostati tutti gli elementi: <b>avviare la scansione</b>.


## Passaggi di acquisizione, elaborazione e copia

Una volta avviata la scansione, l’anteprima mostrerà le foto scattate durante il processo.

La parte di lavorazione è suddivisa in tre parti:

* <b>Acquisizione</b>: scattare tutte le foto necessarie

* <b>Elaborazione</b>: elaborazione delle foto per generare i canali PBR (colore di base, normale, height, opacità)

* <b>Copia in corso</b>: copia dei risultati dal dispositivo HP Z Captis nel computer

Durante l’acquisizione e l’elaborazione, potete aggiungere i metadati (gli stessi che si trovano nel pannello Metadati di Sampler).

![Acquisizione del passaggio](../../../help/assets/sampler_captis-capturing.png)

Durante l&#39;elaborazione, vedrai il risultato generato affiancato per affiancato.

## Passaggio di riepilogo

![Fase di riepilogo del processo di digitalizzazione con Sampler e Captis](../../../help/assets/sampler_captis-summary.png)

In questa fase è possibile esaminare i risultati della scansione. Vengono visualizzati tutti i canali creati (in modalità Esplora risorse, non viene creata alcuna opacità poiché l&#39;anello dell&#39;esploratore non dispone di retroilluminazione).

Puoi scegliere di inviare il materiale a Sampler, di aggiungerlo al tuo progetto e di iniziare a elaborarlo.
Potete inoltre avviare direttamente una nuova acquisizione senza aggiungerla al progetto.
In entrambi i casi, le mappe acquisite si trovano nella cartella equivalente sul computer: C:\Users\username\Documents\Adobe\Adobe Substance 3D Sampler\Captis\Material

## Edizione dei materiali

Dopo essere usciti dalla finestra HP Z Captis, i canali (colore di base, normale, height, rugosità e opacità, se pertinente) verranno aggiunti come livello nel pannello Livelli.

![testo alternativo](../../../help/assets/sampler_captis-imported-material.png)


Usa i filtri di Sampler (Equalizza, Ritaglio prospettiva, Divisione in porzioni, ...) per elaborare e pulire il materiale.

Una volta completata l’operazione, puoi:

* Salva il progetto Sampler: File > Salva con nome ... (Ctrl + S)

* Esportate il materiale: File > Esporta ... (Ctrl + E)

