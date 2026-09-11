---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/interface/panels/share-panel.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il pannello Esporta in Substance 3D Sampler per esportare i materiali come file o inviarli direttamente ad altre applicazioni.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Export panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pannello Esporta
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 3%

---


# Pannello Esporta

Nel <b>pannello Esportazione</b> potete esportare le risorse come file generali o inviarle direttamente ad altre applicazioni.

## Invia a...

Le opzioni Invia a... consentono di inviare direttamente la risorsa ad altre applicazioni installate nel sistema. In genere è molto più veloce rispetto all’importazione e all’esportazione delle risorse.

Attualmente Sampler supporta l&#39;invio a:

* **Substance 3D Painter**: importa materiali e ambienti che puoi utilizzare durante la creazione di texture delle risorse.
* **Substance 3D Stager**: importa luci ambientali per cambiare l&#39;umore della scena. Disponibile solo con luci ambientali, disattivato per i materiali.

I materiali vengono sempre inviati come SBSAR, negli ambienti come EXR.

## Esporta

Fai clic su **Esporta come...** per esportare la risorsa su cui stai attualmente lavorando. Scegliete se modificare le Impostazioni generali o le Impostazioni materiale dal menu a sinistra.

### Impostazioni generali

Con le impostazioni Generali selezionate, potete modificare il nome del materiale e la posizione di salvataggio. Potete anche attivare o disattivare la creazione di una sottocartella per il materiale. Questo può essere utile quando si esporta in un formato di immagine che crea più file.

### Impostazioni dei materiali

Con le impostazioni del materiale selezionate, potete modificare vari parametri per controllare come verrà esportato il materiale:

| Impostazione | Descrizione |
| --- | --- |
| Formato | Scegli se esportare come SBS, SBSAR o come raccolta di immagini in un formato immagine specifico |
| Predefinito | Seleziona un predefinito per organizzare automaticamente l’esportazione per un’applicazione specifica. [Ulteriori informazioni sui predefiniti sono disponibili qui](../../getting-started/export/default-presets/default-presets.md). I predefiniti sono disponibili solo quando è selezionato un formato di immagine. |
| Compressione | Scegli se la compressione dà priorità alla velocità o all&#39;efficienza <br> <ul> <li> **Automatico**: consenti a Sampler di scegliere. <li> **Migliore**: ottimizzazione dell&#39;efficienza della compressione per file più piccoli. <li> **Nessuno**: l&#39;assenza di compressione comporta un&#39;apertura e una chiusura più rapide dei file esportati, ma dimensioni maggiori. </ul> |
| Risoluzione | Modifica la risoluzione dell’esportazione. Questa opzione viene visualizzata in modo diverso in base al formato selezionato <br> <ul> <li> **SBSAR/SBS**: selezionare una larghezza e un height predefiniti per il materiale. Questi possono essere aggiornati in seguito. <li> **Formato immagine**: scegli tra **Output dei livelli**, che esporta ogni mappa alle dimensioni definite dalla Pila livelli, o **Ignora tutto**, che consente di specificare una larghezza e un height per l&#39;esportazione. |
| Modello di materiale | Scegliete se esportare come Adobe Standard Material o come materiale OpenPBR. L&#39;opzione selezionata dipende dalle altre applicazioni utilizzate nella pipeline. Saranno disponibili diversi canali in base al Modello di materiale. |
| Canali | Attivate/disattivate i canali da esportare come parte della risorsa. |

>[!NOTE]
>
> Per ulteriori informazioni sulle opzioni della finestra di dialogo Esporta e altre informazioni quali i formati di file, consulta l&#39;[articolo sull&#39;esportazione](../../getting-started/export/export.md) e il relativo [sottoarticolo nella finestra Esporta](../../getting-started/export/export-window/export-window.md).

Quando sei soddisfatto delle impostazioni di esportazione, fai clic su **Esporta**. L’esportazione verrà visualizzata nella coda di esportazione, con un elenco delle esportazioni recenti. Fai clic sull&#39;icona della cartella su qualsiasi esportazione per aprire il percorso del file di quell&#39;esportazione.
