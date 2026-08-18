---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/tools/height-to-normal.html"
breadcrumb-title: ''
description: Utilizza lo strumento da Height a normale di Substance 3D Sampler per convertire le mappe di height in mappe normali per i flussi di lavoro di creazione del materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to Normal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Da height a normale
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# Da height a normale

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-heighttonormal-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Genera i dati del canale normale in base al canale di height.

Nelle immagini seguenti è possibile visualizzare il filtro **Da Height a Normale** in azione.

![](../../assets/h2n-in.jpg)

Nell&#39;immagine sopra, non ci sono dati normali dal materiale. Solo la mappa height è disponibile e visualizzata nella **vista 2D**.

![](../../assets/h2n-out.jpg)

Con il filtro da **Height a normale**, i dati normali vengono generati dalla mappa height mostrata nell&#39;immagine superiore. La luce rimbalza in modo più realistico dal materiale nella seconda immagine, grazie alla mappa normale generata.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Usa unità globali**: attiva/disattiva\
  Consente di specificare se i parametri devono essere misurati utilizzando unità reali. Questo modifica i parametri disponibili.
  * **Se Usa unità globali è abilitato:**
    * **Dimensioni superficie (cm)**: 0-500\
      Imposta la dimensione dello spazio UV in unità globali
    * **Profondità Height (cm)**: 0-10\
      Imposta la distanza rappresentata dalla mappa del height. Se la mappa del height rappresenta una piccola distanza, una grande differenza nei valori della mappa del height può avere un piccolo impatto sull&#39;angolo normale. Se la mappa del height rappresenta una grande distanza, una piccola differenza nei valori della mappa del height può rappresentare un angolo grande sulla mappa normale.
  * **Se Usa unità globali è disattivato:**
    * **Intensità**: 0-3\
      Regolare la ripidità degli angoli normali
* **Combina normale inferiore**: 0-1\
  Aggiungere la mappa normale esistente ai risultati di questo filtro.

**Maschera**

* **Maschera personalizzata**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Maschera**: immagine/pennello\
    Selezionate un’immagine da usare come maschera o usate il pennello per colorare una maschera personalizzata direttamente nella vista 2D
  * **Maschera personalizzata - Sfocatura**: 0-1\
    Sfocare la maschera
  * **Maschera personalizzata - Inverti**: attiva/disattiva\
    Invertire la maschera
