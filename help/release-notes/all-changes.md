---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Esamina tutte le modifiche e gli aggiornamenti nelle versioni di Substance 3D Sampler per tenere traccia dell’evoluzione delle funzioni e dei miglioramenti nel tempo.
helpx_description: Sampler > Release Notes > All Changes
title: Tutte le modifiche
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0484ed7ae81bd16687abe23ac0ce8f5ad84d1888
workflow-type: tm+mt
source-wordcount: '24940'
ht-degree: 0%

---


# Tutte le modifiche

Questa pagina raggruppa tutte le modifiche apportate a Substance 3D Sampler, dalle nuove funzioni alle correzioni di bug.

## Versione 6

### **6.0.3**

*(Rilasciato: 24 agosto 2026)*

**Corretto:**

[Rendering] Ripristinare una soluzione temporanea per i driver NVIDIA difettosi

### **6.0.2**

*(Rilasciato: 25 giugno 2026)*

**Aggiunto:**

* &lbrack;Assets&rbrack; Controllare la versione secondaria e avvisare gli utenti se il motore è troppo vecchio per leggerlo
* &lbrack;Captis&rbrack; Aggiungi di nuovo opzione per salvare la fotometria dei sottotitoli nelle preferenze

**Corretto:**

* &lbrack;vista 2D&rbrack; Non &#39;visualizzare con proporzioni fisiche&#39; se la dimensioni fisiche è disattivata
* &lbrack;Analytics&rbrack; eventi di analisi mancanti
* &lbrack;Analytics&rbrack; Impedisci che il blocco anomalo segnali un arresto anomalo su vk devicelost
* &lbrack;Application&rbrack; Non distruggere i vkdevices all&#39;uscita per evitare un arresto anomalo nel driver nvidia
* &lbrack;Application&rbrack; Correggi uscita controllo raccolta collegata + gestione canali
* &lbrack;Application&rbrack; Impedisci arresto anomalo all&#39;uscita
* &lbrack;Content&rbrack; Il filtro &quot;finitura metallo&quot; non influisce sulla metallizzazione
* &lbrack;Content&rbrack; Aggiungi dimensioni fisiche ai filtri dinamici dove manca
* &blocco;Filtri&rbrack; Rimuovi riempimento in base al contenuto dall&#39;elenco delle risorse nascoste
* &blocca;Livelli&rbrack; se si fa clic su &quot;Reimposta tutte le impostazioni&quot; non viene reimpostato il menu a discesa &quot;Applica a&quot;
* &lbrack;Livelli&rbrack; Correggere le modifiche minime e massime per il widget posizione
* &lbrack;Layers&rbrack; aggiorna correttamente il filtro
* &lbrack;Dimensioni fisiche&rbrack; verifica che la scala fisica funzioni ovunque + verifica che la dimensione fisica sia corretta con i filtri dinamici
* &lbrack;Project&rbrack; Verifica che la risoluzione delle risorse sia quella predefinita (2k x 2k) durante la creazione di una nuova risorsa
* &lbrack;Project&rbrack; riapertura del progetto corrente utilizzato per aprire la versione precedente
* &lbrack;Project&rbrack; Sampler non offre più di ripristinare un backup dei progetti danneggiati
* &lbrack;Rendering&rbrack; Esegui il rendering della miniatura del materiale a una risoluzione massima di 2k
* &lbrack;UI&rbrack; codice difensivo per evitare l&#39;arresto anomalo se l&#39;utente è più veloce dell&#39;interfaccia utente

### **6.0.1**

*(Rilasciato: 21 maggio 2026)*

**Aggiunto:**

* &lbrack;Application&rbrack; Avvisa l’utente quando apre un progetto con oggetti o luce ambientale 3D
* &lbrack;Captis&rbrack; Adatta l&#39;interfaccia utente a schermi di piccole dimensioni
* &lbrack;Captis&rbrack; Aggiorna interfaccia utente Captis
* &lbrack;Impostazioni canale&rbrack; Attiva automaticamente SSS quando si utilizza il canale SSS in ASM
* &lbrack;Engine&rbrack; Aggiorna Substance Engine alla versione 9.4.3
* &lbrack;Preset&rbrack; Attiva per impostazione predefinita &quot;Applica valori miniature predefinite&quot;
* &lbrack;Resources&rbrack; Visualizza &quot;tutte le librerie&quot; per impostazione predefinita anziché &quot;risorse iniziali&quot; nel pannello delle risorse
* &lbrack;Scripting&rbrack; Aggiungi funzioni Python per gestire &quot;Applicato a&quot; di un livello
* &lbrack;UI&rbrack; L&#39;elenco delle risorse è ora reattivo: le dimensioni delle risorse si adattano al contenitore
* &lbrack;UI&rbrack; Visualizza 3D/Vista 2D per impostazione predefinita
* &lbrack;UI&rbrack; Visualizza il popup di ottimizzazione del materiale quando si rilascia un materiale da Esplora risorse
* &lbrack;UI&rbrack; descrizione comando Attiva capovolgimento pulsanti barra del dispositivo

**Corretto:**

* &lbrack;Applicazione&rbrack; Correggi problemi di spazio colore
* &lbrack;Application&rbrack; Correggi aggiornamento impostazioni
* &lbrack;Applicazione&rbrack; Attiva i canali di scansione quando sono impostati su automatico
* &lbrack;Application&rbrack; il pulsante Nuovo progetto della schermata Home non cancella più il progetto precedente con lo stesso nome
* &lbrack;Application&rbrack; Impedisce l&#39;arresto anomalo all&#39;uscita da macOS
* &lbrack;Application&rbrack; Impedisci l&#39;accesso alla risorsa con riferimenti a risorsa non validi
* &lbrack;Application&rbrack; Impedisce l&#39;arresto anomalo durante l&#39;accesso a surface da VersionedImage in un tweak
* &lbrack;Application&rbrack; Impedisce l&#39;arresto anomalo quando si elimina uno stage quando non è presente
* &lbrack;Captis&rbrack; Verifica che Captis sia disconnesso prima di chiudere Sampler
* &lbrack;Captis&rbrack; Impedisce la visualizzazione due volte dell&#39;avviso USB-2
* &lbrack;Impostazioni canale&rbrack; Correggere i nomi dei canali OpenPBR
* &lbrack;Impostazioni canale&rbrack; aggiornamento delle etichette lunghe per i canali di OpenPBR
* &lbrack;Content&rbrack; Aggiorna tutte le unità di mesh dai metri ai centimetri per i valori SSS
* &lbrack;Export&rbrack; Assicurarsi che i valori predefiniti siano collegati ai filtri dinamici
* &lbrack;Esporta&rbrack; Le immagini sono ora salvate in un thread di lavoro per migliorare le prestazioni
* &lbrack;Filters&rbrack; Riempimento in base al contenuto si arresta in modo anomalo quando si attiva il ridimensionamento
* &lbrack;Filters&rbrack; Impossibile aprire la posizione di un filtro dinamico dal pannello delle risorse
* &lbrack;Filters&rbrack; Fix reset all in AutoTiling, passaggio di regolazione
* &lbrack;Filters&rbrack; Ripristina disabilita elaborazione dell&#39;utilizzo nella creazione di strutture ad albero
* &lbrack;Filters&rbrack; Imposta il valore predefinito corretto per il parametro upscale
* &lbrack;Filters&rbrack; Aggiorna i generatori anche se si trovano in un livello di riempimento
* &blocca;Livelli&rbrack; impedisce la ridenominazione dei livelli di input intestazione o segnaposto
* &lbrack;Layers&rbrack; Impedisce l&#39;arresto anomalo durante l&#39;inserimento del livello a causa di un puntatore oscillante
* &lbrack;Layers&rbrack; Numero errato di immagini nel nome del livello unito
* &lbrack;Localization&rbrack; verificare che i nomi predefiniti siano aggiornati quando si cambia lingua
* &lbrack;Localization&rbrack; Problemi di traduzione multipli nel pannello delle risorse
* &lbrack;Localization&rbrack; Azioni rapide categorie problemi di localizzazione
* &lbrack;Prestazioni&rbrack; Carica modifiche solo nella sezione aperta
* &lbrack;Preferenze&rbrack; Cancellazione del percorso della cache delle preferenze ripristina il valore precedente
* &lbrack;Rendering&rbrack; Perdita di memoria quando si utilizza Tracciatore percorso
* &lbrack;Rendering&rbrack; Impedisci l&#39;eliminazione di texture finché possono ancora essere accessibili da Vulkan
* &lbrack;Rendering&rbrack; La rotazione della texture non è stata convertita da 0-1 a 0-360
* &lbrack;Scripting&rbrack; Rimuovi classi inesistenti dalla documentazione Python
* &lbrack;Scripting&rbrack; selectedAsset restituisce None se non è presente alcuna risorsa selezionata
* &lbrack;Strumenti&rbrack; La reimpostazione di un valore di texture ora interrompe il disegno e cancella la visualizzazione delle patch
* &lbrack;UI&rbrack; Non chiudere le sezioni nel pannello delle proprietà ogni volta che viene modificato qualcosa
* &lbrack;UI&rbrack; etichetta di modifica colore visibile invisibile al passaggio del mouse
* &lbrack;UI&rbrack; Correggere il comportamento reattivo dell&#39;elenco risorse
* &lbrack;UI&rbrack; Correggi ciclo di associazione nella descrizione comando di AssetItem
* &lbrack;UI&rbrack; Correggere il doppio clic sul gruppo di predefiniti selezionato
* &lbrack;UI&rbrack; Correggi area di rilascio nel presentatore immagini
* &lbrack;UI&rbrack; Correggi etichetta con un pulsante per tutte le lingue
* &lbrack;UI&rbrack; Correggi height di righe per giapponese nel popup dell&#39;elenco canali
* &lbrack;UI&rbrack; Correggere il campo del segnale di lunghezza accettato
* &lbrack;UI&rbrack; Correggi la larghezza del popup con l&#39;elemento di controllo lungo a sinistra
* &lbrack;UI&rbrack; Correggi popup anteprima in elementi risorsa
* &lbrack;UI&rbrack; Correggi selettore irregolare/riflessivo
* &lbrack;UI&rbrack; Correggi puntini di sospensione stringa
* &lbrack;UI&rbrack; risolvere il problema di troncamento della stringa
* &lbrack;UI&rbrack; Correggi interruttore pulsante di reimpostazione
* &lbrack;UI&rbrack; Nasconde il menu a discesa Modello di materiale quando è selezionato un predefinito di esportazione personalizzato
* &lbrack;UI&rbrack; Rimuovi la risoluzione nell&#39;elenco dei canali del popup di esportazione
* &lbrack;UI&rbrack; reimposta il layout predefinito mantiene le impostazioni del visualizzatore proiezione
* &lbrack;UI&rbrack; Ripristinare le voci di menu &quot;Modifica in Photoshop&quot; e &quot;Modifica in Illustrator&quot;

**Rimosso:**

* &lbrack;UI&rbrack; Rimuovi la sezione &quot;Applicato a&quot; per i livelli di importazione delle immagini
* &lbrack;UI&rbrack; Rimuovi descrizione comando di apertura automatica al primo avvio

## Versione 5

### **5.1.3 ÎLE FLOTTANTE**

*(Rilasciato: 6 gennaio 2026)*

**Aggiunto:**

* &lbrack;Captis&rbrack; Visualizza un avviso se il protocollo FTP è disattivato dal firewall

**Corretto:**

* &lbrack;Captis&rbrack; L&#39;interruzione durante un&#39;acquisizione può causare errori
* &lbrack;Captis&rbrack; Il download dei risultati alla fine di un&#39;acquisizione utilizza molta RAM
* &lbrack;Captis&rbrack; L&#39;esecuzione di un&#39;attivazione automatica subito dopo un&#39;intensità automatica può causare errori
* &lbrack;Captis&rbrack; La visualizzazione dei risultati HDR nel pannello Riepilogo
* &lbrack;UI&rbrack; In alcuni casi, la finestra di dialogo delle cartelle in MacOS non seleziona la cartella corretta

### **5.1.2 ÎLE FLOTTANTE**

*(Rilasciato: 20 novembre 2025)*

**Aggiunto:**

* &lbrack;Application&rbrack; Rileva la perdita del dispositivo grafico, avvisa l&#39;utente ed esci correttamente
* &lbrack;Layers&rbrack; Messaggistica migliorata durante la conversione dei livelli
* &lbrack;Layers&rbrack; miniature migliorate per i livelli di importazione delle immagini e livelli con unico livello
* &lbrack;Onboarding&brack; contenuti di apprendimento aggiornati nella schermata Home
* &lbrack;Project&rbrack; Recupera l&#39;ultimo stato salvato della sessione prima dell&#39;arresto anomalo
* &lbrack;UI&rbrack; aggiornamento icona applicazione

**Corretto:**

* &lbrack;Application&rbrack; se si inserisce un materiale nella Pila livelli, potrebbe verificarsi un arresto anomalo in macOS
* &lbrack;Application&rbrack; Possibile arresto anomalo su carichi pesanti in macOS
* &lbrack;Application&rbrack; Possibile arresto anomalo durante l&#39;aggiunta di livelli quando la memoria video è piena
* &lbrack;Application&rbrack; Possibile arresto anomalo durante l&#39;apertura di un progetto
* &lbrack;Captis&rbrack; errore se la messa a fuoco automatica viene eseguita poco dopo la calibrazione automatica dell&#39;intensità
* &lbrack;Captis&rbrack; problemi di affidabilità e prestazioni dopo la prima acquisizione
* &lbrack;Captis&rbrack; rallentamenti ed errori durante la copia dei file al termine di un&#39;acquisizione
* &lbrack;Captis&rbrack; Piccola perdita di memoria durante la ricerca delle informazioni sul dispositivo Captis
* &lbrack;Export&rbrack; I parametri esposti dal cursore multiplo producono file .sbsar danneggiati
* &lbrack;Layers&rbrack; Il pattern di suddivisione automatica viene reimpostato sui valori predefiniti quando si cambia risorsa
* &lbrack;Layers&rbrack; Il colore di base personalizzato predefinito viene visualizzato in rosso
* &lbrack;Layers&rbrack; è possibile la conversione parziale dei livelli secondari di Timbro clone che causa problemi di rendering
* &lbrack;Layers&rbrack; Possibile arresto anomalo quando si modifica una pila di livelli mentre è in corso il rendering
* &lbrack;Layers&rbrack; errore imprevisto nel passaggio di area di interesse automatica dell&#39;Affiancamento quando si modificano i canali sorgente
* &lbrack;Project&rbrack; Miniatura errata a volte durante la creazione di un nuovo materiale
* &lbrack;Azioni rapide&brack; Alcune azioni rapide hanno un conteggio di input errato
* &lbrack;UI&rbrack; Il pulsante del gruppo di azioni ha larghezze diverse
* &lbrack;UI&rbrack; Cancella nei campi di testo a volte attiva la perdita dello stato attivo
* &blocco;UI&rbrack; le caselle combinate e i campi di testo sono troppo grandi
* &lbrack;UI&rbrack; icone ed etichette non allineate
* &lbrack;UI&rbrack; L&#39;etichetta del campo Nome è posizionata in modo errato
* &lbrack;UI&rbrack; le etichette dei pulsanti Azioni rapide non sono allineate
* &lbrack;UI&rbrack; i cursori mostrano troppi 0s finali

**Rimosso:**

* &lbrack;Generative AI&brack; rimozione delle funzionalità di intelligenza artificiale generativa. *Questa funzionalità è stata rimossa dall&#39;applicazione e il servizio smetterà di funzionare nelle versioni precedenti di Sampler il 5 marzo.*

### **5.1.1 ÎLE FLOTTANTE**

*(Rilasciato: 18 settembre 2025)*

**Aggiunto:**

* &lbrack;2D View&rbrack; Consente di ridurre ulteriormente la visualizzazione 2D per le texture ad alta risoluzione
* &lbrack;Captis&rbrack; Avvisa gli utenti in caso di problemi durante la copia dei file
* &lbrack;Layers&rbrack; Durante la duplicazione di un livello, utilizza un numero incrementale nel nuovo nome del livello

**Corretto:**

* &lbrack;2D View&rbrack; Quando si colorano i tratti dopo aver reimpostato tutte le proprietà di Timbro clone, i tratti creati in precedenza vengono nuovamente visualizzati
* &lbrack;Application&rbrack; &quot;Salvare il progetto corrente?&quot; il popup utilizza un nome di progetto errato
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &lbrack;Application&rbrack; potenziale arresto anomalo
* &lbrack;Application&rbrack; A volte, viene generata una miniatura con un materiale errato
* &lbrack;Captis&rbrack; Su alcuni dispositivi, quando si esegue una scansione in alta risoluzione, la mappa del height è nera
* &lbrack;Captis&rbrack; Il pulsante &quot;Avvia acquisizione&quot; non è più disattivato quando non è impostato alcun nome di acquisizione e quando è in esecuzione una calibrazione
* &lbrack;Export&rbrack; Quando si esporta un file .sbsar, l&#39;esportazione può non riuscire senza che l&#39;utente riceva una notifica
* &lbrack;Filters&rbrack; Advanced parameters screen for the Auto Tiling filter a volte sfarfalla durante l&#39;ottimizzazione dei parametri
* &lbrack;Filters&rbrack; I parametri predefiniti per il filtro Divisione in porzioni generano artefatti grigi nell&#39;output
* &lbrack;Filters&rbrack; A volte con input ad alta risoluzione, le impostazioni avanzate del filtro Porzione automatica non mostrano i singoli punti del pattern
* &lbrack;Filters&rbrack; La dimensione del pattern per il parametro di dimensione personalizzata Auto Tiling ha un valore predefinito errato
* &lbrack;Layers&rbrack; problema di colore occasionale con il filtro Porzione automatica visibile per lo più sui materiali rossi
* &lbrack;Livelli&rbrack; a volte l’aggiunta di livelli reimposta alcune modifiche sul valore predefinito
* &lbrack;Dimensioni fisiche&rbrack; La miniatura delle risorse con una dimensioni fisiche ha una scala di height errata
* &lbrack;UI&rbrack; Impossibile rinominare i parametri esposti
* &lbrack;UI&rbrack; Il pulsante di attivazione del canale non è quadrato
* &lbrack;UI&rbrack; Se un&#39;etichetta del cursore è troppo lunga, il pulsante di reimpostazione non è accessibile
* &lbrack;UI&rbrack; se si preme il tasto Invio o si fa clic fuori, lo stato attivo non viene rimosso dai campi di testo
* &lbrack;UI&rbrack; a volte nel pannello Dimensioni fisiche compare una descrizione comandi indesiderata
* &lbrack;UI&rbrack; La vista 3D visualizza una trama errata durante la creazione di un progetto vuoto
* &lbrack;UI&rbrack; Quando si espone un input del selettore colore, la relativa etichetta scompare al passaggio del mouse
* &lbrack;UI&rbrack; Quando si espongono i parametri, il punto colore a volte è posizionato in modo errato

### **5.1.0 ÎLE FLOTTANTE**

*(Rilasciato: 7 agosto 2025)*

**Aggiunto:**

* &lbrack;vista 2D&rbrack; La dimensione del pennello ora si adatta alla risoluzione della texture corrente
* &lbrack;vista 3D&rbrack; Attiva/disattiva la scala di visualizzazione nativa per il rendering 3D nelle preferenze
* &lbrack;Application&rbrack; aggiornamento del motore di rendering
* &lbrack;Captis&rbrack; Aggiungi la possibilità di &quot;creare quadrati&quot; durante l&#39;anteprima
* &lbrack;Captis&rbrack; Rilevamento automatico dimensioni fisiche
* &lbrack;Captis&rbrack; L&#39;acquisizione di un nuovo materiale creerà una nuova risorsa
* &lbrack;Captis&rbrack; Cambia la selezione della risoluzione nel menu a discesa in pixel per pollice o centimetro invece della risoluzione pixel dell&#39;area massima
* &lbrack;Captis&rbrack; Guida contestuale alla calibrazione dell&#39;allineamento
* &lbrack;Captis&rbrack; Genera mappa di rugosità
* &lbrack;Captis&rbrack; Avvisa l&#39;utente se mancano i file di calibrazione predefiniti
* &lbrack;Filters&rbrack; Filtro di Affiancamento automatico per scansioni e materiali strutturati
* &blocco;Filtri&rbrack; Nuovo filtro rimozione piegatura
* &lbrack;Filters&rbrack; Nuove funzioni all&#39;interno del filtro Clona /Clone timbro
* &blocco;Filtri&rbrack; Nuove funzioni all&#39;interno del filtro Equalizza
* &lbrack;Layers&rbrack; Possibilità di convertire i livelli
* &blocca;Livelli&rbrack; menu di scelta rapida quando si fa clic con il pulsante destro del mouse su un livello per rinominarlo, duplicarlo, eliminarlo o convertirlo
* &blocco;Onboarding&brack; contenuto per il completamento dell&#39;aggiornamento e Novità delle schermate
* &lbrack;Prestazioni&rbrack; Prestazioni migliori quando si utilizza il filtro Ritaglio
* &lbrack;Performance&rbrack; Migliorare l&#39;utilizzo della memoria per la vista 3D
* &lbrack;Performance&rbrack; l&#39;aggiornamento della vista 3D è più rapido
* &lbrack;Dimensioni fisiche&rbrack; abilita &quot;visualizzazione con proporzioni fisiche&quot; quando si lavora sui filtri Substance quando Dimensioni fisiche è abilitata
* &lbrack;Dimensioni fisiche&rbrack; Quando si importano immagini in una pila vuota, proporre una risoluzione più coerente con le proporzioni dell&#39;immagine
* &lbrack;Azioni rapide&rbrack; 3 nuove azioni rapide per l&#39;elaborazione della scansione
* &lbrack;Scripting&rbrack; API per convertire i livelli
* &lbrack;Scripting&rbrack; Ottieni il nome file di ogni immagine di un livello di importazione immagine
* &lbrack;Scripting&rbrack; Nuova funzione per attivare/disattivare un determinato canale di una risorsa
* &lbrack;UI&rbrack; Icone e pulsanti di rielaborazione nel pannello Livelli per adattarsi alle nuove funzioni
* &lbrack;UI&rbrack; Avvisa in caso di deprecato authoring luce ambiente

**Corretto:**

* &lbrack;2D View&rbrack; La selezione di &#39;display with physical ratio&#39; potrebbe non funzionare quando si utilizzano i filtri Substance
* &lbrack;capture 3D&rbrack; I file Svg sono elencati nel selettore di file ma non sono supportati
* &lbrack;3D View&rbrack; Il parametro relativo all&#39;intensità di emissione nelle impostazioni dello shader non funziona
* &lbrack;vista 3D&rbrack; A volte la posizione della trama non è corretta durante la creazione di una nuova risorsa
* &lbrack;3D View&rbrack; Il passaggio al rendering Traccia percorso si arresta in modo anomalo su hardware non supportato
* &lbrack;Application&rbrack; L&#39;applicazione si blocca quando si chiude il popup della misura manuale senza impostare una dimensione
* &lbrack;Application&rbrack; Arresto anomalo
* &blocco;Applicazione&blocco; Blocco in Windows durante la visualizzazione del desktop (tasto Windows + scelta rapida da tastiera D)
* &lbrack;Application&rbrack; Possibile arresto anomalo quando si cambia lingua
* &lbrack;Captis&rbrack; Arresto anomalo quando i dati di anteprima non sono validi
* &lbrack;Captis&rbrack; impossibile ridurre completamente dopo aver eseguito lo zoom avanti
* &lbrack;Captis&rbrack; Localizzazione mancante in alcuni passaggi della procedura guidata
* &lbrack;Captis&rbrack; Possibile arresto anomalo all&#39;uscita quando si utilizza Captis
* &lbrack;Captis&rbrack; La scansione non funziona se nel dispositivo mancano i file di calibrazione
* &lbrack;Filters&rbrack; L’anteprima del pennello quando si utilizza il filtro Timbro Clona /Clone potrebbe non essere corretta a seconda delle dimensioni della texture e del pennello
* &lbrack;Filters&rbrack; dimensioni di output errate dopo l&#39;utilizzo del filtro Ingrandisci
* &lbrack;Filters&rbrack; Icone mancanti per i filtri Rotazione e Stilizzazione dell&#39;ambiente
* &lbrack;Filters&rbrack; L&#39;aggiornamento di alcuni filtri può causare un rendering errato
* &lbrack;Livelli&rbrack; primo rendering non corretto durante la fusione di due materiali
* &lbrack;Layers&rbrack; Il pulsante per aggiornare i livelli mostra &quot;Aggiorna tutto&quot; anche quando è presente un solo aggiornamento
* &lbrack;Layers&rbrack; calcoli non necessari durante l&#39;importazione di immagini nella Pila livelli
* &lbrack;Prestazioni&rbrack; Migliorare la gestione del formato mappa normale per ridurre i tempi di rendering
* &lbrack;Dimensioni fisiche&rbrack; Il popup di misurazione manuale funziona solo dopo l&#39;esecuzione di una misurazione automatica
* &lbrack;Dimensioni fisiche&rbrack; Risoluzione di esportazione errata nel popup Esporta quando la Dimensioni fisiche è abilitata
* &lbrack;Azioni rapide&rbrack; Localizzazione mancante nei nomi delle risorse generate
* &lbrack;UI&rbrack; l&#39;anteprima della risorsa al passaggio del mouse potrebbe non essere visualizzata
* &lbrack;UI&rbrack; Se si fa clic sul pulsante Ripristina valore predefinito è possibile che alcuni dei controlli vengano interrotti
* &lbrack;UI&rbrack; I messaggi di errore non vengono cancellati quando si cambia progetto
* &lbrack;UI&rbrack; verifica che il nome del materiale nella finestra della vista e nel pannello Proprietà sia vuoto quando non è presente alcuna risorsa
* &lbrack;UI&rbrack; Il pulsante Ripristina valore predefinito per il parametro Punto di vista non funziona
* &lbrack;UI&rbrack; Pulsante Ripristina valore predefinito sovrapposto
* &blocca;Interfaccia&rbrack; Alcuni pulsanti non sono selezionabili quando un pannello è disancorato
* &lbrack;UI&rbrack; Texture parametro V di fatturazione parzialmente nascosto in Impostazioni e vista 3D visualizzatore

**Rimosso:**

* &lbrack;capture 3D&rbrack; Rimuovi supporto capture 3D
* &lbrack;Application&rbrack; Rimuovi supporto macOS x86

### **5.0.3 NOCCIOLA**

*(Rilasciato: 3 giugno 2025)*

**Aggiunto:**

* &lbrack;Captis&rbrack; Consenti di assegnare a un materiale lo stesso nome di un materiale già esistente
* &lbrack;Captis&rbrack; Sposta i messaggi di errore in popup anziché in popup
* &lbrack;Filters&rbrack; Aggiorna il ricamo
* &lbrack;Preferenze&rbrack; Aggiungi reimpostazione nelle impostazioni del visualizzatore e degli ombreggiatori
* &lbrack;UI&rbrack; Non presentare la voce di menu &quot;Mostra percorso&quot; nelle risorse del progetto

**Corretto:**

