---
description: Consulta le note sulla versione per Substance 3D Sampler versione 6.1 per scoprire le nuove funzioni, i miglioramenti e i miglioramenti del flusso di lavoro.
title: Versione 6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# Versione 6.1

**Kouign amann** (pasta sfoglia bretone)

![testo alternativo](../../help/assets/Sampler_splash_large.jpg)

Questa versione introduce la modalità Prestazioni, che consente a chiunque di disattivare le impostazioni che possono rallentare il flusso di lavoro, e miglioramenti automatici alla stabilità che proteggono gli utenti su hardware più leggero.

Le principali novità includono:

## Modalità Prestazioni

Accedi a Sampler in modo più rapido e reattivo. La nuova **modalità Prestazioni** riunisce tutte le impostazioni che possono rallentare il flusso di lavoro: limiti di risoluzione, ombre, qualità dello spostamento e tracciamento del percorso. Disattivate le funzioni non necessarie per migliorare le prestazioni e la reattività.

Ulteriori informazioni [*qui*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode_it)

![](../assets/v6.1/6_1-Performance_Mode.png)

## Supporto migliorato per i computer con specifiche minime

Se l&#39;hardware scende al di sotto delle [specifiche minime](../getting-started/system-requirements.md), Sampler ora esegue automaticamente le regolazioni per mantenere la stabilità. Le funzioni che con maggiore probabilità rallentano o causano un arresto anomalo vengono disattivate automaticamente.

Ulteriori informazioni [*qui*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode_it)

![](../assets/v6.1/6_1-Checked.png)

## Note sulla versione v6.1

*(Rilasciato: 19 novembre 2026)*

## Aggiunto

* &lbrack;Application&rbrack; Nuovo metodo di segnalazione dei requisiti hardware minimi
* &lbrack;Captis&rbrack; Aggiungi un&#39;opzione per scegliere tra 4 e 8 angoli di polarizzazione
* &lbrack;Captis&rbrack; Nuova azione rapida Captis
* &lbrack;Esporta&rbrack; Segnala correttamente gli errori di esportazione all&#39;utente
* &lbrack;Export&rbrack; Update Unreal Engine 4 export preset (rinominato Unreal Engine 5)
* &lbrack;Performance&brack; La creazione delle risorse dal file è ora asincrona
* &lbrack;Performance&rbrack; Sposta il carico di lavoro dal thread principale ai thread di lavoro
* &lbrack;Prestazioni&rbrack; Nuova modalità prestazioni
* &lbrack;Project&rbrack; Avvisa l&#39;utente se il salvataggio del progetto non è riuscito
* &lbrack;Scripting&rbrack; nuovo metodo generate_thumbnail per le risorse e nuova proprietà type per le risorse
* &lbrack;Scripting&rbrack; Rendering di un&#39;istantanea della vista 3D su file dal modulo Python
* &lbrack;UI&rbrack; Se si fa clic in un punto qualsiasi di un&#39;area di rilascio, viene aperta la finestra di dialogo del file
* &lbrack;UI&rbrack; Scelte rapide della barra di navigazione sinistra per gli strumenti (equalizza, ritaglia, Affiancamento, Trasforma, ripara, colore, ...)
* &lbrack;UI&rbrack; aggiorna qt-spectrum per ottenere le icone più recenti

## Fisso

