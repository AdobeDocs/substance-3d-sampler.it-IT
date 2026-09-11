---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/release-notes/version-5-1-substance-3d-sampler.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 5.1 per scoprire le nuove funzioni, i miglioramenti e i miglioramenti del flusso di lavoro.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 5.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '824'
ht-degree: 2%

---


# Versione 5.1

![](../assets/welcome_digitization_tool.jpg)

Dedica meno tempo all&#39;acquisizione dei materiali e all&#39;esportazione dei gemelli digitali con strumenti nuovi e migliorati in <b>Substance 3D Sampler 5.1</b>.

Le principali novità includono:

## Distribuisci automaticamente materiali strutturati

Risparmia tempo nell’elaborazione di materiali strutturati o modellati, come i tessuti, generando automaticamente piastrelle senza interruzioni.

Ulteriori informazioni *[qui](../filters/tools/auto-tiling.md)*.

![](../assets/WhatsNew_Auto-tiling-5_1.jpg)

## Flussi di lavoro sui livelli efficienti

Migliora le prestazioni e riduci il tempo di calcolo con il livello unico Trasforma i risultati dei livelli sovrapposti in un unico insieme di mappe all’interno di un livello unificato. Rinominatele e duplicatele per una maggiore efficienza.

Ulteriori informazioni *[qui](../features-and-workflows/flatten-layers.md)*.

![](../assets/WhatsNew_Flatten-Layers-5_1.png)

## Strumenti potenti per l&#39;elaborazione della scansione

Con i filtri ottimizzati Equalizza e Clona /Clone timbro, oltre a una nuova funzione di rimozione automatica delle pieghe per i tessuti, puoi ottenere scansioni perfette in pochi clic, indipendentemente dalla complessità del materiale.

![](../assets/WhatsNew_Equalize-5_1.jpg)

## Assistenza HP Z Captis migliorata

Ora con la generazione della mappa di rugosità e il rilevamento automatico della dimensioni fisiche in modalità Studio, si ottiene un gemello digitale del materiale più dettagliato e accurato che mai!

![](../assets/whatsnew-hp-z-captis-5-1.jpg)

## Note sulla versione V5.1

*(Rilasciato: 7 agosto 2025)*

## Aggiunto:

* [vista 2D] La dimensione del pennello ora si adatta alla risoluzione della texture corrente
* [vista 3D] Attiva/disattiva la scala di visualizzazione nativa per il rendering 3D nelle preferenze
* Aggiornamento del motore di rendering di [Application]
* [Didascalia] Aggiungi la possibilità di &quot;creare quadrati&quot; durante l’anteprima
* [Captis] Rilevamento automatico dimensioni fisiche
* [Captis] L&#39;acquisizione di un nuovo materiale creerà una nuova risorsa
* [Didascalia] Modifica la selezione della risoluzione nel menu a discesa in pixel per pollice o centimetro invece della risoluzione pixel dell’area massima
* [Captis] Guida contestuale sulla calibrazione dell&#39;allineamento
* [Captis] Genera mappa di rugosità
* [Captis] Avvisa l&#39;utente se mancano i file di calibrazione predefiniti
* [Filtri] Filtro automatico in porzioni per materiali strutturati e scansioni
* [Filtri] Nuovo filtro Rimozione piega
* [Filtri] Nuove funzioni del filtro Clona /Clone timbro
* [Filtri] Nuove funzioni del filtro Equalizza
* [Livelli] Possibilità di convertire i livelli
* [Livelli] Menu di scelta rapida quando si fa clic con il pulsante destro del mouse su un livello per rinominarlo, duplicarlo, eliminarlo o convertirlo
* [Onboarding] Contenuto delle schermate di benvenuto dell’aggiornamento e Novità
* [Prestazioni] Prestazioni migliori quando si utilizza il filtro Ritaglio
* [Prestazioni] Miglioramento dell&#39;utilizzo della memoria per il vista 3D
* [Prestazioni] L’aggiornamento della vista 3D è più rapido
* [Dimensioni fisiche] Abilita &quot;display with physical ratio&quot; quando si lavora sui filtri Substance quando la Dimensioni fisiche è abilitata
* [Dimensioni fisiche] Quando si importano immagini in una pila vuota, proporre una risoluzione più coerente con le proporzioni dell’immagine
* [Azioni rapide] 3 nuove azioni rapide per l’elaborazione della scansione
* [Scripting] API per convertire i livelli
* [Scripting] Ottieni il nome file di ogni immagine di un livello di importazione immagine
* [Scripting] Nuova funzione per attivare/disattivare un determinato canale di una risorsa
* [UI] Rielaborare le icone e i pulsanti nel pannello Livelli per adattarli alle nuove funzioni
* [UI] Avvisa in caso di rimozione della creazione di luci ambientali