* &lbrack;capture 3D&rbrack; Il filtro post-elaborazione Trama non genera le mappe previste
* &lbrack;vista 3D&rbrack; la vista 3D non funziona a causa del danneggiamento della cache di shader
* &lbrack;vista 3D&rbrack; il piano e la griglia del terreno sono verticali quando la scena è Z-up
* &lbrack;vista 3D&rbrack; La trama a volte scompare
* &lbrack;Application&rbrack; La chiusura della finestra di accesso all&#39;avvio senza effettuare l&#39;accesso a volte arresto anomalo l&#39;app
* &lbrack;Application&rbrack; Arresto anomalo quando l&#39;accesso al file di configurazione dei plug-in viene negato
* &lbrack;Applicazione&rbrack; il materiale corrente non è selezionato quando si salva il progetto
* &lbrack;Application&rbrack; Ripristinando il layout predefinito, la risoluzione viene impostata su 64x64
* &lbrack;Application&rbrack; Sampler a volte arresto anomalo durante il rendering di una Pila livelli
* &lbrack;Export&rbrack; La risoluzione dell&#39;esportazione è talvolta reimpostata su 64x64
* &lbrack;Export&rbrack; a volte non è possibile esportare i file .sbs/.sbsar
* &lbrack;Layers&rbrack; Il pulsante Aggiungi materiale di base non esegue alcuna operazione quando il materiale è vuoto
* &lbrack;Layers&rbrack; L&#39;Affiancamento della Texture viene modificato durante la duplicazione di un materiale
* &lbrack;Dimensioni fisiche&rbrack; Misura automatica non funziona se il pannello Dimensioni fisiche è stato ancorato prima di importare l&#39;immagine
* &lbrack;Scripting&rbrack; Il plug-in di salvataggio automatico è interrotto
* &lbrack;UI&rbrack; spaziatura errata nella finestra di dialogo Esporta
* &lbrack;UI&rbrack; L&#39;animazione del cursore delle modifiche non funziona più
* &lbrack;UI&rbrack; I cursori non si allineano a valori interi quando necessario
* &lbrack;UI&rbrack; Alcuni menu a discesa sono ritagliati

### **5.0.2 NOCCIOLA**

*(Rilasciato: 22 aprile 2025)*

**Corretto:**

* &lbrack;Application&rbrack; Il pulsante Indietro nella pagina principale è interrotto
* &lbrack;Application&rbrack; Sampler a volte non si avvia se sul disco sono presenti dati danneggiati da versioni precedenti
* &lbrack;Application&rbrack; L&#39;immagine importata non viene visualizzata nella finestra della vista o nella pila di livelli
* &lbrack;Captis&rbrack; Il campo indirizzo IP Captis rimane vuoto anche dopo il riavvio di Sampler
* &lbrack;Captis&rbrack; L&#39;anteprima della videocamera dal vivo funziona solo quando la lingua dell&#39;applicazione è impostata su Inglese
* &lbrack;Esporta&rbrack; Arresto anomalo durante l&#39;esportazione &lbrack;Livelli&rbrack; Il disegno a volte non funziona nei progetti salvati in precedenza
* &lbrack;Layers&rbrack; Sampler a volte aggiorna tutte le texture quando viene aggiornato un solo canale
* &lbrack;Layers&rbrack; Impossibile utilizzare fusioni di materiale nella pila di livelli dopo l&#39;aggiornamento a 5.0.x
* &lbrack;Layers&rbrack; L&#39;aggiornamento di un progetto con una versione precedente di Image to Material (AI) rende tutto il materiale nero
* &lbrack;Livelli&rbrack; Quando si tenta di importare un&#39;immagine non supportata, Sampler crea un livello interrotto
* &lbrack;Scripting&rbrack; Parte dell’API Python non funziona con un progetto vuoto
* &lbrack;UI&rbrack; Le voci di menu a volte si sovrappongono nel menu File

### **5.0.1 NOCCIOLA**

*(Rilasciato: 20 marzo 2025)*

**Aggiunto**

* &lbrack;Application&rbrack; Elenco di compatibilità dei driver di grafica aggiornato
* &lbrack;Captis&rbrack; Visualizza un popup quando l&#39;utilizzo di HP Z Captis viene bloccato dai criteri del sistema operativo
* &lbrack;Azioni rapide&rbrack; Spiegare il motivo per cui un&#39;azione rapida è disattivata in una descrizione comandi
* &lbrack;UI&rbrack; stile interfaccia utente della finestra del report di arresto anomalo
* &lbrack;UI&rbrack; durante la copia negli Appunti, mostra un avviso popup per indicare che è stato completato

**Corretto:**

* &lbrack;2D View&rbrack; Il cursore Esposizione non ha effetto quando la proiezione sferica è disattivata
* &lbrack;2D View&rbrack; Se si esegue un disegno all&#39;esterno della texture, viene creato un tratto interrotto
* &lbrack;2D View&rbrack; Il pulsante Esposizione non contiene alcun suggerimento.
* &lbrack;2D View&rbrack; Lo zoom sul lato di un&#39;immagine non quadrata non segue il mouse
* &lbrack;capture 3D&rbrack; non funziona su Windows 11 24H2
* &lbrack;capture 3D&rbrack; Arresto anomalo se si esce da Sampler durante la fase di ricostruzione della trama
* &lbrack;3D View&rbrack; Il tempo di calcolo viene talvolta visualizzato come 0 ms
* &lbrack;3D View&rbrack; Quando si cambia proiezione da ortogonale a prospettica, la finestra della vista diventa grigia
* &lbrack;Application&rbrack; Arresto anomalo all&#39;avvio durante il controllo delle funzionalità GPU
* &lbrack;Application&rbrack; Arresto anomalo durante l&#39;installazione
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita dopo aver fatto clic con il pulsante destro del mouse su un campo metadati
* &lbrack;Application&rbrack; luce ambiente mancante all&#39;apertura di un SBSAR da Esplora file del sistema operativo
* &lbrack;Application&rbrack; Se si apre un file .sbsar mentre Sampler è in esecuzione, viene modificata l&#39;impostazione Texture Tiling
* &lbrack;Captis&rbrack; Alcuni metadati potrebbero non essere trasferiti tra i passaggi di acquisizione
* &lbrack;Captis&rbrack; Il nome della risorsa creata non è quello immesso nel campo dei metadati
* &lbrack;Content&rbrack; Il progetto di esempio richiede un aggiornamento del filtro, ma è già aggiornato
* &lbrack;Filters&rbrack; Il filtro di regolazione Normale/height non ha icona
* &lbrack;Livelli&rbrack; Impossibile modificare le immagini in un livello di importazione immagine
* &lbrack;Layers&rbrack; Si arresta in modo anomalo quando si utilizza il filtro Ingrandisci
* &lbrack;Livelli&rbrack; l&#39;aggiornamento di un progetto con una vecchia immagine in materiale rende tutto il materiale nero
* &lbrack;Rendering&rbrack; l’ottimizzazione di una pila di livelli immediatamente dopo la creazione di una risorsa interrompe il rendering
* &lbrack;Scripting&rbrack; Il plug-in di salvataggio automatico si arresta in modo anomalo quando non è presente alcuna risorsa nel progetto
* &lbrack;Strumenti&rbrack; Il valore della dimensione del pennello non è presente nella barra degli strumenti Pennello
* &lbrack;UI&rbrack; La modifica della lingua dell&#39;applicazione non aggiorna alcune delle etichette nella schermata iniziale
* &lbrack;UI&rbrack; toccando i campi di testo Esc o Invio in Slider non perderà lo stato attivo
* &lbrack;UI&rbrack; Nel pannello Proprietà, il pulsante Reimposta tutto e l&#39;etichetta del nome della risorsa si sovrappongono
* &lbrack;UI&rbrack; Problemi durante l&#39;ancoraggio e disancoraggio dei pannelli
* &lbrack;UI&rbrack; Lo scorrimento in un pannello in sovrapposizione scorre anche nella finestra sottostante
* &lbrack;UI&rbrack; Il passaggio alla visualizzazione Elenco nella sezione Progetti recenti della schermata Home non funziona
* &lbrack;UI&rbrack; l&#39;icona del pulsante della modalità di visualizzazione del riquadro di visualizzazione mostra sempre 2D/3D

### **5.0.0 NOCCIOLA**

*(Rilasciato: 20 febbraio 2025)*

**Aggiunto**

* &lbrack;Onboarding&rbrack; nuova home page con accesso rapido a contenuti di apprendimento, progetti di esempio, azioni rapide e progetti recenti.
* &lbrack;Onboarding&brack; Inizia rapidamente con le nuove Azioni rapide, accessibili dalla pagina principale e dal pannello dedicato
* &lbrack;Onboarding&rbrack; &lbrack;Content&rbrack; Le azioni rapide sono flussi di lavoro predefiniti che popolano la pila di livelli con la maggior parte dei livelli utilizzati
* &lbrack;Onboarding&rbrack; possibilità di creare un nuovo progetto tramite un nuovo menu di avvio rapido, tramite azioni rapide o Progetto personalizzato
* &lbrack;Onboarding&rbrack; possibilità di creare un progetto vuoto direttamente dalla home page tramite il pulsante dedicato
* &lbrack;vista 3D&rbrack; nuovo rasterizzatore avanzato e tracciatore percorsi con nuove funzionalità di rendering (proprietà quali rivestimento, lucentezza, traslucidità, dispersione sottosuperficie) e coerenza visiva nell&#39;ecosistema Substance
* &lbrack;3D View&rbrack; Le impostazioni del visualizzatore sono ora accessibili direttamente nella vista 3D
* &lbrack;3D View&rbrack; Possibilità di salvare un&#39;istantanea di rendering negli Appunti o nei file
* &lbrack;3D View&rbrack; Visualizza una griglia per visualizzare l&#39;origine della scena
* &lbrack;3D View&rbrack; Attiva il piano terreno per catturare ombre e riflessi
* &lbrack;3D View&rbrack; controlla la visibilità e l&#39;opacità del piano terreno
* &lbrack;capture 3D&rbrack; Posiziona trama a terra
* &lbrack;Application&rbrack; Verifica la compatibilità hardware all&#39;avvio dell&#39;applicazione
* &lbrack;Application&rbrack; La finestra di segnalazione degli arresti anomali ora si apre subito dopo l&#39;arresto anomalo
* &lbrack;Content&rbrack; Apri un progetto di esempio per iniziare facilmente
* &lbrack;Esporta&rbrack; Esporta lo shader Adobe Standard Material nei file USD
* &lbrack;Generative AI&brack; Selezionare &quot;Non dedurre&quot; tag quando si utilizza un&#39;immagine come input nei flussi di lavoro da immagine a texture
* &lbrack;Project&rbrack; le miniature vengono memorizzate nel file di progetto per velocizzare l&#39;apertura dei progetti
* &lbrack;Progetto&rbrack; Impostazione nelle preferenze per memorizzare i dati della cache all&#39;interno del file di progetto, con modalità diverse (nessuna cache, cache leggera, cache completa)
* &lbrack;Scripting&rbrack; &lbrack;Breaking change&rbrack; migrazione Qt a Qt6.15 - impatto sulla compatibilità dei plug-in esistenti
* &lbrack;Scripting&rbrack; I plug-in predefiniti e la cartella degli script si trovano ora nella cartella Documenti
* &lbrack;Scripting&rbrack; Nuova interfaccia utente per i plug-in per coerenza visiva con i pannelli principali di Sampler
* &lbrack;Scripting&rbrack; Esempi di plug-in di Access 2 per scoprire le funzionalità dei plug-in di Sampler
* &lbrack;Scripting&rbrack; Nuova funzione open_3d_catpure()
* &lbrack;Scripting&rbrack; Quando si inserisce un livello, controllare se è inserito sopra o sotto la posizione di destinazione

**Corretto:**

* &lbrack;capture 3D&rbrack; Arresto anomalo se non è possibile avviare Acquisizione oggetti in macOS
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &blocco;Applicazione&blocco; Blocco all&#39;uscita durante l&#39;aggiunta delle risorse al pannello Progetto
* &lbrack;Applicazione&rbrack; La ridenominazione di una risorsa di progetto non funziona a meno che non si prema invio
* &lbrack;Application&rbrack; Le voci di menu Annulla e Ripeti non sono disattivate quando dovrebbero essere
* &lbrack;Assets&rbrack; impossibile eliminare le risorse dalla sezione Tutte le librerie del pannello Risorse
* &lbrack;Content&rbrack; creatore di Atlas: usa mappa di opacità esistente se presente
* &lbrack;Content&rbrack; Color ID Blend - Correggi selezione colore nel colore di base
* &lbrack;Layers&rbrack; evita calcoli inutili quando si utilizzano i generatori
* &lbrack;Livelli&rbrack; la modifica di un generatore può causare l&#39;attivazione di troppi calcoli
* &lbrack;Prestazioni&rbrack; Miglioramento della gestione della memoria GPU
* &lbrack;Performance&brack; Impossibile utilizzare la cache di rendering al riavvio dell&#39;app
* &lbrack;Resources&rbrack; I file di sola lettura non sono visibili nel pannello Risorse
* &blocco;Scripting&rbrack; Consenti di riutilizzare un livello dopo aver aggiunto un altro livello
* &lbrack;Scripting&rbrack; La modifica ripetuta della struttura della pila di livelli in uno script potrebbe non riuscire

**Rimosso:**

* &lbrack;Application&rbrack; Rimuovi il supporto per i file di immagine .dng e .nef

## Versione 4

### **4.5.2 GRUYERE**

*(Rilasciato il 7 novembre 2024)*

**Corretto:**

* &lbrack;Content&rbrack; filtri di fusione Ritaglia, Ricamo e Height

### **4.5.1 GRUYERE**

*(Rilasciato il 30 luglio 2024)*

**Corretto:**

* &lbrack;Livelli&rbrack; il disegno delle maschere in scala di grigi non funziona, con effetti su strumenti come Timbro Clona /Clone, Alterazione Pittura, Riempimento in base al contenuto

### **4.5.0 GRUYERE**

*(Rilasciato il 18 luglio 2024)*

**Aggiunto**

* &lbrack;Interoperability&rbrack; Invia materiali a UE5, Blender, Maya, 3DsMax Unity
* &lbrack;Content&rbrack; Nuova categoria generatore texture - Sfumature
* &lbrack;Content&rbrack; Strumenti HDRI - nuovo filtro di rotazione Ambiente

**Corretto:**

* &lbrack;Exposed Parameters&rbrack; L&#39;esposizione dei valori di input .sbsar non funziona
* &lbrack;Livelli&rbrack; il Colore di base diventa rosso con immagini in scala di grigi
* &lbrack;Rendering&rbrack; le immagini in scala di grigi utilizzate nei canali di colore hanno uno spazio cromatico errato
* &lbrack;Scripting&rbrack; L’uso di un predefinito di esportazione a volte non esporta i canali previsti
* &lbrack;Content&rbrack; Dirt: se si applica un filtro Dirt sopra Immagine al materiale, viene generata una normale nera
* &lbrack;Content&rbrack; Effetto rilievo: il ridimensionamento di un pattern nel filtro effetto rilievo non è lineare tra 0 e 1
* &lbrack;Content&rbrack; Crea porzioni - Maggiore coerenza tra height e normale

### **4.4.1 FONDUE**

*(Rilasciato il 6 giugno 2024)*

**Corretto:**

* &lbrack;Content&rbrack; filtro Dirt mancante
* &lbrack;Generative AI&rbrack; Talvolta si verificano errori di rete quando si utilizza Image to Texture

### **4.4.0 FONDUE**

*(Rilasciato il 23 maggio 2024)*

**Aggiunto:**

* &lbrack;Application&rbrack; capture 3D Cache è ora memorizzata in una sottocartella separata
* &lbrack;Generative AI&rbrack; Immagine da Texture (Beta)
* &lbrack;Generative AI&brack; Text to Pattern (Beta)
* &lbrack;Generative AI&rbrack; Text to Texture (Beta)
* &lbrack;Scripting&rbrack; Le risorse ora hanno una proprietà &#39;resource&#39;
* &lbrack;Scripting&rbrack; I livelli ora hanno una proprietà &#39;output_usages&#39;

**Corretto:**

* &lbrack;Application&rbrack; Arresto anomalo durante l&#39;apertura di un file di progetto danneggiato
* &lbrack;Application&rbrack; Arresto anomalo quando il progetto contiene risorse danneggiate
* &lbrack;Application&rbrack; Arresto anomalo quando si scollega un monitor su Windows
* &lbrack;Application&rbrack; icona di applicazione non corretta nella barra delle applicazioni di Windows
* &lbrack;Application&rbrack; il danneggiamento del file di configurazione principale può provocare l&#39;eliminazione dei file
* &blocco;Applicazione&rbrack; I pannelli vengono visualizzati davanti ai popup
* &lbrack;Content&rbrack; i generatori di Texture hanno miniature sfocate
* &lbrack;Export&rbrack; Il canale di opacità generato da un&#39;immagine importata si interrompe durante l&#39;esportazione di un file .sbs/.sbsar
* &lbrack;Filters&rbrack; L&#39;arresto anomalo di Ingrandisci dipende dai relativi livelli di input
* &lbrack;Generative AI&rbrack; Possibili arresti anomali durante la ricezione di risultati imprevisti dal servizio
* &lbrack;Scripting&rbrack; Arresto anomalo durante il caricamento automatico di un plug-in dalla variabile di ambiente
* &lbrack;Scripting&rbrack; possibile arresto anomalo durante l’assegnazione dell’utilizzo dell’output con l’API

### **4.3.3 EMPANADA**

*(Rilasciato il 26 marzo 2024)*

**Aggiunto:**

* &lbrack;capture 3D&rbrack; nuovi parametri avanzati auto-UV durante la fase di post-elaborazione
* &lbrack;Filters&rbrack; Perforate filter: possibilità di invertire e modificare le dimensioni del pattern personalizzato

**Corretto:**

* &lbrack;capture 3D&rbrack; Il colore di base può non essere corretto in macOS
* &lbrack;capture 3D&rbrack; Arresto anomalo durante l&#39;elaborazione di una nuova versione
* &lbrack;capture 3D&rbrack; il passaggio post-elaborazione può arrestarsi in modo anomalo in macOS
* &lbrack;capture 3D&rbrack; Il livello Trasformazione trama può causare un rendering errato
* &lbrack;Application&rbrack; Arresto anomalo all&#39;avvio di Sampler mentre è ancora in corso l&#39;esportazione di un&#39;istanza precedente
* &lbrack;Application&rbrack; Sampler non risponde per un momento quando viene avviato per la prima volta
* &lbrack;Esporta&rbrack; mappa angolo di Anisotropia non esportata
* &lbrack;Filters&rbrack; L&#39;aggiunta di Tessuto alla pila di livelli può causare un arresto anomalo
* &lbrack;Filtri&rbrack; l&#39;aggiunta di rilievo alla pila di livelli può causare un arresto anomalo
* &lbrack;Filters&rbrack; arresti anomali di riempimento in base al contenuto quando si utilizzano immagini a 32 bit
* &blocco;Filtri&rbrack; Rilievo: l’opacità dei livelli sottostanti non viene completamente ignorata
* &lbrack;Filters&rbrack; Fill: il metodo di fusione non funziona in Designer e Painter
* &lbrack;Filters&rbrack; Ricamo: selezione colore automatica interrotta
* &lbrack;Preferenze&rbrack; Impedisce di impostare un percorso non supportato per capture 3D Cache
* &lbrack;Preferenze&rbrack; La preferenza Formato normale non funziona
* &lbrack;Scripting&rbrack; I parametri dei canali di Asset.export_material fanno distinzione tra maiuscole e minuscole

### **4.3.2 EMPANADA**

*(Rilasciato il 22 febbraio 2024)*

**Corretto:**

* &lbrack;Applicazione&rbrack; Il salvataggio di un progetto in una condivisione di rete in Windows danneggia il file di progetto

### **4.3.1 EMPANADA**

*(Rilasciato il 15 febbraio 2024)*

**Corretto:**

* &lbrack;capture 3D&rbrack; Arresto anomalo quando i file di immagine diventano inaccessibili durante la generazione in batch delle maschere
* &lbrack;Esporta&rbrack; l&#39;esportazione di un materiale con Ritaglio o relativo al livello dei criteri di input restituisce risultati non validi
* &lbrack;Layers&rbrack; arresto anomalo raro durante il rendering di una Pila livelli
* &lbrack;Filters&rbrack; Ricamo - Risolvere il problema quando si utilizza l&#39;input di materiale su MacOS
* &lbrack;Filters&rbrack; Stylization - Support Texture Generators
* &lbrack;Filters&rbrack; Pattern - Correggi denominazione parametri
* &lbrack;Localization&rbrack; &quot;Salva con nome...&quot; nella finestra delle informazioni sull&#39;hardware, sotto il menu?, viene visualizzato unlocalized

### **4.3.0 EMPANADA**

*(Rilasciato il 25 gennaio 2024)*

**Aggiunto**

* &lbrack;Assets&rbrack; Nuovo tipo di risorsa: Generatori di Texture
* &lbrack;Risorse&rbrack; Nuovi materiali inclusi in Risorse per iniziare
* &lbrack;Assets&rbrack; Nuovo selettore di risorse per i parametri dell&#39;immagine nel pannello Proprietà
* &lbrack;Assets&rbrack; Trascina i generatori di Texture dal pannello Risorse ai selettori di immagini nel pannello Proprietà
* &lbrack;Assets&rbrack; Trascina e rilascia i generatori di Texture da Esplora file del sistema operativo
* &lbrack;Assets&rbrack; I filtri possono suggerire l&#39;adattamento dei generatori tramite un tag utente sull&#39;input dell&#39;immagine
* &lbrack;Assets&rbrack; I generatori di Texture possono definire il filtro da utilizzare come suggerimento tramite un tag utente
* &lbrack;Content&rbrack; Nuovo filtro Prospettiva ritaglio
* &lbrack;Content&rbrack; Nuovo filtro di stilizzazione
* &lbrack;Content&rbrack; Metodo fusione su filtro riempimento
* &lbrack;Content&rbrack; Filtro ricamo aggiornato
* &lbrack;Content&rbrack; Filtro Contorna con disegno aggiornato
* &lbrack;Content&rbrack; Tutti i filtri sono stati aggiornati per supportare i generatori di texture
* &lbrack;Layers&rbrack; Possibilità di scegliere un canale di output del generatore di texture quando lo si aggiunge alla pila di livelli
* &lbrack;Layers&rbrack; Possibilità di elencare e applicare facilmente i predefiniti sui generatori di texture
* &lbrack;Livelli&rbrack; Visualizza un&#39;anteprima di Generatore texture nei selettori di immagini
* &lbrack;Livelli&rbrack; I parametri del generatore di texture possono essere esposti ed esportati
* &lbrack;Livelli&rbrack; Assegna l’uso del colore di base quando si importa una singola immagine con il modello di creazione Importazione texture
* &lbrack;Layers&rbrack; Feedback quando si tenta di trascinare e rilasciare file incompatibili nei selettori di immagini nel pannello Proprietà
* &lbrack;Layers&rbrack; Genera un canale di opacità dal canale alfa di un’immagine importata
* &lbrack;Layers&rbrack; Image to Material (AI) è più veloce da calcolare quando si cambia categoria
* &lbrack;Livelli&rbrack; Seleziona il livello più pertinente dopo l&#39;utilizzo di un modello di creazione
* &lbrack;Layers&rbrack; I widget di posizione ora possono essere modificati con un cursore nel gruppo Advanced Parameters
* &lbrack;Esporta&rbrack; Visualizza una percentuale nella coda anziché i numeri non elaborati
* &lbrack;Interoperabilità&rbrack; Il canale di opacità viene ora riconosciuto come canale alfa quando si invia a Painter
* &lbrack;Applicazione&rbrack; Nuova finestra di dialogo per visualizzare e salvare le informazioni sull&#39;hardware
* &lbrack;Application&rbrack; Nuova preferenza per modificare la scala di height predefinita per ogni progetto
* &lbrack;Applicazione&rbrack; Migliora la modalità di visualizzazione delle risorse obsolete
* &lbrack;Scripting&rbrack; Nuove funzioni asset.documentResolution() e asset.setDocumentResolution()
* &lbrack;Scripting&rbrack; Nuova funzione select_asset()
* &lbrack;Scripting&rbrack; Python API for Texture Generators
* &lbrack;Scripting&rbrack; get_project_assets() ora restituisce oggetti 3D
* &lbrack;UI&rbrack; La dimensione della miniatura della risorsa può essere modificata nel pannello Risorse
* &lbrack;UI&rbrack; icone di visualizzazione della finestra di visualizzazione aggiornate

**Corretto:**

* &lbrack;vista 2D&rbrack; Lo zoom con la rotellina del mouse è bloccato al 244%
* &lbrack;Application&rbrack; Arresto anomalo all&#39;avvio durante l&#39;inizializzazione dell&#39;API grafica
* &lbrack;Application&rbrack; Arresto anomalo se il nome del progetto contiene il carattere #
* &lbrack;Application&rbrack; Possibile arresto anomalo durante l&#39;apertura di un vecchio progetto
* &lbrack;Application&rbrack; La riapertura del progetto corrente può generare un arresto anomalo
* &lbrack;Application&rbrack; Alcune modifiche al progetto non vengono registrate e vengono perse senza preavviso alla chiusura del progetto se non vengono salvate
* &lbrack;Export&rbrack; .sbs/.sbsar problemi di esportazione quando si utilizzano più file con lo stesso nome
* &lbrack;Export&rbrack; Spazio cromatico errato per il file .sbs/.sbsar delle immagini in scala di grigio esportate
* &blocco;Filtri&rbrack; problemi di comportamento della fusione Opacità
* &lbrack;Livelli&rbrack; a volte i file .svg non vengono riprodotti alla risoluzione corretta
* &lbrack;Performance&brack; Alcuni salvataggi di progetto su disco non sono necessari
* &lbrack;Project&rbrack; L&#39;importazione di un vecchio progetto non carica i predefiniti associati
* &lbrack;Scripting&rbrack; impossibile ottenere i parametri del primo livello inserito
* &lbrack;UI&rbrack; Il popup di anteprima quando si passa con il mouse su una risorsa può apparire nella posizione o nella schermata errata
* &lbrack;UI&rbrack; i pannelli non ancorati sono visibili e utilizzabili nella parte superiore della schermata di benvenuto

### **4.2.2 DORAYAKI**

*(Rilasciato il 5 dicembre 2023)*

**Aggiunto:**

* &lbrack;capture 3D&rbrack; è ora dal 5% al 10% più veloce in Windows
* &lbrack;capture 3D&rbrack; migliora la pulizia della trama prima della decimazione
* &lbrack;Engine&rbrack; Aggiorna Substance Engine alla versione 9.0.3
* &lbrack;Layers&rbrack; Riempimento in base al contenuto: aggiornamento a monte, varie correzioni di casi d&#39;uso e supporto di Linux

**Corretto:**

