---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/tools/transform.html"
breadcrumb-title: ''
description: Usate lo strumento Trasforma di Substance 3D Sampler per ridimensionare, ruotare, traslare e manipolare i livelli di texture e materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Transform
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Trasforma
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '553'
ht-degree: 1%

---


# Trasforma

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-transformgeneric-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Usa lo **strumento Trasformazione** per spostare, ridimensionare o ruotare l&#39;immagine o il materiale.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Modalità di controllo**:\
  Scegli se visualizzare i parametri per controllare la trasformazione con cursori oltre alle maniglie **vista 2D**.

  Con **Widget e parametri** selezionati, verranno visualizzati i controlli aggiuntivi seguenti:

  * **Trasformazione sicura**: attiva/disattiva\
    Abilita o disabilita le trasformazioni sicure. Quando questa opzione è attivata, il nodo di trasformazione manterrà la suddivisione in porzioni ed eviterà di perdere i dettagli dei pixel a causa di piccoli scostamenti e rotazioni. Ciò riduce la libertà di controllare la trasformazione e l&#39;attivazione di **Trasformazione sicura** nasconderà alcuni parametri.
  * **Mantieni rapporto**: attiva/disattiva\
    Quando questa opzione è attivata, sarà visibile un solo parametro **Scala** che controlla il ridimensionamento simultaneo su entrambi gli assi. Quando sono disattivati, saranno disponibili i controlli che consentono di modificare separatamente la scala sugli assi Orizzontale e Verticale.

    * **Scala**: 0-1\
      A seconda che **Mantieni rapporto** sia abilitato o disabilitato, saranno disponibili 1 o 2 cursori per regolare la scala.
  * **Rotazione**; 0-360\
    Ruota l&#39;input all&#39;interno delle maniglie.
  * **Inclina**: da -1 a 1\
    Inclina l&#39;input all&#39;interno delle maniglie sugli assi orizzontale e verticale.
* **Scostamento posizione**: da -1 a 1\
  Scostate la trasformazione dalla posizione iniziale sugli assi orizzontale e verticale.
* **Rifletti in orizzontale**: attiva/disattiva\
  Specchiatura orizzontale dell&#39;input
* **Rifletti in verticale**: attiva/disattiva\
  Specchiatura verticale dell&#39;input

**Parametri avanzati**

* **Trasformazione**:\
  Regola la trasformazione delle maniglie con i cursori invece che nella **vista 2D**.
  * **Scala X**: 0-2
  * **Inclina verticale**: da -7,44 a 2
  * **Inclina orizzontale**: 0-1
  * **Scala Y**: 0 - 13,15
* **Disattiva trasformazione per canale**: attiva/disattiva\
  Quando questa opzione è attivata, appariranno altri controlli che consentono di disattivare questa trasformazione per ogni canale.

## Guida all’uso

Fai clic sullo **strumento Trasformazione** per aggiungere un nuovo livello del filtro Trasformazione nella parte superiore della serie di livelli.

La creazione o la selezione di un livello di filtro Trasformazione apre automaticamente la **vista 2D**. Con il livello Trasforma selezionato, nella parte superiore della **vista 2D** viene visualizzata una **barra degli strumenti**.

## Funzionalità

![](../../assets/alchemist-2020-2-transform-1.gif){width="300px"}

### Sposta

Per spostare il livello:

1. Passate il mouse all’interno del riquadro di trasformazione
1. Il cursore si trasformerà in quattro frecce
1. Fate clic e trascinate per spostare il riquadro di trasformazione.

### Scala

Per ridimensionare il livello:

1. Passate il mouse su una delle maniglie lungo il bordo o l’angolo del riquadro di trasformazione
1. Il cursore si trasformerà in quattro frecce.
1. Fate clic e trascinate per ridimensionare il riquadro di trasformazione.

>[!NOTE]
>
> Le maniglie posizionate sull&#39;angolo del riquadro di trasformazione consentono di ridimensionare due quote contemporaneamente, mentre le maniglie posizionate sul bordo del riquadro di trasformazione vi limitano a ridimensionare in una sola quota.

### Ruota

Per ruotare il livello:

1. Passate il mouse fuori dal riquadro di trasformazione ma nella **vista 2D**.
1. Accanto al cursore appare una piccola freccia orizzontale.
1. Fate clic e trascinate per ruotare la casella di trasformazione.

>[!NOTE]
>
> Potete modificare il centro di rotazione trascinando il piccolo cerchio al centro del riquadro di trasformazione. Il riquadro di trasformazione ruota sempre attorno a questo cerchio.

## Barra degli strumenti

![](../../assets/transform-toolbar.png){width="200px"}

La barra degli strumenti contiene le seguenti scelte rapide:

* Rendi quadrato: regola il ridimensionamento della trasformazione corrente per renderla quadrata.
* Rotazione di +90° (a destra): rotazione di 90° in senso orario.
* Rotazione di -90° (a sinistra): rotazione di 90° in senso antiorario.
* Reimposta centro di rotazione: reimposta il centro di rotazione al centro della casella Trasforma.
* Ripristina trasformazione: ripristina la posizione predefinita dello strumento Trasformazione.
