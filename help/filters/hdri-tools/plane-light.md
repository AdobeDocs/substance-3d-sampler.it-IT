---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/hdri-tools/plane-light.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Luce piano in Substance 3D Sampler per aggiungere sorgenti luminose piane agli ambienti HDRI per creare effetti di luce per area.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Plane Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luce piano
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '502'
ht-degree: 0%

---


# Luce piano

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-planelight-18-n-d.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Aggiungete una luce a forma di piano piano all&#39;ambiente.

![](../../assets/3d-2d-filters-cropped-0002-plane-light-out.jpg)

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Esposizione (EV)**: 0-10\
  Regola l’esposizione o la luminosità della luce.
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
      Importate un’immagine da usare come colore. È possibile utilizzare lo strumento Pennello per colorare direttamente nella **vista 2D**, ma questo filtro può produrre risultati imprevedibili.
  * **Sfondo di esempio**
    * Lo sfondo di esempio non rende disponibili nuovi parametri, ma basa il colore della luce sui valori dello sfondo.
* **Modalità posizione**:\
  Modificate il metodo utilizzato per determinare la posizione delle luci. I parametri nella sezione **Coordinate posizione** verranno modificati in base alla selezione. Con **Posizione universale** selezionato, le maniglie scompariranno dalla **vista 2D** e utilizzate invece i parametri in **Coordinate posizione** per modificare la posizione della luce.

**Forma**

* **Scala piano**; 0-1\
  Regolate la scala della luce.
* **Dimensione piano**: 0-1\
  Regolate le dimensioni della luce sugli assi X e Y.
* **Rotazione piano**: 0-1\
  Regolate la rotazione della luce lungo gli assi X, Y e Z.
* **Pattern**:\
  Selezionate la forma della luce.
* **Durezza motivo**: 0-1\
  Ammorbidite o sfocate i bordi della luce
* **Modalità UV modello**:\
  Scegli se le trasformazioni estendono l&#39;intera forma o solo il centro della forma per mantenere i dettagli dei bordi e degli angoli.

**Coordinate posizione**

I parametri disponibili dipendono dalla selezione effettuata per **Parametri di base > Modalità posizione**. Se sono selezionati **Ground/Ceiling** o **Distanza dall&#39;origine**, sono disponibili i seguenti parametri:

* **Height assoluto riga**: 0-1\
  Modificate la distanza della luce dalla fotocamera.
* **Posizione fotocamera**: 0-1\
  Regolate la posizione relativa della videocamera rispetto alla luce sugli assi X, Y e Z.

Se si sceglie **Posizione globale** in **Parametri di base > Modalità posizione**, sono disponibili i seguenti parametri:

* **Vettore Su**:\
  Cambiate la direzione verso l&#39;alto.
* **Posizione mondiale punto 1**: da -2 a 2\
  Regolate la posizione del primo punto della linea sugli assi X, Y e Z.
* **Posizione mondiale punto 2**: da -2 a 2\
  Regolate la posizione del secondo punto della linea sugli assi X, Y e Z.
* **Posizione fotocamera**: 0-1\
  Regolate la posizione relativa della videocamera rispetto alla luce sugli assi X, Y e Z.

**Sfondo**

* **Mostra griglia terreno**: attiva/disattiva\
  Visualizzare o nascondere la griglia del terreno.
* **Abilita ritaglio terreno**: attiva/disattiva\
  Seleziona se la luce può ritagliare o meno il terreno. Se attivato, viene visualizzato il seguente controllo:
  * **Height terreno**: da -2 a 2\
    Regolate il height del terreno allo scopo di ritagliare la luce.
* **Gamma sfondo**:\
  Seleziona il sistema di colore usato per determinare il gamma di sfondo.