* &lbrack;capture 3D&rbrack; Se si fa clic su &quot;Indietro&quot; dopo l&#39;allineamento e poi su &quot;Avanti&quot;, la nuvola di punti non viene aggiornata
* &lbrack;capture 3D&rbrack; Trama visualizzata con fori dopo essere stata aggiunta al progetto
* &lbrack;Application&rbrack; Arresto anomalo quando si esce dalla modalità a schermo intero dopo un Capture 3D
* &lbrack;Application&rbrack; Arresto anomalo con file di immagine creati
* &lbrack;Applicazione&rbrack; Se in &quot;Tutte le librerie&quot; quando si esce da Sampler, il pannello Risorse diventa vuoto al riavvio
* &lbrack;Application&rbrack; Perdita di memoria durante l&#39;esportazione del materiale
* &lbrack;Application&rbrack; se si apre un progetto con versioni precedenti di Sampler, può verificarsi un arresto anomalo
* &lbrack;Application&rbrack; arresti anomali potenziali quando non si convertono le trame 3D
* &lbrack;Application&rbrack; arresto anomalo invisibile all&#39;apertura di un file .sbsar durante l&#39;esecuzione di Sampler
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;esportazione di un file .sbs/.sbsar con un utilizzo personalizzato
* &lbrack;Export&rbrack; La mappa normale esportata è sempre DirectX, indipendentemente dalle impostazioni dell&#39;utente
* &lbrack;Export&rbrack; L’esportazione di un oggetto 3D in un file FBX su macos non funziona
* &lbrack;Export&rbrack; Incongruenze durante l&#39;esportazione di una Pila livelli con un filtro Ricamo come file .sbs/.sbsar
* &lbrack;Export&rbrack; A volte l&#39;esportazione dei file .sbs/.sbsar non funziona
* &lbrack;Export&rbrack; A volte, durante l&#39;esportazione di un file .sbs/.sbsar, le immagini non hanno la profondità di bit corretta
* &lbrack;Layers&rbrack; Rendere invisibile un livello splatter rende invece il suo primo elemento secondario
* &lbrack;Layers&rbrack; Arresto anomalo durante il caricamento della maschera nel livello di luminosità/contrasto
* &blocco;Livelli&rbrack; dopo l&#39;eliminazione del livello vengono visualizzati messaggi di errore fuorvianti
* &lbrack;Layers&rbrack; Possibile arresto anomalo durante il downgrade di una risorsa
* &lbrack;Layers&rbrack; Alcuni output non sono collegati agli input a meno che l’utilizzo non sia forzato nel pannello Impostazioni canale
* &lbrack;Dimensioni fisiche&rbrack; Il menu a discesa del livello di riferimento può essere reimpostato per errore
* &lbrack;UI&rbrack; l&#39;importazione delle icone delle informazioni del modello deve essere aggiornata
* &lbrack;UI&rbrack; Il suggerimento per la scelta rapida da tastiera del riquadro di visualizzazione viene visualizzato ogni volta che cambia il layout del riquadro di visualizzazione

### **4.2.1 DORAYAKI**

*(Rilasciato il 21 settembre 2023)*

**Aggiunto:**

* &lbrack;Content&rbrack; Da immagine a materiale - Migliora la generazione di microdettagli nella mappa normale
* &lbrack;Content&rbrack; Da immagine a materiale - Nuovo parametro di intensità di illuminazione
* &lbrack;Layers&rbrack; Le immagini possono essere aggiunte nei livelli di importazione delle immagini
* &lbrack;Layers&rbrack; Le immagini possono essere rimosse nei livelli di importazione delle immagini
* &lbrack;Layers&rbrack; è ora possibile eliminare i livelli non validi
* &lbrack;vista 2D&rbrack; Maiusc+C scelta rapida da tastiera per far tornare indietro i canali
* &lbrack;capture 3D&rbrack; Visualizza un avviso popup quando l&#39;utente importa meno di 20 immagini
* &lbrack;Applicazione&rbrack; Nuove preferenze per impostare il valore di Affiancamento predefinito della texture di materiale
* &lbrack;Onboarding&brack; interfaccia utente dell&#39;esercitazione aggiornata per Image to Material (AI) e Upscale
* &lbrack;Scripting&rbrack; capture 3D API: DatasetInfo contiene più dati quando Capture3dState è impostato su aligned
* &lbrack;Scripting&rbrack; Nuovo argomento select_asset per create_asset(). Nuove funzioni: wait_for_computation() e clear_render_cache()

**Risolto:**

* &lbrack;Layers&rbrack; Arresto anomalo quando l&#39;area di ritaglio è molto piccola
* &lbrack;Layers&rbrack; Arresto anomalo quando si aggiunge o si modifica il filtro Ritaglio
* &lbrack;Layers&rbrack; Se si crea un quadrato nell’area di ritaglio, la risoluzione dell’output del materiale risulta errata
* &lbrack;Livelli&rbrack; Gli output a volte scompaiono quando più livelli sono disattivati
* &lbrack;Layers&rbrack; La cache di rendering potrebbe non essere invalidata correttamente con i filtri Image to Material (AI) e Upscale
* &lbrack;Layers&rbrack; impossibile aggiungere il filtro Ingrandisci quando si seleziona &quot;Non mostrare più questo messaggio&quot; nel popup di avviso
* &lbrack;Layers&rbrack; impossibile ripristinare l&#39;immagine nel filtro Ricamo una volta modificata
* &lbrack;Esporta&rbrack; la risoluzione della mappa normale esportata cambia quando si cambia il formato normale
* &lbrack;Export&rbrack; Rimuovi il suffisso del nome file &quot;\_environment&quot; durante l&#39;esportazione di un ambiente
* &lbrack;Export&rbrack; Impossibile esportare un file .sbsar quando è presente un livello di Trasforma Altera nella Pila livelli
* &lbrack;2D View&rbrack; &quot;Adatta allo schermo&quot; non funziona quando cambia la risoluzione
* &lbrack;Application&rbrack; Dopo aver chiuso la finestra dell&#39;applicazione durante l&#39;elaborazione, il processo dell&#39;applicazione potrebbe essere ancora in esecuzione
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &lbrack;Applicazione&rbrack; invalida la cache di rendering quando si alternano le reti neurali con accelerazione GPU
* &lbrack;Scripting&rbrack; La denominazione di un plug-in come nome di pannello esistente causa comportamenti imprevisti
* &lbrack;UI&rbrack; se si fa clic su un elemento con una descrizione comandi, quest&#39;ultima scompare fino al riavvio
* &lbrack;UI&rbrack; il valore della scala Height potrebbe cambiare quando si cambia risorsa
* &lbrack;UI&rbrack; Margine errato nelle caselle combinate

### **4.2 DORAYAKI**

*(Rilasciato il 5 settembre 2023)*

**Aggiunto:**

* &lbrack;Content&rbrack; Filtri Image to Material (AI) e Delighter notevolmente migliorati
* &blocco;Content&rbrack; Nuovo filtro Ingrandisci
* &lbrack;Content&rbrack; Il filtro Ritaglio ora ha una risoluzione di output dinamica.
* &lbrack;Material Creation Template&rbrack; Aggiungi impostazione dimensioni documento.
* &lbrack;Material Creation Template&rbrack; Nuovo pulsante di attivazione/disattivazione &quot;Aggiungi un ritaglio&quot;.
* &lbrack;Material Creation Template&rbrack; Nuovo interruttore &quot;Ingrandisci materiale&quot;
* &lbrack;Material Creation Template&rbrack; visualizza le dimensioni dell&#39;immagine importata
* &lbrack;Material Creation Template&rbrack; Fornisci un feedback quando non è possibile utilizzare alcune immagini importate
* &lbrack;Material Creation Template&rbrack; Avvisa quando le dimensioni dell&#39;immagine sono incoerenti
* &lbrack;Modello di creazione materiale&rbrack; nuovi avvisi e descrizioni comandi
* &lbrack;Layers&rbrack; Visualizza la risoluzione dei livelli nella Pila livelli
* &lbrack;Layers&rbrack; La risoluzione di calcolo dei livelli può ora essere impostata su Dimensioni documento o su Dimensioni input
* &lbrack;Layers&rbrack; Mostra la risoluzione dei livelli nella Pila livelli
* &blocco;Livelli&rbrack; Imposta un criterio di risoluzione dei livelli su Input documento o Input livello quando applicabile
* &lbrack;Layers&rbrack; Avvisa l&#39;utente quando un filtro Ingrandisci viene aggiunto manualmente e fornisce la documentazione necessaria
* &lbrack;Layers&rbrack; Avvisa l&#39;utente quando esegue un ingrandimento lineare e offre di utilizzare il filtro Ingrandisci
* &lbrack;Layers&rbrack; Il calcolo di un livello Immagine in materiale (AI) ora può essere annullato più rapidamente per migliorare i tempi di rendering durante l’ottimizzazione della pila di livelli
* &lbrack;Livelli&rbrack; Il calcolo di un livello di ingrandimento può ora essere annullato più rapidamente per migliorare i tempi di rendering durante l’ottimizzazione del gruppo di livelli
* &lbrack;Esporta&rbrack; Consenti l&#39;override della risoluzione delle texture esportate
* &lbrack;Esporta&rbrack; canali da esportare è ora ordinato
* &lbrack;Esporta&rbrack; visualizza la risoluzione dei canali nell&#39;elenco canali da esportare
* &lbrack;Applicazione&rbrack; Nuova preferenza per abilitare o disabilitare le reti neurali con accelerazione GPU
* &lbrack;UI&rbrack; menu a discesa con risoluzione migliorata
* &lbrack;UI&rbrack; nuove icone per i filtri Trasformazione trama, Elaborazione post-trama e Intreccio
* &lbrack;UI&rbrack; Rinomina il pannello &quot;Condividi&quot; in &quot;Esporta&quot;
* &lbrack;Scripting&rbrack; Aggiungi il supporto della risoluzione di output dei livelli all’API di esportazione
* &lbrack;Scripting&rbrack; Sono stati aggiunti Ritaglio, Ingrandimento e Dimensioni documento all’API di importazione delle immagini
* &blocco;Onboarding&rbrack; nuove esercitazioni
* &blocco;Onboarding&brack; contenuto per il completamento dell&#39;aggiornamento e Novità delle schermate
* &lbrack;Engine&rbrack; Aggiorna Substance Engine alla versione 9.0.1

**Corretto:**

* &lbrack;capture 3D&rbrack; Migliora la denominazione delle opzioni di precisione nei parametri delle impostazioni di allineamento
* &lbrack;Application&rbrack; L&#39;importazione di immagini con un numero non multiplo di 16 dimensioni può causare un arresto anomalo
* &lbrack;Application&brack; Arresto anomalo durante la duplicazione di una risorsa nel pannello Progetto
* &lbrack;Application&rbrack; Arresto anomalo quando si cambiano le risorse nel pannello Progetto
* &lbrack;Content&rbrack; Il disegno di una maschera personalizzata per il filtro Snow non funziona correttamente
* &lbrack;Exposed Parameters&rbrack; Le modifiche ai parametri esposti possono andare perdute quando si cambia materiale
* &lbrack;Interoperabilità&rbrack; L&#39;invio di un materiale dal pannello Esporta può causare un arresto anomalo
* &lbrack;Livelli&rbrack; Riempimento in base al contenuto interrompe l&#39;elaborazione quando si passa da un input di immagine singola a un input di materiale
* &lbrack;Layers&rbrack; Arresto anomalo dopo la duplicazione di una luce ambiente che contiene un materiale
* &lbrack;Layers&rbrack; Il livello di importazione immagine visualizza un nome immagine errato nel pannello Proprietà se il file immagine è stato rinominato
* &lbrack;Layers&rbrack; A volte una rotella viene visualizzata su un livello inattivo
* &lbrack;Livelli&rbrack; A volte la modifica dell’utilizzo dell’output di un’immagine in un livello di importazione di immagini non funziona
* &lbrack;Layers&rbrack; Typos nella finestra Modello di creazione
* &lbrack;UI&rbrack; la descrizione del comando di onboarding della finestra della vista 3D presenta problemi relativi allo stato attivo
* &lbrack;UI&rbrack; se il nome del file è troppo lungo, il nome dell&#39;immagine potrebbe essere in eccesso
* &lbrack;UI&rbrack; problemi minori di layout della barra degli strumenti dei pennelli quando si utilizza la gomma
* &lbrack;UI&rbrack; In alcune lingue le stringhe vengono troncate nel pannello Impostazioni visualizzatore
* &lbrack;UI&rbrack; Mentre viene visualizzato il menu a comparsa della descrizione della finestra della vista, premendo &quot;spazio&quot; viene creato un nuovo progetto

### **4.1.2 CANNOLI**

*(Rilasciato il 20 giugno 2023)*

**Corretto:**

* &lbrack;Layers&rbrack; Perdita di memoria durante l&#39;ottimizzazione di materiali e filtri Substance che causa arresti anomali

### **4.1.1 CANNOLI**

*(Rilasciato il 6 giugno 2023)*

**Aggiunto**

* &lbrack;Engine&rbrack; Aggiorna Substance Engine alla versione 9.0
* &lbrack;Interoperabilità&rbrack; Invia oggetti 3D a Stager e Painter

**Corretto:**

* &lbrack;capture 3D&rbrack; arresti anomali di applicazioni quando il rendering del capture 3D non riesce
* &lbrack;capture 3D&rbrack; Arresto anomalo in cui non è possibile caricare un&#39;immagine
* &lbrack;capture 3D&rbrack; Arresto anomalo quando si raggiunge la fase di ricostruzione della trama
* &lbrack;capture 3D&rbrack; Arresto anomalo durante il ridimensionamento del rettangolo di selezione
* &lbrack;capture 3D&rbrack; L&#39;importazione delle maschere in base alla convenzione non assegna correttamente la maschera
* &lbrack;capture 3D&rbrack; Errori di rendering durante la regolazione del rettangolo di selezione
* &lbrack;capture 3D&rbrack; Il passaggio tra la versione e l’alternanza delle opzioni di rendering durante l’elaborazione del post di Capture 3D è lento
* &lbrack;capture 3D&rbrack; Il passaggio da una versione all&#39;altra durante il passaggio Post-elaborazione di capture 3D a volte è interrotto
* &lbrack;Application&rbrack; Arresto anomalo all&#39;avvio
* &lbrack;Application&rbrack; Arresto anomalo durante la duplicazione di un materiale rinominato
* &lbrack;Application&rbrack; Arresto anomalo quando si apre un progetto .alch legacy senza la relativa cartella dipendenze
* &lbrack;Application&rbrack; Arresto anomalo quando si collega/scollega uno schermo, il computer passa alla modalità di sospensione o è accessibile in remoto
* &lbrack;Application&rbrack; Arresti anomali e perdite di memoria correlati alla gestione delle risorse non persistenti
* &lbrack;Export&rbrack; La scelta del formato del materiale per i tipi di file di oggetti 3D che incorporano o fanno riferimento a texture deve essere disattivata
* &lbrack;Export&rbrack; Arresto anomalo se si verifica un errore durante l&#39;esportazione di oggetti 3D
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;esportazione di un file .sbs/.sbsar
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;importazione di un predefinito personalizzato che ha lo stesso Label ma non lo stesso nome di file
* &lbrack;Export&rbrack; L&#39;esportazione di una luce ambientale in un file sbs/.sbsar a volte non funziona
* &lbrack;Export&rbrack; L’esportazione Gltf/Glb codifica le texture in base64
* &lbrack;Export&rbrack; Il campo di testo Nome non funziona durante la rimessa a fuoco
* &lbrack;Export&rbrack; Mantieni Affiancamento non funziona quando si esporta un livello Immagine in materiale (IA Powered) in un file .sbs/.sbsar
* &lbrack;Export&rbrack; Quando si esporta gltf e si sostituiscono i file, l&#39;elenco dei file da sostituire non è corretto
* &lbrack;Exposed Parameters&rbrack; Il valore di inizializzazione casuale non funziona nei file .sbs/.sbsar esportati
* &lbrack;Layers&rbrack; Riempimento in base al contenuto a volte arresti anomali quando viene aggiunto per la seconda volta
* &lbrack;Layers&rbrack; Arresto anomalo durante l&#39;elaborazione di una Pila livelli
* &lbrack;Layers&rbrack; Image to Material (AI) disco cache non funziona
* &lbrack;Layers&rbrack; Possibile arresto anomalo durante l&#39;ottimizzazione di un livello
* &lbrack;Performance&rbrack; perdite di memoria
* &lbrack;Project&rbrack; Arresto anomalo durante il salvataggio di un progetto
* &lbrack;Project&rbrack; L&#39;importazione dello stesso progetto due volte in una riga duplica le risorse
* &lbrack;UI&rbrack; i pulsanti arrotondati con solo un&#39;icona non vengono visualizzati correttamente

### 4.1.0 Cannoli

*(Rilasciato il 28 marzo 2023)*

**Aggiunto:**

* &blocco;Content&rbrack; nuovo filtro Ricamo
* &blocco;Contenuto&rbrack; Nuovo filtro Alterazione pittura
* &lbrack;UI&rbrack; Aggiungi opzione Esporta nel menu File
* &lbrack;capture 3D&rbrack; Indietro è ora disponibile nel passaggio di allineamento
* &lbrack;capture 3D&rbrack; Images Handle JPEG EXIF orientation
* &lbrack;capture 3D&rbrack; Scripting - Nuova proprietà dataset_info.camera
* &lbrack;capture 3D&rbrack; Aggiungi supporto Linux (consultare la documentazione)
* &lbrack;capture 3D&rbrack; Verifica dell&#39;accesso in lettura alle immagini importate
* &lbrack;Onboarding&rbrack; Scopri - 2 nuove esercitazioni (Ricamo e Alterazione pittura)
* &lbrack;Onboarding&rbrack; contenuto aggiornato della sezione Novità

**Corretto:**

* &lbrack;capture 3D&rbrack; Mantiene la posizione della fotocamera quando si modifica la versione
* &lbrack;capture 3D&rbrack; Unisce tutti i gruppi di un oggetto
* &lbrack;capture 3D&rbrack; ha rinominato le trame generate in Originale
* &lbrack;Application&rbrack; Arresto anomalo quando si tenta di generare la miniatura di un&#39;immagine inesistente
* &blocco;Risorse&rbrack; L&#39;icona del cestino non esegue alcuna operazione nel pannello Risorse
* &lbrack;Content&rbrack; L&#39;aggiornamento dei filtri con gli slot dei materiali non funziona come previsto
* &lbrack;Export&rbrack; Possibile arresto anomalo durante l’esportazione di una risorsa con filtri specifici
* &lbrack;Export&rbrack; Esportazione SBS/SBSAR - I livelli di importazione delle immagini avevano la priorità sui parametri delle immagini
* &lbrack;Export&rbrack; UE4 Il predefinito di esportazione non funziona con PNG
* &lbrack;Layers&rbrack; Arresto anomalo quando si rilasciano contemporaneamente un materiale e un filtro da Esplora sistema operativo
* &lbrack;Layers&rbrack; Arresto anomalo durante il trascinamento di un file SBSAR con qualsiasi file di immagine
* &lbrack;Layers&rbrack; Il canale di opacità del ricamo può essere completamente bianco
* &lbrack;Localization&rbrack; La lingua cinese può essere visualizzata per impostazione predefinita su Linux
* &lbrack;Performance&brack; È stato risolto un problema di memoria durante la rimozione di un livello da una risorsa.
* &lbrack;Project&rbrack; Possibile arresto anomalo durante il salvataggio
* &lbrack;UI&rbrack; Aggiungi spaziatura mancante sul pulsante del menu Versione
* &lbrack;UI&rbrack; pulsante Annulla non visualizzato correttamente
* &lbrack;UI&rbrack; Disattiva animazione cursori per parametri di post-elaborazione capture 3D
* &lbrack;UI&rbrack; La finestra Modello di creazione materiale non si chiude automaticamente quando si fa clic all&#39;esterno
* &lbrack;UI&rbrack; La funzione di accesso rapido del filtro si chiude quando si fa clic all&#39;esterno

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.2 Banane

*(Rilasciato il 9 marzo 2023)*

**Aggiunto:**

* &lbrack;capture 3D&rbrack; L&#39;utilizzo del disco mostra la quantità utilizzata
* &lbrack;capture 3D&rbrack; L&#39;importazione delle foto è asincrona e più veloce
* &lbrack;Scripting&rbrack; Nuove classi e funzioni per la creazione di script per la funzionalità capture 3D
* &lbrack;Scripting&rbrack; Nuova classe ExportController per eseguire azioni al termine, all&#39;annullamento o all&#39;errore dell&#39;esportazione
* &lbrack;Scripting&rbrack; Passare argomenti script pitoni eseguiti con —run-script
* &lbrack;UI&rbrack; feedback interfaccia utente quando si trascina una risorsa sul pannello Livelli
* &lbrack;Content&rbrack; Il filtro della temperatura colore è ora in funzione sui materiali
* &lbrack;Content&rbrack; Normale ai filtri Height ha una nuova opzione per mantenere la suddivisione in porzioni

**Corretto:**

* &lbrack;capture 3D&rbrack; dimensioni immagine corrette nel passaggio di allineamento del set di dati
* &lbrack;capture 3D&rbrack; Rimuovi vertici duplicati dopo lo srotolamento UV
* &lbrack;capture 3D&rbrack; MacOS - Migliore rilevamento se il capture 3D è disponibile
* &lbrack;capture 3D&rbrack; Arresto anomalo quando si chiude la finestra del Capture 3D durante l&#39;importazione di immagini
* &lbrack;capture 3D&rbrack; Arresto anomalo durante la generazione di una nuova versione
* &lbrack;capture 3D&rbrack; Arresto anomalo quando si tenta di caricare un oggetto 3D nel visualizzatore
* &lbrack;capture 3D&rbrack; Arresto anomalo quando si utilizza un tracciato con caratteri non UTF8
* &lbrack;capture 3D&rbrack; Tipi di risultati e suggerimenti
* &lbrack;capture 3D&rbrack; Le trame non vengono più ridimensionate per adattarsi al cubo unitario
* &lbrack;capture 3D&rbrack; Impedisce l&#39;arresto anomalo quando si chiude un Capture 3D durante il rendering
* &lbrack;capture 3D&rbrack; La rimozione di una maschera fa scomparire l&#39;immagine
* &lbrack;Application&rbrack; Arresto anomalo durante l&#39;importazione di una risorsa due volte contemporaneamente
* &lbrack;Applicazione&rbrack; esegue il backup della versione precedente delle risorse all&#39;apertura di un progetto se non ne è mai stato eseguito il backup
* &lbrack;Application&rbrack; Memorizza correttamente nella cache le mappe con baking quando non tutte le mappe sono elaborate
* &lbrack;Application&rbrack; Fullscreen si arresta quando viene visualizzato un oggetto 3D.
* &lbrack;Application&rbrack; L&#39;ultimo materiale viene duplicato durante il salvataggio del progetto
* &lbrack;Application&rbrack; Impedisce l&#39;arresto anomalo durante l&#39;annullamento del calcolo di post-elaborazione della trama durante la fase di cottura
* &lbrack;Application&rbrack; la riapertura del progetto corrente non elimina le modifiche
* &lbrack;Application&rbrack; Interrompe la generazione di miniature per oggetti 3D
* &lbrack;2D View&rbrack; Arresto anomalo quando si utilizza lo strumento Pennello
* &blocco;Riempimento in base al contenuto; &blocco;Riempimento in base al contenuto - il calcolo potrebbe bloccarsi
* &lbrack;Content&rbrack; il filtro Atlas Creator esegue il downscaling del canale Opacità
* &blocco;Esporta&rbrack; Correggi cancellazione coda esportazioni non riuscite
* &lbrack;Export&rbrack; L&#39;esportazione OBJ crea un oggetto 100 volte più piccolo del previsto
* &lbrack;Livelli&rbrack; Le immagini a colori importate come canali in scala di grigio sono ora considerate in scala di grigio
* &lbrack;Export&rbrack; i file FBX non possono essere importati in applicazioni di terze parti
* &lbrack;Export&rbrack; I nomi di output dello shader nei file USD non sono corretti
* &lbrack;Layers&rbrack; Il nome dell&#39;immagine non viene aggiornato quando si modifica il nome nell&#39;interfaccia Esplora sistema operativo
* &lbrack;Scripting&rbrack; Visualizza un messaggio di errore durante il ricaricamento di uno script non valido
* &lbrack;UI&rbrack; pulsante Materiale di base disabilitato quando non disponibile
* &lbrack;UI&rbrack; Arresto anomalo quando si accede alla finestra di dialogo del file nella finestra del modello di creazione del materiale
* &lbrack;UI&rbrack; La funzione di accesso rapido è accessibile anche quando il pannello Livelli è chiuso
* &lbrack;UI&rbrack; le icone Invia a non sono allineate
* &lbrack;UI&rbrack; l&#39;icona del livello cambia quando si fa clic sull&#39;icona della Fusione

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.1 Banane

*(Rilasciato il 7 febbraio 2023)*

**Corretto:**

* &lbrack;capture 3D&rbrack; Quando si utilizzano le maschere, la proiezione della texture potrebbe essere interrotta
* &lbrack;capture 3D&rbrack; Gli artefatti possono essere visualizzati sull&#39;oggetto
* &lbrack;capture 3D&rbrack; La trama esportata potrebbe essere molto piccola

**Problemi noti:**

* &lbrack;capture 3D&rbrack; le esportazioni FBX e OBJ riducono la scala del risultato
* &lbrack;capture 3D&rbrack; capture 3D è disponibile in MacOS anche se l&#39;hardware non è compatibile. Consulta la documentazione.
* &lbrack;capture 3D&rbrack; Arresto anomalo al termine della ricostruzione della trama.
* &blocca;Livelli&rbrack; il riempimento in base al contenuto può essere bloccato se si modificano i livelli sottostanti
* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.0 Banane

*(Rilasciato il 31 gennaio 2023)*

**Aggiunto:**

* &lbrack;capture 3D&rbrack; creazione di oggetti 3D da immagini
* &lbrack;capture 3D&rbrack; capture 3D dedicata guidata
* &lbrack;capture 3D&rbrack; Importa o genera maschere in bianco e nero sul set di dati
* &lbrack;capture 3D&rbrack; risultato allineamento - visualizza tutte le funzionalità corrispondenti come una nuvola di punti
* &lbrack;capture 3D&rbrack; Risultato dell&#39;allineamento: visualizzare e interagire con le fotocamere associate a ciascuna foto allineata
* &lbrack;capture 3D&rbrack; Definire l&#39;area di ricostruzione con un widget del rettangolo di selezione
* &lbrack;capture 3D&rbrack; Ridimensiona, trasla e ruota su tutti gli assi il widget del rettangolo di selezione
* &lbrack;capture 3D&rbrack; Definire la precisione della geometria per la trama ricostruita
* &lbrack;capture 3D&rbrack; Ottimizza trama e texture creando una nuova versione
* &lbrack;capture 3D&rbrack; Ognuna delle versioni viene decimata automaticamente in base al numero di facce di destinazione impostato
* &lbrack;capture 3D&rbrack; Il passaggio di post-elaborazione scompone automaticamente, riproietta le texture e quindi esegue il baking delle informazioni di height normale e AO dalla trama ad alto poli
* &lbrack;capture 3D&rbrack; Aggiungi il risultato originale o una versione al progetto Sampler
* &lbrack;capture 3D&rbrack; Nuovo livello di post-elaborazione trama per decimare, annullare automaticamente il contornamento, riproiettare le texture e cuocere i dettagli del livello di trama sottostante
* &lbrack;capture 3D&rbrack; nuovo livello Trasformazione trama per ridimensionare, ruotare o traslare il livello di trama sottostante
* &blocco;Esporta&rbrack; nuova finestra Esporta
* &lbrack;Export&rbrack; Impostazioni dedicate e interfaccia utente a seconda del tipo di risorsa (materiale, luce ambiente, trama)
* &lbrack;Export&rbrack; Esporta la trama come USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &lbrack;Export&rbrack; Definire il tipo di materiale durante l&#39;esportazione dei file di Substance (SBSAR, SBS)
* &lbrack;UI&rbrack; Sposta le impostazioni della cache in una nuova scheda nel popup Preferenze
* &lbrack;Application&rbrack; le finestre delle viste 2D e 3D possono ora essere ridimensionate, scambiate e impilate verticalmente
* &lbrack;Application&rbrack; Nuova variabile di ambiente SAMPLER_RESOURCES_PATH per aggiungere risorse iniziali aggiuntive
* &lbrack;Scripting&rbrack; Aggiunte variabili di ambiente SAMPLER_PLUGIN_PATH e SAMPLER_SCRIPT_PATH per importare plug-in e script all&#39;avvio
* &lbrack;Scripting&rbrack; Funzioni di esportazione aggiunte per materiali, luce ambientale e oggetti 3D
* &lbrack;Scripting&rbrack; identificatore aggiunto, valore predefinito, valori minimo e massimo, etichette ed enum ai parametri
* &lbrack;Scripting&rbrack; aggiunta della funzione import_texture per immettere un utilizzo personalizzato durante l&#39;importazione delle immagini

