---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/auto-tiling.html"
breadcrumb-title: ''
description: Usa lo strumento Affiancamento automatico in Substance 3D Sampler per creare automaticamente pattern di Affiancamento uniformi dalla texture utilizzando la tecnologia IA.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Affiancamento automatico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '575'
ht-degree: 0%

---


# Affiancamento automatico

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il <b>filtro Porzione automatica</b> cerca strutture ripetitive nel materiale e le utilizza per creare un materiale di affiancatura. A differenza del <b>filtro Sezione</b> o del <b>filtro Affiancamento</b>, l&#39;<b>Affiancamento automatico</b> è incentrato sull&#39;isolamento dell&#39;area più piccola del materiale che può essere creato per la sezione.

<b>Affiancatura automatica </b> è particolarmente utile per i tessuti.

</td>
</tr>
</table>

>[!NOTE]
>
> Affinché il filtro Porzione automatica funzioni, sono necessarie almeno 3x3 ripetizioni nell’immagine o nel materiale di origine.

## Esercitazione sul filtro di Affiancamento automatico

## Porzioni automatiche

Quando lo aggiungi alla tua Pila livelli, <b>Affiancamento automatico</b> proverà a trovare automaticamente i pattern ripetuti e a generare un materiale Affiancamento. In caso contrario, è possibile utilizzare il pulsante <b>Impostazioni avanzate </b> per regolare manualmente il processo.

Se intendete creare un materiale Affiancamento da un&#39;immagine, è preferibile utilizzare prima il <b>filtro Affiancamento automatico</b>, quindi l&#39;<b>immagine da Filtro materiale</b>.

<b>Divisione automatica in porzioni</b> viene eseguita completamente sul dispositivo e non viene inviato alcun contenuto al cloud.

## Parametri

A differenza della maggior parte dei filtri, <b>Affiancamento automatico</b> non dispone di parametri. È invece disponibile un pulsante <b>Impostazioni avanzate </b> che consente di configurare il filtro. Non è necessario eseguire regolazioni manuali di ogni passo e potete saltare avanti o indietro selezionando un passo nella parte superiore della finestra.

Questo processo prevede le seguenti fasi:

1. <b>Introduzione</b>: illustra il funzionamento del filtro. Utilizza la casella di controllo per nascondere questa schermata in futuro.
1. <b>Mappa selezione</b>: selezionare il canale che deve essere utilizzato dal filtro. Si consiglia di scegliere il canale con il pattern ripetuto più visibile. Si tratta in genere del colore di base o del canale di Height, ma possono essere utili altri canali a seconda del materiale.
1. <b>Impostazioni di esempio</b>: apportare modifiche al materiale di input per ottenere risultati ottimali. Ciò include la scelta di una risoluzione e la rotazione o l’alterazione dell’input. Se il pattern è molto piccolo, può essere utile selezionare una risoluzione più elevata per assicurarsi che sia visibile. Tuttavia, per i pattern più grandi, una risoluzione inferiore può fornire risultati migliori e più veloci.
1. <b>Dimensione del pattern</b>: in questo passaggio il filtro cerca il pattern più piccolo che può trovare. È possibile scegliere tra un rilevamento automatico più grande o più piccolo oppure selezionare dimensioni personalizzate per specificare dimensioni personalizzate. Per risultati ottimali, selezionate la dimensione minima che ha il pattern ripetuto una volta per casella.\
   Se tutte le caselle hanno una forma irregolare e non sembrano corrispondere al pattern, utilizza la dimensione personalizzata per provare a ottenere risultati più regolari.
1. <b>Rilevamento pattern</b>: posizionare i punti in modo che ogni punto si trovi nella stessa posizione nel pattern. Ad esempio, in un motivo a scacchiera in bianco e nero, è possibile che si desideri che i punti si trovino al centro dei quadrati neri.
1. <b>Area di interesse</b>: selezionate l&#39;area del materiale da utilizzare per creare il pattern finale. L’utilizzo di un’area più ampia riduce la quantità di ripetizioni visibili, ma l’inclusione di aree con artefatti o differenze di illuminazione visibili può aumentare la quantità di ripetizioni visibili.
1. <b>Rimozione della giuntura</b>: regolate le impostazioni per ridurre al minimo la visibilità della giuntura. <b>Lo smoothness del taglio </b> controlla l&#39;uniformità della linea della giuntura, mentre <b>lo spessore della Fusione </b>sfoca la giuntura tra le piastrelle.

Dopo aver completato tutti i passaggi, utilizza <b>Applica</b> per confermare le scelte. Il filtro <b>Affiancamento automatico</b> elaborerà il materiale per generare un risultato finale.
