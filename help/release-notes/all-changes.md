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

* &amp;lbrack;Assets&amp;rbrack; Controllare la versione secondaria e avvisare gli utenti se il motore è troppo vecchio per leggerlo
* &amp;lbrack;Captis&amp;rbrack; Aggiungi di nuovo opzione per salvare la fotometria dei sottotitoli nelle preferenze

**Corretto:**

* &amp;lbrack;vista 2D&amp;rbrack; Non &#39;visualizzare con proporzioni fisiche&#39; se la dimensioni fisiche è disattivata
* &amp;lbrack;Analytics&amp;rbrack; eventi di analisi mancanti
* &amp;lbrack;Analytics&amp;rbrack; Impedisci che il blocco anomalo segnali un arresto anomalo su vk devicelost
* &amp;lbrack;Application&amp;rbrack; Non distruggere i vkdevices all&#39;uscita per evitare un arresto anomalo nel driver nvidia
* &amp;lbrack;Application&amp;rbrack; Correggi uscita controllo raccolta collegata + gestione canali
* &amp;lbrack;Application&amp;rbrack; Impedisci arresto anomalo all&#39;uscita
* &amp;lbrack;Content&amp;rbrack; Il filtro &quot;finitura metallo&quot; non influisce sulla metallizzazione
* &amp;lbrack;Content&amp;rbrack; Aggiungi dimensioni fisiche ai filtri dinamici dove manca
* &amp;blocco;Filtri&amp;rbrack; Rimuovi riempimento in base al contenuto dall&#39;elenco delle risorse nascoste
* &amp;blocca;Livelli&amp;rbrack; se si fa clic su &quot;Reimposta tutte le impostazioni&quot; non viene reimpostato il menu a discesa &quot;Applica a&quot;
* &amp;lbrack;Livelli&amp;rbrack; Correggere le modifiche minime e massime per il widget posizione
* &amp;lbrack;Layers&amp;rbrack; aggiorna correttamente il filtro
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; verifica che la scala fisica funzioni ovunque + verifica che la dimensione fisica sia corretta con i filtri dinamici
* &amp;lbrack;Project&amp;rbrack; Verifica che la risoluzione delle risorse sia quella predefinita (2k x 2k) durante la creazione di una nuova risorsa
* &amp;lbrack;Project&amp;rbrack; riapertura del progetto corrente utilizzato per aprire la versione precedente
* &amp;lbrack;Project&amp;rbrack; Sampler non offre più di ripristinare un backup dei progetti danneggiati
* &amp;lbrack;Rendering&amp;rbrack; Esegui il rendering della miniatura del materiale a una risoluzione massima di 2k
* &amp;lbrack;UI&amp;rbrack; codice difensivo per evitare l&#39;arresto anomalo se l&#39;utente è più veloce dell&#39;interfaccia utente

### **6.0.1**

*(Rilasciato: 21 maggio 2026)*

**Aggiunto:**

* &amp;lbrack;Application&amp;rbrack; Avvisa l’utente quando apre un progetto con oggetti o luce ambientale 3D
* &amp;lbrack;Captis&amp;rbrack; Adatta l&#39;interfaccia utente a schermi di piccole dimensioni
* &amp;lbrack;Captis&amp;rbrack; Aggiorna interfaccia utente Captis
* &amp;lbrack;Impostazioni canale&amp;rbrack; Attiva automaticamente SSS quando si utilizza il canale SSS in ASM
* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine alla versione 9.4.3
* &amp;lbrack;Preset&amp;rbrack; Attiva per impostazione predefinita &quot;Applica valori miniature predefinite&quot;
* &amp;lbrack;Resources&amp;rbrack; Visualizza &quot;tutte le librerie&quot; per impostazione predefinita anziché &quot;risorse iniziali&quot; nel pannello delle risorse
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi funzioni Python per gestire &quot;Applicato a&quot; di un livello
* &amp;lbrack;UI&amp;rbrack; L&#39;elenco delle risorse è ora reattivo: le dimensioni delle risorse si adattano al contenitore
* &amp;lbrack;UI&amp;rbrack; Visualizza 3D/Vista 2D per impostazione predefinita
* &amp;lbrack;UI&amp;rbrack; Visualizza il popup di ottimizzazione del materiale quando si rilascia un materiale da Esplora risorse
* &amp;lbrack;UI&amp;rbrack; descrizione comando Attiva capovolgimento pulsanti barra del dispositivo

**Corretto:**

* &amp;lbrack;Applicazione&amp;rbrack; Correggi problemi di spazio colore
* &amp;lbrack;Application&amp;rbrack; Correggi aggiornamento impostazioni
* &amp;lbrack;Applicazione&amp;rbrack; Attiva i canali di scansione quando sono impostati su automatico
* &amp;lbrack;Application&amp;rbrack; il pulsante Nuovo progetto della schermata Home non cancella più il progetto precedente con lo stesso nome
* &amp;lbrack;Application&amp;rbrack; Impedisce l&#39;arresto anomalo all&#39;uscita da macOS
* &amp;lbrack;Application&amp;rbrack; Impedisci l&#39;accesso alla risorsa con riferimenti a risorsa non validi
* &amp;lbrack;Application&amp;rbrack; Impedisce l&#39;arresto anomalo durante l&#39;accesso a surface da VersionedImage in un tweak
* &amp;lbrack;Application&amp;rbrack; Impedisce l&#39;arresto anomalo quando si elimina uno stage quando non è presente
* &amp;lbrack;Captis&amp;rbrack; Verifica che Captis sia disconnesso prima di chiudere Sampler
* &amp;lbrack;Captis&amp;rbrack; Impedisce la visualizzazione due volte dell&#39;avviso USB-2
* &amp;lbrack;Impostazioni canale&amp;rbrack; Correggere i nomi dei canali OpenPBR
* &amp;lbrack;Impostazioni canale&amp;rbrack; aggiornamento delle etichette lunghe per i canali di OpenPBR
* &amp;lbrack;Content&amp;rbrack; Aggiorna tutte le unità di mesh dai metri ai centimetri per i valori SSS
* &amp;lbrack;Export&amp;rbrack; Assicurarsi che i valori predefiniti siano collegati ai filtri dinamici
* &amp;lbrack;Esporta&amp;rbrack; Le immagini sono ora salvate in un thread di lavoro per migliorare le prestazioni
* &amp;lbrack;Filters&amp;rbrack; Riempimento in base al contenuto si arresta in modo anomalo quando si attiva il ridimensionamento
* &amp;lbrack;Filters&amp;rbrack; Impossibile aprire la posizione di un filtro dinamico dal pannello delle risorse
* &amp;lbrack;Filters&amp;rbrack; Fix reset all in AutoTiling, passaggio di regolazione
* &amp;lbrack;Filters&amp;rbrack; Ripristina disabilita elaborazione dell&#39;utilizzo nella creazione di strutture ad albero
* &amp;lbrack;Filters&amp;rbrack; Imposta il valore predefinito corretto per il parametro upscale
* &amp;lbrack;Filters&amp;rbrack; Aggiorna i generatori anche se si trovano in un livello di riempimento
* &amp;blocca;Livelli&amp;rbrack; impedisce la ridenominazione dei livelli di input intestazione o segnaposto
* &amp;lbrack;Layers&amp;rbrack; Impedisce l&#39;arresto anomalo durante l&#39;inserimento del livello a causa di un puntatore oscillante
* &amp;lbrack;Layers&amp;rbrack; Numero errato di immagini nel nome del livello unito
* &amp;lbrack;Localization&amp;rbrack; verificare che i nomi predefiniti siano aggiornati quando si cambia lingua
* &amp;lbrack;Localization&amp;rbrack; Problemi di traduzione multipli nel pannello delle risorse
* &amp;lbrack;Localization&amp;rbrack; Azioni rapide categorie problemi di localizzazione
* &amp;lbrack;Prestazioni&amp;rbrack; Carica modifiche solo nella sezione aperta
* &amp;lbrack;Preferenze&amp;rbrack; Cancellazione del percorso della cache delle preferenze ripristina il valore precedente
* &amp;lbrack;Rendering&amp;rbrack; Perdita di memoria quando si utilizza Tracciatore percorso
* &amp;lbrack;Rendering&amp;rbrack; Impedisci l&#39;eliminazione di texture finché possono ancora essere accessibili da Vulkan
* &amp;lbrack;Rendering&amp;rbrack; La rotazione della texture non è stata convertita da 0-1 a 0-360
* &amp;lbrack;Scripting&amp;rbrack; Rimuovi classi inesistenti dalla documentazione Python
* &amp;lbrack;Scripting&amp;rbrack; selectedAsset restituisce None se non è presente alcuna risorsa selezionata
* &amp;lbrack;Strumenti&amp;rbrack; La reimpostazione di un valore di texture ora interrompe il disegno e cancella la visualizzazione delle patch
* &amp;lbrack;UI&amp;rbrack; Non chiudere le sezioni nel pannello delle proprietà ogni volta che viene modificato qualcosa
* &amp;lbrack;UI&amp;rbrack; etichetta di modifica colore visibile invisibile al passaggio del mouse
* &amp;lbrack;UI&amp;rbrack; Correggere il comportamento reattivo dell&#39;elenco risorse
* &amp;lbrack;UI&amp;rbrack; Correggi ciclo di associazione nella descrizione comando di AssetItem
* &amp;lbrack;UI&amp;rbrack; Correggere il doppio clic sul gruppo di predefiniti selezionato
* &amp;lbrack;UI&amp;rbrack; Correggi area di rilascio nel presentatore immagini
* &amp;lbrack;UI&amp;rbrack; Correggi etichetta con un pulsante per tutte le lingue
* &amp;lbrack;UI&amp;rbrack; Correggi height di righe per giapponese nel popup dell&#39;elenco canali
* &amp;lbrack;UI&amp;rbrack; Correggere il campo del segnale di lunghezza accettato
* &amp;lbrack;UI&amp;rbrack; Correggi la larghezza del popup con l&#39;elemento di controllo lungo a sinistra
* &amp;lbrack;UI&amp;rbrack; Correggi popup anteprima in elementi risorsa
* &amp;lbrack;UI&amp;rbrack; Correggi selettore irregolare/riflessivo
* &amp;lbrack;UI&amp;rbrack; Correggi puntini di sospensione stringa
* &amp;lbrack;UI&amp;rbrack; risolvere il problema di troncamento della stringa
* &amp;lbrack;UI&amp;rbrack; Correggi interruttore pulsante di reimpostazione
* &amp;lbrack;UI&amp;rbrack; Nasconde il menu a discesa Modello di materiale quando è selezionato un predefinito di esportazione personalizzato
* &amp;lbrack;UI&amp;rbrack; Rimuovi la risoluzione nell&#39;elenco dei canali del popup di esportazione
* &amp;lbrack;UI&amp;rbrack; reimposta il layout predefinito mantiene le impostazioni del visualizzatore proiezione
* &amp;lbrack;UI&amp;rbrack; Ripristinare le voci di menu &quot;Modifica in Photoshop&quot; e &quot;Modifica in Illustrator&quot;

**Rimosso:**

* &amp;lbrack;UI&amp;rbrack; Rimuovi la sezione &quot;Applicato a&quot; per i livelli di importazione delle immagini
* &amp;lbrack;UI&amp;rbrack; Rimuovi descrizione comando di apertura automatica al primo avvio

## Versione 5

### **5.1.3 ÎLE FLOTTANTE**

*(Rilasciato: 6 gennaio 2026)*

**Aggiunto:**

* &amp;lbrack;Captis&amp;rbrack; Visualizza un avviso se il protocollo FTP è disattivato dal firewall

**Corretto:**

* &amp;lbrack;Captis&amp;rbrack; L&#39;interruzione durante un&#39;acquisizione può causare errori
* &amp;lbrack;Captis&amp;rbrack; Il download dei risultati alla fine di un&#39;acquisizione utilizza molta RAM
* &amp;lbrack;Captis&amp;rbrack; L&#39;esecuzione di un&#39;attivazione automatica subito dopo un&#39;intensità automatica può causare errori
* &amp;lbrack;Captis&amp;rbrack; La visualizzazione dei risultati HDR nel pannello Riepilogo
* &amp;lbrack;UI&amp;rbrack; In alcuni casi, la finestra di dialogo delle cartelle in MacOS non seleziona la cartella corretta

### **5.1.2 ÎLE FLOTTANTE**

*(Rilasciato: 20 novembre 2025)*

**Aggiunto:**

* &amp;lbrack;Application&amp;rbrack; Rileva la perdita del dispositivo grafico, avvisa l&#39;utente ed esci correttamente
* &amp;lbrack;Layers&amp;rbrack; Messaggistica migliorata durante la conversione dei livelli
* &amp;lbrack;Layers&amp;rbrack; miniature migliorate per i livelli di importazione delle immagini e livelli con unico livello
* &amp;lbrack;Onboarding&amp;brack; contenuti di apprendimento aggiornati nella schermata Home
* &amp;lbrack;Project&amp;rbrack; Recupera l&#39;ultimo stato salvato della sessione prima dell&#39;arresto anomalo
* &amp;lbrack;UI&amp;rbrack; aggiornamento icona applicazione

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; se si inserisce un materiale nella Pila livelli, potrebbe verificarsi un arresto anomalo in macOS
* &amp;lbrack;Application&amp;rbrack; Possibile arresto anomalo su carichi pesanti in macOS
* &amp;lbrack;Application&amp;rbrack; Possibile arresto anomalo durante l&#39;aggiunta di livelli quando la memoria video è piena
* &amp;lbrack;Application&amp;rbrack; Possibile arresto anomalo durante l&#39;apertura di un progetto
* &amp;lbrack;Captis&amp;rbrack; errore se la messa a fuoco automatica viene eseguita poco dopo la calibrazione automatica dell&#39;intensità
* &amp;lbrack;Captis&amp;rbrack; problemi di affidabilità e prestazioni dopo la prima acquisizione
* &amp;lbrack;Captis&amp;rbrack; rallentamenti ed errori durante la copia dei file al termine di un&#39;acquisizione
* &amp;lbrack;Captis&amp;rbrack; Piccola perdita di memoria durante la ricerca delle informazioni sul dispositivo Captis
* &amp;lbrack;Export&amp;rbrack; I parametri esposti dal cursore multiplo producono file .sbsar danneggiati
* &amp;lbrack;Layers&amp;rbrack; Il pattern di suddivisione automatica viene reimpostato sui valori predefiniti quando si cambia risorsa
* &amp;lbrack;Layers&amp;rbrack; Il colore di base personalizzato predefinito viene visualizzato in rosso
* &amp;lbrack;Layers&amp;rbrack; è possibile la conversione parziale dei livelli secondari di Timbro clone che causa problemi di rendering
* &amp;lbrack;Layers&amp;rbrack; Possibile arresto anomalo quando si modifica una pila di livelli mentre è in corso il rendering
* &amp;lbrack;Layers&amp;rbrack; errore imprevisto nel passaggio di area di interesse automatica dell&#39;Affiancamento quando si modificano i canali sorgente
* &amp;lbrack;Project&amp;rbrack; Miniatura errata a volte durante la creazione di un nuovo materiale
* &amp;lbrack;Azioni rapide&amp;brack; Alcune azioni rapide hanno un conteggio di input errato
* &amp;lbrack;UI&amp;rbrack; Il pulsante del gruppo di azioni ha larghezze diverse
* &amp;lbrack;UI&amp;rbrack; Cancella nei campi di testo a volte attiva la perdita dello stato attivo
* &amp;blocco;UI&amp;rbrack; le caselle combinate e i campi di testo sono troppo grandi
* &amp;lbrack;UI&amp;rbrack; icone ed etichette non allineate
* &amp;lbrack;UI&amp;rbrack; L&#39;etichetta del campo Nome è posizionata in modo errato
* &amp;lbrack;UI&amp;rbrack; le etichette dei pulsanti Azioni rapide non sono allineate
* &amp;lbrack;UI&amp;rbrack; i cursori mostrano troppi 0s finali

**Rimosso:**

* &amp;lbrack;Generative AI&amp;brack; rimozione delle funzionalità di intelligenza artificiale generativa. *Questa funzionalità è stata rimossa dall&#39;applicazione e il servizio smetterà di funzionare nelle versioni precedenti di Sampler il 5 marzo.*

### **5.1.1 ÎLE FLOTTANTE**

*(Rilasciato: 18 settembre 2025)*

**Aggiunto:**

* &amp;lbrack;2D View&amp;rbrack; Consente di ridurre ulteriormente la visualizzazione 2D per le texture ad alta risoluzione
* &amp;lbrack;Captis&amp;rbrack; Avvisa gli utenti in caso di problemi durante la copia dei file
* &amp;lbrack;Layers&amp;rbrack; Durante la duplicazione di un livello, utilizza un numero incrementale nel nuovo nome del livello

**Corretto:**

* &amp;lbrack;2D View&amp;rbrack; Quando si colorano i tratti dopo aver reimpostato tutte le proprietà di Timbro clone, i tratti creati in precedenza vengono nuovamente visualizzati
* &amp;lbrack;Application&amp;rbrack; &quot;Salvare il progetto corrente?&quot; il popup utilizza un nome di progetto errato
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; potenziale arresto anomalo
* &amp;lbrack;Application&amp;rbrack; A volte, viene generata una miniatura con un materiale errato
* &amp;lbrack;Captis&amp;rbrack; Su alcuni dispositivi, quando si esegue una scansione in alta risoluzione, la mappa del height è nera
* &amp;lbrack;Captis&amp;rbrack; Il pulsante &quot;Avvia acquisizione&quot; non è più disattivato quando non è impostato alcun nome di acquisizione e quando è in esecuzione una calibrazione
* &amp;lbrack;Export&amp;rbrack; Quando si esporta un file .sbsar, l&#39;esportazione può non riuscire senza che l&#39;utente riceva una notifica
* &amp;lbrack;Filters&amp;rbrack; Advanced parameters screen for the Auto Tiling filter a volte sfarfalla durante l&#39;ottimizzazione dei parametri
* &amp;lbrack;Filters&amp;rbrack; I parametri predefiniti per il filtro Divisione in porzioni generano artefatti grigi nell&#39;output
* &amp;lbrack;Filters&amp;rbrack; A volte con input ad alta risoluzione, le impostazioni avanzate del filtro Porzione automatica non mostrano i singoli punti del pattern
* &amp;lbrack;Filters&amp;rbrack; La dimensione del pattern per il parametro di dimensione personalizzata Auto Tiling ha un valore predefinito errato
* &amp;lbrack;Layers&amp;rbrack; problema di colore occasionale con il filtro Porzione automatica visibile per lo più sui materiali rossi
* &amp;lbrack;Livelli&amp;rbrack; a volte l’aggiunta di livelli reimposta alcune modifiche sul valore predefinito
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; La miniatura delle risorse con una dimensioni fisiche ha una scala di height errata
* &amp;lbrack;UI&amp;rbrack; Impossibile rinominare i parametri esposti
* &amp;lbrack;UI&amp;rbrack; Il pulsante di attivazione del canale non è quadrato
* &amp;lbrack;UI&amp;rbrack; Se un&#39;etichetta del cursore è troppo lunga, il pulsante di reimpostazione non è accessibile
* &amp;lbrack;UI&amp;rbrack; se si preme il tasto Invio o si fa clic fuori, lo stato attivo non viene rimosso dai campi di testo
* &amp;lbrack;UI&amp;rbrack; a volte nel pannello Dimensioni fisiche compare una descrizione comandi indesiderata
* &amp;lbrack;UI&amp;rbrack; La vista 3D visualizza una trama errata durante la creazione di un progetto vuoto
* &amp;lbrack;UI&amp;rbrack; Quando si espone un input del selettore colore, la relativa etichetta scompare al passaggio del mouse
* &amp;lbrack;UI&amp;rbrack; Quando si espongono i parametri, il punto colore a volte è posizionato in modo errato

### **5.1.0 ÎLE FLOTTANTE**

*(Rilasciato: 7 agosto 2025)*

**Aggiunto:**

* &amp;lbrack;vista 2D&amp;rbrack; La dimensione del pennello ora si adatta alla risoluzione della texture corrente
* &amp;lbrack;vista 3D&amp;rbrack; Attiva/disattiva la scala di visualizzazione nativa per il rendering 3D nelle preferenze
* &amp;lbrack;Application&amp;rbrack; aggiornamento del motore di rendering
* &amp;lbrack;Captis&amp;rbrack; Aggiungi la possibilità di &quot;creare quadrati&quot; durante l&#39;anteprima
* &amp;lbrack;Captis&amp;rbrack; Rilevamento automatico dimensioni fisiche
* &amp;lbrack;Captis&amp;rbrack; L&#39;acquisizione di un nuovo materiale creerà una nuova risorsa
* &amp;lbrack;Captis&amp;rbrack; Cambia la selezione della risoluzione nel menu a discesa in pixel per pollice o centimetro invece della risoluzione pixel dell&#39;area massima
* &amp;lbrack;Captis&amp;rbrack; Guida contestuale alla calibrazione dell&#39;allineamento
* &amp;lbrack;Captis&amp;rbrack; Genera mappa di rugosità
* &amp;lbrack;Captis&amp;rbrack; Avvisa l&#39;utente se mancano i file di calibrazione predefiniti
* &amp;lbrack;Filters&amp;rbrack; Filtro di Affiancamento automatico per scansioni e materiali strutturati
* &amp;blocco;Filtri&amp;rbrack; Nuovo filtro rimozione piegatura
* &amp;lbrack;Filters&amp;rbrack; Nuove funzioni all&#39;interno del filtro Clona /Clone timbro
* &amp;blocco;Filtri&amp;rbrack; Nuove funzioni all&#39;interno del filtro Equalizza
* &amp;lbrack;Layers&amp;rbrack; Possibilità di convertire i livelli
* &amp;blocca;Livelli&amp;rbrack; menu di scelta rapida quando si fa clic con il pulsante destro del mouse su un livello per rinominarlo, duplicarlo, eliminarlo o convertirlo
* &amp;blocco;Onboarding&amp;brack; contenuto per il completamento dell&#39;aggiornamento e Novità delle schermate
* &amp;lbrack;Prestazioni&amp;rbrack; Prestazioni migliori quando si utilizza il filtro Ritaglio
* &amp;lbrack;Performance&amp;rbrack; Migliorare l&#39;utilizzo della memoria per la vista 3D
* &amp;lbrack;Performance&amp;rbrack; l&#39;aggiornamento della vista 3D è più rapido
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; abilita &quot;visualizzazione con proporzioni fisiche&quot; quando si lavora sui filtri Substance quando Dimensioni fisiche è abilitata
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Quando si importano immagini in una pila vuota, proporre una risoluzione più coerente con le proporzioni dell&#39;immagine
* &amp;lbrack;Azioni rapide&amp;rbrack; 3 nuove azioni rapide per l&#39;elaborazione della scansione
* &amp;lbrack;Scripting&amp;rbrack; API per convertire i livelli
* &amp;lbrack;Scripting&amp;rbrack; Ottieni il nome file di ogni immagine di un livello di importazione immagine
* &amp;lbrack;Scripting&amp;rbrack; Nuova funzione per attivare/disattivare un determinato canale di una risorsa
* &amp;lbrack;UI&amp;rbrack; Icone e pulsanti di rielaborazione nel pannello Livelli per adattarsi alle nuove funzioni
* &amp;lbrack;UI&amp;rbrack; Avvisa in caso di deprecato authoring luce ambiente

**Corretto:**

* &amp;lbrack;2D View&amp;rbrack; La selezione di &#39;display with physical ratio&#39; potrebbe non funzionare quando si utilizzano i filtri Substance
* &amp;lbrack;capture 3D&amp;rbrack; I file Svg sono elencati nel selettore di file ma non sono supportati
* &amp;lbrack;3D View&amp;rbrack; Il parametro relativo all&#39;intensità di emissione nelle impostazioni dello shader non funziona
* &amp;lbrack;vista 3D&amp;rbrack; A volte la posizione della trama non è corretta durante la creazione di una nuova risorsa
* &amp;lbrack;3D View&amp;rbrack; Il passaggio al rendering Traccia percorso si arresta in modo anomalo su hardware non supportato
* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione si blocca quando si chiude il popup della misura manuale senza impostare una dimensione
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo
* &amp;blocco;Applicazione&amp;blocco; Blocco in Windows durante la visualizzazione del desktop (tasto Windows + scelta rapida da tastiera D)
* &amp;lbrack;Application&amp;rbrack; Possibile arresto anomalo quando si cambia lingua
* &amp;lbrack;Captis&amp;rbrack; Arresto anomalo quando i dati di anteprima non sono validi
* &amp;lbrack;Captis&amp;rbrack; impossibile ridurre completamente dopo aver eseguito lo zoom avanti
* &amp;lbrack;Captis&amp;rbrack; Localizzazione mancante in alcuni passaggi della procedura guidata
* &amp;lbrack;Captis&amp;rbrack; Possibile arresto anomalo all&#39;uscita quando si utilizza Captis
* &amp;lbrack;Captis&amp;rbrack; La scansione non funziona se nel dispositivo mancano i file di calibrazione
* &amp;lbrack;Filters&amp;rbrack; L’anteprima del pennello quando si utilizza il filtro Timbro Clona /Clone potrebbe non essere corretta a seconda delle dimensioni della texture e del pennello
* &amp;lbrack;Filters&amp;rbrack; dimensioni di output errate dopo l&#39;utilizzo del filtro Ingrandisci
* &amp;lbrack;Filters&amp;rbrack; Icone mancanti per i filtri Rotazione e Stilizzazione dell&#39;ambiente
* &amp;lbrack;Filters&amp;rbrack; L&#39;aggiornamento di alcuni filtri può causare un rendering errato
* &amp;lbrack;Livelli&amp;rbrack; primo rendering non corretto durante la fusione di due materiali
* &amp;lbrack;Layers&amp;rbrack; Il pulsante per aggiornare i livelli mostra &quot;Aggiorna tutto&quot; anche quando è presente un solo aggiornamento
* &amp;lbrack;Layers&amp;rbrack; calcoli non necessari durante l&#39;importazione di immagini nella Pila livelli
* &amp;lbrack;Prestazioni&amp;rbrack; Migliorare la gestione del formato mappa normale per ridurre i tempi di rendering
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Il popup di misurazione manuale funziona solo dopo l&#39;esecuzione di una misurazione automatica
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Risoluzione di esportazione errata nel popup Esporta quando la Dimensioni fisiche è abilitata
* &amp;lbrack;Azioni rapide&amp;rbrack; Localizzazione mancante nei nomi delle risorse generate
* &amp;lbrack;UI&amp;rbrack; l&#39;anteprima della risorsa al passaggio del mouse potrebbe non essere visualizzata
* &amp;lbrack;UI&amp;rbrack; Se si fa clic sul pulsante Ripristina valore predefinito è possibile che alcuni dei controlli vengano interrotti
* &amp;lbrack;UI&amp;rbrack; I messaggi di errore non vengono cancellati quando si cambia progetto
* &amp;lbrack;UI&amp;rbrack; verifica che il nome del materiale nella finestra della vista e nel pannello Proprietà sia vuoto quando non è presente alcuna risorsa
* &amp;lbrack;UI&amp;rbrack; Il pulsante Ripristina valore predefinito per il parametro Punto di vista non funziona
* &amp;lbrack;UI&amp;rbrack; Pulsante Ripristina valore predefinito sovrapposto
* &amp;blocca;Interfaccia&amp;rbrack; Alcuni pulsanti non sono selezionabili quando un pannello è disancorato
* &amp;lbrack;UI&amp;rbrack; Texture parametro V di fatturazione parzialmente nascosto in Impostazioni e vista 3D visualizzatore

**Rimosso:**

* &amp;lbrack;capture 3D&amp;rbrack; Rimuovi supporto capture 3D
* &amp;lbrack;Application&amp;rbrack; Rimuovi supporto macOS x86

### **5.0.3 NOCCIOLA**

*(Rilasciato: 3 giugno 2025)*

**Aggiunto:**

