---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/features-and-workflows/adobe-standard-material.html"
breadcrumb-title: ''
description: Scopri come utilizzare i Materiali standard Adobe in Substance 3D Sampler per creare materiali compatibili con lo standard di materiali Adobe.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Adobe Standard Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Materiale standard Adobe
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 1%

---


# Materiale standard Adobe

>[!NOTE]
>
> Per impostazione predefinita, ora Substance 3D Sampler utilizza il modello di materiale [OpenPBR](openpbr.md) anziché il materiale Adobe Standard.


## Proprietà dei materiali standard

## Proprietà della superficie di base

**Colore di base**

Colore della superficie.

**Rugosità**

Quanto è liscia o opaca la superficie.

![](../assets/surface-roughness.jpg)

**Metallico**

Il grado di lucentezza metallica della superficie.

![](../assets/surface-metallic.jpg)

**Opacità**

La visibilità della superficie.

![](../assets/surface-opacity.jpg)

**occlusione ambiente**

Ombre provenienti da cavità e pieghe che impediscono alla luce di colpire la superficie.

**Specular level**

Intensità dei riflessi di luce sulla superficie.

![](../assets/surface-specularlevel.jpg)

**Specular edge color**

Il colore dei riflessi di luce. Influisce sugli angoli di sfocatura dei materiali metallici.

![](../assets/surface-specularedgecolor.jpg)

**Normale**

Simula i dettagli della superficie come protuberanze e crepe.

**Scala normale**

L’intensità dell’effetto normale.

**Combina normale e height**

Applica la texture normale alla texture del height.

**Height**

Crea i dettagli della superficie utilizzando lo spostamento di rilievo o di geometria.

**Scala Height**

Scala del height in unità di scena. Applicabile sia allo spostamento che alla protuberanza.

**Livello Height**

Il valore della texture del height che rappresenta lo spostamento zero.

**Livello di Anisotropia**

Quantità di estensione delle riflessioni in una direzione lungo la superficie.

![](../assets/surface-anisotropy.jpg)

**Angolo di Anisotropia**

Rotazione antioraria dell’effetto anisotropo.

**Intensità delle emissioni**

Intensità della luce emessa dalla superficie.

![](../assets/surface-emission.jpg)

**Colore di emissione**

Colore della luce emessa.

![](../assets/surface-emissioncolor.jpg)

**Opacità brillantezza**

Simula l’effetto di fibre microscopiche o di fuzz sulla superficie.

![](../assets/surface-sheen.jpg)

**Colore di lucentezza**

Colore dell&#39;effetto brillantezza.

![](../assets/surface-sheencolor.jpg)

**Rugosità brillantezza**

Morbidezza dell&#39;effetto brillantezza.

![](../assets/surface-sheenroughness.jpg)

## Proprietà interne

**Traslucidità**

Quantità di luce in grado di trasmettere attraverso la superficie.

![](../assets/interior-translucency.jpg)

**Colore di assorbimento**

La luce del colore convergerà verso quando verrà assorbita.

**Distanza Assorbimento**

Distanza approssimativa nelle unità di scena che la luce viaggerà prima di raggiungere il colore di assorbimento. Se impostato su zero, thickness non avrà effetto sul colore di assorbimento.

![](../assets/interior-absorptiondistance.jpg)

**Indice di rifrazione**

La quantità di luce che si curva mentre attraversa l’oggetto.

![](../assets/interior-indexofrefraction.jpg)

**Dispersione**

Quantità di rifrazione dello spettro cromatico.

**Dispersione sottosuperficie**

Dispersione la luce al di sotto della superficie, invece di passare direttamente attraverso di essa.

**Colore di dispersione**

Il colore sotto la superficie che diventerà la luce diffusa.

![](../assets/interior-scattercolor.jpg)

**Distanza di dispersione**

La luce a distanza approssimativa deve viaggiare prima di raggiungere la dispersione completa.

![](../assets/interior-scatterdistance.jpg)

**Scala distanza di dispersione**

Moltiplicatore della distanza della dispersione. Può essere diverso per ogni canale di colore.

![](../assets/interior-scatterdistancescale.jpg)

**Scostamento rosso**

Imposta la luce rossa in modo che si sposti più a destra rispetto ad altri colori chiari. Utile per la pelle.

![](../assets/interior-scatterredshift.jpg)

**Dispersione di Rayleigh**

Imposta la luce arancione per spostarsi più sotto la superficie e la luce blu per spostarsi meno.

![](../assets/interior-scatterraleigh.jpg)

**thickness di volumi**

Thickness della superficie relativa al rettangolo di selezione dell&#39;oggetto. Utilizzato per effetti interni quando il thickness reale non è noto.

**Scala thickness volume**

Moltiplicatore del thickness di volumi.

## Proprietà rivestimento

**Opacità pelo**

Simula un livello sopra il materiale. Utilizzato per creare cappotti, lacche e vernici trasparenti.

![](../assets/coat-coatopacity.jpg)

**Colore pelo**

Il colore del cappotto.

![](../assets/coat-coatcolor.jpg)

**Rugosità pelo**

Quanto è liscia o opaca la superficie del pelo.

![](../assets/coat-coatroughness.jpg)

**Indice di rifrazione del rivestimento**

La quantità di luce si piega mentre passa attraverso il pelo.

![](../assets/cooat-coatior.jpg)

**specular level**

L&#39;intensità dei riflessi di luce sul pelo ad angoli di visuale.

![](../assets/coat-coatspecular.jpg)

**Pelo normale**

Simula i dettagli della superficie come protuberanze e crepe sulla superficie del pelo.

![](../assets/coat-coatnormal.jpg)

**Scala normale rivestimento**

La forza dell&#39;effetto normale del pelo.
