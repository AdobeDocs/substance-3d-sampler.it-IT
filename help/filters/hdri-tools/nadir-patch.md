---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/hdri-tools/nadir-patch.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Nadir patch in Substance 3D Sampler per applicare le patch all’area inferiore delle immagini HDRI per ottenere mappe dell’ambiente uniformi.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Nadir Patch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Nadir patch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Nadir patch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-nadirpatch-18-n-d.png)

**In:** Strumenti HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Applicate una patch al bordo inferiore della luce ambientale per nascondere artefatti o cuciture.

Nelle immagini seguenti, potete vedere come **Nadir patch** viene utilizzato per rimuovere il supporto della fotocamera in questa immagine panoramica.

![](../../assets/3d-2d-filters-cropped-0011-nadir-patch-in.jpg)![](../../assets/3d-2d-filters-cropped-0010-nadir-patch-out.jpg)

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Abilita**: attiva/disattiva\
  Attivare o disattivare la patch: questo può essere utile per vedere rapidamente l’impatto della patch senza dover modificare la visibilità del livello.
* **Mostra helper Fotogrammi**: attiva/disattiva\
  Accendere o spegnere i Fotogrammi.
* **Thickness di Fotogrammi**: 0-1\
  Regolate il thickness del fotogramma. Questo può essere utile quando la fonte del cerotto è lontana dal nadir.
* **Scala patch**: 0-1\
  Regolate il contorno dell&#39;area da riparare.
* **Dimensione patch**:\
  Regolate le dimensioni del cerotto.
* **Rotazione patch**: 0-1\
  Ruotate i bordi della patch. In questo modo vengono ruotati sia la sorgente che la patch, in modo che la patch abbia lo stesso orientamento. Per ruotare la patch in posizione, utilizzare **Scostamento rotazione origine**.
* **Alpha patch**:\
  Selezionate la forma usata per mascherare la patch. Se è selezionato **Input maschera**, verrà visualizzato un parametro aggiuntivo:
  * **Input maschera**: immagine/pennello\
    Importa un&#39;immagine da utilizzare come maschera oppure pittura una maschera direttamente nella **Vista 2D**.
* **Durezza patch**: 0-1\
  Regolate la sfocatura sui bordi della maschera del cerotto.
* **Scostamento rotazione origine**: 0-1\
  Scostare la rotazione della sorgente: questo ha l’effetto di ruotare la patch.

## Guida all’uso

Un problema comune che può verificarsi durante la creazione di una luce ambientale da fotografie è rappresentato dagli artefatti che si verificano intorno al bordo superiore e inferiore della texture. Il **Nadir patch** **filtro** consente di ridurre al minimo questi problemi.

1. Aggiungere il **filtro Nadir patch** all&#39;inizio della Pila livelli.
1. Utilizzare l&#39;handle in **Vista 2D** per modificare il percorso di origine della patch.
   1. Il nadir con patch varia a seconda della posizione della sorgente. Se la sorgente si trova nella metà inferiore dello spazio della texture, il nadir inferiore verrà riparato; se la sorgente si trova nella metà superiore, il nadir superiore verrà riparato.
1. Modifica i parametri per perfezionare la Trasforma della patch in modo da nascondere al meglio cuciture e artefatti.