* &amp;lbrack;Captis&amp;rbrack; Consenti di assegnare a un materiale lo stesso nome di un materiale già esistente
* &amp;lbrack;Captis&amp;rbrack; Sposta i messaggi di errore in popup anziché in popup
* &amp;lbrack;Filters&amp;rbrack; Aggiorna il ricamo
* &amp;lbrack;Preferenze&amp;rbrack; Aggiungi reimpostazione nelle impostazioni del visualizzatore e degli ombreggiatori
* &amp;lbrack;UI&amp;rbrack; Non presentare la voce di menu &quot;Mostra percorso&quot; nelle risorse del progetto

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Il filtro post-elaborazione Trama non genera le mappe previste
* &amp;lbrack;vista 3D&amp;rbrack; la vista 3D non funziona a causa del danneggiamento della cache di shader
* &amp;lbrack;vista 3D&amp;rbrack; il piano e la griglia del terreno sono verticali quando la scena è Z-up
* &amp;lbrack;vista 3D&amp;rbrack; La trama a volte scompare
* &amp;lbrack;Application&amp;rbrack; La chiusura della finestra di accesso all&#39;avvio senza effettuare l&#39;accesso a volte arresto anomalo l&#39;app
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando l&#39;accesso al file di configurazione dei plug-in viene negato
* &amp;lbrack;Applicazione&amp;rbrack; il materiale corrente non è selezionato quando si salva il progetto
* &amp;lbrack;Application&amp;rbrack; Ripristinando il layout predefinito, la risoluzione viene impostata su 64x64
* &amp;lbrack;Application&amp;rbrack; Sampler a volte arresto anomalo durante il rendering di una Pila livelli
* &amp;lbrack;Export&amp;rbrack; La risoluzione dell&#39;esportazione è talvolta reimpostata su 64x64
* &amp;lbrack;Export&amp;rbrack; a volte non è possibile esportare i file .sbs/.sbsar
* &amp;lbrack;Layers&amp;rbrack; Il pulsante Aggiungi materiale di base non esegue alcuna operazione quando il materiale è vuoto
* &amp;lbrack;Layers&amp;rbrack; L&#39;Affiancamento della Texture viene modificato durante la duplicazione di un materiale
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Misura automatica non funziona se il pannello Dimensioni fisiche è stato ancorato prima di importare l&#39;immagine
* &amp;lbrack;Scripting&amp;rbrack; Il plug-in di salvataggio automatico è interrotto
* &amp;lbrack;UI&amp;rbrack; spaziatura errata nella finestra di dialogo Esporta
* &amp;lbrack;UI&amp;rbrack; L&#39;animazione del cursore delle modifiche non funziona più
* &amp;lbrack;UI&amp;rbrack; I cursori non si allineano a valori interi quando necessario
* &amp;lbrack;UI&amp;rbrack; Alcuni menu a discesa sono ritagliati

### **5.0.2 NOCCIOLA**

*(Rilasciato: 22 aprile 2025)*

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; Il pulsante Indietro nella pagina principale è interrotto
* &amp;lbrack;Application&amp;rbrack; Sampler a volte non si avvia se sul disco sono presenti dati danneggiati da versioni precedenti
* &amp;lbrack;Application&amp;rbrack; L&#39;immagine importata non viene visualizzata nella finestra della vista o nella pila di livelli
* &amp;lbrack;Captis&amp;rbrack; Il campo indirizzo IP Captis rimane vuoto anche dopo il riavvio di Sampler
* &amp;lbrack;Captis&amp;rbrack; L&#39;anteprima della videocamera dal vivo funziona solo quando la lingua dell&#39;applicazione è impostata su Inglese
* &amp;lbrack;Esporta&amp;rbrack; Arresto anomalo durante l&#39;esportazione &amp;lbrack;Livelli&amp;rbrack; Il disegno a volte non funziona nei progetti salvati in precedenza
* &amp;lbrack;Layers&amp;rbrack; Sampler a volte aggiorna tutte le texture quando viene aggiornato un solo canale
* &amp;lbrack;Layers&amp;rbrack; Impossibile utilizzare fusioni di materiale nella pila di livelli dopo l&#39;aggiornamento a 5.0.x
* &amp;lbrack;Layers&amp;rbrack; L&#39;aggiornamento di un progetto con una versione precedente di Image to Material (AI) rende tutto il materiale nero
* &amp;lbrack;Livelli&amp;rbrack; Quando si tenta di importare un&#39;immagine non supportata, Sampler crea un livello interrotto
* &amp;lbrack;Scripting&amp;rbrack; Parte dell’API Python non funziona con un progetto vuoto
* &amp;lbrack;UI&amp;rbrack; Le voci di menu a volte si sovrappongono nel menu File

### **5.0.1 NOCCIOLA**

*(Rilasciato: 20 marzo 2025)*

**Aggiunto**

* &amp;lbrack;Application&amp;rbrack; Elenco di compatibilità dei driver di grafica aggiornato
* &amp;lbrack;Captis&amp;rbrack; Visualizza un popup quando l&#39;utilizzo di HP Z Captis viene bloccato dai criteri del sistema operativo
* &amp;lbrack;Azioni rapide&amp;rbrack; Spiegare il motivo per cui un&#39;azione rapida è disattivata in una descrizione comandi
* &amp;lbrack;UI&amp;rbrack; stile interfaccia utente della finestra del report di arresto anomalo
* &amp;lbrack;UI&amp;rbrack; durante la copia negli Appunti, mostra un avviso popup per indicare che è stato completato

**Corretto:**

* &amp;lbrack;2D View&amp;rbrack; Il cursore Esposizione non ha effetto quando la proiezione sferica è disattivata
* &amp;lbrack;2D View&amp;rbrack; Se si esegue un disegno all&#39;esterno della texture, viene creato un tratto interrotto
* &amp;lbrack;2D View&amp;rbrack; Il pulsante Esposizione non contiene alcun suggerimento.
* &amp;lbrack;2D View&amp;rbrack; Lo zoom sul lato di un&#39;immagine non quadrata non segue il mouse
* &amp;lbrack;capture 3D&amp;rbrack; non funziona su Windows 11 24H2
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo se si esce da Sampler durante la fase di ricostruzione della trama
* &amp;lbrack;3D View&amp;rbrack; Il tempo di calcolo viene talvolta visualizzato come 0 ms
* &amp;lbrack;3D View&amp;rbrack; Quando si cambia proiezione da ortogonale a prospettica, la finestra della vista diventa grigia
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;avvio durante il controllo delle funzionalità GPU
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante l&#39;installazione
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita dopo aver fatto clic con il pulsante destro del mouse su un campo metadati
* &amp;lbrack;Application&amp;rbrack; luce ambiente mancante all&#39;apertura di un SBSAR da Esplora file del sistema operativo
* &amp;lbrack;Application&amp;rbrack; Se si apre un file .sbsar mentre Sampler è in esecuzione, viene modificata l&#39;impostazione Texture Tiling
* &amp;lbrack;Captis&amp;rbrack; Alcuni metadati potrebbero non essere trasferiti tra i passaggi di acquisizione
* &amp;lbrack;Captis&amp;rbrack; Il nome della risorsa creata non è quello immesso nel campo dei metadati
* &amp;lbrack;Content&amp;rbrack; Il progetto di esempio richiede un aggiornamento del filtro, ma è già aggiornato
* &amp;lbrack;Filters&amp;rbrack; Il filtro di regolazione Normale/height non ha icona
* &amp;lbrack;Livelli&amp;rbrack; Impossibile modificare le immagini in un livello di importazione immagine
* &amp;lbrack;Layers&amp;rbrack; Si arresta in modo anomalo quando si utilizza il filtro Ingrandisci
* &amp;lbrack;Livelli&amp;rbrack; l&#39;aggiornamento di un progetto con una vecchia immagine in materiale rende tutto il materiale nero
* &amp;lbrack;Rendering&amp;rbrack; l’ottimizzazione di una pila di livelli immediatamente dopo la creazione di una risorsa interrompe il rendering
* &amp;lbrack;Scripting&amp;rbrack; Il plug-in di salvataggio automatico si arresta in modo anomalo quando non è presente alcuna risorsa nel progetto
* &amp;lbrack;Strumenti&amp;rbrack; Il valore della dimensione del pennello non è presente nella barra degli strumenti Pennello
* &amp;lbrack;UI&amp;rbrack; La modifica della lingua dell&#39;applicazione non aggiorna alcune delle etichette nella schermata iniziale
* &amp;lbrack;UI&amp;rbrack; toccando i campi di testo Esc o Invio in Slider non perderà lo stato attivo
* &amp;lbrack;UI&amp;rbrack; Nel pannello Proprietà, il pulsante Reimposta tutto e l&#39;etichetta del nome della risorsa si sovrappongono
* &amp;lbrack;UI&amp;rbrack; Problemi durante l&#39;ancoraggio e disancoraggio dei pannelli
* &amp;lbrack;UI&amp;rbrack; Lo scorrimento in un pannello in sovrapposizione scorre anche nella finestra sottostante
* &amp;lbrack;UI&amp;rbrack; Il passaggio alla visualizzazione Elenco nella sezione Progetti recenti della schermata Home non funziona
* &amp;lbrack;UI&amp;rbrack; l&#39;icona del pulsante della modalità di visualizzazione del riquadro di visualizzazione mostra sempre 2D/3D

### **5.0.0 NOCCIOLA**

*(Rilasciato: 20 febbraio 2025)*

**Aggiunto**

* &amp;lbrack;Onboarding&amp;rbrack; nuova home page con accesso rapido a contenuti di apprendimento, progetti di esempio, azioni rapide e progetti recenti.
* &amp;lbrack;Onboarding&amp;brack; Inizia rapidamente con le nuove Azioni rapide, accessibili dalla pagina principale e dal pannello dedicato
* &amp;lbrack;Onboarding&amp;rbrack; &amp;lbrack;Content&amp;rbrack; Le azioni rapide sono flussi di lavoro predefiniti che popolano la pila di livelli con la maggior parte dei livelli utilizzati
* &amp;lbrack;Onboarding&amp;rbrack; possibilità di creare un nuovo progetto tramite un nuovo menu di avvio rapido, tramite azioni rapide o Progetto personalizzato
* &amp;lbrack;Onboarding&amp;rbrack; possibilità di creare un progetto vuoto direttamente dalla home page tramite il pulsante dedicato
* &amp;lbrack;vista 3D&amp;rbrack; nuovo rasterizzatore avanzato e tracciatore percorsi con nuove funzionalità di rendering (proprietà quali rivestimento, lucentezza, traslucidità, dispersione sottosuperficie) e coerenza visiva nell&#39;ecosistema Substance
* &amp;lbrack;3D View&amp;rbrack; Le impostazioni del visualizzatore sono ora accessibili direttamente nella vista 3D
* &amp;lbrack;3D View&amp;rbrack; Possibilità di salvare un&#39;istantanea di rendering negli Appunti o nei file
* &amp;lbrack;3D View&amp;rbrack; Visualizza una griglia per visualizzare l&#39;origine della scena
* &amp;lbrack;3D View&amp;rbrack; Attiva il piano terreno per catturare ombre e riflessi
* &amp;lbrack;3D View&amp;rbrack; controlla la visibilità e l&#39;opacità del piano terreno
* &amp;lbrack;capture 3D&amp;rbrack; Posiziona trama a terra
* &amp;lbrack;Application&amp;rbrack; Verifica la compatibilità hardware all&#39;avvio dell&#39;applicazione
* &amp;lbrack;Application&amp;rbrack; La finestra di segnalazione degli arresti anomali ora si apre subito dopo l&#39;arresto anomalo
* &amp;lbrack;Content&amp;rbrack; Apri un progetto di esempio per iniziare facilmente
* &amp;lbrack;Esporta&amp;rbrack; Esporta lo shader Adobe Standard Material nei file USD
* &amp;lbrack;Generative AI&amp;brack; Selezionare &quot;Non dedurre&quot; tag quando si utilizza un&#39;immagine come input nei flussi di lavoro da immagine a texture
* &amp;lbrack;Project&amp;rbrack; le miniature vengono memorizzate nel file di progetto per velocizzare l&#39;apertura dei progetti
* &amp;lbrack;Progetto&amp;rbrack; Impostazione nelle preferenze per memorizzare i dati della cache all&#39;interno del file di progetto, con modalità diverse (nessuna cache, cache leggera, cache completa)
* &amp;lbrack;Scripting&amp;rbrack; &amp;lbrack;Breaking change&amp;rbrack; migrazione Qt a Qt6.15 - impatto sulla compatibilità dei plug-in esistenti
* &amp;lbrack;Scripting&amp;rbrack; I plug-in predefiniti e la cartella degli script si trovano ora nella cartella Documenti
* &amp;lbrack;Scripting&amp;rbrack; Nuova interfaccia utente per i plug-in per coerenza visiva con i pannelli principali di Sampler
* &amp;lbrack;Scripting&amp;rbrack; Esempi di plug-in di Access 2 per scoprire le funzionalità dei plug-in di Sampler
* &amp;lbrack;Scripting&amp;rbrack; Nuova funzione open_3d_catpure()
* &amp;lbrack;Scripting&amp;rbrack; Quando si inserisce un livello, controllare se è inserito sopra o sotto la posizione di destinazione

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo se non è possibile avviare Acquisizione oggetti in macOS
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;blocco;Applicazione&amp;blocco; Blocco all&#39;uscita durante l&#39;aggiunta delle risorse al pannello Progetto
* &amp;lbrack;Applicazione&amp;rbrack; La ridenominazione di una risorsa di progetto non funziona a meno che non si prema invio
* &amp;lbrack;Application&amp;rbrack; Le voci di menu Annulla e Ripeti non sono disattivate quando dovrebbero essere
* &amp;lbrack;Assets&amp;rbrack; impossibile eliminare le risorse dalla sezione Tutte le librerie del pannello Risorse
* &amp;lbrack;Content&amp;rbrack; creatore di Atlas: usa mappa di opacità esistente se presente
* &amp;lbrack;Content&amp;rbrack; Color ID Blend - Correggi selezione colore nel colore di base
* &amp;lbrack;Layers&amp;rbrack; evita calcoli inutili quando si utilizzano i generatori
* &amp;lbrack;Livelli&amp;rbrack; la modifica di un generatore può causare l&#39;attivazione di troppi calcoli
* &amp;lbrack;Prestazioni&amp;rbrack; Miglioramento della gestione della memoria GPU
* &amp;lbrack;Performance&amp;brack; Impossibile utilizzare la cache di rendering al riavvio dell&#39;app
* &amp;lbrack;Resources&amp;rbrack; I file di sola lettura non sono visibili nel pannello Risorse
* &amp;blocco;Scripting&amp;rbrack; Consenti di riutilizzare un livello dopo aver aggiunto un altro livello
* &amp;lbrack;Scripting&amp;rbrack; La modifica ripetuta della struttura della pila di livelli in uno script potrebbe non riuscire

**Rimosso:**

* &amp;lbrack;Application&amp;rbrack; Rimuovi il supporto per i file di immagine .dng e .nef

## Versione 4

### **4.5.2 GRUYERE**

*(Rilasciato il 7 novembre 2024)*

**Corretto:**

* &amp;lbrack;Content&amp;rbrack; filtri di fusione Ritaglia, Ricamo e Height

### **4.5.1 GRUYERE**

*(Rilasciato il 30 luglio 2024)*

**Corretto:**

* &amp;lbrack;Livelli&amp;rbrack; il disegno delle maschere in scala di grigi non funziona, con effetti su strumenti come Timbro Clona /Clone, Alterazione Pittura, Riempimento in base al contenuto

### **4.5.0 GRUYERE**

*(Rilasciato il 18 luglio 2024)*

**Aggiunto**

* &amp;lbrack;Interoperability&amp;rbrack; Invia materiali a UE5, Blender, Maya, 3DsMax Unity
* &amp;lbrack;Content&amp;rbrack; Nuova categoria generatore texture - Sfumature
* &amp;lbrack;Content&amp;rbrack; Strumenti HDRI - nuovo filtro di rotazione Ambiente

**Corretto:**

* &amp;lbrack;Exposed Parameters&amp;rbrack; L&#39;esposizione dei valori di input .sbsar non funziona
* &amp;lbrack;Livelli&amp;rbrack; il Colore di base diventa rosso con immagini in scala di grigi
* &amp;lbrack;Rendering&amp;rbrack; le immagini in scala di grigi utilizzate nei canali di colore hanno uno spazio cromatico errato
* &amp;lbrack;Scripting&amp;rbrack; L’uso di un predefinito di esportazione a volte non esporta i canali previsti
* &amp;lbrack;Content&amp;rbrack; Dirt: se si applica un filtro Dirt sopra Immagine al materiale, viene generata una normale nera
* &amp;lbrack;Content&amp;rbrack; Effetto rilievo: il ridimensionamento di un pattern nel filtro effetto rilievo non è lineare tra 0 e 1
* &amp;lbrack;Content&amp;rbrack; Crea porzioni - Maggiore coerenza tra height e normale

### **4.4.1 FONDUE**

*(Rilasciato il 6 giugno 2024)*

**Corretto:**

* &amp;lbrack;Content&amp;rbrack; filtro Dirt mancante
* &amp;lbrack;Generative AI&amp;rbrack; Talvolta si verificano errori di rete quando si utilizza Image to Texture

### **4.4.0 FONDUE**

*(Rilasciato il 23 maggio 2024)*

**Aggiunto:**

* &amp;lbrack;Application&amp;rbrack; capture 3D Cache è ora memorizzata in una sottocartella separata
* &amp;lbrack;Generative AI&amp;rbrack; Immagine da Texture (Beta)
* &amp;lbrack;Generative AI&amp;brack; Text to Pattern (Beta)
* &amp;lbrack;Generative AI&amp;rbrack; Text to Texture (Beta)
* &amp;lbrack;Scripting&amp;rbrack; Le risorse ora hanno una proprietà &#39;resource&#39;
* &amp;lbrack;Scripting&amp;rbrack; I livelli ora hanno una proprietà &#39;output_usages&#39;

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante l&#39;apertura di un file di progetto danneggiato
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando il progetto contiene risorse danneggiate
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si scollega un monitor su Windows
* &amp;lbrack;Application&amp;rbrack; icona di applicazione non corretta nella barra delle applicazioni di Windows
* &amp;lbrack;Application&amp;rbrack; il danneggiamento del file di configurazione principale può provocare l&#39;eliminazione dei file
* &amp;blocco;Applicazione&amp;rbrack; I pannelli vengono visualizzati davanti ai popup
* &amp;lbrack;Content&amp;rbrack; i generatori di Texture hanno miniature sfocate
* &amp;lbrack;Export&amp;rbrack; Il canale di opacità generato da un&#39;immagine importata si interrompe durante l&#39;esportazione di un file .sbs/.sbsar
* &amp;lbrack;Filters&amp;rbrack; L&#39;arresto anomalo di Ingrandisci dipende dai relativi livelli di input
* &amp;lbrack;Generative AI&amp;rbrack; Possibili arresti anomali durante la ricezione di risultati imprevisti dal servizio
* &amp;lbrack;Scripting&amp;rbrack; Arresto anomalo durante il caricamento automatico di un plug-in dalla variabile di ambiente
* &amp;lbrack;Scripting&amp;rbrack; possibile arresto anomalo durante l’assegnazione dell’utilizzo dell’output con l’API

### **4.3.3 EMPANADA**

*(Rilasciato il 26 marzo 2024)*

**Aggiunto:**

* &amp;lbrack;capture 3D&amp;rbrack; nuovi parametri avanzati auto-UV durante la fase di post-elaborazione
* &amp;lbrack;Filters&amp;rbrack; Perforate filter: possibilità di invertire e modificare le dimensioni del pattern personalizzato

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Il colore di base può non essere corretto in macOS
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo durante l&#39;elaborazione di una nuova versione
* &amp;lbrack;capture 3D&amp;rbrack; il passaggio post-elaborazione può arrestarsi in modo anomalo in macOS
* &amp;lbrack;capture 3D&amp;rbrack; Il livello Trasformazione trama può causare un rendering errato
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;avvio di Sampler mentre è ancora in corso l&#39;esportazione di un&#39;istanza precedente
* &amp;lbrack;Application&amp;rbrack; Sampler non risponde per un momento quando viene avviato per la prima volta
* &amp;lbrack;Esporta&amp;rbrack; mappa angolo di Anisotropia non esportata
* &amp;lbrack;Filters&amp;rbrack; L&#39;aggiunta di Tessuto alla pila di livelli può causare un arresto anomalo
* &amp;lbrack;Filtri&amp;rbrack; l&#39;aggiunta di rilievo alla pila di livelli può causare un arresto anomalo
* &amp;lbrack;Filters&amp;rbrack; arresti anomali di riempimento in base al contenuto quando si utilizzano immagini a 32 bit
* &amp;blocco;Filtri&amp;rbrack; Rilievo: l’opacità dei livelli sottostanti non viene completamente ignorata
* &amp;lbrack;Filters&amp;rbrack; Fill: il metodo di fusione non funziona in Designer e Painter
* &amp;lbrack;Filters&amp;rbrack; Ricamo: selezione colore automatica interrotta
* &amp;lbrack;Preferenze&amp;rbrack; Impedisce di impostare un percorso non supportato per capture 3D Cache
* &amp;lbrack;Preferenze&amp;rbrack; La preferenza Formato normale non funziona
* &amp;lbrack;Scripting&amp;rbrack; I parametri dei canali di Asset.export_material fanno distinzione tra maiuscole e minuscole

### **4.3.2 EMPANADA**

*(Rilasciato il 22 febbraio 2024)*

**Corretto:**

* &amp;lbrack;Applicazione&amp;rbrack; Il salvataggio di un progetto in una condivisione di rete in Windows danneggia il file di progetto

### **4.3.1 EMPANADA**

*(Rilasciato il 15 febbraio 2024)*

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo quando i file di immagine diventano inaccessibili durante la generazione in batch delle maschere
* &amp;lbrack;Esporta&amp;rbrack; l&#39;esportazione di un materiale con Ritaglio o relativo al livello dei criteri di input restituisce risultati non validi
* &amp;lbrack;Layers&amp;rbrack; arresto anomalo raro durante il rendering di una Pila livelli
* &amp;lbrack;Filters&amp;rbrack; Ricamo - Risolvere il problema quando si utilizza l&#39;input di materiale su MacOS
* &amp;lbrack;Filters&amp;rbrack; Stylization - Support Texture Generators
* &amp;lbrack;Filters&amp;rbrack; Pattern - Correggi denominazione parametri
* &amp;lbrack;Localization&amp;rbrack; &quot;Salva con nome...&quot; nella finestra delle informazioni sull&#39;hardware, sotto il menu?, viene visualizzato unlocalized

### **4.3.0 EMPANADA**

*(Rilasciato il 25 gennaio 2024)*

**Aggiunto**

* &amp;lbrack;Assets&amp;rbrack; Nuovo tipo di risorsa: Generatori di Texture
* &amp;lbrack;Risorse&amp;rbrack; Nuovi materiali inclusi in Risorse per iniziare
* &amp;lbrack;Assets&amp;rbrack; Nuovo selettore di risorse per i parametri dell&#39;immagine nel pannello Proprietà
* &amp;lbrack;Assets&amp;rbrack; Trascina i generatori di Texture dal pannello Risorse ai selettori di immagini nel pannello Proprietà
* &amp;lbrack;Assets&amp;rbrack; Trascina e rilascia i generatori di Texture da Esplora file del sistema operativo
* &amp;lbrack;Assets&amp;rbrack; I filtri possono suggerire l&#39;adattamento dei generatori tramite un tag utente sull&#39;input dell&#39;immagine
* &amp;lbrack;Assets&amp;rbrack; I generatori di Texture possono definire il filtro da utilizzare come suggerimento tramite un tag utente
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Prospettiva ritaglio
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro di stilizzazione
* &amp;lbrack;Content&amp;rbrack; Metodo fusione su filtro riempimento
* &amp;lbrack;Content&amp;rbrack; Filtro ricamo aggiornato
* &amp;lbrack;Content&amp;rbrack; Filtro Contorna con disegno aggiornato
* &amp;lbrack;Content&amp;rbrack; Tutti i filtri sono stati aggiornati per supportare i generatori di texture
* &amp;lbrack;Layers&amp;rbrack; Possibilità di scegliere un canale di output del generatore di texture quando lo si aggiunge alla pila di livelli
* &amp;lbrack;Layers&amp;rbrack; Possibilità di elencare e applicare facilmente i predefiniti sui generatori di texture
* &amp;lbrack;Livelli&amp;rbrack; Visualizza un&#39;anteprima di Generatore texture nei selettori di immagini
* &amp;lbrack;Livelli&amp;rbrack; I parametri del generatore di texture possono essere esposti ed esportati
* &amp;lbrack;Livelli&amp;rbrack; Assegna l’uso del colore di base quando si importa una singola immagine con il modello di creazione Importazione texture
* &amp;lbrack;Layers&amp;rbrack; Feedback quando si tenta di trascinare e rilasciare file incompatibili nei selettori di immagini nel pannello Proprietà
* &amp;lbrack;Layers&amp;rbrack; Genera un canale di opacità dal canale alfa di un’immagine importata
* &amp;lbrack;Layers&amp;rbrack; Image to Material (AI) è più veloce da calcolare quando si cambia categoria
* &amp;lbrack;Livelli&amp;rbrack; Seleziona il livello più pertinente dopo l&#39;utilizzo di un modello di creazione
* &amp;lbrack;Layers&amp;rbrack; I widget di posizione ora possono essere modificati con un cursore nel gruppo Advanced Parameters
* &amp;lbrack;Esporta&amp;rbrack; Visualizza una percentuale nella coda anziché i numeri non elaborati
* &amp;lbrack;Interoperabilità&amp;rbrack; Il canale di opacità viene ora riconosciuto come canale alfa quando si invia a Painter
* &amp;lbrack;Applicazione&amp;rbrack; Nuova finestra di dialogo per visualizzare e salvare le informazioni sull&#39;hardware
* &amp;lbrack;Application&amp;rbrack; Nuova preferenza per modificare la scala di height predefinita per ogni progetto
* &amp;lbrack;Applicazione&amp;rbrack; Migliora la modalità di visualizzazione delle risorse obsolete
* &amp;lbrack;Scripting&amp;rbrack; Nuove funzioni asset.documentResolution() e asset.setDocumentResolution()
* &amp;lbrack;Scripting&amp;rbrack; Nuova funzione select_asset()
* &amp;lbrack;Scripting&amp;rbrack; Python API for Texture Generators
* &amp;lbrack;Scripting&amp;rbrack; get_project_assets() ora restituisce oggetti 3D
* &amp;lbrack;UI&amp;rbrack; La dimensione della miniatura della risorsa può essere modificata nel pannello Risorse
* &amp;lbrack;UI&amp;rbrack; icone di visualizzazione della finestra di visualizzazione aggiornate

**Corretto:**

* &amp;lbrack;vista 2D&amp;rbrack; Lo zoom con la rotellina del mouse è bloccato al 244%
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;avvio durante l&#39;inizializzazione dell&#39;API grafica
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo se il nome del progetto contiene il carattere #
* &amp;lbrack;Application&amp;rbrack; Possibile arresto anomalo durante l&#39;apertura di un vecchio progetto
* &amp;lbrack;Application&amp;rbrack; La riapertura del progetto corrente può generare un arresto anomalo
* &amp;lbrack;Application&amp;rbrack; Alcune modifiche al progetto non vengono registrate e vengono perse senza preavviso alla chiusura del progetto se non vengono salvate
* &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar problemi di esportazione quando si utilizzano più file con lo stesso nome
* &amp;lbrack;Export&amp;rbrack; Spazio cromatico errato per il file .sbs/.sbsar delle immagini in scala di grigio esportate
* &amp;blocco;Filtri&amp;rbrack; problemi di comportamento della fusione Opacità
* &amp;lbrack;Livelli&amp;rbrack; a volte i file .svg non vengono riprodotti alla risoluzione corretta
* &amp;lbrack;Performance&amp;brack; Alcuni salvataggi di progetto su disco non sono necessari
* &amp;lbrack;Project&amp;rbrack; L&#39;importazione di un vecchio progetto non carica i predefiniti associati
* &amp;lbrack;Scripting&amp;rbrack; impossibile ottenere i parametri del primo livello inserito
* &amp;lbrack;UI&amp;rbrack; Il popup di anteprima quando si passa con il mouse su una risorsa può apparire nella posizione o nella schermata errata
* &amp;lbrack;UI&amp;rbrack; i pannelli non ancorati sono visibili e utilizzabili nella parte superiore della schermata di benvenuto

