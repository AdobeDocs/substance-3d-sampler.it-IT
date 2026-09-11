---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/adjustments/color-variation.html"
breadcrumb-title: ''
description: Utilizzate il filtro Variazione colore in Substance 3D Sampler per aggiungere diversità di colore e variazione alle texture per materiali più naturali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Variation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Variazione colore
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '534'
ht-degree: 1%

---


# Variazione colore

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-colorpalette-18-n-d.png)

**In:** Regolazioni

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro Variazione colore consente di sostituire contemporaneamente più colori nel canale di diffusione o di colore di base. Questo è simile al **filtro Sostituzione colore**, ma mentre **Variazione colore** consente di regolare più colori in un filtro, **Sostituzione colore** offre un maggiore controllo sulla maschera utilizzata per sostituire i colori e può essere utilizzata su più canali.

Nelle immagini seguenti, il **filtro Variazione colore** è stato utilizzato per regolare non solo il colore bianco sottostante per farne apparire un turchese pallido, ma anche per aumentare il contrasto di molte delle macchie più piccole.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0047-color-variation-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0046-color-variation-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Conteggio colori**: 1-10\
  Modifica il numero di colori che sostituiranno i colori del canale
* **Variazione luminosità**: 0-1\
  Regola l’impatto dei valori di luminosità sul colore sostituito
* **Segmentazione**:\
  Basate la maschera utilizzata per applicare i colori su un canale diverso.
* **Modalità di selezione colore**:\
  Scegliete se selezionare i colori sorgente manualmente o automaticamente. Se viene scelta la modalità di selezione **Manuale**, utilizzare le maniglie nella **Vista 2D** per selezionare i colori.
  * **Mostra Helper testo**: Attiva/Disattiva\
    Questo controllo è visibile solo se **Modalità di selezione colore** è impostato su **Manuale**. Quando questa opzione è attivata, **Mostra Helper testo** aggiungerà etichette di testo alle maniglie nella **Vista 2D** per distinguere più facilmente le maniglie di selezione del colore
* **Colore X**: selezione colore\
  Il numero di controlli colore disponibili dipende dal valore selezionato con **Conteggio colori**. Per ogni colore, selezionate il nuovo colore per sostituire il colore del materiale originale.

## Guida all’uso

Il **filtro Variazione colore** consente di modificare rapidamente più colori del canale di colore di base contemporaneamente. Per alcuni materiali questo può essere utile per effettuare piccole regolazioni, ma il **filtro Variazione colore** è il più adatto per rivedere completamente i colori del materiale con un singolo filtro.

Per utilizzare il **filtro Variazione colore**:

1. Aggiungere il **filtro Variazione colore** alla Pila livelli
1. Regolate il numero di colori da sostituire con **Conteggio colori**. Il filtro sostituirà tutti i colori del canale: il controllo **Conteggio colori** consente di impostare quanti nuovi colori verranno sostituiti da quelli esistenti.
1. Facoltativamente, seleziona una **Segmentazione** o un canale diverso su cui basare i colori. Ad esempio, potete selezionare il canale metallico e usare **Metodo selezione colore > Manuale** per posizionare una maniglia su un valore metallico nero e un&#39;altra su un valore metallico bianco. Con questa configurazione puoi controllare singolarmente il colore delle parti metalliche e non metalliche del tuo materiale.
1. Selezionate una **modalità di selezione colore**. Con la modalità manuale selezionata, le maniglie vengono visualizzate in **Vista 2D** che consente di selezionare il colore di base originale che verrà sostituito dal nuovo colore. Abilita **Mostra Helper testo** per tenere traccia della maniglia collegata al colore.
1. Modificare i valori di colore con i controlli **Colore 1 - 10**.
1. Regolate la **Variazione luminosità** per regolare l&#39;impatto della luminosità sulla sostituzione del colore. Con una **variazione di luminosità** bassa, potete appiattire completamente i colori del materiale oppure utilizzare una **variazione di luminosità** elevata per mantenere i dettagli dai colori originali.
