---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Scoprite come importare le texture in Substance 3D Sampler per utilizzare i file di immagine esistenti nei flussi di lavoro di creazione del materiale.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Importazione texture
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 4%

---


# Importazione texture

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

Il modello **Importazione texture** carica più immagini e le collega automaticamente ai canali di output corretti in base ai nomi dei file.

La corrispondenza dei canali si basa sulle convenzioni di denominazione specifiche descritte di seguito. In caso di duplicati o texture senza corrispondenza, le immagini vengono contrassegnate come tali nell’interfaccia.

## OpenPBR

Sampler abbinerà i file con i seguenti identificatori di OpenPBR al canale equivalente nel materiale.

>[!NOTE]
>
> Gli identificatori di canale di height sono gli stessi utilizzati per ASM.


| Identificatore OpenPBR | Utilizzo SBSAR |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | metallizzazione/metallica |
| base_diffuso_roughness | baseDiffuseRoughness |
| specular_weight | specularWeight |
| specular_color | specularColor |
| specular_rugosità | specularRoughness/rugosità |
| specular_roughness_anisotropia | specularRoughnessAnisotropy/anisotropyLevel |
| specular_ior | specularIOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | transmissionColor/absorptionColor |
| transmission_profondità | transmissioneProfondità/assorbimentoDistanza |
| transmission_dispersione | transmissionScatter |
| transmission_dispersione_anisotropia | transmissionScatterAnisotropy |
| transmission_dispersion_scale | transmissionDispersionScale |
| transmission_dispersion_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsurfaceWeight/translucency |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_dispersione_anisotropia | subsurfaceScatterAnisotropy |
| coat_weight | coatWeight/coatOpacity |
| coat_color | coatColor |
| coat_roughness | coatRoughness |
| coat_roughness_anisotropia | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| coat_darkening | coatDarkening |
| fuzz_weight | fuzzWeight/sheenOpacity |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_roughness | fuzzRoughness/sheenRoughness |
| peso_emissione | emissionWeight |
| emission_luminance | emissionLuminance |
| emission_color | emissionColor/emisive |
| thin_film_weight | thinFilmWeight |
| thin_film_thickness | thinFilmThickness |
| thin_film_ior | thinFilmIOR |
| opacità | opacità |
| thin_walled | thinWalled |
| normale | normale |
| tangente | tangente |
| coat_normal | coatNormal |
| coat_tangent | coatTangent |

## Materiale standard Adobe

Di seguito è riportato un elenco delle convenzioni di denominazione dei file supportate per ciascun canale:

| **Canale** | **Materiale Adobe Standard** |
| --- | --- |
| **Occlusione ambiente** | <ul><li>ambientocclusione</li><li>ao</li><li>occlusione</li><li>occlusione_ambientale</li></ul> |
| **Colore di base** | <ul><li>basecolor</li><li>colore</li><li>albedo</li><li>base_color</li><li>base</li><li>col</li><li>colore</li><li>base_color</li><li>basecolor</li></ul> |
| **Diffusione** | <ul><li>diffusione</li><li>diff</li></ul> |
| **Emissivo** | <ul><li>con emissioni</li></ul> |
| **Lucentezza** | <ul><li>lucentezza</li><li>lucidalabbra</li></ul> |
| **Height** | <ul><li>height</li><li>heightmap</li><li>spostamento</li><li>disp</li></ul> |
| **Metallico** | <ul><li>metallico</li><li>mtl</li><li>metallicità</li></ul> |
| **Normale** | <ul><li>normale</li><li>nrm</li></ul> |
| **Opacità** | <ul><li>opacità</li><li>alfa</li></ul> |
| **Rugosità** | <ul><li>ruvidità</li><li>ruvido</li></ul> |
| **Specular** | <ul><li>specular</li><li>spec</li></ul> |
| **Specular level** | <ul><li>specularlevel</li><li>specular_level</li></ul> |