### **4.2.2 DORAYAKI**

*(Rilasciato il 5 dicembre 2023)*

**Aggiunto:**

* &amp;lbrack;capture 3D&amp;rbrack; è ora dal 5% al 10% più veloce in Windows
* &amp;lbrack;capture 3D&amp;rbrack; migliora la pulizia della trama prima della decimazione
* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine alla versione 9.0.3
* &amp;lbrack;Layers&amp;rbrack; Riempimento in base al contenuto: aggiornamento a monte, varie correzioni di casi d&#39;uso e supporto di Linux

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Se si fa clic su &quot;Indietro&quot; dopo l&#39;allineamento e poi su &quot;Avanti&quot;, la nuvola di punti non viene aggiornata
* &amp;lbrack;capture 3D&amp;rbrack; Trama visualizzata con fori dopo essere stata aggiunta al progetto
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si esce dalla modalità a schermo intero dopo un Capture 3D
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo con file di immagine creati
* &amp;lbrack;Applicazione&amp;rbrack; Se in &quot;Tutte le librerie&quot; quando si esce da Sampler, il pannello Risorse diventa vuoto al riavvio
* &amp;lbrack;Application&amp;rbrack; Perdita di memoria durante l&#39;esportazione del materiale
* &amp;lbrack;Application&amp;rbrack; se si apre un progetto con versioni precedenti di Sampler, può verificarsi un arresto anomalo
* &amp;lbrack;Application&amp;rbrack; arresti anomali potenziali quando non si convertono le trame 3D
* &amp;lbrack;Application&amp;rbrack; arresto anomalo invisibile all&#39;apertura di un file .sbsar durante l&#39;esecuzione di Sampler
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;esportazione di un file .sbs/.sbsar con un utilizzo personalizzato
* &amp;lbrack;Export&amp;rbrack; La mappa normale esportata è sempre DirectX, indipendentemente dalle impostazioni dell&#39;utente
* &amp;lbrack;Export&amp;rbrack; L’esportazione di un oggetto 3D in un file FBX su macos non funziona
* &amp;lbrack;Export&amp;rbrack; Incongruenze durante l&#39;esportazione di una Pila livelli con un filtro Ricamo come file .sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; A volte l&#39;esportazione dei file .sbs/.sbsar non funziona
* &amp;lbrack;Export&amp;rbrack; A volte, durante l&#39;esportazione di un file .sbs/.sbsar, le immagini non hanno la profondità di bit corretta
* &amp;lbrack;Layers&amp;rbrack; Rendere invisibile un livello splatter rende invece il suo primo elemento secondario
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante il caricamento della maschera nel livello di luminosità/contrasto
* &amp;blocco;Livelli&amp;rbrack; dopo l&#39;eliminazione del livello vengono visualizzati messaggi di errore fuorvianti
* &amp;lbrack;Layers&amp;rbrack; Possibile arresto anomalo durante il downgrade di una risorsa
* &amp;lbrack;Layers&amp;rbrack; Alcuni output non sono collegati agli input a meno che l’utilizzo non sia forzato nel pannello Impostazioni canale
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Il menu a discesa del livello di riferimento può essere reimpostato per errore
* &amp;lbrack;UI&amp;rbrack; l&#39;importazione delle icone delle informazioni del modello deve essere aggiornata
* &amp;lbrack;UI&amp;rbrack; Il suggerimento per la scelta rapida da tastiera del riquadro di visualizzazione viene visualizzato ogni volta che cambia il layout del riquadro di visualizzazione

### **4.2.1 DORAYAKI**

*(Rilasciato il 21 settembre 2023)*

**Aggiunto:**

* &amp;lbrack;Content&amp;rbrack; Da immagine a materiale - Migliora la generazione di microdettagli nella mappa normale
* &amp;lbrack;Content&amp;rbrack; Da immagine a materiale - Nuovo parametro di intensità di illuminazione
* &amp;lbrack;Layers&amp;rbrack; Le immagini possono essere aggiunte nei livelli di importazione delle immagini
* &amp;lbrack;Layers&amp;rbrack; Le immagini possono essere rimosse nei livelli di importazione delle immagini
* &amp;lbrack;Layers&amp;rbrack; è ora possibile eliminare i livelli non validi
* &amp;lbrack;vista 2D&amp;rbrack; Maiusc+C scelta rapida da tastiera per far tornare indietro i canali
* &amp;lbrack;capture 3D&amp;rbrack; Visualizza un avviso popup quando l&#39;utente importa meno di 20 immagini
* &amp;lbrack;Applicazione&amp;rbrack; Nuove preferenze per impostare il valore di Affiancamento predefinito della texture di materiale
* &amp;lbrack;Onboarding&amp;brack; interfaccia utente dell&#39;esercitazione aggiornata per Image to Material (AI) e Upscale
* &amp;lbrack;Scripting&amp;rbrack; capture 3D API: DatasetInfo contiene più dati quando Capture3dState è impostato su aligned
* &amp;lbrack;Scripting&amp;rbrack; Nuovo argomento select_asset per create_asset(). Nuove funzioni: wait_for_computation() e clear_render_cache()

**Risolto:**

* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando l&#39;area di ritaglio è molto piccola
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si aggiunge o si modifica il filtro Ritaglio
* &amp;lbrack;Layers&amp;rbrack; Se si crea un quadrato nell’area di ritaglio, la risoluzione dell’output del materiale risulta errata
* &amp;lbrack;Livelli&amp;rbrack; Gli output a volte scompaiono quando più livelli sono disattivati
* &amp;lbrack;Layers&amp;rbrack; La cache di rendering potrebbe non essere invalidata correttamente con i filtri Image to Material (AI) e Upscale
* &amp;lbrack;Layers&amp;rbrack; impossibile aggiungere il filtro Ingrandisci quando si seleziona &quot;Non mostrare più questo messaggio&quot; nel popup di avviso
* &amp;lbrack;Layers&amp;rbrack; impossibile ripristinare l&#39;immagine nel filtro Ricamo una volta modificata
* &amp;lbrack;Esporta&amp;rbrack; la risoluzione della mappa normale esportata cambia quando si cambia il formato normale
* &amp;lbrack;Export&amp;rbrack; Rimuovi il suffisso del nome file &quot;\_environment&quot; durante l&#39;esportazione di un ambiente
* &amp;lbrack;Export&amp;rbrack; Impossibile esportare un file .sbsar quando è presente un livello di Trasforma Altera nella Pila livelli
* &amp;lbrack;2D View&amp;rbrack; &quot;Adatta allo schermo&quot; non funziona quando cambia la risoluzione
* &amp;lbrack;Application&amp;rbrack; Dopo aver chiuso la finestra dell&#39;applicazione durante l&#39;elaborazione, il processo dell&#39;applicazione potrebbe essere ancora in esecuzione
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;lbrack;Applicazione&amp;rbrack; invalida la cache di rendering quando si alternano le reti neurali con accelerazione GPU
* &amp;lbrack;Scripting&amp;rbrack; La denominazione di un plug-in come nome di pannello esistente causa comportamenti imprevisti
* &amp;lbrack;UI&amp;rbrack; se si fa clic su un elemento con una descrizione comandi, quest&#39;ultima scompare fino al riavvio
* &amp;lbrack;UI&amp;rbrack; il valore della scala Height potrebbe cambiare quando si cambia risorsa
* &amp;lbrack;UI&amp;rbrack; Margine errato nelle caselle combinate

### **4.2 DORAYAKI**

*(Rilasciato il 5 settembre 2023)*

**Aggiunto:**

* &amp;lbrack;Content&amp;rbrack; Filtri Image to Material (AI) e Delighter notevolmente migliorati
* &amp;blocco;Content&amp;rbrack; Nuovo filtro Ingrandisci
* &amp;lbrack;Content&amp;rbrack; Il filtro Ritaglio ora ha una risoluzione di output dinamica.
* &amp;lbrack;Material Creation Template&amp;rbrack; Aggiungi impostazione dimensioni documento.
* &amp;lbrack;Material Creation Template&amp;rbrack; Nuovo pulsante di attivazione/disattivazione &quot;Aggiungi un ritaglio&quot;.
* &amp;lbrack;Material Creation Template&amp;rbrack; Nuovo interruttore &quot;Ingrandisci materiale&quot;
* &amp;lbrack;Material Creation Template&amp;rbrack; visualizza le dimensioni dell&#39;immagine importata
* &amp;lbrack;Material Creation Template&amp;rbrack; Fornisci un feedback quando non è possibile utilizzare alcune immagini importate
* &amp;lbrack;Material Creation Template&amp;rbrack; Avvisa quando le dimensioni dell&#39;immagine sono incoerenti
* &amp;lbrack;Modello di creazione materiale&amp;rbrack; nuovi avvisi e descrizioni comandi
* &amp;lbrack;Layers&amp;rbrack; Visualizza la risoluzione dei livelli nella Pila livelli
* &amp;lbrack;Layers&amp;rbrack; La risoluzione di calcolo dei livelli può ora essere impostata su Dimensioni documento o su Dimensioni input
* &amp;lbrack;Layers&amp;rbrack; Mostra la risoluzione dei livelli nella Pila livelli
* &amp;blocco;Livelli&amp;rbrack; Imposta un criterio di risoluzione dei livelli su Input documento o Input livello quando applicabile
* &amp;lbrack;Layers&amp;rbrack; Avvisa l&#39;utente quando un filtro Ingrandisci viene aggiunto manualmente e fornisce la documentazione necessaria
* &amp;lbrack;Layers&amp;rbrack; Avvisa l&#39;utente quando esegue un ingrandimento lineare e offre di utilizzare il filtro Ingrandisci
* &amp;lbrack;Layers&amp;rbrack; Il calcolo di un livello Immagine in materiale (AI) ora può essere annullato più rapidamente per migliorare i tempi di rendering durante l’ottimizzazione della pila di livelli
* &amp;lbrack;Livelli&amp;rbrack; Il calcolo di un livello di ingrandimento può ora essere annullato più rapidamente per migliorare i tempi di rendering durante l’ottimizzazione del gruppo di livelli
* &amp;lbrack;Esporta&amp;rbrack; Consenti l&#39;override della risoluzione delle texture esportate
* &amp;lbrack;Esporta&amp;rbrack; canali da esportare è ora ordinato
* &amp;lbrack;Esporta&amp;rbrack; visualizza la risoluzione dei canali nell&#39;elenco canali da esportare
* &amp;lbrack;Applicazione&amp;rbrack; Nuova preferenza per abilitare o disabilitare le reti neurali con accelerazione GPU
* &amp;lbrack;UI&amp;rbrack; menu a discesa con risoluzione migliorata
* &amp;lbrack;UI&amp;rbrack; nuove icone per i filtri Trasformazione trama, Elaborazione post-trama e Intreccio
* &amp;lbrack;UI&amp;rbrack; Rinomina il pannello &quot;Condividi&quot; in &quot;Esporta&quot;
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi il supporto della risoluzione di output dei livelli all’API di esportazione
* &amp;lbrack;Scripting&amp;rbrack; Sono stati aggiunti Ritaglio, Ingrandimento e Dimensioni documento all’API di importazione delle immagini
* &amp;blocco;Onboarding&amp;rbrack; nuove esercitazioni
* &amp;blocco;Onboarding&amp;brack; contenuto per il completamento dell&#39;aggiornamento e Novità delle schermate
* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine alla versione 9.0.1

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Migliora la denominazione delle opzioni di precisione nei parametri delle impostazioni di allineamento
* &amp;lbrack;Application&amp;rbrack; L&#39;importazione di immagini con un numero non multiplo di 16 dimensioni può causare un arresto anomalo
* &amp;lbrack;Application&amp;brack; Arresto anomalo durante la duplicazione di una risorsa nel pannello Progetto
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si cambiano le risorse nel pannello Progetto
* &amp;lbrack;Content&amp;rbrack; Il disegno di una maschera personalizzata per il filtro Snow non funziona correttamente
* &amp;lbrack;Exposed Parameters&amp;rbrack; Le modifiche ai parametri esposti possono andare perdute quando si cambia materiale
* &amp;lbrack;Interoperabilità&amp;rbrack; L&#39;invio di un materiale dal pannello Esporta può causare un arresto anomalo
* &amp;lbrack;Livelli&amp;rbrack; Riempimento in base al contenuto interrompe l&#39;elaborazione quando si passa da un input di immagine singola a un input di materiale
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo dopo la duplicazione di una luce ambiente che contiene un materiale
* &amp;lbrack;Layers&amp;rbrack; Il livello di importazione immagine visualizza un nome immagine errato nel pannello Proprietà se il file immagine è stato rinominato
* &amp;lbrack;Layers&amp;rbrack; A volte una rotella viene visualizzata su un livello inattivo
* &amp;lbrack;Livelli&amp;rbrack; A volte la modifica dell’utilizzo dell’output di un’immagine in un livello di importazione di immagini non funziona
* &amp;lbrack;Layers&amp;rbrack; Typos nella finestra Modello di creazione
* &amp;lbrack;UI&amp;rbrack; la descrizione del comando di onboarding della finestra della vista 3D presenta problemi relativi allo stato attivo
* &amp;lbrack;UI&amp;rbrack; se il nome del file è troppo lungo, il nome dell&#39;immagine potrebbe essere in eccesso
* &amp;lbrack;UI&amp;rbrack; problemi minori di layout della barra degli strumenti dei pennelli quando si utilizza la gomma
* &amp;lbrack;UI&amp;rbrack; In alcune lingue le stringhe vengono troncate nel pannello Impostazioni visualizzatore
* &amp;lbrack;UI&amp;rbrack; Mentre viene visualizzato il menu a comparsa della descrizione della finestra della vista, premendo &quot;spazio&quot; viene creato un nuovo progetto

### **4.1.2 CANNOLI**

*(Rilasciato il 20 giugno 2023)*

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Perdita di memoria durante l&#39;ottimizzazione di materiali e filtri Substance che causa arresti anomali

### **4.1.1 CANNOLI**

*(Rilasciato il 6 giugno 2023)*

**Aggiunto**

* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine alla versione 9.0
* &amp;lbrack;Interoperabilità&amp;rbrack; Invia oggetti 3D a Stager e Painter

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; arresti anomali di applicazioni quando il rendering del capture 3D non riesce
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo in cui non è possibile caricare un&#39;immagine
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo quando si raggiunge la fase di ricostruzione della trama
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo durante il ridimensionamento del rettangolo di selezione
* &amp;lbrack;capture 3D&amp;rbrack; L&#39;importazione delle maschere in base alla convenzione non assegna correttamente la maschera
* &amp;lbrack;capture 3D&amp;rbrack; Errori di rendering durante la regolazione del rettangolo di selezione
* &amp;lbrack;capture 3D&amp;rbrack; Il passaggio tra la versione e l’alternanza delle opzioni di rendering durante l’elaborazione del post di Capture 3D è lento
* &amp;lbrack;capture 3D&amp;rbrack; Il passaggio da una versione all&#39;altra durante il passaggio Post-elaborazione di capture 3D a volte è interrotto
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;avvio
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante la duplicazione di un materiale rinominato
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si apre un progetto .alch legacy senza la relativa cartella dipendenze
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si collega/scollega uno schermo, il computer passa alla modalità di sospensione o è accessibile in remoto
* &amp;lbrack;Application&amp;rbrack; Arresti anomali e perdite di memoria correlati alla gestione delle risorse non persistenti
* &amp;lbrack;Export&amp;rbrack; La scelta del formato del materiale per i tipi di file di oggetti 3D che incorporano o fanno riferimento a texture deve essere disattivata
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo se si verifica un errore durante l&#39;esportazione di oggetti 3D
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;esportazione di un file .sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;importazione di un predefinito personalizzato che ha lo stesso Label ma non lo stesso nome di file
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione di una luce ambientale in un file sbs/.sbsar a volte non funziona
* &amp;lbrack;Export&amp;rbrack; L’esportazione Gltf/Glb codifica le texture in base64
* &amp;lbrack;Export&amp;rbrack; Il campo di testo Nome non funziona durante la rimessa a fuoco
* &amp;lbrack;Export&amp;rbrack; Mantieni Affiancamento non funziona quando si esporta un livello Immagine in materiale (IA Powered) in un file .sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; Quando si esporta gltf e si sostituiscono i file, l&#39;elenco dei file da sostituire non è corretto
* &amp;lbrack;Exposed Parameters&amp;rbrack; Il valore di inizializzazione casuale non funziona nei file .sbs/.sbsar esportati
* &amp;lbrack;Layers&amp;rbrack; Riempimento in base al contenuto a volte arresti anomali quando viene aggiunto per la seconda volta
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante l&#39;elaborazione di una Pila livelli
* &amp;lbrack;Layers&amp;rbrack; Image to Material (AI) disco cache non funziona
* &amp;lbrack;Layers&amp;rbrack; Possibile arresto anomalo durante l&#39;ottimizzazione di un livello
* &amp;lbrack;Performance&amp;rbrack; perdite di memoria
* &amp;lbrack;Project&amp;rbrack; Arresto anomalo durante il salvataggio di un progetto
* &amp;lbrack;Project&amp;rbrack; L&#39;importazione dello stesso progetto due volte in una riga duplica le risorse
* &amp;lbrack;UI&amp;rbrack; i pulsanti arrotondati con solo un&#39;icona non vengono visualizzati correttamente

### 4.1.0 Cannoli

*(Rilasciato il 28 marzo 2023)*

**Aggiunto:**

* &amp;blocco;Content&amp;rbrack; nuovo filtro Ricamo
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro Alterazione pittura
* &amp;lbrack;UI&amp;rbrack; Aggiungi opzione Esporta nel menu File
* &amp;lbrack;capture 3D&amp;rbrack; Indietro è ora disponibile nel passaggio di allineamento
* &amp;lbrack;capture 3D&amp;rbrack; Images Handle JPEG EXIF orientation
* &amp;lbrack;capture 3D&amp;rbrack; Scripting - Nuova proprietà dataset_info.camera
* &amp;lbrack;capture 3D&amp;rbrack; Aggiungi supporto Linux (consultare la documentazione)
* &amp;lbrack;capture 3D&amp;rbrack; Verifica dell&#39;accesso in lettura alle immagini importate
* &amp;lbrack;Onboarding&amp;rbrack; Scopri - 2 nuove esercitazioni (Ricamo e Alterazione pittura)
* &amp;lbrack;Onboarding&amp;rbrack; contenuto aggiornato della sezione Novità

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Mantiene la posizione della fotocamera quando si modifica la versione
* &amp;lbrack;capture 3D&amp;rbrack; Unisce tutti i gruppi di un oggetto
* &amp;lbrack;capture 3D&amp;rbrack; ha rinominato le trame generate in Originale
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si tenta di generare la miniatura di un&#39;immagine inesistente
* &amp;blocco;Risorse&amp;rbrack; L&#39;icona del cestino non esegue alcuna operazione nel pannello Risorse
* &amp;lbrack;Content&amp;rbrack; L&#39;aggiornamento dei filtri con gli slot dei materiali non funziona come previsto
* &amp;lbrack;Export&amp;rbrack; Possibile arresto anomalo durante l’esportazione di una risorsa con filtri specifici
* &amp;lbrack;Export&amp;rbrack; Esportazione SBS/SBSAR - I livelli di importazione delle immagini avevano la priorità sui parametri delle immagini
* &amp;lbrack;Export&amp;rbrack; UE4 Il predefinito di esportazione non funziona con PNG
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si rilasciano contemporaneamente un materiale e un filtro da Esplora sistema operativo
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante il trascinamento di un file SBSAR con qualsiasi file di immagine
* &amp;lbrack;Layers&amp;rbrack; Il canale di opacità del ricamo può essere completamente bianco
* &amp;lbrack;Localization&amp;rbrack; La lingua cinese può essere visualizzata per impostazione predefinita su Linux
* &amp;lbrack;Performance&amp;brack; È stato risolto un problema di memoria durante la rimozione di un livello da una risorsa.
* &amp;lbrack;Project&amp;rbrack; Possibile arresto anomalo durante il salvataggio
* &amp;lbrack;UI&amp;rbrack; Aggiungi spaziatura mancante sul pulsante del menu Versione
* &amp;lbrack;UI&amp;rbrack; pulsante Annulla non visualizzato correttamente
* &amp;lbrack;UI&amp;rbrack; Disattiva animazione cursori per parametri di post-elaborazione capture 3D
* &amp;lbrack;UI&amp;rbrack; La finestra Modello di creazione materiale non si chiude automaticamente quando si fa clic all&#39;esterno
* &amp;lbrack;UI&amp;rbrack; La funzione di accesso rapido del filtro si chiude quando si fa clic all&#39;esterno

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.2 Banane

*(Rilasciato il 9 marzo 2023)*

**Aggiunto:**

* &amp;lbrack;capture 3D&amp;rbrack; L&#39;utilizzo del disco mostra la quantità utilizzata
* &amp;lbrack;capture 3D&amp;rbrack; L&#39;importazione delle foto è asincrona e più veloce
* &amp;lbrack;Scripting&amp;rbrack; Nuove classi e funzioni per la creazione di script per la funzionalità capture 3D
* &amp;lbrack;Scripting&amp;rbrack; Nuova classe ExportController per eseguire azioni al termine, all&#39;annullamento o all&#39;errore dell&#39;esportazione
* &amp;lbrack;Scripting&amp;rbrack; Passare argomenti script pitoni eseguiti con —run-script
* &amp;lbrack;UI&amp;rbrack; feedback interfaccia utente quando si trascina una risorsa sul pannello Livelli
* &amp;lbrack;Content&amp;rbrack; Il filtro della temperatura colore è ora in funzione sui materiali
* &amp;lbrack;Content&amp;rbrack; Normale ai filtri Height ha una nuova opzione per mantenere la suddivisione in porzioni

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; dimensioni immagine corrette nel passaggio di allineamento del set di dati
* &amp;lbrack;capture 3D&amp;rbrack; Rimuovi vertici duplicati dopo lo srotolamento UV
* &amp;lbrack;capture 3D&amp;rbrack; MacOS - Migliore rilevamento se il capture 3D è disponibile
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo quando si chiude la finestra del Capture 3D durante l&#39;importazione di immagini
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo durante la generazione di una nuova versione
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo quando si tenta di caricare un oggetto 3D nel visualizzatore
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo quando si utilizza un tracciato con caratteri non UTF8
* &amp;lbrack;capture 3D&amp;rbrack; Tipi di risultati e suggerimenti
* &amp;lbrack;capture 3D&amp;rbrack; Le trame non vengono più ridimensionate per adattarsi al cubo unitario
* &amp;lbrack;capture 3D&amp;rbrack; Impedisce l&#39;arresto anomalo quando si chiude un Capture 3D durante il rendering
* &amp;lbrack;capture 3D&amp;rbrack; La rimozione di una maschera fa scomparire l&#39;immagine
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante l&#39;importazione di una risorsa due volte contemporaneamente
* &amp;lbrack;Applicazione&amp;rbrack; esegue il backup della versione precedente delle risorse all&#39;apertura di un progetto se non ne è mai stato eseguito il backup
* &amp;lbrack;Application&amp;rbrack; Memorizza correttamente nella cache le mappe con baking quando non tutte le mappe sono elaborate
* &amp;lbrack;Application&amp;rbrack; Fullscreen si arresta quando viene visualizzato un oggetto 3D.
* &amp;lbrack;Application&amp;rbrack; L&#39;ultimo materiale viene duplicato durante il salvataggio del progetto
* &amp;lbrack;Application&amp;rbrack; Impedisce l&#39;arresto anomalo durante l&#39;annullamento del calcolo di post-elaborazione della trama durante la fase di cottura
* &amp;lbrack;Application&amp;rbrack; la riapertura del progetto corrente non elimina le modifiche
* &amp;lbrack;Application&amp;rbrack; Interrompe la generazione di miniature per oggetti 3D
* &amp;lbrack;2D View&amp;rbrack; Arresto anomalo quando si utilizza lo strumento Pennello
* &amp;blocco;Riempimento in base al contenuto; &amp;blocco;Riempimento in base al contenuto - il calcolo potrebbe bloccarsi
* &amp;lbrack;Content&amp;rbrack; il filtro Atlas Creator esegue il downscaling del canale Opacità
* &amp;blocco;Esporta&amp;rbrack; Correggi cancellazione coda esportazioni non riuscite
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione OBJ crea un oggetto 100 volte più piccolo del previsto
* &amp;lbrack;Livelli&amp;rbrack; Le immagini a colori importate come canali in scala di grigio sono ora considerate in scala di grigio
* &amp;lbrack;Export&amp;rbrack; i file FBX non possono essere importati in applicazioni di terze parti
* &amp;lbrack;Export&amp;rbrack; I nomi di output dello shader nei file USD non sono corretti
* &amp;lbrack;Layers&amp;rbrack; Il nome dell&#39;immagine non viene aggiornato quando si modifica il nome nell&#39;interfaccia Esplora sistema operativo
* &amp;lbrack;Scripting&amp;rbrack; Visualizza un messaggio di errore durante il ricaricamento di uno script non valido
* &amp;lbrack;UI&amp;rbrack; pulsante Materiale di base disabilitato quando non disponibile
* &amp;lbrack;UI&amp;rbrack; Arresto anomalo quando si accede alla finestra di dialogo del file nella finestra del modello di creazione del materiale
* &amp;lbrack;UI&amp;rbrack; La funzione di accesso rapido è accessibile anche quando il pannello Livelli è chiuso
* &amp;lbrack;UI&amp;rbrack; le icone Invia a non sono allineate
* &amp;lbrack;UI&amp;rbrack; l&#39;icona del livello cambia quando si fa clic sull&#39;icona della Fusione

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.1 Banane

*(Rilasciato il 7 febbraio 2023)*

**Corretto:**

* &amp;lbrack;capture 3D&amp;rbrack; Quando si utilizzano le maschere, la proiezione della texture potrebbe essere interrotta
* &amp;lbrack;capture 3D&amp;rbrack; Gli artefatti possono essere visualizzati sull&#39;oggetto
* &amp;lbrack;capture 3D&amp;rbrack; La trama esportata potrebbe essere molto piccola

**Problemi noti:**

* &amp;lbrack;capture 3D&amp;rbrack; le esportazioni FBX e OBJ riducono la scala del risultato
* &amp;lbrack;capture 3D&amp;rbrack; capture 3D è disponibile in MacOS anche se l&#39;hardware non è compatibile. Consulta la documentazione.
* &amp;lbrack;capture 3D&amp;rbrack; Arresto anomalo al termine della ricostruzione della trama.
* &amp;blocca;Livelli&amp;rbrack; il riempimento in base al contenuto può essere bloccato se si modificano i livelli sottostanti
* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 4.0.0 Banane

*(Rilasciato il 31 gennaio 2023)*

**Aggiunto:**

