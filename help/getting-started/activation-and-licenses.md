---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: Scopri come attivare e gestire le licenze per Substance 3D Sampler per iniziare a utilizzare l'applicazione e accedere a tutte le funzioni.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Attivazione e licenze
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 1%

---


# Attivazione e licenze

Questa pagina contiene informazioni su come attivare e gestire le licenze per iniziare a utilizzare Sampler.

## Processo di attivazione per tipo di applicazione

Il processo di attivazione dipende da dove hai acquistato o hai accesso a Sampler:

| Tipo applicazione | Processo di attivazione |
| --- | --- |
| Creative Cloud desktop | Consulta la pagina dedicata nella [documentazione HelpX](https://helpx.adobe.com/it/support/substance-3d-sampler.html).In caso di problemi, la [documentazione di Creative Cloud](https://helpx.adobe.com/it/creative-cloud/user-guide.html) può fornire risposte aggiuntive. |
| Vapore | Avvia il prodotto direttamente dalla libreria Steam. |
| Substance 3D autonomo | Consulta il processo di attivazione descritto di seguito. |

## Passaggi di attivazione

### Attivazione guidata

![](../assets/activation-wizard.png){width="350px"}

Sono disponibili tre opzioni:

* **Valutazione del prodotto**: le versioni di prova precedenti non sono più disponibili. Puoi invece avviare una versione di prova di 30 giorni per ogni applicazione Substance 3D [qui](https://www.adobe.com/creativecloud/3d-augmented-reality.html) o con Creative Cloud Desktop. Ogni versione di prova è indipendente dalle altre applicazioni Substance 3D, quindi puoi provarle una alla volta o tutte contemporaneamente.
* **Attivazione tramite un file di licenza**: attivare il prodotto con un file di licenza (**\*.key**) scaricato dalla pagina dell&#39;account nel [sito Web Substance 3D](https://store.substance3d.com/user) prima del 30 settembre 2022.
* **Attiva utilizzando il tuo account**: gli account Substance legacy non possono più essere utilizzati per l&#39;attivazione. [Ulteriori informazioni sugli account di Substance sono disponibili qui](https://helpx.adobe.com/it/substance-3d/unlisted/faq-end-of-life-accounts.html).

>[!WARNING]
>
> Per installare il file di licenza con l&#39;Attivazione guidata, assicurati di eseguire Sampler come amministratore e di disattivare temporaneamente l&#39;antivirus.

### Attivazione manuale

È possibile attivare manualmente Sampler inserendo il file **license.key** nella seguente cartella:

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Piattaforma</th><th>Versione</th><th colspan="2">Percorso</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>3.0</strong> o versione successiva</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td rowspan="2">Precedente</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Allegorithmic\Substance Alchemist</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Allegorithmic\Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>3.0</strong> o versione successiva</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">Precedente</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Allegorithmic/Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>3.0</strong> o versione successiva</td><td colspan="2">/home/[nome utente]/.local/share/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td>Precedente</td><td colspan="2">/home/[nome utente]/.local/share/Allegorithmic/Substance Alchemist</td></tr></tbody></table>

>[!NOTE]
>
> Alcune delle directory nei percorsi sopra menzionati potrebbero essere nascoste per impostazione predefinita. Digitate il percorso manualmente in Esplora file o visualizzate i file nascosti per visualizzarli.

>[!NOTE]
>
> Assicurati che il file sia denominato **license.key** altrimenti l&#39;applicazione non sarà in grado di trovarlo.

### Variabile di ambiente

È possibile eseguire l&#39;override del percorso controllato da Sampler per il file **license.key** con una [variabile di ambiente](../pipeline-and-integrations/environment-variables.md).
