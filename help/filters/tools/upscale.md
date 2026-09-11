---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/upscale.html"
breadcrumb-title: ''
description: Utilizza lo strumento Ingrandisci di Substance 3D Sampler per aumentare la risoluzione della texture utilizzando una tecnologia di upscaling basata sull'intelligenza artificiale.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Miglioramento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 2%

---


# Miglioramento

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![Icona Filtro](../../assets/SAPR_SuperResolution_18_N_D.png)

**In:** Strumenti

</td>
<td style="border: 0;" valign="top">

## Descrizione

Il filtro <b>Ingrandisci </b> utilizza l&#39;IA per eseguire il upsampling dei canali PBR (BaseColor, Rugosità, Normale, Metallico, Height) dai livelli sottostanti.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">



</td>
<td style="border: 0;" valign="top">

![](../../assets/F5W_vAHaYAQLsz7.jpg)

</td>
</tr>
</table>

In questo esempio si inizia con un&#39;immagine di 1024x1024px ma il risultato è di 4098x4098px. I risultati che utilizzano il filtro <b>Ingrandimento</b> sono più definiti.

</td>
<td style="border: 0;" valign="top">

>[!NOTE]
>
> **Filtro avanzato**
> 
> <b>Ingrandimento</b> è un filtro avanzato.\
> Per usarlo alla sua capacità massima ed evitare risultati sfocati, ti consigliamo di impostare i livelli sotto <b>Ingrandisci</b> in Input livello Max o Input livello Min.
> 
> Non ci sono limiti al numero di filtri <b>Ingrandisci </b> utilizzabili, ma l&#39;upsampling al di sopra della risoluzione di 8k potrebbe influire in modo significativo sulle prestazioni.

</td>
</tr>
</table>

## Parametri

<b>Parametri di base</b>

* <b>Esempio precedente</b>: Attiva/Disattiva gruppo pulsanti\
  Scegliere il fattore di moltiplicazione da aumentare

## Procedure

![](../../assets/SAPR_Upscale_screen_001.png)

Nell&#39;immagine precedente, un&#39;immagine a bassa risoluzione viene elaborata da [Image to Material (AI Powered)](image-to-material.md).

![](../../assets/SAPR_Upscale_Screen_003.png)

Il filtro <b>Ingrandisci</b> è stato aggiunto per campionare i risultati. Alucinare i dettagli per raggiungere una risoluzione più elevata mantenendo la qualità del materiale. È possibile scegliere nelle proprietà di eseguire il upsampling di 2 o di 4.
