---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/pbr-validate.html"
breadcrumb-title: ''
description: Utilizza lo strumento PBR Validata di Substance 3D Sampler per convalidare e garantire che i materiali soddisfino gli standard di rendering basati fisicamente.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > PBR Validate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: PBR Validata
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '653'
ht-degree: 0%

---


# PBR Validata

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pbrvalidate-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Utilizza il **filtro PBR Validata** per assicurarti che i valori PBR del materiale siano corretti. A differenza della maggior parte dei filtri, il **filtro PBR Validata** non è progettato per essere una parte permanente del gruppo di livelli, ma per convalidare il materiale e quindi rimuoverlo in modo che non modifichi il materiale.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Modalità di convalida**:\
  Selezionare se convalidare i valori di albedo (colore di base o diffusione), i valori metallici o entrambi i valori di albedo e metallici. Altri parametri verranno aggiornati in base a questa selezione
  * **Modalità di convalida: Albedo**
    * **Albedo soglia intervallo scuro**:\
      Imposta la soglia per i valori scuri che il filtro deve rilevare come non valida.
    * **Sovrapposizione mappa**: attiva/disattiva\
      Passare dalla modalità di sovrapposizione all’altra: se attivata, la mappa colore di base viene sovrapposta ai pixel non validi.
    * **Nascondi convalida in colore di base**: attiva/disattiva\
      Nascondi le informazioni di convalida dal canale del colore di base.
  * **Modalità di convalida: Metal**
    * **Intervallo Di Riflessione Metallica**:\
      Impostate l’intervallo di valori di riflessione che il filtro deve rilevare come non valido.
    * **Sovrapposizione mappa**: attiva/disattiva\
      Passare dalla modalità di sovrapposizione all’altra: se attivata, la mappa colore di base viene sovrapposta ai pixel non validi.
    * **Nascondi convalida in colore di base**: attiva/disattiva\
      Nascondi le informazioni di convalida dal canale del colore di base.
  * **Modalità di convalida: combinata**
    * **Albedo soglia intervallo scuro**:\
      Imposta la soglia per i valori scuri che il filtro deve rilevare come non valida.
    * **Intervallo Di Riflessione Metallica**:\
      Impostate l’intervallo di valori di riflessione che il filtro deve rilevare come non valido.
    * **Nascondi convalida in colore di base**: attiva/disattiva\
      Nascondi le informazioni di convalida dal canale del colore di base.

## Guida all’uso

Il **PBR Validata** **filtro** consente di evitare problemi con l&#39;albedo e i valori metallici in un materiale. Per capire come funziona il **filtro PBR Validata**, è utile innanzitutto parlare un po&#39; di PBR.

## Che cos&#39;è PBR?

PBR è l’acronimo di Physically Based Rendering (Rendering basato su fisica) ed è un metodo di rendering di oggetti e materiali mediante la rappresentazione delle proprietà fisiche di una superficie con vari canali. PBR è stato creato per rappresentare più accuratamente il mondo reale e fisico rispetto ai precedenti metodi di rendering e ombreggiatura.

Nel mondo reale, ci sono alcuni colori e combinazioni di proprietà che sono o impossibile o incredibilmente raro. Ad esempio, quasi nulla nel mondo reale ha un&#39;albedo di bianco puro o nero puro o un colore di base.

Quindi, poiché PBR sta cercando di rappresentare valori reali, e poiché alcuni valori non appaiono o appaiono raramente nel mondo reale, è possibile avere valori PBR &#39;errati&#39;. Questo è ciò che il **filtro PBR Validata** è progettato per trovare.

## Come usare PBR Validata

Per utilizzare **PBR Validata**, aggiungilo nella parte superiore dello stack di livelli. Dovresti notare un cambiamento drastico nell&#39;aspetto del tuo materiale, perché **filtro PBR Validata** mostra i risultati della convalida nel canale di albedo.

Il filtro utilizza una scala da rossa a verde per mostrare dove si trovano gli errori. Se l’intero materiale è verde, non c’è nulla di sbagliato nei colori o nei valori metallici del materiale. Tuttavia, se vedi aree gialle, arancioni o rosse, ci sono problemi con il tuo materiale.

Se utilizzate la modalità di convalida del colore, le aree non verdi indicano in genere che nel colore di base sono presenti valori vicini al nero o al bianco. Usate filtri di regolazione come **Tonalità/Saturazione** o **Luminosità/Contrasto** per regolare i valori del canale di colore finché il **filtro PBR Validata** non mostra più errori.

Se utilizzate la modalità di convalida del metallo, le aree non verdi in genere indicano che la combinazione di colore, rugosità e mappe metalliche in tali aree non è realistica. Di solito questo accade con i valori di colore scuro, la rugosità 0 e 1 i valori metallici. Per correggere questi errori, è possibile modificare i valori di rugosità, metallizzazione o colore finché il **filtro PBR Validata** non mostrerà più errori.
