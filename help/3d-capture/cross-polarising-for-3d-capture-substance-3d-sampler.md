---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/cross-polarising-for-3d-capturesubstance-3d-sampler.html"
breadcrumb-title: ''
description: Scoprite come utilizzare le tecniche di polarizzazione incrociata in Substance 3D Sampler per ridurre i riflessi e migliorare la qualità del Capture 3D.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Polarizzazione incrociata per capture 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---


# Polarizzazione incrociata per capture 3D

>[!WARNING]
>
> Il supporto per capture 3D è stato rimosso dalla versione 5.1 di Sampler.

## Cross-polarizing

In questa guida utente spiegheremo come gestire gli oggetti riflettenti e i problemi che causano, e come utilizzare la polarizzazione della luce per risolverli.

Preferisci saperne di più in un&#39;esercitazione video? [qui](https://youtu.be/VWsbP56MDk0?si=Hdp7vblJB6L1RPxK "Esercitazione sulla polarizzazione incrociata").

![](../assets/polarized-lens-3d-capture.png)

Quando la luce colpisce una superficie, di solito si riflette in modo diffuso, rimbalzando in modo uniforme, conferendo alla superficie l&#39;aspetto cromatico. Ma a seconda della ruvidezza della superficie, una certa luce può essere riflessa direttamente verso l’occhio o la fotocamera. Questo <b>riflesso specular</b> cambia a seconda dell&#39;angolo di visualizzazione.

La fotogrammetria funziona allineando motivi ed elementi visivi tra le fotografie; presuppone che l&#39;aspetto di un oggetto non cambi tra ogni foto consecutiva. Il riflesso specular qui è un effetto indesiderato. Un oggetto con forma lieve può avere solo un rivestimento riflettente, ma gli oggetti che sono in metallo possono essere molto più complessi e richiedere più impegno per risolverli. Affronteremo il caso lieve in questa guida utente. Dobbiamo solo immortalare un colore di base perfetto, incontaminato dalle luci degli specular. Una volta acquisita, è facile aggiungere nuovamente la riflettività in 3D.

Per risolvere questo problema, possiamo filtrare i riflessi degli specular utilizzando un metodo chiamato <b>polarizzazione incrociata</b>. Quando la luce è polarizzata, tutte le onde sono orientate nella stessa direzione. Se poi lo polarizzate di nuovo, in direzione perpendicolare, viene completamente bloccato, rendendolo invisibile.

La polarizzazione influisce principalmente sulla luce specular, in quanto si tratta di raggi di luce focalizzati che viaggiano in una direzione specifica, in contrapposizione alla luce diffusa diffusa diffusa che vogliamo mantenere.

Polarizzate la luce con un filtro polarizzante, uno speciale foglio trasparente che filtra le onde. Sono disponibili in diverse forme, utilizzeremo filtri di vetro a vite per i vostri obiettivi, oltre a fogli di pellicola polarizzanti in stile fai da te

L&#39;idea di base è <b>aggiungere un filtro alla luce</b> e <b>all&#39;obiettivo</b> e impostarli in modo che siano <b>perpendicolari l&#39;uno all&#39;altro</b>. Ciò significa che dovrai regolare l&#39;orientamento del filtro ruotandolo. Una volta impostate, i riflessi di specular di quella luce diventano invisibili. È molto speciale da vedere: ruotare i filtri può eliminare completamente tutti i riflessi da una luce polarizzata.

![](../assets/polarizing-before-after-3d-capture.png)

Per ottenere ottiche ottimali, potete acquistare un filtro polarizzante per l’obiettivo, consentendo di ottenere foto nitide e ben definite. Obiettivi diversi hanno dimensioni diverse filettate per avvitare i filtri, quindi assicuratevi di scegliere quello giusto per il vostro obiettivo preferito o alcune dimensioni per obiettivi multipli se state sperimentando.

La polarizzazione delle luci è più semplice e conveniente: <b> fogli di pellicola polarizzante</b> sono relativamente economici. Potete usare un intero foglio o ritagliare dei pezzi. Si consiglia di tagliare dei pezzi circolari che coprano l’intera luce, in quanto ciò ne facilita la rotazione. Alcune luci sono migliori per questo, potrebbero avere un piccolo portafiltri, o magneti per tenere le lenzuola in posizione. In caso contrario, il nastro adesivo funziona sempre!

Assicuratevi di <b>aggiungere il polarizzatore dopo eventuali diffusori</b>, in quanto la diffusione della luce annulla qualsiasi polarizzazione.

L&#39;anello più economico lampeggia a vite nel vostro slot di filtro, e potrebbe non permettere di collegare più un filtro obiettivo. Inoltre, non hanno alcun modo di collegare i filtri di polarizzazione alla luce del flash, quindi dovrete crearne di nuovi. Solo i modelli di fascia alta supportano correttamente questa funzionalità.

<b>La rotazione e la corrispondenza dei polarizzatori nella configurazione devono essere eseguite costantemente</b>. Il filtro dell&#39;obiettivo deve essere completamente perpendicolare a tutte le luci, l&#39;unico modo per farlo è guardare il display della fotocamera e regolare le cose. Mi piace iniziare con la registrazione di un singolo foglio sul flash, quindi regolare il filtro dell&#39;obiettivo per bloccare i riflessi del flash. È possibile farlo solo scattando una foto o accendendo a secco il flash. È un po’ complicato: potete contrassegnare l’orientamento corretto sul filtro dell’obiettivo con un marcatore, quindi cercare di non toccare più l’obiettivo e il filtro del flash.

Regolare la polarizzazione delle luci video è diverso, ma più semplice. Dovrete regolare costantemente le luci mentre le spostate o quando regolate il height della fotocamera. È sufficiente <b>ruotare il foglio finché non appare correttamente sullo schermo della fotocamera</b>.

<b>Ogni singola sorgente luminosa visualizzata nei riflessi deve essere polarizzata</b>, quindi potrebbe essere necessario chiudere le finestre o spegnere gli schermi.

Una volta impostato correttamente, dovresti essere in grado di acquisire un oggetto come se fosse completamente opaco, senza riflessi e senza luce. Proprio come la trama con la sola texture del colore di base applicata, consente di catturare oggetti riflessivi difficili.

Ora scopri di più su [come elaborare il tuo Capture 3D utilizzando Substance 3D Sampler](processing-advanced-3d-captures.md).
