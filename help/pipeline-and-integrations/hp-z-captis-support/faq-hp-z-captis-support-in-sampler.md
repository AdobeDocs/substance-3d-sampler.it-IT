---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/faq-hp-z-captis-support-in-sampler.html"
breadcrumb-title: ''
description: Accedi alle domande frequenti sul supporto di HP Z Captis in Substance 3D Sampler per trovare risposte sull'integrazione e l'utilizzo dell'hardware.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Domande frequenti sul supporto di HP Z Captis in Sampler
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1547'
ht-degree: 0%

---


# Domande frequenti

## Campioni di materiale

+++Quali casi di utilizzo sono trattati da Captis?
La soluzione copre casi d&#39;uso intersettoriali (automobilistico, abbigliamento, progettazione di prodotti, media e intrattenimento, architettura...). La modalità Studio consente l&#39;acquisizione da desktop (ripetibile, efficiente e semplice), mentre la modalità Esplora risorse consente l&#39;acquisizione da dispositivo mobile &#39;flessibile, in movimento, adattandosi a ogni situazione).

+++

+++Quali tipi di materiale possono essere scansionati e acquisiti con Captis?
È possibile scansionare e acquisire qualsiasi tipo di materiale, ad eccezione di più strati di rivestimento trasparente (le vernici per auto sono escluse dall’ambito di applicazione di Captis). Alcuni materiali specifici potrebbero richiedere un’elaborazione aggiuntiva in Sampler per ottimizzare i risultati. Si prega di notare che gli algoritmi di elaborazione saranno continuamente ottimizzati nel tempo.

+++

+++Quali sono le restrizioni sulle dimensioni o la forma del campione di materiale? I campioni devono essere piatti?
I sottotitoli possono scansionare un&#39;ampia varietà di dimensioni o forme di campioni di materiale. Viene fornito con magneti per spianare i campioni sulla vaschetta di campionamento. Sono disponibili diverse modalità per acquisire un campione di materiale con Captis:

* Modalità Studio: con la base studio sulla scrivania, in studio o in fabbrica, Captis preleverà campioni fino a 30cm x 30cm, con retroilluminazione per opacità. La profondità del vassoio di campionamento è di 1,8 CM.

* Modalità Esplora risorse: è possibile utilizzare l&#39;anello dell&#39;esploratore sul campo, sul set o in ambienti unici e abilitare l&#39;acquisizione flessibile per campioni di dimensioni superiori a 30 cm x 30 cm. Limitazione corrente: la modalità Explorer è ancora in una versione precedente e non è ancora ottimizzata (versione del 29 luglio 2024).

+++

## Software

+++Il dispositivo HP Z Captis richiede un abbonamento software o una licenza per l&#39;uso?
Il dispositivo Captis richiede una licenza attiva per Substance 3D Sampler Enterprise, Teams o University, disponibile nella raccolta Substance 3D alle stesse condizioni e condizioni d&#39;uso di qualsiasi abbonamento a Substance 3D.

Il dispositivo (HP Z Captis) e la licenza (Substance 3D Sampler) sono venduti separatamente.

+++

+++Qual è il livello di integrazione della suite Adobe Substance?
Il dispositivo HP Z Captis è completamente controllato e gestito tramite Adobe Substance 3D Sampler: è possibile visualizzare in anteprima e avviare l&#39;acquisizione da Substance 3D Sampler; una volta completata l&#39;acquisizione, i canali PBR verranno caricati automaticamente come livello e verrà creato un materiale 3D. Potete continuare a elaborare i vostri materiali con tutti gli strumenti e i filtri disponibili in Sampler.

