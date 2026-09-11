---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/tools/make-it-tile.html"
breadcrumb-title: ''
description: Usa lo strumento Crea porzioni in Substance 3D Sampler per creare automaticamente pattern di Affiancamento senza interruzioni da texture non Affiancamenti.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Make it Tile
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Crea porzioni
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '556'
ht-degree: 0%

---


# Crea porzioni

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizza il **filtro Affianca** per rendere affiancabile il materiale. Anche il **filtro Affiancamento** rende affiancabile il materiale, ma ogni filtro funziona in modo diverso. Se il **filtro Affianca** non funziona, provare il **filtro Affiancamento**.

Nelle immagini seguenti, puoi vedere come il **filtro Crea porzione** può convertire un materiale non Affiancamento in un materiale affiancabile. Questo materiale si affianca bene perché segue un pattern a griglia e non ci sono punti specifici che attirano l&#39;attenzione.

![](../../assets/3d-2d-filters-cropped-0015-make-it-tile-in.jpg)

Nell&#39;immagine sopra, la linea rossa mostra il contorno del materiale. È abbastanza chiaro che c&#39;è una cucitura forte, e che questo materiale non piastrella.

![](../../assets/3d-2d-filters-cropped-0014-make-it-tile-out.jpg)

Dopo aver **reso piastrella**, questo materiale piastrella bene e senza la linea rossa, sarebbe impossibile vedere le giunture ai bordi del materiale.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Soglia**: 0-1\
  Regola le dimensioni e la corrispondenza del livello superiore.
* **Smoothness**: 0-1\
  Attenua la giuntura dello strato superiore.
* **Contrasto**: 0-1\
  Regolate il contrasto della giuntura. Diminuire il contrasto equivale a sfocare la giuntura.
* **Rimozione macchie**: attiva/disattiva\
  Se questa opzione è attivata, il filtro tenterà di rimuovere gli artefatti vicino alla giuntura tra i livelli superiore e inferiore.
* **Color Equalizer**: 0-50\
  Equalizza i valori di colore per ridurre la visibilità della giuntura.
* **Height corrispondente**:\
  Modifica il metodo di fusione delle mappe altezza per il livello superiore e inferiore del filtro. Per visualizzare i risultati in modo più chiaro, visualizzare il canale di height nel **Vista 2D**. Tenete presente che la corrispondenza dei height non influisce sui canali diversi dal canale del height, pertanto le normali e l’AO non saranno influenzate dalle modifiche apportate alla corrispondenza dei height.

**Parametri avanzati**

* **Influenza crominanza**: 0-1\
  Regolate l’effetto dei valori di colore sulla giuntura.
* **Inversione maschera**: attiva/disattiva\
  Invertite le maschere dei livelli superiore e inferiore.
* **Smoothness di corrispondenza Height**: 0-16\
  Regola la sfocatura della corrispondenza height tra i livelli superiore e inferiore.
* **Origine patch sinistra/destra**: da -1 a 1\
  Regola la posizione di origine per le patch sinistra e destra.
* **Origine patch superiore/inferiore**: da -1 a 1\
  Regola la posizione di origine per le patch superiore e inferiore.

## Guida all’uso

Il **riquadro** **filtro** funziona sovrapponendo più copie del materiale l&#39;una sull&#39;altra.

L’immagine seguente mostra il layout dei livelli:

* Il perimetro verde mostra i bordi del materiale risultante dal **filtro Porzione**
* Le linee rosse mostrano i bordi del livello inferiore. Lo strato inferiore è scostato del 50% dello spazio UV sugli assi X e Y, quindi le linee rosse sono giunture Affiancamenti che devono essere coperte.
* Il quadrato blu e i semicerchi coprono le cuciture rosse. I parametri del filtro consentono di regolare i bordi delle forme blu per garantire che la giuntura rossa non sia visibile, mantenendo la giuntura blu il più uniforme possibile.

![](../../assets/makeittilediagram.png){width="512px"}

I semicerchi sinistro e destro si abbinano tra loro per garantire che le porzioni di materiale orizzontalmente, mentre i semicerchi superiore e inferiore assicurano le porzioni di materiale verticalmente. Il quadrato blu al centro rimuove tutte le giunture rimanenti per creare un materiale completamente piastrellabile senza giunture.
