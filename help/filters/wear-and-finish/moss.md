---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/moss.html"
breadcrumb-title: ''
description: Usa il filtro Moss in Substance 3D Sampler per aggiungere ai tuoi materiali una crescita del muschio realistica e effetti di superficie organici.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Moss
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Muschio
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 0%

---


# Muschio

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/moss-filter-icon.png)

**Entrata:** usura e fine

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Usa il **filtro Moss** per aggiungere muschi e licheni al materiale. **Moss** utilizza la mappa di occlusione del materiale per crescere in modo naturale nelle crepe e nelle fessure.

Le immagini seguenti mostrano il materiale del dirt prima e dopo l&#39;applicazione del **filtro Moss**.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0021-moss-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0020-moss-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Valore di inizializzazione casuale su cui sono basati tutti gli altri parametri casuali in questo filtro.
* **Moss Global Spread**: 0-1\
  Regola la copertura del muschio sul materiale.
* **Colore Moss**: selezione colore\
  Selezionate il colore primario del muschio.
* **Colore Moss secondario**: selezione colore\
  Selezionate il colore secondario del muschio.
* **Partizione Moss**:\
  Selezionare il metodo utilizzato per applicare il muschio. Per impostazione predefinita, **Occlusioni** utilizza la mappa AO del materiale per applicare il muschio, ma le altre opzioni avranno effetti diversi. Se è selezionato **Personalizzato** **Maschera**, verrà visualizzata la **Maschera** **sezione**.

**Maschera**

Questa sezione viene visualizzata solo se è stata scelta **Maschera personalizzata** in **Parametri di base > Partizione Moss**.

* **Maschera personalizzata - Sfocatura**: 0-1\
  Sfocate la maschera.
* **Maschera personalizzata - Inverti**: attiva/disattiva\
  Invertite la maschera.
* **Maschera personalizzata**: immagine/pennello\
  Selezionate un’immagine da usare come maschera oppure usate il pennello per pittura una maschera personalizzata direttamente nella Vista 2D.

**Moss**

I parametri disponibili in questa sezione dipendono dall&#39;opzione selezionata in **Parametri di base > Partizione Moss**.

* **Occlusione**
  * **Propagazione Occlusione Moss**: 0-1\
    Controlla la diffusione del muschio in base all’occlusione.
  * **Maschera Occlusione Moss**: 0-1\
    Regola la quantità di muschio utilizzando la mappa di occlusione come maschera.
* **Globale**
  * **Propagazione complessiva Moss**: 0-1\
    Regolate la quantità di muschio da visualizzare.
* **Primi**
  * **Soglia Moss Superiore**: 0-1\
    Consente di controllare la soglia che determina se viene visualizzato o meno il muschio.
  * **Angolo superiore del muschio** Regola il modo in cui il muschio si applica al materiale in base alla mappa normale.
* **Tutti**
  * **Tutti** include tutti i parametri indicati in precedenza per **Occlusione**, **Complessiva** e **Principale**.

I seguenti parametri sono disponibili indipendentemente dall&#39;opzione selezionata in **Parametri di base > Partizione Moss**.

* **Dimensione fiori Moss**: 0-1\
  Modificate la granularità del muschio.
* **Intensità grana Moss**: 0-1\
  Regolate la visibilità della granulosità del Moss.
* **Dimensione Moss Clumps**: 0-1\
  Controlla la tendenza del muschio ad aggregarsi insieme.
* **Nitidezza grumi di muschio**: 0-1\
  Regolate la morbidezza dei bordi dei grumi.
* **Intensità grumi di mosaico**: 0-1\
  Controllate l’intensità dei grumi di muschio.
* **Sfumatura Moss**: 0-1\
  Regola la sfumatura dei bordi della maschera di muschio.
* **Intensità rilievo Moss**: 0-1\
  Cambia i rilievi del muschio.
* **Soglia Moss Superiore**: 0-1

**Parametri tecnici**

* **Intensità normale**: 0-1\
  Regolate la forza delle normali del muschio.
* **Intensità Occlusione ambientale** Controlla l&#39;intensità dell&#39;occlusione ambientale del muschio.