* &amp;lbrack;capture 3D&amp;rbrack; creazione di oggetti 3D da immagini
* &amp;lbrack;capture 3D&amp;rbrack; capture 3D dedicata guidata
* &amp;lbrack;capture 3D&amp;rbrack; Importa o genera maschere in bianco e nero sul set di dati
* &amp;lbrack;capture 3D&amp;rbrack; risultato allineamento - visualizza tutte le funzionalità corrispondenti come una nuvola di punti
* &amp;lbrack;capture 3D&amp;rbrack; Risultato dell&#39;allineamento: visualizzare e interagire con le fotocamere associate a ciascuna foto allineata
* &amp;lbrack;capture 3D&amp;rbrack; Definire l&#39;area di ricostruzione con un widget del rettangolo di selezione
* &amp;lbrack;capture 3D&amp;rbrack; Ridimensiona, trasla e ruota su tutti gli assi il widget del rettangolo di selezione
* &amp;lbrack;capture 3D&amp;rbrack; Definire la precisione della geometria per la trama ricostruita
* &amp;lbrack;capture 3D&amp;rbrack; Ottimizza trama e texture creando una nuova versione
* &amp;lbrack;capture 3D&amp;rbrack; Ognuna delle versioni viene decimata automaticamente in base al numero di facce di destinazione impostato
* &amp;lbrack;capture 3D&amp;rbrack; Il passaggio di post-elaborazione scompone automaticamente, riproietta le texture e quindi esegue il baking delle informazioni di height normale e AO dalla trama ad alto poli
* &amp;lbrack;capture 3D&amp;rbrack; Aggiungi il risultato originale o una versione al progetto Sampler
* &amp;lbrack;capture 3D&amp;rbrack; Nuovo livello di post-elaborazione trama per decimare, annullare automaticamente il contornamento, riproiettare le texture e cuocere i dettagli del livello di trama sottostante
* &amp;lbrack;capture 3D&amp;rbrack; nuovo livello Trasformazione trama per ridimensionare, ruotare o traslare il livello di trama sottostante
* &amp;blocco;Esporta&amp;rbrack; nuova finestra Esporta
* &amp;lbrack;Export&amp;rbrack; Impostazioni dedicate e interfaccia utente a seconda del tipo di risorsa (materiale, luce ambiente, trama)
* &amp;lbrack;Export&amp;rbrack; Esporta la trama come USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &amp;lbrack;Export&amp;rbrack; Definire il tipo di materiale durante l&#39;esportazione dei file di Substance (SBSAR, SBS)
* &amp;lbrack;UI&amp;rbrack; Sposta le impostazioni della cache in una nuova scheda nel popup Preferenze
* &amp;lbrack;Application&amp;rbrack; le finestre delle viste 2D e 3D possono ora essere ridimensionate, scambiate e impilate verticalmente
* &amp;lbrack;Application&amp;rbrack; Nuova variabile di ambiente SAMPLER_RESOURCES_PATH per aggiungere risorse iniziali aggiuntive
* &amp;lbrack;Scripting&amp;rbrack; Aggiunte variabili di ambiente SAMPLER_PLUGIN_PATH e SAMPLER_SCRIPT_PATH per importare plug-in e script all&#39;avvio
* &amp;lbrack;Scripting&amp;rbrack; Funzioni di esportazione aggiunte per materiali, luce ambientale e oggetti 3D
* &amp;lbrack;Scripting&amp;rbrack; identificatore aggiunto, valore predefinito, valori minimo e massimo, etichette ed enum ai parametri
* &amp;lbrack;Scripting&amp;rbrack; aggiunta della funzione import_texture per immettere un utilizzo personalizzato durante l&#39;importazione delle immagini

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si apre un progetto recente e si salva nella finestra di dialogo di conferma
* &amp;lbrack;Application&amp;rbrack; La finestra di dialogo File impedisce l&#39;apertura di file .ssa
* &amp;lbrack;Application&amp;rbrack; Le finestre di dialogo File possono essere visualizzate in una finestra di sfondo in macOS
* &amp;lbrack;Application&amp;rbrack; arresto anomalo potenziale all&#39;apertura di progetti 3.2
* &amp;lbrack;Applicazione&amp;rbrack; la selezione di un file chiude la finestra di dialogo File prima di visualizzare gli avvisi
* &amp;lbrack;Exposed Parameters&amp;rbrack; L&#39;esportazione delle luci di ambiente parametriche non funziona
* &amp;lbrack;Layers&amp;rbrack; il collegamento &quot;Fai clic qui per sfogliare&quot; nella pila di livelli non funziona più
* &amp;lbrack;Livelli&amp;rbrack; Il disegno di più immagini all&#39;interno dello stesso livello a volte non funziona
* &amp;lbrack;Layers&amp;rbrack; L&#39;impostazione di un&#39;immagine nelle proprietà del livello non aggiorna la miniatura del selettore di immagini
* &amp;lbrack;Livelli&amp;rbrack; L&#39;ottimizzazione di una risorsa Sampler aggiunta come livello non funziona
* &amp;lbrack;Project&amp;rbrack; Aggiornamento di risorse indesiderate all&#39;apertura di un progetto
* &amp;lbrack;Scripting&amp;rbrack; La ricerca della cartella del plug-in a volte non riesce in Windows
* &amp;lbrack;Scripting&amp;rbrack; Arresto anomalo quando si utilizza &#39;open_project()&#39; in uno script Python
* &amp;lbrack;Scripting&amp;rbrack; Esportazione JPEG non presente nell’API
* &amp;lbrack;Scripting&amp;rbrack; Il pannello del registro non è di sola lettura
* &amp;lbrack;Scripting&amp;rbrack; image_picker non funziona
* &amp;lbrack;UI&amp;rbrack; icona risorsa mancante per la luce ambientale nel pannello Progetto
* &amp;lbrack;UI&amp;rbrack; Il menu a discesa Invia a formato Designer nel popup Preferenze può essere vuoto
* &amp;lbrack;UI&amp;rbrack; Alcuni pulsanti hanno uno stile errato
* &amp;lbrack;UI&amp;rbrack; L&#39;etichetta si sovrappone ai pulsanti nei widget Gruppo pulsanti
* &amp;lbrack;UI&amp;rbrack; Posizione della descrizione comando errata per &quot;Strumenti&quot; in Imposta menu dimensioni fisiche
* &amp;lbrack;UI&amp;rbrack; Quando si cambia lingua, il menu File non è allineato

**Problemi noti:**

* &amp;lbrack;capture 3D&amp;rbrack; Quando si utilizzano le maschere, la proiezione della texture potrebbe essere interrotta
* &amp;lbrack;capture 3D&amp;rbrack; piccoli artefatti potrebbero apparire sull&#39;oggetto se la scala nella Trasforma Trama è troppo piccola
* &amp;lbrack;capture 3D&amp;rbrack; La trama esportata potrebbe essere molto piccola. Reimpostate la scala della trasformazione Trama e riesportate
* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

## Versione 3

### 3.4.1 Arancini

*(Rilasciato il 6 ottobre 2022)*

**Aggiunto:**

* &amp;blocco;Onboarding&amp;brack; Schermate Nuovo benvenuto e Novità
* &amp;lbrack;Onboarding&amp;rbrack; interfaccia utente della schermata iniziale aggiornata
* &amp;lbrack;Onboarding&amp;rbrack; nuovo contenuto Scopri nella schermata Home
* &amp;lbrack;Scripting&amp;rbrack; registra un errore nel pannello Registro quando non viene riconosciuto un metodo
* &amp;lbrack;Scripting&amp;rbrack; Nuovo modulo ssa.helpers per abilitare la stampa nel pannello Registro
* &amp;lbrack;Application&amp;rbrack; Supporto per il nuovo widget dei pulsanti affiancati di Substance 3D Designer

**Corretto:**

* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l’esportazione di un file .sbsar che fa riferimento a un’immagine mancante
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;esportazione di una risorsa che fa riferimento a un file di immagine danneggiato
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione di un file .sbsar con un livello Ricamo genera un materiale grigio
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione di un materiale in un file .sbs/sbsar può generare un materiale completamente trasparente
* &amp;lbrack;Export&amp;rbrack; Il parametro Formato normale non è esposto correttamente nei file sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione Sbs/sbsar di una Pila livelli che fa riferimento a un file .svg è interrotta
* &amp;lbrack;Export&amp;rbrack; Trasforma livello non viene esportato correttamente / Enscape aggiornato - Aggiorna predefinito di esportazione
* &amp;lbrack;Exposed Parameters&amp;rbrack; Arresto anomalo quando si elimina un livello contenente un parametro esposto
* &amp;lbrack;Exposed Parameters&amp;rbrack; L&#39;aggiornamento di un livello obsoleto nella pila di livelli può causare il danneggiamento di un elenco di parametri esposti
* &amp;lbrack;Exposed Parameters&amp;rbrack; I parametri che non devono essere esportati vengono comunque esportati
* &amp;lbrack;Parametri esposti&amp;rbrack; La rimozione di un filtro di fusione quando si elimina un livello non ne annulla la visualizzazione dei parametri
* &amp;lbrack;Exposed Parameters&amp;rbrack; I parametri di testo interrompono le esportazioni sbs/.sbsar
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si rilascia una Pila livelli in un&#39;altra Pila livelli
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando non si carica un filtro
* &amp;lbrack;Layers&amp;rbrack; Impossibile ricaricare l&#39;immagine precedente durante la reimpostazione del campo Immagine
* &amp;lbrack;Layers&amp;rbrack; Impossibile annullare/ripristinare le modifiche apportate allo strumento di Trasforma
* &amp;lbrack;Layers&amp;rbrack; Clona /Clone livello Timbro si blocca dopo aver fatto clic su &quot;Ripristina tutte le impostazioni&quot;
* &amp;lbrack;Layers&amp;rbrack; L&#39;uso di uno dei pulsanti di reimpostazione impedisce di disegnare nel campo Immagine
* &amp;lbrack;Layers&amp;rbrack; Il pulsante Ripristina non cancella la maschera di disegno nel campo Immagine
* &amp;lbrack;Layers&amp;rbrack; Il pulsante Reimposta nel campo Immagine non ha alcun effetto se l&#39;utente ha disegnato qualcosa
* &amp;lbrack;Layers&amp;rbrack; La cache di rendering non funziona quando si utilizza lo strumento Pennello
* &amp;lbrack;Layers&amp;rbrack; Il livello eliminato può ancora essere visualizzato nel pannello Proprietà
* &amp;lbrack;Livelli&amp;rbrack; il calcolo dei livelli può bloccarsi quando si passa da un progetto all’altro
* &amp;lbrack;Project&amp;rbrack; A volte Sampler non è in grado di aprire un progetto dal disco
* &amp;lbrack;2D View&amp;rbrack; La vista 2D restituisce sempre per impostazione predefinita Output materiale

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.4.0 Arancini

*(Rilasciato il 6 settembre 2022)*

**Aggiunto:**

* &amp;lbrack;Parametri esposti&amp;rbrack; Nuovo Pannello dei parametri esposti
* &amp;lbrack;Exposed Parameters&amp;rbrack; Nuovo pulsante al passaggio del mouse sui parametri per esporre e rimuovere i parametri dal pannello Proprietà
* &amp;lbrack;Parametri esposti&amp;rbrack; Nuovo menu di scelta rapida con pulsante destro del mouse su parametri per esporre e rimuovere i parametri dal pannello Proprietà
* &amp;lbrack;Exposed Parameters&amp;rbrack; I parametri esposti sono elencati nel Pannello dei parametri esposti
* &amp;lbrack;Exposed Parameters&amp;rbrack; punti colore e dischi colore vengono aggiunti in diversi punti per identificare facilmente i parametri esposti
* &amp;lbrack;Exposed Parameters&amp;rbrack; Le etichette dei parametri possono essere modificate nel Pannello dei parametri esposti
* &amp;lbrack;Exposed Parameters&amp;rbrack; Visualizza un avviso per i parametri non esportabili
* &amp;lbrack;Exposed Parameters&amp;rbrack; visualizza un avviso se si sposta un livello con parametri di fusione esposti in un punto in cui diventano nascosti
* &amp;lbrack;Exposed Parameters&amp;rbrack; I parametri esposti vengono esportati nei formati SBS e SBSAR
* &amp;lbrack;Metadata&amp;rbrack; Supporto modelli di metadati personalizzati
* &amp;lbrack;Metadata&amp;rbrack; nuovo modello di metadati delle proprietà fisiche CLO
* &amp;lbrack;Metadati&amp;rbrack; Aggiungi icone al passaggio del mouse per aggiungere/rimuovere metadati personalizzati
* &amp;lbrack;Python API&amp;rbrack; Nuova API Python
* &amp;lbrack;Python API&amp;rbrack; per la creazione di risorse
* &amp;lbrack;Python API&amp;rbrack; per la gestione dei livelli
* &amp;lbrack;Python API&amp;rbrack; API per la gestione dei parametri
* &amp;lbrack;Python API&amp;rbrack; per la gestione dei progetti
* &amp;lbrack;Python API&amp;rbrack; È possibile attivare e disattivare un plug-in
* &amp;lbrack;Python API&amp;rbrack; Documentazione delle API Python accessibile dal menu Aiuto
* &amp;blocco;Scripting&amp;rbrack; sezione Nuovi plug-in e script nel popup Preferenze
* &amp;lbrack;Scripting&amp;rbrack; Creazione e importazione di plug-in per personalizzare l&#39;interfaccia di Sampler con i propri pannelli
* &amp;lbrack;Scripting&amp;rbrack; I plug-in diventano parte dell&#39;interfaccia di Sampler e possono essere ancorati e spostati come pannelli standard di Sampler
* &amp;lbrack;Scripting&amp;rbrack; Barra dei pulsanti dedicata per i plug-in sulla barra degli strumenti a destra di Sampler
* &amp;lbrack;Scripting&amp;rbrack; Crea e importa script per eseguire un elenco di determinate attività
* &amp;lbrack;Scripting&amp;rbrack; Avvia script Python dal menu Script
* &amp;lbrack;Scripting&amp;rbrack; I plug-in e gli script possono essere eliminati, riordinati e ricaricati dalla finestra Preferenze
* &amp;lbrack;Scripting&amp;rbrack; aggiunto —parametri della riga di comando run-script
* &amp;blocco;Registri&amp;rbrack; nuovo pannello Registri
* &amp;blocca;Registri&amp;brack; Attiva il pannello Registri dalla finestra Preferenze
* &amp;blocca;Registri&amp;rbrack; Nuova barra delle azioni per cancellare, copiare/incollare, esportare i registri
* &amp;lbrack;Proprietà&amp;rbrack; Nuovo pulsante al passaggio del mouse sui parametri per reimpostare il valore del parametro
* &amp;lbrack;Proprietà&amp;rbrack; Nuovo menu di scelta rapida con pulsante destro del mouse sui parametri per reimpostare il valore del parametro
* &amp;lbrack;Content&amp;rbrack; Da immagine a materiale (basata su IA) ora funziona su MacOS
* &amp;lbrack;Engine&amp;rbrack; Aggiorna il motore di Substance alla versione 8.6.0

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione potrebbe uscire quando è in corso la generazione di una miniatura
* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione potrebbe arresto anomalo quando si utilizza &#39;Salva con nome&#39; all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione potrebbe bloccarsi durante l&#39;arresto di MacOS
* &amp;lbrack;Applicazione&amp;rbrack; Il salvataggio con la finestra di dialogo colore aperta non consente di salvare le modifiche
* &amp;lbrack;Export&amp;rbrack; La convenzione di denominazione dei dati di utilizzo non è corretta durante l&#39;esportazione
* &amp;lbrack;Livelli&amp;rbrack; Se si trascina un materiale sopra un filtro, potrebbe verificarsi l&#39;arresto anomalo
* &amp;lbrack;Layers&amp;rbrack; L&#39;aggiornamento di una Pila livelli obsoleta potrebbe aggiornare Pile livelli non correlate
* &amp;blocco;Metadati&amp;rbrack; vengono esportati campi vuoti
* &amp;lbrack;Metadati&amp;rbrack; Quando è presente un solo elemento di metadati, l&#39;interfaccia utente consente di riordinarlo
* &amp;lbrack;Project&amp;rbrack; Il calcolo non termina mai dopo la duplicazione di un materiale
* &amp;blocco;Project&amp;rbrack; risorsa di progetto duplicata dopo il salvataggio iniziale del progetto
* &amp;lbrack;Project&amp;rbrack; calcoli non necessari quando si cambia risorsa
* &amp;lbrack;Rendering&amp;rbrack; Alcune pile di livelli non eseguono correttamente il rendering dopo l&#39;eliminazione di un livello
* &amp;lbrack;Security&amp;rbrack; Correzione di CVE-2015-20107
* &amp;lbrack;UI&amp;rbrack; gli output 2D possono essere sfocati a seconda delle dimensioni della finestra
* &amp;lbrack;UI&amp;rbrack; l&#39;anteprima della risorsa può rimanere aperta in primo piano quando l&#39;applicazione perde lo stato attivo
* &amp;lbrack;UI&amp;rbrack; gli angoli arrotondati della schermata di avvio hanno uno sfondo quadrato opaco

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.2 Zucchini

*(Rilasciato il 28 giugno 2022)*

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; Correggere il potenziale arresto anomalo all&#39;apertura di un progetto
* &amp;lbrack;Esporta&amp;rbrack; Il riavvio di Sampler interrompe l&#39;elenco dei predefiniti di esportazione personalizzati importati
* &amp;lbrack;Interoperability&amp;rbrack; Correggere l&#39;arresto anomalo quando un materiale inviato da Designer viene eliminato e quindi inviato nuovamente da Designer
* &amp;lbrack;Project&amp;rbrack; impossibile eliminare l&#39;ultima luce ambiente o materiale se si tratta dell&#39;ultima risorsa del progetto
* &amp;lbrack;Project&amp;rbrack; Se si fa clic con il pulsante destro del mouse su una luce ambiente, viene visualizzato l&#39;asterisco &quot;modifiche non salvate&quot;

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.1 Zucchini

*(Rilasciato il 7 giugno 2022)*

**Aggiunto:**

* &amp;lbrack;Application&amp;rbrack; supporto nativo per Apple silicon (M1)
* &amp;lbrack;UI&amp;rbrack; Nuova scelta rapida, tasto &quot;C&quot;, per scorrere i canali nella vista 2D
* &amp;lbrack;Strumenti&amp;rbrack; campo numerico per modificare il valore del colore in scala di grigio nella barra degli strumenti Pennello

**Corretto:**

* &amp;lbrack;Strumenti&amp;rbrack; L&#39;uso dello strumento Pennello su Windows con una scala dell&#39;interfaccia utente frazionaria (150%) determina lo scostamento dei tratti
* &amp;lbrack;Prestazioni&amp;rbrack; Migliorare il consumo di memoria
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; informazioni sulla Dimensioni fisiche possono mancare quando si abilita la funzione
* &amp;lbrack;UI&amp;rbrack; Lo scorrimento del mouse a volte non funziona come previsto quando si preme il tasto Alt
* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione potrebbe bloccarsi all&#39;apertura di un progetto salvato
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si trascinano e rilasciano più immagini e si utilizza l&#39;importazione delle texture nella finestra Modello di creazione materiale
* &amp;lbrack;Application&amp;rbrack; potenziale arresto anomalo durante il salvataggio di un progetto contenente un filtro personalizzato
* &amp;lbrack;Application&amp;rbrack; A volte lo stato del tasto Control viene perso quando si cambia applicazione
* &amp;lbrack;Assets&amp;rbrack; Arresto anomalo durante la ridenominazione di una cartella locale

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.3.0 Zucchini

*(Rilasciato il 17 maggio 2022)*

**Aggiunto:**

* &amp;blocco;Content&amp;rbrack; nuovo filtro Riempimento in base al contenuto (Windows e Mac)
* &amp;lbrack;Riempimento in base al contenuto sta lavorando su immagini, materiali PBR e luci ambiente
* &amp;lbrack;Content&amp;rbrack; Aggiungi il parametro &quot;Mantieni porzioni&quot; a Immagine su materiale (basata su IA)
* &amp;lbrack;Content&amp;rbrack; Il filtro Trasforma Prospettiva può visualizzare una griglia tra i quattro punti
* &amp;lbrack;Interoperabilità&amp;rbrack; Invia materiali ad Adobe Substance 3D Stager
* &amp;lbrack;Strumenti&amp;rbrack; centra la trasformazione premendo Ctrl durante il ridimensionamento dello strumento Trasforma o Ritaglia
* &amp;lbrack;Strumenti&amp;rbrack; Blocca il rapporto al quadrato premendo Maiusc durante il ridimensionamento dello strumento Trasforma o Ritaglio
* &amp;lbrack;Strumenti&amp;rbrack; Il cursore Timbro clone offre un&#39;anteprima di ciò che verrà timbrato
* &amp;lbrack;Strumenti&amp;rbrack; Visualizza in anteprima il contenuto originale nel cursore della Gomma quando si utilizza Timbro Clona /Clone
* &amp;lbrack;Strumenti&amp;rbrack; Ctrl+Clic crea un nuovo timbro nel livello Timbro clone
* &amp;lbrack;Strumenti&amp;rbrack; I timbri clone successivi sono ora raggruppati in un singolo livello
* &amp;lbrack;Strumenti&amp;rbrack; Brush Toolbar UI Revamp
* &amp;lbrack;Strumenti&amp;rbrack; La posizione della barra degli strumenti Pennello è persistente durante una sessione
* &amp;lbrack;Strumenti&amp;rbrack; Nuove opzioni di suddivisione del pennello in porzioni per asse
* &amp;lbrack;Strumenti&amp;rbrack; Nascondi/visualizza la sovrapposizione sulla vista 2D quando si disegna
* &amp;lbrack;Strumenti&amp;rbrack; Nuova scelta rapida, tasto &quot;X&quot;, per alternare tra Pennello e Gomma
* &amp;lbrack;Strumenti&amp;rbrack; Nuova scelta rapida, &quot;&amp;lbrack;&quot; &quot;&amp;rbrack;&quot; per modificare la dimensione del pennello
* &amp;lbrack;Strumenti&amp;rbrack; Nuova scelta rapida, tasto &quot;E&quot;, per attivare/disattivare la gomma
* &amp;lbrack;2D View&amp;rbrack; Nuova modalità Proiezione sferica durante la creazione della luce ambiente
* &amp;lbrack;2D View&amp;rbrack; Lo strumento Pennello è supportato con la modalità proiezione sferica
* &amp;lbrack;2D View&amp;rbrack; Lo strumento Posizione è supportato con la modalità proiezione sferica
* &amp;lbrack;2D View&amp;rbrack; Annulla/Ripeti è supportato in modalità proiezione sferica
* &amp;lbrack;2D View&amp;rbrack; In Proiezione sferica, impostare la posizione predefinita per osservare il centro dell&#39;ambiente
* &amp;lbrack;2D View&amp;rbrack; Nuovo controllo dell&#39;esposizione
* &amp;lbrack;UI&amp;rbrack; Nel pannello Proprietà, la modifica dell&#39;immagine mostra la sorgente del contenuto (immagine o da un livello)
* &amp;lbrack;UI&amp;rbrack; migliorato lo sfondo del menu a discesa dei livelli/materiali di output
* &amp;lbrack;UI&amp;rbrack; nuova posizione delle informazioni sulla risoluzione nella vista 2D
* &amp;lbrack;UI&amp;rbrack; Nuovo tooltip con le scelte rapide dei controlli di navigazione della vista 3D
* &amp;lbrack;UI&amp;rbrack; Nuova descrizione con i controlli del pennello
* &amp;lbrack;UI&amp;rbrack; Nuovo tooltip con scelte rapide dei controlli di navigazione della proiezione
* &amp;lbrack;Compound Filters&amp;rbrack; I filtri composti gestiscono le variazioni per lavorare su immagini, materiali PBR e luci ambiente
* &amp;lbrack;Compound Filters&amp;rbrack; L&#39;ordine di modifica corrisponde all&#39;ordine dell&#39;elenco dei nodi nel filtro composto
* &amp;lbrack;Compound Filters&amp;rbrack; Le modifiche di nodi diversi con lo stesso gruppo verranno unite in un unico gruppo nel pannello Proprietà
* &amp;lbrack;Applicazione&amp;rbrack; con impostazioni visualizzatore dedicate per tipo di risorsa

**Corretto:**

* &amp;lbrack;Application&amp;rbrack; L&#39;applicazione potrebbe arrestarsi in modo anomalo quando si passa alla vista 2D
* &amp;lbrack;Application&amp;rbrack; Correggere un possibile deadlock o arresto anomalo durante l&#39;esportazione più volte
* &amp;lbrack;Application&amp;rbrack; Rendi i valori predefiniti per i canali coerenti con Substance 3D Designer
* &amp;lbrack;Application&amp;rbrack; Il caricamento di un progetto non attiva il ricalcolo del materiale
* &amp;lbrack;Application&amp;rbrack; Aggiornamento dell&#39;URL alla documentazione di importazione delle texture
* &amp;lbrack;Content&amp;rbrack; Quando si utilizza un filtro composto, viene richiesto di essere aggiornato quando non dovrebbe, al momento del ricaricamento
* &amp;lbrack;Content&amp;rbrack; i dettagli nella mappa dell&#39;altezza scompaiono quando si utilizza la Fusione di opacità
* &amp;lbrack;UI&amp;rbrack; Nella finestra di dialogo Colore, è possibile uscire dall&#39;intervallo utilizzando i campi di testo del cursore
* &amp;lbrack;UI&amp;rbrack; l&#39;elenco Utilizzo include una barra di scorrimento verticale inutile

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* &amp;lbrack;Content&amp;rbrack; Il widget luce forma non funziona in modalità proiezione sferica
* &amp;lbrack;Interoperability&amp;rbrack; Il materiale con spostamento inviato a Stager perderà i controlli di spostamento

### 3.2.1 Yakitori

*(Rilasciato: 8 marzo 2022)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Esporta metadati dpi nei file di immagine
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Mantiene il rapporto con le texture non quadrate durante la modifica delle dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; I metadati della Dimensioni fisiche vengono applicati immediatamente quando la dimensioni fisiche cambia
* &amp;lbrack;UI&amp;rbrack; Regola il cursore massimo scala Height in modo che possa influenzare qualsiasi tipo di materiale quando la Dimensioni fisiche è abilitata
* &amp;lbrack;UI&amp;rbrack; Nuovi suggerimenti sui filtri di ricerca nel pannello Risorsa
* &amp;lbrack;UI&amp;rbrack; utilizzare le descrizioni comandi per spiegare quando i pulsanti sono disattivati nel pannello Risorse
* &amp;lbrack;Content&amp;rbrack; aggiornamento del filtro Contrasto luminosità

**Corretto:**

* &amp;lbrack;vista 2D&amp;rbrack; il pulsante di rotazione di 90 gradi negli strumenti Ritaglia e Trasforma non funziona come previsto
* &amp;lbrack;vista 2D&amp;rbrack; Il widget Ritaglio a volte scompare
* &amp;lbrack;Applicazione&amp;rbrack; La cancellazione di un parametro immagine non ricollega il livello sottostante
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita dopo il salvataggio di un progetto
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si trascina e si rilascia il materiale corrente in una raccolta del pannello Risorse
* &amp;lbrack;Application&amp;rbrack; È possibile che si verifichi un arresto anomalo di trascinamento di una risorsa nella finestra della vista
* &amp;lbrack;Contenuto&amp;rbrack; La fusione normale ha una regolazione di inizializzazione casuale
* &amp;lbrack;Content&amp;rbrack; Il filtro Snow ha un output normale errato a seconda dei valori dei parametri neve freschi e sciolti
* &amp;blocco;Content&amp;rbrack; filtro parquet: cuciture impreviste corrette
* &amp;lbrack;Content&amp;rbrack; filtro Ricamo: rimuovi filetto in mappa metallica
* &amp;lbrack;Content&amp;rbrack; filtro porzioni di Floor: correzione del numero di porzioni x e y
* &amp;lbrack;Content&amp;rbrack; Filtro muro di mattoni: output normale e height a 16 bit
* &amp;lbrack;Export&amp;rbrack; Il nome predefinito del file nel popup di esportazione non è il nome del materiale corrente
* &amp;lbrack;Esporta&amp;rbrack; l&#39;esportazione con rapporto fisico con un predefinito di esportazione fornisce dimensioni errate
* &amp;lbrack;Export&amp;rbrack; Metallic non è presente nel predefinito di esportazione CLO
* &amp;lbrack;Export&amp;rbrack; Quando si sostituisce un predefinito personalizzato di esportazione, il nome visualizzato non viene aggiornato
* &amp;lbrack;Layers&amp;rbrack; I canali personalizzati del primo livello inserito non vengono rilevati
* &amp;lbrack;Layers&amp;rbrack; Il materiale viene rivalutato quando si modificano le modifiche di un livello nascosto
* &amp;lbrack;Localization&amp;rbrack; Le descrizioni comandi non sono localizzate nel pannello Esporta
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; se si disabilita la Dimensioni fisiche di una risorsa, non viene rimossa la scala fisica
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; impossibile impostare il valore di Scala Height oltre i limiti del cursore la prima volta
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; L&#39;importazione di un&#39;immagine senza dimensioni fisiche impedisce l&#39;apertura del progetto
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; La Dimensioni fisiche è erroneamente impostata su zero se mancante
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Dimensioni fisiche scala fisica: lo stato della casella di controllo non viene aggiornato alla prima visualizzazione
* &amp;lbrack;UI&amp;rbrack; Materiale di base e normale al Height non hanno una categoria
* &amp;lbrack;UI&amp;rbrack; Il cursore a volte è invisibile quando si disegna un&#39;immagine
* &amp;lbrack;UI&amp;rbrack; se è vuoto, disattiva le opzioni &quot;Copia tutto&quot; e &quot;Taglia tutto&quot; nel menu di modifica di un campo di testo
* &amp;lbrack;UI&amp;rbrack; I nomi dei filtri contengono caratteri errati
* &amp;lbrack;UI&amp;rbrack; il pulsante Dimensioni fisiche blocco non ha lo stile corretto
* &amp;lbrack;UI&amp;rbrack; Il pulsante di chiusura nella barra di ricerca nel pannello Risorse non cancella la stringa di ricerca

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.2.0 Yakitori

