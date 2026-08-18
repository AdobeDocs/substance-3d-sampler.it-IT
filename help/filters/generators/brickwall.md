---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/generators/brickwall.html"
breadcrumb-title: ''
description: Utilizza il generatore Brickwall in Substance 3D Sampler per creare pattern di muri di mattoni realistici e trame di muratura per i materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Brickwall
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Brickwall
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '558'
ht-degree: 0%

---


# Brickwall

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-brickwall-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

DescrizioneIl filtro Brickwall genera un motivo di mattoni basato sui livelli sottostanti. Questo è utile per la creazione di muri di mattoni (come suggerisce il nome) ma anche di pavimenti o in qualsiasi altro luogo in cui vengono utilizzati mattoni.

Nelle immagini seguenti, un materiale argilloso viene convertito in un muro di mattoni con il **filtro Brickwall.**

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0053-brickwall-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0052-brickwall-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parametri

**Predefiniti**

Scegliete tra una serie di predefiniti per emulare rapidamente uno stile specifico.

**Parametri di base**

* **Numero casuale**: numero casuale\
  Valore casuale utilizzato per determinare altri valori casuali in questo filtro.\
  Fai clic sul numero per ottenere un nuovo valore casuale. Quando è stato selezionato un valore casuale, fate clic sul nome del parametro per reimpostare il valore su 0.
* **Legame di mattoni**:\
  Unire più mattoni in base allo stile selezionato
* **Tipo mattone**:\
  Selezionare lo stile del mattone
* **Affianca**: 1-25\
  Modificate la quantità di suddivisione in porzioni sugli assi X e Y.
* **Scostamento**: 0-1\
  Modificate l&#39;offset di ogni riga di mattoni dalla riga precedente.
* **Usa colore personalizzato**: attiva/disattiva\
  Unire più mattoni in base allo stile selezionato

**Mix**

* **Modalità mista**:\
  Modificare la modalità di organizzazione dei mattoni. L&#39;uso di una **modalità Mix** crea un secondo set di mattoni che può essere controllato indipendentemente dal set di base.\
  Con **Modalità mix** impostata su **Nessuna**, in questa sezione non verrà visualizzato alcun altro parametro.
* **Tipo mattone 2**:\
  Selezionate lo stile del secondo gruppo di mattoni.
* **Scostamento Height**: 0-1\
  Scostare il height della seconda serie di mattoni

**Cemento**

* **Colore cemento**: selettore colore\
  Cambia il colore del cemento tra i mattoni.
* **Rugosità cemento**: 0-1\
  Modificate la rugosità del cemento tra i mattoni.
* **Interstizio cemento**: 0-1\
  Modificate la larghezza del cemento tra i mattoni. Modifica le dimensioni del mattone.
* **Livello cemento**: 0-1\
  Cambiare il height del cemento
* **Disturbo cemento**: 0-1\
  Regolate la planarità del cemento. A valori alti il cemento può salire sopra i mattoni.

**Età**

* **Disturbo del mattone**: 0-1\
  Regolate in modo casuale la rotazione di ciascun mattone in 3 dimensioni.
* **Esplosione mattoni**: 0-1\
  Aggiungere crepe nei mattoni
* **Bordo mattone**: 0-1\
  Danneggiare e rompere i bordi dei mattoni
* **Blocco mattone**: 0-1\
  Rimuovere i mattoni a caso
* **Variazione colore mattone**: 0-1\
  Varia il colore dei mattoni per rendere la parete meno uniforme
* **Sporgenza mattoni**: 0-1\
  Aggiungere dirt ai mattoni

**Parametri avanzati**

* **Intensità fusione Height**: 0-1\
  Regola la fusione del height dal materiale di base. Un valore pari a 0 ignora il height del materiale di base e utilizza solo i parametri del filtro Brickwall per generare le informazioni sul height. Un valore pari a 1 usa il materiale di base per generare le informazioni sul height.
* **Intensità normale**: 0-1\
  Regolare l&#39;intensità delle normali generate dal filtro Brickwall. Un valore pari a 0 significa in effetti nessuna norma.
* **Intensità Occlusione ambiente**: 0-1\
  Regolate l’intensità dell’AO. Un valore pari a 0 indica in pratica che non è presente alcuna Occlusione Ambiente.

Guida all’uso

Il filtro Brickwall suddivide il materiale sottostante in singoli mattoni che vengono poi ridisposti. Per questo motivo, il filtro Brickwall funziona meglio con superfici dure come rocce o metalli - in altre parole i materiali più adatti ad essere mattoni nel mondo reale.

Il filtro Brickwall è utile per creare un materiale di base su cui è possibile sovrapporre altri effetti, come muschio, neve o dirt.
