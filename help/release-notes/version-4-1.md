---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-1.html"
breadcrumb-title: ''
description: Consultate le note sulla versione di Substance 3D Sampler 4.1 per informazioni sul filtro Alterazione pittura, sugli aggiornamenti del filtro Ricamo e sui miglioramenti apportati alla capture 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 4.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 4.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '812'
ht-degree: 0%

---


# Versione 4.1

<b>Substance 3D Sampler 4.1.0 </b>introduce nuovi contenuti con il filtro <b>Alterazione pittura </b> e una versione migliorata del filtro <b>Ricamo </b>. Questo aggiornamento include alcuni miglioramenti al capture 3D.

*Data di pubblicazione: 28 marzo 2023*

## Alterazione dipinto

Il filtro Alterazione pittura consente di alterare i materiali disegnando curve sulla vista 2D.\
L&#39;opzione Raddrizza consente di riallineare i materiali per un flusso di lavoro di suddivisione in porzioni semplice e uniforme.

## Ricamo

Il nuovo generatore di ricami consente di creare patch per ricami da un singolo file vettoriale di immagine o da un disegno.\
Può ricamare fino a 6 colori e combina diverse tecniche di giuntura.

## Tutorial

## Nota di rilascio

<b>4.1.2 CANNOLI</b>

*(Rilasciato il 20 giugno 2023)*

<b>Corretto:</b>

* [Livelli] Perdita di memoria durante l’ottimizzazione dei materiali e dei filtri delle Substance che causa arresti anomali

<b>4.1.1 CANNOLI</b>

*(Rilasciato il 6 giugno 2023)*

<b>Aggiunto</b>:

* [Engine] Aggiorna Substance Engine alla versione 9.0
* [Interoperabilità] Invio di oggetti 3D a Stager e Painter

<b>Corretto:</b>

* [capture 3D] Le applicazioni si arrestano in modo anomalo quando il modulo di rendering del capture 3D non riesce
* [capture 3D] Arresto anomalo quando non è possibile caricare un’immagine
* [capture 3D] Arresto anomalo quando si raggiunge la fase di ricostruzione della trama
* [capture 3D] Arresto anomalo durante il ridimensionamento del rettangolo di selezione
* [capture 3D] L’importazione di maschere conformi alla convenzione non assegna correttamente la maschera
* [capture 3D] Problemi di rendering durante la regolazione del rettangolo di selezione
* [capture 3D] Il passaggio da una versione all’altra e l’alternanza delle opzioni di rendering durante l’elaborazione del post di Capture 3D è lento
* [capture 3D] Il passaggio da una versione all’altra durante la fase di post-elaborazione del capture 3D a volte non funziona
* [Applicazione] Arresto anomalo all’avvio
* [Applicazione] Arresto anomalo durante la duplicazione di un materiale rinominato
* [Applicazione] Arresto anomalo quando si apre un progetto .alch legacy senza la relativa cartella di dipendenza
* [Applicazione] Arresto anomalo quando si collega/scollega uno schermo, il computer passa alla modalità di sospensione o è accessibile in remoto
* [Applicazione] Arresti anomali e perdite di memoria correlati alla gestione di risorse non persistenti
* [Esportazione] La scelta del formato di materiale per i tipi di file di oggetti 3D che incorporano o fanno riferimento a texture deve essere disattivata
* [Esporta] Arresto anomalo se si verifica un errore durante l’esportazione di oggetti 3D
* [Esportazione] Arresto anomalo durante l’esportazione di un file .sbs/.sbsar
* [Esporta] Arresto anomalo durante l’importazione di un predefinito personalizzato con lo stesso Label ma non lo stesso nome di file
* [Esportazione] L&#39;esportazione di una luce di ambiente in un file .sbs/.sbsar a volte non funziona
* [Export] L’esportazione Gltf/Glb codifica le texture in base64
* [Esporta] Il campo di testo Nome non funziona quando si rimette a fuoco
* [Esporta] Mantieni affiancamento non funziona quando si esporta un livello Immagine in materiale (IA Powered) in un file .sbs/.sbsar
* [Export] Quando si esporta gltf e si sostituiscono i file, l&#39;elenco dei file da sostituire non è corretto
* [Parametri esposti] Il valore di inizializzazione casuale non funziona nei file .sbs/.sbsar esportati
* [Livelli] Il riempimento in base al contenuto a volte si arresta in modo anomalo quando viene aggiunto per la seconda volta
* [Layers] Arresto anomalo durante l’elaborazione di una pila di livelli
* [Layers] La cache del disco da immagine a materiale (AI) non funziona
* [Livelli] Possibile arresto anomalo durante l’ottimizzazione di un livello
* [Prestazioni] Perdite di memoria
* [Progetto] Arresto anomalo durante il salvataggio di un progetto
* [Project] L&#39;importazione dello stesso progetto due volte in una riga duplica le risorse
* [UI] I pulsanti arrotondati con solo un’icona non vengono visualizzati correttamente

