---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/perforate.html"
breadcrumb-title: ''
description: Utilizzate il generatore Perforazione di Substance 3D Sampler per creare pattern perforati e array di fori in materiali e texture.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Perforate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Perforare
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---


# Perforare

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-perforation-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizzate il filtro Perfora per aggiungere fori al materiale.

*Prima e dopo l&#39;applicazione del **filtro Perforazione**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0007-perforate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0006-perforate-out.jpg){width="200px"}

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
* **Selezione pattern**:\
  Selezionate la forma dei fori o scegliete Pattern personale per creare un&#39;immagine personalizzata.
* **Posizione perforazione**:\
  Selezionare se le normali e il height si ritirano nel materiale o se risaltano dal materiale
* **Dimensione smusso perforazione**: 0-1\
  Modificare le dimensioni dello smusso sugli spigoli dei fori
* **Dimensione foro**: 0-1\
  Modificare le dimensioni dei fori
* **Usa maschera**: attiva/disattiva\
  Consente di attivare la **sezione Maschera** che potete utilizzare per mascherare la perforazione con un pennello o un&#39;immagine.
* **Usa mappa scala**: attiva/disattiva\
  Consente l&#39;utilizzo di una mappa scala. Quando questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Moltiplicatore mappa scala**: 0-1\
    Regolate l’impatto della mappa di scala sulla scala di perforazione
  * **Inverti mappa scala**: attiva/disattiva\
    Invertire i valori della mappa scala
  * **Mappa scala personalizzata**: immagine/pennello\
    Importa un&#39;immagine da utilizzare come mappa scala o utilizza il pennello per pittura una mappa scala direttamente nella **vista 2D** **vista**

**Maschera**

Questa sezione è visibile solo se è abilitato **Parametri di base > Usa maschera**

* **Inverti maschera**:
* **Sfocatura maschera**: 0-1\
  Regolare la sfocatura applicata alla maschera
* **Soglia maschera**: 0-1\
  Modificate la soglia della maschera. Utilizzate insieme i valori **Sfocatura maschera** e **Soglia maschera** per perfezionare i bordi della maschera.
* **Maschera personalizzata**: immagine/pennello\
  Importa un&#39;immagine da utilizzare come maschera o pittura una maschera direttamente in **Vista 2D**

**Perforazione**

* **Dimensione perforazione**: 0-1\
  Modificate le dimensioni di ciascuna perforazione, compresi il foro e lo smusso.
* **Perforazione Y**: 1-64\
  Regolare il numero di perforazioni sull&#39;asse Y
* **Perforazione X Quantità**: 1-64\
  Regola il numero di perforazioni sull’asse X
* **Densità perforazione**: 0-1\
  Perforazioni casuali della maschera
* **Scostamento perforazione**: 0-1\
  Regolare lo scostamento di ogni seconda riga di perforazioni
* **Opacità colore perforazione**: 0-1\
  Regolare la trasparenza del colore dell’area smussata delle perforazioni
* **Colore perforazione**: selezione colore\
  Selezionate il colore dell’area smussata di ogni perforazione
* **Rugosità perforazione**: 0-1\
  Modificare il valore di rugosità delle perforazioni
* **Perforazione Metallica**: 0-1\
  Modificare il valore metallico delle perforazioni

**Parametri avanzati**

* **Luminosità**: 0-1
* **Contrasto**: da -1 a 1
* **Scostamento tonalità**: 0-1
* **Saturazione**: 0-1
* **Intensità normale**: da -1 a 1\
  Regolare la forza di ogni perforazione normale
* **Intensità Height**: 0-1\
  Regolare l&#39;intensità di ciascuna mappa dell&#39;altezza delle perforazioni
