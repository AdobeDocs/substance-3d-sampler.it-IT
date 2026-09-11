---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/crop-tool.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Taglierina di Substance 3D Sampler per ritagliare e ridimensionare texture e livelli di materiale con un controllo preciso delle dimensioni.
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

Usa lo **strumento Taglierina** per regolare il ritaglio dell&#39;immagine o del materiale. Lo **strumento taglierina** funziona in modo molto simile allo **strumento Trasforma**. Con lo **strumento di Trasforma**, le modifiche apportate alla casella di Trasforma si comportano in modo unidirezionale rispetto all&#39;immagine sottostante, pertanto l&#39;aumento della scala della casella di Trasforma comporta l&#39;aumento delle dimensioni dell&#39;immagine sottostante. Con lo **strumento taglierina**, questa relazione viene invertita e aumentando la scala del riquadro di ritaglio vengono ridotte le dimensioni dell&#39;immagine sottostante. Per questo motivo, quando si utilizza lo **strumento Taglierina**, può essere utile impostare **vista 2D** in modo da visualizzare gli input di livello, anziché gli output di materiale predefiniti.

Lo **strumento taglierina** è utile per regolare le immagini con proporzioni non standard. Ad esempio, puoi usare lo strumento taglierina per regolare la scala di un’immagine importata tramite i parametri Dimensione input nel **pannello Proprietà**.

>[!NOTE]
>
> Tieni presente che lo **strumento Taglierina** può funzionare su immagini o materiali. Se nella Pila livelli sotto il **livello di ritaglio** è presente un&#39;immagine o un canale di scansione, al canale di scansione verrà applicato il **filtro Ritaglio**. Se non esiste alcun canale di immagine o scansione, il **filtro Ritaglio** modificherà il materiale.

Nelle immagini seguenti puoi vedere lo **strumento Taglierina** in azione.

![](../../assets/3d-2d-filters-cropped-0047-crop-in.jpg)

Si noti che il Vista 2D è impostato per visualizzare gli input di livello in modo che le maniglie in **Vista 2D** mostrino quale area dell&#39;input diventerà l&#39;output.

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
* **Trasforma di ritaglio**: 0-1\
  Modificare i valori della matrice della Trasforma. La modifica di questi valori può fornire un controllo più preciso della rotazione e del ridimensionamento e consente inoltre di inclinare le maniglie di ritaglio.
* **Scostamento ritaglio**: 0-1\
  Spostate il ritaglio dalla posizione iniziale.

## Guida all’uso

>[!NOTE]
>
> Il filtro Taglierina ha una propria risoluzione: ritaglierà e produrrà una risoluzione adeguata a seconda del materiale o dell’immagine ritagliata. Per mantenere i risultati migliori, inserisci i livelli precedenti in Input Max e usa un Ingrandimento per ingrandire i risultati finali.

Fai clic sullo **strumento Taglierina** per aggiungere un nuovo livello del filtro Taglierina nella parte superiore della Pila livelli.

La creazione o la selezione di un livello di filtro Ritaglio apre automaticamente il **Vista 2D**. Con il livello Ritaglio selezionato, viene visualizzata una barra degli strumenti nella parte superiore del **Vista 2D**.

## Funzionalità

>[!NOTE]
>
> Il filtro Ritaglio esegue l’inverso dello spostamento, della scala o della rotazione richiesti. Se il filtro Ritaglio non è corretto, potrebbe risultare più utile utilizzare il filtro Trasforma.

### Sposta

Per spostare il livello:

1. Passare il mouse all’interno della casella di Trasforma
1. Il cursore si trasformerà in quattro frecce
1. Fate clic e trascinate per spostare la casella di Trasforma.

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
