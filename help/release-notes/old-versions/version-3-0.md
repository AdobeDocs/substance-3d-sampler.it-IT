---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-0.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 3.0 per scoprire la rielaborazione dell'interfaccia utente, le luci ambiente, i filtri e l'integrazione delle Creative Cloud.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 3.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '2019'
ht-degree: 0%

---


# Versione 3.0

**Substance 3D Sampler 3.0.0** è il nuovo nome di Substance Alchemist ora che è connesso a Adobe Creative Cloud. Offre una rielaborazione completa dell&#39;interfaccia utente, supporto per la creazione di luci ambiente, rielaborazione completa e nuovi filtri, funzionalità Invia a e supporto dello shader ASM.

Data di pubblicazione: *23 giugno 2021*

## Funzioni principali

### Nuova interfaccia e gestione del pannello

Con un nuovo nome, si ottiene un nuovo look. L’interfaccia utente di Sampler è stata completamente rinnovata per consentire una maggiore personalizzazione e un accesso più semplice.

![](../../assets/ui-dualscreen.jpg){width="600px"}

I pannelli possono essere ancorati e disancorati, consentendo di utilizzare completamente una configurazione a doppio schermo.

### Nuovo flusso di lavoro progetto

![](../../assets/ui-project-panel.png)

Sampler ora funziona con i progetti. Il [pannello Progetto](../../interface/panels/project-panel.md)consente di gestire e raggruppare le risorse per progetto. I progetti sono archiviati in file Substance Sampler, facilmente condivisibili.

### Nuovo pannello Risorse

![](../../assets/image2021-6-22-17-58-15.png)

Il [pannello Risorse](../../interface/panels/assets-panel.md)è un nuovo progetto comune del pannello Risorse, combinato con le tue raccolte.

* 3 sezioni: Risorse iniziali + Le tue risorse + Cartelle locali connesse
* Supporto di nuovi tipi di risorse: filtri e immagini
* Vista stretta/ampia
* Filtrare e cercare filtri

### Creazione nuova luce di ambiente

![](../../assets/idl.jpg){width="600px"}

Sampler ora consente di creare più di semplici materiali. Le luci ambiente sono un nuovo tipo di risorsa con [un proprio set di filtri](../../filters/hdri-tools/hdri-tools.md). Iniziate da [360 foto tra parentesi](../../filters/hdri-tools/hdr-merge.md), create una luce ambiente [da zero](../../filters/hdri-tools/shape-light.md) o [modificate un file HDR esistente](../../filters/hdri-tools/nadir-patch.md).

### Filtri rielaborati e nuovi

![](../../assets/filter-all-filters.jpg){width="600px"}

Tutti i filtri esistenti sono stati rielaborati:

* Supporto per i canali delle specifiche/lucidi.
* Supporto per maschere personalizzate
* Nomi dei parametri standardizzati
* Icone per quasi tutti i filtri

Il Filtro di regolazione è stato suddiviso in filtri separati in base alla funzionalità, per simulare Photoshop:

![](../../assets/filter-adjustment-filters.jpg)

Sono stati aggiunti alcuni nuovi filtri:

* [Altera trasformazione](../../filters/tools/warp-transform.md)
* [Intreccio](../../filters/generators/weave.md)
* [Pannello](../../filters/generators/panel.md)

### Nuova funzionalità Invia a

![](../../assets/image2021-6-22-18-2-10.png)

Sampler può ora [condividere facilmente materiali e ambienti luminosi](../../interface/panels/share-panel.md)con Substance 3D Painter e Stager, con un solo clic.

### Nuovo motore di rendering in tempo reale