## Fisso:

* [Vista 2D] La selezione di &#39;visualizza con rapporto fisico&#39; potrebbe non funzionare quando si utilizzano i filtri Substance
* [capture 3D] I file SVG sono elencati nel selettore di file ma non sono supportati
* [vista 3D] Il parametro relativo all’intensità delle emissioni nelle impostazioni dello Shader non funziona
* [vista 3D] A volte la posizione della trama non è corretta durante la creazione di una nuova risorsa
* [vista 3D] Passaggio agli arresti anomali di rendering Traccia percorso su hardware non supportato
* [Applicazione] L&#39;applicazione si blocca quando si chiude il popup della misura manuale senza impostare una dimensione
* arresto anomalo [Applicazione]
* [Applicazione] Blocco in Windows durante la visualizzazione del desktop (tasto Windows + scelta rapida da tastiera tastiera D)
* [Applicazione] Possibile arresto anomalo quando si cambia lingua
* [Captis] Arresto anomalo in cui i dati di anteprima non sono validi
* [Didascalia] Impossibile ridurre completamente lo zoom dopo aver eseguito lo zoom in
* [Captis] Localizzazione mancante in alcuni passaggi della procedura guidata
* [Captis] Possibile arresto anomalo all&#39;uscita quando si utilizza Captis
* [Didascalia] La scansione non funziona se nel dispositivo mancano i file di calibrazione
* [Filtri] L’anteprima del pennello quando si utilizza il filtro Timbro Clona /Clone potrebbe essere errata in base alle dimensioni della texture e del pennello
* [Filtri] Dimensioni di output errate dopo l’utilizzo del filtro Ingrandisci
* [Filtri] Icone mancanti per i filtri Rotazione e Stilizzazione dell&#39;ambiente
* [Filtri] L’aggiornamento di alcuni filtri può causare un rendering errato
* [Livelli] Primo rendering non corretto durante la fusione di due materiali
* [Livelli] Il pulsante per aggiornare i livelli mostra &quot;Aggiorna tutto&quot; anche quando è presente un solo aggiornamento
* [Livelli] Calcoli non necessari durante l’importazione di immagini nella Pila livelli
* [Prestazioni] Miglioramento della gestione del formato mappa normale per ridurre i tempi di rendering
* [Dimensioni fisiche] Il popup di misurazione manuale funziona solo dopo aver eseguito una misurazione automatica
* [Dimensioni fisiche] Risoluzione di esportazione errata nel popup Esporta quando la Dimensioni fisiche è abilitata
* [Azioni rapide] Localizzazione mancante nei nomi delle risorse generate
* [UI] L’anteprima delle risorse al passaggio del mouse potrebbe non essere visualizzata
* [UI] Facendo clic sul pulsante Ripristina valore predefinito è possibile che alcuni controlli vengano interrotti
* [UI] I messaggi di errore non vengono cancellati quando si cambia progetto
* [UI] Assicurati che il nome del materiale nella finestra della vista e nel pannello Proprietà sia vuoto quando non è presente alcuna risorsa
* [UI] Il pulsante Ripristina valore predefinito per il parametro Punto di vista non funziona
* [UI] Sovrapposizione pulsante Ripristina valore predefinito
* [UI] Alcuni pulsanti non sono selezionabili quando un pannello è disancorato
* [UI] Texture parametro V di fatturazione parzialmente nascosto in Impostazioni e vista 3D visualizzatore

## Rimosso:

* [capture 3D] Rimuovi supporto capture 3D
* [Applicazione] Rimuovi supporto macOS x86
