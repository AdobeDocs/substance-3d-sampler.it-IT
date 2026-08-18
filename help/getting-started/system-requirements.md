---
helpx_url: 'https://helpx.adobe.com/it/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: Verifica i requisiti di sistema di Substance 3D Sampler per verificare che hardware e software soddisfino gli standard di compatibilità.
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Requisiti di sistema
user-guide-description: ''
user-guide-title: ''
source-git-commit: cd61972eaf1567863dc8c3549a1c90c84ffee825
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 1%

---


# Sistemi supportati

Di seguito è riportato un elenco di hardware e sistemi supportati dall&#39;applicazione:

>[!WARNING]
>
> I seguenti driver Nvidia causano instabilità durante l&#39;esecuzione di Sampler:
>
> * 610.47
>
> Si consiglia di evitare di utilizzare queste versioni: preferibilmente, utilizzare una versione più recente o, se non è disponibile una versione più recente, utilizzare la versione precedente.

## Windows

|  | Minimo | Consigliato | Ottimale |
| --- | --- | --- | --- |
| **SO** | Windows 11 64 bit versione 23H2 | Windows 11 64 bit versione 24H1 | Windows 11 64 bit versione 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Archiviazione** | SSD con 30 GB di spazio disponibile | SSD con 50 GB di spazio disponibile | SSD con 70 GB di spazio disponibile |

### macOS

|  | Minimo | Consigliato | Ottimale |
| --- | --- | --- | --- |
| **SO** | macOS 13 Ventura | macOS 14 Sonoma | macOS 26 Tahoe |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 24 GB | 32 GB | 64 GB |
| **Archiviazione** | SSD con 30 GB di spazio disponibile | SSD con 50 GB di spazio disponibile | SSD con 70 GB di spazio disponibile |

### Linux

| Enterprise | Vapore |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22,04 |

>[!NOTE]
>
> Se il sistema soddisfa i requisiti di sistema indicati in precedenza, ma le prestazioni sono ancora lente, Sampler potrebbe utilizzare la GPU errata.
>
> Se si utilizza una GPU NVIDIA, [modificare la GPU utilizzata da Sampler seguendo le istruzioni riportate in questa pagina](../technical-support/configuration/nvidia-driver-settings.md).

## Raccomandazioni generali

* Per lavorare in condizioni ottimali, consigliamo un monitor con una risoluzione superiore a 1 MegaPixel e una larghezza superiore a 1280 pixel.
* Molte app Substance dipendono da OpenSSL 1.1.1 per la compatibilità con RHEL8/9. Per i sistemi con versioni OpenSSL più recenti, dovrai fornirlo manualmente.

## Configurazione non supportata

**Windows**

* La macchina virtuale non è supportata.
* Windows Server non è supportato.

**Mac**

* Sono supportate solo le configurazioni Apple ufficiali.
* Le eGPU non sono attualmente supportate e potrebbero presentare problemi di stabilità.

**Linux**

* I driver Mesa su Linux non sono supportati.

**Qualsiasi piattaforma**

* Le GPU integrate non sono supportate su CPU x86-64 (Intel, AMD).
* L’utilizzo di Sampler in combinazione con software di terze parti che intercetta le chiamate Sampler ai driver grafici non è supportato. Tali software includono:
  * Iniettori di post-elaborazione come tamponi che applicano Color Grading, effetti fotocamera, ...
  * Sovrapposizioni su schermo come mirini personalizzati, metriche delle prestazioni GPU, interfacce per lo streaming video...

## Versioni minime del driver GPU

Di seguito è riportato un elenco delle versioni minime dei driver della GPU necessarie per l&#39;esecuzione dell&#39;applicazione senza problemi. Questo elenco è soggetto a modifiche man mano che vengono rilasciate nuove versioni.

Per scaricare nuovi driver, vedere: [La GPU contiene driver obsoleti](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers).

| SO | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro/FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04 o versioni successive *o* 535.54.03 o versioni successive | Radeon 23.20 Pro 23.Q3 | Non supportato |

>[!NOTE]
>
> In **Mac OS** il driver della GPU è fornito dal sistema operativo stesso. Esegui l’aggiornamento alla versione più recente del sistema operativo per accedere al driver più recente.

## Lingue

L&#39;interfaccia software è disponibile nelle seguenti lingue:

* Inglese
* Tedesco
* Francese
* Giapponese
* Coreano
* Cinese
* Italiano
* Portoghese
* Spagnolo
