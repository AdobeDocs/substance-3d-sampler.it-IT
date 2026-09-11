---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-2.html"
breadcrumb-title: ''
description: Consultate le note sulla versione per Substance 3D Sampler versione 4.2 per informazioni su Image to Material, funzione di ingrandimento dell'intelligenza artificiale e controlli della risoluzione basati sull'intelligenza artificiale.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 4.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '861'
ht-degree: 0%

---


# Versione 4.2

<b>Substance 3D Sampler 4.2</b> introduce una nuova versione basata su IA di <b>Image to Material</b> e una nuova funzionalità <b>AI Upscale</b>. Questa versione include il controllo completo della risoluzione per livello.

*Data di pubblicazione: 05 settembre 2023*

## Da immagine a materiale - Nuova versione

![](../assets/sa_whats-new-screen_v4-2-0_image_to_material.png)

Da immagine a materiale genera per te canali di materiale (colore di base, rugosità, normale, spostamento e metallico) da una singola immagine.

La versione aggiornata di Immagine in materiale migliora la generazione del materiale e la gamma di materiali supportati.

Ora, Image to Material (Da immagine a materiale) è stato addestrato su tutti i tipi di materiale, generando risultati migliori per Tessuto, plastica, legno, ecc.

La versione aggiornata ha un nuovo parametro per selezionare il tipo di materiale per generare accuratamente tutti i canali e regolare automaticamente l&#39;intervallo.

![Substance 3D Sampler con il nuovo filtro Da immagine a materiale (basato su intelligenza artificiale)](../assets/Materia_ScreenShot.png "Da immagine a materiale - Nuova versione")

## Ingrandimento dell&#39;IA

![](../assets/F5W_vAHaYAQLsz7.jpg)

Grazie al nuovo livello Ingrandisci, Sampler migliora le caratteristiche del materiale o dell&#39;immagine moltiplicando per 2 o 4 la risoluzione della risorsa (materiale o immagine).

Ciò consente di aumentare la qualità e il livello di dettagli delle texture a bassa risoluzione mantenendo la coerenza delle caratteristiche tra le mappe durante l&#39;ingrandimento delle texture.

Il filtro Ingrandisci consente di migliorare i canali colore di base, normale, height, rugosità e metallico del materiale.

Per ottimizzare la qualità dei risultati, il filtro Ingrandisci deve essere utilizzato sui dati (materiale e immagine) alla loro risoluzione originale senza precedenti modifiche di risoluzione.

![Filtro di ingrandimento aggiunto al progetto Substance 3D Sampler](../assets/Upscale_Highlighted.png "Filtro di ingrandimento")

## Risoluzione livello

![](../assets/sa_whats-new-screen_v4-2-0_layer-resolution.png)

Il nuovo sistema di Risoluzione livello consente di avere il pieno controllo della risoluzione di ogni livello. Un livello assume la risoluzione delle dimensioni del documento o le risoluzioni del livello sottostante.

La risoluzione viene visualizzata su ciascun livello per visualizzare facilmente l’impatto del tuo lavoro sulla risoluzione del materiale.

Ciò consente di aumentare la qualità dei materiali, ma anche le prestazioni mentre lavori sulle tue risorse.

## Tutorial

## Nota di rilascio

<b>4.2 DORAYAKI</b>

*(Rilasciato il 5 settembre 2023)*

<b>Aggiunto</b>:

