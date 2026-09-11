---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/sphere-light.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Luce sfera in Substance 3D Sampler per aggiungere sorgenti di luce sferica agli ambienti HDRI per creare effetti di luce puntuali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Sphere Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luce sfera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# Luce sfera

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-spherelight-18-n-d.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Aggiungi una luce sferica all’ambiente.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Metodo colore forma**:\
  Selezionate il metodo da usare per determinare il colore della luce. I parametri disponibili verranno modificati in base a questa selezione.
  * **Temperatura (Kelvin)**
    * **Temperatura**: 1000 - 27000\
      Regolate la temperatura della luce.
  * **RGB**
    * **Colore**: selezione colore\
      Selezionate il colore della luce.
  * **Input immagine**
    * **Input immagine forma**: immagine/pennello\
      Importate un’immagine da usare come colore. È possibile utilizzare lo strumento Pennello per eseguire pitture direttamente in **Vista 2D**, ma questo filtro può produrre risultati imprevedibili.
  * **Sfondo di esempio**
    * Lo sfondo di esempio non rende disponibili nuovi parametri, ma basa il colore della luce sui valori dello sfondo.
* **Esposizione (EV)**: 0-10\
  Regola l’esposizione o la luminosità della luce.
* **Raggio sfera**: 0-1\
  Regolate le dimensioni della luce.
* **Modalità posizione**:\
  Modificate il metodo utilizzato per determinare la posizione delle luci. I parametri nella sezione **Coordinate posizione** verranno modificati in base alla selezione.

**Coordinate posizione**

I parametri disponibili dipendono dalla selezione effettuata per **Parametri di base > Modalità posizione**. Se è selezionato **Distanza dall&#39;origine**, sono disponibili i seguenti parametri:

* **Distanza dall&#39;origine**: 0-20\
  Regolate la distanza della luce dalla fotocamera.
* **Posizione fotocamera**: 0-1\
  Regolate la posizione relativa della videocamera rispetto alla luce sugli assi X, Y e Z.

Se è selezionato **Posizione globale**, sono disponibili i seguenti parametri:

* **Vettore Su**:\
  Cambiate la direzione verso l&#39;alto.
* **Posizione globale sfera**: da -2 a 2\
  Regola la posizione della luce della sfera sugli assi X, Y e Z.
* **Distanza dall&#39;origine**: 0-20\
  Regolate la distanza della luce dalla fotocamera.
* **Posizione fotocamera**: 0-1\
  Regolate la posizione relativa della videocamera rispetto alla luce sugli assi X, Y e Z.

**Forma**

* **Durezza sfera**: 0-1\
  Ammorbidite o indurisce i bordi della luce della sfera
* **Ombreggiatura**:\
  Modificate la sfumatura dell&#39;esposizione della luce in base ai diversi stili di luce del mondo reale. Con **Luce Ombreggiatura** selezionata, vengono visualizzati parametri aggiuntivi:
  * **Ombreggiatura posizione mondo luce**: da -1 a 1\
    Modificate la posizione dell’area ombreggiata sulla luce
  * **Trasparenza Penumbra**: 0-1\
    Regolate il livello di opacità dell’area ombreggiata della luce.

**Sfondo**

* **Gamma sfondo**:\
  Seleziona il sistema di colore usato per determinare il gamma di sfondo.
