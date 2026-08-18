---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/filters/generators/splatter.html"
breadcrumb-title: ''
description: Usate il generatore di splatter in Substance 3D Sampler per creare effetti di splatter di vernice e pattern casuali per le texture di materiale.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Splatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Schizzo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '736'
ht-degree: 0%

---


# Schizzo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-splatter-18-n-d.png)

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Suddividi le istanze di altri materiali nel tuo materiale.

>[!NOTE]
>
> Per i materiali atlas, utilizzare invece il filtro Atlas scatter.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:\
  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.
* **Input materiale**:\
  Selezionate il numero di materiali da utilizzare come input. Nota: un livello di splatter con 3 slot di input ma solo uno slot con un input apparirà in modo diverso rispetto a un livello di splatter con 1 slot di input e quello slot con lo stesso input. Per questo motivo si consiglia di utilizzare solo il numero di input necessario.
* **Dimensione griglia**: 1-64\
  La dimensione della griglia determina il numero di istanze create dal filtro Spruzzo.
* **Profondità Height AO**: 0-1\
  Regolate l’intensità dell’AO per le istanze create dal filtro.

**Forma**

* **Scala**: 0-5\
  Regolare le dimensioni di base di tutte le istanze
* **Scala casuale**: 0-1\
  Regola la casualità del valore di scala per ogni istanza
* **Scala senza sovrapposizione**: 0-1\
  Modificare le dimensioni delle istanze per evitare sovrapposizioni
* **Posizione casuale**: 0-2\
  Controllare la casualità della dispersione delle istanze
* **Rotazione casuale**: 0-1\
  Controllare la casualità della rotazione delle istanze
* **Rotazione dalla Pendenza di sfondo**: 0-1\
  Modificate l&#39;impatto delle normali del materiale sottostante sulla rotazione delle varianti.

**Colore di base**

* **Albedo corrispondente**: 0-1\
  Associa il colore delle istanze al colore del materiale sottostante
* **Regolazione HSL**: 0-1\
  Regolare Tonalità, Saturazione e Luminosità delle istanze
* **HSL casuale**: 0-1\
  Controllate la casualità di Tonalità, Saturazione e Luminosità di ogni istanza

**Normale**

* **Normale da** **Sfondo**: 0-1\
  Regolate in che misura la normale del materiale sotto ogni istanza influisce sulla normale dell&#39;istanza.
* **Angolo normale casuale**: 0-1\
  Inclinate le normali di ogni variante con un angolo casuale.

**Rugosità**

* **Regolazione rugosità**: da -1 a 1\
  Aggiungete o sottraete dal valore di rugosità in modo uniforme tra le varianti
* **Rugosità casuale**: da -1 a 1\
  Aggiungete o sottraete casualmente dal valore di rugosità di ogni istanza
* **Rugosità Dallo Sfondo**: 0-1\
  Regola di quanto il valore di rugosità del materiale sottostante influisce sul valore di rugosità di ciascuna istanza

**Height**

* **Scostamento Height**: da -1 a 1\
  Spostate il height di varianti. Ciò può influire sul modo in cui le istanze si fondono con il materiale sottostante.
* **Scostamento Height casuale**: 0-1\
  Aggiungere un valore casuale allo scostamento del height di ogni istanza
* **Scala Height**: 0-2\
  Regolate il height di tutte le istanze.
* **Scala Height casuale**: 0-1\
  Aggiungi un valore casuale al height di ogni istanza
* **Inclina da Bg Pendenza**: 0-1\
  Aggiungete una pendenza a ogni istanza in modo che corrisponda alla pendenza del materiale sottostante
* **Smoothness Pendenza in background**: 0-2\
  Regola la pendenza dello sfondo ai fini del parametro **Inclina da Pendenza sfondo**
* **Conformità allo sfondo**: 0-1\
  Controlla l’impatto della mappa del height di sfondo sulla mappa del height di istanze. In questo modo è possibile ridurre le istanze che contornano i dettagli dello sfondo
* **Sfondo uniforme**: 0-1\
  Regola quanti dettagli sono visibili a causa della **Conformità allo sfondo**

**Metallico**

* **Regolazione metallica**: da -1 a 1\
  Controllare i valori metallici delle varianti
* **Metallico casuale**: da -1 a 1\
  Aggiungete o sottraete valori casuali dal metallizzato di ciascuna variante
* **Metallico da sfondo**: 0-1\
  Regola l’impatto dei valori metallici di sfondo su ogni istanza

**Maschera**

* **Usa maschera personalizzata**: attiva/disattiva\
  Abilita questa opzione per utilizzare una maschera personalizzata e accedere ai controlli maschera personalizzati:
  * **Maschera personalizzata**: immagine/pennello\
    Importa un&#39;immagine da utilizzare come maschera o pittura personalizzata direttamente nella **vista 2D**
  * **Sfocatura maschera personalizzata**: 0-1\
    Sfocare i bordi della maschera personalizzata
  * **Inversione maschera personalizzata**: attiva/disattiva
  * **Opacità maschera personalizzata**: 0-1\
    Regolare l’intensità della maschera personalizzata

Guida all’uso

Il filtro Spruzzo è un modo utile per dare dispersione alle risorse nel materiale, ad esempio foglie, pietre o rifiuti.

Per usare il filtro Spruzzo:

1. Aggiungere il filtro Spruzzo alla pila di livelli
1. Sotto il livello di splatter, appariranno gli slot di input
1. È possibile modificare il numero di slot di input disponibili con **Parametri di base > Input materiale**
1. Trascina i materiali negli slot di input dello splatter

Puoi regolare i parametri della dispersione nel **pannello Proprietà** selezionando il livello di splatter.

Potete regolare i parametri dei materiali di input nel **pannello Proprietà** selezionando il materiale nello slot di input.