**Corretto:**

* &lbrack;Application&rbrack; Arresto anomalo quando si apre un progetto recente e si salva nella finestra di dialogo di conferma
* &lbrack;Application&rbrack; La finestra di dialogo File impedisce l&#39;apertura di file .ssa
* &lbrack;Application&rbrack; Le finestre di dialogo File possono essere visualizzate in una finestra di sfondo in macOS
* &lbrack;Application&rbrack; arresto anomalo potenziale all&#39;apertura di progetti 3.2
* &lbrack;Applicazione&rbrack; la selezione di un file chiude la finestra di dialogo File prima di visualizzare gli avvisi
* &lbrack;Exposed Parameters&rbrack; L&#39;esportazione delle luci di ambiente parametriche non funziona
* &lbrack;Layers&rbrack; il collegamento &quot;Fai clic qui per sfogliare&quot; nella pila di livelli non funziona più
* &lbrack;Livelli&rbrack; Il disegno di più immagini all&#39;interno dello stesso livello a volte non funziona
* &lbrack;Layers&rbrack; L&#39;impostazione di un&#39;immagine nelle proprietà del livello non aggiorna la miniatura del selettore di immagini
* &lbrack;Livelli&rbrack; L&#39;ottimizzazione di una risorsa Sampler aggiunta come livello non funziona
* &lbrack;Project&rbrack; Aggiornamento di risorse indesiderate all&#39;apertura di un progetto
* &lbrack;Scripting&rbrack; La ricerca della cartella del plug-in a volte non riesce in Windows
* &lbrack;Scripting&rbrack; Arresto anomalo quando si utilizza &#39;open_project()&#39; in uno script Python
* &lbrack;Scripting&rbrack; Esportazione JPEG non presente nell’API
* &lbrack;Scripting&rbrack; Il pannello del registro non è di sola lettura
* &lbrack;Scripting&rbrack; image_picker non funziona
* &lbrack;UI&rbrack; icona risorsa mancante per la luce ambientale nel pannello Progetto
* &lbrack;UI&rbrack; Il menu a discesa Invia a formato Designer nel popup Preferenze può essere vuoto
* &lbrack;UI&rbrack; Alcuni pulsanti hanno uno stile errato
* &lbrack;UI&rbrack; L&#39;etichetta si sovrappone ai pulsanti nei widget Gruppo pulsanti
* &lbrack;UI&rbrack; Posizione della descrizione comando errata per &quot;Strumenti&quot; in Imposta menu dimensioni fisiche
* &lbrack;UI&rbrack; Quando si cambia lingua, il menu File non è allineato

**Problemi noti:**

* &lbrack;capture 3D&rbrack; Quando si utilizzano le maschere, la proiezione della texture potrebbe essere interrotta
* &lbrack;capture 3D&rbrack; piccoli artefatti potrebbero apparire sull&#39;oggetto se la scala nella Trasforma Trama è troppo piccola
* &lbrack;capture 3D&rbrack; La trama esportata potrebbe essere molto piccola. Reimpostate la scala della trasformazione Trama e riesportate
* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

## Versione 3

### 3.4.1 Arancini

*(Rilasciato il 6 ottobre 2022)*

**Aggiunto:**

* &blocco;Onboarding&brack; Schermate Nuovo benvenuto e Novità
* &lbrack;Onboarding&rbrack; interfaccia utente della schermata iniziale aggiornata
* &lbrack;Onboarding&rbrack; nuovo contenuto Scopri nella schermata Home
* &lbrack;Scripting&rbrack; registra un errore nel pannello Registro quando non viene riconosciuto un metodo
* &lbrack;Scripting&rbrack; Nuovo modulo ssa.helpers per abilitare la stampa nel pannello Registro
* &lbrack;Application&rbrack; Supporto per il nuovo widget dei pulsanti affiancati di Substance 3D Designer

**Corretto:**

* &lbrack;Export&rbrack; Arresto anomalo durante l’esportazione di un file .sbsar che fa riferimento a un’immagine mancante
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;esportazione di una risorsa che fa riferimento a un file di immagine danneggiato
* &lbrack;Export&rbrack; L&#39;esportazione di un file .sbsar con un livello Ricamo genera un materiale grigio
* &lbrack;Export&rbrack; L&#39;esportazione di un materiale in un file .sbs/sbsar può generare un materiale completamente trasparente
* &lbrack;Export&rbrack; Il parametro Formato normale non è esposto correttamente nei file sbs/.sbsar
* &lbrack;Export&rbrack; L&#39;esportazione Sbs/sbsar di una Pila livelli che fa riferimento a un file .svg è interrotta
* &lbrack;Export&rbrack; Trasforma livello non viene esportato correttamente / Enscape aggiornato - Aggiorna predefinito di esportazione
* &lbrack;Exposed Parameters&rbrack; Arresto anomalo quando si elimina un livello contenente un parametro esposto
* &lbrack;Exposed Parameters&rbrack; L&#39;aggiornamento di un livello obsoleto nella pila di livelli può causare il danneggiamento di un elenco di parametri esposti
* &lbrack;Exposed Parameters&rbrack; I parametri che non devono essere esportati vengono comunque esportati
* &lbrack;Parametri esposti&rbrack; La rimozione di un filtro di fusione quando si elimina un livello non ne annulla la visualizzazione dei parametri
* &lbrack;Exposed Parameters&rbrack; I parametri di testo interrompono le esportazioni sbs/.sbsar
* &lbrack;Layers&rbrack; Arresto anomalo quando si rilascia una Pila livelli in un&#39;altra Pila livelli
* &lbrack;Layers&rbrack; Arresto anomalo quando non si carica un filtro
* &lbrack;Layers&rbrack; Impossibile ricaricare l&#39;immagine precedente durante la reimpostazione del campo Immagine
* &lbrack;Layers&rbrack; Impossibile annullare/ripristinare le modifiche apportate allo strumento di Trasforma
* &lbrack;Layers&rbrack; Clona /Clone livello Timbro si blocca dopo aver fatto clic su &quot;Ripristina tutte le impostazioni&quot;
* &lbrack;Layers&rbrack; L&#39;uso di uno dei pulsanti di reimpostazione impedisce di disegnare nel campo Immagine
* &lbrack;Layers&rbrack; Il pulsante Ripristina non cancella la maschera di disegno nel campo Immagine
* &lbrack;Layers&rbrack; Il pulsante Reimposta nel campo Immagine non ha alcun effetto se l&#39;utente ha disegnato qualcosa
* &lbrack;Layers&rbrack; La cache di rendering non funziona quando si utilizza lo strumento Pennello
* &lbrack;Layers&rbrack; Il livello eliminato può ancora essere visualizzato nel pannello Proprietà
* &lbrack;Livelli&rbrack; il calcolo dei livelli può bloccarsi quando si passa da un progetto all’altro
* &lbrack;Project&rbrack; A volte Sampler non è in grado di aprire un progetto dal disco
* &lbrack;2D View&rbrack; La vista 2D restituisce sempre per impostazione predefinita Output materiale

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.4.0 Arancini

*(Rilasciato il 6 settembre 2022)*

**Aggiunto:**

* &lbrack;Parametri esposti&rbrack; Nuovo Pannello dei parametri esposti
* &lbrack;Exposed Parameters&rbrack; Nuovo pulsante al passaggio del mouse sui parametri per esporre e rimuovere i parametri dal pannello Proprietà
* &lbrack;Parametri esposti&rbrack; Nuovo menu di scelta rapida con pulsante destro del mouse su parametri per esporre e rimuovere i parametri dal pannello Proprietà
* &lbrack;Exposed Parameters&rbrack; I parametri esposti sono elencati nel Pannello dei parametri esposti
* &lbrack;Exposed Parameters&rbrack; punti colore e dischi colore vengono aggiunti in diversi punti per identificare facilmente i parametri esposti
* &lbrack;Exposed Parameters&rbrack; Le etichette dei parametri possono essere modificate nel Pannello dei parametri esposti
* &lbrack;Exposed Parameters&rbrack; Visualizza un avviso per i parametri non esportabili
* &lbrack;Exposed Parameters&rbrack; visualizza un avviso se si sposta un livello con parametri di fusione esposti in un punto in cui diventano nascosti
* &lbrack;Exposed Parameters&rbrack; I parametri esposti vengono esportati nei formati SBS e SBSAR
* &lbrack;Metadata&rbrack; Supporto modelli di metadati personalizzati
* &lbrack;Metadata&rbrack; nuovo modello di metadati delle proprietà fisiche CLO
* &lbrack;Metadati&rbrack; Aggiungi icone al passaggio del mouse per aggiungere/rimuovere metadati personalizzati
* &lbrack;Python API&rbrack; Nuova API Python
* &lbrack;Python API&rbrack; per la creazione di risorse
* &lbrack;Python API&rbrack; per la gestione dei livelli
* &lbrack;Python API&rbrack; API per la gestione dei parametri
* &lbrack;Python API&rbrack; per la gestione dei progetti
* &lbrack;Python API&rbrack; È possibile attivare e disattivare un plug-in
* &lbrack;Python API&rbrack; Documentazione delle API Python accessibile dal menu Aiuto
* &blocco;Scripting&rbrack; sezione Nuovi plug-in e script nel popup Preferenze
* &lbrack;Scripting&rbrack; Creazione e importazione di plug-in per personalizzare l&#39;interfaccia di Sampler con i propri pannelli
* &lbrack;Scripting&rbrack; I plug-in diventano parte dell&#39;interfaccia di Sampler e possono essere ancorati e spostati come pannelli standard di Sampler
* &lbrack;Scripting&rbrack; Barra dei pulsanti dedicata per i plug-in sulla barra degli strumenti a destra di Sampler
* &lbrack;Scripting&rbrack; Crea e importa script per eseguire un elenco di determinate attività
* &lbrack;Scripting&rbrack; Avvia script Python dal menu Script
* &lbrack;Scripting&rbrack; I plug-in e gli script possono essere eliminati, riordinati e ricaricati dalla finestra Preferenze
* &lbrack;Scripting&rbrack; aggiunto —parametri della riga di comando run-script
* &blocco;Registri&rbrack; nuovo pannello Registri
* &blocca;Registri&brack; Attiva il pannello Registri dalla finestra Preferenze
* &blocca;Registri&rbrack; Nuova barra delle azioni per cancellare, copiare/incollare, esportare i registri
* &lbrack;Proprietà&rbrack; Nuovo pulsante al passaggio del mouse sui parametri per reimpostare il valore del parametro
* &lbrack;Proprietà&rbrack; Nuovo menu di scelta rapida con pulsante destro del mouse sui parametri per reimpostare il valore del parametro
* &lbrack;Content&rbrack; Da immagine a materiale (basata su IA) ora funziona su MacOS
* &lbrack;Engine&rbrack; Aggiorna il motore di Substance alla versione 8.6.0

**Corretto:**

* &lbrack;Application&rbrack; L&#39;applicazione potrebbe uscire quando è in corso la generazione di una miniatura
* &lbrack;Application&rbrack; L&#39;applicazione potrebbe arresto anomalo quando si utilizza &#39;Salva con nome&#39; all&#39;uscita
* &lbrack;Application&rbrack; L&#39;applicazione potrebbe bloccarsi durante l&#39;arresto di MacOS
* &lbrack;Applicazione&rbrack; Il salvataggio con la finestra di dialogo colore aperta non consente di salvare le modifiche
* &lbrack;Export&rbrack; La convenzione di denominazione dei dati di utilizzo non è corretta durante l&#39;esportazione
* &lbrack;Livelli&rbrack; Se si trascina un materiale sopra un filtro, potrebbe verificarsi l&#39;arresto anomalo
* &lbrack;Layers&rbrack; L&#39;aggiornamento di una Pila livelli obsoleta potrebbe aggiornare Pile livelli non correlate
* &blocco;Metadati&rbrack; vengono esportati campi vuoti
* &lbrack;Metadati&rbrack; Quando è presente un solo elemento di metadati, l&#39;interfaccia utente consente di riordinarlo
* &lbrack;Project&rbrack; Il calcolo non termina mai dopo la duplicazione di un materiale
* &blocco;Project&rbrack; risorsa di progetto duplicata dopo il salvataggio iniziale del progetto
* &lbrack;Project&rbrack; calcoli non necessari quando si cambia risorsa
* &lbrack;Rendering&rbrack; Alcune pile di livelli non eseguono correttamente il rendering dopo l&#39;eliminazione di un livello
* &lbrack;Security&rbrack; Correzione di CVE-2015-20107
* &lbrack;UI&rbrack; gli output 2D possono essere sfocati a seconda delle dimensioni della finestra
* &lbrack;UI&rbrack; l&#39;anteprima della risorsa può rimanere aperta in primo piano quando l&#39;applicazione perde lo stato attivo
* &lbrack;UI&rbrack; gli angoli arrotondati della schermata di avvio hanno uno sfondo quadrato opaco

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.2 Zucchini

*(Rilasciato il 28 giugno 2022)*

**Corretto:**

* &lbrack;Application&rbrack; Correggere il potenziale arresto anomalo all&#39;apertura di un progetto
* &lbrack;Esporta&rbrack; Il riavvio di Sampler interrompe l&#39;elenco dei predefiniti di esportazione personalizzati importati
* &lbrack;Interoperability&rbrack; Correggere l&#39;arresto anomalo quando un materiale inviato da Designer viene eliminato e quindi inviato nuovamente da Designer
* &lbrack;Project&rbrack; impossibile eliminare l&#39;ultima luce ambiente o materiale se si tratta dell&#39;ultima risorsa del progetto
* &lbrack;Project&rbrack; Se si fa clic con il pulsante destro del mouse su una luce ambiente, viene visualizzato l&#39;asterisco &quot;modifiche non salvate&quot;

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.1 Zucchini

*(Rilasciato il 7 giugno 2022)*

**Aggiunto:**

* &lbrack;Application&rbrack; supporto nativo per Apple silicon (M1)
* &lbrack;UI&rbrack; Nuova scelta rapida, tasto &quot;C&quot;, per scorrere i canali nella vista 2D
* &lbrack;Strumenti&rbrack; campo numerico per modificare il valore del colore in scala di grigio nella barra degli strumenti Pennello

**Corretto:**

* &lbrack;Strumenti&rbrack; L&#39;uso dello strumento Pennello su Windows con una scala dell&#39;interfaccia utente frazionaria (150%) determina lo scostamento dei tratti
* &lbrack;Prestazioni&rbrack; Migliorare il consumo di memoria
* &lbrack;Dimensioni fisiche&rbrack; informazioni sulla Dimensioni fisiche possono mancare quando si abilita la funzione
* &lbrack;UI&rbrack; Lo scorrimento del mouse a volte non funziona come previsto quando si preme il tasto Alt
* &lbrack;Application&rbrack; L&#39;applicazione potrebbe bloccarsi all&#39;apertura di un progetto salvato
* &lbrack;Application&rbrack; Arresto anomalo quando si trascinano e rilasciano più immagini e si utilizza l&#39;importazione delle texture nella finestra Modello di creazione materiale
* &lbrack;Application&rbrack; potenziale arresto anomalo durante il salvataggio di un progetto contenente un filtro personalizzato
* &lbrack;Application&rbrack; A volte lo stato del tasto Control viene perso quando si cambia applicazione
* &lbrack;Assets&rbrack; Arresto anomalo durante la ridenominazione di una cartella locale

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.0 Zucchini

*(Rilasciato il 17 maggio 2022)*

**Aggiunto:**

* &blocco;Content&rbrack; nuovo filtro Riempimento in base al contenuto (Windows e Mac)
* &lbrack;Riempimento in base al contenuto sta lavorando su immagini, materiali PBR e luci ambiente
* &lbrack;Content&rbrack; Aggiungi il parametro &quot;Mantieni porzioni&quot; a Immagine su materiale (basata su IA)
* &lbrack;Content&rbrack; Il filtro Trasforma Prospettiva può visualizzare una griglia tra i quattro punti
* &lbrack;Interoperabilità&rbrack; Invia materiali ad Adobe Substance 3D Stager
* &lbrack;Strumenti&rbrack; centra la trasformazione premendo Ctrl durante il ridimensionamento dello strumento Trasforma o Ritaglia
* &lbrack;Strumenti&rbrack; Blocca il rapporto al quadrato premendo Maiusc durante il ridimensionamento dello strumento Trasforma o Ritaglio
* &lbrack;Strumenti&rbrack; Il cursore Timbro clone offre un&#39;anteprima di ciò che verrà timbrato
* &lbrack;Strumenti&rbrack; Visualizza in anteprima il contenuto originale nel cursore della Gomma quando si utilizza Timbro Clona /Clone
* &lbrack;Strumenti&rbrack; Ctrl+Clic crea un nuovo timbro nel livello Timbro clone
* &lbrack;Strumenti&rbrack; I timbri clone successivi sono ora raggruppati in un singolo livello
* &lbrack;Strumenti&rbrack; Brush Toolbar UI Revamp
* &lbrack;Strumenti&rbrack; La posizione della barra degli strumenti Pennello è persistente durante una sessione
* &lbrack;Strumenti&rbrack; Nuove opzioni di suddivisione del pennello in porzioni per asse
* &lbrack;Strumenti&rbrack; Nascondi/visualizza la sovrapposizione sulla vista 2D quando si disegna
* &lbrack;Strumenti&rbrack; Nuova scelta rapida, tasto &quot;X&quot;, per alternare tra Pennello e Gomma
* &lbrack;Strumenti&rbrack; Nuova scelta rapida, &quot;&lbrack;&quot; &quot;&rbrack;&quot; per modificare la dimensione del pennello
* &lbrack;Strumenti&rbrack; Nuova scelta rapida, tasto &quot;E&quot;, per attivare/disattivare la gomma
* &lbrack;2D View&rbrack; Nuova modalità Proiezione sferica durante la creazione della luce ambiente
* &lbrack;2D View&rbrack; Lo strumento Pennello è supportato con la modalità proiezione sferica
* &lbrack;2D View&rbrack; Lo strumento Posizione è supportato con la modalità proiezione sferica
* &lbrack;2D View&rbrack; Annulla/Ripeti è supportato in modalità proiezione sferica
* &lbrack;2D View&rbrack; In Proiezione sferica, impostare la posizione predefinita per osservare il centro dell&#39;ambiente
* &lbrack;2D View&rbrack; Nuovo controllo dell&#39;esposizione
* &lbrack;UI&rbrack; Nel pannello Proprietà, la modifica dell&#39;immagine mostra la sorgente del contenuto (immagine o da un livello)
* &lbrack;UI&rbrack; migliorato lo sfondo del menu a discesa dei livelli/materiali di output
* &lbrack;UI&rbrack; nuova posizione delle informazioni sulla risoluzione nella vista 2D
* &lbrack;UI&rbrack; Nuovo tooltip con le scelte rapide dei controlli di navigazione della vista 3D
* &lbrack;UI&rbrack; Nuova descrizione con i controlli del pennello
* &lbrack;UI&rbrack; Nuovo tooltip con scelte rapide dei controlli di navigazione della proiezione
* &lbrack;Compound Filters&rbrack; I filtri composti gestiscono le variazioni per lavorare su immagini, materiali PBR e luci ambiente
* &lbrack;Compound Filters&rbrack; L&#39;ordine di modifica corrisponde all&#39;ordine dell&#39;elenco dei nodi nel filtro composto
* &lbrack;Compound Filters&rbrack; Le modifiche di nodi diversi con lo stesso gruppo verranno unite in un unico gruppo nel pannello Proprietà
* &lbrack;Applicazione&rbrack; con impostazioni visualizzatore dedicate per tipo di risorsa

**Corretto:**

* &lbrack;Application&rbrack; L&#39;applicazione potrebbe arrestarsi in modo anomalo quando si passa alla vista 2D
* &lbrack;Application&rbrack; Correggere un possibile deadlock o arresto anomalo durante l&#39;esportazione più volte
* &lbrack;Application&rbrack; Rendi i valori predefiniti per i canali coerenti con Substance 3D Designer
* &lbrack;Application&rbrack; Il caricamento di un progetto non attiva il ricalcolo del materiale
* &lbrack;Application&rbrack; Aggiornamento dell&#39;URL alla documentazione di importazione delle texture
* &lbrack;Content&rbrack; Quando si utilizza un filtro composto, viene richiesto di essere aggiornato quando non dovrebbe, al momento del ricaricamento
* &lbrack;Content&rbrack; i dettagli nella mappa dell&#39;altezza scompaiono quando si utilizza la Fusione di opacità
* &lbrack;UI&rbrack; Nella finestra di dialogo Colore, è possibile uscire dall&#39;intervallo utilizzando i campi di testo del cursore
* &lbrack;UI&rbrack; l&#39;elenco Utilizzo include una barra di scorrimento verticale inutile

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &lbrack;Content&rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &lbrack;Interoperability&rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.2.1 Yakitori

*(Rilasciato: 8 marzo 2022)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; Esporta metadati dpi nei file di immagine
* &lbrack;Dimensioni fisiche&rbrack; Mantiene il rapporto con le texture non quadrate durante la modifica delle dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; I metadati della Dimensioni fisiche vengono applicati immediatamente quando la dimensioni fisiche cambia
* &lbrack;UI&rbrack; Regola il cursore massimo scala Height in modo che possa influenzare qualsiasi tipo di materiale quando la Dimensioni fisiche è abilitata
* &lbrack;UI&rbrack; Nuovi suggerimenti sui filtri di ricerca nel pannello Risorsa
* &lbrack;UI&rbrack; utilizzare le descrizioni comandi per spiegare quando i pulsanti sono disattivati nel pannello Risorse
* &lbrack;Content&rbrack; aggiornamento del filtro Contrasto luminosità

**Corretto:**

* &lbrack;vista 2D&rbrack; il pulsante di rotazione di 90 gradi negli strumenti Ritaglia e Trasforma non funziona come previsto
* &lbrack;vista 2D&rbrack; Il widget Ritaglio a volte scompare
* &lbrack;Applicazione&rbrack; La cancellazione di un parametro immagine non ricollega il livello sottostante
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita dopo il salvataggio di un progetto
* &lbrack;Application&rbrack; Arresto anomalo quando si trascina e si rilascia il materiale corrente in una raccolta del pannello Risorse
* &lbrack;Application&rbrack; È possibile che si verifichi un arresto anomalo di trascinamento di una risorsa nella finestra della vista
* &lbrack;Contenuto&rbrack; La fusione normale ha una regolazione di inizializzazione casuale
* &lbrack;Content&rbrack; Il filtro Snow ha un output normale errato a seconda dei valori dei parametri neve freschi e sciolti
* &blocco;Content&rbrack; filtro parquet: cuciture impreviste corrette
* &lbrack;Content&rbrack; filtro Ricamo: rimuovi filetto in mappa metallica
* &lbrack;Content&rbrack; filtro porzioni di Floor: correzione del numero di porzioni x e y
* &lbrack;Content&rbrack; Filtro muro di mattoni: output normale e height a 16 bit
* &lbrack;Export&rbrack; Il nome predefinito del file nel popup di esportazione non è il nome del materiale corrente
* &lbrack;Esporta&rbrack; l&#39;esportazione con rapporto fisico con un predefinito di esportazione fornisce dimensioni errate
* &lbrack;Export&rbrack; Metallic non è presente nel predefinito di esportazione CLO
* &lbrack;Export&rbrack; Quando si sostituisce un predefinito personalizzato di esportazione, il nome visualizzato non viene aggiornato
* &lbrack;Layers&rbrack; I canali personalizzati del primo livello inserito non vengono rilevati
* &lbrack;Layers&rbrack; Il materiale viene rivalutato quando si modificano le modifiche di un livello nascosto
* &lbrack;Localization&rbrack; Le descrizioni comandi non sono localizzate nel pannello Esporta
* &lbrack;Dimensioni fisiche&rbrack; se si disabilita la Dimensioni fisiche di una risorsa, non viene rimossa la scala fisica
* &lbrack;Dimensioni fisiche&rbrack; impossibile impostare il valore di Scala Height oltre i limiti del cursore la prima volta
* &lbrack;Dimensioni fisiche&rbrack; L&#39;importazione di un&#39;immagine senza dimensioni fisiche impedisce l&#39;apertura del progetto
* &lbrack;Dimensioni fisiche&rbrack; La Dimensioni fisiche è erroneamente impostata su zero se mancante
* &lbrack;Dimensioni fisiche&rbrack; Dimensioni fisiche scala fisica: lo stato della casella di controllo non viene aggiornato alla prima visualizzazione
* &lbrack;UI&rbrack; Materiale di base e normale al Height non hanno una categoria
* &lbrack;UI&rbrack; Il cursore a volte è invisibile quando si disegna un&#39;immagine
* &lbrack;UI&rbrack; se è vuoto, disattiva le opzioni &quot;Copia tutto&quot; e &quot;Taglia tutto&quot; nel menu di modifica di un campo di testo
* &lbrack;UI&rbrack; I nomi dei filtri contengono caratteri errati
* &lbrack;UI&rbrack; il pulsante Dimensioni fisiche blocco non ha lo stile corretto
* &lbrack;UI&rbrack; Il pulsante di chiusura nella barra di ricerca nel pannello Risorse non cancella la stringa di ricerca

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.2.0 Yakitori

*(Rilasciato il 25 gennaio 2022)*

**Aggiunto:**

