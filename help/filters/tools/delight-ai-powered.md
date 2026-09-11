---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/delight-ai-powered.html"
breadcrumb-title: ''
description: Utilizzate il filtro Delight basato sull'intelligenza artificiale in Substance 3D Sampler per rimuovere le informazioni di illuminazione dalle immagini e creare materiali di base neutri.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Delight (AI Powered)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Delight (basata su IA)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# Delight (basata su IA)

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-lightgeneric-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il Delighter consente di rimuovere le informazioni di illuminazione dal canale del colore di base. Questo è importante quando si convertono le immagini in materiali, perché in genere i materiali non devono includere informazioni sull’illuminazione. Un materiale è una raccolta di informazioni che spiega come la luce dovrebbe reagire con una superficie, quindi se ci sono già informazioni di luce eseguite i baking in un canale che non dovrebbe avere informazioni di luce, può rompere la capacità del materiale di rappresentare la superficie realisticamente.

*Esempio **un&#39;immagine prima e dopo l&#39;elaborazione da parte del filtro**&#x200B;Delight (IA Powered)**. Le ombre e le luci sono state rimosse, rimane solo il colore di base.*

![](../../assets/120-0-comparison.png)

Le immagini seguenti mostrano un materiale prima e dopo l&#39;elaborazione da parte di un filtro **Delight (basato su IA)**.

![](../../assets/3d-2d-filters-cropped-0043-delighter-in.jpg)

Nell&#39;immagine precedente, il materiale include ancora una notevole quantità di informazioni di illuminazione nel canale del colore di base. Le ombre scure tra i mattoni non dovrebbero essere presenti nel canale del colore di base.

![](../../assets/3d-2d-filters-cropped-0042-delight-out.jpg)

Dopo il delizioso passaggio, le ombre sono state rimosse per creare un canale di colore di base più accurato dal punto di vista fisico. Anche se i risultati in questo esempio potrebbero non sembrare evidenti, la delizia delle immagini è un passaggio importante della conversione delle immagini in materiali.

Nelle immagini sorgente, la luce proviene da sorgenti statiche, ma i materiali devono essere in grado di gestire la luce proveniente da qualsiasi angolazione. Ad esempio: se un’immagine sorgente con luce che splende dall’alto verso il basso viene convertita in un materiale senza passare per un passaggio delizioso, potrebbe essere visualizzata in uno spazio 3D in cui la luce splende dal basso verso l’alto. Il materiale guarderà rapidamente fuori posizione perché contemporaneamente sembra proiettare ombre da più luci quando c&#39;è solo una singola sorgente luminosa.

</td>
</tr>
</table>

## Parametri

Il delighter non ha parametri - funziona automaticamente.

## Guida all’uso

Come utilizzarlo?

Aggiungere il **filtro Delighter** nella parte superiore della Pila livelli.

### Quando utilizzarlo?

Quando si utilizza **Immagine in materiale (B2M)**, una volta estratti tutti i canali dalle immagini e reso affiancabile il materiale, utilizzare il delizioso per rimuovere le informazioni di illuminazione dal colore di base. **Da immagine a materiale (basata sull&#39;intelligenza artificiale)** include un passaggio delizioso, quindi non dovrebbe essere necessario utilizzare il filtro **Delighter (basato sull&#39;intelligenza artificiale)**.