Una volta che il materiale acquisito è in Substance 3D Sampler, puoi esportarlo in qualsiasi applicazione della suite Substance 3D (Substance 3D Designer, Painter, Stager) e in qualsiasi applicazione di terze parti che supporti la Substance, tra cui 3DS Max, Maya, Blender, Unreal Engine, CLO, Browzwear, VRED, Rhino, Cinema4D e molte altre (consulta l&#39;elenco completo qui: <https://www.adobe.com/it/products/substance3d/plugins.html>).

+++

+++Quali sono le specifiche consigliate per utilizzare Substance 3D Sampler con Captis?
Le specifiche hardware di Sampler sono disponibili [qui](system-requirements-to-use-hp-z-captis.md).

+++

+++Il flusso di lavoro HP Z Captis è disponibile sia su Windows che su Mac?
A partire dalla versione del 20 febbraio 2025, il flusso di lavoro Sampler con HP Z Captis è disponibile solo su Windows.

+++

+++Dove posso trovare la versione di Substance 3D Sampler con il flusso di lavoro HP Z Captis?
A partire dalla versione del 20 febbraio 2025, è possibile accedere al flusso di lavoro Adobe Substance 3D Sampler con Captis come parte delle normali build di Substance 3D Sampler, scaricate dall’app desktop Creative Cloud. Non è più necessario scaricarli da Adobe Prerelease.

+++

+++Cosa non è ancora disponibile?
*Limitazioni a partire da agosto 2025 (build di Sampler 5.1.0):*

* Il flusso di lavoro Sampler con HP Z Captis è disponibile solo per ora su Windows.

* Le cinque mappe esportate oggi sono Colore base, Rugosità, Normale, Height, Opacità.

* La modalità Esplora risorse è ancora una versione precedente e non è ancora ottimizzata.

* La suddivisione in porzioni viene eseguita nello stack di livelli Sampler utilizzando i filtri di suddivisione in porzioni correnti.

+++

+++Quali canali PBR sono disponibili?
A partire dalla versione del 7 agosto 2025, le cinque mappe esportate sono il Colore di base, Rugosità, Normale, Height e Opacità. La pipeline di elaborazione corrente non gestisce ancora la mappa Metalness.

+++

+++La suddivisione in porzioni viene effettuata automaticamente?
La suddivisione in porzioni viene eseguita nella pila di livelli di Sampler utilizzando i filtri di suddivisione in porzioni correnti.

Il filtro Porzione automatica può essere utilizzato per affiancare automaticamente materiali con una struttura ripetitiva definita o piccoli pattern, con un minimo di 3 pattern in ogni direzione. Ulteriori informazioni su questo filtro sono disponibili nella [sezione dedicata della documentazione](../../filters/tools/auto-tiling.md).

+++

+++Con quali formati possono essere esportati i materiali scansionati?
HP Z Captis è gestito in modo nativo da Adobe Substance 3D Sampler. HP Z Captis acquisisce 64 immagini raw (recuperabili dalla cartella locale) e mappe PBR (elaborate dalle immagini raw acquisite e caricate automaticamente in Substance 3D Sampler). Substance 3D Sampler creerà un materiale 3D basato sui canali PBR caricati automaticamente nello stack di livelli Sampler dopo l’acquisizione.

Da Adobe Substance 3D Sampler, puoi esportare il tuo materiale digitale in qualsiasi formato di esportazione disponibile in Substance 3D Sampler: come file Substance (.SBS e .SBSAR) o come texture bitmap, tra cui .PNG, .JPG, .TIFF... (consulta i dettagli nella pagina Web della documentazione Sampler: [https://helpx.adobe.com/it/substance-3d-sampler/getting-started/export.html](../../getting-started/export/export.md)).

+++

+++Qual è la differenza tra LDR e HDR durante l’acquisizione?
Durante l’anteprima, puoi scegliere il tipo di output tra LDR (low dynamic range) e HDR (high dynamic range).\
Anche se si sceglie LDR, le mappe HDR verranno acquisite e salvate sul dispositivo.\
Si consiglia di selezionare l&#39;LDR, in quanto ciò renderà più gestibile la dimensione del progetto in Sampler e in qualsiasi app di terze parti in cui verrà utilizzato il file sbsar.

+++

## Elaborazione

+++Come posso utilizzare Captis nella mia pipeline 3D corrente se utilizzo formati di file, standard e specifiche specifici o applicazioni di terze parti?
HP Z Captis è gestito in modo nativo da Adobe Substance 3D Sampler. Una volta acquisito e digitalizzato il vostro campione di materiale in Substance 3D Sampler, potete esportare senza problemi i vostri materiali digitali:

In qualsiasi applicazione dell’ecosistema Substance 3D (compresi Substance 3D Designer o Substance 3D Painter che supportano vari formati di esportazione: https://experienceleague.adobe.com/it/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats).

In tutte le applicazioni che integrano il formato di file Substance come 3DS Max, Maya, Blender, C4D, Rhino, Browzwear, CLO... (vedere l&#39;elenco completo qui: <https://www.adobe.com/it/products/substance3d/plugins.html>). Se utilizzate un’applicazione non presente nell’elenco, potete sempre esportare le immagini di texture PBR e collegarle manualmente a qualsiasi applicazione che non supporti il formato nativo del file di Substance.

+++

+++Quante foto vengono scattate per creare le mappe?
[8 pannelli luminosi + 1 retroilluminazione] x [8 stati di polarizzazione] x [8 esposizioni di bracketing per HDR] x [4 overdraw to reduced noise] = 2048 + 256 (per retroilluminazione)

+++

## Gestione dei dispositivi

Per ulteriori informazioni sul dispositivo e sulle relative specifiche, visita il [sito Web HP](https://www.hp.com/us-en/workstations/z-captis.html "HP Z Captis").

+++È possibile modificare l&#39;indirizzo IP del dispositivo?
Per modificare l&#39;indirizzo IP del dispositivo è possibile modificare il file di Windows C:\Windows\System32\drivers\etc\hosts.txt by aggiungendo una riga aggiuntiva:

Ad esempio, puoi aggiungere 192.168.55.1 captis-device e quindi in <b>Impostazioni di Sampler > Archiviazione e cache > Acquisizione materiale > Indirizzo Captis</b> sostituire l&#39;IP con captis-device

+++

## Problemi di utilizzo

+++Sampler non rileva HP Z Captis.
Assicurarsi che HP Z Captis sia collegato a una porta USB 3.0.

Assicurarsi che il cavo USB sia collegato alla base del HP Z Captis, non al cono.

+++

+++La mia anteprima è completamente nera nella finestra di Sampler.
Assicurati di aver rimosso la protezione della fotocamera.

+++

+++La copia dei file da HP Z Captis sul computer è lenta.
Assicurarsi che HP Z Captis sia collegato a una porta USB 3.0.

Se viene chiesto di recuperare sia il materiale che le immagini fotometriche, è normale che la copia richieda più tempo.

+++

+++Sampler non ha copiato le immagini nel computer. È necessario riavviare la scansione?
No, non è vero. Potete sfogliare il contenuto del dispositivo e copiare le immagini presenti nella cartella dell’Adobe utilizzando l’interfaccia Esplora file del sistema operativo.

+++

+++Il menu indica che il dispositivo è in modalità di ripristino.
Premere il pulsante di alimentazione per alcuni secondi per spegnerlo. Accendila di nuovo.

+++

+++Ho spostato il cono dalla sua base all&#39;anello dell&#39;esploratore e non posso più scansionarlo.
Si consiglia di spegnere HP Z Captis prima di scollegarlo dalla sua base o dall&#39;anello dell&#39;esploratore.

+++

+++L&#39;esportazione del mio materiale in SBSAR è lenta.
Verificate che le immagini non siano in formato a 32 bit a virgola mobile nel pannello Proprietà.

Puoi anche impostare il livello di compressione su &quot;nessuno&quot; per velocizzare l’esportazione.

+++

+++Voglio cambiare il percorso di salvataggio dei materiali acquisiti e delle immagini fotometriche.
È ora possibile modificare la posizione in cui verranno salvati i materiali acquisiti e le immagini fotometriche, in Modifica > Preferenze > Archiviazione e cache > Acquisizione materiale.

+++

+++La finestra è più grande dello schermo e non è possibile ridimensionarla.
La finestra Maiuscole non è infatti ridimensionabile. È possibile che si stia utilizzando un ingrandimento dello schermo non gestito. Captis supporta quanto segue:

* Risoluzione: 1920x1080
  * Ingrandimento massimo: 100%

* Ingrandimento massimo: 100%

* Risoluzione: 2560x1440
  * Ingrandimento massimo: 125%

* Ingrandimento massimo: 125%

* Risoluzione: 3840x2160
  * Ingrandimento massimo: 200%

* Ingrandimento massimo: 200%

* Le risoluzioni inferiori a 1920x1080 non sono supportate.



+++
