---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/tiling.html"
breadcrumb-title: ''
description: Usa lo strumento Affiancamento di Substance 3D Sampler per creare pattern di Affiancamento uniformi da texture per superfici di materiale ripetibili.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Tiling
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Affiancamento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Affiancamento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizza il **filtro Affiancamento** per rendere affiancabile il materiale. Anche il **filtro Affianca** rende affiancabile il materiale, ma ogni filtro funziona in modo diverso. Se riscontri che il **filtro Affiancamento** non funziona, prova il **filtro Sezione**.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Mostra cucitura**: attiva/disattiva\
  Scegliere se visualizzare la giuntura
* **Usa maschera**: attiva/disattiva\
  Se questa opzione è attivata, potete creare una maschera personalizzata per controllare la posizione della giuntura
  * **Maschera**: immagine/pennello\
    Importa un&#39;immagine da utilizzare come maschera o utilizza il pennello per pittura una maschera direttamente nella **Vista 2D**

**Edge**

* **Rileva bordi**: attiva/disattiva\
  Attivate o disattivate la rilevazione dei bordi in base ai canali di materiale per creare una transizione più organica tra i livelli di materiale. Se selezionata, vengono visualizzati i seguenti parametri aggiuntivi:
  * **Usa soglia per canale**: attiva/disattiva\
    Se questa opzione è attivata, vengono visualizzati parametri aggiuntivi per regolare singolarmente la soglia di ciascun canale.
    * **Colore di base di soglie**: 0-1
    * **Soglia normale**: 0-1
    * **Height di soglie**: 0-1
  * **Soglia**: 0-1\
    Regolate il valore di soglia utilizzato per trovare la giuntura.
  * **Sfocatura**: 0-1\
    Sfoca l’area intorno alla giuntura
  * **Smoothness**: 0-2\
    Regolate lo smoothness della giuntura. Questo può aiutare a evitare gli artefatti
  * **Risoluzione griglia**: 1-11\
    Regolate la risoluzione della griglia su cui viene disegnata la giuntura. Una risoluzione inferiore può migliorare le prestazioni ma ridurre la qualità della giuntura
  * **Usa Colore di base**: attiva/disattiva\
    Consente di specificare se le informazioni sul colore di base devono essere considerate nella generazione di cuciture
  * **Usa normale**: attiva/disattiva\
    Cambia se le informazioni normali vengono considerate nella generazione della cucitura
  * **Usa Height**: attiva/disattiva\
    Consente di specificare se le informazioni sul height devono essere considerate nella generazione di cuciture
  * **Scostamento taglio**: 0-0,5\
    Regolare lo scostamento della giuntura sugli assi X e Y

**Parametri avanzati**

* **Trasforma**: 0-2\
  Regolare i valori di Trasforma della matrice. Aumentate i valori X e W per regolare la quantità di sovrapposizione esistente tra il materiale sottostante e quello sovrapposto.
* **Scostamento**: 0-1\
  offset del materiale sugli assi X e Y
* **Filtraggio**:\
  Selezionate il metodo di filtraggio da usare sui pixel ridimensionati. Il filtro bilineare sfoca i pixel, mentre il filtro più vicino mantiene il bordo netto tra i pixel.
* **Dimensione input**: 0-8192\
  Regola la dimensione dell&#39;input in pixel sugli assi X e Y.

## Guida all’uso

Il **filtro Affiancamento** funziona in due passaggi:

1. Scala e sposta il materiale per generare una sovrapposizione.
1. Quindi varia il bordo sovrapposto per nascondere la giuntura.

Pertanto, per utilizzare il **filtro Divisione in porzioni**, è possibile ottenere i risultati migliori regolando queste due parti del processo.

1. Aggiungi il **filtro In porzioni** alla parte superiore dello stack di livelli
1. Usate le maniglie per Trasforma il materiale in modo che vi sia una sovrapposizione sufficiente a nascondere la giuntura.
   1. La modifica in scala del materiale può essere utile per creare una sovrapposizione, ma può anche causare la perdita di dettagli.
1. Regola i parametri nella sezione **Edge** per regolare la giuntura.

Per alcuni materiali, l&#39;utilizzo del solo **filtro Affiancamento** produrrà comunque artefatti o problemi lungo la giuntura. In questo caso, è consigliabile utilizzare altri filtri, ad esempio **Clona /Clone timbro**, per correggere i problemi di giuntura e Affiancamento.

È buona norma lavorare sull’Affiancamento del materiale nelle fasi iniziali del processo di creazione del materiale: non appena un elemento non Affiancamento viene aggiunto al materiale, è buona norma assicurarsi che venga affiancato prima di continuare a lavorare. I filtri di Sampler sono progettati in modo da non rompere i materiali di affiancamento. Ciò significa che, una volta che le porzioni di materiale sottostanti, è possibile continuare a lavorare con i filtri e i materiali inclusi di Sampler e il materiale sarà ancora affiancato.
