---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/weave.html"
breadcrumb-title: ''
description: Usa il generatore Tessitura in Substance 3D Sampler per creare pattern di tessuto intrecciato e texture tessili per la creazione di materiali.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Weave
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Intreccio
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '756'
ht-degree: 0%

---


# Intreccio

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

**In:** Generatori

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Usate il filtro Intreccia per convertire le immagini in pattern intrecciati.

</td>
</tr>
</table>

## Parametri

**Predefiniti**

Usare i predefiniti per modificare rapidamente i parametri e visualizzare diversi stili di trama

**Parametri di base**

* **Numero casuale**:\
  Valore di inizializzazione casuale su cui sono basati tutti gli altri parametri casuali in questo filtro.
* **Immagine**: immagine/pennello\
  Selezionate un&#39;immagine o un disegno direttamente nella **vista 2D**. Il **filtro Intreccio** funziona meglio quando si seleziona un&#39;immagine.
* **Conteggio colori**: 1-10\
  Il **filtro Intreccio** suddivide automaticamente l&#39;input dell&#39;immagine in diversi colori in base a questo parametro. I parametri di ciascun colore possono essere controllati in modo indipendente.
* **Dimensioni area (cm)**: 2-50\
  Modificate la dimensioni fisiche rappresentata dallo spazio 2D. Questo modificherà il numero di punti utilizzati per ricreare l’immagine di input.
* **Densità (punti per cm)**: 1-105\
  Utilizza il controllo **Dimensioni area (cm)** per regolare il numero di punti nello spazio 2D.
* **Rugosità globale**: 0-1,0\
  Regolare la ruvidità del materiale
* **Modalità colore weft**:\
  Consente di specificare se colorare lo sfondo in base all’input dell’immagine o in base a selezioni di colori personalizzate. Se è selezionato **Ignora per colore**, in ogni colore verrà visualizzato un parametro **Colore** aggiuntivo.

**Colore X**

Il numero di colori disponibili per la modifica dipende da **Parametri di base > Conteggio colori**.

* **Colore**: selezione colore\
  Disponibile solo se **Parametri di base > Metodo colore weft** è impostato su **Ignora per colore**. Scegliete il colore del materiale per questa sezione.
* **Dimensione bordo**: 0-1\
  Aggiungete un bordo ai bordi del colore selezionato. Il bordo aumenta la lunghezza della trama tra i fili di alterazione vicino al bordo del colore, evitando che i punti di alterazione appaiano vicini al bordo dei set di colori.
* **Scostamento rugosità**: 0-1\
  Modifica la ruvidità per questo set di colori
* **Metallico**: 0-1\
  Modifica il valore metallico per questo set di colori
* **Posizione Height**: 0-1\
  Regola il height di questo set di colori. Utilizzate questa opzione per aggiungere profondità alla versione intrecciata dell’immagine.

**Avanzate**

* **Altera colore**: selezione colore\
  Modificate il colore dei filetti di alterazione (per impostazione predefinita, i filetti di alterazione vengono eseguiti perpendicolarmente ai filetti più visibili).
* **Altera - Scambio a sinistra**:\
  Scambiate i filetti che sono alterazione e trama. Questo ha l&#39;effetto di ruotare i punti di 90 gradi,
* **Alberi di alterazione**: 1-16\
  Regolate la frequenza relativa dei filetti di alterazione in Filetti a sbalzo. Può essere utilizzato per creare diversi pattern jacquard.
* **Dimensione alterazione**: 0-1\
  Intensificare o ridurre i fili di alterazione
* **Intensità sfocatura differenza Height**: 0-1\
  Controlla la pendenza o la sfocatura causata dalle differenze di **Posizione Height**. Questa operazione non produce alcun effetto a meno che non si modifichi il cursore **Posizione Height** per almeno un set di colori.

## Guida all’uso

All&#39;inizio il filtro Intreccia può essere un po&#39; confuso, ma con pochi parametri importanti per iniziare, presto creerai intrecci complessi da aggiungere ai tuoi materiali.

>[!NOTE]
>
> Se hai già utilizzato il filtro [Ricamo](embroidery.md), il filtro Intreccia funziona in modo simile. Producono effetti diversi, ma si possono usare le immagini allo stesso modo.
> 
> Le immagini per la tessitura devono avere proporzioni quadrate, alta risoluzione (minimo 2K) e presentare al massimo 10 colori diversi. Il canale alfa o di trasparenza può essere utilizzato per ritagliare forme. Idealmente sono basati su vettori, ma vengono esportati come bitmap PNG.

Per utilizzare il filtro Intreccia:

1. Trascina e rilascia un’immagine in
1. Aggiungete il filtro Intreccio alla pila di livelli.
1. Regolate **Parametri di base > Conteggio colori** fino a ottenere il bilanciamento del colore corretto per l’immagine. Con un limite di 10 colori, il filtro Intreccia funziona meglio con i colori piatti e le immagini illustrate.
1. Regolate altri parametri per perfezionare l’aspetto del cerotto.

Queste sono le nozioni di base su come utilizzare il filtro Intreccia.

È possibile utilizzare immagini trasparenti nel filtro Intreccio, ma per impostazione predefinita queste influiranno anche sulla mappa di opacità del materiale: le parti trasparenti dell&#39;immagine renderanno anche il materiale trasparente. Per creare un cerotto con il filtro Intreccia e farlo sedere sopra i livelli sottostanti, usate il filtro Decalcomania.

1. Crea un filtro Decalcomania.
1. Aggiungi il filtro Intreccia allo slot di input del filtro Decalcomania.
1. Seguite i passaggi normali per regolare il pattern Intreccio.

Il livello Decal converte l’input Weave in un Decal: in questo modo la trasparenza del livello Weave indica al livello decalcomania come mascherare il pattern Woven. Con il livello Decal puoi anche spostare il pattern sul materiale o abilitare la funzionalità come affiancamento.
