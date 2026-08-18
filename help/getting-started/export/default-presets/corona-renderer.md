---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/getting-started/export/default-presets/corona-renderer.html"
breadcrumb-title: ''
description: Scopri come esportare i materiali da Substance 3D Sampler utilizzando il predefinito di rendering Corona per flussi di lavoro di visualizzazione architettonica.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Default Presets > Corona Renderer
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Corona Renderer
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '91'
ht-degree: 2%

---


# Corona Renderer

| Predefinito | Compatibilità | Descrizione output Impacchettamento |
| --- | --- | --- |
| Corona Renderer | <ul data-preserve-html="true"><li data-preserve-html="true">Rugosità/Metallico PBR</li><li data-preserve-html="true">Specular/lucidità PBR</li></ul> | **Diffusione**&#x200B;**RiflessioneGlossità** (\*)**ColoreRiflessione** (\*\*)**FrescoIOR** (\*\*\*)**Normale &#x200B;**&#x200B;**Spostamento**&#x200B;**&#x200B; Emissivo**&#x200B;**Opacità** |

>[!NOTE]
>
> **(\*)** Riflessione Glossiness: versione quadrata del canale glossiness (Glossiness \* Glossiness)
> 
> **(\*\*)** Colore di riflessione: esporta una mappa in cui il bianco indica materiali dielettrici e altri colori per materiali metallici
> 
> **(\*\*\*)** Francesi IOR: 1 diviso per il valore ior, ior viene generato dalla mappa metallica: 1,4 per i dielettrici, 100 per i metalli (colore nero)
