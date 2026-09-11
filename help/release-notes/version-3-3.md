---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/release-notes/version-3-3.html"
breadcrumb-title: ''
description: Consultate le note sulla versione per Substance 3D Sampler versione 3.3 per informazioni su nuovi strumenti, contenuti e funzioni di creazione di materiali.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.3
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 3.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1108'
ht-degree: 0%

---


# Versione 3.3

**Substance 3D Sampler 3.3.0** introduce una serie di nuovi strumenti, contenuti e funzionalità per creare e modificare più facilmente materiali e luce ambientale.

*Data di pubblicazione: 17 maggio 2022*

## Funzioni principali

## Riempimento in base al contenuto

Riempimento in base al contenuto è una tecnologia diffusa in Adobe Photoshop, utilizzata per rimuovere i dettagli in un&#39;immagine mantenendo l&#39;integrità dell&#39;area circostante.

Substance 3D Sampler ora utilizza la stessa tecnologia, che consente di pulire i materiali PBR e le luci ambiente. Nei materiali PBR, il Riempimento in base al contenuto viene applicato a tutti i canali. Non è necessario elaborare ogni canale separatamente.

Riempimento in base al contenuto consente di rimuovere elementi di grandi dimensioni per evitare ripetizioni durante l&#39;Affiancamento di un materiale o rimuovere piccole imperfezioni sul fabric scansionato.

Durante l’acquisizione di 360 panorami, potrebbe non essere possibile controllare tutti gli elementi della scena e quindi è necessario rimuovere piccoli oggetti sul terreno, dipinti su un muro o una persona in piedi sullo sfondo. Riempimento in base al contenuto ora semplifica questa operazione.

## Authoring IBL

### Proiezione sferica

L&#39;editing di luce ambientale e 360 immagini può essere difficile quando vengono visualizzate come immagini normali. Tutti gli elementi risultano distorti rendendo quasi impossibile la modifica. Con la nuova proiezione sferica, potete navigare a 360° e apportare modifiche con strumenti dedicati come Nadir patch, Riempimento in base al contenuto e tutte le luci della procedurali senza distorsione. Ad esempio, ora è più facile modificare o pulire le linee rette, rimuovere il treppiede dalla fotocamera e posizionare perfettamente le luci della linea.