* &lbrack;Dimensioni fisiche&rbrack; nuovo pannello Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; Aggiungi opzioni Dimensioni fisiche alla finestra Modello creazione materiale
* &lbrack;Dimensioni fisiche&rbrack; Aggiungi strumento di misurazione Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; Aggiungi strumento di misurazione automatica Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; Aggiungi strumento diagnostica Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; Consenti impostazione del valore z della Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; widget a discesa per impostare il livello di zoom nella vista 2D
* &lbrack;Dimensioni fisiche&rbrack; Nuova opzione &quot;Visualizza con rapporto fisico&quot; nel menu a discesa del livello di zoom
* &lbrack;Dimensioni fisiche&rbrack; Nuova opzione &quot;Adatta alla dimensioni fisiche&quot; nel menu a discesa del livello di zoom
* &lbrack;Dimensioni fisiche&rbrack; Visualizza la Dimensioni fisiche nella vista 2D
* &lbrack;Dimensioni fisiche&rbrack; Visualizza la Dimensioni fisiche nella finestra della vista 3D
* &lbrack;Dimensioni fisiche&rbrack; Nella finestra di dialogo di importazione delle immagini, mostra profondità dimensioni fisiche se è presente una mappa di altezza importata
* &lbrack;Dimensioni fisiche&rbrack; Mostra la Dimensioni fisiche nel menu di scelta rapida della risorsa
* &lbrack;Dimensioni fisiche&rbrack; Imposta l&#39;unità di lunghezza nelle Preferenze
* &lbrack;Dimensioni fisiche&rbrack; Esporta texture che rispettano le proporzioni fisiche
* &lbrack;Metadata&rbrack; Possibilità di aggiungere metadati personalizzati a una risorsa creata dall&#39;utente
* &lbrack;Esporta&rbrack; Esporta metadati personalizzati in file .sbs(ar)
* &lbrack;Esporta&rbrack; Esporta descrizione, categoria, autore e tag metadati in file .sbs(ar)
* &lbrack;Export&rbrack; Esporta la Dimensioni fisiche come file .sbs(ar)
* &lbrack;Esporta&rbrack; Imposta l&#39;impostazione di compressione del file .sbsar
* &lbrack;Export&rbrack; Esporta la miniatura della risorsa in file .sbs(ar)
* &lbrack;Export&rbrack; Imposta il tipo di grafico durante l&#39;esportazione di un file .sbs(ar)
* &lbrack;Application&rbrack; Realtime Engine 2021 non è più disponibile
* &lbrack;Application&rbrack; Annulla/Ripeti ora supporta le modifiche del cursore Affiancamento (U,V) e della scala height
* &lbrack;Rendering&rbrack; Genera cache disco quando la risorsa creata viene salvata
* &lbrack;Assets&rbrack; Utilizzare Ctrl+clic per attivare più filtri per tipo di risorsa nel pannello Risorse
* &lbrack;UI&rbrack; Possibilità di bloccare i cursori Affiancamenti (U,V)
* &lbrack;UI&rbrack; Aggiungi un menu di scelta rapida con &quot;Copia&quot;, &quot;Taglia&quot;, &quot;Incolla&quot;, &quot;Copia tutto&quot; e &quot;Taglia tutto&quot; nei campi di testo
* &lbrack;UI&rbrack; unità di lunghezza (metri, pollici, parsec, ...) supporto per etichette e campi di testo
* &lbrack;UI&rbrack; L&#39;utente può impostare la precisione decimale utilizzata per visualizzare i numeri
* &lbrack;UI&rbrack; Utilizza le unità nei popup delle misure ovunque sia pertinente
* &lbrack;Localization&rbrack; Il nuovo nome predefinito della risorsa è ora localizzato
* &lbrack;Content&rbrack; Nuovo generatore intreccio tessuto
* &lbrack;Content&rbrack; Nuovo filtro per cambio canale
* &lbrack;Content&rbrack; Tutti i filtri pertinenti sono ora a conoscenza della Dimensioni fisiche
* &blocco;Content&rbrack; Nuove icone per Finitura legno
* &lbrack;Content&rbrack; Tutti i filtri sono ora compatibili con i canali Adobi Standard Material (ASM)
* &lbrack;Content&rbrack; I filtri possono ora avere una variante &quot;ambiente&quot;

**Corretto:**

* &lbrack;vista 2D&rbrack; Il canale rimane nell&#39;elenco quando viene rimosso
* &lbrack;Application&rbrack; Impossibile duplicare una risorsa caricata da Esplora file del sistema operativo
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &lbrack;Application&rbrack; Arresto anomalo che a volte quando si fa clic su &quot;Risorse per iniziare&quot; nel pannello Risorse
* &lbrack;Application&rbrack; Arresto anomalo quando si elimina un materiale
* &lbrack;Application&rbrack; La variabile di ambiente &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; è ancora attiva se impostata su &quot;0&quot; o &quot;&quot;.
* &lbrack;Application&rbrack; Blocca durante il salvataggio di un progetto con più materiali
* &lbrack;Application&rbrack; L&#39;importazione di un&#39;immagine può generare un arresto anomalo
* &lbrack;Application&rbrack; alcune risorse iniziali mancanti al primo avvio
* &lbrack;Export&rbrack; L&#39;esportazione di una risorsa a volte genera un arresto anomalo
* &lbrack;Layers&rbrack; Impossibile importare immagini quando il pannello dei livelli è chiuso o invisibile
* &lbrack;Livelli&rbrack; La modifica della lingua fa sì che la risorsa corrente venga ricalcolata
* &lbrack;Livelli&rbrack; La modifica dell&#39;utilizzo di un&#39;immagine importata non aggiorna la variazione del filtro da utilizzare
* &lbrack;Layers&rbrack; Image to Material (AI) a volte non viene calcolato quando si modificano i livelli sottostanti
* &lbrack;Layers&rbrack; Image to Material (AI) a volte ricalcola quando non è necessario
* &lbrack;Layers&rbrack; Non è consigliato alcun aggiornamento quando si aggiorna un filtro personalizzato sul disco
* &lbrack;Layers&rbrack; Il canale Normale a volte ha il formato dei pixel errato
* &nero;Livelli&rbrack; alcuni livelli vengono ancora calcolati anche quando non sono visibili
* &lbrack;Layers&rbrack; Gli strumenti di Vista 2D potrebbero essere interrotti quando si attiva o disattiva la visibilità di un livello
* &lbrack;Layers&rbrack; L&#39;interfaccia utente si blocca quando si utilizza Image to Material (AI)
* &lbrack;Layers&rbrack; Alternando la visibilità del livello del filtro Trasforma si interrompe lo strumento di visualizzazione 2D e si potrebbe verificare un arresto anomalo
* &lbrack;Layers&rbrack; troppe rielaborazioni durante la rimozione di un livello dal gruppo di livelli
* &lbrack;Livelli&rbrack; Quando un filtro composto contiene un input/output insolito o personalizzato, Sampler non lo calcola
* &lbrack;Performance&brack; l&#39;apertura del pannello Risorse è lenta
* &lbrack;Prestazioni&rbrack; Evita di ricalcolare inutilmente il gruppo di livelli
* &lbrack;Prestazioni&rbrack; Il caricamento delle risorse del progetto richiede troppo tempo
* &lbrack;Performance&brack; Impossibile utilizzare la cache di rendering sul disco
* &lbrack;Prestazioni&rbrack; Il passaggio tra i livelli è lento
* &lbrack;Prestazioni&rbrack; La modifica di un materiale o di un filtro è lenta
* &lbrack;Project&rbrack; Il salvataggio di un progetto alla chiusura può provocare un arresto anomalo
* &lbrack;Rendering&rbrack; La rimozione di un&#39;immagine può rimuovere tutti gli output
* &lbrack;Rendering&rbrack; Il tempo di rendering visualizzato nella finestra della vista è errato durante l&#39;ottimizzazione
* &lbrack;UI&rbrack; Impossibile scorrere verticalmente nel popup di esportazione quando necessario
* &lbrack;UI&rbrack; È possibile aprire il popup di esportazione quando non vi è nulla da esportare
* &lbrack;UI&rbrack; Alcuni popup non scorrono se il loro contenuto fuoriesce
* &lbrack;UI&rbrack; I campi di testo non sono selezionati quando si fa clic su di essi o si apre un menu
* &lbrack;UI&rbrack; Il nome del metodo di fusione nel pannello delle proprietà a volte non è corretto
* &lbrack;UI&rbrack; L&#39;opzione Salva nel menu File a volte è disattivata
* &lbrack;UI&rbrack; Il campo di testo non scompare dopo la ridenominazione di due materiali
* &lbrack;UI&rbrack; Errore di battitura nel popup delle preferenze

**Problemi noti:**

* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.2 Xocoatl

*(Rilasciato il 14 dicembre 2021)*

**Corretto:**

* &lbrack;Interoperability&rbrack; L’apertura del file .sbsar con Substance 3D Sampler da Bridge può non riuscire su Windows
* &lbrack;Livelli&rbrack; Lo spostamento dell&#39;unico livello sottostante si arresta in modo anomalo
* &lbrack;UI&rbrack; Il pulsante Impostazioni canale scompare quando si cambia lingua
* &lbrack;UI&rbrack; il nome del materiale nel pannello Proprietà scompare dopo aver salvato il progetto
* &blocca;Risorse&blocca; Se si fa clic su &quot;Tutte le librerie&quot; si può verificare un arresto anomalo

**Problemi noti:**

* &lbrack;Realtime Engine 2021&rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.1 Xocoatl

*(Rilasciato il 24 novembre 2021)*

**Aggiunto:**

* &lbrack;Interoperability&rbrack; Invia risorse (SBS o SBSAR) a Substance 3D Designer
* &lbrack;Interoperability&rbrack; impostare nelle preferenze il formato predefinito per l&#39;interoperabilità con Substance 3D Designer
* &lbrack;Interoperability&rbrack; Ricezione di più risorse da Adobe Bridge
* &lbrack;UI&rbrack; nuovo widget Numero casuale
* &lbrack;UI&rbrack; aggiornamento del menu di scelta rapida
* &lbrack;Risorse&rbrack; Trascina le immagini dal pannello Risorse al pannello Proprietà
* &lbrack;Project&rbrack; I nomi delle risorse sono riservati per evitare alcuni caratteri specifici
* &lbrack;Branding&rbrack; Aggiorna icona file per file SBSAR
* &lbrack;Engine&rbrack; Aggiorna Substance Engine versione 8.3.0

**Corretto:**

* &lbrack;Content&rbrack; Ritaglio - Mantieni proporzioni durante il ritaglio di immagini non quadrate
* &lbrack;Content&rbrack; Trasforma - La trasformazione orizzontale non viene invertita quando si utilizza il widget
* &lbrack;Content&rbrack; Gravel - correggi la pittura a maschera personalizzata su tutti i canali
* &blocco;Content&brack; porzioni di pavimento - risolvere i problemi di suddivisione in porzioni e ripetizione dei pattern
* &lbrack;Assets&rbrack; opzione Adobe Bridge grigia se non installata
* &blu;Selettore colore&rbrack; il tasto Esc chiude il Selettore colore
* &lbrack;Rendering&rbrack; Correggere la scala della distanza di diffusione quando si utilizza l&#39;input in scala di grigi
* &lbrack;Condividi&rbrack; Le opzioni Invia a sono disponibili solo con le licenze Adobe
* &lbrack;Project&rbrack; Correggere un problema di prestazioni della memoria

**Problemi noti:**

* &lbrack;Realtime Engine 2021&rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.0 Xocoatl

*(Rilasciato il 28 settembre 2021)*

**Aggiunto:**

* &lbrack;Selettore colore&rbrack; Nuova interfaccia utente Selettore colore
* &lbrack;Selettore colore&rbrack; Anteprima affiancata dei colori corrente e precedente
* &lbrack;Selettore colore&rbrack; Immettere il colore in Esadecimale
* &nero;Selettore colore&rbrack; Nuovo contagocce con anteprima colore
* &lbrack;Selettore colore&rbrack; Il contagocce può selezionare un colore esterno a Sampler
* &lbrack;Selettore colore&rbrack; modifica il colore negli spazi colore RGB o HSV
* &lbrack;Selettore colore&rbrack; Salva e gestisci campioni
* &lbrack;Interoperability&rbrack; Modifica le immagini in Illustrator dal livello Importazione immagine o dai parametri Immagine
* &lbrack;Interoperability&rbrack; Modifica le immagini in Photoshop dal livello Importazione immagine o dai parametri Immagine
* &lbrack;Widget&rbrack; Nuovo widget ritaglio
* &lbrack;Widget&rbrack; Premere Invio per convalidare il ritaglio
* &lbrack;Widget&rbrack; Il widget Ritaglio legge le dimensioni dell&#39;immagine per adattarle al widget e mantiene le proporzioni durante il ridimensionamento
* &lbrack;UI&rbrack; Nuova interfaccia utente del cursore per la visualizzazione in grigio
* &lbrack;Applicazione&rbrack; Aggiungi selezione formato normale nelle preferenze
* &lbrack;Applicazione&rbrack; Il formato normale nei livelli Importazione immagine segue il formato normale predefinito impostato nelle preferenze
* &lbrack;Application&rbrack; Nella vista 2D, la normale viene visualizzata nel formato normale impostato nelle preferenze
* &lbrack;Application&rbrack; Il normale viene esportato nel formato normale impostato nelle preferenze
* &lbrack;Export&rbrack; Aggiungi parametro formato normale alle esportazioni di file SBS e SBSAR
* &lbrack;Export&rbrack; Aggiungi impostazioni shader alle esportazioni di file SBS e SBSAR
* &lbrack;Esporta&rbrack; Imposta la risoluzione predefinita dei grafici SBS esportati
* &lbrack;Compound Filters&rbrack; crea pacchetti di filtri SSA con 7z
* &lbrack;Compound Filters&rbrack; Aggiungi i metadati delle categorie nei filtri composti
* &lbrack;Compound Filters&rbrack; I filtri composti possono avere una miniatura incorporata
* &lbrack;Compound Filters&rbrack; Estensione dei filtri composti (.ssafilter) aggiunta alla finestra di dialogo Ottieni file del contenuto
* &lbrack;Compound Filters&rbrack; Importa filtri composti (.ssafilter) nel pannello Risorse
* &lbrack;Engine&rbrack; Aggiorna il motore Substance alla versione 8.2.0

**Corretto:**

* &blocco;Application&rbrack; Le cartelle locali connesse possono bloccarsi
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &lbrack;Application&rbrack; Arresto anomalo all&#39;avvio di due istanze di Sampler
* &lbrack;Content&rbrack; Il filtro Ritaglio ha una regolazione di inizializzazione casuale
* &lbrack;Content&rbrack; Alcuni materiali Substance a volte non vengono aggiornati
* &blocco;Esporta&rbrack; Arresto anomalo durante l&#39;esportazione con un predefinito personalizzato appena aggiunto
* &lbrack;Export&rbrack; Dimensioni stimate del pacchetto mancanti nel popup di esportazione
* &lbrack;Export&rbrack; Correggere la perdita di memoria durante l&#39;esportazione di file SBS e SBSAR
* &lbrack;Compound Filters&rbrack; I filtri composti possono avere input duplicati
* &lbrack;Compound Filters&rbrack; Arresto anomalo se un filtro contiene riferimenti non soddisfatti
* &lbrack;Compound Filters&rbrack; Arresto anomalo durante il riordinamento di una pila di livelli con un filtro composto al suo interno
* &lbrack;Compound Filters&rbrack; Il rendering a volte si blocca
* &lbrack;Importa&amp;rbrack immagine; L&#39;importazione di un&#39;immagine attiva più rendering
* &lbrack;Layers&rbrack; Arresto anomalo quando si annulla/ripeti
* &lbrack;Layers&rbrack; Arresto anomalo quando si aggiunge un Materiale di base
* &lbrack;Layers&rbrack; Arresto anomalo quando si utilizza un&#39;immagine non valida come luce ambiente
* &lbrack;Layers&rbrack; Correggere l&#39;importazione duplicata quando si inserisce un filtro con diversi grafici
* &blocca;Livelli&rbrack; Riordinare i livelli non sempre funziona
* &lbrack;Project&rbrack; Arresto anomalo durante il caricamento di un file di progetto incompleto
* &blocco;Project&rbrack; arresto anomalo all&#39;apertura di un progetto danneggiato
* &lbrack;Project&rbrack; alcune risorse possono scomparire da un progetto
* &lbrack;Proprietà&rbrack; Correggere i predefiniti del filtro mancanti
* &lbrack;UI&rbrack; impossibile impostare i parametri Angolo
* &lbrack;UI&rbrack; I metadati dei filtri vengono visualizzati nel pannello Risorse
* &lbrack;UI&rbrack; il raggruppamento per categoria nasconde i filtri
* &blocco;UI&rbrack; problema di scorrimento nel pannello Risorse
* &lbrack;UI&rbrack; Il pannello di esportazione ha ora una barra di scorrimento
* &lbrack;UI&rbrack; La miniatura non viene visualizzata per alcuni formati immagine nel selettore immagini

**Problemi noti:**

* &lbrack;Realtime Engine 2021&rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &lbrack;Selettore colore&rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.0.1 Waffle

*(Rilasciato il 27 luglio 2021)*

**Aggiunto:**

* &lbrack;Pennello&rbrack; Abilita i colori nello strumento Pennello se l&#39;input dell&#39;immagine lo supporta
* &lbrack;Pennello&rbrack; tenendo premuto il tasto Maiusc nello strumento pennello, vengono tracciate linee rette
* &lbrack;Pennello&rbrack; Mostra l&#39;anteprima della linea quando si tiene premuto Maiusc nello strumento Pennello
* &lbrack;Pennello&rbrack; Lo strumento Pennello ora supporta le operazioni Annulla e Ripeti
* &lbrack;2D View&rbrack; Il colore predefinito di input dell&#39;immagine viene utilizzato quando si disegna
* &lbrack;Layers&rbrack; Valore predefinito di input Substance di lettura nei file SBSAR
* &lbrack;Rendering&rbrack; Consenti di combinare il height con normale
* &lbrack;Rendering&rbrack; supporto per la dispersione sotto la superficie (non disponibile in MacOS)
* &lbrack;Assets&rbrack; Utilizza il tipo di grafico SBSAR per determinare il tipo di risorsa
* &lbrack;Assets&rbrack; migliori prestazioni per la ricerca e l&#39;individuazione delle risorse nel pannello Risorse
* &lbrack;Assets&rbrack; Ha aggiunto una voce &quot;Tutte le librerie&quot; nel pannello Risorse che visualizza tutte le risorse di tutte le tue librerie
* &lbrack;Risorse&rbrack; L&#39;utente può ora scegliere di raggruppare le risorse per categoria o tipo
* &lbrack;Import&rbrack; Rileva automaticamente anisotropia, pellicola, brillantezza e texture specular edge color durante l&#39;importazione
* &lbrack;UI&rbrack; Sostituisci il titolo del pannello con un&#39;icona
* &lbrack;UI&rbrack; aggiornamento stile campi di testo
* &lbrack;UI&rbrack; Nuovo testo descrittivo nella finestra di creazione del modello luce ambiente
* &lbrack;Applicazione&rbrack; Esporta le risorse con la risoluzione corrente durante l&#39;invio all&#39;applicazione esterna
* &lbrack;Applicazione&rbrack; la risoluzione predefinita del materiale è ora 2048\*2048 (1024\*1024 su macos)
* &blocco;Contenuto&rbrack; Nuovi pattern nel filtro Porzioni
* &lbrack;Content&rbrack; Nuovo metodo colore doppio nel filtro Sostituzione colore

**Corretto:**

* &lbrack;2D View&rbrack; Il primo tratto nello strumento Pennello a volte è interrotto
* &lbrack;2D View&rbrack; risorse gratuite quando lo strumento Pennello non è visibile
* &lbrack;2D View&rbrack; Utilizza il cursore di ridimensionamento destro nel widget della trasformazione
* &lbrack;2D View&rbrack; I widget non vengono visualizzati se l&#39;utente ha eseguito il panning nella vista 2D in precedenza
* &lbrack;Application&rbrack; Arresto anomalo durante l’apertura di un progetto con flusso di lavoro interrotto
* &lbrack;Application&rbrack; Correggere l&#39;arresto dell&#39;applicazione per evitare che il registro venga inondato da errori inutili
* &blocco;Applicazione&rbrack; Ripristina, elimina e salva scelte rapide da tastiera non funzionano in alcuni sistemi operativi
* &lbrack;Application&rbrack; Annulla/Ripeti modifica utilizzo immagine nel livello di importazione è interrotto
* &lbrack;Esporta&rbrack; Il nome delle immagini esportate per il colore di emissione è errato
* &lbrack;Export&rbrack; Environment is 8bit when using SBSAR export
* &lbrack;Esporta&rbrack; Rimuovi gli spazi superflui nei nomi dei file immagine esportati
* &blocco;Esporta&rbrack; La sostituzione o l’eliminazione di un predefinito di esportazione personalizzato si arresta in modo anomalo
* &lbrack;Layers&rbrack; Evita l&#39;arresto anomalo quando il numero di input non corrisponde
* &lbrack;Layers&rbrack; Arresto anomalo durante l&#39;inserimento di un livello Materiale di base
* &lbrack;Layers&rbrack; Il conteggio input filtro è limitato al valore predefinito
* &lbrack;Layers&rbrack; Redo modifica erroneamente il tipo di fusione in fusione Height
* &lbrack;Layers&rbrack; Rimuovi zona di rilascio sopra le intestazioni di input
* &lbrack;Livelli&rbrack; I livelli vengono inseriti nella posizione errata attorno alle intestazioni di input
* &lbrack;Layers&rbrack; Il pulsante Ripristina tutte le impostazioni non reimposta i valori dei widget a discesa
* &lbrack;Layers&rbrack; Annulla/Ripeti quando si modifica un’immagine sul livello Importazione immagine, contrassegna il progetto come modificato e così via per salvarlo
* &lbrack;Layers&rbrack; Gli usi possono essere interrotti dai livelli di fusione
* &lbrack;Project&rbrack; Arresto anomalo durante il caricamento di un progetto precedente con cartella dipendenze mancante
* &lbrack;Project&rbrack; Arresto anomalo quando si utilizza Annulla/Ripeti dopo il salvataggio
* &lbrack;Project&rbrack; L&#39;apertura di un file SBSAR contenente una luce ambiente crea una risorsa materiale
* &lbrack;Project&rbrack; La ridenominazione di un materiale può attivare la generazione di miniature
* &lbrack;Project&rbrack; Il salvataggio dopo la ridenominazione di un materiale contrassegna il progetto come non modificato
* &blocco;Progetto&rblocco; Alcune modifiche dopo la ridenominazione di un materiale non vengono salvate
* &lbrack;Rendering&rbrack; i punti luminosi sono visibili nell&#39;ambiente con il motore in tempo reale del 2020
* &lbrack;Rendering&rbrack; Arresto anomalo durante il ridimensionamento con Real Time Engine 2021
* &lbrack;Rendering&rbrack; Ricalcola ombre alla modifica a livello di height
* &lbrack;Risorse&rbrack; Le cartelle connesse interrompono l&#39;indicizzazione delle nuove risorse quando si aggiunge un file non valido
* &lbrack;Assets&rbrack; Arresto anomalo durante la connessione di una cartella locale con molti materiali
* &lbrack;UI&rbrack; pulsanti di visualizzazione 2D/3D mancanti
* &lbrack;UI&rbrack; tutte le risorse nel pannello Risorse sono evidenziate all&#39;avvio
* &lbrack;UI&rbrack; Breadcrumbs a volte sparisce nel pannello Risorse durante l&#39;importazione dei materiali
* &lbrack;UI&rbrack; La modifica della lingua non influisce sul pannello Progetto
* &lbrack;UI&rbrack; il pannello Impostazioni canale mostra le informazioni sul flusso di lavoro precedente
* &lbrack;UI&rbrack; Allinea correttamente il testo &quot;Nessuna impostazione per questo elemento&quot; per i filtri senza modifiche nel pannello delle proprietà
* &lbrack;UI&rbrack; Gli elementi non sono allineati correttamente nella schermata di benvenuto e nel popup delle preferenze
* &lbrack;UI&rbrack; I titoli dei pannelli hanno una larghezza errata
* &lbrack;UI&rbrack; Lo scorrimento a volte è interrotto nel pannello Proprietà
* &lbrack;UI&rbrack; La schermata iniziale ha proporzioni errate ed è sfocata
* &lbrack;UI&rbrack; La modalità a schermo intero non è a schermo intero
* &lbrack;UI&rbrack; I pannelli non ancorati sono sempre in primo piano anche quando l&#39;applicazione non è attiva in MacOS
* &lbrack;UI&rbrack; Aggiorna immagine banner schermata di benvenuto
* &lbrack;Content&rbrack; Il filtro Porzione non elabora il canale di occlusione ambientale
* &lbrack;Content&rbrack; problema di unione superfici con la selezione della giuntura dell&#39;assieme di saldatura e il motivo a rombo
* &lbrack;Content&rbrack; Il filtro Rilievo funziona in 256 px per 256 px
* &lbrack;Content&rbrack; Risolvi il problema di affiancamento con le porzioni del pavimento quando lo scostamento è maggiore di 0

**Problemi noti:**

* &lbrack;Realtime Engine 2021&rbrack; Calcolo pesante, arresto anomalo dell&#39;applicazione
* &lbrack;Realtime Engine 2021&rbrack; Realtime Engine 2021 verrà arresto anomalo su computer Windows con CPU AMD e GPU Nvidia

### 3.0.0 Waffle

*(Rilasciato il 23 giugno 2021)*

**Aggiunto:**