*(Rilasciato il 25 gennaio 2022)*

**Aggiunto:**

* &amp;lbrack;Dimensioni fisiche&amp;rbrack; nuovo pannello Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi opzioni Dimensioni fisiche alla finestra Modello creazione materiale
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi strumento di misurazione Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi strumento di misurazione automatica Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi strumento diagnostica Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Consenti impostazione del valore z della Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; widget a discesa per impostare il livello di zoom nella vista 2D
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Nuova opzione &quot;Visualizza con rapporto fisico&quot; nel menu a discesa del livello di zoom
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Nuova opzione &quot;Adatta alla dimensioni fisiche&quot; nel menu a discesa del livello di zoom
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Visualizza la Dimensioni fisiche nella vista 2D
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Visualizza la Dimensioni fisiche nella finestra della vista 3D
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Nella finestra di dialogo di importazione delle immagini, mostra profondità dimensioni fisiche se è presente una mappa di altezza importata
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Mostra la Dimensioni fisiche nel menu di scelta rapida della risorsa
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Imposta l&#39;unità di lunghezza nelle Preferenze
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Esporta texture che rispettano le proporzioni fisiche
* &amp;lbrack;Metadata&amp;rbrack; Possibilità di aggiungere metadati personalizzati a una risorsa creata dall&#39;utente
* &amp;lbrack;Esporta&amp;rbrack; Esporta metadati personalizzati in file .sbs(ar)
* &amp;lbrack;Esporta&amp;rbrack; Esporta descrizione, categoria, autore e tag metadati in file .sbs(ar)
* &amp;lbrack;Export&amp;rbrack; Esporta la Dimensioni fisiche come file .sbs(ar)
* &amp;lbrack;Esporta&amp;rbrack; Imposta l&#39;impostazione di compressione del file .sbsar
* &amp;lbrack;Export&amp;rbrack; Esporta la miniatura della risorsa in file .sbs(ar)
* &amp;lbrack;Export&amp;rbrack; Imposta il tipo di grafico durante l&#39;esportazione di un file .sbs(ar)
* &amp;lbrack;Application&amp;rbrack; Realtime Engine 2021 non è più disponibile
* &amp;lbrack;Application&amp;rbrack; Annulla/Ripeti ora supporta le modifiche del cursore Affiancamento (U,V) e della scala height
* &amp;lbrack;Rendering&amp;rbrack; Genera cache disco quando la risorsa creata viene salvata
* &amp;lbrack;Assets&amp;rbrack; Utilizzare Ctrl+clic per attivare più filtri per tipo di risorsa nel pannello Risorse
* &amp;lbrack;UI&amp;rbrack; Possibilità di bloccare i cursori Affiancamenti (U,V)
* &amp;lbrack;UI&amp;rbrack; Aggiungi un menu di scelta rapida con &quot;Copia&quot;, &quot;Taglia&quot;, &quot;Incolla&quot;, &quot;Copia tutto&quot; e &quot;Taglia tutto&quot; nei campi di testo
* &amp;lbrack;UI&amp;rbrack; unità di lunghezza (metri, pollici, parsec, ...) supporto per etichette e campi di testo
* &amp;lbrack;UI&amp;rbrack; L&#39;utente può impostare la precisione decimale utilizzata per visualizzare i numeri
* &amp;lbrack;UI&amp;rbrack; Utilizza le unità nei popup delle misure ovunque sia pertinente
* &amp;lbrack;Localization&amp;rbrack; Il nuovo nome predefinito della risorsa è ora localizzato
* &amp;lbrack;Content&amp;rbrack; Nuovo generatore intreccio tessuto
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro per cambio canale
* &amp;lbrack;Content&amp;rbrack; Tutti i filtri pertinenti sono ora a conoscenza della Dimensioni fisiche
* &amp;blocco;Content&amp;rbrack; Nuove icone per Finitura legno
* &amp;lbrack;Content&amp;rbrack; Tutti i filtri sono ora compatibili con i canali Adobi Standard Material (ASM)
* &amp;lbrack;Content&amp;rbrack; I filtri possono ora avere una variante &quot;ambiente&quot;

**Corretto:**

* &amp;lbrack;vista 2D&amp;rbrack; Il canale rimane nell&#39;elenco quando viene rimosso
* &amp;lbrack;Application&amp;rbrack; Impossibile duplicare una risorsa caricata da Esplora file del sistema operativo
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo che a volte quando si fa clic su &quot;Risorse per iniziare&quot; nel pannello Risorse
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si elimina un materiale
* &amp;lbrack;Application&amp;rbrack; La variabile di ambiente &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; è ancora attiva se impostata su &quot;0&quot; o &quot;&quot;.
* &amp;lbrack;Application&amp;rbrack; Blocca durante il salvataggio di un progetto con più materiali
* &amp;lbrack;Application&amp;rbrack; L&#39;importazione di un&#39;immagine può generare un arresto anomalo
* &amp;lbrack;Application&amp;rbrack; alcune risorse iniziali mancanti al primo avvio
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione di una risorsa a volte genera un arresto anomalo
* &amp;lbrack;Layers&amp;rbrack; Impossibile importare immagini quando il pannello dei livelli è chiuso o invisibile
* &amp;lbrack;Livelli&amp;rbrack; La modifica della lingua fa sì che la risorsa corrente venga ricalcolata
* &amp;lbrack;Livelli&amp;rbrack; La modifica dell&#39;utilizzo di un&#39;immagine importata non aggiorna la variazione del filtro da utilizzare
* &amp;lbrack;Layers&amp;rbrack; Image to Material (AI) a volte non viene calcolato quando si modificano i livelli sottostanti
* &amp;lbrack;Layers&amp;rbrack; Image to Material (AI) a volte ricalcola quando non è necessario
* &amp;lbrack;Layers&amp;rbrack; Non è consigliato alcun aggiornamento quando si aggiorna un filtro personalizzato sul disco
* &amp;lbrack;Layers&amp;rbrack; Il canale Normale a volte ha il formato dei pixel errato
* &amp;nero;Livelli&amp;rbrack; alcuni livelli vengono ancora calcolati anche quando non sono visibili
* &amp;lbrack;Layers&amp;rbrack; Gli strumenti di Vista 2D potrebbero essere interrotti quando si attiva o disattiva la visibilità di un livello
* &amp;lbrack;Layers&amp;rbrack; L&#39;interfaccia utente si blocca quando si utilizza Image to Material (AI)
* &amp;lbrack;Layers&amp;rbrack; Alternando la visibilità del livello del filtro Trasforma si interrompe lo strumento di visualizzazione 2D e si potrebbe verificare un arresto anomalo
* &amp;lbrack;Layers&amp;rbrack; troppe rielaborazioni durante la rimozione di un livello dal gruppo di livelli
* &amp;lbrack;Livelli&amp;rbrack; Quando un filtro composto contiene un input/output insolito o personalizzato, Sampler non lo calcola
* &amp;lbrack;Performance&amp;brack; l&#39;apertura del pannello Risorse è lenta
* &amp;lbrack;Prestazioni&amp;rbrack; Evita di ricalcolare inutilmente il gruppo di livelli
* &amp;lbrack;Prestazioni&amp;rbrack; Il caricamento delle risorse del progetto richiede troppo tempo
* &amp;lbrack;Performance&amp;brack; Impossibile utilizzare la cache di rendering sul disco
* &amp;lbrack;Prestazioni&amp;rbrack; Il passaggio tra i livelli è lento
* &amp;lbrack;Prestazioni&amp;rbrack; La modifica di un materiale o di un filtro è lenta
* &amp;lbrack;Project&amp;rbrack; Il salvataggio di un progetto alla chiusura può provocare un arresto anomalo
* &amp;lbrack;Rendering&amp;rbrack; La rimozione di un&#39;immagine può rimuovere tutti gli output
* &amp;lbrack;Rendering&amp;rbrack; Il tempo di rendering visualizzato nella finestra della vista è errato durante l&#39;ottimizzazione
* &amp;lbrack;UI&amp;rbrack; Impossibile scorrere verticalmente nel popup di esportazione quando necessario
* &amp;lbrack;UI&amp;rbrack; È possibile aprire il popup di esportazione quando non vi è nulla da esportare
* &amp;lbrack;UI&amp;rbrack; Alcuni popup non scorrono se il loro contenuto fuoriesce
* &amp;lbrack;UI&amp;rbrack; I campi di testo non sono selezionati quando si fa clic su di essi o si apre un menu
* &amp;lbrack;UI&amp;rbrack; Il nome del metodo di fusione nel pannello delle proprietà a volte non è corretto
* &amp;lbrack;UI&amp;rbrack; L&#39;opzione Salva nel menu File a volte è disattivata
* &amp;lbrack;UI&amp;rbrack; Il campo di testo non scompare dopo la ridenominazione di due materiali
* &amp;lbrack;UI&amp;rbrack; Errore di battitura nel popup delle preferenze

**Problemi noti:**

* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.2 Xocoatl

*(Rilasciato il 14 dicembre 2021)*

**Corretto:**

* &amp;lbrack;Interoperability&amp;rbrack; L’apertura del file .sbsar con Substance 3D Sampler da Bridge può non riuscire su Windows
* &amp;lbrack;Livelli&amp;rbrack; Lo spostamento dell&#39;unico livello sottostante si arresta in modo anomalo
* &amp;lbrack;UI&amp;rbrack; Il pulsante Impostazioni canale scompare quando si cambia lingua
* &amp;lbrack;UI&amp;rbrack; il nome del materiale nel pannello Proprietà scompare dopo aver salvato il progetto
* &amp;blocca;Risorse&amp;blocca; Se si fa clic su &quot;Tutte le librerie&quot; si può verificare un arresto anomalo

**Problemi noti:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.1 Xocoatl

*(Rilasciato il 24 novembre 2021)*

**Aggiunto:**

* &amp;lbrack;Interoperability&amp;rbrack; Invia risorse (SBS o SBSAR) a Substance 3D Designer
* &amp;lbrack;Interoperability&amp;rbrack; impostare nelle preferenze il formato predefinito per l&#39;interoperabilità con Substance 3D Designer
* &amp;lbrack;Interoperability&amp;rbrack; Ricezione di più risorse da Adobe Bridge
* &amp;lbrack;UI&amp;rbrack; nuovo widget Numero casuale
* &amp;lbrack;UI&amp;rbrack; aggiornamento del menu di scelta rapida
* &amp;lbrack;Risorse&amp;rbrack; Trascina le immagini dal pannello Risorse al pannello Proprietà
* &amp;lbrack;Project&amp;rbrack; I nomi delle risorse sono riservati per evitare alcuni caratteri specifici
* &amp;lbrack;Branding&amp;rbrack; Aggiorna icona file per file SBSAR
* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine versione 8.3.0

**Corretto:**

* &amp;lbrack;Content&amp;rbrack; Ritaglio - Mantieni proporzioni durante il ritaglio di immagini non quadrate
* &amp;lbrack;Content&amp;rbrack; Trasforma - La trasformazione orizzontale non viene invertita quando si utilizza il widget
* &amp;lbrack;Content&amp;rbrack; Gravel - correggi la pittura a maschera personalizzata su tutti i canali
* &amp;blocco;Content&amp;brack; porzioni di pavimento - risolvere i problemi di suddivisione in porzioni e ripetizione dei pattern
* &amp;lbrack;Assets&amp;rbrack; opzione Adobe Bridge grigia se non installata
* &amp;blu;Selettore colore&amp;rbrack; il tasto Esc chiude il Selettore colore
* &amp;lbrack;Rendering&amp;rbrack; Correggere la scala della distanza di diffusione quando si utilizza l&#39;input in scala di grigi
* &amp;lbrack;Condividi&amp;rbrack; Le opzioni Invia a sono disponibili solo con le licenze Adobe
* &amp;lbrack;Project&amp;rbrack; Correggere un problema di prestazioni della memoria

**Problemi noti:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.1.0 Xocoatl

*(Rilasciato il 28 settembre 2021)*

**Aggiunto:**

* &amp;lbrack;Selettore colore&amp;rbrack; Nuova interfaccia utente Selettore colore
* &amp;lbrack;Selettore colore&amp;rbrack; Anteprima affiancata dei colori corrente e precedente
* &amp;lbrack;Selettore colore&amp;rbrack; Immettere il colore in Esadecimale
* &amp;nero;Selettore colore&amp;rbrack; Nuovo contagocce con anteprima colore
* &amp;lbrack;Selettore colore&amp;rbrack; Il contagocce può selezionare un colore esterno a Sampler
* &amp;lbrack;Selettore colore&amp;rbrack; modifica il colore negli spazi colore RGB o HSV
* &amp;lbrack;Selettore colore&amp;rbrack; Salva e gestisci campioni
* &amp;lbrack;Interoperability&amp;rbrack; Modifica le immagini in Illustrator dal livello Importazione immagine o dai parametri Immagine
* &amp;lbrack;Interoperability&amp;rbrack; Modifica le immagini in Photoshop dal livello Importazione immagine o dai parametri Immagine
* &amp;lbrack;Widget&amp;rbrack; Nuovo widget ritaglio
* &amp;lbrack;Widget&amp;rbrack; Premere Invio per convalidare il ritaglio
* &amp;lbrack;Widget&amp;rbrack; Il widget Ritaglio legge le dimensioni dell&#39;immagine per adattarle al widget e mantiene le proporzioni durante il ridimensionamento
* &amp;lbrack;UI&amp;rbrack; Nuova interfaccia utente del cursore per la visualizzazione in grigio
* &amp;lbrack;Applicazione&amp;rbrack; Aggiungi selezione formato normale nelle preferenze
* &amp;lbrack;Applicazione&amp;rbrack; Il formato normale nei livelli Importazione immagine segue il formato normale predefinito impostato nelle preferenze
* &amp;lbrack;Application&amp;rbrack; Nella vista 2D, la normale viene visualizzata nel formato normale impostato nelle preferenze
* &amp;lbrack;Application&amp;rbrack; Il normale viene esportato nel formato normale impostato nelle preferenze
* &amp;lbrack;Export&amp;rbrack; Aggiungi parametro formato normale alle esportazioni di file SBS e SBSAR
* &amp;lbrack;Export&amp;rbrack; Aggiungi impostazioni shader alle esportazioni di file SBS e SBSAR
* &amp;lbrack;Esporta&amp;rbrack; Imposta la risoluzione predefinita dei grafici SBS esportati
* &amp;lbrack;Compound Filters&amp;rbrack; crea pacchetti di filtri SSA con 7z
* &amp;lbrack;Compound Filters&amp;rbrack; Aggiungi i metadati delle categorie nei filtri composti
* &amp;lbrack;Compound Filters&amp;rbrack; I filtri composti possono avere una miniatura incorporata
* &amp;lbrack;Compound Filters&amp;rbrack; Estensione dei filtri composti (.ssafilter) aggiunta alla finestra di dialogo Ottieni file del contenuto
* &amp;lbrack;Compound Filters&amp;rbrack; Importa filtri composti (.ssafilter) nel pannello Risorse
* &amp;lbrack;Engine&amp;rbrack; Aggiorna il motore Substance alla versione 8.2.0

**Corretto:**

* &amp;blocco;Application&amp;rbrack; Le cartelle locali connesse possono bloccarsi
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;avvio di due istanze di Sampler
* &amp;lbrack;Content&amp;rbrack; Il filtro Ritaglio ha una regolazione di inizializzazione casuale
* &amp;lbrack;Content&amp;rbrack; Alcuni materiali Substance a volte non vengono aggiornati
* &amp;blocco;Esporta&amp;rbrack; Arresto anomalo durante l&#39;esportazione con un predefinito personalizzato appena aggiunto
* &amp;lbrack;Export&amp;rbrack; Dimensioni stimate del pacchetto mancanti nel popup di esportazione
* &amp;lbrack;Export&amp;rbrack; Correggere la perdita di memoria durante l&#39;esportazione di file SBS e SBSAR
* &amp;lbrack;Compound Filters&amp;rbrack; I filtri composti possono avere input duplicati
* &amp;lbrack;Compound Filters&amp;rbrack; Arresto anomalo se un filtro contiene riferimenti non soddisfatti
* &amp;lbrack;Compound Filters&amp;rbrack; Arresto anomalo durante il riordinamento di una pila di livelli con un filtro composto al suo interno
* &amp;lbrack;Compound Filters&amp;rbrack; Il rendering a volte si blocca
* &amp;lbrack;Importa&amp;rbrack immagine; L&#39;importazione di un&#39;immagine attiva più rendering
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si annulla/ripeti
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si aggiunge un Materiale di base
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si utilizza un&#39;immagine non valida come luce ambiente
* &amp;lbrack;Layers&amp;rbrack; Correggere l&#39;importazione duplicata quando si inserisce un filtro con diversi grafici
* &amp;blocca;Livelli&amp;rbrack; Riordinare i livelli non sempre funziona
* &amp;lbrack;Project&amp;rbrack; Arresto anomalo durante il caricamento di un file di progetto incompleto
* &amp;blocco;Project&amp;rbrack; arresto anomalo all&#39;apertura di un progetto danneggiato
* &amp;lbrack;Project&amp;rbrack; alcune risorse possono scomparire da un progetto
* &amp;lbrack;Proprietà&amp;rbrack; Correggere i predefiniti del filtro mancanti
* &amp;lbrack;UI&amp;rbrack; impossibile impostare i parametri Angolo
* &amp;lbrack;UI&amp;rbrack; I metadati dei filtri vengono visualizzati nel pannello Risorse
* &amp;lbrack;UI&amp;rbrack; il raggruppamento per categoria nasconde i filtri
* &amp;blocco;UI&amp;rbrack; problema di scorrimento nel pannello Risorse
* &amp;lbrack;UI&amp;rbrack; Il pannello di esportazione ha ora una barra di scorrimento
* &amp;lbrack;UI&amp;rbrack; La miniatura non viene visualizzata per alcuni formati immagine nel selettore immagini

**Problemi noti:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Il calcolo spesso può causare l&#39;arresto anomalo dell&#39;applicazione
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 si arresterà in modo anomalo su un computer Windows con CPU AMD e GPU Nvidia installate
* &amp;lbrack;Selettore colore&amp;rbrack; La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare

### 3.0.1 Waffle

*(Rilasciato il 27 luglio 2021)*

**Aggiunto:**

* &amp;lbrack;Pennello&amp;rbrack; Abilita i colori nello strumento Pennello se l&#39;input dell&#39;immagine lo supporta
* &amp;lbrack;Pennello&amp;rbrack; tenendo premuto il tasto Maiusc nello strumento pennello, vengono tracciate linee rette
* &amp;lbrack;Pennello&amp;rbrack; Mostra l&#39;anteprima della linea quando si tiene premuto Maiusc nello strumento Pennello
* &amp;lbrack;Pennello&amp;rbrack; Lo strumento Pennello ora supporta le operazioni Annulla e Ripeti
* &amp;lbrack;2D View&amp;rbrack; Il colore predefinito di input dell&#39;immagine viene utilizzato quando si disegna
* &amp;lbrack;Layers&amp;rbrack; Valore predefinito di input Substance di lettura nei file SBSAR
* &amp;lbrack;Rendering&amp;rbrack; Consenti di combinare il height con normale
* &amp;lbrack;Rendering&amp;rbrack; supporto per la dispersione sotto la superficie (non disponibile in MacOS)
* &amp;lbrack;Assets&amp;rbrack; Utilizza il tipo di grafico SBSAR per determinare il tipo di risorsa
* &amp;lbrack;Assets&amp;rbrack; migliori prestazioni per la ricerca e l&#39;individuazione delle risorse nel pannello Risorse
* &amp;lbrack;Assets&amp;rbrack; Ha aggiunto una voce &quot;Tutte le librerie&quot; nel pannello Risorse che visualizza tutte le risorse di tutte le tue librerie
* &amp;lbrack;Risorse&amp;rbrack; L&#39;utente può ora scegliere di raggruppare le risorse per categoria o tipo
* &amp;lbrack;Import&amp;rbrack; Rileva automaticamente anisotropia, pellicola, brillantezza e texture specular edge color durante l&#39;importazione
* &amp;lbrack;UI&amp;rbrack; Sostituisci il titolo del pannello con un&#39;icona
* &amp;lbrack;UI&amp;rbrack; aggiornamento stile campi di testo
* &amp;lbrack;UI&amp;rbrack; Nuovo testo descrittivo nella finestra di creazione del modello luce ambiente
* &amp;lbrack;Applicazione&amp;rbrack; Esporta le risorse con la risoluzione corrente durante l&#39;invio all&#39;applicazione esterna
* &amp;lbrack;Applicazione&amp;rbrack; la risoluzione predefinita del materiale è ora 2048\*2048 (1024\*1024 su macos)
* &amp;blocco;Contenuto&amp;rbrack; Nuovi pattern nel filtro Porzioni
* &amp;lbrack;Content&amp;rbrack; Nuovo metodo colore doppio nel filtro Sostituzione colore

**Corretto:**

* &amp;lbrack;2D View&amp;rbrack; Il primo tratto nello strumento Pennello a volte è interrotto
* &amp;lbrack;2D View&amp;rbrack; risorse gratuite quando lo strumento Pennello non è visibile
* &amp;lbrack;2D View&amp;rbrack; Utilizza il cursore di ridimensionamento destro nel widget della trasformazione
* &amp;lbrack;2D View&amp;rbrack; I widget non vengono visualizzati se l&#39;utente ha eseguito il panning nella vista 2D in precedenza
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante l’apertura di un progetto con flusso di lavoro interrotto
* &amp;lbrack;Application&amp;rbrack; Correggere l&#39;arresto dell&#39;applicazione per evitare che il registro venga inondato da errori inutili
* &amp;blocco;Applicazione&amp;rbrack; Ripristina, elimina e salva scelte rapide da tastiera non funzionano in alcuni sistemi operativi
* &amp;lbrack;Application&amp;rbrack; Annulla/Ripeti modifica utilizzo immagine nel livello di importazione è interrotto
* &amp;lbrack;Esporta&amp;rbrack; Il nome delle immagini esportate per il colore di emissione è errato
* &amp;lbrack;Export&amp;rbrack; Environment is 8bit when using SBSAR export
* &amp;lbrack;Esporta&amp;rbrack; Rimuovi gli spazi superflui nei nomi dei file immagine esportati
* &amp;blocco;Esporta&amp;rbrack; La sostituzione o l’eliminazione di un predefinito di esportazione personalizzato si arresta in modo anomalo
* &amp;lbrack;Layers&amp;rbrack; Evita l&#39;arresto anomalo quando il numero di input non corrisponde
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante l&#39;inserimento di un livello Materiale di base
* &amp;lbrack;Layers&amp;rbrack; Il conteggio input filtro è limitato al valore predefinito
* &amp;lbrack;Layers&amp;rbrack; Redo modifica erroneamente il tipo di fusione in fusione Height
* &amp;lbrack;Layers&amp;rbrack; Rimuovi zona di rilascio sopra le intestazioni di input
* &amp;lbrack;Livelli&amp;rbrack; I livelli vengono inseriti nella posizione errata attorno alle intestazioni di input
* &amp;lbrack;Layers&amp;rbrack; Il pulsante Ripristina tutte le impostazioni non reimposta i valori dei widget a discesa
* &amp;lbrack;Layers&amp;rbrack; Annulla/Ripeti quando si modifica un’immagine sul livello Importazione immagine, contrassegna il progetto come modificato e così via per salvarlo
* &amp;lbrack;Layers&amp;rbrack; Gli usi possono essere interrotti dai livelli di fusione
* &amp;lbrack;Project&amp;rbrack; Arresto anomalo durante il caricamento di un progetto precedente con cartella dipendenze mancante
* &amp;lbrack;Project&amp;rbrack; Arresto anomalo quando si utilizza Annulla/Ripeti dopo il salvataggio
* &amp;lbrack;Project&amp;rbrack; L&#39;apertura di un file SBSAR contenente una luce ambiente crea una risorsa materiale
* &amp;lbrack;Project&amp;rbrack; La ridenominazione di un materiale può attivare la generazione di miniature
* &amp;lbrack;Project&amp;rbrack; Il salvataggio dopo la ridenominazione di un materiale contrassegna il progetto come non modificato
* &amp;blocco;Progetto&amp;rblocco; Alcune modifiche dopo la ridenominazione di un materiale non vengono salvate
* &amp;lbrack;Rendering&amp;rbrack; i punti luminosi sono visibili nell&#39;ambiente con il motore in tempo reale del 2020
* &amp;lbrack;Rendering&amp;rbrack; Arresto anomalo durante il ridimensionamento con Real Time Engine 2021
* &amp;lbrack;Rendering&amp;rbrack; Ricalcola ombre alla modifica a livello di height
* &amp;lbrack;Risorse&amp;rbrack; Le cartelle connesse interrompono l&#39;indicizzazione delle nuove risorse quando si aggiunge un file non valido
* &amp;lbrack;Assets&amp;rbrack; Arresto anomalo durante la connessione di una cartella locale con molti materiali
* &amp;lbrack;UI&amp;rbrack; pulsanti di visualizzazione 2D/3D mancanti
* &amp;lbrack;UI&amp;rbrack; tutte le risorse nel pannello Risorse sono evidenziate all&#39;avvio
* &amp;lbrack;UI&amp;rbrack; Breadcrumbs a volte sparisce nel pannello Risorse durante l&#39;importazione dei materiali
* &amp;lbrack;UI&amp;rbrack; La modifica della lingua non influisce sul pannello Progetto
* &amp;lbrack;UI&amp;rbrack; il pannello Impostazioni canale mostra le informazioni sul flusso di lavoro precedente
* &amp;lbrack;UI&amp;rbrack; Allinea correttamente il testo &quot;Nessuna impostazione per questo elemento&quot; per i filtri senza modifiche nel pannello delle proprietà
* &amp;lbrack;UI&amp;rbrack; Gli elementi non sono allineati correttamente nella schermata di benvenuto e nel popup delle preferenze
* &amp;lbrack;UI&amp;rbrack; I titoli dei pannelli hanno una larghezza errata
* &amp;lbrack;UI&amp;rbrack; Lo scorrimento a volte è interrotto nel pannello Proprietà
* &amp;lbrack;UI&amp;rbrack; La schermata iniziale ha proporzioni errate ed è sfocata
* &amp;lbrack;UI&amp;rbrack; La modalità a schermo intero non è a schermo intero
* &amp;lbrack;UI&amp;rbrack; I pannelli non ancorati sono sempre in primo piano anche quando l&#39;applicazione non è attiva in MacOS
* &amp;lbrack;UI&amp;rbrack; Aggiorna immagine banner schermata di benvenuto
* &amp;lbrack;Content&amp;rbrack; Il filtro Porzione non elabora il canale di occlusione ambientale
* &amp;lbrack;Content&amp;rbrack; problema di unione superfici con la selezione della giuntura dell&#39;assieme di saldatura e il motivo a rombo
* &amp;lbrack;Content&amp;rbrack; Il filtro Rilievo funziona in 256 px per 256 px
* &amp;lbrack;Content&amp;rbrack; Risolvi il problema di affiancamento con le porzioni del pavimento quando lo scostamento è maggiore di 0

