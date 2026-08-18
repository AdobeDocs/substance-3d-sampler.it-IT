---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Usate lo strumento Altera in Substance 3D Sampler per applicare l’alterazione direzionale e gli effetti distorsione ai livelli di texture e materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Warp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ordito
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---


# Ordito

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-warp-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Il **filtro Altera** consente di alterare il materiale in base a diversi rumori generati.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Selezione disturbo**:\
  Selezionate il disturbo su cui basare l’alterazione. Disturbi diversi possono creare effetti diversi.
* **Scala disturbo**: 0-10\
  Regola la scala del disturbo sorgente. Il rumore sarà sempre affiancato.
* **Tipo**:\
  Selezionate il metodo utilizzato per alterare il materiale. Se sono selezionati **Alterazione direzionale** o **Alterazione multidirezionale**, verrà visualizzato un parametro aggiuntivo:
  * **Angolo di alterazione**: 0-1\
    Regolate la direzione lungo cui avviene l’alterazione
* **Intensità**: 0-1\
  Regolate l’intensità dell’alterazione.
* **Disturbo personalizzato**: attiva/disattiva\
  Abilita per utilizzare un rumore personalizzato anziché la selezione in **Selezione rumore**. I parametri disponibili cambieranno a seconda che **Disturbo personalizzato** sia abilitato o disabilitato. Se questa opzione è attivata, vengono visualizzati i seguenti parametri:
  * **Sfocatura disturbo personalizzata**: 0-1\
    Sfoca il disturbo personalizzato
  * **Disturbo personalizzato**: immagine/pennello\
    Importate una mappa del disturbo personalizzata da utilizzare come sorgente di alterazione.
* **Altera per canale**: attiva/disattiva\
  Quando questa opzione è attivata, appariranno sezioni aggiuntive per controllare l’alterazione di ciascun canale in modo indipendente. Per ciascun canale sono disponibili i seguenti parametri:
  * ***Nome canale***: attiva/disattiva\
    Attivare/disattivare se il canale è interessato dal **filtro Altera**.
  * **Metodo fusione**:\
    Seleziona la modalità di fusione dei risultati dell’alterazione per questo canale con il livello sottostante
  * **Opacità**: 0-1\
    Modifica l&#39;opacità dei risultati del filtro per questo canale.
