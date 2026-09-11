---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/multiangle-to-material.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Multiangolo su materiale di Substance 3D Sampler per creare materiali da più angolazioni di una superficie.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Multiangle To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Multiangolo su materiale
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Multiangolo su materiale

![](../../assets/sat-multi-angle.png)

Il modello **Multiangolo su materiale** consente di creare un materiale da 2 a 8 immagini di input scattate in condizioni di luce specifiche. Tali condizioni di luce possono essere ottenute con uno scanner di materiale.

>[!NOTE]
>
> In questo articolo[&#128279;](https://www.adobe.com/products/substance3d/magazine/your-smartphone-is-a-material-scanner-vol-ii.html) sono disponibili ulteriori informazioni su come creare il proprio scanner di materiali .

## Esempio

Di seguito è riportato un esempio di materiale creato da 8 immagini di input:

* Le prime 8 immagini sono le immagini acquisite in 8 angoli di luce.
* Le immagini in basso rappresentano gli output del modello (colore di base, normale, height, metallico e rugosità).

![](../../assets/scan-801x697.jpg){width="400px"}

## Configurazione di Substance 3D Sampler

Per garantire che i canali PBR vengano estratti correttamente, è necessario impostare e configurare tre elementi:

* Ordine delle immagini acquisite
* Primo angolo di luce di ingresso
* l&#39;angolo di illuminazione di ingresso successivo

![](../../assets/multiangles-1024x1024.jpg){width="450px"}

### Ordine di scansione delle immagini

Quando importate le immagini, verificate nel livello Importazione immagine che le 8 immagini siano consecutive.

Ad esempio, la prima immagine a 0° deve essere **scansione1**, quindi l&#39;immagine a 45° deve essere **scansione2**... quindi l&#39;immagine a 315° deve essere **scansione8**

![](../../assets/multiangle-image-import.png){width="450px"}

### Angolo luce primo e successivo

Nel livello Multiangolo su materiale:

* Impostate Primo Angolo Luce Di Ingresso. Se la **scansione1** è a 180°, il primo angolo di luce di input =0,5 o se la **scansione1** è a 0°, il primo angolo di luce di input = 0
* Imposta angolo luce di input successivo: definisce la direzione della rotazione dell’immagine. Se scan1 è 0°, scan2 45°... il valore è **in senso antiorario**

![](../../assets/multiangle-multiangle-to-material.png){width="450px"}
