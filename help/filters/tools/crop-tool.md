---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/crop-tool.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Taglierina di Substance 3D Sampler per ritagliare e ridimensionare i livelli di texture e materiale con un controllo preciso delle dimensioni.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Crop tool
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Strumento taglierina
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '707'
ht-degree: 0%

---


# Strumento taglierina

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-crop-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Usa lo **strumento Taglierina** per regolare il ritaglio dell&#39;immagine o del materiale. Lo **strumento Taglierina** funziona in modo molto simile allo **strumento Trasformazione**. Con lo **strumento Trasformazione**, le modifiche apportate al riquadro Trasforma si comportano in modo da uno a uno con l&#39;immagine sottostante, pertanto aumentando la scala del riquadro Trasforma le dimensioni dell&#39;immagine sottostante aumentano. Con lo **strumento taglierina**, questa relazione viene invertita e aumentando la scala del riquadro di ritaglio vengono ridotte le dimensioni dell&#39;immagine sottostante. Per questo motivo, quando si utilizza lo **strumento Taglierina**, può essere utile impostare la **vista 2D** in modo da visualizzare gli input dei livelli, anziché gli output dei materiali predefiniti.

Lo **strumento taglierina** è utile per regolare le immagini con proporzioni non standard. Ad esempio, puoi usare lo strumento taglierina per regolare la scala di un’immagine importata tramite i parametri Dimensione input nel **pannello Proprietà**.

>[!NOTE]
>
> Tieni presente che lo **strumento Taglierina** può funzionare su immagini o materiali. Se esiste un’immagine o un canale di scansione nella pila di livelli sotto il **livello di ritaglio**, il **filtro Ritaglio** verrà applicato al canale di scansione. Se non esiste alcun canale di immagine o scansione, il **filtro Ritaglio** modificherà il materiale.

Nelle immagini seguenti puoi vedere lo **strumento Taglierina** in azione.

![](../../assets/3d-2d-filters-cropped-0047-crop-in.jpg)

Si noti che la vista 2D è impostata per visualizzare Input livello in modo che le maniglie nella **vista 2D** mostrino l&#39;area dell&#39;input che diventerà l&#39;output.

![](../../assets/3d-2d-filters-cropped-0046-crop-out.jpg)

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Dimensione input**: 0-8192\
  Regola la dimensione dell&#39;input in pixel sugli assi X e Y.

**Parametri avanzati**

* **Filtraggio**:\
  Selezionate il metodo di filtraggio applicato ai pixel ridimensionati. Il filtro bilineare sfoca i pixel l’uno nell’altro, mentre il filtro Più vicino mantiene i bordi dei pixel.
* **Trasformazione Ritaglio**: 0-1\
  Modificate i valori della matrice della trasformazione. La modifica di questi valori può fornire un controllo più preciso della rotazione e del ridimensionamento e consente inoltre di inclinare le maniglie di ritaglio.
* **Scostamento ritaglio**: 0-1\
  Spostate il ritaglio dalla posizione iniziale.

## Guida all’uso

>[!NOTE]
>
> Il filtro Taglierina ha una propria risoluzione: ritaglierà e produrrà una risoluzione adeguata a seconda del materiale o dell’immagine ritagliata. Per mantenere i risultati migliori, inserisci i livelli precedenti in Input Max e usa un Ingrandimento per ingrandire i risultati finali.

Fai clic sullo **strumento Taglierina** per aggiungere un nuovo livello del filtro Taglierina nella parte superiore della serie di livelli.

La creazione o la selezione di un livello di filtro Ritaglio apre automaticamente la **vista 2D**. Con il livello Ritaglio selezionato, nella parte superiore della **vista 2D** viene visualizzata una barra degli strumenti.

## Funzionalità

>[!NOTE]
>
> Il filtro Ritaglio esegue l’inverso dello spostamento, della scala o della rotazione richiesti. Se il filtro Ritaglio non risulta corretto, l’opzione Trasforma potrebbe risultare più utile.

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
