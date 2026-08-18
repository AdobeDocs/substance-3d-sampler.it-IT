---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/atlas-splitter.html"
breadcrumb-title: ''
description: Usate lo strumento Atlas splitter di Substance 3D Sampler per dividere gli atlanti delle texture in singole mappe di texture per la modifica del materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Splitter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas splitter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---


# Atlas splitter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlassplitter-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

L&#39;**Atlas splitter** è uno strumento utile per organizzare e visualizzare gli elementi di un atlas.

Le immagini seguenti mostrano l&#39;**Atlas splitter** in azione.

![](../../assets/3d-2d-filters-cropped-0039-atlas-splittter-in.jpg)

L&#39;immagine sopra mostra un materiale atlas aggiunto alla pila di livelli. utilizzare l&#39;**Atlas splitter** per selezionare elementi specifici dall&#39;atlas.

![](../../assets/3d-2d-filters-cropped-0038-atlas-splitter-out.jpg)

Con l&#39;**Atlas splitter** aggiunto alla pila di livelli, è possibile concentrarsi su una singola foglia o su qualsiasi altro elemento del materiale dell&#39;atlas.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Visualizzazione griglia**: attiva/disattiva\
  Passare dalla vista griglia alla vista individuale degli elementi. Se questa opzione è attivata, vengono visualizzati i seguenti parametri aggiuntivi:
  * **Opacità griglia**: 0-1\
    Modificare l&#39;opacità della griglia
  * **Opacità selezione griglia**: 0-1\
    Modifica l&#39;opacità del bordo attorno all&#39;elemento selezionato
  * **Scala automatica**: attiva/disattiva\
    Consente di specificare se gli elementi atlas devono essere ridimensionati in scala per riempire ogni quadrato della griglia.
* **Ritaglio automatico**: attiva/disattiva\
  Selezionare se si desidera regolare il ritaglio della forma selezionata. Se attivata, verrà visualizzata un’opzione aggiuntiva:
  * **Modalità di ritaglio automatico**:\
    Scegliete come ritagliare l&#39;elemento selezionato per riempire lo spazio del materiale.
* **Selezione forma**: 1-10\
  Modificare l&#39;elemento dell&#39;atlante selezionato. Per gli atlanti con più di 10 elementi, è possibile digitare un numero nel valore **Selezione forma** per modificare l&#39;intervallo del cursore.
* **Rotazione**: 0-1\
  Ruotare gli elementi

**Parametri avanzati**

* **Tolleranza forme piccole**: 0-1\
  Regola le dimensioni minime delle forme che devono essere raccolte dall&#39;**Atlas splitter**. Questo è utile per filtrare gli artefatti
* **Rotazione automatica**: attiva/disattiva\
  Se attivata, gli elementi verranno ruotati automaticamente per avere orientamenti simili.
* **Riduci maschera di opacità**: 0-4\
  Regola la scala della maschera di opacità. Se si aumenta questo valore, la qualità della maschera di opacità può diminuire.
* **Precisione rilevamento forme**:\
  Selezionare l&#39;algoritmo di rilevamento della forma da utilizzare.
* **Larghezza dilatazione**: 0-32\
  Modifica la dilatazione: i colori dei bordi dell&#39;elemento vengono estrusi nell&#39;area mascherata per evitare problemi di trasparenza ai bordi degli elementi atlas. Visualizzare il canale del colore di base nella **vista 2D** per visualizzare i risultati.
* **Colore sfondo personalizzato**: attiva/disattiva\
  Se questa opzione è attivata, viene visualizzato un controllo che modifica il colore di sfondo del canale normale:
  * **Colore sfondo normale**: selezione colore\
    Selezionate il colore di sfondo personalizzato del canale normale nelle parti trasparenti del materiale.
* **Colore sfondo Height**: 0-1\
  Regola il colore di sfondo del canale del height. In genere è consigliabile che lo sfondo del height corrisponda al height medio dei bordi degli elementi atlas per evitare artefatti ai bordi degli elementi.
