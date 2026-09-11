---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Unione HDR in Substance 3D Sampler per unire più immagini di esposizione in un'unica immagine a high dynamic range.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Unione HDR
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# Unione HDR

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

L&#39;**unione HDR** **filtro** consente di unire una raccolta di immagini SDR (Standard Dynamic Range) per creare un&#39;immagine HDR.

Le immagini seguenti mostrano i risultati dell&#39;**unione HDR**.

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

Prima che venga completata l&#39;**unione HDR**, la sfera nella **vista 3D** riflette la luce ambientale predefinita. Per impostazione predefinita, nella **vista 2D** vengono visualizzati i dati dell&#39;immagine importata per la prima immagine di scansione, che in questo caso è l&#39;immagine con esposizione più bassa.

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

Dopo l&#39;aggiunta del **HDR Merge** **filter**, la sfera riflette una nuova luce ambientale, ovvero l&#39;immagine HDR generata dalle immagini di input.

</td>
</tr>
</table>

## Parametri TP

**Parametri di base**

* **Delta esposizione input (EV)**: 0-2\
  Imposta la differenza di esposizione tra le esposizioni in entrata più alte e più basse. Un delta di esposizione elevata aumenterà il contrasto risultante dall&#39;operazione di unione.
* **Esposizione automatica output**: attiva/disattiva\
  Attivate o disattivate la regolazione automatica dell&#39;esposizione.
* **Scostamento esposizione di output (EV)**: da -5 a 5\
  Scostate l’esposizione.

## Guida all’uso

Guarda questo documento per scoprire come utilizzare il **filtro Unione HDR** e altri filtri che consentono di convertire le immagini SDR in una luce ambientale HDR.

I passaggi di base per l&#39;utilizzo dell&#39;**unione HDR** **filtro** sono i seguenti:

1. Importate il set di immagini da unire nella Pila livelli.
1. Aggiungere il **filtro Unione HDR** alla Pila livelli.
1. Modificate i parametri per garantire che i valori di esposizione siano corretti.
