---
title: Procedure ottimali per la scansione
description: Scopri come preparare e posizionare i campioni fisici prima della scansione con HP Z Captis per risparmiare tempo nella post-elaborazione in Substance 3D Sampler.
source-git-commit: a0034da3bee13d0d7423828a902da62cf2219474
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 0%

---


# Best practice per la scansione

La qualità del materiale digitalizzato viene stabilita molto prima di premere il pulsante di scansione. Un campione pulito, piatto e ben posizionato produce mappe pulite e pronte all&#39;uso, mentre un&#39;acquisizione rapida trasporta ogni ruga, macchia di dust e fibra isolata direttamente nei canali PBR.

La regola generale è semplice: **un minuto in più per preparare il materiale prima che la scansione vi faccia risparmiare circa dieci minuti di pulizia in un secondo momento**. Tempo impiegato per stirare un tessuto, spazzolare via il dust o allineare il campione è tempo che non passerete più a deformare il materiale, a riparare le particelle o a rimuovere le fibre sciolte.

In questa pagina sono illustrate due aree che fanno la differenza maggiore: **preparazione del campione fisico** e **posizionamento corretto** nel dispositivo.

## Preparare il campione fisico

Tutto ciò che è visibile sul campione quando viene acquisito viene inserito nelle mappe. Alcuni minuti di preparazione rimuovono i problemi alla sorgente, prima che diventino lavoro di editing.

**Pulire l&#39;esempio**

Pulite rapidamente il campione prima di inserirlo. Qualsiasi segno sulla superficie verrà interpretato come un dettaglio di materiale e riprodotto su ogni canale.

**Rimuovere particelle estranee e dust**

Dust, capelli, fili e altre particelle sono una delle fonti più comuni di lavoro di post-elaborazione. Pennello o aria compressa per pulire la superficie, poiché ogni particella lasciata dietro deve essere dipinta a mano in un secondo momento.

![](../../assets/scanning/clean-textile.png)

**Tessuti in ferro per rimuovere le rughe**

Per i tessuti e altri materiali flessibili, stirare sempre il campione prima della scansione. Le rughe e le pieghe creano false informazioni su height e ombre che è difficile rimuovere in seguito e che interrompono l&#39;inclinabilità del materiale.

![](../../assets/scanning/flatten-textile.png)

**Rimuovere le macchie dalle superfici lisce**

Su materiali lisci e non porosi, pulisci eventuali macchie, impronte digitali o macchie. Questi sono visibili chiaramente nei canali del colore di base e della rugosità.

**Conoscere il thickness di esempio**

Tenete presente lo spessore del campione. La conoscenza del thickness consente di posizionarlo correttamente e di impostare l’acquisizione in modo che la superficie resti a fuoco su tutta l’area di scansione.

## Inserire correttamente il campione

Una buona disposizione mantiene il materiale piatto, nitido e centrato, riducendo la quantità di ritaglio, deformazione e allineamento da eseguire in seguito.

![](../../assets/scanning/center-textile.png)

**Centrare il materiale nell&#39;area di scansione**

Posizionare il campione al centro dell&#39;area di scansione. Qui fuoco e illuminazione sono più uniformi, e dà la superficie più utilizzabile una volta che il materiale è ritagliato. Per questo motivo è sempre ideale eseguire la scansione di un campione alla volta, in modo da poterlo posizionare al centro dell&#39;area di scansione e ottenere i migliori risultati possibili.

**Allinearlo il più diritto possibile**

Allineare il campione in modo quadrato con l’area di scansione, anziché angolarlo. Un campione semplice è molto più facile da affiancare e richiede meno rotazione e ritaglio in Sampler.

**Mantenere il campione piatto**

Assicurarsi che il campione sia completamente piatto rispetto alla superficie di scansione. Se necessario, utilizzare i magneti forniti con il dispositivo HP Z Captis per tenere in posizione materiali flessibili o arricciati. Un campione piatto evita l’alterazione e la messa a fuoco irregolare, che altrimenti richiederebbero molto tempo per la correzione.

**Non sovrapporre campioni**

Se si posizionano più campioni contemporaneamente, non lasciarli toccare o sovrapporsi. I bordi sovrapposti creano contorni ambigui che sono difficili da separare e ritagliare in un secondo momento.

## I vantaggi di Sampler

Quando il campione è pulito, piatto e centrato, le mappe che arrivano in Sampler sono già pronte per la produzione. Passate il tempo a rifinire il materiale invece di ripararlo: meno tempo a non deformare, meno tempo a pulire dust e fibre, e meno tempo a riparare macchie e rughe dai vostri canali.

Una volta importato il materiale, utilizzate i filtri di Sampler (Equalizza, Divisione in porzioni automatica, Ritaglio prospettiva, Divisione in porzioni, ...) per i tocchi finali ed esportate quando siete soddisfatti del risultato.
