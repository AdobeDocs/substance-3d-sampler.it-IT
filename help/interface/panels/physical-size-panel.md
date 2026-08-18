---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/interface/panels/physical-size-panel.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il pannello Dimensioni fisiche in Substance 3D Sampler per impostare dimensioni reali per materiali e texture.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Physical Size Panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pannello dimensioni fisiche
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 13%

---


# Pannello dimensioni fisiche

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/3-2-0-cover.png)

</td>
<td width="58.30%" style="border: 0;" valign="top">

Utilizza il **pannello Dimensioni fisiche** per configurare la dimensioni fisiche reale dei campioni e delle immagini acquisiti.

</td>
</tr>
</table>

Corrispondenza della dimensioni fisiche reale dei campioni e delle immagini scansionati in un contesto digitale per creare immagini fisicamente accurate tra le applicazioni.\
I seguenti strumenti e parametri consentono di definire la dimensioni fisiche dei materiali e di creare immagini accurate e realistiche quando applicate il materiale a un oggetto.

## Imposta le dimensioni fisiche

>[!NOTE]
>
> Per impostare la Dimensioni fisiche del materiale, è necessario disporre di un livello di importazione di immagini.

Per calcolare la dimensioni fisiche dell&#39;esempio o dell&#39;immagine, abilita **Imposta dimensioni fisiche**.

### Dimensioni immagine di input

Questa sezione consente di impostare manualmente le dimensioni del campione e fornisce strumenti per calcolare automaticamente la dimensioni fisiche.

**Livello di riferimento:** Riferimento all&#39;immagine da cui viene calcolata la dimensioni fisiche.\
**Larghezza (X):** impostare la larghezza fisica del livello di riferimento\
**Height/i:** Impostare il height fisico del livello di riferimento\
**Strumenti:**

![](../../assets/screenshot-2022-01-17-at-13-59-37.png)

La diagnostica di misurazione consente di misurare la distanza tra due punti sull&#39;immagine (solo a scopo informativo).

![](../../assets/screenshot-2022-01-17-at-14-00-06.png)

Lo strumento di misurazione automatica consente di ottenere una stima delle dimensioni fisiche del campione in base ai metadati dell&#39;immagine (dpi). Questo metodo è accurato solo con i campioni scansionati.

![](../../assets/screenshot-2022-01-17-at-14-00-24.png)

Lo strumento Misura (Measure) consente di calibrare la dimensioni fisiche definendo la distanza fisica tra due feature del campione. Questo è in genere il metodo migliore per calcolare la dimensioni fisiche del campione.

### Superficie della trama 3D

Questi strumenti consentono di impostare l&#39;aspetto della superficie del materiale.

**Scala fisica:** attivare o disattivare la scala fisica. La scala fisica è la circonferenza della trama lungo i tre assi.\
Ridimensionate il materiale con valori fisici. Manipolazione della larghezza (X) del Height (Y) e della Profondità (Z).\
**Affiancamento texture:** impostate l&#39;affiancamento del materiale

### Materiale output

Aiuta a visualizzare l&#39;output del materiale con il suo aspetto reale.

**Visualizzazione con rapporto fisico:**\
La visualizzazione nella finestra della vista 2D rispetta le proporzioni fisiche.\
**Scala Height:** impostata/calcolata dalla finestra della vista 3D in base alla scala fisica.
