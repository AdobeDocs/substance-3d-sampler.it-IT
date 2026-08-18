---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/line-light.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Luce linea in Substance 3D Sampler per aggiungere sorgenti luminose lineari agli ambienti HDRI per un controllo preciso dell’illuminazione.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Line Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luce linea
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---


# Luce linea

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-linelight-18-n-d.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Aggiungete una **luce di linea** alla luce ambiente.

Le immagini seguenti mostrano come utilizzare una **luce di linea** per regolare l&#39;illuminazione dell&#39;ambiente.![](../../assets/3d-2d-filters-cropped-0017-line-light-in.jpg)

L&#39;immagine qui sopra mostra una sfera senza modifiche alla luce ambiente.

![](../../assets/3d-2d-filters-cropped-0016-line-light-out.jpg)

Dopo aver aggiunto una **luce di linea**, l&#39;aspetto della sfera è notevolmente cambiato.

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

* **Rotazione riga**: 0-1\
  Ruotare la luce
* **Thickness di righe**: 0-1\
  Regolate il thickness della linea che forma la luce.
* **Pattern**:\
  Modificare la forma della linea
* **Durezza motivo**: 0-1\
  Ammorbidite i bordi della luce
* **Modalità UV modello**:\
  Modificate il pattern su cui si basa la luce. **Allunga** allunga l&#39;intera forma in modo che corrisponda ai punti finali della linea. **Allunga solo al centro** allunga il centro della forma mantenendo invariate le estremità della linea. **Ripeti + Spaziatura** crea timbri della forma lungo la lunghezza delle linee e aggiunge un ulteriore parametro per gestire la spaziatura:
  * **Spaziatura ripetizione pattern**: 0-1\
    Regolare la larghezza della spaziatura tra le istanze di forme

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