**Problemi noti:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Calcolo pesante, arresto anomalo dell&#39;applicazione
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021 verrà arresto anomalo su computer Windows con CPU AMD e GPU Nvidia

### 3.0.0 Waffle

*(Rilasciato il 23 giugno 2021)*

**Aggiunto:**

* &amp;lbrack;Branding&amp;rbrack; Substance Alchemist diventa Adobe Substance 3D Sampler
* &amp;lbrack;Branding&amp;rbrack; Icone di una nuova applicazione
* &amp;lbrack;UI&amp;rbrack; Nuova esperienza utente e interfaccia utente
* &amp;lbrack;UI&amp;rbrack; Nuova schermata iniziale
* &amp;lbrack;UI&amp;rbrack; I pannelli non sono ancorabili e ancorabili nell&#39;interfaccia
* &amp;lbrack;UI&amp;rbrack; ancorare fino a 3 pannelli nella stessa colonna
* &amp;lbrack;UI&amp;rbrack; ancorate fino a 3 pannelli nello stesso pannello (schede)
* &amp;lbrack;UI&amp;rbrack; Disancora i pannelli per creare una finestra separata nella stessa schermata o in una schermata diversa
* &amp;lbrack;UI&amp;rbrack; popup per pannelli chiusi quando si fa clic sulle relative icone
* &amp;lbrack;UI&amp;rbrack; ridisporre la barra sinistra e destra spostando le icone dei pannelli
* &amp;lbrack;UI&amp;rbrack; nuova barra degli strumenti per accedere a filtri specifici direttamente (Ritaglia, Trasforma, Prospettiva Trasforma, Clona /Clone timbro)
* &amp;lbrack;UI&amp;rbrack; Nuovo pulsante &quot;Ottieni contenuto&quot; nella barra a sinistra
* &amp;lbrack;UI&amp;rbrack; Importa i file direttamente nelle tue risorse con il pulsante Ottieni contenuto
* &amp;lbrack;UI&amp;rbrack; Importa i file direttamente nei tuoi livelli con il pulsante Ottieni contenuto
* &amp;lbrack;UI&amp;rbrack; Accedi direttamente al sito Web di Substance 3D Assets con il pulsante Ottieni contenuto
* &amp;lbrack;UI&amp;rbrack; Il widget Risoluzione è ora direttamente accessibile nella finestra della vista
* &amp;lbrack;UI&amp;rbrack; Tutti gli elementi dell&#39;interfaccia utente ora vengono caricati dinamicamente
* &amp;lbrack;UI&amp;rbrack; Scelta rapida da tastiera: utilizza &quot;2&quot; per attivare/disattivare la visibilità della Vista 2D
* &amp;lbrack;UI&amp;rbrack; Scelta rapida da tastiera: utilizza &quot;3&quot; per attivare/disattivare la visibilità della vista 3D
* &amp;lbrack;Schermata introduttiva&amp;brack; Crea un progetto con un clic con il pulsante Nuovo
* &amp;lbrack;Schermata introduttiva&amp;rbrack; Nuovo banner grafica
* &amp;blocco;Progetto&amp;rblocco; Tutti i progetti sono ora associati a un file univoco
* &amp;lbrack;Project&amp;rbrack; Nuova estensione file di progetto .ssa
* &amp;lbrack;Project&amp;rbrack; Salva come progetto ti chiederà di selezionare dove salvare il progetto
* &amp;lbrack;Project&amp;rbrack; se non viene salvato, alla chiusura di Sampler verrà richiesto di salvare il progetto
* &amp;lbrack;Project&amp;rbrack; Se si chiude Sampler, verrà richiesto di salvare il progetto se sono presenti modifiche dall&#39;ultimo salvataggio
* &amp;lbrack;Project&amp;rbrack; Il nome del progetto viene visualizzato sopra la finestra della vista
* &amp;lbrack;Project&amp;rbrack; Il nome del progetto è in corsivo con una stella se non viene salvato o se contiene modifiche dall&#39;ultimo salvataggio
* &amp;lbrack;Project&amp;rbrack; Apri un file di progetto .ssa direttamente da Esplora sistema operativo
* &amp;lbrack;Project&amp;rbrack; Apri un file .sbsar da Esplora sistemi operativi per avviare Sampler con un nuovo progetto con questo file .sbsar pronto per l&#39;uso
* &amp;lbrack;Project&amp;rbrack; Aprire un file .alch (file di Substance Alchemist legacy) dall&#39;esploratore del sistema operativo
* &amp;blocco;Pannello progetto&amp;rbrack; nuovo pannello che conterrà tutte le risorse create all’interno di un progetto
* &amp;lbrack;Pannello progetto&amp;rbrack; Crea una risorsa (materiale o luce ambiente) utilizzando l&#39;icona +
* &amp;blocco;Pannello progetto&amp;rbrack; facendo clic con il pulsante destro del mouse sulla risorsa si apre un menu di scelta rapida
* &amp;lbrack;Pannello progetto&amp;rbrack; Dal menu di scelta rapida, è possibile eliminare una risorsa
* &amp;lbrack;Pannello progetto&amp;rbrack; Dal menu di scelta rapida, è possibile duplicare una risorsa
* &amp;lbrack;Pannello progetto&amp;rbrack; Dal menu di scelta rapida, è possibile rinominare una risorsa
* &amp;lbrack;Pannello progetto&amp;rbrack; Il passaggio tra le risorse non perderà le modifiche
* &amp;lbrack;Resolution&amp;rbrack; Ora puoi impostare una risoluzione non quadrata per tutte le tue risorse
* &amp;lbrack;Resolution&amp;rbrack; Il valore di risoluzione viene salvato per risorsa all&#39;interno di un progetto
* &amp;lbrack;Luce ambientale&amp;rbrack; Creazione di luce ambientale in Substance 3D Sampler
* &amp;lbrack;Luce ambiente&amp;rbrack; Durante la creazione di una luce ambiente, trascinando e rilasciando le immagini verrà visualizzata la finestra Modello creazione luce ambiente
* &amp;lbrack;Environment Light&amp;rbrack; Nel modello Environment Light Creation, selezionare Environment Import (Importa ambiente) per assegnare l&#39;immagine all&#39;ambiente nella vista 3D
* &amp;lbrack;Luce ambiente&amp;rbrack; Nel modello Creazione luce ambiente, seleziona Unione HDR per creare una luce ambiente da diverse immagini a 360 gradi con esposizione diversa
* &amp;lbrack;Environment Light&amp;brack; Nel modello Environment Light Creation, selezionare &quot;Use as bitmap&quot; (Usa come bitmap) per modificare le immagini prima di creare una luce ambiente
* &amp;lbrack;Luce ambiente&amp;rbrack; Assegna l’utilizzo dell’ambiente nel livello Importazione immagine per assegnare direttamente l’immagine all’ambiente nella vista 3D
* &amp;lbrack;Luce ambiente&amp;rbrack; Nella vista 2D per il canale ambiente, è disponibile una correzione colore automatica che consente di visualizzare il rendering come nella vista 3D
* &amp;lbrack;Luce ambiente&amp;rbrack; nuovo contenuto dedicato per la creazione di luce ambiente
* &amp;lbrack;Pannello Risorse&amp;rbrack; i pannelli Risorse e Filtri vengono uniti in un nuovo pannello Risorse
* &amp;lbrack;Pannello Risorse&amp;rbrack; Il pannello Risorse ora supporta i seguenti tipi di risorse: materiali, filtri e immagini
* &amp;lbrack;Pannello Risorse&amp;rbrack; tutte le risorse per iniziare sono accessibili nella sezione Risorse per iniziare
* &amp;lbrack;Assets Panel&amp;rbrack; La sezione Starter Assets è di sola lettura
* &amp;blocca;Pannello Risorse; Nuova sezione &quot;Le tue risorse&quot;
* &amp;blocca;Pannello Risorse&amp;Rbrack; &quot;Le tue risorse&quot; è la sezione in cui puoi importare tutte le tue risorse
* &amp;lbrack;Pannello Risorse&amp;rbrack; Tutte le risorse in &quot;Le tue risorse&quot; vengono aggiunte in una cartella specifica nei tuoi documenti
* &amp;blocca;Pannello Risorse&amp;Rbrack; collega le cartelle locali nel pannello Risorse per aggiungere nuove sezioni
* &amp;lbrack;Pannello Risorse&amp;rbrack; La ricerca verrà eseguita nella cartella corrente e nelle relative sottocartelle
* &amp;blocco;Pannello risorse&amp;rbrack; Spostarsi tra cartelle e sottocartelle con spostamenti
* &amp;blocca;Pannello Risorse&amp;Rbrack; Filtra la cartella corrente per materiale, filtro o immagine
* &amp;lbrack;Assets Panel&amp;rbrack; Combina diversi filtri per ottenere solo materiali e immagini
* &amp;lbrack;Pannello Risorse&amp;rbrack; Cambia la visualizzazione passando da una griglia all’altra o da un elenco
* &amp;lbrack;Assets Panel&amp;rbrack; I filtri sono rappresentati con la relativa icona
* &amp;lbrack;Assets Panel&amp;rbrack; Le immagini sono rappresentate con la relativa anteprima
* &amp;lbrack;Pannello Risorse&amp;rbrack; Aumentando la larghezza si modifica il layout del pannello con una vista specifica per spostarsi tra le cartelle
* &amp;lbrack;Pannello Risorse&amp;rbrack; Nelle sezioni non di sola lettura, elimina una risorsa trascinandola sull’icona del raccoglitore
* &amp;blocca;Pannello risorse&amp;rbrack; facendo clic con il pulsante destro del mouse sulla risorsa si apre un menu di scelta rapida
* &amp;lbrack;Pannello risorse&amp;rbrack; Dal menu di scelta rapida, fare clic con il pulsante destro del mouse, accedere ai metadati della risorsa (nome, categoria, posizione)
* &amp;lbrack;Assets Panel&amp;rbrack; Dal menu di scelta rapida, eliminare la risorsa (disponibile solo nelle sezioni non di sola lettura)
* &amp;lbrack;Assets Panel&amp;rbrack; Dal menu di scelta rapida, sfoglia la risorsa in Adobe Bridge
* &amp;lbrack;Pannello Livelli&amp;rbrack; Icona Nuovo per aggiungere direttamente un materiale di base sopra i livelli
* &amp;lbrack;Layers Panel&amp;rbrack; Scelta rapida da tastiera - Maiusc + B aggiunge un materiale di base sopra i livelli
* &amp;lbrack;Pannello Livelli&amp;rbrack; I livelli ora hanno una miniatura di anteprima (miniatura materiale, icona filtro o anteprima immagine)
* &amp;blocco;Pannello Proprietà&amp;rbrack; Nuovo design del titolo del pannello Proprietà con il nome della risorsa e la relativa miniatura
* &amp;lbrack;Pannello Proprietà&amp;rbrack; I livelli filtro ora supportano i predefiniti
* &amp;lbrack;Pannello Proprietà&amp;rbrack; Nel livello di importazione immagine, fare clic con il pulsante destro del mouse sull&#39;anteprima immagine per modificare l&#39;immagine in Photoshop
* &amp;lbrack;Adobe Bridge&amp;rbrack; Sfoglia la tua risorsa in Adobe Bridge, avvierà Bridge nel percorso della risorsa
* &amp;lbrack;Adobe Photoshop&amp;rbrack; Modifica in Adobe Photoshop aprirà l&#39;immagine in Photoshop pronta per essere modificata
* &amp;lbrack;Adobe Photoshop&amp;rbrack; A ogni salvataggio in Adobe Photoshop, l&#39;immagine modificata verrà ricaricata in Sampler
* &amp;lbrack;Substance 3D Designer&amp;rbrack; Le risorse inviate da Adobe Substance 3D Designer arriveranno direttamente nella sezione &quot;Le tue risorse&quot; del pannello Risorse
* &amp;lbrack;Esporta&amp;rbrack; Invia risorse direttamente a Adobe Substance 3D Painter e Adobe Substance 3D Stager
* &amp;lbrack;Esporta&amp;rbrack; Invia materiali e luce ambientale ad Adobe Substance 3D Painter
* &amp;lbrack;Esporta&amp;rbrack; Invia luci ambiente ad Adobe Substance 3D Stager
* &amp;lbrack;Rendering&amp;rbrack; le nuove proprietà dei materiali sono ora supportate e renderizzate in 3D
* &amp;lbrack;Rendering&amp;rbrack; aggiunta di supporto per la brillantezza (Colore di lucentezza, opacità lucentezza e rugosità lucentezza)
* &amp;lbrack;Rendering&amp;rbrack; aggiunta del supporto per il rivestimento (colore del pelo, rugosità del pelo, normale del pelo, Specular level del pelo e rivestimento IOR)
* &amp;lbrack;Rendering&amp;rbrack; Aggiunta del supporto Anisotropie (livello Anisotropia e angolo Anisotropia)
* &amp;lbrack;Rendering&amp;rbrack; Aggiunta del supporto Specular edge color
* &amp;lbrack;Rendering&amp;rbrack; Attiva queste nuove proprietà nel pannello Impostazioni canale
* &amp;lbrack;Rendering&amp;rbrack; Introduzione di un nuovo modulo di rendering in tempo reale (2021) in versione beta
* &amp;lbrack;Rendering&amp;rbrack; Passa da una versione all’altra del modulo di rendering nel pannello Impostazioni visualizzatore
* &amp;lbrack;Rendering&amp;rbrack; Il modulo di rendering in tempo reale (2021) supporta le proprietà traslucidità, assorbimento e dispersione del materiale
* &amp;lbrack;Rendering&amp;rbrack; Il modulo di rendering in tempo reale (2021) introduce un nuovo modo per calcolare le ombre dalla luce ambientale
* &amp;lbrack;Rendering&amp;rbrack; Il modulo di rendering in tempo reale (2021) calcola in tempo reale l’irradianza della luce ambiente
* &amp;lbrack;Pannello Impostazioni shader&amp;rbrack; Nuovo pannello Impostazioni shader per modificare parametri specifici dello shader di materiale
* &amp;lbrack;Shader Settings Panel&amp;rbrack; Nuovi parametri (Scala normale, Scala height, Livello height, Intensità di emissione, IOR, Intensità normale rivestimento e Coat IOR)
* &amp;lbrack;Shader Settings Panel&amp;rbrack; Parametri specifici per il motore in tempo reale 2021 (dispersione sottosuperficie, distanza di dispersione, spostamento rosso e dispersione Rayleigh)
* &amp;lbrack;Shader Settings Panel&amp;rbrack; I valori delle impostazioni vengono salvati per risorsa
* &amp;lbrack;Viewer Settings Panel&amp;rbrack; Ha aggiunto un&#39;anteprima delle luci ambientali predefinite
* &amp;lbrack;Pannello impostazioni visualizzatore&amp;rbrack; ha aggiunto un&#39;anteprima delle trame predefinite
* &amp;lbrack;Pannello impostazioni visualizzatore&amp;rbrack; parametro opacità nuovo ambiente
* &amp;lbrack;Pannello Impostazioni visualizzatore&amp;rbrack; parametro per la sfocatura del nuovo ambiente (specifico per il modulo di rendering Realtime Engine 2021)
* &amp;lbrack;Localization&amp;rbrack; Nuove traduzioni in tedesco e francese
* &amp;lbrack;Content&amp;rbrack; Nuovi materiali di partenza predefiniti
* &amp;lbrack;Content&amp;rbrack; Nuove luci ambientali predefinite
* &amp;lbrack;Content&amp;rbrack; Tutti i filtri sono stati aggiornati, puliti e ottimizzati
* &amp;lbrack;Content&amp;rbrack; Il filtro Regolazione è stato suddiviso in diversi filtri
* &amp;lbrack;Content&amp;rbrack; nuovo filtro Luminosità/contrasto
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Tonalità/Saturazione
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Vividezza
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Nitidezza
* &amp;lbrack;Content&amp;rbrack; Nuova regolazione Normale/Height
* &amp;blocco;Content&amp;rbrack; filtro Nuovi pannelli
* &amp;blocco;Content&amp;rbrack; Nuovo filtro Sfumino
* &amp;blocco;Content&amp;rbrack; filtro Nuove trame
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Trasforma alterazione
* &amp;lbrack;Content&amp;rbrack; Nuovo Height per filtro AO
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro da Height a normale
* &amp;lbrack;Content&amp;rbrack; Color Replace: Sostituisci in nuovi canali supportati (brillantezza, rivestimento, Anisotropia,...)
* &amp;lbrack;Content&amp;rbrack; Variazione colore - Modalità manuale per selezionare esattamente i colori da modificare
* &amp;lbrack;Content&amp;rbrack; Affiancamento - opzione per visualizzare il taglio delle cuciture
* &amp;lbrack;Content&amp;rbrack; Affiancamento - opzione per pittura il taglio delle cuciture per un Affiancamento perfetto
* &amp;lbrack;Content&amp;rbrack; Match - opzione per aggiungere un materiale che corrisponda al suo colore e alla sua ruvidezza
* &amp;lbrack;Content&amp;rbrack; Match - ora funziona sulle immagini in modo che corrispondano al colore di un&#39;altra immagine
* &amp;lbrack;Content&amp;rbrack; luce ambiente - Nuovo filtro Temperatura colore
* &amp;lbrack;Content&amp;rbrack; Luce ambiente - Nuovo filtro Esposizione
* &amp;lbrack;Content&amp;rbrack; Luce ambiente - Nuovo filtro Anteprima esposizione
* &amp;lbrack;Content&amp;rbrack; luce ambiente - Nuovo filtro Nadir patch
* &amp;lbrack;Content&amp;rbrack; luce ambiente - Nuovo filtro Nadir extract
* &amp;lbrack;Content&amp;rbrack; Luce ambiente - Nuovi filtri Luci (Sfera, Linea, Forma, Piano)
* &amp;lbrack;Content&amp;rbrack; Luce ambiente - Nuovo filtro Toppa panorama
* &amp;lbrack;Content&amp;rbrack; Luce ambiente - Nuovo filtro Raddrizza orizzonte
* &amp;lbrack;Content&amp;rbrack; luce ambiente - Nuovo filtro unione HDR

**Problemi noti:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Modifica del layout, arresto anomalo dell&#39;applicazione
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Calcolo pesante, arresto anomalo dell&#39;applicazione
* &amp;lbrack;Panels&amp;rbrack; MacOS - I pannelli non ancorati sono in primo piano rispetto a tutte le applicazioni
* &amp;lbrack;Widget&amp;rbrack; I widget Trasforma e Posizioni possono scomparire. Nascondi e Mostra il livello per farli apparire.
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione SBSAR di una luce ambientale perde la precisione di 32profondità di bit
* &amp;lbrack;Pannello Risorse&amp;rbrack; Le risorse possono essere evidenziate all&#39;apertura di una cartella
* &amp;lbrack;Pannello proprietà&amp;rbrack; Il ripristino dei parametri non reimposta l&#39;interfaccia utente della casella combinata
* &amp;lbrack;Localization&amp;rbrack; La modifica della lingua non influisce sul pannello del progetto finché non viene ricreato

## Versione 2

### 2.3.2 (2020.3.2) Vermicelli

*(Rilasciato il 23 febbraio 2021)*

**Aggiunto:**

* &amp;lbrack;Localization&amp;rbrack; supporto giapponese

**Corretto:**

* &amp;lbrack;Livelli&amp;rbrack; se si modifica un materiale nel filtro ricamo, si perde l’immagine del ricamo

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.3.1 (2020.3.1) Vermicelli

*(Rilasciato il 17 dicembre 2020)*

**Aggiunto:**

* &amp;lbrack;Engine&amp;rbrack; aggiornamento Substance Engine
* &amp;lbrack;Application&amp;rbrack; variabile di ambiente per disabilitare funzioni specifiche
* &amp;lbrack;Content&amp;rbrack; Sostituisci colore - Nuova opzione di segmentazione avanzata
* &amp;blocco;Content&amp;rbrack; porzioni di Floor - sono disponibili nuovi pattern e opzioni
* &amp;lbrack;Content&amp;rbrack; Ricamo - Aggiornamento completo del filtro
* &amp;lbrack;Content&amp;rbrack; Adjustment - Nuovo parametro metallico + correzione Trasforma opacità sicura

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Impossibile importare due volte lo stesso filtro personalizzato
* &amp;lbrack;Layers&amp;rbrack; Impossibile utilizzare l&#39;input dell&#39;immagine con lo strumento pennello
* &amp;lbrack;Esporta&amp;rbrack; Esporta .jpg invece di .jpeg
* &amp;lbrack;UI&amp;rbrack; Aggiorna i crediti immagine della schermata di benvenuto
* &amp;lbrack;UI&amp;rbrack; Correggere il separatore invisibile nei menu
* &amp;lbrack;UI&amp;rbrack; I pulsanti di scelta visualizzano una descrizione comandi quando vengono troncati
* &amp;lbrack;UI&amp;rbrack; Errore: Materiali iniziali
* &amp;lbrack;Application&amp;rbrack; I caratteri UTF-8 nei nomi delle risorse non funzionano
* &amp;lbrack;Localization&amp;rbrack; Disattiva stile font corsivo per impostazioni internazionali cinesi
* &amp;lbrack;Localization&amp;rbrack; stringa localizzata divisa in 2 righe
* &amp;lbrack;Localization&amp;rbrack; Regola il nome della cartella e sostituiscilo con i puntini di sospensione se è troppo lungo
* &amp;lbrack;Localization&amp;rbrack; Formattare i numeri con il separatore delle migliaia
* &amp;lbrack;Localization&amp;rbrack; Localizza visualizzazione data e ora
* &amp;lbrack;Localization&amp;rbrack; Localizza selettore colore in Windows
* &amp;lbrack;Content&amp;rbrack; Trasforma - Con la trasformazione sicura attivata, la normale ruota correttamente ogni 45°
* &amp;lbrack;Content&amp;rbrack; Surface rilievo - Risolvere il problema di Affiancamento con disturbo frattale al perlino (disturbo avanzato)
* &amp;lbrack;Content&amp;rbrack; Brickwall Pattern - Input Height a 16 bit
* &amp;lbrack;Content&amp;rbrack; Rendering icona materiale - Problema di riflessi Specular
* &amp;lbrack;Content&amp;rbrack; Variazione colore - Nessun cambiamento di colore tra gli input di colore e il risultato
* &amp;lbrack;Content&amp;rbrack; Variazione colore - Aggiornamento prestazioni

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.3.0 (2020.3.0) Vermicelli

*(Rilasciato il 26 ottobre 2020)*

**Aggiunto:**

* &amp;lbrack;Da immagine a materiale&amp;rbrack; supporto della serie NVIDIA RTX 3000
* &amp;lbrack;Da immagine a materiale&amp;rbrack; nuovi parametri per controllare i dettagli della geometria
* &amp;lbrack;Da immagine a materiale&amp;rbrack; nuovi parametri per controllare la rugosità
* &amp;lbrack;Da immagine a materiale&amp;rbrack; nuovi parametri per controllare l&#39;intensità della luce
* &amp;lbrack;Thumbnails&amp;rbrack; nuovo generatore di miniature basato sul modulo di rendering PBR di Substance Designer
* &amp;lbrack;Thumbnails&amp;rbrack; Aggiorna materiali di base e atlanti per incorporare la loro miniatura
* &amp;lbrack;Thumbnails&amp;rbrack; Recupera la miniatura dal file .sbsar, se presente
* &amp;lbrack;Thumbnails&amp;rbrack; Modificare la qualità delle miniature nelle Preferenze
* &amp;lbrack;Engine&amp;rbrack; aggiornato alla versione di Substance Engine 8
* &amp;lbrack;Localization&amp;rbrack; localizzazione cinese
* &amp;lbrack;UI&amp;rbrack; Selettore tinte piatte sperimentale
* &amp;lbrack;Content&amp;rbrack; Nuova mappa ambiente - Studio 06
* &amp;blocco;Content&amp;rbrack; Aggiungi filtro Generatore Atlas
* &amp;lbrack;Content&amp;rbrack; Aggiungi filtro Atlas splitter
* &amp;blocco;Content&amp;brack; Aggiungi filtro Gomme scartate
* &amp;lbrack;Content&amp;rbrack; Aggiungi filtro Impronte digitali
* &amp;lbrack;Content&amp;rbrack; Aggiungi filtro Scratches
* &amp;lbrack;Content&amp;rbrack; Aggiungi filtro Rilievo superficie (sostituisci filtro modulazione height)
* &amp;blocco;Contenuto&amp;rbrack; Aggiungi filtro Altera
* &amp;blocco;Content&amp;brack; Aggiungi filtro Inverti
* &amp;blocco;Contenuto&amp;rbrack; Aggiungi filtro Colorazione
* &amp;blocco;Content&amp;rbrack; Aggiungi filtro Sostituisci colore
* &amp;lbrack;Content&amp;rbrack; Transform: consente di disattivare la trasformazione su un canale specifico.
* &amp;lbrack;Content&amp;rbrack; Trasforma - Aggiungi rotazione quando è attivata la Trasforma sicura
* &amp;lbrack;Content&amp;rbrack; Color Variation - Aggiunge un&#39;opzione di segmentazione per scegliere come distribuire i colori

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Aggiorna correttamente l&#39;interfaccia utente quando si eseguono più azioni di annullamento/ripetizione
* &amp;lbrack;Layers&amp;rbrack; Impedisce arresti anomali quando si eseguono più azioni di annullamento/ripetizione
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si utilizza Image to Material (AI Powered), con registro: numero ordinale dispositivo non valido
* &amp;lbrack;Filters&amp;rbrack; Migliora il rilevamento della scheda grafica NVIDIA per le funzioni specifiche di NVidia
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo alla chiusura dell&#39;applicazione
* &amp;lbrack;Application&amp;rbrack; Correggere il rilevamento della quantità di VRAM in MacOS
* &amp;lbrack;Esporta&amp;rbrack; Alcuni predefiniti di esportazione a volte mancanti
* &amp;lbrack;Content&amp;rbrack; Effetto Dipinto a olio - Correggi intervallo height con ampiezza spostamento elevata
* &amp;lbrack;Content&amp;rbrack; Make It Tile Advanced - Nessun colore di base sbiadito durante l&#39;esportazione
* &amp;lbrack;Content&amp;rbrack; Crea porzione avanzata - Maschera bianca sul colore di base quando l&#39;AO è troppo forte
* &amp;lbrack;Content&amp;rbrack; Adjustment: ora funziona sulle immagini (scan1, ...)

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte lo stesso stack di livelli di materiale

### 2.2.1 (2020.2.1) Udon

*(Rilasciato il 21 luglio 2020)*

**Aggiunto:**

