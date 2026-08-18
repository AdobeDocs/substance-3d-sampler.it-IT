---
breadcrumb-title: ''
description: Scoprite come utilizzare il Materiale di base in Sampler, un ottimo punto di partenza per un editing efficiente dei materiali.
title: Usa come bitmap
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 4%

---


# Materiale base

Il **Materiale di base** è un livello di materiale fondamentale progettato per offrire un punto di partenza rapido e flessibile durante la creazione di materiali in Sampler. Viene visualizzato un insieme completo di parametri che si adattano automaticamente al **modello di materiale** utilizzato dal materiale (OpenPBR o ASM), consentendo di costruire qualsiasi cosa, dalle superfici semplici ai materiali complessi e fisicamente ricchi.
Indipendentemente dal fatto che tu stia iniziando da un predefinito o costruendo un materiale da zero, il Materiale di base ti garantisce sempre di iniziare da una **base chiara, prevedibile e modificabile**.

## Consapevolezza del modello di materiale (OpenPBR vs ASM)

Il Materiale di base è in grado di riconoscere **modelli di materiali**.
Ciò significa che le proprietà disponibili e i valori predefiniti variano a seconda che il materiale venga creato utilizzando:

* OpenPBR
* ASM (Adobe Standard Material)

Entrambe le versioni hanno lo stesso scopo, ma espongono **diversi gruppi di parametri e comportamenti**, che corrispondono al modello di materiale sottostante:

### Materiale di base

I gruppi di parametri includono:

* Base
* Speculare
* Trasmissione
* Sottosuperficie
* Rivestimento
* Fuzz
* Emissione
* Pellicola sottile
* Geometria
* Varie

Questi parametri si allineano con la rappresentazione unificata basata su dati fisici di OpenPBR e sono progettati per l&#39;interoperabilità nell&#39;ecosistema 3D più ampio.

### MATERIALE DI BASE ASM

I gruppi di parametri includono:

* Superficie
* Assorbimento
* A dispersione
* Traslucidità
* Rivestimento
* Lucentezza
* Emissione
* Geometria

Questo layout riflette il modello di ombreggiatura ASM e garantisce la continuità con i flussi di lavoro basati su ASM esistenti.

>[!NOTE]
>
>Il Materiale di base si adatta sempre al modello di materiale del materiale a cui viene applicato. Un Materiale di base applicato a un materiale di OpenPBR non esporrà i parametri ASM e viceversa.

## Valori uniformi e mappe personalizzate

Per ogni parametro esposto, il Materiale di base offre due metodi di lavoro:

### Valori uniformi (predefinito)

Per impostazione predefinita, i parametri utilizzano valori uniformi (cursori o selettori colore).
Ciò consente di definire rapidamente l’aspetto generale del materiale senza alcun input di texture.

I valori uniformi sono ideali per:

* Blocco dei materiali
* Creazione di superfici pulite e semplici
* Definizione di un punto di partenza visivo

### Mappe personalizzate

Se disponi già di mappe texture, puoi **ignorare qualsiasi valore uniforme** abilitando il relativo **input mappa personalizzato**.

* Attiva/disattiva l&#39;opzione mappa personalizzata per il parametro
* Collegate la texture esistente
* La mappa sostituisce completamente il valore uniforme

## Predefiniti

Il Materiale di base include un set di **predefiniti**, visibili come miniature nella parte superiore del pannello Proprietà.
I predefiniti forniscono:

* Valori Materiali di base preconfigurati
* Un modo veloce per iniziare da una configurazione visivamente significativa
* Punti di partenza coerenti e leggibili per tipi di superfici comuni

La selezione di un predefinito non blocca il materiale. Tutti i parametri restano completamente modificabili.

## &quot;Applicare valori predefiniti&quot; durante la creazione di un materiale

Quando create un nuovo materiale, potete scegliere di applicare i valori predefiniti dal pannello Crea nuovo materiale.
Funzionamento di questo

* Sostituisce i valori predefiniti del Materiale di base con i valori rappresentati dalla miniatura predefinita selezionata
* Fornisce un punto di partenza visivo immediato, anziché valori predefiniti neutri
* Consente di ridurre l’effetto &quot;pagina vuota&quot; all’inizio di un nuovo materiale

Cosa non fa

* Non blocca i valori
* Non impedisce ulteriori modifiche
* Non aggiunge automaticamente le mappe texture

Potete immaginarlo come la scelta del punto di partenza, senza limitare il punto di partenza.

## Attivazione dei canali: un passo fondamentale

Affinché un parametro di Materiale di base abbia un effetto visibile, il canale corrispondente deve essere abilitato nelle Impostazioni canale del materiale.

### Best practice

Prima di modificare un parametro, verificate che il relativo canale sia abilitato
Abilita solo i canali necessari per mantenere il materiale pulito ed efficiente