Guarda il nuovo tutorial per [creare luci ambiente](https://www.youtube.com/watch?v=cfW9IyoTXQ8) utilizzando questa nuova modalità.

### Cursore Esposizione

Nel Vista 2D, potete modificare temporaneamente l&#39;esposizione per visualizzare meglio i dettagli o gli oggetti sulle parti sottoesposte o sovraesposte dell&#39;ambiente che state modificando.

### Impostazioni del visualizzatore dedicato

Le impostazioni del visualizzatore sono persistenti per tipo di risorsa (materiale o luce ambientale). Puoi impostare la trama, la texture predefinita o il campo di visualizzazione della videocamera per ogni tipo di risorsa per passare più facilmente da una all’altra e lavorare nel contesto corretto.

## Widget migliorati

### Clona /Clone timbro

Con questo aggiornamento timbro Clona /Clone, puoi pittura più tratti di timbro con varie fonti in un singolo livello e accedere alla cronologia del timbro nella Pila livelli. Inoltre, è ora possibile visualizzare il risultato del timbro direttamente nell’anteprima del pennello prima di colorare. Questo semplifica la pulizia dei materiali ed evita che si ripetano spesso spostamenti tra le viste.

### Ritagliare e Trasforma

Questo aggiornamento introduce nuove scelte rapide per la manipolazione dei widget Ritaglia e Trasforma.

### Barra degli strumenti Pennello

La nuova interfaccia utente, simile ai prodotti di Adobe più recenti come Fresco, consente di spostare la barra degli strumenti in qualsiasi punto del Vista 2D, in verticale o in orizzontale. Mentre colorate, passate dal pennello alla gomma con il tasto E e utilizzate le nuove opzioni di Affiancamento per controllare meglio ciò che pitture.

## Da immagine a materiale (basato sull&#39;intelligenza artificiale)

### Mantieni Affiancamento

Da immagine a materiale (basata su IA) ottiene una nuova opzione: ora può preservare l&#39;Affiancamento dell&#39;immagine affiancabile, riducendo il tempo necessario per affiancare il materiale.

## Interoperabilità

Invia materiali a Stager

Era già possibile inviare luci ambientali a Stager. Ora puoi inviare i tuoi materiali a Stager con un solo clic, proprio come puoi fare con Designer e Painter. Grazie a questa funzione, non è più necessario pubblicare i materiali e caricarli in Stager come file singoli (richiede Stager versione 1.2.0 con il nuovo gestore materiali).

## Note sulla versione

### 3.3.0 Zucchini

*(Rilasciato Il 17 Maggio 2022)*

**Aggiunto:**

* [Contenuto] Nuovo filtro Riempimento in base al contenuto (Windows e Mac)
* [Content] Il riempimento in base al contenuto funziona su immagini, materiali PBR e luce ambientale
* [Contenuto] Aggiungi il parametro &quot;Mantieni Affiancamento&quot; a Immagine su materiale (basata su IA)
* [Contenuto] Il filtro Trasforma Prospettiva consente di visualizzare una griglia tra i quattro punti
* [Interoperabilità] Invia materiali ad Adobe Substance 3D Stager
* [Tools] Centra la trasformazione premendo Ctrl durante il ridimensionamento dello strumento Trasformazione o Ritaglio
* [Strumenti] Blocca il rapporto al quadrato premendo Maiusc durante il ridimensionamento dello strumento Trasforma o Ritaglio
* [Tools] Clona /Clone cursore timbro offre un’anteprima di ciò che verrà timbrato
* [Strumenti] Visualizza in anteprima il contenuto originale nel cursore Gomma quando si utilizza Timbro clone
* [Strumenti] Ctrl+Clic per creare un nuovo timbro nel livello Clona /Clone timbro
* [Strumenti] I successivi timbri clone sono ora raggruppati in un singolo livello
* [Tools] Brush Toolbar UI Revamp
* [Strumenti] La posizione della barra degli strumenti Pennello è persistente durante una sessione
* [Strumenti] Nuove opzioni di Affiancamento pennello in base all’asse
* [Strumenti] Nascondere/visualizzare la sovrapposizione sul Vista 2D quando si disegna
* [Tools] Nuova scelta rapida da tastiera, tasto &quot;X&quot;, per alternare tra Pennello e Gomma
* [Strumenti] Nuova scelta rapida da tastiera, &quot;[&quot; &quot;]&quot; per modificare la dimensione del pennello
* [Tools] Nuova scelta rapida, tasto &quot;E&quot;, per attivare/disattivare la gomma
* [Vista 2D] Nuova modalità Proiezione sferica durante la creazione della luce ambiente
* [Vista 2D] Lo strumento Pennello è supportato in modalità proiezione sferica
* [vista 2D] Lo strumento Posizione è supportato in modalità proiezione sferica
* [vista 2D] La modalità proiezione sferica supporta le operazioni Annulla/Ripeti.
* [vista 2D] In Proiezione sferica, imposta la posizione predefinita per guardare al centro dell&#39;ambiente
* [Vista 2D] Nuovo controllo dell&#39;esposizione
* [UI] Nel pannello Proprietà, la modifica dell&#39;immagine mostra la sorgente del contenuto (immagine o da un livello)
* [UI] È stato migliorato lo sfondo a discesa dei livelli/output di materiale.
* [UI] Nuova posizione delle informazioni di risoluzione nel vista 2D
* [UI] Nuova descrizione con scelte rapide dei controlli di navigazione della vista 3D
* [UI] Nuova descrizione con i controlli del pennello
* [UI] Nuova descrizione con le scelte rapide dei controlli di navigazione della proiezione
* [Filtri composti] I filtri composti gestiscono le variazioni per lavorare su immagini, materiali PBR e luce ambientale
* [Filtri composti] L’ordine delle modifiche corrisponde all’ordine dell’elenco dei nodi nel filtro composto
* [Filtri composti] Le modifiche di nodi diversi con lo stesso gruppo verranno unite in un unico gruppo nel pannello Proprietà
* [Applicazione] Dispone di impostazioni del visualizzatore dedicate per tipo di risorsa

**Corretto:**

* [Applicazione] L&#39;applicazione potrebbe arresto anomalo quando si passa a Vista 2D
* [Applicazione] Correggere un possibile deadlock o arresto anomalo durante l&#39;esportazione multipla
* [Applicazione] Rendi i valori predefiniti per i canali coerenti con Substance 3D Designer
* [Applicazione] Il caricamento di un progetto non attiva il ricalcolo del materiale
* [Applicazione] Aggiornamento dell&#39;URL per la texture della documentazione di importazione
* [Contenuto] Quando si utilizza un filtro composto, richiede di essere aggiornato quando non dovrebbe, al ricaricamento
* [Contenuto] I dettagli nella mappa dell’altezza scompaiono quando si utilizza la Fusione di opacità
* [UI] Nella finestra di dialogo Colore, è possibile uscire dall&#39;intervallo utilizzando i campi di testo del cursore
* [UI] L’elenco Utilizzo include una barra di scorrimento verticale inutile

**Problemi noti:**

* [Selettore colore] La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
* [Contenuto] Il widget della luce della forma non funziona in modalità proiezione sferica
* [Interoperabilità] Il materiale con spostamento inviato a Stager perderà i controlli di spostamento
