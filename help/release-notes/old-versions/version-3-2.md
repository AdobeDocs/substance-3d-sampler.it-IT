---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-2.html"
breadcrumb-title: ''
description: Consultate le note sulla versione per Substance 3D Sampler versione 3.2 per informazioni sul flusso di lavoro di digitalizzazione dei materiali, nuovi filtri e metadati personalizzati.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.2
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 3.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1058'
ht-degree: 0%

---


# Versione 3.2

**Substance 3D Sampler 3.2** introduce un flusso di lavoro end-to-end per la digitalizzazione dei materiali che acquisisce ed elabora la dimensioni fisiche dei materiali, nuovi filtri come intreccio di stoffa e commutazione del canale e la possibilità di creare metadati personalizzati.

Data di pubblicazione: 25 *gennaio 2022*

## Caratteristiche principali

### Dimensione fisica

In questa versione è stato introdotto un nuovo flusso di lavoro per la scansione del materiale che acquisisce ed elabora la dimensioni fisiche dei materiali.

Corrispondenza della [dimensioni fisiche](../../features-and-workflows/end-to-end-physical-size-workflow.md) effettiva dei campioni/delle immagini in un contesto digitale per creare materiali fisicamente accurati in qualsiasi software.

![](../../assets/physicalsize-1.png){width="400px"}

### Tessuto

