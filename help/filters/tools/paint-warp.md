---
title: Pittura alterazione
description: Scoprite come utilizzare il filtro Alterazione Pittura in Substance 3D Sampler per un controllo preciso dell’alterazione del materiale.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 2%
---

# Alterazione dipinto

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_WarpPaint_18_N_D.png" alt=""/><br><strong>In:</strong> Strumenti</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il filtro <strong>Alterazione Pittura</strong> è uno strumento potente progettato per correggere distorsioni geometriche nelle scansioni basate su immagini. È particolarmente utile per materiali con pattern lineari, come tessuti di velluto, tavole di legno o mattoni, in cui le linee naturali non sono perfettamente dritte o allineate con gli assi. Definendo manualmente il flusso del pattern, potete "raddrizzare" il materiale per garantire mappe di texture di Affiancamento e professionali senza interruzioni.<br></td>
  </tr>
</table>

## Allineamento delle serie di materiali

Potete aggiungere manualmente il filtro Alterazione Pittura alla Pila livelli, ma il flusso di lavoro più efficiente per le scansioni consiste nell’utilizzare l’azione rapida dedicata.

### Utilizzo dell&#39;azione rapida

1. Apri la scheda **Azione rapida**.
1. Selezionate **Allinea pattern materiale mediante disegno**.

* Sampler aggiungerà automaticamente tre livelli alla pila: **Equalizza**, **Alterazione Pittura orizzontale** e **Alterazione Pittura verticale**.

1. Nella **Pila livelli**, identifica la direzione che segue il tuo pattern.

* *Esempio:* per la torbiera con nervature verticali, mantieni **Alterazione Pittura verticale** e disabilita o elimina la versione orizzontale.

### Colorare le guide di alterazione

Una volta selezionato il filtro, è necessario definire il percorso &quot;storto&quot; corrente del pattern, in modo che Sampler sappia come raddrizzarlo.

1. Accedete al pannello **Proprietà** del filtro Alterazione Pittura.

1. Individuate la proprietà **Input immagine** e fate clic sull&#39;icona **Pennello** accanto ad essa per accedere alla modalità di disegno.

1. Regola la **Dimensione pennello** utilizzando i widget o le scelte rapide dell&#39;interfaccia utente.

1. Pittura lungo le linee del materiale:

   >[!TIP]
   >
   > Tieni premuto **Maiusc** e fai clic per creare segmenti perfettamente dritti tra i punti.

1. Tracciate diverse linee lungo la larghezza o il height della texture per fornire all&#39;algoritmo dati sufficienti.

1. Nel pannello **Proprietà**, impostate il parametro **Raddrizza** su **Attivato**. Sampler altererà l’immagine in modo che le linee dipinte diventino perfettamente parallele all’asse scelto.

## Riferimento parametri

| Nome | Descrizione | Intervallo/Opzioni | Impostazione predefinita |
| --- | --- | --- | --- |
| **Direzione** | Determina l’asse a cui si allineerà l’alterazione. | Verticale, Orizzontale | Verticale |
| **Raddrizza** | Attiva o disattiva l’effetto di alterazione in base alla maschera dipinta. | Attiva/disattiva (On/Off) | Disattivato |
| **Mostra input** | Una sovrapposizione di supporto che visualizza le guide per migliorare la precisione del disegno. | Attiva/disattiva (On/Off) | Disattivato |
| **Alterazione uniforme** | Controlla il decadimento e lo smoothness della deformazione tra le guide dipinte. | 0.0 - 1.0 | 0.5 |

## Suggerimenti e procedure consigliate

* **Usa Mostra input:** Abilita l&#39;interruttore **Mostra input** durante il disegno. In questo modo è possibile ottenere una griglia in sovrapposizione che consente di vedere più facilmente la posizione esatta della scansione originale rispetto a una griglia perfetta.
* **Non sovraccaricare la Pittura:** non è necessario tracciare ogni singola riga in un pattern. Di solito, da 3 a 5 linee ben posizionate sulla texture sono sufficienti per permettere all&#39;algoritmo di calcolare la deformazione necessaria.
* **Combinare con l&#39;Affiancamento:** Utilizzare Alterazione Pittura prima di applicare il filtro **Affiancamento**. Un pattern raddrizzato è notevolmente più facile da affiancare senza giunture visibili o linee &quot;rotte&quot; ai bordi.
* **Equalizza prima:** Come mostrato nell&#39;azione rapida, il posizionamento di un filtro **Equalizza** prima di Alterazione Pittura consente di rimuovere le sfumature di luce, rendendo più facile visualizzare i dettagli del pattern che si sta tentando di allineare.

## Articoli correlati

* [Equalizza](../adjustments/equalize.md)
* [Affiancamento](tiling.md)
* [Azioni rapide](../../features-and-workflows/quick-actions.md)
* [Best practice per la scansione](../../pipeline-and-integrations/hp-z-captis-support/scanning-best-practices.md)