* &lbrack;Branding&rbrack; Substance Alchemist diventa Adobe Substance 3D Sampler
* &lbrack;Branding&rbrack; Icone di una nuova applicazione
* &lbrack;UI&rbrack; Nuova esperienza utente e interfaccia utente
* &lbrack;UI&rbrack; Nuova schermata iniziale
* &lbrack;UI&rbrack; I pannelli non sono ancorabili e ancorabili nell&#39;interfaccia
* &lbrack;UI&rbrack; ancorare fino a 3 pannelli nella stessa colonna
* &lbrack;UI&rbrack; ancorate fino a 3 pannelli nello stesso pannello (schede)
* &lbrack;UI&rbrack; Disancora i pannelli per creare una finestra separata nella stessa schermata o in una schermata diversa
* &lbrack;UI&rbrack; popup per pannelli chiusi quando si fa clic sulle relative icone
* &lbrack;UI&rbrack; ridisporre la barra sinistra e destra spostando le icone dei pannelli
* &lbrack;UI&rbrack; nuova barra degli strumenti per accedere a filtri specifici direttamente (Ritaglia, Trasforma, Prospettiva Trasforma, Clona /Clone timbro)
* &lbrack;UI&rbrack; Nuovo pulsante &quot;Ottieni contenuto&quot; nella barra a sinistra
* &lbrack;UI&rbrack; Importa i file direttamente nelle tue risorse con il pulsante Ottieni contenuto
* &lbrack;UI&rbrack; Importa i file direttamente nei tuoi livelli con il pulsante Ottieni contenuto
* &lbrack;UI&rbrack; Accedi direttamente al sito Web di Substance 3D Assets con il pulsante Ottieni contenuto
* &lbrack;UI&rbrack; Il widget Risoluzione è ora direttamente accessibile nella finestra della vista
* &lbrack;UI&rbrack; Tutti gli elementi dell&#39;interfaccia utente ora vengono caricati dinamicamente
* &lbrack;UI&rbrack; Scelta rapida da tastiera: utilizza &quot;2&quot; per attivare/disattivare la visibilità della Vista 2D
* &lbrack;UI&rbrack; Scelta rapida da tastiera: utilizza &quot;3&quot; per attivare/disattivare la visibilità della vista 3D
* &lbrack;Schermata introduttiva&brack; Crea un progetto con un clic con il pulsante Nuovo
* &lbrack;Schermata introduttiva&rbrack; Nuovo banner grafica
* &blocco;Progetto&rblocco; Tutti i progetti sono ora associati a un file univoco
* &lbrack;Project&rbrack; Nuova estensione file di progetto .ssa
* &lbrack;Project&rbrack; Salva come progetto ti chiederà di selezionare dove salvare il progetto
* &lbrack;Project&rbrack; se non viene salvato, alla chiusura di Sampler verrà richiesto di salvare il progetto
* &lbrack;Project&rbrack; Se si chiude Sampler, verrà richiesto di salvare il progetto se sono presenti modifiche dall&#39;ultimo salvataggio
* &lbrack;Project&rbrack; Il nome del progetto viene visualizzato sopra la finestra della vista
* &lbrack;Project&rbrack; Il nome del progetto è in corsivo con una stella se non viene salvato o se contiene modifiche dall&#39;ultimo salvataggio
* &lbrack;Project&rbrack; Apri un file di progetto .ssa direttamente da Esplora sistema operativo
* &lbrack;Project&rbrack; Apri un file .sbsar da Esplora sistemi operativi per avviare Sampler con un nuovo progetto con questo file .sbsar pronto per l&#39;uso
* &lbrack;Project&rbrack; Aprire un file .alch (file di Substance Alchemist legacy) dall&#39;esploratore del sistema operativo
* &blocco;Pannello progetto&rbrack; nuovo pannello che conterrà tutte le risorse create all’interno di un progetto
* &lbrack;Pannello progetto&rbrack; Crea una risorsa (materiale o luce ambiente) utilizzando l&#39;icona +
* &blocco;Pannello progetto&rbrack; facendo clic con il pulsante destro del mouse sulla risorsa si apre un menu di scelta rapida
* &lbrack;Pannello progetto&rbrack; Dal menu di scelta rapida, è possibile eliminare una risorsa
* &lbrack;Pannello progetto&rbrack; Dal menu di scelta rapida, è possibile duplicare una risorsa
* &lbrack;Pannello progetto&rbrack; Dal menu di scelta rapida, è possibile rinominare una risorsa
* &lbrack;Pannello progetto&rbrack; Il passaggio tra le risorse non perderà le modifiche
* &lbrack;Resolution&rbrack; Ora puoi impostare una risoluzione non quadrata per tutte le tue risorse
* &lbrack;Resolution&rbrack; Il valore di risoluzione viene salvato per risorsa all&#39;interno di un progetto
* &lbrack;Luce ambientale&rbrack; Creazione di luce ambientale in Substance 3D Sampler
* &lbrack;Luce ambiente&rbrack; Durante la creazione di una luce ambiente, trascinando e rilasciando le immagini verrà visualizzata la finestra Modello creazione luce ambiente
* &lbrack;Environment Light&rbrack; Nel modello Environment Light Creation, selezionare Environment Import (Importa ambiente) per assegnare l&#39;immagine all&#39;ambiente nella vista 3D
* &lbrack;Luce ambiente&rbrack; Nel modello Creazione luce ambiente, seleziona Unione HDR per creare una luce ambiente da diverse immagini a 360 gradi con esposizione diversa
* &lbrack;Environment Light&brack; Nel modello Environment Light Creation, selezionare &quot;Use as bitmap&quot; (Usa come bitmap) per modificare le immagini prima di creare una luce ambiente
* &lbrack;Luce ambiente&rbrack; Assegna l’utilizzo dell’ambiente nel livello Importazione immagine per assegnare direttamente l’immagine all’ambiente nella vista 3D
* &lbrack;Luce ambiente&rbrack; Nella vista 2D per il canale ambiente, è disponibile una correzione colore automatica che consente di visualizzare il rendering come nella vista 3D
* &lbrack;Luce ambiente&rbrack; nuovo contenuto dedicato per la creazione di luce ambiente
* &lbrack;Pannello Risorse&rbrack; i pannelli Risorse e Filtri vengono uniti in un nuovo pannello Risorse
* &lbrack;Pannello Risorse&rbrack; Il pannello Risorse ora supporta i seguenti tipi di risorse: materiali, filtri e immagini
* &lbrack;Pannello Risorse&rbrack; tutte le risorse per iniziare sono accessibili nella sezione Risorse per iniziare
* &lbrack;Assets Panel&rbrack; La sezione Starter Assets è di sola lettura
* &blocca;Pannello Risorse; Nuova sezione &quot;Le tue risorse&quot;
* &blocca;Pannello Risorse&Rbrack; &quot;Le tue risorse&quot; è la sezione in cui puoi importare tutte le tue risorse
* &lbrack;Pannello Risorse&rbrack; Tutte le risorse in &quot;Le tue risorse&quot; vengono aggiunte in una cartella specifica nei tuoi documenti
* &blocca;Pannello Risorse&Rbrack; collega le cartelle locali nel pannello Risorse per aggiungere nuove sezioni
* &lbrack;Pannello Risorse&rbrack; La ricerca verrà eseguita nella cartella corrente e nelle relative sottocartelle
* &blocco;Pannello risorse&rbrack; Spostarsi tra cartelle e sottocartelle con spostamenti
* &blocca;Pannello Risorse&Rbrack; Filtra la cartella corrente per materiale, filtro o immagine
* &lbrack;Assets Panel&rbrack; Combina diversi filtri per ottenere solo materiali e immagini
* &lbrack;Pannello Risorse&rbrack; Cambia la visualizzazione passando da una griglia all’altra o da un elenco
* &lbrack;Assets Panel&rbrack; I filtri sono rappresentati con la relativa icona
* &lbrack;Assets Panel&rbrack; Le immagini sono rappresentate con la relativa anteprima
* &lbrack;Pannello Risorse&rbrack; Aumentando la larghezza si modifica il layout del pannello con una vista specifica per spostarsi tra le cartelle
* &lbrack;Pannello Risorse&rbrack; Nelle sezioni non di sola lettura, elimina una risorsa trascinandola sull’icona del raccoglitore
* &blocca;Pannello risorse&rbrack; facendo clic con il pulsante destro del mouse sulla risorsa si apre un menu di scelta rapida
* &lbrack;Pannello risorse&rbrack; Dal menu di scelta rapida, fare clic con il pulsante destro del mouse, accedere ai metadati della risorsa (nome, categoria, posizione)
* &lbrack;Assets Panel&rbrack; Dal menu di scelta rapida, eliminare la risorsa (disponibile solo nelle sezioni non di sola lettura)
* &lbrack;Assets Panel&rbrack; Dal menu di scelta rapida, sfoglia la risorsa in Adobe Bridge
* &lbrack;Pannello Livelli&rbrack; Icona Nuovo per aggiungere direttamente un materiale di base sopra i livelli
* &lbrack;Layers Panel&rbrack; Scelta rapida da tastiera - Maiusc + B aggiunge un materiale di base sopra i livelli
* &lbrack;Pannello Livelli&rbrack; I livelli ora hanno una miniatura di anteprima (miniatura materiale, icona filtro o anteprima immagine)
* &blocco;Pannello Proprietà&rbrack; Nuovo design del titolo del pannello Proprietà con il nome della risorsa e la relativa miniatura
* &lbrack;Pannello Proprietà&rbrack; I livelli filtro ora supportano i predefiniti
* &lbrack;Pannello Proprietà&rbrack; Nel livello di importazione immagine, fare clic con il pulsante destro del mouse sull&#39;anteprima immagine per modificare l&#39;immagine in Photoshop
* &lbrack;Adobe Bridge&rbrack; Sfoglia la tua risorsa in Adobe Bridge, avvierà Bridge nel percorso della risorsa
* &lbrack;Adobe Photoshop&rbrack; Modifica in Adobe Photoshop aprirà l&#39;immagine in Photoshop pronta per essere modificata
* &lbrack;Adobe Photoshop&rbrack; A ogni salvataggio in Adobe Photoshop, l&#39;immagine modificata verrà ricaricata in Sampler
* &lbrack;Substance 3D Designer&rbrack; Le risorse inviate da Adobe Substance 3D Designer arriveranno direttamente nella sezione &quot;Le tue risorse&quot; del pannello Risorse
* &lbrack;Esporta&rbrack; Invia risorse direttamente a Adobe Substance 3D Painter e Adobe Substance 3D Stager
* &lbrack;Esporta&rbrack; Invia materiali e luce ambientale ad Adobe Substance 3D Painter
* &lbrack;Esporta&rbrack; Invia luci ambiente ad Adobe Substance 3D Stager
* &lbrack;Rendering&rbrack; le nuove proprietà dei materiali sono ora supportate e renderizzate in 3D
* &lbrack;Rendering&rbrack; aggiunta di supporto per la brillantezza (Colore di lucentezza, opacità lucentezza e rugosità lucentezza)
* &lbrack;Rendering&rbrack; aggiunta del supporto per il rivestimento (colore del pelo, rugosità del pelo, normale del pelo, Specular level del pelo e rivestimento IOR)
* &lbrack;Rendering&rbrack; Aggiunta del supporto Anisotropie (livello Anisotropia e angolo Anisotropia)
* &lbrack;Rendering&rbrack; Aggiunta del supporto Specular edge color
* &lbrack;Rendering&rbrack; Attiva queste nuove proprietà nel pannello Impostazioni canale
* &lbrack;Rendering&rbrack; Introduzione di un nuovo modulo di rendering in tempo reale (2021) in versione beta
* &lbrack;Rendering&rbrack; Passa da una versione all’altra del modulo di rendering nel pannello Impostazioni visualizzatore
* &lbrack;Rendering&rbrack; Il modulo di rendering in tempo reale (2021) supporta le proprietà traslucidità, assorbimento e dispersione del materiale
* &lbrack;Rendering&rbrack; Il modulo di rendering in tempo reale (2021) introduce un nuovo modo per calcolare le ombre dalla luce ambientale
* &lbrack;Rendering&rbrack; Il modulo di rendering in tempo reale (2021) calcola in tempo reale l’irradianza della luce ambiente
* &lbrack;Pannello Impostazioni shader&rbrack; Nuovo pannello Impostazioni shader per modificare parametri specifici dello shader di materiale
* &lbrack;Shader Settings Panel&rbrack; Nuovi parametri (Scala normale, Scala height, Livello height, Intensità di emissione, IOR, Intensità normale rivestimento e Coat IOR)
* &lbrack;Shader Settings Panel&rbrack; Parametri specifici per il motore in tempo reale 2021 (dispersione sottosuperficie, distanza di dispersione, spostamento rosso e dispersione Rayleigh)
* &lbrack;Shader Settings Panel&rbrack; I valori delle impostazioni vengono salvati per risorsa
* &lbrack;Viewer Settings Panel&rbrack; Ha aggiunto un&#39;anteprima delle luci ambientali predefinite
* &lbrack;Pannello impostazioni visualizzatore&rbrack; ha aggiunto un&#39;anteprima delle trame predefinite
* &lbrack;Pannello impostazioni visualizzatore&rbrack; parametro opacità nuovo ambiente
* &lbrack;Pannello Impostazioni visualizzatore&rbrack; parametro per la sfocatura del nuovo ambiente (specifico per il modulo di rendering Realtime Engine 2021)
* &lbrack;Localization&rbrack; Nuove traduzioni in tedesco e francese
* &lbrack;Content&rbrack; Nuovi materiali di partenza predefiniti
* &lbrack;Content&rbrack; Nuove luci ambientali predefinite
* &lbrack;Content&rbrack; Tutti i filtri sono stati aggiornati, puliti e ottimizzati
* &lbrack;Content&rbrack; Il filtro Regolazione è stato suddiviso in diversi filtri
* &lbrack;Content&rbrack; nuovo filtro Luminosità/contrasto
* &lbrack;Content&rbrack; Nuovo filtro Tonalità/Saturazione
* &lbrack;Content&rbrack; Nuovo filtro Vividezza
* &lbrack;Content&rbrack; Nuovo filtro Nitidezza
* &lbrack;Content&rbrack; Nuova regolazione Normale/Height
* &blocco;Content&rbrack; filtro Nuovi pannelli
* &blocco;Content&rbrack; Nuovo filtro Sfumino
* &blocco;Content&rbrack; filtro Nuove trame
* &lbrack;Content&rbrack; Nuovo filtro Trasforma alterazione
* &lbrack;Content&rbrack; Nuovo Height per filtro AO
* &lbrack;Content&rbrack; Nuovo filtro da Height a normale
* &lbrack;Content&rbrack; Color Replace: Sostituisci in nuovi canali supportati (brillantezza, rivestimento, Anisotropia,...)
* &lbrack;Content&rbrack; Variazione colore - Modalità manuale per selezionare esattamente i colori da modificare
* &lbrack;Content&rbrack; Affiancamento - opzione per visualizzare il taglio delle cuciture
* &lbrack;Content&rbrack; Affiancamento - opzione per pittura il taglio delle cuciture per un Affiancamento perfetto
* &lbrack;Content&rbrack; Match - opzione per aggiungere un materiale che corrisponda al suo colore e alla sua ruvidezza
* &lbrack;Content&rbrack; Match - ora funziona sulle immagini in modo che corrispondano al colore di un&#39;altra immagine
* &lbrack;Content&rbrack; luce ambiente - Nuovo filtro Temperatura colore
* &lbrack;Content&rbrack; Luce ambiente - Nuovo filtro Esposizione
* &lbrack;Content&rbrack; Luce ambiente - Nuovo filtro Anteprima esposizione
* &lbrack;Content&rbrack; luce ambiente - Nuovo filtro Nadir patch
* &lbrack;Content&rbrack; luce ambiente - Nuovo filtro Nadir extract
* &lbrack;Content&rbrack; Luce ambiente - Nuovi filtri Luci (Sfera, Linea, Forma, Piano)
* &lbrack;Content&rbrack; Luce ambiente - Nuovo filtro Toppa panorama
* &lbrack;Content&rbrack; Luce ambiente - Nuovo filtro Raddrizza orizzonte
* &lbrack;Content&rbrack; luce ambiente - Nuovo filtro unione HDR

**Problemi noti:**

* &lbrack;Realtime Engine 2021&rbrack; Modifica del layout, arresto anomalo dell&#39;applicazione
* &lbrack;Realtime Engine 2021&rbrack; Calcolo pesante, arresto anomalo dell&#39;applicazione
* &lbrack;Panels&rbrack; MacOS - I pannelli non ancorati sono in primo piano rispetto a tutte le applicazioni
* &lbrack;Widget&rbrack; I widget Trasforma e Posizioni possono scomparire. Nascondi e Mostra il livello per farli apparire.
* &lbrack;Export&rbrack; L&#39;esportazione SBSAR di una luce ambientale perde la precisione di 32profondità di bit
* &lbrack;Pannello Risorse&rbrack; Le risorse possono essere evidenziate all&#39;apertura di una cartella
* &lbrack;Pannello proprietà&rbrack; Il ripristino dei parametri non reimposta l&#39;interfaccia utente della casella combinata
* &lbrack;Localization&rbrack; La modifica della lingua non influisce sul pannello del progetto finché non viene ricreato

## Versione 2

### 2.3.2 (2020.3.2) Vermicelli

*(Rilasciato il 23 febbraio 2021)*

**Aggiunto:**

* &lbrack;Localization&rbrack; supporto giapponese

**Corretto:**

* &lbrack;Livelli&rbrack; se si modifica un materiale nel filtro ricamo, si perde l’immagine del ricamo

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.3.1 (2020.3.1) Vermicelli

*(Rilasciato il 17 dicembre 2020)*

**Aggiunto:**

* &lbrack;Engine&rbrack; aggiornamento Substance Engine
* &lbrack;Application&rbrack; variabile di ambiente per disabilitare funzioni specifiche
* &lbrack;Content&rbrack; Sostituisci colore - Nuova opzione di segmentazione avanzata
* &blocco;Content&rbrack; porzioni di Floor - sono disponibili nuovi pattern e opzioni
* &lbrack;Content&rbrack; Ricamo - Aggiornamento completo del filtro
* &lbrack;Content&rbrack; Adjustment - Nuovo parametro metallico + correzione Trasforma opacità sicura

**Corretto:**

* &lbrack;Layers&rbrack; Impossibile importare due volte lo stesso filtro personalizzato
* &lbrack;Layers&rbrack; Impossibile utilizzare l&#39;input dell&#39;immagine con lo strumento pennello
* &lbrack;Esporta&rbrack; Esporta .jpg invece di .jpeg
* &lbrack;UI&rbrack; Aggiorna i crediti immagine della schermata di benvenuto
* &lbrack;UI&rbrack; Correggere il separatore invisibile nei menu
* &lbrack;UI&rbrack; I pulsanti di scelta visualizzano una descrizione comandi quando vengono troncati
* &lbrack;UI&rbrack; Errore: Materiali iniziali
* &lbrack;Application&rbrack; I caratteri UTF-8 nei nomi delle risorse non funzionano
* &lbrack;Localization&rbrack; Disattiva stile font corsivo per impostazioni internazionali cinesi
* &lbrack;Localization&rbrack; stringa localizzata divisa in 2 righe
* &lbrack;Localization&rbrack; Regola il nome della cartella e sostituiscilo con i puntini di sospensione se è troppo lungo
* &lbrack;Localization&rbrack; Formattare i numeri con il separatore delle migliaia
* &lbrack;Localization&rbrack; Localizza visualizzazione data e ora
* &lbrack;Localization&rbrack; Localizza selettore colore in Windows
* &lbrack;Content&rbrack; Trasforma - Con la trasformazione sicura attivata, la normale ruota correttamente ogni 45°
* &lbrack;Content&rbrack; Surface rilievo - Risolvere il problema di Affiancamento con disturbo frattale al perlino (disturbo avanzato)
* &lbrack;Content&rbrack; Brickwall Pattern - Input Height a 16 bit
* &lbrack;Content&rbrack; Rendering icona materiale - Problema di riflessi Specular
* &lbrack;Content&rbrack; Variazione colore - Nessun cambiamento di colore tra gli input di colore e il risultato
* &lbrack;Content&rbrack; Variazione colore - Aggiornamento prestazioni

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.3.0 (2020.3.0) Vermicelli

*(Rilasciato il 26 ottobre 2020)*

**Aggiunto:**

* &lbrack;Da immagine a materiale&rbrack; supporto della serie NVIDIA RTX 3000
* &lbrack;Da immagine a materiale&rbrack; nuovi parametri per controllare i dettagli della geometria
* &lbrack;Da immagine a materiale&rbrack; nuovi parametri per controllare la rugosità
* &lbrack;Da immagine a materiale&rbrack; nuovi parametri per controllare l&#39;intensità della luce
* &lbrack;Thumbnails&rbrack; nuovo generatore di miniature basato sul modulo di rendering PBR di Substance Designer
* &lbrack;Thumbnails&rbrack; Aggiorna materiali di base e atlanti per incorporare la loro miniatura
* &lbrack;Thumbnails&rbrack; Recupera la miniatura dal file .sbsar, se presente
* &lbrack;Thumbnails&rbrack; Modificare la qualità delle miniature nelle Preferenze
* &lbrack;Engine&rbrack; aggiornato alla versione di Substance Engine 8
* &lbrack;Localization&rbrack; localizzazione cinese
* &lbrack;UI&rbrack; Selettore tinte piatte sperimentale
* &lbrack;Content&rbrack; Nuova mappa ambiente - Studio 06
* &blocco;Content&rbrack; Aggiungi filtro Generatore Atlas
* &lbrack;Content&rbrack; Aggiungi filtro Atlas splitter
* &blocco;Content&brack; Aggiungi filtro Gomme scartate
* &lbrack;Content&rbrack; Aggiungi filtro Impronte digitali
* &lbrack;Content&rbrack; Aggiungi filtro Scratches
* &lbrack;Content&rbrack; Aggiungi filtro Rilievo superficie (sostituisci filtro modulazione height)
* &blocco;Contenuto&rbrack; Aggiungi filtro Altera
* &blocco;Content&brack; Aggiungi filtro Inverti
* &blocco;Contenuto&rbrack; Aggiungi filtro Colorazione
* &blocco;Content&rbrack; Aggiungi filtro Sostituisci colore
* &lbrack;Content&rbrack; Transform: consente di disattivare la trasformazione su un canale specifico.
* &lbrack;Content&rbrack; Trasforma - Aggiungi rotazione quando è attivata la Trasforma sicura
* &lbrack;Content&rbrack; Color Variation - Aggiunge un&#39;opzione di segmentazione per scegliere come distribuire i colori

**Corretto:**

* &lbrack;Layers&rbrack; Aggiorna correttamente l&#39;interfaccia utente quando si eseguono più azioni di annullamento/ripetizione
* &lbrack;Layers&rbrack; Impedisce arresti anomali quando si eseguono più azioni di annullamento/ripetizione
* &lbrack;Layers&rbrack; Arresto anomalo quando si utilizza Image to Material (AI Powered), con registro: numero ordinale dispositivo non valido
* &lbrack;Filters&rbrack; Migliora il rilevamento della scheda grafica NVIDIA per le funzioni specifiche di NVidia
* &lbrack;Application&rbrack; Arresto anomalo alla chiusura dell&#39;applicazione
* &lbrack;Application&rbrack; Correggere il rilevamento della quantità di VRAM in MacOS
* &lbrack;Esporta&rbrack; Alcuni predefiniti di esportazione a volte mancanti
* &lbrack;Content&rbrack; Effetto Dipinto a olio - Correggi intervallo height con ampiezza spostamento elevata
* &lbrack;Content&rbrack; Make It Tile Advanced - Nessun colore di base sbiadito durante l&#39;esportazione
* &lbrack;Content&rbrack; Crea porzione avanzata - Maschera bianca sul colore di base quando l&#39;AO è troppo forte
* &lbrack;Content&rbrack; Adjustment: ora funziona sulle immagini (scan1, ...)

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.2.1 (2020.2.1) Udon

*(Rilasciato il 21 luglio 2020)*

**Aggiunto:**

* &lbrack;Layers&rbrack; In App Messaggio di errore quando la memoria di Image to Material (basata su IA) è esaurita

**Corretto:**

