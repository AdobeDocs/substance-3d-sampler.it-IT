---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Utilizzate il generatore di Rilievi di superfici in Substance 3D Sampler per creare pattern di superfici in rilievo e rilievi nei materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Surface Relief
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Rilievo di superficie
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Rilievo di superficie

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-surfacerelief-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizzate il filtro Rilievo superficie (Surface) per aggiungere disturbo al materiale. In questo modo è possibile suddividere forme grandi o aggiungere interesse visivo.

</td>
</tr>
</table>

## Parametri

<b>Parametri di base</b>

* <b>Numero casuale</b>:\
  Valore di inizializzazione casuale su cui sono basati tutti gli altri parametri casuali in questo filtro.
* <b>Intensità</b>: 0-1\
  Modificare l’ampiezza del disturbo
* <b>Intensità sfocatura</b>: 0-1\
  Intensità della sfocatura applicata al disturbo
* <b>Imperfezione Superficie </b>: Immagine/Pennello/Generatore Texture\
  Usate un’immagine o un generatore di texture come imperfezione della superficie.

<b>Parametri disturbo</b>

* <b>Blocco</b>: 0-1\
  Bloccare il disturbo a un determinato intervallo
* <b>Contrasto</b>: 0-1\
  Modificare il contrasto del disturbo
* <b>Inverti</b>: attiva/disattiva\
  Invertire la mappa di height del disturbo

<b>Trasformazione</b>

* <b>Affiancatura</b>: 1-16\
  A differenza di <b>parametri di base > scala</b>, <b>Divisione in porzioni</b> gestisce il numero di istanze del disturbo.
* <b>Speculare</b>:\
  Specchiatura del disturbo su uno o entrambi gli assi
* <b>Scostamento</b>:\
  Riposizionare il disturbo sugli assi X e Y
* <b>Rotazione</b>:\
  Ruotate il disturbo. L’angolo di rotazione si aggancia per garantire che la suddivisione in porzioni sia ancora possibile.

<b>Maschera</b>

* <b>Usa maschera personalizzata</b>: attiva/disattiva\
  Abilita per visualizzare i controlli Maschera personalizzata:
  * <b>Maschera</b>: immagine/pennello/Generatore texture\
    Importa un&#39;immagine da utilizzare come maschera o utilizza il pennello per dipingere direttamente nella <b>vista 2D</b>
  * <b>Maschera personalizzata - Sfocatura</b>: 0-1\
    Sfocare la maschera
  * <b>Maschera personalizzata - Inverti</b>: attiva/disattiva

<b>Parametri avanzati</b>

* <b>Intensità Height</b>: 0-1\
  Controlla la fusione della mappa dell&#39;altezza del disturbo con la mappa dell&#39;altezza dei materiali sottostante
* <b>Height - Sostituisci base</b>: attiva/disattiva\
  Attivare/disattivare la sostituzione del height di base
* <b>Intensità normale</b>: 0-1\
  Regola l’intensità della mappa normale del disturbo
* <b>Normale - Sostituisci base</b>: attiva/disattiva\
  Attiva/disattiva la sostituzione della mappa normale di base o meno
* <b>Direzione -Normale</b>:\
  Modificare gli assi da utilizzare per la generazione normale
* <b>Normale - Direzione rotazione</b>
* <b>Occlusione ambiente - Intensità</b>
* <b>Occlusione ambiente - Raggio</b>