* &lbrack;vista 3D&rbrack; Correggi Offset UV e rotazione immediati, rimuovi scala normale per OpenPBR
* &lbrack;vista 3D&rbrack; impedisce un arresto anomalo verificando che non si verifichi alcuna modifica dello stage durante l&#39;eliminazione della finestra della vista
* &lbrack;vista 3D&rbrack; rimuove correttamente le informazioni sullo spostamento (height) quando si modifica la risorsa visualizzata
* &lbrack;vista 3D&rbrack; Aggiorna correttamente il documento quando si elimina la trama
* &lbrack;Application&rbrack; verificare che la superficie rimanga attiva durante l&#39;elaborazione delle informazioni di debug del filtro dinamico
* &lbrack;Application&rbrack; Correggi arresto anomalo all&#39;uscita dalla scena
* &lbrack;Application&rbrack; Correggere il potenziale arresto anomalo quando si elimina una risorsa durante la chiusura del servizio del database delle risorse
* &lbrack;Application&rbrack; Rende sicuro il thread delle informazioni di debug della cache per impedire un arresto anomalo
* &lbrack;Application&rbrack; Impedisci l&#39;accesso a un arresto anomalo verificando che il nodo non sia null prima di accedervi
* &lbrack;Application&rbrack; Impedisce l&#39;arresto anomalo causato dall&#39;accesso al primo elemento di un vettore vuoto
* &lbrack;Application&rbrack; Impedisci arresto anomalo in invalidateVisibleIfs
* &lbrack;Application&rbrack; Impedisce la creazione di arresti anomali durante la chiusura del servizio di database
* &lbrack;Application&rbrack; Impedisce condizioni di gara all&#39;uscita
* &lbrack;Assets&rbrack; Assicurarsi che le risorse siano correttamente protette dietro il blocco destro
* &lbrack;Captis&rbrack; Bug con valore di intensità in modalità manuale
* &lbrack;Captis&rbrack; Impedisce all&#39;utente di selezionare una zona più grande di quella consentita dal backend
* &lbrack;Impostazioni canale&rbrack; doppia occorrenza di SpecularColor in ASM
* &lbrack;Impostazioni canale&rbrack; Correggere l&#39;ID di un utilizzo creato da una stringa
* &lbrack;Content&rbrack; problema di opacità Atlas scatter
* &lbrack;Content&rbrack; nel filtro Ricamo manca la caratteristica metallica
* &blocco;Contenuto&rbrack; Correggi filtro perforazione
* &lbrack;Content&rbrack; Correggi categoria del filtro Stilizzazione e alcune correzioni nel pannello delle risorse
* &blocco;Content&rbrack; Aggiorna filtro Riempimento
* &lbrack;Creative Cloud&rbrack; correggi il percorso delle risorse 3D in Creative Cloud
* &lbrack;Engine&rbrack; Impedisce l&#39;arresto anomalo durante l&#39;accesso ai dati del motore mentre il processo è stato annullato
* &lbrack;Esporta&rbrack; Aggiungi codice difensivo per controllare che la struttura non sia Null
* &lbrack;Export&rbrack; Codice difensivo per evitare arresti anomali nella generazione dell&#39;SBS
* &lbrack;Esporta&rbrack; Abilita l&#39;output di usi personalizzati, anche se noti al motore
* &lbrack;Esporta&rbrack; Correggi predefiniti di esportazione
* &lbrack;Esporta&rbrack; Mappa normale esportata come non elaborata in USD
* &lbrack;Esporta&rbrack; Usa etichette di output invece di usi quando si esporta con un predefinito
* &lbrack;Exposed Parameters&rbrack; Correggere i parametri esposti nei filtri dinamici
* &lbrack;Exposed Parameters&rbrack; corregge l&#39;aggiornamento del parametro esposto quando cambia nome
* &lbrack;Filters&rbrack; Verifica che i filtri dinamici e gli identificatori di modifiche siano identici tra ogni esecuzione su ogni piattaforma
* &lbrack;Filters&rbrack; Nascondi usi non supportati nella selezione della mappa di suddivisione automatica
* &lbrack;Livelli&rbrack; la modifica della visibilità dei livelli ricrea sempre le strutture
* &lbrack;Layers&rbrack; Arresto anomalo quando si appiattisce un timbro Clona /Clone sopra qualcosa
* &lbrack;Layers&rbrack; L&#39;inserimento di un generatore direttamente sulla pila ora imposta correttamente le modifiche e il nome del nodo
* &lbrack;Layers&rbrack; se si inserisce un generatore con Riempimento, la texture nel selettore viene visualizzata correttamente
* &lbrack;Localization&rbrack; Correggere la conformità del set di caratteri cinese a GB18030
* &lbrack;Progetto&rbrack; Arresto anomalo durante il salvataggio dopo aver colorato su un timbro Clona /Clone
* &blocca;Project&brack; verifica che i nomi della sessione e del progetto siano stati effettivamente salvati
* &lbrack;Project&rbrack; Impedisci arresto anomalo durante il salvataggio di una struttura
* &lbrack;Project&rbrack; è tornato il ripristino di un progetto danneggiato dal database
* &lbrack;Azioni rapide&rbrack; Visualizza il popup di selezione dell&#39;immagine quando non è presente alcuna immagine nella pila
* &lbrack;Azioni rapide&rbrack; Risolvi i problemi delle azioni rapide; l&#39;annullamento di un&#39;azione rapida non chiude più il comando Avvio rapido
* &lbrack;Azioni rapide&rbrack; Importa texture chiede di abilitare alcuni canali e non deve
* &lbrack;Azioni rapide&rbrack; Impedisce il caricamento di un arresto anomalo se un&#39;azione rapida non riesce
* &lbrack;Azioni rapide&rbrack; Aggiorna contenuto azioni rapide
* &lbrack;Rendering&rbrack; Correggere combineNormalAndHeight per i materiali ASM
* &lbrack;Rendering&rbrack; Correggere gli usi della texture visualizzabile con Vulkan
* &lbrack;Rendering&rbrack; Contrassegna struttura danneggiata quando viene modificato l&#39;output di utilizzo univoco
* &lbrack;Rendering&rbrack; Utilizzare la struttura di riferimento corretta per calcolare i nodi della struttura ad albero da calcolare
* &lbrack;Scripting&rbrack; Non bloccarsi se si verifica un errore durante un’esportazione
* &lbrack;Scripting&rbrack; Assicurarsi che import_images() restituisca il livello importato
* &lbrack;Scripting&rbrack; L&#39;impostazione di un&#39;ottimizzazione immagine per un riferimento a una risorsa immagine non riesce
* &lbrack;Scripting&rbrack; get_filters() non restituisce filtri dinamici
* &lbrack;Thumbnail&rbrack; Correggi potenziali arresti anomali durante la generazione della miniatura
* &lbrack;Thumbnail&rbrack; Ricrea il generatore di miniature quando cambia il layout
* &lbrack;UI&rbrack; se si modifica la risorsa, è possibile impostare la scala del height sul valore massimo del cursore
* &lbrack;UI&rbrack; Il disegno in una texture aggiorna il selettore di texture in tempo reale
* &lbrack;UI&rbrack; l&#39;accesso alla modalità a schermo intero senza ingrandimento riempie ora l&#39;intera finestra
* &lbrack;UI&rbrack; Correggi collegamento interrotto a Substance rivista
* &lbrack;UI&rbrack; Correggere i margini popup di esportazione
* &lbrack;UI&rbrack; Correggi dimensione titolo sezione
* &lbrack;UI&rbrack; Correggi il refuso in una stringa
* &lbrack;UI&rbrack; la finestra di dialogo del file Linux ora utilizza il plug-in GTK
* &lbrack;UI&rbrack; Impedisce l&#39;arresto anomalo durante la visualizzazione di un emoji
* &lbrack;UI&rbrack; Rinomina i file .ssa come &#39;archivio Adobe Substance 3D Sampler&#39; (senza versione o beta)
* &lbrack;UI&rbrack; Ripristina la decelerazione dello sfarfallio quando si utilizza il mouse
* &lbrack;UI&rbrack; piccole correzioni nella finestra di dialogo &quot;Crea nuovo materiale&quot;
