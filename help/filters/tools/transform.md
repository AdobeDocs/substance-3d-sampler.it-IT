---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/transform.html"
breadcrumb-title: ''
description: Usa lo strumento Trasforma in Substance 3D Sampler per ridimensionare, ruotare, tradurre e manipolare i livelli di texture e materiale.
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

Usa lo **strumento Trasforma** per spostare, ridimensionare o ruotare l&#39;immagine o il materiale.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Modalità di controllo**:\
  Scegli se visualizzare i parametri per controllare la Trasforma con cursori oltre alle maniglie **Vista 2D**.

  Con **Widget e parametri** selezionati, verranno visualizzati i controlli aggiuntivi seguenti:

  * **Trasforma sicura**: attiva/disattiva\
    Abilita o disabilita le trasformazioni sicure. Quando questa opzione è attivata, il nodo di Trasforma manterrà l’Affiancamento ed evita di perdere i dettagli dei pixel a causa di piccoli scostamenti e rotazioni. Ciò riduce la libertà di controllare la trasformazione e l&#39;attivazione di **Trasforma sicura** nasconderà alcuni parametri.
  * **Mantieni rapporto**: attiva/disattiva\
    Quando questa opzione è attivata, sarà visibile un solo parametro **Scala** che controlla il ridimensionamento simultaneo su entrambi gli assi. Quando sono disattivati, saranno disponibili i controlli che consentono di modificare separatamente la scala sugli assi Orizzontale e Verticale.

    * **Scala**: 0-1\
      A seconda che **Mantieni rapporto** sia abilitato o disabilitato, saranno disponibili 1 o 2 cursori per regolare la scala.
  * **Rotazione**; 0-360\
    Ruota l&#39;input all&#39;interno delle maniglie.
  * **Inclina**: da -1 a 1\
    Inclina l&#39;input all&#39;interno delle maniglie sugli assi orizzontale e verticale.
* **Scostamento posizione**: da -1 a 1\
  Spostate la Trasforma dalla posizione iniziale sugli assi orizzontale e verticale.
* **Rifletti in orizzontale**: attiva/disattiva\
  Specchiatura orizzontale dell&#39;input
* **Rifletti in verticale**: attiva/disattiva\
  Specchiatura verticale dell&#39;input

**Parametri avanzati**

* **Trasformazione**:\
  Regola la trasformazione delle maniglie con i cursori invece che nel **Vista 2D**.
  * **Scala X**: 0-2
  * **Inclina verticale**: da -7,44 a 2
  * **Inclina orizzontale**: 0-1
  * **Scala Y**: 0 - 13,15
* **Disattiva Trasforma per canale**: attiva/disattiva\
  Quando questa opzione è attivata, appariranno altri controlli che consentono di disattivare questo Trasforma per ciascun canale.

## Guida all’uso

Fai clic sullo **strumento di Trasforma** per aggiungere un nuovo livello di filtro di Trasforma nella parte superiore della Pila livelli.

La creazione o la selezione di un livello di filtro di Trasforma apre automaticamente il **Vista 2D**. Con il livello di Trasforma selezionato, viene visualizzata una **barra degli strumenti** nella parte superiore del **Vista 2D**.

## Funzionalità

![](../../assets/alchemist-2020-2-transform-1.gif){width="300px"}

### Sposta

Per spostare il livello:

1. Passare il mouse all’interno della casella di Trasforma
1. Il cursore si trasformerà in quattro frecce
1. Fate clic e trascinate per spostare il riquadro di trasformazione.

### Scala

Per ridimensionare il livello:

1. Passa il mouse su una delle maniglie lungo il bordo o l’angolo della casella di Trasforma
1. Il cursore si trasformerà in quattro frecce.
1. Fate clic e trascinate per ridimensionare la casella di Trasforma.

>[!NOTE]
>
> Le maniglie posizionate sull&#39;angolo della casella di Trasforma consentono di ridimensionare due quote contemporaneamente, mentre le maniglie posizionate sul bordo della casella di Trasforma vi limitano a ridimensionare in una sola quota.

### Ruota

Per ruotare il livello:

1. Passare il mouse all&#39;esterno della casella di Trasforma ma all&#39;interno del **Vista 2D**.
1. Accanto al cursore appare una piccola freccia orizzontale.
1. Fate clic e trascinate per ruotare la casella di Trasforma.

>[!NOTE]
>
> Potete modificare il centro di rotazione trascinando il piccolo cerchio al centro della casella di Trasforma. La casella di Trasforma ruota sempre attorno a questo cerchio.

## Barra degli strumenti

![](../../assets/transform-toolbar.png){width="200px"}

La barra degli strumenti contiene le seguenti scelte rapide:

* Rendi quadrato: regola il ridimensionamento della trasformazione corrente per renderla quadrata.
* Rotazione di +90° (a destra): rotazione di 90° in senso orario.
* Rotazione di -90° (a sinistra): rotazione di 90° in senso antiorario.
* Reimposta centro di rotazione: reimposta il centro di rotazione al centro della casella di Trasforma.
* Ripristina trasformazione: ripristina la posizione predefinita dello strumento di Trasforma.
