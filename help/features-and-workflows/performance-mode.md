---
description: Scoprite come utilizzare la modalità Prestazioni in Substance 3D Sampler per migliorare le prestazioni o anche eseguire Sampler su computer che non soddisfano i requisiti minimi di sistema.
title: Modalità Prestazioni
hold: true
source-git-commit: ce1229a1dfc9f6c8871c524b54a0641bdde19ee7
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 1%
---

# Modalità Prestazioni

La modalità Prestazioni riunisce tutte le impostazioni che possono rallentare il flusso di lavoro: limiti di risoluzione, ombre, qualità dello spostamento e tracciamento del percorso. Disattivate gli elementi non necessari e ottenete la velocità di risposta desiderata, in particolare su hardware più leggero.

>[!NOTE]
>
> La modalità Prestazioni viene attivata automaticamente con le limitazioni massime se l&#39;hardware non soddisfa i [requisiti minimi](../getting-started/system-requirements.md) di Sampler. In questo modo è possibile continuare a utilizzare Sampler su hardware meno potente.

## Attiva/disattiva modalità Prestazioni

La modalità Prestazioni può essere attivata/disattivata con il **pulsante Modalità prestazioni** in alto a destra della **finestra di Sampler**.

![](../assets/performance-mode-button.png)

## Modifica impostazioni modalità prestazioni

Utilizzare il menu a discesa accanto al **pulsante Modalità prestazioni** per controllare i limiti attivati dalla modalità Prestazioni.

![](../assets/performance-mode-settings.png)

| Impostazione | Descrizione |
| --- | --- |
| **Risoluzione massima anteprima** | La modalità Prestazioni riduce la risoluzione dell’anteprima per un rendering più veloce. Ciò non modifica la risoluzione delle risorse importate o del documento, ma la qualità del modulo di rendering della finestra della vista. |
| **Disattiva qualità spostamento** | Quando questa impostazione è attivata, la **modalità Prestazioni** blocca il **valore di qualità dello Spostamento** su 0, disabilitando l&#39;effetto di spostamento nella finestra della vista. Per materiali morbidi come piastrelle o tessuti fini, questo ha un impatto visivo minimo, ma può migliorare notevolmente le prestazioni. |
| **Disattiva ombre** | Trame e materiali rimossi possono proiettare ombre, creando un&#39;immagine più realistica a costo di prestazioni. Con **Disattiva ombre** attivato, la modalità Prestazioni disattiva tutta l&#39;elaborazione shadow, migliorando le prestazioni. |
| **Disattiva traccia percorso** | Il tracciamento del tracciato è un metodo di rendering avanzato che segue i tracciati luminosi mentre rimbalzano attraverso la scena, creando rendering fotorealistici. Tuttavia, il tracciamento del tracciato è costoso. Quando è attivata l&#39;opzione **Disattiva traccia percorso**, la modalità Prestazioni disattiva l&#39;opzione per attivare la traccia del percorso nel **riquadro di visualizzazione 3D**. |

>[!NOTE]
>
> È possibile accedere alla traccia del percorso dalla barra degli strumenti del **riquadro di visualizzazione 3D**.
>
> ![](../assets/enable-path-tracing.png)
>
> Se Traccia percorso non è abilitato, l&#39;attivazione della modalità Prestazioni con solo **Disattiva traccia percorso** attivata non avrà alcun effetto.
