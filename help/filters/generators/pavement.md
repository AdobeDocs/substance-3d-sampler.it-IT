---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Utilizzate il generatore di pavimenti in Substance 3D Sampler per creare texture di pavimentazione e di superficie stradale realistiche per i materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pavement
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Marciapiede
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 1%

---


# Marciapiede

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pavement-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Converti il materiale in un pattern di pavimentazione. Il filtro Pavimento include una serie di opzioni per modificare lo stile del pattern in modo rapido e semplice.

*Esempio del **filtro Pavimento**.*

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Scala Materiali di base**: 0-1\
  Controllare la scala del materiale utilizzato in ciascun mattone
* **Spaziatura mattoni**: 0-1\
  Modificare la quantità di spazio tra i mattoni
* **Rotondità angolo**: 0-1\
  Rendete gli angoli dei mattoni più o meno arrotondati.
* **Rotondità bordo**: 0-1\
  Attenuate i bordi dei mattoni per renderli più usurati
* **Intensità inclinazione**: 0-1\
  Modificare l’intensità dell’inclinazione casuale applicata a ciascun mattone
* **Intensità elevazione casuale**: 0-1\
  Modificate la variazione dei height di mattoni l&#39;uno rispetto all&#39;altro.

**Pattern**

Ogni pattern dispone di un diverso set di parametri che verranno visualizzati quando il pattern viene selezionato in **Tipo di pattern**. Sperimentate con i parametri per vedere l&#39;effetto.

* **Tipo di motivo**:\
  Selezionate il pattern per disporre i mattoni.

**Giunto**

* **Giunto** **Height**: 0-1\
  Modificare il height del materiale tra i mattoni
* **Larghezza giunto**: 0-1\
  Regolare la distanza di sovrapposizione del materiale tra i mattoni e i bordi dei mattoni
* **Variazione larghezza giunto**: 0-1\
  Regola la casualità della **Larghezza giunto**
* **Luminosità articolazione**: 0-1\
  Modificate l&#39;aspetto del materiale tra i mattoni. Questa funzione è utile ad esempio per le maschere.

**Parametri avanzati**

* **Intensità superficie**: 0-1\
  Consente di controllare l’intensità delle normali per le deformazioni della superficie, ad esempio crepe o ammaccature.
* **Dimensioni superficie (cm)**: 0-1000\
  Regolare la dimensioni fisiche rappresentata dal materiale
* **Scala Height di superficie (cm)**: 0-1000\
  Modificare lo spazio fisico rappresentato dalla mappa dell&#39;altezza
* **Smoothness superficie**: 0-1\
  Controllare la quantità di variazione e dettaglio nella superficie
* **Surface Poke**: 0-1\
  Aggiungere danni o variazioni alla superficie modificando casualmente il height e le normali
* **Soglia maschera poke superficie**: 0-1\
  Modifica la soglia della maschera utilizzata per controllare **Surface Poke**
* **Abilita mappa scala**: attiva/disattiva\
  Usare una mappatura per regolare le dimensioni dei mattoni in base alla loro posizione
* **Intensità Scalemap**: 0-1\
  Regolate l’impatto della smerigliatura sulla scala dei mattoni.
