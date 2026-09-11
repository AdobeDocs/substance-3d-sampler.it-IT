---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/generators/embossing.html"
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

Testo o pattern Effetti rilievi sui materiali.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Dimensione Effetto rilievo**: 0-1\
  Modificare le dimensioni di ogni istanza
* **Distanza Effetto rilievo**: 0-1\
  Modificare il thickness di linee in rilievo
* **Selezione pattern**:\
  Selezionare il pattern da rendere effetto rilievo. Da qui potete selezionare un testo in effetto rilievo o un pattern personalizzato.
* **Affianca Motivo X**: 1-64\
  Modificare il numero di istanze sull&#39;asse X
* **Affianca Motivo Y**: 1-64\
  Modificare il numero di istanze sull&#39;asse Y

**Effetto rilievo**

* **Usa Effetto rilievo bordo**: attiva/disattiva\
  Attiva/disattiva l’effetto rilievo del bordo del pattern scelto
* **Inversione Effetto rilievo bordo**: attiva/disattiva\
  Invertire il height dell&#39;effetto rilievo del bordo
* **Intensità Effetto rilievo bordo**: 0-1\
  Modificare l’intensità dell’effetto effetto rilievo
* **Usa Effetto rilievo riempimento**: attiva/disattiva\
  Attivate/disattivate l’effetto rilievo del riempimento del pattern scelto
* **Inversione Effetto rilievo riempimento**: attiva/disattiva\
  Invertire il height dell’effetto effetto rilievo riempimento
* **Intensità Effetto rilievo riempimento**: 0-1\
  Modificare l’intensità dell’effetto effetto rilievo

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
  Abilita questa opzione per ignorare la rugosità del materiale sottostante con un valore di rugosità personalizzato ovunque appaia l’effetto effetto rilievo.\
  Quando questa opzione è attivata, verrà visualizzato un controllo **Rugosità pattern** per impostare la rugosità.
* **Usa criterio metallico**: attiva/disattiva\
  Abilitate questa opzione per ignorare i valori metallici del materiale sottostanti con un valore metallico personalizzato ovunque appaia l’effetto effetto rilievo.\
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
* **Occlusione ambientale Gomma**: 0-1
* **Opacità Gomma**: 0-1

**Parametri avanzati**

Questi parametri consentono di regolare i valori per l&#39;intero materiale.

* **Luminosità**: 0-1
* **Contrasto**: da -1 a 1
* **Scostamento tonalità**; 0-1
* **Saturazione**: 0-1
* **Intensità normale**; 0-1

## Guida all’uso

Aggiungete il filtro Rilievo nella parte superiore della Pila livelli, quindi iniziate a regolare i parametri.

I parametri più importanti sono in genere **Parametri di base > Selezione pattern** per modificare il pattern che verrà utilizzato dal filtro e **Pattern > Usa porzione pattern** per attivare e disattivare l’Affiancamento.
