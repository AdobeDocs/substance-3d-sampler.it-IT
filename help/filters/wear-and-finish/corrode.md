---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Utilizzate il filtro Corrode di Substance 3D Sampler per aggiungere effetti di corrosione e degradazione chimica ai materiali metallici.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Corrode
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Corrode
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---


# Corrode

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/corrode-filter-icon.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro corrode simula l’effetto di un consumo acido nel materiale, lasciando fori e danneggiando la superficie.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Aree interessate**:\
  Selezionate la modalità di impatto della curvatura della superficie sull&#39;effetto del filtro.
* **Livello di perforazione**: 0-1\
  Regolate il numero di fori creati.
* **Posizione curvatura**: 0-1\
  Modificate l&#39;intervallo di curvatura su cui agire.
* **Curvatura Uniforme**: 0-1\
  Arrotonda la mappa di curvatura.
* **Distanza dai danni**: 0-1\
  Controllate il raggio di danneggiamento attorno alle aree corrose.
* **Intensità danno**: 0-1\
  Regolate la quantità di danno nelle aree interessate.
* **Intensità Height**: 0-1\
  Controllare l&#39;impatto del danno sulla mappa del height.
* **Posizione estrusione**: attiva/disattiva\
  Cambiare la direzione del danno sulla mappa del height. Quando è disattivata, la lesione si riversa in superficie; quando è attivata, la lesione si sviluppa verso l&#39;esterno dalla superficie.

**Maschera**

* **Usa maschera personalizzata**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Maschera**: immagine/pennello\
    Selezionate un’immagine da usare come maschera o usate il pennello per colorare una maschera personalizzata direttamente nella vista 2D.
  * **Maschera personalizzata - Sfocatura**: 0-1\
    Sfocate la maschera.
  * **Maschera personalizzata - Inverti**: attiva/disattiva\
    Invertite la maschera.

**Parametri avanzati**

Alcuni dei parametri avanzati influiscono sull&#39;intero materiale anziché solo sulle aree modificate da questo filtro.

* **Luminosità**: 0-1\
  Regolate la luminosità o la luminosità per tutto il materiale.
* **Contrasto**: da -1 a 1\
  Regolate il contrasto di albedo per tutto il materiale.
* **Scostamento tonalità**: 0-1\
  Scostate il valore della tonalità dei colori nell&#39;intero materiale.
* **Saturazione**: 0-1\
  Regolate la saturazione per tutto il materiale.
* **Intensità normale**: 0-1\
  Regolare l&#39;intensità della mappa normale in cui è stata interessata dal **filtro Corrode**.
* **Intervallo Height**: 0-1\
  Aumentate l&#39;intervallo di valori nella mappa del height per l&#39;intero materiale.
* **Posizione Height**: 0-1\
  Eseguite l&#39;offset del height dell&#39;intero materiale.
* **Intensità Occlusione ambiente**: 0-1\
  Regola l&#39;intensità dell&#39;impatto AO grazie al **filtro Corrode**.
