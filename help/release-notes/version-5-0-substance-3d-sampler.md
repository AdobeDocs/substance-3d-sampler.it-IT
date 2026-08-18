---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-5-0-substance-3d-sampler.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Sampler versione 5.0 per scoprire i nuovi strumenti di digitalizzazione, le funzioni e i miglioramenti del flusso di lavoro.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 5.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '647'
ht-degree: 0%

---


# Versione 5.0

![](../assets/welcome_digitization_tool.jpg)

<b>Substance 3D Sampler 5.0</b> introduce metodi più semplici per passare a un gemello digitale materiale con scansioni e rendering di qualità superiore.

Le principali novità includono:

## Azioni rapide

Avvia tutti i flussi di lavoro principali di Sampler con un solo clic e prepara lo stack di livelli.

Ulteriori informazioni *[qui](../interface/panels/quick-actions-panel.md)*.

![](../assets/quick_actions_1440x810.png)

## Nuovo layout della schermata iniziale

Trova tutti i tuoi progetti, esercitazioni e inizia il tuo lavoro direttamente dalla home page.

Ulteriori informazioni *[qui](../interface/the-home-screen.md)*.

![](../assets/new_home_screen_layout_1440x810.png)

## Nuovo modulo di rendering

Scegliete tra tracciamento in tempo reale e tracciamento del percorso per migliorare la coerenza visiva e supportare nuove proprietà dei materiali. Salvate le istantanee del lavoro direttamente dalla vista 3D.

Ulteriori informazioni *[qui](../interface/2d-and-3d-viewport.md)*.

![](../assets/eclair_support_1440x810.png)

## Integrazione di HP Z Captis

Con HP Z Captis e Substance 3D Sampler, portate i materiali reali in digitale in pochi minuti.

Funzione disponibile per gli account Enterprise, Teams e Education.

Ulteriori informazioni *[qui](../pipeline-and-integrations/hp-z-captis-support/hp-z-captis-support.md)*.

![](../assets/hp_z_captis_1440x810.png)

## Note sulla versione V5.0

*(Rilasciato: 20 febbraio 2025)*

<b>Aggiunto</b>:



* [Onboarding] Nuova home page con accesso rapido a contenuti di apprendimento, progetto di esempio, azioni rapide e progetti recenti.
* [Onboarding] Inizia rapidamente con le nuove Azioni rapide, accessibili dalla pagina principale e dal pannello dedicato
* [Onboarding] [Contenuto] Le azioni rapide sono flussi di lavoro predefiniti che popolano la pila di livelli con la maggior parte dei livelli utilizzati
* [Onboarding] Possibilità di creare un nuovo progetto tramite un nuovo menu di avvio rapido, tramite azioni rapide o Progetto personalizzato
* [Onboarding] Possibilità di creare un progetto vuoto direttamente dalla home page tramite il pulsante dedicato
* [Vista 3D] Nuova rasterizzazione avanzata e tracciamento dei percorsi con nuove funzionalità di rendering (proprietà come rivestimento, lucentezza, translucenza, dispersione sottosuperficiale) e coerenza visiva nell&#39;ecosistema Substance
* [Vista 3D] Le impostazioni del visualizzatore sono ora accessibili direttamente nella vista 3D
* [Vista 3D] Possibilità di salvare un&#39;istantanea di rendering negli Appunti o nei file
* [Vista 3D] Visualizza una griglia per visualizzare l&#39;origine della scena
* [Vista 3D] Abilita il piano terreno per catturare ombre e riflessi
* [Vista 3D] Controlla la visibilità e l’opacità del piano terreno
* [capture 3D] Posizionare la trama a terra
* [Applicazione] Verifica la compatibilità hardware all&#39;avvio dell&#39;applicazione
* [Applicazione] La finestra di segnalazione degli arresti anomali ora si apre subito dopo l’arresto anomalo
* [Content] Apri un progetto di esempio per iniziare facilmente
* [Esportazione] Esportare lo shader di materiali standard Adobe in file USD
* [Intelligenza artificiale generativa] Seleziona il tag &quot;Non dedurre&quot; quando si utilizza l&#39;immagine come input nei flussi di lavoro da immagine a texture
* [Progetto] Le miniature vengono memorizzate nel file di progetto per velocizzare l’apertura dei progetti
* [Progetto] Impostazione nelle preferenze per memorizzare i dati della cache all&#39;interno del file di progetto, con modalità diverse (nessuna cache, cache leggera, cache completa)
* [Scripting] [Breaking change] Migrazione Qt a Qt6.15 - impatto sulla compatibilità dei plug-in esistenti
* [Scripting] I plug-in predefiniti e la cartella script si trovano ora nella cartella Documenti
* [Scripting] Nuova interfaccia utente per i plug-in per coerenza visiva con i pannelli principali di Sampler
* [Scripting] Esempi di plug-in di Access 2 per scoprire le funzionalità dei plug-in di Sampler
* [Scripting] Nuova funzione aperta\_3d\_catpure()
* [Scripting] Quando inserite un livello, controllate se è inserito sopra o sotto la posizione di destinazione

<b>Corretto:</b>

* [capture 3D] Arresto anomalo se non è possibile avviare Acquisizione oggetto in macOS
* [Applicazione] Arresto anomalo all’uscita
* [Applicazione] Blocco all’uscita durante l’aggiunta delle risorse al pannello Progetto
* [Applicazione] La ridenominazione di una risorsa di progetto non funziona a meno che non si preme invio
* [Applicazione] Le voci del menu Annulla e Ripeti non sono disattivate quando dovrebbero essere
* [Risorse] Impossibile eliminare le risorse dalla sezione Tutte le librerie del pannello Risorse
* [Content] Creatore di Atlas: usa la mappa di opacità esistente se presente
* [Content] Color ID Blend - Correggi selezione colore nel colore di base
* [Livelli] Evitare calcoli inutili quando si utilizzano i generatori
* [Livelli] La modifica di un generatore può causare l&#39;attivazione di troppi computer
* [Prestazioni] Miglioramento della gestione della memoria GPU
* [Prestazioni] La cache di rendering non può essere utilizzata al riavvio dell’app
* [Risorse] I file di sola lettura non sono visibili nel pannello Risorse
* [Scripting] Consente di riutilizzare un livello dopo averne aggiunto un altro
* [Scripting] La modifica ripetuta della struttura della serie di livelli in uno script può non riuscire

<b>Rimosso:</b>

* [Applicazione] Rimuovi il supporto per i file di immagine .dng e .nef