* &amp;lbrack;Layers&amp;rbrack; In App Messaggio di errore quando la memoria di Image to Material (basata su IA) è esaurita

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Image to Material (Basato sull&#39;intelligenza artificiale) non funziona con i flussi di lavoro Specular/lucidità
* &amp;lbrack;Layers&amp;rbrack; Si arresta in modo anomalo quando la memoria video è esaurita durante l&#39;utilizzo di Image to Material (basato su IA)
* &amp;lbrack;Layers&amp;rbrack; La cache del disco non viene utilizzata per la visualizzazione durante l&#39;apertura di una pila
* &amp;lbrack;Layers&amp;rbrack; Rilevamento di Nvidia RTX 8000
* &amp;lbrack;Livelli&amp;rbrack; a volte è impossibile spostare un livello all’esterno di un input di tipo splatter
* &amp;lbrack;Layers&amp;rbrack; La cache del disco non viene utilizzata quando si inserisce una pila in una pila
* &amp;lbrack;Layers&amp;rbrack; Alcuni utilizzi dei canali vengono calcolati anche se non vengono utilizzati
* &amp;lbrack;Layers&amp;rbrack; Gli output vuoti vengono talvolta creati durante l&#39;importazione delle immagini
* &amp;lbrack;2D View&amp;rbrack; Passaggio a un altro livello con la modalità Disegno attiva blocchi panning e zoom
* &amp;lbrack;Content&amp;rbrack; Snow - Problema a 8 bit sulla mappa normale
* &amp;lbrack;Content&amp;rbrack; Pattern pavimentazione - Problema di 8 bit sulla mappa normale
* &amp;lbrack;Content&amp;rbrack; Equalizzatore - Problema di 8 bit sulla mappa normale
* &amp;lbrack;Content&amp;rbrack; Gravel Generator - Problema di 8 bit sulla mappa normale
* &amp;blocco;Content&amp;rbrack; Porzioni Floor - Gestisce opacità e specular level
* &amp;lbrack;Content&amp;rbrack; I cicli di fusione hanno sempre un predefinito di esportazione - inverti mappa normale
* &amp;lbrack;Content&amp;rbrack; Correggere il problema con immagini di grandi dimensioni con Image to Material (basata su IA)
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si sceglie &quot;Backup e riavvio&quot; in caso di errore del database
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando si fa clic rapidamente sulla stessa risorsa
* &amp;lbrack;Application&amp;rbrack; arresti anomali rari all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante l&#39;eliminazione di file nella schermata di benvenuto
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo quando viene caricato un file di ambiente danneggiato
* &amp;lbrack;Application&amp;rbrack; arresto anomalo raro quando si cambia rapidamente risorsa di rendering
* &amp;blocco;Applicazione&amp;blocco; Blocco quando si esce durante l&#39;elaborazione di una risorsa
* &amp;lbrack;Application&amp;rbrack; arresto anomalo raro all&#39;avvio su macos
* &amp;lbrack;Application&amp;rbrack; Deadlock alla chiusura dell&#39;applicazione subito dopo l&#39;avvio
* &amp;lbrack;Rendering&amp;rbrack; a volte la vista 3D sfarfalla
* &amp;lbrack;UI&amp;rbrack; Il selettore colore e i widget di inizializzazione casuale non sono allineati con il resto delle modifiche
* &amp;lbrack;Rendering&amp;rbrack; Tempo di calcolo errato visualizzato
* &amp;lbrack;Esporta&amp;rbrack; Alcuni predefiniti di esportazione a volte mancanti

**Problemi noti:**

* L&#39;utilizzo di Image to Material (AI) su immagini ad alta risoluzione può risultare lento
* Arresti anomali più gradevoli con driver NVIDIA meno recenti (meno di 400.x)
* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Impossibile salvare due volte la stessa identica Pila livelli di materiale

### 2.2.0 (2020.2.0) Udon

*(Rilasciato il 15 giugno 2020)*

**Aggiunto:**

* &amp;lbrack;Create&amp;rbrack; Filtro Nuova immagine-materiale (basato sull&#39;intelligenza artificiale) disponibile su Windows e Linux
* &amp;lbrack;Crea&amp;rbrack; Rinomina bitmap in Materiale in Immagine in Materiale (B2M)
* &amp;blocco;Importa immagine&amp;rbrack; finestra a comparsa Nuovo modello di creazione materiale
* &amp;lbrack;Image Import&amp;rbrack; New &quot;Add a materiale di base&quot; (Aggiungi )
* &amp;lbrack;Image Import&amp;rbrack; Possibilità di trascinare e rilasciare immagini aggiuntive nel modello di creazione di materiali
* &amp;lbrack;Image Import&amp;rbrack; Possibilità di rimuovere immagini nel modello di creazione materiale
* &amp;lbrack;Image Import&amp;rbrack; Assegna automaticamente il canale alle bitmap importate in base al nome file
* &amp;lbrack;Image Import&amp;rbrack; Possibilità di invertire la mappa normale
* &amp;lbrack;vista 2D&amp;rbrack; Introduzione di una modalità di pittura
* &amp;lbrack;vista 2D&amp;rbrack; Le porzioni di pittura
* &amp;lbrack;vista 2D&amp;rbrack; Imposta un valore in scala di grigi per il colore del pennello
* &amp;lbrack;vista 2D&amp;rbrack; Panning e zoom durante il disegno
* &amp;lbrack;2D View&amp;rbrack; scelta rapida X per invertire il valore della scala di grigi del pennello
* &amp;lbrack;vista 2D&amp;rbrack; &amp;lbrack; e &amp;rbrack; scelte rapide per modificare la dimensione del pennello
* &amp;lbrack;vista 2D&amp;rbrack; Ctrl (o Cmd) + Rotellina del mouse per modificare la dimensione del pennello
* &amp;lbrack;vista 2D&amp;rbrack; È ora possibile modificare la posizione di origine quando si utilizza Clona /Clone patch
* &amp;lbrack;Livelli&amp;rbrack; Maiusc + trascina per dispersione automatica atlanti
* &amp;lbrack;Layers&amp;rbrack; Alt + trascinamento inserisce un materiale come decalcomania
* &amp;lbrack;Layers&amp;rbrack; Esporre facilmente le matrici di trasformazione dal Substance Designer
* &amp;lbrack;Livelli&amp;rbrack; L&#39;eliminazione di texture in una pila non vuota viene assegnata automaticamente ai canali corretti
* &amp;lbrack;Livelli&amp;rbrack; Nuovo tipo di livello: Filtri composti
* &amp;lbrack;Parametri&amp;rbrack; supporto input stringa Substance
* &amp;lbrack;UI&amp;rbrack; ha aggiunto ombre esterne per popup e menu
* &amp;lbrack;UI&amp;rbrack; nuovo widget a colori con opzioni di clic con il pulsante destro del mouse (cancella, copia, incolla)
* &amp;lbrack;UI&amp;rbrack; nuovo widget immagine con opzione strumento di pittura
* &amp;lbrack;UI&amp;rbrack; Possibilità di colorare su un&#39;immagine importata in un widget di immagine
* &amp;lbrack;Rendering&amp;rbrack; Nuova posizione videocamera predefinita
* &amp;lbrack;Export&amp;rbrack; i file di Substance vengono esportati per Substance Designer 2020.1.2 (10.1.2)
* &amp;lbrack;Prestazioni&amp;rbrack; tempo di avvio migliore dell&#39;applicazione
* &amp;lbrack;Prestazioni&amp;rbrack; Miglioramento della gestione delle attività asincrone
* &amp;lbrack;Prestazioni&amp;rbrack; migliora le prestazioni dello stack di livelli quando si aggiungono, si rimuovono o si spostano livelli
* &amp;lbrack;Performance&amp;rbrack; Da immagine a materiale (basata su IA) funziona più velocemente sulle GPU RTX
* &amp;nero;Content&amp;brack; Nuove trame: T-Shirt femmina, T-Shirt maschio, Scarpa
* &amp;lbrack;Content&amp;rbrack; Nuovo Metodo Fusione - Per Fusione Canale
* &amp;lbrack;Content&amp;rbrack; Opacità fonde la correzione del height con 2 nuovi parametri (posizione height e scala height)
* &amp;lbrack;Content&amp;rbrack; Aggiungi regolazioni Height nel metodo di fusione Height
* &amp;lbrack;Content&amp;rbrack; Usa informazioni Height opzione nella fusione maschera personalizzata
* &amp;blocco;Content&amp;rbrack; Nuovo strumento di correzione prospettiva
* &amp;lbrack;Content&amp;rbrack; Generatore pattern - Aggiunge un parametro per invertire il pattern
* &amp;lbrack;Content&amp;rbrack; Generatore pattern - Aggiungi un nuovo parametro Ignora dettagli materiale
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro decalcomania
* &amp;blocco;Content&amp;rbrack; Nuovo filtro Moss
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Crepe
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro PBR Validata
* &amp;blocco;Content&amp;rbrack; filtro Nuove porzioni pavimento
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro Adesivo unione superfici
* &amp;lbrack;Content&amp;rbrack; Atlas scatter - Aggiungi input maschera personalizzata per abilitare l&#39;opzione di pittura
* &amp;lbrack;Content&amp;rbrack; Dirt - Aggiungi input maschera personalizzata per abilitare l&#39;opzione di pittura
* &amp;lbrack;Content&amp;rbrack; predefinito di esportazione CLO
* &amp;blocco;Content&amp;rbrack; VStitcher export preset
* &amp;lbrack;Content&amp;rbrack; i predefiniti HDRP di unità esportano un dettaglioMap

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Le immagini importate vengono caricate troppe volte
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante la creazione di una patch clone nella parte inferiore della pila
* &amp;lbrack;Livelli&amp;rbrack; L&#39;aggiunta di un materiale nella parte inferiore della pila lo rende instabile
* &amp;lbrack;Layers&amp;rbrack; Il filtro dopo l&#39;importazione dell&#39;immagine non funziona correttamente
* &amp;lbrack;Layers&amp;rbrack; workflow_type non viene aggiornato quando si passa da un progetto all&#39;altro con un filtro personalizzato
* &amp;blocca;Livelli&amp;rbrack; disabilita il pulsante &quot;rimuovi livello&quot; quando non è selezionato alcun livello
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante il caricamento di una risorsa contenente una patch Clona /Clone
* &amp;lbrack;Layers&amp;rbrack; Normale agli arresti anomali del filtro Height in MacOs
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante il caricamento delle mappe dell&#39;ambiente
* &amp;lbrack;Application&amp;rbrack; problemi di prestazioni quando è installato un driver di tavoletta grafica
* &amp;lbrack;Application&amp;rbrack; i file EXR a 32 bit importati sono neri
* &amp;lbrack;Application&amp;rbrack; Arresti anomali durante il caricamento e lo scaricamento delle risorse
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante il passaggio da esplora a crea
* &amp;lbrack;Application&amp;rbrack; Raccolta di destinazione durante il salvataggio di un materiale non appartenente al progetto corrente
* &amp;lbrack;Application&amp;rbrack; correggere backup e riavvio
* &amp;lbrack;Image Import&amp;rbrack; Importa correttamente immagini in scala di grigio
* &amp;lbrack;Content&amp;rbrack; nuovi filtri per la gestione delle nuove matrici
* &amp;lbrack;Content&amp;rbrack; I filtri personalizzati importati sono visibili nella barra di accesso rapido
* &amp;blocco;Contenuto&amp;rbrack; Correggere lo scostamento del colore con il filtro Avanzate Porre affiancato
* &amp;lbrack;Performance&amp;brack; l&#39;apertura di una finestra di dialogo di colore è lenta e ricalcola il livello corrente
* &amp;lbrack;UI&amp;rbrack; Le scelte rapide da tastiera a volte non funzionano
* &amp;lbrack;2D View&amp;rbrack; Riempimento in base al contenuto richiede un inutile primo clic per funzionare
* &amp;lbrack;Resources&amp;rbrack; Le cartelle nei dischi locali vengono ancora controllate per verificare la disponibilità di aggiornamenti dopo la rimozione
* &amp;blocco;Risorse&amp;blocco; L&#39;eliminazione di una cartella collegata dal file system non comporta la rimozione
* &amp;lbrack;Esporta&amp;rbrack; Gli usi personalizzati nei predefiniti di esportazione personalizzati non vengono esportati
* &amp;lbrack;Esporta&amp;rbrack; l&#39;esportazione del file .sbsar con caratteri speciali nel percorso non riesce

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

* &amp;blocco;Project&amp;rbrack; Esportare e importare metadati
* &amp;lbrack;Application&amp;rbrack; CTRL+S salva ora un predefinito in Esplora
* &amp;lbrack;Performance&amp;rbrack; utilizza la cache di rendering invece di ricalcolare i materiali salvati per risoluzioni fino a 2k

**Corretto:**

* &amp;lbrack;UI&amp;rbrack; Indicatore di calcolo fisso nella finestra della vista
* &amp;lbrack;UI&amp;rbrack; l&#39;immissione di valori negativi nei cursori è fissa
* &amp;lbrack;UI&amp;rbrack; Caselle combinate: le frecce della tastiera e la barra di scorrimento ora funzionano
* &amp;lbrack;UI&amp;rbrack; Mantiene il canale selezionato quando si passa da &quot;Output materiale&quot; a &quot;Input livello&quot; nella vista 2D
* &amp;lbrack;Layers&amp;rbrack; Risolto l&#39;arresto anomalo durante l&#39;aggiunta di canali personalizzati nel Materiale di base
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo durante la manipolazione dei livelli
* &amp;lbrack;Livelli&amp;rbrack; i canali personalizzati non vengono visualizzati con un materiale salvato
* &amp;lbrack;Application&amp;rbrack; Risolto l&#39;arresto anomalo raro durante l&#39;importazione di una risorsa
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; Le caselle combinate ora mostrano i valori corretti quando si cambiano i predefiniti
* &amp;laback;Export&amp;brack; Predefinito Enscape rinominato in Enscape Revit
* &amp;lbrack;Esporta&amp;rbrack; L&#39;importazione di un predefinito di esportazione dopo la rimozione funziona
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo all&#39;esportazione
* &amp;lbrack;Rendering&amp;rbrack; Rendering fisso quando il colore di base è in formato a metà virgola mobile a 16 bit
* &amp;lbrack;Project&amp;rbrack; Non arrestarsi in modo anomalo durante l&#39;importazione di un pacchetto danneggiato
* &amp;lbrack;Project&amp;rbrack; migrazione da Handle 2019.1.4 a 2.x.x quando la funzione Crea non è mai stata aperta
* &amp;lbrack;Project&amp;rbrack; Correggere un arresto anomalo durante l&#39;importazione dello stesso progetto due volte
* &amp;blocco;Project&amp;rbrack; Correggere un arresto anomalo durante l&#39;importazione dei progetti
* &amp;lbrack;Resources&amp;rbrack; I filtri personalizzati importati nelle versioni precedenti funzionano
* &amp;lbrack;Resources&amp;rbrack; I materiali con lo stesso nome non si cancellano più a vicenda
* &amp;lbrack;Resources&amp;rbrack; Arresto anomalo durante il collegamento di una cartella locale
* &amp;lbrack;Resources&amp;rbrack; le cartelle create dall&#39;utente per Materiali Starter non vengono più rimosse dopo un riavvio
* &amp;lbrack;Inspire&amp;rbrack; Correggi area di rilascio materiale/raccolta e aggiungi un messaggio di avviso se si utilizza un materiale non salvato

**Problemi noti:**

* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

### 2.1.0 (2020.1.0) Tiramisu

*(Rilasciato il 12 marzo 2020)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Esporta selezione predefinita per comprimere la texture per i moduli di rendering e i motori grafici
* &amp;lbrack;Export&amp;rbrack; Esporta predefinito su Unreal Engine 4
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito in Unity Standard
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito in Unity HDRP
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito in Cicli fusione/Evento
* &amp;lbrack;Export&amp;rbrack; Esporta predefinito in Arnold 5
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito nel modulo di rendering Corona
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito su Enscape
* &amp;lbrack;Export&amp;rbrack; Esporta predefinito in Keyshot 9
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito su Redshift
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito su Vray Next
* &amp;lbrack;Export&amp;rbrack; Esporta predefinito in Lens Studio
* &amp;lbrack;Export&amp;rbrack; Esporta predefinito in Spark AR Studio
* &amp;lbrack;Esporta&amp;rbrack; Esporta predefinito in Lucentezza Specular PBR dalla Rugosità metallica PBR
* &amp;blocco;Esporta&amp;rbrack; Nuova interfaccia utente di esportazione
* &amp;blocco;Esporta&amp;rback; Ricorda impostazioni di esportazione
* &amp;blocco;Esporta&amp;rbrack; Importa e gestisci i predefiniti di esportazione personalizzati
* &amp;blocco;Esporta&amp;rbrack; Elimina e sostituisci i predefiniti di esportazione personalizzati
* &amp;lbrack;Esporta&amp;rbrack; Rinomina i predefiniti di esportazione personalizzati
* &amp;lbrack;Esporta&amp;rbrack; Imposta la risoluzione di esportazione predefinita sulla risoluzione corrente
* &amp;lbrack;Esporta&amp;rbrack; Aggiungi la scelta per creare una sottocartella al percorso di esportazione
* &amp;blocco;Esporta&amp;rbrack; Messaggio di avvertenza prima di sostituire i file esistenti
* &amp;lbrack;Application&amp;rbrack; Nuovo schema di numerazione delle versioni
* &amp;lbrack;Application&amp;rbrack; Apri Crea all&#39;avvio e cambia l&#39;ordine dei laboratori
* &amp;blocco;Schermata introduttiva&amp;bra; Nuovo banner di benvenuto
* &amp;lbrack;Project&amp;rbrack; Apri l&#39;ultimo progetto all&#39;avvio
* &amp;lbrack;UI&amp;rbrack; Nuovo stile casella combinata
* &amp;lbrack;Vista 2D&amp;rbrack; F scelta rapida da tastiera da attivare nella vista 2d
* &amp;lbrack;Filters&amp;rbrack; Supporto aggiunto per alchemist::parameterVisibility tag nei grafici a Substance
* &amp;lbrack;Filters&amp;rbrack; Dispone di un&#39;impostazione globale per gestire la visibilità dei parametri in base al flusso di lavoro
* &amp;lbrack;Resources&amp;rbrack; Nuova opzione della riga di comando per configurare risorse e cartelle collegate con un file di configurazione
* &amp;lbrack;Verifica versione&amp;rbrack; Configurazione del controllo delle versioni
* &amp;lbrack;Content&amp;rbrack; Nuovi materiali per iniziare
* &amp;lbrack;Content&amp;rbrack; Bitmap to Material - Aggiungi la possibilità di definire il canale metallico (uniforme, importazione immagine personalizzata, selezione colore)
* &amp;lbrack;Content&amp;rbrack; Adjustment - Aggiunge il supporto del flusso di lavoro specular/lucentezza PBR
* &amp;lbrack;Content&amp;rbrack; Atlas scatter - Nuovi parametri

**Corretto:**

* &amp;lbrack;Project&amp;rbrack; Arresto anomalo durante l&#39;importazione dello stesso progetto due volte
* &amp;lbrack;Project&amp;rbrack; arresto anomalo corretto durante l&#39;importazione e l&#39;apertura di progetti più volte
* &amp;lbrack;Application&amp;rbrack; Arresto anomalo durante il caricamento di un materiale senza nome
* &amp;lbrack;Application&amp;rbrack; Riconosci i file mancanti quando li reimporta
* &amp;lbrack;Application&amp;rbrack; Correggi arresto anomalo casuale all&#39;arresto
* &amp;lbrack;Application&amp;rbrack; arresto anomalo raro fisso quando si scarica un materiale in Create
* &amp;lbrack;Application&amp;rbrack; arresto anomalo casuale fisso quando si utilizzano controlli dell&#39;interfaccia utente
* &amp;lbrack;Application&amp;rbrack; Corretta esportazione dei file di registro sul desktop in Windows 10
* &amp;lbrack;UI&amp;rbrack; la dimensione del pannello di esportazione non è corretta quando lo si apre in Crea
* &amp;lbrack;UI&amp;rbrack; Apri il progetto con un solo clic
* &amp;lbrack;UI&amp;rbrack; Imposta correttamente i valori minimo e massimo del cursore
* &amp;lbrack;UI&amp;rbrack; Mostra l&#39;etichetta degli usi del canale invece degli ID
* &amp;lbrack;UI&amp;rbrack; Facendo clic su un materiale si apre/chiude sempre il pannello di regolazione
* &amp;lbrack;UI&amp;rbrack; Correggi colori livelli nascosti
* &amp;lbrack;UI&amp;rbrack; miglioramenti ai pulsanti della schermata iniziale
* &amp;lbrack;Livelli&amp;rbrack; meno ricalcoli non necessari
* &amp;lbrack;Layers&amp;rbrack; Si Arresta In Modo Anomalo Quando Si Utilizza Patch Clone
* &amp;lbrack;Livelli&amp;rbrack; La selezione di un livello di importazione immagine non attiva più un calcolo
* &amp;lbrack;Layers&amp;rbrack; Clona /Clone i livelli di Riempimento in base al contenuto non vengono più ricalcolati quando sono selezionati
* &amp;lbrack;Impostazioni canale&amp;rbrack; L’attivazione o la disattivazione degli usi ora attiva un rendering
* &amp;blocca;Risorse&amp;blocca; impedisce il blocco quando si fa clic su una pila nella libreria
* &amp;lbrack;Resources&amp;rbrack; Prestazioni raggiunte quando si aggiunge nuovamente una cartella collegata aggiunta in precedenza
* &amp;lbrack;Resources&amp;rbrack; È stato risolto un arresto anomalo durante il tentativo di aprire un file .sbsar eliminato.
* &amp;lbrack;Prestazioni&amp;rbrack; Evita di caricare materiali per accedere ai relativi parametri
* &amp;lbrack;Performance&amp;brack; Backup delle risorse solo se utilizzate in un progetto o in un materiale creato
* &amp;lbrack;Esporta&amp;rbrack; I materiali fissi nella coda di esportazione a volte vengono saltati o esportati con parametri errati
* &amp;lbrack;vista 2D&amp;rbrack; Panning e zoom ripristinati
* &amp;lbrack;Content&amp;rbrack; Il pattern parquet tiene conto del canale di Occlusione ambientale
* &amp;lbrack;Content&amp;rbrack; Pittura - Visualizza l&#39;input della maschera quando si abilita la maschera personalizzata
* &amp;lbrack;Content&amp;rbrack; Stonewall Pattern - Rimuovi possibili effetti di striatura nella mappa normale
* &amp;lbrack;Content&amp;rbrack; Modulazione Height - Correggere le doppie voci di colore di base nella vista 2d

**Problemi noti:**

* I filtri Riempimento in base al contenuto sono lenti in alta risoluzione
* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore

## Versione 1

### 1.1.4 (2019.1.4) Sesamo

*(Rilasciato: 30 gennaio 2020)*

**Aggiunto:**

* &amp;blocco;Resources&amp;rbrack; Richiesta di conferma durante la cancellazione di una cartella di risorse

**Corretto:**

* &amp;blocca;Livelli&amp;rbrack; sposta i livelli in due o più livelli sottostanti o superiori
* &amp;lbrack;Create&amp;rbrack; allocazione di un budget VRAM sufficiente per ottenere buone prestazioni

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

* &amp;blocco;Workflow&amp;rbrack; supporto di più flussi di lavoro
* &amp;lbrack;Workflow&amp;rbrack; supporto del flusso di lavoro di Lucentezza degli Specular PBR
* &amp;blocco;Workflow&amp;rbrack; nuovo pannello Impostazioni canale
* &amp;lbrack;Workflow&amp;rbrack; selezione del flusso di lavoro alla creazione del progetto
* &amp;lbrack;Impostazioni canale&amp;rbrack; Attiva/Disattiva calcolo canale specifico
* &amp;lbrack;Impostazioni canale&amp;rbrack; Visualizza l&#39;elenco dei canali personalizzati disponibili nel materiale corrente
* &amp;lbrack;Impostazioni canale&amp;rbrack; calcolo automatico dei canali personalizzati quando necessario
* &amp;lbrack;Impostazioni canale&amp;rbrack; Forza/Blocca calcolo canali personalizzati
* &amp;lbrack;Layers&amp;rbrack; Nuova interfaccia utente del segnaposto di input materiale nei filtri Atlas scatter e Frazionamento
* &amp;lbrack;Layers&amp;rbrack; Il parametro di input dell&#39;immagine di un filtro può essere alimentato dai livelli sottostanti
* &amp;lbrack;Layers&amp;rbrack; Visualizza una notifica quando alcuni livelli non sono aggiornati
* &amp;lbrack;Layers&amp;rbrack; possibilità di aggiornare alla versione più recente di livelli obsoleti tramite la notifica
* &amp;blocco;Project&amp;rbrack; Nuovi campi metadati durante la creazione del progetto
* &amp;lbrack;Inspire&amp;rbrack; le varianti generate sono specifiche di un progetto
* &amp;lbrack;vista 2D&amp;rbrack; Passa tra gli input e gli output dei livelli e gli output dei materiali
* &amp;lbrack;Schermata introduttiva&amp;rbrack; Aggiungi progetto di importazione (.alch), opzione
* &amp;lbrack;Preferenze&amp;rbrack; Nuova finestra Preferenze per impostare la posizione della cache e le impostazioni di privacy analitica
* &amp;blocco;UI&amp;rbrack; pulsanti Nuova interfaccia utente
* &amp;lbrack;Performance&amp;rbrack; miglioramento generale del sistema di parallelizzazione
* &amp;lbrack;Performance&amp;rbrack; ottimizzazione del numero di calcoli di materiale
* &amp;lbrack;Engine&amp;rbrack; aggiornamento Substance Engine
* &amp;lbrack;Framework&amp;rbrack; Aggiornamento a Qt 5.13
* &amp;lbrack;MacOS&amp;rbrack; miglioramenti globali del supporto di macOS Catalina
* &amp;lbrack;Content&amp;rbrack; Filtro di regolazione - Intensità normale e parametri inverti

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Annulla l&#39;impostazione del parametro Image Input quando si elimina il livello
* &amp;lbrack;Layers&amp;rbrack; Correggere un arresto anomalo quando si aggiunge un livello patch clone
* &amp;lbrack;Layers&amp;rbrack; Correggere alcuni arresti anomali quando si fondono livelli per impilare materiali in altri materiali di Pila livelli
* &amp;lbrack;Export&amp;rbrack; La selezione dei canali per l&#39;esportazione è ora rispettata
* &amp;lbrack;Resources&amp;rbrack; Non eseguire l&#39;arresto anomalo durante la navigazione nel pannello Risorse
* &amp;lbrack;Resources&amp;rbrack; Correggere l&#39;arresto anomalo durante l&#39;importazione di file di Substance danneggiati
* &amp;lbrack;Resources&amp;rbrack; Riduzione del numero di arresti anomali durante il caricamento di cartelle di grandi dimensioni
* &amp;lbrack;Thumbnail&amp;rbrack; Il calcolo delle miniature non blocca l&#39;interfaccia
* &amp;lbrack;Image Import&amp;rbrack; uniformizzazione del tipo di immagine supportata nell&#39;applicazione
* &amp;lbrack;Preset&amp;rbrack; Salva la descrizione durante la creazione di un predefinito da un SBSAR
* &amp;laback;Ispirazione&amp;brack; Correggi trascinamento immagine
* &amp;lbrack;Application&amp;rbrack; Correggi arresti anomali all&#39;uscita
* &amp;lbrack;Application&amp;rbrack; Fix si arresta in modo anomalo all&#39;uscita durante l&#39;esportazione dei materiali
* &amp;lbrack;UI&amp;rbrack; correzioni e miglioramenti
* &amp;lbrack;UI&amp;rbrack; Rinomina risorsa temporanea in &quot;materiale non salvato&quot;
* &amp;lbrack;Content&amp;rbrack; Aggiornamento globale e pulizia di tutti i filtri

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

* &amp;lbrack;Layers&amp;rbrack; Le opzioni Salva e Salva con nome sono accessibili tramite l&#39;interfaccia nella barra degli strumenti della serie di livelli
* &amp;lbrack;Resources&amp;rbrack; Analisi dettagliata del pannello Risorse per spostarsi tra le cartelle
* &amp;blocca;Risorse&amp;blocca; pulsante Mantieni indietro premuto per accedere a tutte le cartelle superiori
* &amp;lbrack;Resources&amp;rbrack; Aggiungi opzione di ricaricamento dei materiali importati per aggiornarli alla versione più recente
* &amp;lbrack;Layers&amp;rbrack; Possibilità di modificare l&#39;immagine nel livello di importazione immagine
* &amp;lbrack;Livelli&amp;rbrack; possibilità di definire un&#39;immagine come canale (colore di base, normale, height,...) nel livello Importazione immagine
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Atlas scatter per dispersione nuovi elementi atlas da Substance Source
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro effetto Pittura a olio
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro di generazione canali per generare height, occlusione ambientale e rugosità da colore di base e mappa normale

**Corretto:**

* &amp;lbrack;UI&amp;rbrack; Riattiva le descrizioni comandi sulla barra degli strumenti dello stack Livelli
* &amp;lbrack;UI&amp;rbrack; risolvere il problema che si verifica quando si digitano due decimali in un valore del cursore
* &amp;lbrack;Performance&amp;rbrack; Correggi l&#39;arresto anomalo quando si passa rapidamente da un materiale all&#39;altro
* &amp;lbrack;Esporta&amp;rbrack; Il passaggio a un altro materiale prima della fine di un&#39;esportazione non subisce più l&#39;arresto anomalo
* &amp;lbrack;Resources&amp;rbrack; Il menu di scelta rapida viene visualizzato sopra il materiale quando si fa clic su di esso con il pulsante destro del mouse
* &amp;lbrack;Layers&amp;rbrack; Il collegamento &quot;Fai clic qui&quot; funziona quando la pila di livelli è vuota
* &amp;lbrack;Presets&amp;rbrack; Rimuovi il pulsante Salva nel pannello Tweak quando si tratta di un materiale creato in Alchemist
* &amp;lbrack;Tweak&amp;rbrack; Messaggio informativo visualizzato quando si tratta di un materiale creato in Alchemist
* &amp;lbrack;Viewport&amp;rbrack; il valore predefinito della texture di Specular level è corretto in 0,04
* &amp;laback;Menu file&amp;brack; opzione Correggi e rinomina Salva e Salva con nome
* &amp;lbrack;Engine&amp;rbrack; Aggiorna la versione del motore di Substance per evitare arresti anomali di alcuni file SBSAR durante l&#39;importazione.
* &amp;lbrack;Content&amp;rbrack; Il filtro Affiancamento funziona sul canale di occlusione ambientale
* &amp;lbrack;Content&amp;rbrack; Il filtro Ritaglio funziona sul canale di occlusione ambientale
* &amp;lbrack;Content&amp;rbrack; Il filtro Acqua modifica il guadagno della mappa di altezza
* &amp;lbrack;Content&amp;rbrack; Correggi Affiancamento del materiale superiore nel metodo di fusione opacità
* &amp;lbrack;Content&amp;rbrack; il Height del materiale in alto viene mantenuto nel metodo di fusione opacità
* &amp;lbrack;Content&amp;rbrack; Possibilità di aggiungere una maschera personalizzata, un pattern personalizzato o una mappa di scala nel filtro Perforazione
* &amp;lbrack;Content&amp;rbrack; Il filtro Modulazione Height forza height e mappa normale in 16 bit
* &amp;lbrack;Content&amp;rbrack; Il filtro di regolazione forza le mappe normali e di height in 16 bit

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

* &amp;lbrack;Blend&amp;brack; Nuovo metodo di fusione opacità
* &amp;lbrack;Engine&amp;rbrack; Nuova versione di Substance Engine

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; Correggere l&#39;arresto anomalo durante l&#39;eliminazione di un livello che sta ancora elaborando
* &amp;blocca;Livelli&amp;rbrack; Correggi l&#39;arresto anomalo durante la rimozione del livello inferiore
* &amp;lbrack;Layers&amp;rbrack; Correggere l&#39;arresto anomalo quando il nome del materiale contiene caratteri speciali
* &amp;lbrack;Layers&amp;rbrack; Interrompere l&#39;elaborazione di tutti i filtri che utilizzano un widget
* &amp;blocco;Livelli&amp;rbrack; Evitare l&#39;arresto anomalo durante l&#39;utilizzo dei filtri Patch clone e Riempimento in base al contenuto
* &amp;lbrack;Layers&amp;rbrack; Correggere l&#39;arresto anomalo durante il trascinamento di un filtro negli slot di input di uno splatter
* &amp;lbrack;Resources&amp;rbrack; Correggere l&#39;arresto anomalo durante il collegamento di cartelle locali o l&#39;importazione di risorse in Substance Alchemist
* &amp;lbrack;Collection&amp;rbrack; Correggi l&#39;arresto anomalo durante il passaggio rapido tra i materiali
* &amp;lbrack;UI&amp;rbrack; Correggere l&#39;arresto anomalo se il valore è null o non valido in affiancatura, spostamento dei cursori nella finestra della vista
* &amp;lbrack;Inspire&amp;rbrack; Correggere l&#39;arresto anomalo durante l&#39;accesso alla scheda Ispirazione
* &amp;lbrack;Inspire&amp;rbrack; Correggere l&#39;arresto anomalo mentre si ispira a un materiale della pila di livelli appena salvati
* &amp;lbrack;Performance&amp;rbrack; Substance di materiali e filtri (Affiancamento) pesanti più veloce
* &amp;lbrack;Help&amp;rbrack; Correggi file registro di esportazione
* &amp;lbrack;Content&amp;rbrack; Il filtro casuale funziona su tutti i canali
* &amp;lbrack;Content&amp;rbrack; Il flusso di lavoro con più angoli prende in considerazione tutte le scansioni
* &amp;lbrack;Content&amp;rbrack; AO Fusione corretta
* &amp;lbrack;Content&amp;rbrack; Curvatura Fusione corretta fusione
* &amp;lbrack;Content&amp;rbrack; Color ID Fusione corretta fusione
* &amp;lbrack;Content&amp;rbrack; Custom Mask Blend corregge la fusione
* &amp;lbrack;Content&amp;rbrack; Correggi filtro di regolazione per modifica della rugosità
* &amp;lbrack;Content&amp;rbrack; Correggi filtro Materiale di base per il caricamento personalizzato dei canali normali
* &amp;lbrack;Content&amp;rbrack; Correggi pattern di importazione personalizzato del filtro Rilievo

**Problemi noti:**

* L&#39;uso di più delighters in un unico materiale non è raccomandato
* Delighter si arresta in modo anomalo con i driver NVIDIA più vecchi (meno di 400.x)
* Il coma o il punto possono essere ignorati quando si digita un valore specifico in un cursore
* Il filtro Normale al Height può bloccarsi su MacOS

### 1.1.0 (2019.1.0) Sesame

*(Rilasciato il 4 novembre 2019)*

**Aggiunto:**

* &amp;lbrack;Project&amp;rbrack; Creazione di un progetto
* &amp;lbrack;Project&amp;rbrack; Introduzione al formato di file .alch che contiene i dati del progetto
* &amp;lbrack;Project&amp;rbrack; Esporta un progetto .alch contenente le raccolte e i relativi materiali
* &amp;lbrack;Project&amp;rbrack; Importa un progetto .alch
* &amp;lbrack;Project&amp;rbrack; Apri progetti recenti
* &amp;lbrack;Schermata introduttiva&amp;rbrack; All&#39;avvio viene visualizzata una schermata di benvenuto
* &amp;lbrack;Schermata introduttiva&amp;brack; Crea un progetto dalla schermata introduttiva
* &amp;lbrack;Schermata introduttiva&amp;brack; Accedi all’elenco di tutti i tuoi progetti nella schermata introduttiva
* &amp;lbrack;Schermata introduttiva&amp;brack; Collegamenti rapidi per accedere alla documentazione, alla finestra a comparsa Informazioni sulla gestione licenze
* &amp;lbrack;Menu File&amp;rbrack; Integrazione di un menu file
* &amp;lbrack;Menu File&amp;rbrack; Accedi ai comandi del progetto dalla scheda File e salva il gruppo di livelli
* &amp;lbrack;Menu File&amp;rbrack; accedere ai comandi Annulla e Ripeti della scheda Modifica
* &amp;lbrack;Menu File&amp;rbrack; Il menu della Guida precedente è stato spostato nel menu File sotto la scheda Guida
* &amp;lbrack;Layers&amp;rbrack; Nuova architettura dello stack di livelli
* &amp;lbrack;Layers&amp;rbrack; Nuova interfaccia utente del gruppo di livelli
* &amp;lbrack;Livelli&amp;rbrack; Selezionare il metodo di fusione direttamente sulla barra degli strumenti
* &amp;lbrack;Layers&amp;rbrack; Accedi separatamente ai parametri di fusione e ai parametri del materiale
* &amp;lbrack;Layers&amp;rbrack; Aggiungi materiali direttamente negli input dedicati del filtro Spruzzo nella pila di livelli
* &amp;lbrack;Layers&amp;rbrack; Cambia l&#39;ordine di scansione direttamente nel livello di importazione dell&#39;immagine
* &amp;lbrack;Viewport&amp;rbrack; controllo del campo visivo della videocamera
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; possibilità di passare da una fotocamera ortogonale a una prospettica
* &amp;lbrack;Viewport&amp;rbrack; visualizza le informazioni relative alla risoluzione e alle profondità di bit per ciascun canale
* &amp;lbrack;Resources&amp;rbrack; Materiali di base aperti per impostazione predefinita
* &amp;blocco;Cache&amp;rbrack; Individua la cartella della cache delle miniature
* &amp;blocco;Cache&amp;rbrack; Individua la cartella della cache di rendering
* &amp;blocca;Panels&amp;rbrack; il pannello Impostazioni materiale è temporaneamente nascosto
* &amp;lbrack;Workflow&amp;rbrack; Specular/lucidità temporaneamente disattivato
* &amp;lbrack;MacOS&amp;rbrack; versione del sistema operativo Catalina per l’autenticazione ufficiale
* &amp;lbrack;Content&amp;rbrack; Nuova versione del filtro Delighter
* &amp;blocco;Content&amp;brack; nuovo filtro Riempimento in base al contenuto dell&#39;immagine
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro Riempimento in base al contenuto del materiale
* &amp;lbrack;Content&amp;rbrack; filtro di Trasforma con opzione Trasforma sicura

**Corretto:**

* Tutti i bug precedenti relativi a Crea non sono più validi con la nuova versione per interfaccia e architettura
* Le icone nella barra superiore (3D, 2D, 2D/3D) non vengono nascoste nelle descrizioni comandi
* &amp;lbrack;Content&amp;rbrack; Il filtro splatter accetta Atlas con mappa altezza completa
* &amp;lbrack;Content&amp;rbrack; Il filtro di Trasforma funziona sulle immagini (scan1, scan2,...)

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

* &amp;lbrack;Create&amp;rbrack; Alcuni filtri erano elencati nella funzione di accesso rapido ma non nel pannello dei filtri
* &amp;lbrack;MacOS&amp;rbrack; Corretti alcuni arresti anomali all&#39;uscita

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

* &amp;blocca;Risorse&amp;blocca; Collega e copia speculare le tue cartelle dei materiali sui dischi locali
* &amp;lbrack;Resources&amp;rbrack; Sfoglia le cartelle dei materiali e le relative sottocartelle
* &amp;blocca;Risorse&amp;blocca; scollega il pannello delle risorse materiali in una finestra separata per visualizzare le risorse a schermo intero
* &amp;blocco;Risorse&amp;rbrack; Nuovo layout del pannello Risorse per supportare la navigazione di cartelle e sottocartelle
* &amp;lbrack;Resources&amp;rbrack; Utilizza il breadcrum per spostarti tra le cartelle
* &amp;lbrack;Resources&amp;rbrack; Forza la sincronizzazione della cartella locale con l&#39;opzione Sincronizza accessibile facendo clic con il pulsante destro del mouse
* &amp;lbrack;Resources&amp;rbrack; Disconnetti la cartella locale con l&#39;opzione Disconnetti accessibile facendo clic con il pulsante destro del mouse
* &amp;lbrack;Gestisci&amp;rbrack; Visualizza i tag incorporati dei file Substance
* &amp;lbrack;Gestisci&amp;rbrack; Aggiungi, modifica ed elimina i tag dei materiali
* &amp;lbrack;Gestisci&amp;rbrack; Valuta i tuoi materiali
* &amp;lbrack;Layers&amp;rbrack; Supporta l&#39;output Panorama
* &amp;lbrack;Layers&amp;rbrack; Potete eliminare gli input dall&#39;immagine nel livello Importazione immagine
* &amp;lbrack;Layers&amp;rbrack; Selezione automatica del nuovo livello aggiunto
* &amp;blocca;Livelli&amp;rbrack; selezione automatica del livello sottostante dopo l&#39;eliminazione di un livello
* &amp;lbrack;UX&amp;rbrack; Mantiene la visibilità dei pannelli a sinistra quando si passa a un altro Lab
* &amp;lbrack;UX&amp;rbrack; Non creare un livello base o aprire il popup Flusso di lavoro materiale durante l&#39;importazione di immagini in una pila di livelli non vuota
* &amp;lbrack;UI&amp;rbrack; Nuovo stile per campi di testo
* &amp;lbrack;UI&amp;rbrack; nuovo stile SearchBox
* &amp;lbrack;UI&amp;rbrack; Nuovo stile intestazione pannello
* &amp;lbrack;UI&amp;rbrack; Nuovo stile indicatore Occupato
* &amp;lbrack;UI&amp;rbrack; Stile sfondo sovrapposizione nuovi livelli
* &amp;lbrack;UI&amp;rbrack; Usa font Adobe Clean
* &amp;lbrack;UI&amp;rbrack; Rimuovi segnaposto icona contagocce del parametro di input colore
* &amp;lbrack;Performance&amp;rbrack; Ottimizzazione indicatore attività
* &amp;blocco;Content&amp;rbrack; nuovo filtro Generatore pattern
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Sfocatura

**Corretto:**

* &amp;lbrack;Inspire&amp;rbrack; Correggi arresto anomalo quando si utilizzano più di 10 colori
* &amp;lbrack;vista 2D&amp;rbrack; Correggere la barra di scorrimento nell&#39;elenco dei canali del Vista 2D
* &amp;lbrack;Viewer&amp;rbrack; Correggere l&#39;arresto anomalo durante l&#39;importazione di una mappa dell&#39;ambiente senza alimentazione di 2
* &amp;lbrack;Content&amp;rbrack; Correggere l&#39;importazione PNG per il pattern personalizzato dei filtri Rilievo e Perforazione
* &amp;lbrack;Esporta&amp;rbrack; Correggi normale e height 16 bit per esportazione canale
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

* &amp;lbrack;Filters&amp;rbrack; Accedi rapidamente ai filtri premendo la barra spaziatrice
* &amp;lbrack;Filters&amp;rbrack; Nuovo pannello dedicato per gestire, sfogliare e importare i filtri
* &amp;lbrack;Metadata&amp;rbrack; fare clic con il pulsante destro del mouse su un materiale per visualizzarne i metadati
* &amp;lbrack;Metadata&amp;rbrack; fare clic con il pulsante destro del mouse su un materiale per visualizzarne la posizione sul disco
* &amp;lbrack;Cursori&amp;rbrack; anima i cursori quando li passi con il mouse premendo Ctrl
* &amp;lbrack;Cursori&amp;rbrack; interrompere e riavviare l&#39;animazione dei cursori premendo il tasto P
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione SBSAR è conforme alle linee guida Substance Source
* &amp;lbrack;License&amp;rbrack; Attiva Substance Alchemist utilizzando una variabile di ambiente
* &amp;lbrack;UX&amp;rbrack; La finestra di dialogo File ricorda l&#39;ultimo percorso file selezionato
* &amp;lbrack;UX&amp;rbrack; La finestra di dialogo Cartella ricorda l&#39;ultimo percorso cartella selezionato
* &amp;lbrack;UI&amp;rbrack; Aggiorna interfaccia utente del pannello Risorse
* &amp;lbrack;UI&amp;rbrack; Aggiorna interfaccia utente della barra di ricerca
* &amp;lbrack;UI&amp;rbrack; l&#39;icona Crea nuovo materiale è stata aggiornata
* &amp;lbrack;Help&amp;rbrack; Gli URL vengono aggiornati al dominio substance3d.com
* &amp;lbrack;Mesh&amp;brack; Ora è disponibile una trama in tessuto
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro per la corrosione
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro ossidazione
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro Moss
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Dust
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro pattern Brickwall
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro pattern stonewall
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro finitura legno
* &amp;blocco;Content&amp;rbrack; Nuovo filtro finitura metallica
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Snow
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro casuale
* &amp;lbrack;Content&amp;rbrack; Ora puoi importare la texture direttamente nel filtro Materiale di base

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

* &amp;lbrack;Engine&amp;rbrack; Aggiornamento Substance Engine per compatibilità con la versione di Substance Designer più recente
* &amp;lbrack;License&amp;rbrack; Aggiorna la cartella delle licenze per le prime installazioni
* &amp;lbrack;Layers&amp;rbrack; Ricarica in qualsiasi momento la Pila livelli per aggiornare i filtri personalizzati

**Corretto:**

* &amp;lbrack;Compatibilità dati&amp;rbrack; correzione preventiva per limitare il danneggiamento dei dati al momento dell&#39;aggiornamento

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

* &amp;lbrack;Metadata&amp;rbrack; visualizzare e riempire i metadati dei materiali in una scheda dedicata
* &amp;lbrack;Collection&amp;brack; Crea una raccolta direttamente dai risultati della ricerca
* &amp;lbrack;Media Publishing&amp;rbrack; Esportare una bacheca di una raccolta
* &amp;lbrack;UX&amp;rbrack; Annulla una modifica di modifica o un&#39;importazione di immagini premendo Ctrl+Z
* &amp;lbrack;UX&amp;rbrack; Ripeti una modifica di modifica o un&#39;importazione di immagini premendo Ctrl+Maiusc+Z
* &amp;lbrack;UI&amp;rbrack; nuove icone con un nuovo stile
* &amp;lbrack;Prestazioni&amp;rbrack; Nuovo gestore sessioni per gestire meglio il passaggio tra le schede
* &amp;lbrack;Performance&amp;rbrack; Apertura più rapida del livello Importazione immagine
* &amp;lbrack;Content&amp;rbrack; Nuovo materiale generico metallico
* &amp;lbrack;Content&amp;rbrack; Nuovo materiale Ruggine
* &amp;lbrack;Content&amp;rbrack; Nuovo materiale generico Pietra
* &amp;blocco;Content&amp;rbrack; aggiornamento filtro in rilievo
* &amp;lbrack;Content&amp;rbrack; aggiornamento del filtro Ricamo
* &amp;lbrack;Content&amp;rbrack; aggiornamento filtro Pittura
* &amp;lbrack;Content&amp;rbrack; aggiornamento del filtro Delighter

**Corretto:**

* &amp;lbrack;Content&amp;rbrack; Il filtro Acqua funziona nel flusso di lavoro Specular/Lucentezza
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

* &amp;lbrack;Stack&amp;rbrack; Arresto anomalo durante la rimozione di un livello splatter
* &amp;lbrack;Data&amp;rbrack; Il database delle risorse viene danneggiato quando si verificano arresti anomali dell&#39;applicazione
* &amp;lbrack;Data&amp;rbrack;: impossibile avviare la Substance Alchemist se il database delle risorse è danneggiato
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
* &amp;lbrack;UI&amp;rbrack; Clona /Clone la nuova interfaccia utente dello strumento con visualizzazione della dimensione del pennello
* &amp;lbrack;UI&amp;rbrack; Selezionare ed eliminare le fasi nascoste
* &amp;lbrack;UI&amp;rbrack; Nuova interfaccia utente dei campi di testo
* &amp;lbrack;Help&amp;rbrack; accesso ai siti Web delle accademie Substance Source, Substance share e Substance
* &amp;lbrack;Content&amp;rbrack; nuovi materiali predefiniti con generatori e atlas
* &amp;lbrack;Content&amp;rbrack; Aggiornamento da bitmap a materiale
* &amp;lbrack;Content&amp;rbrack; Aggiornamento Dirt
* &amp;lbrack;Content&amp;rbrack; Aggiornamento Ruggine
* &amp;blocco;Content&amp;rbrack; nuovo filtro in rilievo
* &amp;blocco;Content&amp;rbrack; nuovo filtro Ricamo
* &amp;blocco;Content&amp;rbrack; Nuovo Filtro Erosione
* &amp;lbrack;Content&amp;rbrack; Nuovo generatore di ghiaia
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro Pittura
* &amp;blocco;Contenuto&amp;rbrack; Nuovo filtro Pattern parquet
* &amp;lbrack;Content&amp;rbrack; nuovo filtro Pattern pavimentazione
* &amp;blocco;Content&amp;rbrack; Nuovo filtro Perforazione
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro splatter
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro usura tessile
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro di Trasforma

**Corretto:**

* &amp;lbrack;Viewport&amp;rbrack; mesh sfera con Affiancamento x2 su X
* &amp;lbrack;Viewport&amp;rbrack; Arresto anomalo durante il caricamento del proprio ambiente
* &amp;lbrack;Viewport&amp;rbrack; nella mappa ambiente viene ora utilizzato anche il valore di esposizione
* &amp;lbrack;Viewport&amp;rbrack; F scelta rapida da tastiera non reimposta l&#39;angolo della fotocamera
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione SBS funziona con l&#39;ultimo Substance Designer 2018.3.3
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione SBSAR rispetta le stesse linee guida dei materiali di Substance Source
* &amp;lbrack;UI&amp;rbrack; le barre di scorrimento possono essere trascinate
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

* &amp;lbrack;Pila livelli&amp;rbrack; riordinamento dei livelli
* &amp;lbrack;Pila livelli&amp;rbrack; Eliminare un livello nascosto
* &amp;lbrack;Pila livelli&amp;rbrack; Importa un materiale direttamente nella posizione desiderata
* &amp;lbrack;Pila livelli&amp;rbrack; input di materiale come nuovo tipo di parametro del filtro
* &amp;lbrack;Performance&amp;rbrack; Il budget delle Substance Engine è dinamico per prestazioni migliori
* &amp;lbrack;Performance&amp;rbrack; Migliori prestazioni OpenGL, in particolare su MacOS
* &amp;lbrack;Data&amp;rbrack; Aggiornamento dei dati più rapido dopo il rilascio di una nuova versione
* &amp;lbrack;Content&amp;rbrack; AI Delighter disponibile su Windows 7 e Windows 8
* &amp;lbrack;Content&amp;rbrack; AI Delighter disponibile su GPU RTX

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

* &amp;lbrack;Export&amp;rbrack; Substance archive (sbsar) export of your collection
* &amp;lbrack;Esporta&amp;rbrack; esportazione di file di Substance (sbs) della raccolta
* &amp;lbrack;Export&amp;rbrack; coda di esportazione visibile nel pannello Esporta
* &amp;lbrack;Esporta&amp;rbrack; assegna un nome alla raccolta o al materiale prima dell&#39;esportazione
* &amp;lbrack;Data&amp;rbrack; Salva come materiale premendo Ctrl+Maiusc+S
* &amp;lbrack;Data&amp;rbrack; Salva il materiale premendo Ctrl+S
* &amp;lbrack;Data&amp;rbrack; le raccolte e i materiali sono compatibili tra le versioni
* &amp;lbrack;Data&amp;rbrack; Aggiorna la Pila livelli del materiale con filtri aggiornati
* &amp;lbrack;Data&amp;rbrack; Ricaricamento a caldo dei filtri personalizzati importati
* &amp;lbrack;UI&amp;rbrack; Feedback visivo nella finestra della vista durante l&#39;elaborazione
* &amp;lbrack;UI&amp;rbrack; Nuovo stile pulsante
* &amp;lbrack;UI&amp;rbrack; nel menu a comparsa Salva viene visualizzato il nome della raccolta attiva
* &amp;lbrack;UI&amp;rbrack; modifica le immagini sorgente di un livello di importazione immagini
* &amp;lbrack;Content&amp;rbrack; Gli usi personalizzati sono ora supportati
* &amp;lbrack;Content&amp;rbrack; nei parametri di input dell&#39;immagine sono supportati altri formati di immagini
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro di Affiancamento denominato Make It Tile Advanced
* &amp;lbrack;Content&amp;rbrack; aggiornamento del filtro Acqua

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

* &amp;blocco;Esporta&amp;rbrack; finestra a comparsa Nuova esportazione
* &amp;lbrack;Esporta&amp;rbrack; Esporta un&#39;intera raccolta
* &amp;lbrack;Esporta&amp;rbrack; Esporta bitmap nel formato desiderato
* &amp;lbrack;Esporta&amp;rbrack; Esporta bitmap alla risoluzione desiderata
* &amp;lbrack;Export&amp;rbrack; Esporta solo i canali desiderati
* &amp;lbrack;Esporta&amp;rbrack; Visualizza in anteprima la stima delle dimensioni dell&#39;esportazione
* &amp;lbrack;Esporta&amp;rbrack; visualizza in anteprima le dimensioni disponibili sul disco prima dell&#39;esportazione
* &amp;lbrack;UX&amp;rbrack; Azioni sulla raccolta accessibili utilizzando il pulsante destro del mouse
* &amp;lbrack;UX&amp;rbrack; Consenti di disimpostare un&#39;immagine o una risorsa in Inspire
* &amp;lbrack;UX&amp;rbrack; Substance Alchemist avviata ingrandita
* &amp;lbrack;Risorse&amp;rbrack; Nuovo modo di salvare i materiali per mantenerli persistenti con le versioni successive
* &amp;lbrack;Help&amp;rbrack; Accesso alla documentazione in linea tramite il menu?
* &amp;lbrack;Performance&amp;rbrack; Variazioni di colore più rapide per materiali complessi creati con Substance Alchemist
* &amp;lbrack;Prestazioni&amp;rbrack; Riduci le perdite di memoria quando si cambia laboratorio
* &amp;lbrack;Content&amp;rbrack; Controllo scala per diagnosticare la dimensioni fisiche del materiale
* &amp;lbrack;Content&amp;rbrack; Aggiorna il materiale delle piastrelle del mosaico italiano di Venezia
* &amp;lbrack;Content&amp;rbrack; Aggiorna splatter Moss

**Corretto:**

* Non è più disponibile il nome predefinito quando si salva un materiale
* I parametri dei filtri vengono persi dopo aver salvato un materiale e riaperto la Substance Alchemist
* &amp;lbrack;Content&amp;rbrack; Correggi dalla logica inferiore e superiore per AO e fusione curvatura

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
* &amp;lbrack;Log&amp;rbrack; Esporta il file di registro tramite il menu Aiuto
* &amp;blocco;UI&amp;rbrack;Nuovo stile cursori
* &amp;blocco;UI&amp;rbrack;I pannelli Predefiniti e Tweak sono uniti
* &amp;blocco;UI&amp;rbrack;Nuovo stile miniature
* Impostazioni di Spostamento, Affiancamento e Ombre accessibili direttamente nella finestra della vista
* &amp;lbrack;Content&amp;rbrack; Nuovi materiali predefiniti
* &amp;lbrack;Content&amp;rbrack; aggiornamento Moss Splatter
* &amp;lbrack;Framework&amp;rbrack; Aggiorna Substance Engine Framework

**Corretto:**

* L’eliminazione della versione di Pila livelli tramite il cambio di laboratorio è stata corretta
* I valori di tempo di caricamento visualizzati nella finestra della vista sono corretti
* I canali predefiniti del flusso di lavoro dei materiali sono inizializzati correttamente
* Disattiva importazione trama personalizzata
* Esportazione bitmap
* &amp;lbrack;MacOS&amp;rbrack; La Substance Alchemist di chiusura può richiedere un &quot;Forza all&#39;uscita&quot;

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
* &amp;lbrack;MacOS&amp;rbrack; La Substance Alchemist può essere impostata a schermo intero
* &amp;lbrack;Filter&amp;rbrack; Importa maschera personalizzata per gestire la fusione tra due materiali
* &amp;lbrack;Filter&amp;rbrack; Control Moss scale
* &amp;lbrack;Filter&amp;rbrack; Clona /Clone aggiornamento patch

**Corretto:**

* Aggiungere un’immagine in un input di immagine nell’elenco dei parametri e aggiornare gli output
* Il filtro Importa personalizzato non aggiunge un’Occlusione ambientale nera né un’opacità nera

**Problemi noti:**

* I materiali creati con una versione precedente non saranno disponibili nella nuova versione.
* &amp;lbrack;MacOS&amp;rbrack; La Substance Alchemist di chiusura può richiedere un &quot;Forza all&#39;uscita&quot;
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
