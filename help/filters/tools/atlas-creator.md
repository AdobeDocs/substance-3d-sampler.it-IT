---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/atlas-creator.html"
breadcrumb-title: ''
description: Usa lo strumento Atlas Creator in Substance 3D Sampler per creare atlanti di texture da più immagini per un'organizzazione efficiente dei materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Creator
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Creator
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---


# Atlas Creator

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlasgenerator-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

**Atlas Creator** **filter** consente di convertire materiali e immagini in un atlas. Puoi quindi utilizzare altri filtri come **Atlas scatter** e **Atlas splitter** per utilizzare gli elementi atlas all&#39;interno dei materiali.

Le immagini seguenti mostrano un atlante delle foglie di giungla prima e dopo l&#39;elaborazione da parte del **creatore di atlanti**.

![](../../assets/3d-2d-filters-cropped-0041-atlas-creator-in.jpg)

Nell&#39;immagine precedente, un&#39;immagine atlante è stata importata e convertita in un materiale, ma non è ancora un materiale atlante perché la mappa di opacità non tiene conto dei singoli elementi.

![](../../assets/3d-2d-filters-cropped-0040-atlas-creator-out.jpg)

Dopo aver eseguito **Atlas Creator**, viene generata una mappa di opacità e l&#39;area tra gli elementi atlas viene riempita nel canale di colore di base.

</td>
</tr>
</table>

Parametri

**Parametri di base**

* **Rimuovi forme piccole**: 0-1

  Usate questa opzione per regolare le dimensioni minime degli oggetti all’interno dell’atlante. Ciò è utile per rimuovere gli artefatti.
* **Opacità - Influenza crominanza**: 0-2

  Perfeziona i bordi degli elementi atlas in base ai valori cromatici.
* **Aggiungi opacità**: immagine/pennello

  Importa un file da utilizzare come maschera o usa il pennello per colorare le aree che dovrebbero essere opache direttamente nella **vista 2D**.

Guida all’uso

## Preparare un&#39;immagine dell&#39;atlas

Prima di utilizzare il **filtro Atlas Creator**, è consigliabile verificare che l&#39;immagine atlas sia preparata correttamente.

**Atlas Creator** funziona in base al colore dell&#39;immagine e non considera la trasparenza. Ciò significa che il modo migliore per preparare l&#39;immagine atlas è assicurarsi che lo spazio tra gli elementi sia in bianco o nero uniforme, in modo che **Atlas Creator** possa generare più facilmente la maschera di opacità.

## Generare un materiale atlas da un&#39;immagine

**Atlas Creator** è progettato per convertire un&#39;immagine atlas in un atlas dei materiali.

1. Importate l’immagine sorgente nel gruppo di livelli.
1. Se viene richiesto di selezionare un modello di creazione di materiale, selezionate Da immagine a materiale. In caso contrario, con l&#39;immagine nella pila di livelli, aggiungi un filtro **Immagine da materiale (basata su IA)** sopra l&#39;immagine.
1. Attendi che il filtro **Immagine in materiale** converta l&#39;immagine di origine in un materiale. Regolate i parametri finché il risultato non vi soddisfa.
1. Aggiungi il **filtro Atlas Creator** nella parte superiore dello stack di livelli.
1. Regola i parametri di **Atlas Creator** finché i risultati non ti soddisfano.

1. Aggiungete l’immagine al gruppo di livelli. Se viene richiesto di selezionare un modello di creazione di materiale, selezionare **Usa come bitmap**.
1. Con il livello immagine selezionato, nel **pannello Proprietà** modificate il **Utilizzo output** in **Colore base**.
1. Aggiungi **Atlas Creator** nella parte superiore dello stack di livelli.
1. Regolate i parametri di **Atlas Creator** finché non siete soddisfatti dei risultati: visualizzate il canale di opacità nella **vista 2D** per visualizzare i risultati del filtro in modo più chiaro.
1. Utilizza il **pannello Esporta** per esportare i canali generati.