* &lbrack;Layers&rbrack; Image to Material (Basato sull&#39;intelligenza artificiale) non funziona con i flussi di lavoro Specular/lucidità
* &lbrack;Layers&rbrack; Si arresta in modo anomalo quando la memoria video è esaurita durante l&#39;utilizzo di Image to Material (basato su IA)
* &lbrack;Layers&rbrack; La cache del disco non viene utilizzata per la visualizzazione durante l&#39;apertura di una pila
* &lbrack;Layers&rbrack; Rilevamento di Nvidia RTX 8000
* &lbrack;Livelli&rbrack; a volte è impossibile spostare un livello all’esterno di un input di tipo splatter
* &lbrack;Layers&rbrack; La cache del disco non viene utilizzata quando si inserisce una pila in una pila
* &lbrack;Layers&rbrack; Alcuni utilizzi dei canali vengono calcolati anche se non vengono utilizzati
* &lbrack;Layers&rbrack; Gli output vuoti vengono talvolta creati durante l&#39;importazione delle immagini
* &lbrack;2D View&rbrack; Passaggio a un altro livello con la modalità Disegno attiva blocchi panning e zoom
* &lbrack;Content&rbrack; Snow - Problema a 8 bit sulla mappa normale
* &lbrack;Content&rbrack; Pattern pavimentazione - Problema di 8 bit sulla mappa normale
* &lbrack;Content&rbrack; Equalizzatore - Problema di 8 bit sulla mappa normale
* &lbrack;Content&rbrack; Gravel Generator - Problema di 8 bit sulla mappa normale
* &blocco;Content&rbrack; Porzioni Floor - Gestisce opacità e specular level
* &lbrack;Content&rbrack; I cicli di fusione hanno sempre un predefinito di esportazione - inverti mappa normale
* &lbrack;Content&rbrack; Correggere il problema con immagini di grandi dimensioni con Image to Material (basata su IA)
* &lbrack;Application&rbrack; Arresto anomalo quando si sceglie &quot;Backup e riavvio&quot; in caso di errore del database
* &lbrack;Application&rbrack; Arresto anomalo quando si fa clic rapidamente sulla stessa risorsa
* &lbrack;Application&rbrack; arresti anomali rari all&#39;uscita
* &lbrack;Application&rbrack; Arresto anomalo durante l&#39;eliminazione di file nella schermata di benvenuto
* &lbrack;Application&rbrack; Arresto anomalo quando viene caricato un file di ambiente danneggiato
* &lbrack;Application&rbrack; arresto anomalo raro quando si cambia rapidamente risorsa di rendering
* &blocco;Applicazione&blocco; Blocco quando si esce durante l&#39;elaborazione di una risorsa
* &lbrack;Application&rbrack; arresto anomalo raro all&#39;avvio su macos
* &lbrack;Application&rbrack; Deadlock alla chiusura dell&#39;applicazione subito dopo l&#39;avvio
* &lbrack;Rendering&rbrack; a volte la vista 3D sfarfalla
* &lbrack;UI&rbrack; Il selettore colore e i widget di inizializzazione casuale non sono allineati con il resto delle modifiche
* &lbrack;Rendering&rbrack; Tempo di calcolo errato visualizzato
* &lbrack;Esporta&rbrack; Alcuni predefiniti di esportazione a volte mancanti

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte la stessa identica Pila livelli di materiale

### 2.2.0 (2020.2.0) Udon

*(Rilasciato il 15 giugno 2020)*

**Aggiunto:**

* &lbrack;Create&rbrack; Filtro Nuova immagine-materiale (basato sull&#39;intelligenza artificiale) disponibile su Windows e Linux
* &lbrack;Crea&rbrack; Rinomina bitmap in Materiale in Immagine in Materiale (B2M)
* &blocco;Importa immagine&rbrack; finestra a comparsa Nuovo modello di creazione materiale
* &lbrack;Image Import&rbrack; New &quot;Add a materiale di base&quot; (Aggiungi )
* &lbrack;Image Import&rbrack; Possibilità di trascinare e rilasciare immagini aggiuntive nel modello di creazione di materiali
* &lbrack;Image Import&rbrack; Possibilità di rimuovere immagini nel modello di creazione materiale
* &lbrack;Image Import&rbrack; Assegna automaticamente il canale alle bitmap importate in base al nome file
* &lbrack;Image Import&rbrack; Possibilità di invertire la mappa normale
* &lbrack;vista 2D&rbrack; Introduzione di una modalità di pittura
* &lbrack;vista 2D&rbrack; Le porzioni di pittura
* &lbrack;vista 2D&rbrack; Imposta un valore in scala di grigi per il colore del pennello
* &lbrack;vista 2D&rbrack; Panning e zoom durante il disegno
* &lbrack;2D View&rbrack; scelta rapida X per invertire il valore della scala di grigi del pennello
* &lbrack;vista 2D&rbrack; &lbrack; e &rbrack; scelte rapide per modificare la dimensione del pennello
* &lbrack;vista 2D&rbrack; Ctrl (o Cmd) + Rotellina del mouse per modificare la dimensione del pennello
* &lbrack;vista 2D&rbrack; È ora possibile modificare la posizione di origine quando si utilizza Clona /Clone patch
* &lbrack;Livelli&rbrack; Maiusc + trascina per dispersione automatica atlanti
* &lbrack;Layers&rbrack; Alt + trascinamento inserisce un materiale come decalcomania
* &lbrack;Layers&rbrack; Esporre facilmente le matrici di trasformazione dal Substance Designer
* &lbrack;Livelli&rbrack; L&#39;eliminazione di texture in una pila non vuota viene assegnata automaticamente ai canali corretti
* &lbrack;Livelli&rbrack; Nuovo tipo di livello: Filtri composti
* &lbrack;Parametri&rbrack; supporto input stringa Substance
* &lbrack;UI&rbrack; ha aggiunto ombre esterne per popup e menu
* &lbrack;UI&rbrack; nuovo widget a colori con opzioni di clic con il pulsante destro del mouse (cancella, copia, incolla)
* &lbrack;UI&rbrack; nuovo widget immagine con opzione strumento di pittura
* &lbrack;UI&rbrack; Possibilità di colorare su un&#39;immagine importata in un widget di immagine
* &lbrack;Rendering&rbrack; Nuova posizione videocamera predefinita
* &lbrack;Export&rbrack; i file di Substance vengono esportati per Substance Designer 2020.1.2 (10.1.2)
* &lbrack;Prestazioni&rbrack; tempo di avvio migliore dell&#39;applicazione
* &lbrack;Prestazioni&rbrack; Miglioramento della gestione delle attività asincrone
* &lbrack;Prestazioni&rbrack; migliora le prestazioni dello stack di livelli quando si aggiungono, si rimuovono o si spostano livelli
* &lbrack;Performance&rbrack; Da immagine a materiale (basata su IA) funziona più velocemente sulle GPU RTX
* &nero;Content&brack; Nuove trame: T-Shirt femmina, T-Shirt maschio, Scarpa
* &lbrack;Content&rbrack; Nuovo Metodo Fusione - Per Fusione Canale
* &lbrack;Content&rbrack; Opacità fonde la correzione del height con 2 nuovi parametri (posizione height e scala height)
* &lbrack;Content&rbrack; Aggiungi regolazioni Height nel metodo di fusione Height
* &lbrack;Content&rbrack; Usa informazioni Height opzione nella fusione maschera personalizzata
* &blocco;Content&rbrack; Nuovo strumento di correzione prospettiva
* &lbrack;Content&rbrack; Generatore pattern - Aggiunge un parametro per invertire il pattern
* &lbrack;Content&rbrack; Generatore pattern - Aggiungi un nuovo parametro Ignora dettagli materiale
* &lbrack;Content&rbrack; Nuovo filtro decalcomania
* &blocco;Content&rbrack; Nuovo filtro Moss
* &lbrack;Content&rbrack; Nuovo filtro Crepe
* &lbrack;Content&rbrack; Nuovo filtro PBR Validata
* &blocco;Content&rbrack; filtro Nuove porzioni pavimento
* &blocco;Contenuto&rbrack; Nuovo filtro Adesivo unione superfici
* &lbrack;Content&rbrack; Atlas scatter - Aggiungi input maschera personalizzata per abilitare l&#39;opzione di pittura
* &lbrack;Content&rbrack; Dirt - Aggiungi input maschera personalizzata per abilitare l&#39;opzione di pittura
* &lbrack;Content&rbrack; predefinito di esportazione CLO
* &blocco;Content&rbrack; VStitcher export preset
* &lbrack;Content&rbrack; i predefiniti HDRP di unità esportano un dettaglioMap

**Corretto:**

* &lbrack;Layers&rbrack; Le immagini importate vengono caricate troppe volte
* &lbrack;Layers&rbrack; Arresto anomalo durante la creazione di una patch clone nella parte inferiore della pila
* &lbrack;Livelli&rbrack; L&#39;aggiunta di un materiale nella parte inferiore della pila lo rende instabile
* &lbrack;Layers&rbrack; Il filtro dopo l&#39;importazione dell&#39;immagine non funziona correttamente
* &lbrack;Layers&rbrack; workflow_type non viene aggiornato quando si passa da un progetto all&#39;altro con un filtro personalizzato
* &blocca;Livelli&rbrack; disabilita il pulsante &quot;rimuovi livello&quot; quando non è selezionato alcun livello
* &lbrack;Layers&rbrack; Arresto anomalo durante il caricamento di una risorsa contenente una patch Clona /Clone
* &lbrack;Layers&rbrack; Normale agli arresti anomali del filtro Height in MacOs
* &lbrack;Application&rbrack; Arresto anomalo durante il caricamento delle mappe dell&#39;ambiente
* &lbrack;Application&rbrack; problemi di prestazioni quando è installato un driver di tavoletta grafica
* &lbrack;Application&rbrack; i file EXR a 32 bit importati sono neri
* &lbrack;Application&rbrack; Arresti anomali durante il caricamento e lo scaricamento delle risorse
* &lbrack;Application&rbrack; Arresto anomalo durante il passaggio da esplora a crea
* &lbrack;Application&rbrack; Raccolta di destinazione durante il salvataggio di un materiale non appartenente al progetto corrente
* &lbrack;Application&rbrack; correggere backup e riavvio
* &lbrack;Image Import&rbrack; Importa correttamente immagini in scala di grigio
* &lbrack;Content&rbrack; nuovi filtri per la gestione delle nuove matrici
* &lbrack;Content&rbrack; I filtri personalizzati importati sono visibili nella barra di accesso rapido
* &blocco;Contenuto&rbrack; Correggere lo scostamento del colore con il filtro Avanzate Porre affiancato
* &lbrack;Performance&brack; l&#39;apertura di una finestra di dialogo di colore è lenta e ricalcola il livello corrente
* &lbrack;UI&rbrack; Le scelte rapide da tastiera a volte non funzionano
* &lbrack;2D View&rbrack; Riempimento in base al contenuto richiede un inutile primo clic per funzionare
* &lbrack;Resources&rbrack; Le cartelle nei dischi locali vengono ancora controllate per verificare la disponibilità di aggiornamenti dopo la rimozione
* &blocco;Risorse&blocco; L&#39;eliminazione di una cartella collegata dal file system non comporta la rimozione
* &lbrack;Esporta&rbrack; Gli usi personalizzati nei predefiniti di esportazione personalizzati non vengono esportati
* &lbrack;Esporta&rbrack; l&#39;esportazione del file .sbsar con caratteri speciali nel percorso non riesce

**Problemi noti:**

* Ripetute ricalcoli di Image to Material (basati sull&#39;intelligenza artificiale) possono innescare un arresto anomalo (memoria insufficiente)
* Ripetute ricalcoli del Delighter possono innescare un arresto anomalo (memoria esaurita)
* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* L’utilizzo di Image to Material (AI) su GPU con basso VRAM può innescare un arresto anomalo (memoria insufficiente)
* La funzione Da immagine a materiale (basata su IA) non è disponibile su Specular/Lucentezza PBR
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.1.1 (2020.1.1) Tiramisu

*(Rilasciato il 1° aprile 2020)*

**Aggiunto:**

* &blocco;Project&rbrack; Esportare e importare metadati
* &lbrack;Application&rbrack; CTRL+S salva ora un predefinito in Esplora
* &lbrack;Performance&rbrack; utilizza la cache di rendering invece di ricalcolare i materiali salvati per risoluzioni fino a 2k

**Corretto:**

* &lbrack;UI&rbrack; Indicatore di calcolo fisso nella finestra della vista
* &lbrack;UI&rbrack; l&#39;immissione di valori negativi nei cursori è fissa
* &lbrack;UI&rbrack; Caselle combinate: le frecce della tastiera e la barra di scorrimento ora funzionano
* &lbrack;UI&rbrack; Mantiene il canale selezionato quando si passa da &quot;Output materiale&quot; a &quot;Input livello&quot; nella vista 2D
* &lbrack;Layers&rbrack; Risolto l&#39;arresto anomalo durante l&#39;aggiunta di canali personalizzati nel Materiale di base
* &lbrack;Layers&rbrack; Arresto anomalo durante la manipolazione dei livelli
* &lbrack;Livelli&rbrack; i canali personalizzati non vengono visualizzati con un materiale salvato
* &lbrack;Application&rbrack; Risolto l&#39;arresto anomalo raro durante l&#39;importazione di una risorsa
* &lbrack;Application&rbrack; Arresto anomalo all&#39;uscita
* &lbrack;Application&rbrack; Le caselle combinate ora mostrano i valori corretti quando si cambiano i predefiniti
* &laback;Export&brack; Predefinito Enscape rinominato in Enscape Revit
* &lbrack;Esporta&rbrack; L&#39;importazione di un predefinito di esportazione dopo la rimozione funziona
* &lbrack;Export&rbrack; Arresto anomalo all&#39;esportazione
* &lbrack;Rendering&rbrack; Rendering fisso quando il colore di base è in formato a metà virgola mobile a 16 bit
* &lbrack;Project&rbrack; Non arrestarsi in modo anomalo durante l&#39;importazione di un pacchetto danneggiato
* &lbrack;Project&rbrack; migrazione da Handle 2019.1.4 a 2.x.x quando la funzione Crea non è mai stata aperta
* &lbrack;Project&rbrack; Correggere un arresto anomalo durante l&#39;importazione dello stesso progetto due volte
* &blocco;Project&rbrack; Correggere un arresto anomalo durante l&#39;importazione dei progetti
* &lbrack;Resources&rbrack; I filtri personalizzati importati nelle versioni precedenti funzionano
* &lbrack;Resources&rbrack; I materiali con lo stesso nome non si cancellano più a vicenda
* &lbrack;Resources&rbrack; Arresto anomalo durante il collegamento di una cartella locale
* &lbrack;Resources&rbrack; le cartelle create dall&#39;utente per Materiali Starter non vengono più rimosse dopo un riavvio
* &lbrack;Inspire&rbrack; Correggi area di rilascio materiale/raccolta e aggiungi un messaggio di avviso se si utilizza un materiale non salvato

**Problemi noti:**

* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

### 2.1.0 (2020.1.0) Tiramisu

*(Rilasciato il 12 marzo 2020)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; Esporta selezione predefinita per comprimere la texture per i moduli di rendering e i motori grafici
* &lbrack;Export&rbrack; Esporta predefinito su Unreal Engine 4
* &lbrack;Esporta&rbrack; Esporta predefinito in Unity Standard
* &lbrack;Esporta&rbrack; Esporta predefinito in Unity HDRP
* &lbrack;Esporta&rbrack; Esporta predefinito in Cicli fusione/Evento
* &lbrack;Export&rbrack; Esporta predefinito in Arnold 5
* &lbrack;Esporta&rbrack; Esporta predefinito nel modulo di rendering Corona
* &lbrack;Esporta&rbrack; Esporta predefinito su Enscape
* &lbrack;Export&rbrack; Esporta predefinito in Keyshot 9
* &lbrack;Esporta&rbrack; Esporta predefinito su Redshift
* &lbrack;Esporta&rbrack; Esporta predefinito su Vray Next
* &lbrack;Export&rbrack; Esporta predefinito in Lens Studio
* &lbrack;Export&rbrack; Esporta predefinito in Spark AR Studio
* &lbrack;Esporta&rbrack; Esporta predefinito in Lucentezza Specular PBR dalla Rugosità metallica PBR
* &blocco;Esporta&rbrack; Nuova interfaccia utente di esportazione
* &blocco;Esporta&rback; Ricorda impostazioni di esportazione
* &blocco;Esporta&rbrack; Importa e gestisci i predefiniti di esportazione personalizzati
* &blocco;Esporta&rbrack; Elimina e sostituisci i predefiniti di esportazione personalizzati
* &lbrack;Esporta&rbrack; Rinomina i predefiniti di esportazione personalizzati
* &lbrack;Esporta&rbrack; Imposta la risoluzione di esportazione predefinita sulla risoluzione corrente
* &lbrack;Esporta&rbrack; Aggiungi la scelta per creare una sottocartella al percorso di esportazione
* &blocco;Esporta&rbrack; Messaggio di avvertenza prima di sostituire i file esistenti
* &lbrack;Application&rbrack; Nuovo schema di numerazione delle versioni
* &lbrack;Application&rbrack; Apri Crea all&#39;avvio e cambia l&#39;ordine dei laboratori
* &blocco;Schermata introduttiva&bra; Nuovo banner di benvenuto
* &lbrack;Project&rbrack; Apri l&#39;ultimo progetto all&#39;avvio
* &lbrack;UI&rbrack; Nuovo stile casella combinata
* &lbrack;Vista 2D&rbrack; F scelta rapida da tastiera da attivare nella vista 2d
* &lbrack;Filters&rbrack; Supporto aggiunto per alchemist::parameterVisibility tag nei grafici a Substance
* &lbrack;Filters&rbrack; Dispone di un&#39;impostazione globale per gestire la visibilità dei parametri in base al flusso di lavoro
* &lbrack;Resources&rbrack; Nuova opzione della riga di comando per configurare risorse e cartelle collegate con un file di configurazione
* &lbrack;Verifica versione&rbrack; Configurazione del controllo delle versioni
* &lbrack;Content&rbrack; Nuovi materiali per iniziare
* &lbrack;Content&rbrack; Bitmap to Material - Aggiungi la possibilità di definire il canale metallico (uniforme, importazione immagine personalizzata, selezione colore)
* &lbrack;Content&rbrack; Adjustment - Aggiunge il supporto del flusso di lavoro specular/lucentezza PBR
* &lbrack;Content&rbrack; Atlas scatter - Nuovi parametri

**Corretto:**

* &lbrack;Project&rbrack; Arresto anomalo durante l&#39;importazione dello stesso progetto due volte
* &lbrack;Project&rbrack; arresto anomalo corretto durante l&#39;importazione e l&#39;apertura di progetti più volte
* &lbrack;Application&rbrack; Arresto anomalo durante il caricamento di un materiale senza nome
* &lbrack;Application&rbrack; Riconosci i file mancanti quando li reimporta
* &lbrack;Application&rbrack; Correggi arresto anomalo casuale all&#39;arresto
* &lbrack;Application&rbrack; arresto anomalo raro fisso quando si scarica un materiale in Create
* &lbrack;Application&rbrack; arresto anomalo casuale fisso quando si utilizzano controlli dell&#39;interfaccia utente
* &lbrack;Application&rbrack; Corretta esportazione dei file di registro sul desktop in Windows 10
* &lbrack;UI&rbrack; la dimensione del pannello di esportazione non è corretta quando lo si apre in Crea
* &lbrack;UI&rbrack; Apri il progetto con un solo clic
* &lbrack;UI&rbrack; Imposta correttamente i valori minimo e massimo del cursore
* &lbrack;UI&rbrack; Mostra l&#39;etichetta degli usi del canale invece degli ID
* &lbrack;UI&rbrack; Facendo clic su un materiale si apre/chiude sempre il pannello di regolazione
* &lbrack;UI&rbrack; Correggi colori livelli nascosti
* &lbrack;UI&rbrack; miglioramenti ai pulsanti della schermata iniziale
* &lbrack;Livelli&rbrack; meno ricalcoli non necessari
* &lbrack;Layers&rbrack; Si Arresta In Modo Anomalo Quando Si Utilizza Patch Clone
* &lbrack;Livelli&rbrack; La selezione di un livello di importazione immagine non attiva più un calcolo
* &lbrack;Layers&rbrack; Clona /Clone i livelli di Riempimento in base al contenuto non vengono più ricalcolati quando sono selezionati
* &lbrack;Impostazioni canale&rbrack; L’attivazione o la disattivazione degli usi ora attiva un rendering
* &blocca;Risorse&blocca; impedisce il blocco quando si fa clic su una pila nella libreria
* &lbrack;Resources&rbrack; Prestazioni raggiunte quando si aggiunge nuovamente una cartella collegata aggiunta in precedenza
* &lbrack;Resources&rbrack; È stato risolto un arresto anomalo durante il tentativo di aprire un file .sbsar eliminato.
* &lbrack;Prestazioni&rbrack; Evita di caricare materiali per accedere ai relativi parametri
* &lbrack;Performance&brack; Backup delle risorse solo se utilizzate in un progetto o in un materiale creato
* &lbrack;Esporta&rbrack; I materiali fissi nella coda di esportazione a volte vengono saltati o esportati con parametri errati
* &lbrack;vista 2D&rbrack; Panning e zoom ripristinati
* &lbrack;Content&rbrack; Il pattern parquet tiene conto del canale di Occlusione ambientale
* &lbrack;Content&rbrack; Pittura - Visualizza l&#39;input della maschera quando si abilita la maschera personalizzata
* &lbrack;Content&rbrack; Stonewall Pattern - Rimuovi possibili effetti di striatura nella mappa normale
* &lbrack;Content&rbrack; Modulazione Height - Correggere le doppie voci di colore di base nella vista 2d

**Problemi noti:**

* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

## Versione 1

### 1.1.4 (2019.1.4) Sesamo

*(Rilasciato: 30 gennaio 2020)*

**Aggiunto:**

* &blocco;Resources&rbrack; Richiesta di conferma durante la cancellazione di una cartella di risorse

**Corretto:**

* &blocca;Livelli&rbrack; sposta i livelli in due o più livelli sottostanti o superiori
* &lbrack;Create&rbrack; allocazione di un budget VRAM sufficiente per ottenere buone prestazioni

**Problemi noti:**

* L&#39;importazione di molte risorse può davvero rallentare la Substance Alchemist
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

### 1.1.3 (2019.1.3) Sesamo

*(Rilasciato il 28 gennaio 2020)*

**Aggiunto:**

* &blocco;Workflow&rbrack; supporto di più flussi di lavoro
* &lbrack;Workflow&rbrack; supporto del flusso di lavoro di Lucentezza degli Specular PBR
* &blocco;Workflow&rbrack; nuovo pannello Impostazioni canale
* &lbrack;Workflow&rbrack; selezione del flusso di lavoro alla creazione del progetto
* &lbrack;Impostazioni canale&rbrack; Attiva/Disattiva calcolo canale specifico
* &lbrack;Impostazioni canale&rbrack; Visualizza l&#39;elenco dei canali personalizzati disponibili nel materiale corrente
* &lbrack;Impostazioni canale&rbrack; calcolo automatico dei canali personalizzati quando necessario
* &lbrack;Impostazioni canale&rbrack; Forza/Blocca calcolo canali personalizzati
* &lbrack;Layers&rbrack; Nuova interfaccia utente del segnaposto di input materiale nei filtri Atlas scatter e Frazionamento
* &lbrack;Layers&rbrack; Il parametro di input dell&#39;immagine di un filtro può essere alimentato dai livelli sottostanti
* &lbrack;Layers&rbrack; Visualizza una notifica quando alcuni livelli non sono aggiornati
* &lbrack;Layers&rbrack; possibilità di aggiornare alla versione più recente di livelli obsoleti tramite la notifica
* &blocco;Project&rbrack; Nuovi campi metadati durante la creazione del progetto
* &lbrack;Inspire&rbrack; le varianti generate sono specifiche di un progetto
* &lbrack;vista 2D&rbrack; Passa tra gli input e gli output dei livelli e gli output dei materiali
* &lbrack;Schermata introduttiva&rbrack; Aggiungi progetto di importazione (.alch), opzione
* &lbrack;Preferenze&rbrack; Nuova finestra Preferenze per impostare la posizione della cache e le impostazioni di privacy analitica
* &blocco;UI&rbrack; pulsanti Nuova interfaccia utente
* &lbrack;Performance&rbrack; miglioramento generale del sistema di parallelizzazione
* &lbrack;Performance&rbrack; ottimizzazione del numero di calcoli di materiale
* &lbrack;Engine&rbrack; aggiornamento Substance Engine
* &lbrack;Framework&rbrack; Aggiornamento a Qt 5.13
* &lbrack;MacOS&rbrack; miglioramenti globali del supporto di macOS Catalina
* &lbrack;Content&rbrack; Filtro di regolazione - Intensità normale e parametri inverti

**Corretto:**

* &lbrack;Layers&rbrack; Annulla l&#39;impostazione del parametro Image Input quando si elimina il livello
* &lbrack;Layers&rbrack; Correggere un arresto anomalo quando si aggiunge un livello patch clone
* &lbrack;Layers&rbrack; Correggere alcuni arresti anomali quando si fondono livelli per impilare materiali in altri materiali di Pila livelli
* &lbrack;Export&rbrack; La selezione dei canali per l&#39;esportazione è ora rispettata
* &lbrack;Resources&rbrack; Non eseguire l&#39;arresto anomalo durante la navigazione nel pannello Risorse
* &lbrack;Resources&rbrack; Correggere l&#39;arresto anomalo durante l&#39;importazione di file di Substance danneggiati
* &lbrack;Resources&rbrack; Riduzione del numero di arresti anomali durante il caricamento di cartelle di grandi dimensioni
* &lbrack;Thumbnail&rbrack; Il calcolo delle miniature non blocca l&#39;interfaccia
* &lbrack;Image Import&rbrack; uniformizzazione del tipo di immagine supportata nell&#39;applicazione
* &lbrack;Preset&rbrack; Salva la descrizione durante la creazione di un predefinito da un SBSAR
* &laback;Ispirazione&brack; Correggi trascinamento immagine
* &lbrack;Application&rbrack; Correggi arresti anomali all&#39;uscita
* &lbrack;Application&rbrack; Fix si arresta in modo anomalo all&#39;uscita durante l&#39;esportazione dei materiali
* &lbrack;UI&rbrack; correzioni e miglioramenti
* &lbrack;UI&rbrack; Rinomina risorsa temporanea in &quot;materiale non salvato&quot;
* &lbrack;Content&rbrack; Aggiornamento globale e pulizia di tutti i filtri

**Problemi noti:**

* L&#39;importazione di molte risorse può davvero rallentare la Substance Alchemist
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

### 1.1.2 (2019.1.2) Sesamo

*(Rilasciato l&#39;11 dicembre 2019)*

**Aggiunto:**

* &lbrack;Layers&rbrack; Le opzioni Salva e Salva con nome sono accessibili tramite l&#39;interfaccia nella barra degli strumenti della serie di livelli
* &lbrack;Resources&rbrack; Analisi dettagliata del pannello Risorse per spostarsi tra le cartelle
* &blocca;Risorse&blocca; pulsante Mantieni indietro premuto per accedere a tutte le cartelle superiori
* &lbrack;Resources&rbrack; Aggiungi opzione di ricaricamento dei materiali importati per aggiornarli alla versione più recente
* &lbrack;Layers&rbrack; Possibilità di modificare l&#39;immagine nel livello di importazione immagine
* &lbrack;Livelli&rbrack; possibilità di definire un&#39;immagine come canale (colore di base, normale, height,...) nel livello Importazione immagine
* &lbrack;Content&rbrack; Nuovo filtro Atlas scatter per dispersione nuovi elementi atlas da Substance Source
* &lbrack;Content&rbrack; Nuovo filtro effetto Pittura a olio
* &lbrack;Content&rbrack; Nuovo filtro di generazione canali per generare height, occlusione ambientale e rugosità da colore di base e mappa normale

**Corretto:**

* &lbrack;UI&rbrack; Riattiva le descrizioni comandi sulla barra degli strumenti dello stack Livelli
* &lbrack;UI&rbrack; risolvere il problema che si verifica quando si digitano due decimali in un valore del cursore
* &lbrack;Performance&rbrack; Correggi l&#39;arresto anomalo quando si passa rapidamente da un materiale all&#39;altro
* &lbrack;Esporta&rbrack; Il passaggio a un altro materiale prima della fine di un&#39;esportazione non subisce più l&#39;arresto anomalo
* &lbrack;Resources&rbrack; Il menu di scelta rapida viene visualizzato sopra il materiale quando si fa clic su di esso con il pulsante destro del mouse
* &lbrack;Layers&rbrack; Il collegamento &quot;Fai clic qui&quot; funziona quando la pila di livelli è vuota
* &lbrack;Presets&rbrack; Rimuovi il pulsante Salva nel pannello Tweak quando si tratta di un materiale creato in Alchemist
* &lbrack;Tweak&rbrack; Messaggio informativo visualizzato quando si tratta di un materiale creato in Alchemist
* &lbrack;Viewport&rbrack; il valore predefinito della texture di Specular level è corretto in 0,04
* &laback;Menu file&brack; opzione Correggi e rinomina Salva e Salva con nome
* &lbrack;Engine&rbrack; Aggiorna la versione del motore di Substance per evitare arresti anomali di alcuni file SBSAR durante l&#39;importazione.
* &lbrack;Content&rbrack; Il filtro Affiancamento funziona sul canale di occlusione ambientale
* &lbrack;Content&rbrack; Il filtro Ritaglio funziona sul canale di occlusione ambientale
* &lbrack;Content&rbrack; Il filtro Acqua modifica il guadagno della mappa di altezza
* &lbrack;Content&rbrack; Correggi Affiancamento del materiale superiore nel metodo di fusione opacità
* &lbrack;Content&rbrack; il Height del materiale in alto viene mantenuto nel metodo di fusione opacità
* &lbrack;Content&rbrack; Possibilità di aggiungere una maschera personalizzata, un pattern personalizzato o una mappa di scala nel filtro Perforazione
* &lbrack;Content&rbrack; Il filtro Modulazione Height forza height e mappa normale in 16 bit
* &lbrack;Content&rbrack; Il filtro di regolazione forza le mappe normali e di height in 16 bit

**Problemi noti:**

* L&#39;importazione di molte risorse può davvero rallentare la Substance Alchemist
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

### 1.1.1 (2019.1.1) Sesamo

*(Rilasciato il 26 novembre 2019)*

**Aggiunto:**

* &lbrack;Blend&brack; Nuovo metodo di fusione opacità
* &lbrack;Engine&rbrack; Nuova versione di Substance Engine

**Corretto:**

* &lbrack;Layers&rbrack; Correggere l&#39;arresto anomalo durante l&#39;eliminazione di un livello che sta ancora elaborando
* &blocca;Livelli&rbrack; Correggi l&#39;arresto anomalo durante la rimozione del livello inferiore
* &lbrack;Layers&rbrack; Correggere l&#39;arresto anomalo quando il nome del materiale contiene caratteri speciali
* &lbrack;Layers&rbrack; Interrompere l&#39;elaborazione di tutti i filtri che utilizzano un widget
* &blocco;Livelli&rbrack; Evitare l&#39;arresto anomalo durante l&#39;utilizzo dei filtri Patch clone e Riempimento in base al contenuto
* &lbrack;Layers&rbrack; Correggere l&#39;arresto anomalo durante il trascinamento di un filtro negli slot di input di uno splatter
* &lbrack;Resources&rbrack; Correggere l&#39;arresto anomalo durante il collegamento di cartelle locali o l&#39;importazione di risorse in Substance Alchemist
* &lbrack;Collection&rbrack; Correggi l&#39;arresto anomalo durante il passaggio rapido tra i materiali
* &lbrack;UI&rbrack; Correggere l&#39;arresto anomalo se il valore è null o non valido in affiancatura, spostamento dei cursori nella finestra della vista
* &lbrack;Inspire&rbrack; Correggere l&#39;arresto anomalo durante l&#39;accesso alla scheda Ispirazione
* &lbrack;Inspire&rbrack; Correggere l&#39;arresto anomalo mentre si ispira a un materiale della pila di livelli appena salvati
* &lbrack;Performance&rbrack; Substance di materiali e filtri (Affiancamento) pesanti più veloce
* &lbrack;Help&rbrack; Correggi file registro di esportazione
* &lbrack;Content&rbrack; Il filtro casuale funziona su tutti i canali
* &lbrack;Content&rbrack; Il flusso di lavoro con più angoli prende in considerazione tutte le scansioni
* &lbrack;Content&rbrack; AO Fusione corretta
* &lbrack;Content&rbrack; Curvatura Fusione corretta fusione
* &lbrack;Content&rbrack; Color ID Fusione corretta fusione
* &lbrack;Content&rbrack; Custom Mask Blend corregge la fusione
* &lbrack;Content&rbrack; Correggi filtro di regolazione per modifica della rugosità
* &lbrack;Content&rbrack; Correggi filtro Materiale di base per il caricamento personalizzato dei canali normali
* &lbrack;Content&rbrack; Correggi pattern di importazione personalizzato del filtro Rilievo

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

### 1.1.0 (2019.1.0) Sesame

*(Rilasciato il 4 novembre 2019)*

**Aggiunto:**

* &lbrack;Project&rbrack; Creazione di un progetto
* &lbrack;Project&rbrack; Introduzione al formato di file .alch che contiene i dati del progetto
* &lbrack;Project&rbrack; Esporta un progetto .alch contenente le raccolte e i relativi materiali
* &lbrack;Project&rbrack; Importa un progetto .alch
* &lbrack;Project&rbrack; Apri progetti recenti
* &lbrack;Schermata introduttiva&rbrack; All&#39;avvio viene visualizzata una schermata di benvenuto
* &lbrack;Schermata introduttiva&brack; Crea un progetto dalla schermata introduttiva
* &lbrack;Schermata introduttiva&brack; Accedi all’elenco di tutti i tuoi progetti nella schermata introduttiva
* &lbrack;Schermata introduttiva&brack; Collegamenti rapidi per accedere alla documentazione, alla finestra a comparsa Informazioni sulla gestione licenze
* &lbrack;Menu File&rbrack; Integrazione di un menu file
* &lbrack;Menu File&rbrack; Accedi ai comandi del progetto dalla scheda File e salva il gruppo di livelli
* &lbrack;Menu File&rbrack; accedere ai comandi Annulla e Ripeti della scheda Modifica
* &lbrack;Menu File&rbrack; Il menu della Guida precedente è stato spostato nel menu File sotto la scheda Guida
* &lbrack;Layers&rbrack; Nuova architettura dello stack di livelli
* &lbrack;Layers&rbrack; Nuova interfaccia utente del gruppo di livelli
* &lbrack;Livelli&rbrack; Selezionare il metodo di fusione direttamente sulla barra degli strumenti
* &lbrack;Layers&rbrack; Accedi separatamente ai parametri di fusione e ai parametri del materiale
* &lbrack;Layers&rbrack; Aggiungi materiali direttamente negli input dedicati del filtro Spruzzo nella pila di livelli
* &lbrack;Layers&rbrack; Cambia l&#39;ordine di scansione direttamente nel livello di importazione dell&#39;immagine
* &lbrack;Viewport&rbrack; controllo del campo visivo della videocamera
* &lbrack;Riquadro di visualizzazione&rbrack; possibilità di passare da una fotocamera ortogonale a una prospettica
* &lbrack;Viewport&rbrack; visualizza le informazioni relative alla risoluzione e alle profondità di bit per ciascun canale
* &lbrack;Resources&rbrack; Materiali di base aperti per impostazione predefinita
* &blocco;Cache&rbrack; Individua la cartella della cache delle miniature
* &blocco;Cache&rbrack; Individua la cartella della cache di rendering
* &blocca;Panels&rbrack; il pannello Impostazioni materiale è temporaneamente nascosto
* &lbrack;Workflow&rbrack; Specular/lucidità temporaneamente disattivato
* &lbrack;MacOS&rbrack; versione del sistema operativo Catalina per l’autenticazione ufficiale
* &lbrack;Content&rbrack; Nuova versione del filtro Delighter
* &blocco;Content&brack; nuovo filtro Riempimento in base al contenuto dell&#39;immagine
* &blocco;Contenuto&rbrack; Nuovo filtro Riempimento in base al contenuto del materiale
* &lbrack;Content&rbrack; filtro di Trasforma con opzione Trasforma sicura

**Corretto:**

* Tutti i bug precedenti relativi a Crea non sono più validi con la nuova versione per interfaccia e architettura
* Le icone nella barra superiore (3D, 2D, 2D/3D) non vengono nascoste nelle descrizioni comandi
* &lbrack;Content&rbrack; Il filtro splatter accetta Atlas con mappa altezza completa
* &lbrack;Content&rbrack; Il filtro di Trasforma funziona sulle immagini (scan1, scan2,...)

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

## Beta

### Quinoa 0,8,1-beta

*(Rilasciato il 19 agosto 2019)*

**Aggiunto:**

* Possibilità di inviare risorse di Substance Source dal modulo di avvio a Project Substance Alchemist

**Corretto:**

* &lbrack;Create&rbrack; Alcuni filtri erano elencati nella funzione di accesso rapido ma non nel pannello dei filtri
* &lbrack;MacOS&rbrack; Corretti alcuni arresti anomali all&#39;uscita

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al height può bloccarsi su MacOS
* Può ancora verificarsi un arresto anomalo casuale quando si esce da MacOS

### Quinoa 0,8-beta

*(Rilasciato: 8 agosto 2019)*

**Aggiunto:**

* &blocca;Risorse&blocca; Collega e copia speculare le tue cartelle dei materiali sui dischi locali
* &lbrack;Resources&rbrack; Sfoglia le cartelle dei materiali e le relative sottocartelle
* &blocca;Risorse&blocca; scollega il pannello delle risorse materiali in una finestra separata per visualizzare le risorse a schermo intero
* &blocco;Risorse&rbrack; Nuovo layout del pannello Risorse per supportare la navigazione di cartelle e sottocartelle
* &lbrack;Resources&rbrack; Utilizza il breadcrum per spostarti tra le cartelle
* &lbrack;Resources&rbrack; Forza la sincronizzazione della cartella locale con l&#39;opzione Sincronizza accessibile facendo clic con il pulsante destro del mouse
* &lbrack;Resources&rbrack; Disconnetti la cartella locale con l&#39;opzione Disconnetti accessibile facendo clic con il pulsante destro del mouse
* &lbrack;Gestisci&rbrack; Visualizza i tag incorporati dei file Substance
* &lbrack;Gestisci&rbrack; Aggiungi, modifica ed elimina i tag dei materiali
* &lbrack;Gestisci&rbrack; Valuta i tuoi materiali
* &lbrack;Layers&rbrack; Supporta l&#39;output Panorama
* &lbrack;Layers&rbrack; Potete eliminare gli input dall&#39;immagine nel livello Importazione immagine
* &lbrack;Layers&rbrack; Selezione automatica del nuovo livello aggiunto
* &blocca;Livelli&rbrack; selezione automatica del livello sottostante dopo l&#39;eliminazione di un livello
* &lbrack;UX&rbrack; Mantiene la visibilità dei pannelli a sinistra quando si passa a un altro Lab
* &lbrack;UX&rbrack; Non creare un livello base o aprire il popup Flusso di lavoro materiale durante l&#39;importazione di immagini in una pila di livelli non vuota
* &lbrack;UI&rbrack; Nuovo stile per campi di testo
* &lbrack;UI&rbrack; nuovo stile SearchBox
* &lbrack;UI&rbrack; Nuovo stile intestazione pannello
* &lbrack;UI&rbrack; Nuovo stile indicatore Occupato
* &lbrack;UI&rbrack; Stile sfondo sovrapposizione nuovi livelli
* &lbrack;UI&rbrack; Usa font Adobe Clean
* &lbrack;UI&rbrack; Rimuovi segnaposto icona contagocce del parametro di input colore
* &lbrack;Performance&rbrack; Ottimizzazione indicatore attività
* &blocco;Content&rbrack; nuovo filtro Generatore pattern
* &lbrack;Content&rbrack; Nuovo filtro Sfocatura

**Corretto:**

* &lbrack;Inspire&rbrack; Correggi arresto anomalo quando si utilizzano più di 10 colori
* &lbrack;vista 2D&rbrack; Correggere la barra di scorrimento nell&#39;elenco dei canali del Vista 2D
* &lbrack;Viewer&rbrack; Correggere l&#39;arresto anomalo durante l&#39;importazione di una mappa dell&#39;ambiente senza alimentazione di 2
* &lbrack;Content&rbrack; Correggere l&#39;importazione PNG per il pattern personalizzato dei filtri Rilievo e Perforazione
* &lbrack;Esporta&rbrack; Correggi normale e height 16 bit per esportazione canale
* Correggi un ciclo infinito durante l&#39;importazione di un materiale con due predefiniti con lo stesso nome
* Correggere la visualizzazione del percorso lungo del file nel livello Materiale di base

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al height può essere arresto anomalo in MacOS
* È possibile eseguire l’arresto anomalo in modo casuale quando si esce da MacOS

### Pepe 0.7.0-beta

*(Rilasciato il 13 giugno 2019)*

**Aggiunto:**

* &lbrack;Filters&rbrack; Accedi rapidamente ai filtri premendo la barra spaziatrice
* &lbrack;Filters&rbrack; Nuovo pannello dedicato per gestire, sfogliare e importare i filtri
* &lbrack;Metadata&rbrack; fare clic con il pulsante destro del mouse su un materiale per visualizzarne i metadati
* &lbrack;Metadata&rbrack; fare clic con il pulsante destro del mouse su un materiale per visualizzarne la posizione sul disco
* &lbrack;Cursori&rbrack; anima i cursori quando li passi con il mouse premendo Ctrl
* &lbrack;Cursori&rbrack; interrompere e riavviare l&#39;animazione dei cursori premendo il tasto P
* &lbrack;Export&rbrack; L&#39;esportazione SBSAR è conforme alle linee guida Substance Source
* &lbrack;License&rbrack; Attiva Substance Alchemist utilizzando una variabile di ambiente
* &lbrack;UX&rbrack; La finestra di dialogo File ricorda l&#39;ultimo percorso file selezionato
* &lbrack;UX&rbrack; La finestra di dialogo Cartella ricorda l&#39;ultimo percorso cartella selezionato
* &lbrack;UI&rbrack; Aggiorna interfaccia utente del pannello Risorse
* &lbrack;UI&rbrack; Aggiorna interfaccia utente della barra di ricerca
* &lbrack;UI&rbrack; l&#39;icona Crea nuovo materiale è stata aggiornata
* &lbrack;Help&rbrack; Gli URL vengono aggiornati al dominio substance3d.com
* &lbrack;Mesh&brack; Ora è disponibile una trama in tessuto
* &lbrack;Content&rbrack; Nuovo filtro per la corrosione
* &lbrack;Content&rbrack; Nuovo filtro ossidazione
* &blocco;Contenuto&rbrack; Nuovo filtro Moss
* &lbrack;Content&rbrack; Nuovo filtro Dust
* &blocco;Contenuto&rbrack; Nuovo filtro pattern Brickwall
* &blocco;Contenuto&rbrack; Nuovo filtro pattern stonewall
* &lbrack;Content&rbrack; Nuovo filtro finitura legno
* &blocco;Content&rbrack; Nuovo filtro finitura metallica
* &lbrack;Content&rbrack; Nuovo filtro Snow
* &lbrack;Content&rbrack; Nuovo filtro casuale
* &lbrack;Content&rbrack; Ora puoi importare la texture direttamente nel filtro Materiale di base

**Corretto:**

* Correggere un arresto anomalo durante il salvataggio della Pila livelli
* È possibile aggiungere un valore superiore a 1 nel cursore di rotazione dell’ambiente
* Non perdere i parametri di fusione quando un livello di fusione viene Trasforma avanti e indietro dal livello di fusione al livello di materiale
* Correggere i duplicati quando si generano più volte variazioni della stessa Pila livelli
* Quando riapri un materiale, Alchemist memorizza gli intervalli modificati (min e max) dei cursori

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al height può essere arresto anomalo in MacOS

### 0,6,1-beta arancione

*(Rilasciato il 13 giugno 2019)*

**Aggiunto:**

* &lbrack;Engine&rbrack; Aggiornamento Substance Engine per compatibilità con la versione di Substance Designer più recente
* &lbrack;License&rbrack; Aggiorna la cartella delle licenze per le prime installazioni
* &lbrack;Layers&rbrack; Ricarica in qualsiasi momento la Pila livelli per aggiornare i filtri personalizzati

**Corretto:**

* &lbrack;Compatibilità dati&rbrack; correzione preventiva per limitare il danneggiamento dei dati al momento dell&#39;aggiornamento

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

### 0,6,0-beta arancione

*(Rilasciato il 18 aprile 2019)*

**Aggiunto:**

* &lbrack;Metadata&rbrack; visualizzare e riempire i metadati dei materiali in una scheda dedicata
* &lbrack;Collection&brack; Crea una raccolta direttamente dai risultati della ricerca
* &lbrack;Media Publishing&rbrack; Esportare una bacheca di una raccolta
* &lbrack;UX&rbrack; Annulla una modifica di modifica o un&#39;importazione di immagini premendo Ctrl+Z
* &lbrack;UX&rbrack; Ripeti una modifica di modifica o un&#39;importazione di immagini premendo Ctrl+Maiusc+Z
* &lbrack;UI&rbrack; nuove icone con un nuovo stile
* &lbrack;Prestazioni&rbrack; Nuovo gestore sessioni per gestire meglio il passaggio tra le schede
* &lbrack;Performance&rbrack; Apertura più rapida del livello Importazione immagine
* &lbrack;Content&rbrack; Nuovo materiale generico metallico
* &lbrack;Content&rbrack; Nuovo materiale Ruggine
* &lbrack;Content&rbrack; Nuovo materiale generico Pietra
* &blocco;Content&rbrack; aggiornamento filtro in rilievo
* &lbrack;Content&rbrack; aggiornamento del filtro Ricamo
* &lbrack;Content&rbrack; aggiornamento filtro Pittura
* &lbrack;Content&rbrack; aggiornamento del filtro Delighter

**Corretto:**

* &lbrack;Content&rbrack; Il filtro Acqua funziona nel flusso di lavoro Specular/Lucentezza
* Correggere il pulsante di scelta della scala di grigi nella finestra a comparsa dell’attivazione
* Accettare file contenenti caratteri coma
* Risolvere piccoli problemi di font nelle finestre a comparsa
* Correzione del problema dell’interfaccia utente di trasparenza a causa di un conflitto con il parametro FXAA di alcune schede NVIDIA
* Rimuovere il punto attivo del campo dopo aver inserito un valore in un cursore
* Assegnare la quantità minima di VRAM al delighter per ridurre gli arresti anomali
* Correggere il blocco della finestra durante il ridimensionamento della finestra dell’applicazione
* È stato corretto un arresto anomalo in cui la Pila livelli veniva eliminata durante la valutazione.

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter non è consigliato
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

### 0,5,4-beta Nacho

*(Rilasciato il 26 marzo 2019)*

**Corretto:**

* &lbrack;Stack&rbrack; Arresto anomalo durante la rimozione di un livello splatter
* &lbrack;Data&rbrack; Il database delle risorse viene danneggiato quando si verificano arresti anomali dell&#39;applicazione
* &lbrack;Data&rbrack;: impossibile avviare la Substance Alchemist se il database delle risorse è danneggiato
* Arresto anomalo casuale durante l&#39;importazione di materiali di Substance

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* La raccolta predefinita in cui salvare può essere vuota

### 0,5,3-beta Nacho

*(Rilasciato il 19 marzo 2019)*

**Aggiunto:**

* Ricerca per nome materiale nel pannello Risorse
* &lbrack;UI&rbrack; Clona /Clone la nuova interfaccia utente dello strumento con visualizzazione della dimensione del pennello
* &lbrack;UI&rbrack; Selezionare ed eliminare le fasi nascoste
* &lbrack;UI&rbrack; Nuova interfaccia utente dei campi di testo
* &lbrack;Help&rbrack; accesso ai siti Web delle accademie Substance Source, Substance share e Substance
* &lbrack;Content&rbrack; nuovi materiali predefiniti con generatori e atlas
* &lbrack;Content&rbrack; Aggiornamento da bitmap a materiale
* &lbrack;Content&rbrack; Aggiornamento Dirt
* &lbrack;Content&rbrack; Aggiornamento Ruggine
* &blocco;Content&rbrack; nuovo filtro in rilievo
* &blocco;Content&rbrack; nuovo filtro Ricamo
* &blocco;Content&rbrack; Nuovo Filtro Erosione
* &lbrack;Content&rbrack; Nuovo generatore di ghiaia
* &lbrack;Content&rbrack; Nuovo filtro Pittura
* &blocco;Contenuto&rbrack; Nuovo filtro Pattern parquet
* &lbrack;Content&rbrack; nuovo filtro Pattern pavimentazione
* &blocco;Content&rbrack; Nuovo filtro Perforazione
* &lbrack;Content&rbrack; Nuovo filtro splatter
* &lbrack;Content&rbrack; Nuovo filtro usura tessile
* &lbrack;Content&rbrack; Nuovo filtro di Trasforma

**Corretto:**

* &lbrack;Viewport&rbrack; mesh sfera con Affiancamento x2 su X
* &lbrack;Viewport&rbrack; Arresto anomalo durante il caricamento del proprio ambiente
* &lbrack;Viewport&rbrack; nella mappa ambiente viene ora utilizzato anche il valore di esposizione
* &lbrack;Viewport&rbrack; F scelta rapida da tastiera non reimposta l&#39;angolo della fotocamera
* &lbrack;Export&rbrack; L&#39;esportazione SBS funziona con l&#39;ultimo Substance Designer 2018.3.3
* &lbrack;Export&rbrack; L&#39;esportazione SBSAR rispetta le stesse linee guida dei materiali di Substance Source
* &lbrack;UI&rbrack; le barre di scorrimento possono essere trascinate
* Caratteri speciali supportati nei percorsi di cartella e file
* La miniatura viene rigenerata durante il salvataggio del materiale

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* L’importazione di ambienti personalizzati può diventare nera
* Le immagini TIF non vengono visualizzate nel pannello Proprietà nel livello di importazione delle immagini
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* La raccolta predefinita in cui salvare può essere vuota

### 0,5,2-beta Nacho

*(Rilasciato il 7 marzo 2019)*

**Aggiunto:**

* Rilevamento e utilizzo della GPU di alto profilo

**Corretto:**

* Il parametro Rotazione dispone di un widget del cursore appropriato
* Correggere la visibilità della linea di colore blu quando si trascinano e rilasciano materiali
* Correggere la fusione dei materiali quando si rilascia un materiale sotto il primo livello
* L’input dell’immagine può essere collegato solo se non è stato impostato un percorso personalizzato

**Problemi noti:**

* I caratteri speciali nel percorso del file impediscono il salvataggio di un materiale
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* Arresto anomalo durante il caricamento del proprio ambiente

### 0,5,1-beta Nacho

*(Rilasciato il 4 marzo 2019)*

**Corretto:**

* Risolvi i problemi relativi a report di Arresti anomali, segnalazioni di bug e licenze nelle finestre a comparsa

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* Arresto anomalo durante il caricamento del proprio ambiente

### 0.5.0-beta Nacho

*(Rilasciato il 28 febbraio 2019)*

**Aggiunto:**

* &lbrack;Pila livelli&rbrack; riordinamento dei livelli
* &lbrack;Pila livelli&rbrack; Eliminare un livello nascosto
* &lbrack;Pila livelli&rbrack; Importa un materiale direttamente nella posizione desiderata
* &lbrack;Pila livelli&rbrack; input di materiale come nuovo tipo di parametro del filtro
* &lbrack;Performance&rbrack; Il budget delle Substance Engine è dinamico per prestazioni migliori
* &lbrack;Performance&rbrack; Migliori prestazioni OpenGL, in particolare su MacOS
* &lbrack;Data&rbrack; Aggiornamento dei dati più rapido dopo il rilascio di una nuova versione
* &lbrack;Content&rbrack; AI Delighter disponibile su Windows 7 e Windows 8
* &lbrack;Content&rbrack; AI Delighter disponibile su GPU RTX

**Corretto:**

* Correggere possibili arresti anomali all’uscita dall’applicazione
* L’esportazione della finestra a comparsa si apre più rapidamente durante l’esportazione di raccolte di grandi dimensioni

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* Arresto anomalo durante il caricamento del proprio ambiente

### Muffin 0.4.0-beta

*(Rilasciato il 17 gennaio 2019)*

**Aggiunto:**

* &lbrack;Export&rbrack; Substance archive (sbsar) export of your collection
* &lbrack;Esporta&rbrack; esportazione di file di Substance (sbs) della raccolta
* &lbrack;Export&rbrack; coda di esportazione visibile nel pannello Esporta
* &lbrack;Esporta&rbrack; assegna un nome alla raccolta o al materiale prima dell&#39;esportazione
* &lbrack;Data&rbrack; Salva come materiale premendo Ctrl+Maiusc+S
* &lbrack;Data&rbrack; Salva il materiale premendo Ctrl+S
* &lbrack;Data&rbrack; le raccolte e i materiali sono compatibili tra le versioni
* &lbrack;Data&rbrack; Aggiorna la Pila livelli del materiale con filtri aggiornati
* &lbrack;Data&rbrack; Ricaricamento a caldo dei filtri personalizzati importati
* &lbrack;UI&rbrack; Feedback visivo nella finestra della vista durante l&#39;elaborazione
* &lbrack;UI&rbrack; Nuovo stile pulsante
* &lbrack;UI&rbrack; nel menu a comparsa Salva viene visualizzato il nome della raccolta attiva
* &lbrack;UI&rbrack; modifica le immagini sorgente di un livello di importazione immagini
* &lbrack;Content&rbrack; Gli usi personalizzati sono ora supportati
* &lbrack;Content&rbrack; nei parametri di input dell&#39;immagine sono supportati altri formati di immagini
* &lbrack;Content&rbrack; Nuovo filtro di Affiancamento denominato Make It Tile Advanced
* &lbrack;Content&rbrack; aggiornamento del filtro Acqua

**Corretto:**

* Bitmap su materiale gestisce il flusso di lavoro Specular/Lucentezza

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* Delighter non è supportato sulla scheda GPU RTX
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni

### 0.3.1-beta Lasagne

*(Rilasciato il 17 dicembre 2018)*

**Corretto:**

* Generare una variazione di colore con 10 arresti anomali estratti di colore
* Generare una variazione di colore con arresti anomali di Pila livelli appena salvati
* Collegamenti errati nella finestra a comparsa per l’aggiornamento della versione di Substance Alchemist

**Problemi noti:**

* Da Bitmap a materiale non gestisce il flusso di lavoro Specular/rugosità
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni

### Lasagne 0.3.0-beta

*(Rilasciato il 12 dicembre 2018)*

**Aggiunto:**

* &blocco;Esporta&rbrack; finestra a comparsa Nuova esportazione
* &lbrack;Esporta&rbrack; Esporta un&#39;intera raccolta
* &lbrack;Esporta&rbrack; Esporta bitmap nel formato desiderato
* &lbrack;Esporta&rbrack; Esporta bitmap alla risoluzione desiderata
* &lbrack;Export&rbrack; Esporta solo i canali desiderati
* &lbrack;Esporta&rbrack; Visualizza in anteprima la stima delle dimensioni dell&#39;esportazione
* &lbrack;Esporta&rbrack; visualizza in anteprima le dimensioni disponibili sul disco prima dell&#39;esportazione
* &lbrack;UX&rbrack; Azioni sulla raccolta accessibili utilizzando il pulsante destro del mouse
* &lbrack;UX&rbrack; Consenti di disimpostare un&#39;immagine o una risorsa in Inspire
* &lbrack;UX&rbrack; Substance Alchemist avviata ingrandita
* &lbrack;Risorse&rbrack; Nuovo modo di salvare i materiali per mantenerli persistenti con le versioni successive
* &lbrack;Help&rbrack; Accesso alla documentazione in linea tramite il menu?
* &lbrack;Performance&rbrack; Variazioni di colore più rapide per materiali complessi creati con Substance Alchemist
* &lbrack;Prestazioni&rbrack; Riduci le perdite di memoria quando si cambia laboratorio
* &lbrack;Content&rbrack; Controllo scala per diagnosticare la dimensioni fisiche del materiale
* &lbrack;Content&rbrack; Aggiorna il materiale delle piastrelle del mosaico italiano di Venezia
* &lbrack;Content&rbrack; Aggiorna splatter Moss

**Corretto:**

* Non è più disponibile il nome predefinito quando si salva un materiale
* I parametri dei filtri vengono persi dopo aver salvato un materiale e riaperto la Substance Alchemist
* &lbrack;Content&rbrack; Correggi dalla logica inferiore e superiore per AO e fusione curvatura

**Problemi noti:**

* I materiali creati con una versione precedente non saranno disponibili nella nuova versione.
* Da Bitmap a materiale non gestisce il flusso di lavoro Specular/rugosità
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni

### Kiwi 0,2-beta

*(Rilasciato il 9 novembre 2018)*

**Aggiunto:**

* Le impostazioni del visualizzatore vengono salvate da una sessione all’altra
* Le impostazioni dei materiali vengono salvate da una sessione all’altra
* Caricamento rapido del pannello Proprietà
* &lbrack;Log&rbrack; Esporta il file di registro tramite il menu Aiuto
* &blocco;UI&rbrack;Nuovo stile cursori
* &blocco;UI&rbrack;I pannelli Predefiniti e Tweak sono uniti
* &blocco;UI&rbrack;Nuovo stile miniature
* Impostazioni di Spostamento, Affiancamento e Ombre accessibili direttamente nella finestra della vista
* &lbrack;Content&rbrack; Nuovi materiali predefiniti
* &lbrack;Content&rbrack; aggiornamento Moss Splatter
* &lbrack;Framework&rbrack; Aggiorna Substance Engine Framework

**Corretto:**

* L’eliminazione della versione di Pila livelli tramite il cambio di laboratorio è stata corretta
* I valori di tempo di caricamento visualizzati nella finestra della vista sono corretti
* I canali predefiniti del flusso di lavoro dei materiali sono inizializzati correttamente
* Disattiva importazione trama personalizzata
* Esportazione bitmap
* &lbrack;MacOS&rbrack; La Substance Alchemist di chiusura può richiedere un &quot;Forza all&#39;uscita&quot;

**Problemi noti:**

* I materiali creati con una versione precedente non saranno disponibili nella nuova versione.
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni

### 0.1.1-beta Marmellata

*(Rilasciato il 24 ottobre 2018)*

**Aggiunto:**

* BaseColor Delighter è ora disponibile
* Accedere alle informazioni sulla Substance Alchemist dal menu Aiuto
* Ricevi una notifica quando è disponibile una nuova versione di Substance Alchemist
* La console non è più visibile su Windows
* Nuovo stile miniature
* &lbrack;MacOS&rbrack; La Substance Alchemist può essere impostata a schermo intero
* &lbrack;Filter&rbrack; Importa maschera personalizzata per gestire la fusione tra due materiali
* &lbrack;Filter&rbrack; Control Moss scale
* &lbrack;Filter&rbrack; Clona /Clone aggiornamento patch

**Corretto:**

* Aggiungere un’immagine in un input di immagine nell’elenco dei parametri e aggiornare gli output
* Il filtro Importa personalizzato non aggiunge un’Occlusione ambientale nera né un’opacità nera

**Problemi noti:**

* I materiali creati con una versione precedente non saranno disponibili nella nuova versione.
* &lbrack;MacOS&rbrack; La Substance Alchemist di chiusura può richiedere un &quot;Forza all&#39;uscita&quot;
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* L&#39;interruttore di visibilità rapida di uno stadio Delighter influirà sulle prestazioni
* L&#39;esportazione dei materiali può arresto anomalo

### IceCream 0.1.0-beta

*(Rilasciato il 17 ottobre 2018)*

**Aggiunto:**

* Fusione materiale con 4 tipi di fusione (Fusione Height, Fusione campione, Fusione curvatura, Fusione AO)
* Introduzione del meccanismo di memorizzazione nella cache per ottimizzare i ricalcoli Pila livelli
* Selezione automatica di un materiale in Inspire se presente nella finestra della vista
* Formato normale centralizzato nel pannello Impostazioni materiale
* Controlli per ritaglio e Affiancamento dei widget (-90xB0,+90xB0, make square,...) pulizia
* Nuovo filtro Snow

**Corretto:**

* Pulizia dell’interfaccia utente del pannello
* Sfarfallio della finestra della vista durante il ridimensionamento di finestre e pannelli
* Pila livelli non ricalcolata al momento del salvataggio
* La denominazione delle risorse nell&#39;interfaccia utilizza etichette invece dei nomi dei grafici

**Problemi noti:**

* Allungamento la grafica cambiando rapidamente la visibilità del livello
* La messa a fuoco ripristina l&#39;angolazione della videocamera
