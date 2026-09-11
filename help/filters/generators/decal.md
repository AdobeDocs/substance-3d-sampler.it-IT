---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/decal.html"
breadcrumb-title: ''
description: Utilizza il generatore di decalcomanie in Substance 3D Sampler per creare pattern di decalcomanie e texture di sovrapposizione per le superfici di materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Decal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Decalcomania
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 1%

---


# Decalcomania

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-decal-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro Decalcomania consente di aggiungere istanze di un altro materiale in una posizione specifica. Questo è utile per aggiungere elementi come adesivi o dettagli specifici che potrebbero non essere facili da generare proceduralmente.

Le immagini seguenti mostrano il **filtro decalcomania** utilizzato per aggiungere danni al cemento.

![](../../assets/3d-2d-filters-cropped-0045-decal-in.jpg)

Prima di aggiungere la decalcomania, lo strato di base in cemento è pulito e integro.

![](../../assets/3d-2d-filters-cropped-0044-decal-out.jpg)

Con il **filtro decalcomania** applicato, al materiale vengono aggiunte crepe realistiche e danni.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Modalità Affiancamento**:\
  Determina se affiancare le maniglie in **Vista 2D**.\
  H significa Orizzontale, mentre V significa Verticale.
* **Corrispondenza colore materiale inferiore**: 0-1\
  Regola i colori del materiale della decalcomania in modo che corrispondano al valore cromatico dei livelli sottostanti.
* **Metodo fusione normale**:\
  Regola il modo in cui le normali vengono fuse tra il materiale decalcomania e gli strati sottostanti
* **Fusione opacità normale**: 0-1\
  Modificare l&#39;opacità delle normali del materiale decalcomania
* **Posizione Height decalcomanie**: 0-1\
  Regola il height della decalcomania rispetto al height dei livelli sottostanti
* **Scala Height decalcomanie**: 0-1\
  Modifica il contrasto della mappa dell&#39;altezza per il materiale della decalcomania

**Parametri avanzati**

* **Trasformazione decalcomania**:\
  Regola i valori di Trasforma della matrice per la decalcomania. In generale, è più semplice utilizzare le maniglie del **Vista 2D** per regolare il Trasforma della decalcomania.
* **Decalcomania** **Scostamento**: da -1 a 1\
  Regola lo scostamento della decalcomania.

## Guida all’uso

Per utilizzare il filtro Decalcomania:

1. Aggiungere il filtro Decal alla Pila livelli
1. Sotto il livello decalcomania, apparirà uno slot di input
1. Trascina il materiale della decalcomania nello slot di input del livello della decalcomania

Puoi regolare i parametri del filtro nel **pannello Proprietà** selezionando il livello Decal.

Puoi regolare i parametri del materiale di input della decalcomania nel **pannello Proprietà** selezionando il materiale nello slot di input.
