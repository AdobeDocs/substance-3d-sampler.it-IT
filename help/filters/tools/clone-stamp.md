---
description: Utilizzate lo strumento Timbro Clona /Clone in Substance 3D Sampler per clonare e pittura le aree della texture per velocizzare le operazioni di modifica e riparazione del materiale.
title: Clona /Clone timbro
source-git-commit: 09278e59a21757710d15d1bb447002a4aecb25a7
workflow-type: tm+mt
source-wordcount: '872'
ht-degree: 1%
---

# Clona /Clone timbro

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-clonestamp-18-n-d.png)

**In:** Strumenti

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrizione

Lo strumento **Timbro Clona /Clone** consente di duplicare manualmente o applicare patch a parti del materiale. Viene utilizzato principalmente per correggere le giunture e rimuovere gli errori dai materiali scansionati, come detriti, ombre o artefatti. Puoi pittura più tratti di timbro da diverse aree sorgente all’interno di un singolo livello Timbro Clona /Clone e gestire ogni timbro singolarmente nel **pannello Livelli**.

Le immagini seguenti mostrano il **timbro Clona /Clone** utilizzato per rimuovere i detriti da un materiale innevato.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

Il materiale nevoso comprende un certo numero di ramoscelli e altri detriti sparsi intorno.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

Dopo aver utilizzato lo strumento **Timbro Clona /Clone**, i ramoscelli vengono sostituiti con neve pulita.

</td>
</tr>
</table>

## Parametri

**Parametri di base**

* **Espandi maschera**: 0-1

  Regolate la distanza attorno all’area dipinta che il filtro tenterà di abbinare al materiale sottostante.

* **Fusione dissolvenza**: 0-1

  Ammorbidite il bordo dell&#39;area clonata per fonderlo più naturalmente con il materiale circostante.

* **Maschera sfocatura**: 0-1

  Regolate la quantità di dettagli del bordo sul timbro clone. Più alti sono i valori, più uniformi e simili ai blob.

* **Mantieni rapporto**: attiva/disattiva

  Se è deselezionata, consente di regolare in modo indipendente le proporzioni orizzontale e verticale dell’area stampata.

  * **Orizzontale**: 0-2
  * **Verticale**: 0-2
* **Rotazione**: da -180 a 180

  Ruotate l&#39;area stampata in modo che corrisponda alla direzione o alla granulosità del materiale circostante.

* **Rifletti in orizzontale**: attiva/disattiva

  Specchiate l’area stampata lungo un asse orizzontale.

* **Rifletti in verticale**: attiva/disattiva

  Specchiate l’area stampata lungo un asse verticale.

**Fusione dissolvenza**

Utilizzate i controlli di fusione dissolvenza per canale per regolare in modo indipendente l’intensità di fusione per ciascun canale di materiale.

**Avanzate**

* **Intensità normale**: 0-2

  Regolate l’intensità della mappa normale nell’area stampata per controllare la risposta della superficie clonata all’illuminazione.

* **Posizione di origine**:
  * Orizzontale: 0-1: regola la posizione orizzontale della sorgente clone.
  * Verticale: 0-1 — regola la posizione verticale della sorgente clone.
* **Posizione di destinazione**:
  * Orizzontale: 0-1 — Regola la posizione orizzontale del bersaglio della pittura.
  * Verticale: 0-1 — regola la posizione verticale del bersaglio della pittura.
* **Modalità Affiancamento**: menu a discesa

  Attivate o disattivate l’Affiancamento durante la clonazione vicino ai bordi del materiale.

## Come usare Clona /Clone Stamp

1. Fai clic su **Clona /Clone timbro** nella barra laterale sinistra o aggiungilo dal pulsante **Aggiungi un livello** nel **pannello Livelli**. Viene visualizzato un nuovo livello Timbro Clona /Clone nella parte superiore della Pila livelli e **Vista 2D** si apre automaticamente.

