---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/wear-and-finish/paint.html"
breadcrumb-title: ''
description: Utilizzate il filtro Disegno di Substance 3D Sampler per aggiungere livelli di pittura, rivestimenti ed effetti di superficie colorata ai materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Paint
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Vernice
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 0%

---


# Vernice

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-paint-18-n-d.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il **filtro Pittura** consente di coprire il materiale in un livello di pittura di thickness variabile.

*Materiale metallico con sopra vernice usurata.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0017-paint-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0016-paint-out.jpg){width="200px"}

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
* **Colore**: selezione colore\
  Impostate il colore del disegno.
* **Rugosità**: 0-1\
  Impostate la ruvidezza delle aree coperte dalla vernice.
* **Thickness**: 0-1\
  Regolate la viscosità e il thickness della vernice. Questo incide sulla quantità di height sottostante e di informazioni normali visibili attraverso il colore.
* **Sbuccia**: 0-1\
  Aggiungete le patch in cui la vernice si è staccata dal materiale sottostante.
* **Granulosità**: 0-1\
  Modificate la granulosità della superficie del disegno.
* **Granulosità**: 1-5\
  Regolate la scala della texture usata per creare le granulosità.

**Maschera**

* **Maschera cavità**: attiva/disattiva\
  Create una maschera in base alle cavità presenti nella mappa del height. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Dimensioni cavità**: 0-1\
    Regolate l’intervallo height usato per creare la maschera della cavità.
  * **Intensità cavità**: 0-1\
    Regola l’opacità della maschera in base alla profondità della cavità.
  * **Inverti maschera cavità**: attiva/disattiva\
    Invertite la maschera della cavità per modificare l’effetto sui punti alti o bassi.
* **Usa maschera personalizzata**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Maschera**: immagine/pennello\
    Selezionate un’immagine da usare come maschera o usate il pennello per colorare una maschera personalizzata direttamente nella vista 2D.
  * **Maschera personalizzata - Sfocatura**: 0-1\
    Sfocate la maschera.
  * **Maschera personalizzata - Inverti**: attiva/disattiva\
    Invertite la maschera.

**Parametri avanzati**

* **Colore di base**: attiva/disattiva\
  Consente di impostare se il canale del colore di base è interessato dal filtro.
* **Metallico**: attiva/disattiva\
  Imposta se il filtro agisce sul canale metallico.
  * **Valore metallico**: 0-1\
    Regolate il valore metallico delle aree dipinte.
* **Rugosità**: attiva/disattiva\
  Impostate se il canale di rugosità è interessato dal filtro.
* **Normale**: attiva/disattiva\
  Consente di impostare se il filtro agisce sul canale normale. Se questa opzione è attivata, viene visualizzato un controllo aggiuntivo:
  * **Normale - Intensità**: da -1 a 1\
    Regolate l’intensità delle normali.
* **Height**: attiva/disattiva\
  Consente di impostare se il filtro agisce sul canale del height. Se questa opzione è attivata, viene visualizzato un controllo aggiuntivo:
  * **Height - Intensità**: 0-1\
    Regola il contrasto della mappa del height.
* **Opacità**: attiva/disattiva\
  Impostate se il filtro agisce sul canale di opacità. Se questa opzione è attivata, viene visualizzato un controllo aggiuntivo:
  * **Opacità - Valore**: 0-1\
    Modificate l&#39;opacità del materiale.
* **Emissivo**: attiva/disattiva\
  Impostare se il canale di emissione è influenzato dal filtro. Se questa opzione è attivata, viene visualizzato un controllo aggiuntivo:
  * **Emissivo - Colore**: selezione colore\
    Imposta il colore del canale di emissione.
* **Occlusione ambiente**: attiva/disattiva\
  Consente di specificare se il filtro agisce sul canale di occlusione dell’ambiente. Se questa opzione è attivata, compaiono i seguenti controlli aggiuntivi:
  * **Occlusione ambiente - Intensità**: 0-1\
    Regolate l’intensità dell’AO generato.
  * **Occlusione ambiente** **- Raggio**: 0-1\
    Regolate il raggio dell’effetto AO.
