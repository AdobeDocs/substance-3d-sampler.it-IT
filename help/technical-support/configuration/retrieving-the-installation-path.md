---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: Scopri come recuperare il percorso di installazione di Substance 3D Sampler su diverse piattaforme per scopi di scripting e configurazione.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Recupero del percorso di installazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 5%

---


# Recupero del percorso di installazione

Questa pagina raggruppa le informazioni sui modi per recuperare il percorso di installazione dell&#39;applicazione a seconda della versione e della piattaforma.

## Windows

### Creative Cloud desktop

1. Apri l&#39;editor del Registro di sistema di Windows (**regedit**).
1. Accedi alla chiave del Registro di sistema: **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Percorsi\**
1. Apri la sottochiave **Adobe Substance 3D Sampler.exe**
1. Il valore della chiave contiene il percorso del file eseguibile dell&#39;applicazione in cui è installato

>[!NOTE]
>
> Questa chiave del Registro di sistema è disponibile solo dalla versione 3.\
> Per le versioni precedenti, il percorso di installazione può essere recuperato dalle associazioni di file in **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**.

### Substance 3D autonomo

1. Apri l&#39;editor del Registro di sistema di Windows (**regedit**).
1. Accedi alla chiave del Registro di sistema: **HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. Trova la sottochiave corrispondente all’AppID della versione dell’applicazione (vedi tabella seguente)
1. Il valore della chiave contiene il percorso di installazione dell&#39;applicazione

| Versione | AppId |
| --- | --- |
| Da **1.x (2019.x) a 2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x (o versione successiva)** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### Vapore

L&#39;applicazione è installata nella sottocartella **steamapps/common/** della cartella di installazione di Steam.

## Mac

In Mac l’applicazione viene installata nei seguenti casi:

| Versione | Percorso |
| --- | --- |
| **3.x o versioni successive** | **/Applicazioni/Adobe Substance 3D Sampler.app** |
| **Precedente** | **/Applicazioni/Substance Alchemist.app** |

## Linux

Su Linux il pacchetto rpm è installato nel seguente percorso:

| Versione | Percorso |
| --- | --- |
| **3.x o versioni successive** | **/opt/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **Precedente** | **/opt/Allegorithmic/Substance\_Alchemist** |
