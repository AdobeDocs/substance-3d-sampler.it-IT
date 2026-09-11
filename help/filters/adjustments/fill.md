---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/fill.html"
breadcrumb-title: ''
description: Utilizzate il filtro Riempimento in Substance 3D Sampler per riempire le aree della texture con colori a tinta unita o pattern per i flussi di lavoro di creazione del materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Fill
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Riempimento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '741'
ht-degree: 4%

---


# Riempimento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/Fill_Icon_1.png)

**In:** Regolazioni

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il **filtro Riempimento** consente di sostituire o regolare i valori di canali specifici in base a un valore selezionato.
Da Sampler 6.0, il filtro Riempimento adatta i propri parametri in base al tipo di canale a cui viene applicato. In questo modo si garantisce che i controlli disponibili corrispondano sempre al significato fisico e al tipo di dati del canale selezionato e che il filtro possa essere applicato a qualsiasi mappa, anche da flussi di lavoro personalizzati.

Nelle immagini seguenti, il canale del colore di base è stato sostituito.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/fillnobc.png.img.png){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/fillbc.png){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parametri

<b>Applicato a...</b>

Il menu a discesa Applicato a... determina il canale interessato dal filtro Riempimento.
**In questo elenco vengono visualizzati solo i canali attualmente abilitati nelle impostazioni dei canali del materiale.** Se il canale da riempire non è disponibile:

* Apri il pannello delle impostazioni dei canali (nella parte inferiore della barra di navigazione sinistra)
* Fare clic su &quot;Modifica elenco&quot;
* Abilita il canale desiderato
* Riapplicare o aggiornare il filtro Riempimento

Una volta attivato, il canale diventa disponibile nel menu a discesa Applicato a...

<b>Parametri di base</b>

I parametri del filtro Riempimento **cambiano in modo dinamico a seconda del tipo di canale** selezionato in Applicato a... Esistono quattro insiemi di parametri, ognuno dei quali corrisponde a un tipo specifico di mappa.

### Parametri della mappa colore

Utilizzato quando il filtro Riempimento viene applicato ai canali di colore.

#### Canali di esempio:

* Colore di base
* Colore rivestimento
* Colore sottosuperficie...

#### Parametri disponibili

* Colore
Seleziona il colore RGB utilizzato per riempire il canale.
* Valore personalizzato
Passa a Attiva/Disattiva per aprire la mappa personalizzata. Seleziona un&#39;immagine per sostituire il canale selezionato con o pittura direttamente nella **Vista 2D**.
* Seme casuale
Modifica la casualità utilizzata quando sono attivate le variazioni procedurali.
* Metodo fusione
Determina il modo in cui il riempimento si fonde con i livelli sottostanti (ad esempio: Copia, Aggiungi, Moltiplica).
* Opacità
Regola l’opacità delle nuove informazioni del canale in relazione alle informazioni esistenti del canale. In altre parole, questo controlla l’opacità della maschera usata per applicare il nuovo riempimento del canale.

Questa modalità viene in genere utilizzata per inizializzare o ignorare le informazioni sul colore.

### Parametri della mappa della scala dei grigi

Utilizzato quando il filtro Riempimento viene applicato a canali in scala di grigi scalari.

#### Canali di esempio:

* Ruvidità speculare
* Metallicità base
* Opacità
* Height...

#### Parametri disponibili

* Valore
Imposta un singolo valore in scala di grigi per il canale.
* Seme casuale
Modifica la casualità utilizzata quando sono attivate le variazioni procedurali.
* Valore personalizzato
Passa a Attiva/Disattiva per aprire la mappa personalizzata. Seleziona un&#39;immagine per sostituire il canale selezionato con o pittura direttamente nella **Vista 2D**.
* Metodo fusione
Copia, Aggiungi (Scherma lineare), Subastratta, Moltiplica, Aggiungi sotto, Max (Schiarisci), Min (Scurisci), Interruttore, Dividi, Sovrapponi, Schermo, Luce soffusa.
Seleziona il metodo di fusione per fondere l’input personalizzato con i livelli sottostanti.
* Opacità
Regola l’opacità delle nuove informazioni del canale in relazione alle informazioni esistenti del canale. In altre parole, questo controlla l’opacità della maschera usata per applicare il nuovo riempimento del canale.

Questa modalità è utile per definire proprietà fisiche uniformi, come rugosità costante o valore di opacità.

#### Mappa normale parametri

Utilizzato quando il filtro Riempimento viene applicato a **Canali normali**.

##### Canali di esempio:

* Normale
* Rivestimento normale

##### Parametri disponibili

* Seme casuale
Modifica la casualità utilizzata quando sono attivate le variazioni procedurali.
* Valore personalizzato
Passa a Attiva/Disattiva per aprire la mappa personalizzata. Seleziona un&#39;immagine per sostituire il canale selezionato con o pittura direttamente nella **Vista 2D**.
* Opacità
Regola l’opacità delle nuove informazioni del canale in relazione alle informazioni esistenti del canale. In altre parole, questo controlla l’opacità della maschera usata per applicare il nuovo riempimento del canale.

Questa modalità viene utilizzata principalmente per ripristinare o neutralizzare le informazioni normali o per stabilire una linea di base pulita prima di aggiungere dettagli normali.

### Parametri di valori uniformi

Utilizzato per i canali che si basano su un singolo valore fisico uniforme anziché su una mappa texture.

#### Canali di esempio

* Specular IOR...

#### Parametri disponibili

* Seme casuale
Modifica la casualità utilizzata quando sono attivate le variazioni procedurali.
* Valore
Definisce il valore costante applicato al canale.
* Modalità Fusione
Tra Normale e Moltiplica

Questa modalità è particolarmente utile quando si utilizzano comportamenti avanzati per i materiali introdotti tramite i modelli, in cui alcune proprietà sono controllate da valori scalari anziché da mappe.

## Casi d’uso tipici

Il filtro Riempimento viene in genere utilizzato per:

* Inizializzare i canali durante la creazione di un materiale da zero
* Ignora valori di canale esistenti
* Imposta proprietà fisiche uniformi (ad esempio rugosità fissa o metallizzazione)
* Neutralizzare i canali, ad esempio Normale, prima di ricostruire i dettagli
* Modifica rapida delle proprietà avanzate, come fuzz, traslucidità o valori di rivestimento

Poiché il filtro Riempimento si adatta automaticamente al canale selezionato, fornisce un flusso di lavoro coerente e prevedibile per tutti i tipi di materiale.
