---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: Scopri come risolvere i problemi di avvio di Substance 3D Sampler su Linux per risolvere i problemi di avvio dell'applicazione e i messaggi di errore.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: L'applicazione non viene avviata su Linux
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# L&#39;applicazione non si avvia su Linux

L&#39;applicazione potrebbe non avviarsi su Linux con il seguente messaggio di errore in un terminale:

```
error while loading shared libraries: libicui18n.so.50
```


Ciò significa che l&#39;ICU della libreria ([Componenti internazionali per Unicode](http://site.icu-project.org/)) è mancante o che la versione installata è troppo recente. L’applicazione richiede la versione 50.

Per risolvere questo problema, installa la versione 50 da Gestione pacchetti o [scarica manualmente](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm) la versione mancante durante l&#39;installazione in **/usr/lib64**.
