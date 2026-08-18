---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embossing.html"
breadcrumb-title: ''
description: Usa il generatore Rilievo di Substance 3D Sampler per creare pattern in rilievo ed effetti di rilievo della superficie sollevata nei materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embossing
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Rilievo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---


# Rilievo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embossing-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Metti in rilievo il testo o i pattern sui tuoi materiali.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Dimensione rilievo**: 0-1\
  Modificare le dimensioni di ogni istanza
* **Distanza rilievo**: 0-1\
  Modificare il thickness di linee in rilievo
* **Selezione pattern**:\
  Selezionate il pattern da applicare all&#39;effetto rilievo. Da qui potete selezionare per riportare in rilievo il testo o un pattern personalizzato.
* **Affianca Motivo X**: 1-64\
  Modificare il numero di istanze sull&#39;asse X
* **Affianca Motivo Y**: 1-64\
  Modificare il numero di istanze sull&#39;asse Y

**Rilievo**

* **Usa rilievo bordo**: attiva/disattiva\
  Attivate/disattivate se rendere in rilievo il bordo del pattern scelto
* **Inversione rilievo bordo**: attiva/disattiva\
  Invertire il height dei bordi in rilievo
* **Intensità rilievo bordo**: 0-1\
  Modificare l’intensità dell’effetto rilievo
* **Usa rilievo riempimento**: attiva/disattiva\
  Attivate/disattivate se rendere in rilievo il riempimento del pattern scelto
* **Inversione rilievo riempimento**: attiva/disattiva\
  Invertire il height dell’effetto rilievo riempimento
* **Intensità rilievo riempimento**: 0-1\
  Modificare l’intensità dell’effetto rilievo

**Pattern**

* **Usa colore**: attiva/disattiva\
  Attivare/disattivare l’aggiunta di colore all’area in rilievo\
  Quando l&#39;opzione **Usa colore** è attivata, verrà visualizzato un altro parametro **Colore** per regolare il colore.
* **Maschera pattern** **Distanza**: 0-1\
  Modifica le dimensioni della maschera utilizzata per applicare il colore all’area in rilievo
* **Contrasto maschera pattern**: 0-1\
  Regolate il contrasto della maschera. Riducendo il contrasto, i bordi della maschera appaiono più sfocati.
* **Usa riquadro pattern**: attiva/disattiva\
  Attivate per affiancare il pattern, disattivate per avere una sola istanza. Se il pattern non è affiancato, le opzioni **Affianca pattern** non verranno visualizzate nella sezione **Parametri di base**.
* **Rotazione motivo**: 0-1\
  Ruotare il pattern
* **Scostamento motivo**: 0-1\
  Scostate ciascuna riga del pattern dalla riga precedente.
* **Usa rugosità pattern**: attiva/disattiva\
  Abilitate questa opzione per ignorare la rugosità del materiale sottostante con un valore di rugosità personalizzato ovunque venga visualizzato l’effetto rilievo.\
  Quando questa opzione è attivata, verrà visualizzato un controllo **Rugosità pattern** per impostare la rugosità.
* **Usa criterio metallico**: attiva/disattiva\
  Attivate questa opzione per ignorare i valori metallici del materiale sottostante con un valore metallico personalizzato ovunque venga visualizzato l’effetto rilievo.\
  Quando questa opzione è attivata, verrà visualizzato un controllo **Metallico pattern** per impostare la rugosità.

**Testo** - Questa sezione viene visualizzata solo se **Selezione pattern** in **Parametri di base** è impostato su **Testo**

* **Selezione font**:\
  Seleziona un carattere
* **Testo**: campo di testo\
  Digita il testo da rendere in rilievo
* **Dimensioni testo**: 0-1\
  Regolare la dimensione del font

**Gomma**

* **Gomma normale**: 0-1
* **Occlusione ambiente gomma**: 0-1
* **Opacità gomma**: 0-1

**Parametri avanzati**

Questi parametri consentono di regolare i valori per l&#39;intero materiale.

* **Luminosità**: 0-1
* **Contrasto**: da -1 a 1
* **Scostamento tonalità**; 0-1
* **Saturazione**: 0-1
* **Intensità normale**; 0-1

## Guida all’uso

Aggiungete il filtro Rilievo nella parte superiore della serie di livelli, quindi iniziate a regolare i parametri.

I parametri più importanti sono in genere **Parametri di base > Selezione pattern** per modificare il pattern che verrà utilizzato dal filtro e **Pattern > Usa porzione pattern** per attivare e disattivare la suddivisione in porzioni.
