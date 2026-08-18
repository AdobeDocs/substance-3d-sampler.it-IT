---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/water.html"
breadcrumb-title: ''
description: Utilizza il filtro Acqua di Substance 3D Sampler per aggiungere effetti acqua, umidità e umidità ai materiali e alle texture.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Water
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Acqua
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Acqua

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-water-18-n-d.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Usa **Filtro Erosione** per indossare macchie alte sul tuo materiale.

![](../../assets/water-compare.png)

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Livello dell&#39;acqua**: 0-1\
  Regolate il height dell&#39;acqua.
* **Acqua scura**: 0-1\
  Rendete l&#39;acqua più chiara o più scura.
* **Umidità bordi**: 0-1\
  Regolate la distanza al di sopra della linea dell&#39;acqua in cui il materiale appare bagnato.
* **Abilita Dirt sull&#39;acqua**: attiva/disattiva\
  Aggiungete del dirt alla parte superiore dell&#39;acqua modificando leggermente la mappa di rugosità. La sezione **Dirt** viene visualizzata solo se questo parametro è abilitato.
* **Maschera personalizzata**: attiva/disattiva\
  Quando questa opzione è attivata, viene visualizzato il controllo aggiuntivo seguente:
  * **Maschera**: immagine/pennello\
    Selezionate un&#39;immagine da utilizzare come maschera personalizzata o usate il pennello per colorare una maschera direttamente nella **vista 2D**.

**Dirt**

Questa sezione viene visualizzata solo se è abilitato **Parametri di base > Abilita Dirt sull&#39;acqua**

* **Quantità Dirt**: 0-1\
  Regolate la quantità di dirt che galleggia sulla superficie dell&#39;acqua.
* **Intensità Distorsione**: 0-1\
  Controllare la quantità di distorsione del dirt di superficie in base all&#39;intersezione tra l&#39;acqua e il resto del materiale.
* **Intensità bordo Dirt**: 0-1\
  Gestite l’intensità del dirt di superfici vicino ai bordi della maschera del dirt.
* **Distanza Dirt Dal Bordo**: 0-1\
  Controlla la distanza del bordo del dirt dall&#39;intersezione tra le aree bagnate e asciutte del materiale.
* **Precisione bordo**: 0-1\
  Regola la precisione del bordo del dirt.
* **Alterazione bordo**: 0-1\
  Alterate il bordo per interrompere l’uniformità della superficie del dirt.

**Parametri avanzati**

* **Distanza bagnata bordi**: 0-1\
  Controllate la distanza nelle aree asciutte in cui si estende l’umidità dei bordi.
* **Quantità sfocatura Profondità**: 0-1\
  Regolate la quantità di sfocatura del colore di base per le aree subacquee.
* **Opacità sfocatura Profondità**: 0-1\
  Regolate la trasparenza dell&#39;acqua.
* **Colore fango**: selezione colore\
  Modificate il colore del dirt che si trova sopra la superficie dell&#39;acqua.
* **Opacità fango**: 0-1\
  Regolare la trasparenza dei fanghi.
