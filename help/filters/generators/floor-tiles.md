---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/floor-tiles.html"
breadcrumb-title: ''
description: Usa il generatore di piastrelle di Floor in Substance 3D Sampler per creare realistici motivi di piastrelle da pavimento e texture in ceramica per i materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Floor Tiles
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Floor porzioni
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '787'
ht-degree: 0%

---


# Floor porzioni

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-floortiles-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro Floor suddivide il materiale sottostante e lo converte in una disposizione di Floor.

Le immagini seguenti mostrano un materiale di cemento convertito in piastrelle da pavimento con un motivo a scacchi.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0031-floor-tiles-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0030-floor-tiles-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

Parametri

<b>Parametri di base</b>

* <b>Numero casuale</b>: \
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* <b>Numero di materiali</b>: \
  Modifica il numero di materiali da convertire in piastrelle. Il primo materiale è determinato dai livelli sotto il livello del filtro Floor porzioni. Se selezionata, la seconda opzione può essere aggiunta come input.
* <b>Intensità materiali di input</b>: 0-1 \
  Misura in cui i dettagli dei materiali di input saranno visibili nelle porzioni
* <b>Inverti materiali</b>: Attiva/Disattiva \
  Quando si utilizzano due materiali, sostituire il punto in cui appaiono nelle porzioni.
* <b>Variazione colore</b>: 0-1 \
  Misura in cui il colore varia tra ogni porzione dello stesso materiale
* <b>Raggio smusso</b>: 0-1 \
  Dimensione del riquadro rispetto alla dimensione del mortaio
* <b>Profondità smussata</b>: 0-1 \
  Profondità del mortaio
* <b>Rotondità smusso</b>: 0-1 \
  Determina gli angoli esterni delle porzioni
* <b>Grana di superficie</b>: 0-1 \
  Determina la misura in cui il dettaglio del materiale originale viene visualizzato sulle mappe normale e di altezza delle porzioni
* <b>Maschera pattern</b>: input.  \
  Ogni maschera del pattern Porzioni Floor ha a disposizione un diverso set di parametri. Qui copriamo solo i parametri disponibili per <b>riquadro quadrato</b>

  * <b>Numero casuale </b>\
    Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
  * <b>X Importo </b>\
    Regolare il numero di colonne di porzioni
  * <b>Importo Y</b> \
    Regolare il numero di linee di porzioni
  * <b>Sfumatura </b> \
    Regola la proporzione delle dimensioni del riquadro rispetto alle dimensioni del mortaio.
  * <b>Luminanza casuale</b>\
    Poiché la luminanza influenza la mappa di altezza, questo parametro rimuove casualmente alcune porzioni
  * <b>Rotazione motivo</b>: 0-1 \
    Ruota l’angolo delle porzioni tenendole lontane l’una dall’altra per evitare sovrapposizioni
  * <b>Scala forme:</b> 0-1 \
    Regola la proporzione delle dimensioni del riquadro rispetto alle dimensioni del mortaio.
  * <b>Scala forma casuale </b>\
    Aggiunge una differenza casuale nelle dimensioni delle porzioni
  * <b>Dimensioni forma </b>\
    Regolare la lunghezza e la larghezza delle porzioni
  * <b>Dimensioni forma casuali </b>\
    Aggiungere un po’ di casualità alla lunghezza e alla larghezza delle porzioni
  * <b>Modalità scostamento posizione</b>: elenco a discesa
  * <b>Scostamento posizione </b>\
    Sposta casualmente le colonne delle porzioni in modo che le porzioni non siano allineate orizzontalmente
  * <b>Posizione casuale</b> \
    Posiziona le porzioni casualmente sulla superficie, con una potenziale sovrapposizione tra le porzioni
  * <b>Rotazione forma </b>\
    Ruotare l&#39;angolo delle porzioni nella stessa direzione, mantenendole il più vicino possibile con una potenziale sovrapposizione
  * <b>Rotazione forma casuale </b>\
    Ruotate in modo casuale l&#39;angolo delle porzioni, mantenendole il più vicino possibile con una potenziale sovrapposizione

<b>Spazio vuoto</b>

* <b>Colore spazio</b>: selezione colore \
  Modificare il colore tra le porzioni
* <b>Rugosità spazio</b>: 0-1 \
  Modificate il valore di rugosità del materiale tra le porzioni.
* <b>Metallico spazio</b>: 0-1 \
  Modificate il valore metallico del materiale tra le porzioni.
* <b>Height spazio</b>: 0-1 \
  Modificate il valore height del materiale tra le porzioni.
* <b>Irregolarità spazio</b>: 0-1 \
  Regola la precisione con cui il mortaio verrà applicato tra le porzioni.

<b>Età</b>

* <b>Inclinazione Floor</b>: 0-1 \
  Aggiungere un’inclinazione alle porzioni casuali
* <b>Height casuale</b> \
  Aggiungere una differenza di height tra le porzioni in modo casuale
* <b>Dirt</b>: 0-1 \
  Aggiungere dirt alle porzioni e allo spazio
* <b>Danni</b>: 0-1 \
  Rimuovete casualmente alcuni frammenti dal bordo dello smusso di ciascuna porzione
* <b>Imperfezioni</b> \
  Aggiungere piccoli fori e imperfezioni nelle porzioni

<b>Parametri tecnici</b>

* <b>Scala materiale</b>: 0-1 \
  Scala del materiale all’interno delle porzioni
* <b>Intensità normale</b>: 0-1 \
  Regolate l’intensità della normale dello spazio vuoto, delle porzioni e del materiale all’interno

<b>Guida all&#39;uso</b>

Il filtro Porzioni Floor consente di convertire rapidamente il materiale in porzioni. La maggior parte del filtro Floor è abbastanza semplice da usare, tranne quando si utilizzano più materiali. Per utilizzare due materiali:

1. Imposta <b>Parametri di base > Numero di materiali</b> su 2.
1. Trascinate il secondo materiale nello slot di input visualizzato sotto il filtro Piastrelle di pavimento nella pila dei livelli.
1. Regolate i parametri del materiale di input fino a ottenere il risultato desiderato.

Anche se è possibile aggiungere più materiali e filtri in un unico slot di input, in genere è consigliabile evitare questa operazione in quanto aggiunge complessità e può rendere più difficile la lettura del materiale in un secondo momento. Creare invece nuovi materiali nel progetto e quindi trascinare un&#39;istanza del nuovo materiale nello slot di input. Quando si aggiorna il materiale nel progetto, il materiale viene aggiornato automaticamente nello slot di input, offrendo pieno controllo e semplificando la Pila livelli.
