---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/nvidia-driver-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni del driver NVIDIA per Substance 3D Sampler per ottimizzare le prestazioni della GPU e risolvere il problema di lentezza.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > NVIDIA Driver Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni driver NVIDIA
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---


# Impostazioni driver NVIDIA

Se si utilizza una GPU NVIDIA ma le prestazioni sono lente, vi sono due cause comuni:

1. Driver mancanti o non aggiornati
1. Sampler sta utilizzando la GPU errata

## Aggiorna driver

Per aggiornare i driver NVIDIA:

1. Vai alla pagina di download dei driver NVIDIA - <https://www.nvidia.com/Download/index.aspx?lang=en-us>
1. Selezionate il modello di GPU e scaricate i driver.
1. Installa i driver con il file scaricato.

Una volta installati i driver più recenti, apri Sampler per vedere se le prestazioni sono migliorate. Se le prestazioni sono lente, Sampler potrebbe utilizzare la GPU errata.

## Configurazione di Sampler

Per verificare quale GPU Sampler sta utilizzando, effettuate le seguenti operazioni:

![](../../assets/nvidiacontrolpanel.png)

1. Apri il pannello di controllo NVIDIA. Per aprire il Pannello di controllo NVIDIA, effettua una delle seguenti operazioni:
   1. Cercare NVIDIA nel Pannello di controllo utilizzando il menu Start
   1. Nell’area di notifica, fare clic con il pulsante destro del mouse sull’icona Geforce e selezionare Pannello di controllo NVIDIA.
1. Nel Pannello di controllo NVIDIA, seleziona Gestisci impostazioni 3D nel menu a sinistra.
1. Selezionare la scheda Impostazioni programma.
1. In Seleziona un programma da personalizzare, usa il menu a discesa per trovare Sampler.
1. Se Sampler non è elencato nel menu a discesa, utilizza Aggiungi.
   1. Individuare il percorso di installazione di Sampler (il percorso di installazione predefinito è **C:/Program Files/Adobe/Adobe Substance 3D Sampler**).
   1. Seleziona **Adobe Substance 3D Sampler.exe** dal percorso di installazione.
1. Dopo aver selezionato Sampler, in &quot;Selezionare il processore grafico preferito per questo programma&quot; selezionare &quot;Processore NVIDIA ad alte prestazioni&quot;.
1. Fai clic su Applica.

Dopo aver seguito questo processo, apri Sampler per vedere se le prestazioni sono migliorate.