Il nuovissimo Generatore viene aggiunto in questa versione. La Tessitura in tessuto consente di creare e progettare tessuti in tessuto con pattern di tessitura personalizzati.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/weavecollection.png){width="390px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/weaveinterface.png){width="400px"}

</td>
</tr>
</table>

### Metadati personalizzati

Aggiungi metadati personalizzati ai tuoi materiali. Tutti i metadati personalizzati saranno inclusi nel file di materiale (SBSAR) per garantire un flusso di lavoro più efficiente per la condivisione di materiali digitali tra le applicazioni.

![](../../assets/custommetadata.png){width="264px"}

### Interruttore canale

Con Channel Switch è ora possibile cambiare i canali delle mappe di output del materiale.

![](../../assets/screenshot-2022-02-15-at-15-53-00.png){width="300px"}

### Esporta

A questa versione sono state aggiunte nuove funzioni di esportazione.

* Imposta impostazione di compressione file .sbsar

  ![](../../assets/compressionsbsar.png){width="400px"}
* Imposta il tipo di grafico quando si esporta un file .sbs(ar)
* Mantieni il rapporto fisico per EXR, JPEG, PNG, TARGA, TIFF

  ![](../../assets/screenshot-2022-02-16-at-15-28-09.png){width="400px"}

## Note sulla versione

### 3.2.0 Yakitori

*(Rilasciato il 25 gennaio 2022)*

**Aggiunto:**

* [Dimensioni fisiche] Nuovo pannello Dimensioni fisiche
* [Dimensioni fisiche] Aggiungere opzioni Dimensioni fisiche alla finestra Modello creazione materiale
* [Dimensioni fisiche] Aggiungi strumento di misurazione Dimensioni fisiche
* [Dimensioni fisiche] Aggiungi strumento di misurazione automatica Dimensioni fisiche
* [Dimensioni fisiche] Aggiungi strumento di diagnostica Dimensioni fisiche
* [Dimensioni fisiche] Consente di impostare il valore z della Dimensioni fisiche
* [Dimensioni fisiche] Widget a discesa per impostare il livello di zoom nella Vista 2D
* [Dimensioni fisiche] Nuova opzione &quot;Display with physical ratio&quot; (Visualizzazione con rapporto fisico) nel menu a discesa livello di zoom
* [Dimensioni fisiche] Nuova opzione &quot;Adatta alla dimensioni fisiche&quot; nel menu a discesa del livello di zoom
* [Dimensioni fisiche] Visualizza la Dimensioni fisiche nella Vista 2D
* [Dimensioni fisiche] Visualizza la Dimensioni fisiche nella finestra della vista 3D
* [Dimensioni fisiche] Nella finestra di dialogo di importazione delle immagini, mostra profondità dimensioni fisiche se è presente una mappa di height importata
* [Dimensioni fisiche] Visualizza la Dimensioni fisiche nel menu di scelta rapida della risorsa
* [Dimensioni fisiche] Impostate l’unità di lunghezza nelle Preferenze
* [Dimensioni fisiche] Esportare texture che rispettino il rapporto fisico
* [Metadati] Possibilità di aggiungere metadati personalizzati a una risorsa creata dall’utente
* [Esporta] Esportare metadati personalizzati in file .sbs(ar)
* [Esportazione] Esportazione di metadati di descrizione, categoria, autore e tag nei file .sbs(ar)
* [Esporta] Esporta la Dimensioni fisiche nei file .sbs(ar)
* [Export] Imposta l&#39;impostazione di compressione del file .sbsar
* [Export] Esporta la miniatura della risorsa nei file .sbs(ar)
* [Export] Imposta il tipo di grafico quando si esporta un file .sbs(ar)
* [Applicazione] Il motore in tempo reale 2021 non è più disponibile
* [Applicazione] Annulla/Ripeti ora supporta le modifiche del cursore Affiancamento (U,V) e Scala height
* [Rendering] Genera cache disco quando la risorsa creata viene salvata
* [Risorse] Utilizzare Ctrl+clic per attivare più filtri per il tipo di risorsa nel pannello Risorse
* [UI] Possibilità di bloccare i cursori Porzione (U,V)
* [UI] Aggiungi un menu di scelta rapida con &quot;Copia&quot;, &quot;Taglia&quot;, &quot;Incolla&quot;, &quot;Copia tutto&quot; e &quot;Taglia tutto&quot; nei campi di testo
* [UI] Unità di lunghezza (metri, pollici, parsec, ...) supporto per etichette e campi di testo
* [UI] L’utente può impostare la precisione decimale utilizzata per visualizzare i numeri
* [UI] Utilizza le unità nei popup delle misure ovunque sia pertinente
* [Localizzazione] Il nome predefinito della nuova risorsa è ora localizzato
* [Contenuto] Nuovo generatore tessuto tessuto
* [Content] Nuovo filtro per cambio canale
* [Contenuto] Tutti i filtri pertinenti sono ora a conoscenza della Dimensioni fisiche
* [Content] Nuove icone per Finitura legno
* [Contenuto] Tutti i filtri sono ora compatibili con i canali di Adobe Standard Material (ASM)
* [Content] I filtri possono ora avere una variazione di &quot;ambiente&quot;

**Corretto:**

* [vista 2D] Il canale rimane nell&#39;elenco quando viene rimosso
* [Applicazione] Impossibile duplicare una risorsa caricata da Esplora file del sistema operativo
* [Applicazione] Arresto anomalo all’uscita
* [Applicazione] Arresto anomalo che talvolta si verifica quando si fa clic su &quot;Risorse per iniziare&quot; nel pannello Risorse
* arresto anomalo [Applicazione] durante l&#39;eliminazione di un materiale
* [Application] La variabile di ambiente &quot;SUBSTANCE\_DISABLE\_SPECIFIC\_FEATURES&quot; è ancora attiva se impostata su &quot;0&quot; o &quot;&quot;.
* [Applicazione] Si verifica un blocco durante il salvataggio di un progetto con più materiali
* [Applicazione] L&#39;importazione di un&#39;immagine può provocare un arresto anomalo
* [Applicazione] Alcune risorse iniziali mancanti al primo avvio
* [Esportazione] L’esportazione di una risorsa a volte genera un arresto anomalo
* [Livelli] Impossibile importare immagini quando il pannello dei livelli è chiuso o invisibile
* [Livelli] Se si cambia la lingua, la risorsa corrente viene ricalcolata
* [Livelli] Se si modifica l’utilizzo di un’immagine importata, la variazione del filtro da utilizzare non viene aggiornata
* [Livelli] L&#39;immagine nel materiale (AI) a volte non viene calcolata quando si modificano i livelli sottostanti
* [Layers] L&#39;opzione Da immagine a materiale (AI) a volte ricalcola quando non è necessaria
* [Livelli] Non è consigliato alcun aggiornamento quando si aggiorna un filtro personalizzato sul disco
* [Livelli] Il formato dei pixel del canale normale a volte è errato
* [Livelli] Alcuni livelli vengono comunque calcolati anche quando non sono visibili
* [Livelli] Quando si attiva o disattiva la visibilità di un livello, gli strumenti di Vista 2D potrebbero essere danneggiati
* [Layers] L&#39;interfaccia si blocca quando si utilizza Image to Material (AI)
* [Livelli] Attivando o disattivando la visibilità del livello del filtro di Trasforma si interrompe lo strumento Vista 2D e si potrebbe verificare un arresto anomalo
* [Livelli] Troppe rielaborazioni durante la rimozione di un livello dalla Pila livelli
* [Livelli] Quando un filtro composto contiene un input/output insolito o personalizzato, Sampler non lo calcola
* [Prestazioni] Il pannello Risorse si apre lentamente
* [Prestazioni] Evitare di ricalcolare la Pila livelli in modo non necessario
* [Prestazioni] Il caricamento delle risorse del progetto richiede troppo tempo
* [Prestazioni] Impossibile utilizzare la cache di rendering sul disco
* [Prestazioni] Il passaggio da un livello all’altro è lento
* [Prestazioni] La modifica di un materiale o di un filtro è lenta
* [Progetto] Il salvataggio di un progetto alla chiusura può provocare un arresto anomalo
* [Rendering] La rimozione di un’immagine può rimuovere tutti gli output
* [Rendering] Il tempo di rendering visualizzato nella finestra della vista è errato durante l’ottimizzazione
* [UI] Impossibile scorrere verticalmente nel popup di esportazione quando necessario
* [UI] È possibile aprire il popup di esportazione quando non c&#39;è nulla da esportare
* [UI] Alcuni popup non scorrono se il loro contenuto sovraccarica
* [UI] I campi di testo non sono selezionati quando si fa clic su di essi o si apre un menu
* [UI] Il nome del metodo di fusione nel pannello delle proprietà a volte non è corretto
* [UI] L’opzione Salva nel menu File a volte è disattivata
* [UI] Il campo di testo non scompare dopo aver rinominato due materiali
* [UI] Errore di battitura nel popup delle preferenze

**Problemi noti:**

* [Selettore colore] La selezione di un colore su un secondo monitor con una risoluzione diversa potrebbe non funzionare
