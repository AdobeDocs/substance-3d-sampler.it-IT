---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/adjustments/equalize.html"
breadcrumb-title: ''
description: Utilizzate il filtro Equalizza in Substance 3D Sampler per ridistribuire i valori di luminosità e migliorare automaticamente il contrasto dell’immagine.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Equalize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Equalizza
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---


# Equalizza

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-equalize-18-n-d.png)

**In:** Regolazioni

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro Equalizza regola il contrasto locale in base a un intervallo di distanza. Il filtro Equalizza ha lo scopo di ridurre le differenze significative tra i canali. Di conseguenza, è generalmente utile come parte del flusso di lavoro da immagine a materiale (B2M): il filtro Da immagine a materiale (basato sull&#39;intelligenza artificiale) include una passata Equalizza all&#39;interno del filtro per migliorare i risultati.

Le immagini seguenti mostrano il **filtro Equalizza** in azione.

![](../../assets/3d-2d-filters-cropped-0033-equalizer-in.jpg)

Prima dell&#39;aggiunta del **filtro Equalizza**, la mappa di height e il colore di base di questo materiale presentano variazioni significative.

![](../../assets/3d-2d-filters-cropped-0032-equalizer-out.jpg)

Dopo aver aggiunto il **filtro Equalizza**, sia la mappa del height che i canali dei colori di base sono più uniformi senza perdere dettagli.

</td>
</tr>
</table>

## Esercitazione sul filtro Equalizza

## Parametri

<b>Parametri di base</b>

* <b>Input affiancato</b>: attiva/disattiva\
  Quando questa opzione è attivata, trattate il materiale come se fosse affiancato ripetutamente, in modo che la modifica vicino ai bordi sia influenzata dai valori cromatici sul bordo opposto.
* <b>Raggio</b>: 0-1\
  Estende l’effetto Equalizza su un’area più ampia.
* <b>Perdita di colore</b>: 0-1\
  Controllate i colori che smarginano nell&#39;area circostante.
* <b>Dettagli locali</b>: 0-1\
  Regolate il modo in cui il filtro Equalizza tenta di mantenere i dettagli locali.

<b>*Canale*</b>

I controlli di ciascun canale funzionano allo stesso modo.

* <b>Ignora parametri comuni</b>: attiva/disattiva\
  Abilita questa opzione per personalizzare l’effetto Equalizza per questo canale. Quando questa opzione è attivata, compaiono altri controlli:
  * <b>Input affiancato</b>: attiva/disattiva\
    Quando questa opzione è attivata, trattate il materiale come se fosse affiancato ripetutamente, in modo che la modifica vicino ai bordi sia influenzata dai valori cromatici sul bordo opposto.
  * <b>Raggio</b>: 0-1\
    Estende l’effetto equalizza su un’area più ampia.
  * <b>Mantieni differenze locali</b>: attiva/disattiva\
    Abilita per far funzionare l&#39;effetto equalizza a una risoluzione più alta per mantenere i dettagli
* <b>Modalità destinazione</b>:\
  Selezionate la modalità di distorsione dell’effetto Equalizza. Per impostazione predefinita, Equalizza tenta di spostare i colori verso il colore medio del canale. Usate Parametro per orientarvi invece verso un colore o un valore scelto. Con Parametro selezionato, viene visualizzato un controllo aggiuntivo:
  * <b>Destinazione</b>: selezione colore\
    Selezionare un colore o un valore da utilizzare come destinazione per l&#39;algoritmo Equalizza.
* <b>Variazione colore personalizzata</b>: cursori HSL\
  Regolate Tonalità, Crominanza (Saturazione) e Luminanza (Luminanza) del risultato dopo aver eseguito l&#39;algoritmo Equalizza per il canale specificato.

<b>Maschera</b>

* <b>Maschera personalizzata</b>: attiva/disattiva\
  Abilita o disabilita l’utilizzo di una maschera personalizzata per questo filtro
* <b>Maschera personalizzata</b>: immagine/pennello\
  Selezionate un’immagine da usare come maschera oppure usate il pennello per colorare una maschera personalizzata direttamente nella vista 2D
* <b>Inversione maschera personalizzata</b>: attiva/disattiva
