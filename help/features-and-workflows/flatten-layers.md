---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/features-and-workflows/flatten-layers.html"
breadcrumb-title: ''
description: Scopri come ridurre a livello singolo i livelli in Substance 3D Sampler per migliorare le prestazioni e semplificare il gruppo di livelli, comprendendone l’impatto.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Appiattisci livelli
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 1%

---


# Appiattisci livelli

La conversione della trasparenza dei livelli è utile per migliorare le prestazioni e semplificare la serie di livelli, ma è importante essere consapevoli dell’impatto che la conversione della trasparenza dei livelli può avere sul progetto.

## Qual è la funzione del pulsante Appiattisci livelli?

Appiattisci livelli unisce tutti i livelli sotto il livello attualmente selezionato in un singolo livello. Il livello appiattito risultante ha lo stesso aspetto dei livelli originali, ma non è più possibile apportare regolazioni ai singoli livelli originali.

### Perché ridurre a livello singolo?

Ogni volta che modificate un livello nello stack di livelli, Sampler deve ricalcolare l’output di quel livello e di tutti i livelli sovrastanti. Ogni livello aggiuntivo da calcolare significa maggiore tempo di elaborazione e utilizzo della memoria. La conversione della trasparenza di più livelli riduce il tempo e la memoria necessari per elaborare tali livelli. Ad esempio, invece di ricalcolare 10 livelli, Sampler deve elaborare solo un singolo livello.

Inoltre, la conversione dei livelli risulta in una pila di livelli più semplice, più facile da consultare e comprendere.

### In quali casi non è opportuno ridurre a livello singolo i livelli?

Tutti i livelli convertiti non sono accessibili singolarmente nella pila di livelli, quindi non sarai in grado di apportare modifiche ai parametri nel risultato della conversione. Di conseguenza, dovreste unire i livelli solo se non è più necessario apportare modifiche al risultato di tali livelli.

## Parametri livello ridotti a livello singolo

Mentre i parametri dei livelli originali vengono persi, i livelli convertiti dispongono di un proprio insieme di parametri che potete regolare per controllare come viene utilizzato ciascun canale risultante.

Per ogni canale, puoi:

* <b>Utilizzo dell&#39;output</b>: cambiare il canale per il quale viene utilizzato l&#39;output. Quando si appiattiscono i livelli, viene creato e denominato un TIFF per ciascun canale, che viene assegnato automaticamente a tale canale.
* <b>Opacità dal canale alfa</b>: attivate/disattivate se l’opacità è basata sul risultato del canale di Alpha.
* <b>Rimuovi</b>: rimuovi il canale da questo livello. Questa opzione può essere utile per i canali che non contengono informazioni utili. Ad esempio, è consigliabile rimuovere un canale di opacità completamente bianco, in quanto in questo modo si libera la memoria senza influire sui risultati visivi.