* [Content] Filtri Image to Material (AI) e Delighter notevolmente migliorati
* [Content] Nuovo filtro Ingrandisci
* [Content] Il filtro Ritaglio ha ora una risoluzione di output dinamica.
* [Modello di creazione materiale] Aggiungi impostazione dimensioni documento.
* [Material Creation Template] Nuovo pulsante di attivazione/disattivazione &quot;Add a crop&quot;.
* [Modello di creazione del materiale] Nuovo interruttore &quot;Ingrandisci materiale&quot;
* [Modello creazione materiale] Visualizza le dimensioni dell&#39;immagine importata
* [Modello creazione materiale] Fornisci un feedback quando non è possibile utilizzare alcune immagini importate
* [Modello di creazione del materiale] Avvisa quando le dimensioni dell&#39;immagine non sono coerenti
* [Modello di creazione materiale] Nuovi avvisi e descrizioni comandi
* [Livelli] Visualizza la risoluzione dei livelli nella Pila livelli
* [Livelli] La risoluzione di calcolo dei livelli può ora essere impostata su Dimensione documento o Dimensione input
* [Livelli] Mostra la risoluzione dei livelli nella Pila livelli
* [Livelli] Impostate i criteri di risoluzione dei livelli su Input documento o Input livello quando applicabile
* [Layers] Avvisa l’utente quando un filtro Ingrandisci viene aggiunto manualmente e fornisce la documentazione necessaria
* [Livelli] Avvisa l’utente quando esegue un ingrandimento lineare e propone di utilizzare il filtro Ingrandisci
* [Livelli] Il calcolo di un livello di immagine in materiale (AI) ora può essere annullato più rapidamente, per migliorare i tempi di rendering durante l’ottimizzazione della Pila livelli
* [Livelli] Il calcolo di un livello di ingrandimento ora può essere annullato più rapidamente per migliorare i tempi di rendering durante l’ottimizzazione della Pila livelli
* [Esporta] Consenti l’override della risoluzione delle texture esportate
* [Esporta] L’elenco Canali da esportare è ora ordinato
* [Esporta] Visualizza la risoluzione del canale nell’elenco canali da esportare
* [Applicazione] Nuova preferenza per abilitare o disabilitare le reti neurali con accelerazione GPU
* [UI] Menu a discesa con risoluzione migliorata
* [UI] Nuove icone per i filtri Trasforma trama, Elaborazione post trama e Intreccio
* [UI] Rinomina il pannello &quot;Condividi&quot; in &quot;Esporta&quot;
* [Scripting] Aggiungi il supporto per la risoluzione dell’output dei livelli all’API di esportazione
* [Scripting] Sono stati aggiunti ritaglio, ingrandimento e dimensione del documento all’API di importazione delle immagini
* [Onboarding] Nuove esercitazioni
* [Onboarding] Contenuto delle schermate di benvenuto dell’aggiornamento e Novità
* [Engine] Aggiorna Substance Engine alla versione 9.0.1

<b>Corretto:</b>

* [capture 3D] Miglioramento della denominazione delle opzioni di precisione nei parametri delle impostazioni di allineamento
* [Applicazione] L’importazione di immagini con non multipli di 16 dimensioni può causare un arresto anomalo
* [Applicazione] Arresto anomalo di duplicazione di una risorsa nel pannello Progetto
* [Applicazione] Arresto anomalo di cambio di risorse nel pannello Progetto
* [Contenuto] Il disegno di una maschera personalizzata per il filtro Snow non funziona correttamente
* [Parametri esposti] Le modifiche ai parametri esposti possono andare perdute quando si cambia materiale
* [Interoperabilità] L&#39;invio di un materiale dal pannello Esporta può provocare un arresto anomalo
* [Livelli] Riempimento in base al contenuto interrompe l’elaborazione quando si passa da un input di immagine singola a un input di materiale
* [Livelli] Arresto anomalo dopo la duplicazione di una Luce ambientale che contiene un materiale
* [Livelli] Il livello di importazione immagine visualizza un nome immagine errato nel pannello Proprietà se il file immagine è stato rinominato
* [Livelli] A volte una rotella viene visualizzata su un livello inattivo
* [Livelli] A volte la modifica dell’utilizzo dell’output di un’immagine in un livello di importazione di immagini non funziona
* [Layers] Composizioni nella finestra Modello di creazione
* [UI] Problemi relativi allo stato attivo nella descrizione del menu della vista 3D
* [UI] Se il nome del file è troppo lungo, il nome dell&#39;immagine potrebbe essere in overflow
* [UI] Problemi minori di layout della barra degli strumenti dei pennelli quando si utilizza la gomma
* [UI] Le stringhe vengono troncate in alcune lingue nel pannello Impostazioni visualizzatore
* [UI] Mentre viene visualizzato il menu a comparsa della finestra della vista, premendo &quot;spazio&quot; si crea un nuovo progetto