### 4.1.0 Cannoli

*(Rilasciato il 28 marzo 2023)*

<b>Aggiunto:</b>

* [Content] Nuovo filtro Ricamo
* [Contenuto] Nuovo filtro Alterazione pittura
* [UI] Aggiungi opzione di esportazione nel menu File
* [capture 3D] Il pulsante Indietro è ora disponibile nel passaggio di allineamento
* [capture 3D] Immagini Handle JPEG orientamento EXIF
* [capture 3D] Scripting - Nuova proprietà dataset\_info.camera
* [capture 3D] Aggiungere il supporto Linux (consultare la documentazione)
* [capture 3D] Verificare l&#39;accesso in lettura alle immagini importate
* [Onboarding] Scopri - 2 nuove esercitazioni (Ricamo e Alterazione pittura)
* [Onboarding] Aggiornato il contenuto Novità

<b>Corretto:</b>

* [capture 3D] Mantieni la posizione della fotocamera quando si cambia versione
* [capture 3D] Unire tutti i gruppi di un oggetto
* [capture 3D] Rinominate le trame generate in Originale
* [Applicazione] Arresto anomalo quando si tenta di generare la miniatura di un’immagine inesistente
* [Risorse] L’icona del cestino non esegue alcuna operazione nel pannello Risorse
* [Contenuto] L’aggiornamento dei filtri con slot per materiale non funziona come previsto
* [Esportazione] Possibile arresto anomalo durante l’esportazione di una risorsa con filtri specifici
* [Export] Esportazione SBS/SBSAR - I livelli di importazione delle immagini avevano la priorità sui parametri delle immagini
* [Esporta] Il predefinito di esportazione UE4 non funziona con PNG
* [Livelli] Arresto anomalo quando si rilasciano contemporaneamente un materiale e un filtro da Esplora sistemi operativi
* [Layers] Arresto anomalo quando si trascina un file SBSAR con un file di immagine
* [Livelli] Il canale di opacità del ricamo può essere completamente bianco
* [Localizzazione] La lingua cinese può essere visualizzata per impostazione predefinita su Linux
* [Prestazioni] È stato risolto un problema di memoria durante la rimozione di un livello da una risorsa.
* [Progetto] Possibile arresto anomalo durante il salvataggio
* [UI] Aggiungi spaziatura mancante sul pulsante del menu Versione
* [UI] Il pulsante Annulla non viene visualizzato correttamente
* [UI] Disattiva l’animazione dei cursori per i parametri post-elaborazione del capture 3D
* [UI] La finestra Modello di creazione materiale non si chiude da sola quando si fa clic all’esterno
* [UI] La funzione di accesso rapido del filtro si chiude quando si fa clic all&#39;esterno

<b>Problemi noti:</b>

* [Selettore colore] La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* [Contenuto] Il widget della luce della forma non funziona in modalità proiezione sferica
* [Interoperabilità] Il materiale con spostamento inviato a Stager perderà i controlli di spostamento
