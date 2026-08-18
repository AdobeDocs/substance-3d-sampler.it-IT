---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/wear-and-finish/rust.html"
breadcrumb-title: ''
description: Utilizzate il filtro Ruggine di Substance 3D Sampler per aggiungere effetti di ruggine e corrosione realistici ai materiali e alle superfici metalliche.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Rust
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ruggine
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 0%

---


# Ruggine

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-rust-18-n-d.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizza il **filtro Ruggine** per aggiungere uno strato di metallo ossidato al materiale.

Nelle immagini seguenti è possibile visualizzare un materiale metallico prima e dopo l&#39;aggiunta del **filtro Ruggine**.

![](../../assets/3d-filters-cropped-0002-rust-out.jpg){width="200px"}

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Ruggine pagine affiancate**: 0-1\
  Controlla la distribuzione o la quantità di ruggine.
* **Influenza Edge**: 0-1\
  Regola il modo in cui la ruggine interagisce con i bordi in base alla mappa di curvatura.
* **Smoothness pagine affiancate**: 0-1\
  Aumentate questo valore per aumentare la visibilità delle aree di attendibilità o ridurla per renderle più dettagliate.
* **Solo Metal**: Attiva/Disattiva\
  Se attivato, il **filtro Ruggine** avrà effetto solo sulle aree con un valore metallico maggiore di 0.

**Ruggine**

* **Forma Ruggine**:\
  Modificate il pattern su cui si basa la ruggine.
* **Intensità Ruggine**: 0-1\
  Modificate l’intensità dell’effetto ruggine. Aumentando questo valore, la ruggine appare più vecchia e più forte.

**Sbuccia**

* **Scala Della Buccia**: 0-1\
  Modificate la scala della ruggine di sbucciatura.
* **Intensità normale della buccia**: 0-1\
  Regolate la visibilità delle normali della buccia.
* **Intensità Height Della Buccia**: 0-1\
  Regolate l&#39;impatto delle bucce sulla mappa del height.

**Gocce**

* **Intensità gocce**: 0-1\
  Modificate l’intensità dell’effetto goccia.
* **Orientamento gocce**: 0-1\
  Orientate le gocce in base alla gravità o al vento.
* **Lunghezza gocce**: 0-1\
  Regolate la distanza di estensione delle gocce dalla sorgente.

**Maschera**

* **Usa maschera**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Maschera**: immagine/pennello\
    Selezionate un’immagine da usare come maschera o usate il pennello per colorare una maschera personalizzata direttamente nella vista 2D.
  * **Maschera personalizzata - Sfocatura**: 0-1\
    Sfocate la maschera.
  * **Maschera personalizzata - Inverti**: attiva/disattiva\
    Invertite la maschera.
