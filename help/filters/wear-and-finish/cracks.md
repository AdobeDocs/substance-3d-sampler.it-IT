---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/cracks.html"
breadcrumb-title: ''
description: Utilizza il filtro Crepe di Substance 3D Sampler per aggiungere pattern di crepe realistici e effetti di danno alla superficie dei materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Cracks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Crepe
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 1%

---


# Crepe

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-cracks-18-n-d.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizza il **filtro Crepe** per invecchiare e danneggiare il tuo materiale aggiungendo una rete di crepe e fessure.

Il **filtro Crepe** applicato a un materiale di marmo pulito.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0043-cracks-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0042-cracks-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Pagine affiancate Crepe**: 0-1\
  Regola la distanza di diffusione della crepe: questo modifica sia la larghezza che la lunghezza della crepa.
* **Importo Crepe**: 0-1\
  Modificate il numero di crepe visualizzate.

**Maschera**

* **Usa maschera personalizzata**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Maschera**: immagine/pennello\
    Selezionate un’immagine da usare come maschera oppure usate il pennello per pittura una maschera personalizzata direttamente nella Vista 2D.
  * **Maschera personalizzata - Inverti**: attiva/disattiva\
    Invertite la maschera.

**Crepe**

* **Colore Crepe**: selezione colore\
  Modificate il colore della superficie interna rivelata dalle crepe.
* **Rugosità Crepe**: 0-1\
  Regolate il valore di rugosità delle crepe.
* **Opacità rugosità Crepe**: 0-1\
  Regola l’impatto del valore **Rugosità Crepe** sulla mappa di rugosità
* **Crepe metalliche**: 0-1\
  Modificate il valore metallico delle crepe.
* **Opacità Metallica Crepe**: 0-1\
  Regola l&#39;impatto del valore **Crepe metalliche** sulla mappa metallica
* **Intensità height Crepe**: 0-1\
  Regolate la profondità delle crepe. Questo influisce sia sulla mappa dell’altezza che sui risultati delle mappe normali del filtro.

**Parametri avanzati**

* **Intensità normale**: 0-1\
  Regolate la forza delle normali della crepa.
* **Intervallo Height**: 0-1\
  Modificate l&#39;intervallo height dell&#39;intero materiale. Per regolare il height delle crepe, utilizza **Crepe > Intensità Height Crepe**.
* **Posizione Height**: 0-1\
  Scostate la mappa di altezza dell&#39;intero materiale.
