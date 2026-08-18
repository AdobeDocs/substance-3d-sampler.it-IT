---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: Usate lo strumento Anteprima esposizione in Substance 3D Sampler per visualizzare in anteprima le regolazioni dell’esposizione nelle immagini HDRI prima di applicare le modifiche.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Anteprima esposizione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# Anteprima esposizione

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il **filtro** filtro **per l&#39;anteprima dell&#39;esposizione** consente di visualizzare rapidamente un&#39;anteprima di uno spettro di valori di esposizione.

Di seguito potete vedere le operazioni eseguite dal filtro **Anteprima esposizione**.

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

Nell&#39;immagine sopra, è stata creata una luce ambiente e i dati dell&#39;immagine HDR sono visibili nella **vista 2D**.

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

Con l&#39;**anteprima esposizione** **filtro** aggiunto allo stack di livelli, diventa disponibile un nuovo canale, Diagnostica ambiente, che mostra la luce ambiente a varie esposizioni.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Esposizione minima (EV)**: da -8 a 8\
  Impostate l’esposizione dell’immagine con la minore esposizione.
* **Esposizione massima (EV)**: da -8 a 8\
  Impostate l’esposizione dell’immagine più esposta.

## Guida all’uso

Il filtro **Anteprima esposizione** funziona in modo leggermente diverso rispetto ad altri filtri di Sampler. È uno strumento che serve a trovare l&#39;esposizione corretta per la luce ambiente, ma non influisce sul canale Ambiente. Quando invece aggiungete il **filtro Anteprima esposizione** allo stack di livelli, diventa disponibile un canale aggiuntivo da visualizzare nella **vista 2D**, il canale Diagnostica ambiente.

Se si visualizza il canale di diagnostica dell&#39;ambiente, è possibile visualizzare alcune istanze dell&#39;immagine dell&#39;ambiente 2D con valori di esposizione variabili. Regolate i parametri del **filtro Anteprima esposizione** per modificare l&#39;intervallo di esposizioni visibili nel canale di diagnostica dell&#39;ambiente.