1. **Imposta un punto di origine**: tieni premuto `Ctrl` (`Cmd` su macOS) e fai clic su un&#39;area pulita del materiale nel **Vista 2D**. Definisce l&#39;area che verrà copiata.

   > 📸 SCREENSHOT [ID: clone-stamp-001]
   > Mostra: finestra vista 2D con una crocetta del punto sorgente visibile su un&#39;area pulita di un materiale neve
   > Stato: Clona /Clone livello timbro selezionato; Ctrl premuto; indicatore sorgente visibile
   > Annotazione: assegnazione di un&#39;etichetta al mirino di origine

1. **Pittura sull&#39;area del problema**: fate clic e trascinate sull&#39;area da correggere. Il materiale proveniente dal punto sorgente sostituisce l’area dipinta in tempo reale.

   ![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

1. Regolate **Fusione dissolvenza** e **Espandi maschera** nel **pannello Proprietà** per perfezionare il modo in cui l&#39;area clonata si fonde con l&#39;ambiente circostante.

>[!NOTE]
>
> Evitate di posizionare il punto sorgente vicino all’area da clonare. Se la sorgente si sovrappone all’area problematica, l’artefatto può essere clonato insieme al contenuto pulito.

## Utilizzo di più sorgenti

Puoi aggiungere più punti sorgente all’interno di un singolo livello Timbro Clona /Clone, ognuno con impostazioni proprie di posizione, rotazione e fusione. Ciò consente di correggere diverse aree o di disegnare da diverse aree pulite senza sovrapporre più livelli.

Per aggiungere una nuova origine, tieni premuto `Ctrl` (`Cmd` in macOS) e fai clic su una nuova area nella **Vista 2D**. Una nuova voce del timbro viene visualizzata sotto il livello Clona /Clone timbro nel **pannello Livelli**.

> 📸 SCREENSHOT [ID: clone-stamp-002]
> Mostra: il pannello Livelli con un livello Timbro Clona /Clone espanso, che mostra tre singole voci di timbro nidificate sotto di esso
> Stato: Clona /Clone livello timbro espanso; tre timbri visibili con diverse posizioni sorgente
> Annotazione: freccia rivolta verso le voci di timbro nidificate nel pannello Livelli

Selezionate una voce del timbro nel **pannello Livelli** per regolarne i parametri in modo indipendente nel **pannello Proprietà**, comprese le impostazioni di posizione sorgente, rotazione e fusione.

>[!TIP]
>
> Prima di eseguire il commit di un tratto, utilizza l&#39;**anteprima pennello** nella **Vista 2D** per visualizzare il risultato del timbro. In questo modo è possibile verificare che l’area sorgente corrisponda all’area circostante prima di colorare.

## Barra degli strumenti

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Quando è selezionato un livello Clona /Clone timbro, in **Vista 2D** viene visualizzata una barra degli strumenti.

* Seleziona **Strumento Pennello** per aggiungere alla maschera.
* Seleziona **Strumento Cancella** per rimuoverlo dalla maschera.
* Impostate le dimensioni dello strumento attualmente selezionato.
* Accedere a controlli aggiuntivi:
  * **Affiancamento pennello**: attiva/disattiva l’Affiancamento pennello X e Y.
  * **Sovrapposizione**: attivate o disattivate la visibilità della sovrapposizione mentre passate il mouse sopra il Vista 2D.
* Visualizza **controlli Vista 2D**.

</td>
</tr>
</table>

>[!NOTE]
>
> Analogamente ad altre barre degli strumenti della finestra della vista, è possibile trascinare la maniglia nella parte superiore della barra degli strumenti per riposizionarla, fare doppio clic sulla maniglia per passare da un layout verticale a uno orizzontale oppure utilizzare la doppia virgoletta per nasconderla o espanderla.

## Scelte rapide

| Azione | Windows + Linux | macOS |
| --- | --- | --- |
| Aumenta dimensione pennello | `]` o `Ctrl` + rotellina del mouse | `]` o `Cmd` + rotellina del mouse |
| Riduci dimensione pennello | `[` o `Ctrl` + rotellina del mouse | `[` o `Cmd` + rotellina del mouse |
| Impostare la sorgente | `Ctrl` + clic sinistro | `Cmd` + clic sinistro |

## Correlati

* [Ordito](./warp.md)
* [Crea porzioni](./make-it-tile.md)
* [Immagine su materiale](./image-to-material.md)
