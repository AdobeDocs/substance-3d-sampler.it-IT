---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/generators/atlas-scatter.html"
breadcrumb-title: ''
description: Usate il generatore di Atlas scatter in Substance 3D Sampler per dispersione gli elementi dagli atlanti delle texture su superfici di materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Atlas Scatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas scatter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '745'
ht-degree: 0%

---


# Atlas scatter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_AtlasScatter_18_N_D.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il filtro Atlas scatter dispersione le istanze degli elementi all&#39;interno di un materiale atlas attraverso il materiale sottostante. L’Atlas scatter è utile per spargere in modo naturale foglie, rocce o immondizia attraverso un materiale.

Le immagini seguenti mostrano il **filtro Atlas scatter** in azione.

![](../../assets/3d-2d-filters-cropped-0037-atlas-scatter-in.jpg)

Prima che venga utilizzato il **filtro Atlas scatter**, abbiamo un materiale fangoso di base, non molto eccitante.

![](../../assets/3d-2d-filters-cropped-0036-atlas-scatter-out.jpg)

Aggiungendo il **filtro Atlas scatter** con un atlas dei ciottoli, il materiale diventa più interessante poiché i ciottoli sono sparsi e si fondono realisticamente con il fango sottostante.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **X importo**: 1-64\
  Numero di istanze nell&#39;asse X
* **Importo Y**: 1-64\
  Numero di istanze nell&#39;asse Y
* **Modalità Fusione**:\
  Metodo usato per fondere con i livelli sottostanti
* **Scala**: 0-5\
  Scala delle istanze
* **Posizione casuale**: 0-2\
  Aumenta o riduce lo scostamento casuale delle istanze dalle posizioni della griglia
* **Scala Height**: 0-1\
  Regolare un height di istanze
* **Conformità allo sfondo**: 0-1\
  Modifica dell’impatto dei valori di height sottostanti sulle istanze disperse
* **Colore dallo sfondo**:
  * **Tonalità:** 0-1\
    Regolare la tonalità delle istanze
  * **Saturazione:** 0-1\
    Regolare la saturazione delle istanze
  * **Valore:** 0-1\
    Regolare il valore delle istanze

**Maschera**

* **Maschera personalizzata**: attiva/disattiva\
  Attivare o disattivare l’uso di una maschera personalizzata. Quando questa opzione è attivata, compaiono i seguenti comandi:
  * **Maschera personalizzata:**\
    Selezionate un file da usare come maschera o usate la modalità pennello per applicare manualmente la maschera.
  * **Inverti maschera:**\
    Invertire il valore della maschera
* **Maschera casuale**: 0-1\
  Nascondere una percentuale di istanze in modo casuale

**Dimensioni**

* **Scala casuale**: 0-1\
  Quantità di scala randomizzata da applicare a ciascuna istanza
* **Scala senza sovrapposizione**: 0-1\
  Regolare la scala di ciascuna istanza per evitare la sovrapposizione delle istanze

**Height**

* **Scostamento Height**: da -1 a 1\
  Scostare il height di istanze dal livello di base 0
* **Scostamento Height casuale**: 0-1\
  Aggiungi un valore casuale allo scostamento del height per ogni istanza
* **Inclina da Bg Pendenza**: 0-1\
  Regola l’inclinazione delle normali in base alla pendenza di sfondo
* **Smoothness sfondo**: 0-2\
  Regolare lo Smoothness dello sfondo

**Rotazione**

* **Rotazione**: 0-1\
  Ruotare tutte le istanze di un valore impostato
* **Rotazione casuale**: 0-1\
  Aggiungi un valore casuale alla rotazione di ogni istanza
* **Rotazione da Bg Pendenza**:\
  Ruotare le istanze in base alla pendenza del materiale sottostante

**Regolazioni materiale Atlas**

* **Regolazione colore**:\
  Regolare i valori HSV per l’atlante
* **Colore casuale**:\
  Aggiungi casualità ai valori HSV impostati in **Regolazione colore**
* **Rugosità da sfondo**: 0-1\
  Usa la rugosità dello sfondo invece della rugosità di ogni istanza.
* **Regolazione rugosità**: da -1 a 1\
  Aggiungete o sottraete da ogni istanza i valori di rugosità.
* **Normale casuale**: 0-1\
  Ruota le normali di ogni istanza di un valore casuale per istanza
* **Ricalcola Occlusione ambientale**: attiva/disattiva\
  Se attivata, i valori di Occlusione ambientale verranno ricalcolati in base ai valori di height modificati

**Rilevamento forme atlante**

* **Intervallo pattern**:\
  Limita le risorse disponibili dall&#39;atlas in base alla posizione. Lascia i valori X e Y su 0 per utilizzare tutte le risorse dell&#39;atlas.
* **Abbassa opacità atlante**: 0-4
* **Precisione rilevamento forme**:\
  Selezionare l&#39;algoritmo per il rilevamento delle forme. Atlanti diversi saranno adatti a diversi algoritmi di rilevamento. Nessuna modalità di errore è più costosa a livello di calcolo di entrambe le altre opzioni.
* **Ignora forma più piccola di**: 0-1\
  Utilizzate questa opzione per evitare che le forme molto piccole diventino elementi singoli.

Guida all’uso

Il filtro Atlas scatter è un metodo utile per la dispersione delle risorse tra materiali quali foglie, pietre o rifiuti. Per utilizzare il filtro Atlas scatter, è necessario un materiale atlas per l&#39;elaborazione del filtro.

>[!NOTE]
>
> Un materiale atlante è un materiale che contiene una raccolta (o atlante) di risorse separate. Ad esempio, Sampler include per impostazione predefinita le foglie di alloro secche, un materiale dell’atlante in quanto contiene una raccolta di foglie in un unico materiale in cui ciascuna foglia è separata l’una dall’altra. Il nodo Atlas scatter utilizza un algoritmo per gestire ogni foglia del materiale atlante come elemento separato.

Per utilizzare il filtro Atlas scatter:

1. Aggiungere il filtro Atlas scatter alla Pila livelli
1. Sotto il livello di Atlas scatter, appare uno slot di input
1. Trascina il materiale dell&#39;atlante nello slot di ingresso Atlas scatter

Potete regolare i parametri della dispersione nel **pannello Proprietà** selezionando il livello Atlas scatter.

Potete regolare i parametri del materiale dell&#39;atlante nel **pannello Proprietà** selezionando il materiale nello slot di input.
