---
breadcrumb-title: ''
description: Scopri come utilizzare i modelli di materiale in Substance 3D Sampler per creare rapidamente materiali complessi e realistici applicando effetti fisici avanzati attraverso punti di partenza semplici e pronti all’uso.
user-guide-description: ''
user-guide-title: ''
title: Predefiniti per la creazione di materiali
source-git-commit: 8777fdda4545110ed765f1d275c35bd11e71903b
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 2%

---


# Predefiniti per la creazione di materiali

I modelli di creazione dei materiali forniscono punti di partenza predefiniti per i materiali da costruzione con comportamento fisico avanzato. Ogni modello configura il modello di materiale, i canali abilitati e i parametri predefiniti necessari per un tipo specifico di superficie, consentendo di creare rapidamente materiali complessi mantenendo pieno controllo sul risultato. Le maschere sono disponibili durante la creazione di un nuovo materiale e possono essere utilizzate sia con i modelli di materiale di OpenPBR che con quelli ASM.

![Finestra Crea nuovo materiale](../../assets/6.0_materialPresets.png)

>[!TIP]
> Ulteriori informazioni sulla creazione di materiali avanzati che sfruttano i canali fuzz, subsurface e coating [sono disponibili qui.](../../features-and-workflows/create-advanced-materials/advanced-materials.md)

## Creazione di un materiale da un modello

Per creare un materiale utilizzando una maschera:

Aprite la finestra di dialogo Crea nuovo materiale. Selezionate un modello dalle schede Predefinito o Personalizzato. Regolate le impostazioni del materiale (nome, risoluzione, modello di materiale, canali). Fate clic su Crea (Create) per iniziare a lavorare con il materiale configurato.

Il modello selezionato definisce la struttura iniziale del materiale, inclusi i canali abilitati e il modo in cui sono impostati nella pila di livelli.

## Categorie predefinite

### Modelli predefiniti

I modelli predefiniti sono configurazioni di materiali pronte all’uso progettate per coprire i comportamenti più comuni dei materiali fisici. Codificano le procedure consigliate e le configurazioni di canale consigliate per ogni caso di utilizzo. I modelli predefiniti disponibili includono:

- Materiale di base Materiale standard basato su impostazioni fisiche con i canali più comuni attivati. Utilizza questo modello per materiali semplici o generici che non richiedono un comportamento specializzato.

- Anisotropia Configura il materiale per i riflessi dipendenti dalla direzione, adatto per superfici o metalli spazzolati con microdettagli orientati.

- Rivestimento Aggiunge uno strato riflettente secondario sulla parte superiore del materiale di base, consentendo effetti di vernice o di rivestimento trasparente.

- Fuzz Consente effetti di superficie morbidi e a dispersione di luce utilizzati per tessuti, fibre o materiali con un aspetto vellutato.

- Subsurface Attiva il trasporto di luce subsuperficiale per materiali come cera, plastica o superfici organiche in cui la luce penetra sotto la superficie.

- Trasparente Configura il materiale per la trasmissione della luce, adatto per materiali trasparenti sottili o simili al vetro.

Ciascun predefinito preimpostato imposta automaticamente i canali e i valori predefiniti richiesti, riducendo la configurazione manuale e la complessità tecnica.

### Predefiniti personali

I predefiniti personalizzati consentono di riutilizzare le configurazioni dei materiali. Qualsiasi predefinito di materiale creato può essere salvato come modello personalizzato e verrà visualizzato nella scheda Personalizzato. Ciò consente la creazione coerente di materiale tra progetti o team, utilizzando standard condivisi e configurazioni di canale.

## Dettagli predefinito

Il pannello Dettagli predefinito visualizza e controlla le impostazioni utilizzate per creare il nuovo materiale.

### Nome della risorsa

Definisce il nome del cespite materiale che verrà creato.

### Risoluzione

Controlla la risoluzione predefinita delle mappe di materiale (Larghezza e Height). Questa risoluzione si applica a tutti i canali abilitati al momento della creazione del materiale.

### Modello di materiale

Specifica il modello di materiale utilizzato dal materiale:

OpenPBR di flussi di lavoro ASM moderni e standardizzati basati su elementi fisici per la compatibilità con le tubazioni esistenti

Il modello selezionato viene adattato al modello di materiale selezionato.

### Aggiungi materiale di base

Quando questa opzione è attivata, Sampler crea un livello di riempimento base utilizzando un materiale di base compatibile con il modello selezionato. Ciò fornisce un risultato visivo immediato e un punto di partenza utilizzabile. Il materiale di base è adattato sia ai modelli di materiale OpenPBR che ASM.

### Applica valori predefiniti delle miniature

Quando questa opzione è attivata, il materiale viene inizializzato con i valori utilizzati per generare la miniatura di anteprima del modello, anziché con i valori di default neutri. Ciò consente di dimostrare il comportamento desiderato del modello e di disporre di una base visiva su cui iniziare a costruire.

### Modifica elenco

Fai clic su **Modifica elenco** per personalizzare il set di canali prima di creare il materiale. È possibile attivare o disattivare i canali in base alle esigenze oppure salvare la configurazione come un nuovo modello personalizzato.