* Supporto dei materiali ASM, per consentire un aspetto coerente tra le applicazioni con più canali di materiale.
* Passare da 2 [motori in tempo reale](https://helpx.adobe.com/substance-3d/unlisted/documentation/sadoc/viewer-settings-188973164.html)
* Possibilità di controllare le texture predefinite su una trama

### Miglioramenti generali

* Nuove lingue
* Velocità di risposta dell’applicazione
* Supporto per texture non quadrate
* Strumenti Annulla/Ripeti
* Assegnare usi personalizzati alle immagini nel livello Importazione immagine
* Reimpostare un valore di parametro
* Avanzamento dell&#39;esportazione nella barra delle applicazioni di Windows

## Tutorial

Di seguito sono riportate le nostre esercitazioni video sulle nuove funzioni:

## Note sulla versione

### 3.0.0 Waffle

*(Rilasciato Il 23 Giugno 2021)*

**Aggiunto:**

* [Branding] Substance Alchemist diventa Adobe Substance 3D Sampler
* [Branding] Icone di nuove applicazioni
* [UI] Nuova esperienza utente e interfaccia utente
* [UI] Nuova schermata iniziale
* [UI] I pannelli sono disancorabili e ancorabili nell’interfaccia
* [UI] Ancora fino a 3 pannelli nella stessa colonna
* [UI] Aggancia fino a 3 pannelli nello stesso pannello (schede)
* [UI] Disancora i pannelli per creare una finestra separata nella stessa schermata o in una schermata diversa
* [UI] Popup pannelli chiusi quando si fa clic sulle relative icone
* [UI] Ridisponi la barra sinistra e destra spostando le icone dei pannelli
* [UI] Nuova barra degli strumenti per accedere a filtri specifici direttamente (Ritaglia, Trasforma, Trasformazione prospettiva, Timbro clone)
* [UI] Nuovo pulsante &quot;Ottieni contenuto&quot; nella barra a sinistra
* [UI] Importa i file direttamente nelle tue risorse con il pulsante Ottieni contenuto
* [UI] Importa i file direttamente nei livelli con il pulsante Ottieni contenuto
* [UI] Accedi direttamente al sito Web di Adobe con il pulsante Ottieni contenuto
* [UI] Il widget Risoluzione è ora direttamente accessibile nella finestra della vista
* [UI] Tutti gli elementi dell’interfaccia ora vengono caricati dinamicamente
* [UI] Scelta rapida - Utilizzate &quot;2&quot; per attivare/disattivare la visibilità della vista 2D
* [UI] Scelta rapida - Utilizzate &quot;3&quot; per attivare/disattivare la visibilità della vista 3D
* [Schermata introduttiva] Crea un progetto con un solo clic con il pulsante Nuovo
* [Schermata introduttiva] Nuovo banner per grafica
* [Progetto] Tutti i progetti sono ora associati a un file univoco
* [Progetto] Nuova estensione file di progetto .ssa
* [Progetto] Salva come progetto richiede di selezionare dove salvare il progetto
* [Progetto] Se non salvi, alla chiusura di Sampler ti verrà chiesto di salvare il progetto
* [Progetto] Se si chiude Sampler, viene richiesto di salvare il progetto se sono state apportate modifiche dall’ultimo salvataggio
* [Progetto] Il nome del progetto viene visualizzato sopra la finestra della vista
* [Progetto] Il nome del progetto è in corsivo con una stella se non è stato salvato o se contiene modifiche dall’ultimo salvataggio
* [Progetto] Apri un file di progetto .ssa direttamente da Esplora sistema operativo
* [Progetto] Apri un file .sbsar da Esplora sistemi operativi per avviare Sampler con un nuovo progetto in cui questo file .sbsar è pronto per l’uso
* [Progetto] Apri un file .alch (file di Substance Alchemist legacy) da Esplora sistema operativo
* [Pannello Progetto] Nuovo pannello che conterrà tutte le risorse create all’interno di un progetto
* [Pannello Progetto] Crea una risorsa (materiale o luce di ambiente) utilizzando l&#39;icona +
* [Pannello Progetto] Facendo clic con il pulsante destro del mouse su una risorsa si apre un menu contestuale
* [Pannello Progetto] Dal menu di scelta rapida, puoi eliminare una risorsa
* [Pannello Progetto] Dal menu di scelta rapida, puoi duplicare una risorsa
* [Pannello Progetto] Dal menu di scelta rapida, puoi rinominare una risorsa
* [Pannello progetto] Il passaggio da una risorsa all&#39;altra non perderà le modifiche
* [Risoluzione] Ora puoi impostare la risoluzione non quadrata per tutte le tue risorse
* [Risoluzione] Il valore di risoluzione viene salvato per risorsa all’interno di un progetto
* [Luce ambiente] Crea luce ambiente in Substance 3D Sampler
* [Luce ambiente] Durante la creazione di una luce ambiente, trascinando e rilasciando l&#39;immagine o le immagini viene visualizzata la finestra Modello creazione luce ambiente
* [Luce ambiente] Nel modello Creazione luce ambiente, seleziona Importazione ambiente per assegnare l’immagine all’ambiente nella vista 3D
* [Luce ambiente] Nel modello Creazione luce ambiente, seleziona Unione HDR per creare una luce ambiente da diverse immagini a 360 gradi con un’esposizione diversa
* [Luce ambiente] Nel modello di creazione della luce ambiente, seleziona &quot;Usa come bitmap&quot; per modificare le immagini prima di creare una luce ambiente
* [Luce ambiente] Assegna l’utilizzo dell’ambiente nel livello Importazione immagine per assegnare direttamente l’immagine all’ambiente nella vista 3D
* [Luce ambiente] Nella vista 2D per il canale ambiente, è disponibile una correzione automatica del colore che consente di visualizzare il rendering come nella vista 3D
* [Luce ambiente] Nuovo contenuto dedicato per la creazione di luce ambientale
* [Pannello Risorse] I pannelli Risorse e Filtri vengono uniti in un nuovo pannello Risorse
* [Pannello Risorse] Il pannello Risorse ora supporta i seguenti tipi di risorse: materiali, filtri e immagini
* [Pannello Risorse] Tutte le Risorse per iniziare sono accessibili nella sezione Risorse per iniziare
* [Pannello Risorse] La sezione Risorse iniziali è di sola lettura
* [Pannello Risorse] Nuova sezione &quot;Le tue risorse&quot;
* La sezione [Pannello risorse] &quot;Le tue risorse&quot; è il luogo in cui puoi importare tutte le tue risorse
* [Pannello Risorse] Tutte le risorse in &quot;Le tue risorse&quot; vengono aggiunte in una cartella specifica nei tuoi documenti
* [Pannello Risorse] Collega le cartelle locali nel pannello Risorse per aggiungere nuove sezioni
* [Pannello Risorse] La ricerca verrà eseguita nella cartella corrente e nelle relative sottocartelle
* [Pannello Risorse] Spostarsi tra cartelle e sottocartelle con spostamenti
* [Pannello Risorse] Filtra la cartella corrente in base al materiale, al filtro o all&#39;immagine
* [Pannello Risorse] Combina diversi filtri per ottenere solo materiali e immagini
* [Pannello Risorse] Modifica la visualizzazione passando da una griglia o un elenco
* [Pannello Risorse] I filtri sono rappresentati dalla relativa icona
* [Pannello Risorse] Le immagini sono rappresentate con la loro anteprima
* [Pannello Risorse] Aumentando la larghezza si modifica il layout del pannello con una vista specifica per spostarsi tra le cartelle
* [Pannello Risorse] Nelle sezioni non di sola lettura, elimina una risorsa trascinandola sull’icona del cestino
* [Pannello Risorse] Facendo clic con il pulsante destro del mouse su una risorsa si apre un menu contestuale
* [Pannello Risorse] Dal menu di scelta rapida, accedi ai metadati della risorsa (nome, categoria, posizione)
* [Pannello Risorse] Dal menu di scelta rapida, elimina la risorsa (disponibile solo per sezioni di sola lettura)
* [Pannello Risorse] Dal menu di scelta rapida, sfoglia la tua risorsa in Adobe Bridge
* [Pannello Livelli] Icona Nuova per aggiungere direttamente un materiale di base sopra i livelli
* [Pannello Livelli] Scelta rapida - Maiusc + B per aggiungere un materiale di base sopra i livelli
* [Pannello Livelli] I livelli ora hanno un&#39;anteprima con miniatura (miniatura del materiale, icona del filtro o anteprima dell&#39;immagine)
* [Pannello Proprietà] Nuovo design del titolo del pannello Proprietà con il nome e la miniatura della risorsa
* [Pannello Proprietà] I livelli filtro ora supportano i predefiniti
* [Pannello Proprietà] Nel livello Importazione immagine, fai clic con il pulsante destro del mouse sull&#39;anteprima dell&#39;immagine per modificare l&#39;immagine in Photoshop
* [Adobe Bridge] Sfoglia la tua risorsa in Adobe Bridge. Bridge verrà avviato nel percorso della risorsa
* [Adobe Photoshop] La modifica in Adobe Photoshop aprirà l&#39;immagine in Photoshop pronta per essere modificata
* [Adobe Photoshop] Ad ogni salvataggio in Adobe Photoshop, l&#39;immagine modificata verrà ricaricata in Sampler
* [Substance 3D Designer] Le risorse inviate da Adobe Substance 3D Designer arriveranno direttamente nella sezione &quot;Le tue risorse&quot; del pannello Risorse
* [Esporta] Invia le risorse direttamente ad Adobe Substance 3D Painter e Adobe Substance 3D Stager
* [Esportazione] Invia materiali e luci ambiente ad Adobe Substance 3D Painter
* [Esporta] Invia luci ambiente ad Adobe Substance 3D Stager
* [Rendering] Le nuove proprietà dei materiali sono ora supportate e renderizzate in 3D
* [Rendering] Aggiunta di supporto per la brillantezza (Colore di lucentezza, opacità lucentezza e rugosità lucentezza)
* [Rendering] Aggiunta del supporto del rivestimento (colore del pelo, rugosità del pelo, rivestimento normale, Specular level del pelo e rivestimento IOR)
* [Rendering] Aggiunta del supporto delle Anisotropie (livello di Anisotropia e angolo di Anisotropia)
* [Rendering] Aggiunta del supporto del Specular edge color
* [Rendering] Attiva queste nuove proprietà nel pannello Impostazioni canale
* [Rendering] Introduzione di un nuovo modulo di rendering in tempo reale (2021) in versione beta
* [Rendering] Passa da una versione all’altra nel pannello Impostazioni visualizzatore
* [Rendering] Il modulo di rendering Realtime Engine (2021) supporta le proprietà di traslucidità, assorbimento e dispersione del materiale
* [Rendering] Il modulo di rendering in tempo reale (2021) introduce un nuovo modo di calcolare le ombre dalla luce ambientale
* [Rendering] Il modulo di rendering in tempo reale (2021) calcola in tempo reale l’irradianza della luce ambiente
* [Pannello Impostazioni shader] Nuovo pannello Impostazioni shader per modificare parametri specifici dello shader di materiale
* [Pannello Impostazioni shader] Nuovi parametri (Scala normale, Scala height, Livello height, Intensità di emissione, IOR, Intensità normale del pelo e Coat IOR)
* [Pannello Impostazioni shader] Parametri specifici per il motore in tempo reale 2021 (dispersione sottosuperficie, distanza di dispersione, spostamento rosso e diffusione Rayleigh)
* [Pannello Impostazioni shader] I valori delle impostazioni vengono salvati per risorsa.
* [Pannello impostazioni visualizzatore] È stata aggiunta un&#39;anteprima delle luci di ambiente predefinite
* [Pannello impostazioni visualizzatore] È stata aggiunta un&#39;anteprima delle trame predefinite
* [Pannello impostazioni visualizzatore] Parametro opacità nuovo ambiente
* [Pannello Impostazioni visualizzatore] Nuovo parametro di sfocatura ambiente (specifico per il modulo di rendering Realtime Engine 2021)
* [Localizzazione] Nuove traduzioni in tedesco e francese
* [Content] Nuovi materiali di partenza predefiniti
* [Contenuto] Nuove luci ambiente predefinite
* [Contenuto] Tutti i filtri sono stati aggiornati, puliti e ottimizzati
* [Content] Il filtro di regolazione è stato suddiviso in diversi filtri
* [Content] Nuovo filtro Luminosità/contrasto
* [Content] Nuovo filtro Tonalità/Saturazione
* [Contenuto] Nuovo filtro Vividezza
* [Content] Nuovo filtro Nitidezza
* [Contenuto] Nuova regolazione Normale/Height
* [Content] Nuovo filtro Pannelli
* [Contenuto] Nuovo filtro Sfumino
* [Content] New Weaves, filtro
* [Contenuto] Nuovo filtro Trasformazione alterazione
* [Content] Nuovo Height al filtro AO
* [Contenuto] Nuovo filtro da Height a normale
* [Content] Sostituisci colore - Sostituisci in nuovi canali supportati (brillantezza, rivestimento, Anisotropia,...)
* [Content] Variazione colore - Modalità manuale per selezionare esattamente i colori da modificare
* [Contenuto] Affiancatura: opzione per visualizzare il taglio delle cuciture
* [Contenuto] Affiancatura - opzione per dipingere le cuciture tagliate per una piastrellatura perfetta
* [Content] Match - opzione per aggiungere un materiale che corrisponda al suo colore e alla sua ruvidezza
* [Contenuto] Corrispondenza: ora funziona sulle immagini in modo che corrispondano al colore di un’altra immagine
* [Content] Luce ambiente - Nuovo filtro Temperatura colore
* [Content] Luce ambiente - Nuovo filtro Esposizione
* [Content] Luce ambiente - Nuovo filtro Anteprima esposizione
* [Content] Luce ambiente - Nuovo filtro Nadir patch
* [Content] Luce ambiente - Nuovo filtro Nadir extract
* [Content] Luce ambiente - Nuovi filtri Luci (Sfera, Linea, Forma, Piano)
* [Content] Luce ambiente - Nuovo filtro Toppa panorama
* [Content] Luce ambiente - Nuovo filtro Raddrizza orizzonte
* [Content] Luce ambiente - Nuovo filtro unione HDR

**Problemi noti:**

* [Realtime Engine 2021] Modifica del layout, arresto anomalo dell’applicazione
* [Realtime Engine 2021] Calcolo pesante, arresto anomalo dell&#39;applicazione
* [Pannelli] MacOS: i pannelli non ancorati sono presenti in tutte le applicazioni
* [Widget] I widget Trasformazione e Posizioni possono scomparire. Nascondi e Mostra il livello per farli apparire.
* [Esportazione] L’esportazione SBSAR di una luce ambiente perde la precisione a 32 profondità di bit
* [Pannello Risorse] Le risorse possono essere evidenziate quando si apre una cartella
* [Pannello Proprietà] Il ripristino dei parametri non reimposta l&#39;interfaccia utente della casella combinata
* [Localizzazione] La modifica della lingua non influisce sul pannello del progetto finché non viene ricreato
