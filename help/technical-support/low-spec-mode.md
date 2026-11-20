---
title: Modalità a specifiche basse
description: Informazioni sulla modalità a basse specifiche, attivata da Sampler quando l'hardware non soddisfa i requisiti minimi di sistema.
hold: true
source-git-commit: 59761aab02bff266047813f1714e3f53ddcb805c
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%
---

# Modalità a specifiche basse

![](../assets/v6.1/6_1-Checked.png)

Se l&#39;hardware non soddisfa i [requisiti minimi](../getting-started/system-requirements.md) di Sampler, Sampler verrà avviato automaticamente in modalità con specifiche basse, che si comporta come la [modalità Prestazioni](performance-mode.md) senza la possibilità di modificare le impostazioni.

## Limitazioni della modalità con specifiche ridotte

La modalità con specifiche basse attiva automaticamente la **modalità Prestazioni** con tutte le funzioni disattivate e una risoluzione di anteprima massima di 2048 × 2048.

La modalità con specifiche basse disattiva:

* **Spostamento**
* **Ombre**
* **Traccia percorso**

Inoltre, la modalità con specifiche basse impedisce le esportazioni superiori a 2048 px × 2048 px.

![](../assets/low-spec-mode-export-message.png)

*Questo messaggio viene visualizzato nella **finestra Esportazione**in **modalità con specifiche basse**per fornire informazioni aggiuntive.*

## Come capisco se è attivata la modalità a basse specifiche?

Quando avvii Sampler, se l’hardware non soddisfa i requisiti minimi, viene visualizzata una finestra che indica i requisiti non soddisfatti e che offre la possibilità di continuare ad avviare Sampler.

L&#39;immagine seguente mostra un esempio di un computer con meno di 8 GB di VRAM.

![](../assets/low-device-specs-popup.png)

Se scegli di **avviare comunque**, Sampler verrà avviato in **modalità con specifiche basse**. Se hai utilizzato la casella di controllo nel messaggio precedente per non mostrare e avviare comunque, vedrai comunque il seguente banner ai successivi avvii.

![](../assets/low-spec-mode-banner.png)

Infine, quando è attivata la modalità **Specifiche basse**, non è possibile disattivare la modalità Prestazioni o regolare le impostazioni di tale modalità.

![](../assets/performance-mode-locked.png)
