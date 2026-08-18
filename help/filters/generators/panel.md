---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/panel.html"
breadcrumb-title: ''
description: Utilizza il generatore pannelli in Substance 3D Sampler per creare pattern di pannelli e texture di superfici segmentate per i materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pannello
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '576'
ht-degree: 0%

---


# Pannello

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-metalpanels-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Convertite il materiale in pannelli. Il filtro Pannelli è particolarmente indicato per i materiali metallici.

*Materiale metallico continuo convertito in pannelli.*

![](../../assets/3d-filters-cropped-0015-panel-in.jpg){width="200px"}

![](../../assets/3d-filters-cropped-0014-panel-out.jpg){width="200px"}

</td>
</tr>
</table>

## Parametri

**Predefiniti**

Usa i predefiniti per modificare rapidamente i parametri e creare un effetto specifico.

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **X importo**: 0-20\
  Modificare il numero di pannelli sull’asse X
* **Importo Y**: 0-20\
  Modificare il numero di pannelli sull’asse Y
* **Tipo cucitura**:\
  Selezionare diversi stili di cuciture tra i pannelli
* **Usa elementi di fissaggio**:\
  Aggiungete elementi di fissaggio tra i pannelli. Quando questa opzione è attivata, la sezione Elementi di fissaggio viene visualizzata nell&#39;elenco dei parametri.

**Pannelli**

* **Importo offset**: 0-1\
  Effettuate lo scostamento di ogni riga di pannelli rispetto alla riga precedente in base a una percentuale delle dimensioni del pannello.
* **Scostamento casuale**: 0-1\
  Aggiungere un valore casuale allo scostamento di ogni riga
* **Scostamento verticale**: attiva/disattiva\
  Consente di passare dallo scostamento orizzontale allo scostamento verticale.
* **Tensione sgrossata**: da -1 a 1\
  Modificate le normali di ciascun pannello in modo che sembri proiettato verso l’interno o l’esterno a causa della pressione.
* **Rughe**: 0-1\
  Aggiungere sottili ammaccature e rughe ai pannelli
* **Variazione colore**: 0-1\
  Variare in modo casuale il colore tra i singoli pannelli
* **Variazione riflessione**: 0-1\
  Variare in modo casuale la rugosità dei singoli pannelli

**Cuciture**

La selezione dei parametri in questa sezione dipende dal valore scelto in **Parametri di base > Tipo di giunzione**.

* ***Spazio vuoto***
  * **Larghezza cucitura**: 0-1\
    Modificare la larghezza tra i pannelli
  * **Variazione spazio**: 0-1\
    Spostate leggermente i pannelli per far variare la larghezza degli spazi tra i pannelli
  * **Arrotondamento angoli aperture**: 0-1\
    Arrotondare i bordi dei pannelli
  * **Smusso spazio**: 0-1\
    Smussare i bordi dei pannelli
* ***Saldatura***
  * **Larghezza cucitura**: 0-1\
    Modificare la larghezza tra i pannelli
  * **Qualità saldatura**: 0-1\
    Regolate l&#39;uniformità della saldatura
  * **Scolorimento della saldatura**: 0-1\
    Modificate la quantità di scolorimento della saldatura rispetto al colore dei pannelli.
  * **Sostituisci materiale saldatura**: attiva/disattiva\
    Abilitate per personalizzare il materiale utilizzato per creare la saldatura. Se questa opzione è attivata, verranno visualizzati i seguenti parametri aggiuntivi:
    * **Colore materiale saldatura**: selezione colore\
      Selezionate il colore della saldatura. Questa modifica sarà comunque influenzata da **alterazione del colore della saldatura**.
    * **Rugosità materiale saldatura**: 0-1\
      Regolate la ruvidità della cucitura di saldatura tra i pannelli
* ***Sovrapposizione***
  * **Larghezza cucitura**: 0-1\
    Modificare la larghezza tra i pannelli
* ***Cucitura in piedi***
  * **Larghezza cucitura**: 0-1\
    Modificare la larghezza tra i pannelli

**Elementi di fissaggio**

* **Tipo elemento di fissaggio**:\
  Selezionare lo stile del fissaggio da utilizzare tra i pannelli
* **Fastener**: 3-10\
  Modificate il numero di elementi di fissaggio da utilizzare lungo il bordo tra due pannelli.
* **Dimensione elemento di fissaggio**: 0-1\
  Modificare le dimensioni degli elementi di fissaggio
* **Variazione elemento di fissaggio**: 0-1\
  Scostare la posizione degli elementi di fissaggio
* **Sostituisci materiale elemento di fissaggio**: attiva/disattiva\
  Modificare il materiale utilizzato per gli elementi di fissaggio separatamente dal materiale di base. Quando questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Colore materiale elemento di fissaggio**: selezione colore\
    Selezionare il colore del materiale di fissaggio
  * **Rugosità materiale elemento di fissaggio**: 0-1\
    Modificare la rugosità del materiale di fissaggio

**Avanzate**

* **Normale** **Intensità**: 0-3\
  Regolare l’intensità normale complessiva del materiale
* **Intervallo Height cuciture**: 0-1\
  Modifica l’elevazione delle cuciture personalizzate sopra i pannelli
* **Intervallo Height elementi di fissaggio**: 0-1\
  Modificare il height degli elementi di fissaggio
* **Profondità Height AO**: 0-1\
  Modificare la forza dell’AO
* **Raggio AO**: 0-1\
  Modificare il raggio dell’AO
