---
title: Riempimento in base al contenuto
description: Scoprite come utilizzare il filtro Riempimento in base al contenuto in Substance 3D Sampler per risolvere i problemi relativi ai pattern ripetuti o rimuovere dirt o sporcizia indesiderati.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 1%
---

# Riempimento in base al contenuto

<table>
  <tr>
    <td><img src="../../assets/Filters/S_ContentAwareFill_18_N_D.png" alt=""/><br><strong>In:</strong> Strumenti</td>
    <td>Descrizione<br>Il riempimento in base al contenuto consente di rimuovere senza problemi elementi come dirt, testo o altri oggetti indesiderati dai materiali.<br>Nell'esempio seguente sul pavimento della foresta, il bastone si distingue nel motivo ripetuto. Con Riempimento in base al contenuto, possiamo rimuovere il rametto, rendendo la ripetizione un po' meno evidente. <br><br><img src="../../assets/content-aware-fill-before.png" alt=""/><br><em>Prima della rimozione</em><br><br><img src="../../assets/content-aware-fill-after.png" alt=""/><br><em>Dopo la rimozione</em></td>
  </tr>
</table>

## Parametri

* **Selezione canali:** selezionare i canali su cui eseguire il filtro. Per impostazione predefinita, questa opzione è impostata su tutti i canali; tuttavia, potete anche scegliere di eseguire solo sui canali del Height o del Colore di base.
* **Speculare:** Per i materiali o i pattern simmetrici, questa impostazione guida Riempimento in base al contenuto per incorporare il contenuto di mirroring nel materiale.
* **Scala:** Per motivi geometrici quali porzioni o mattoni, questa impostazione consente di mantenere inalterata la struttura del motivo.

### Parametri tecnici

* **Maschera personalizzata:** applicate una maschera utilizzando una texture o usate il pennello per pittura la vostra maschera nel **riquadro di visualizzazione 2D**.
* **Cerca fattore di ritaglio:** Ritaglia l&#39;area campione utilizzata dal filtro. Per impostazione predefinita, l’area campione copre l’intera texture eccetto l’area mascherata. Aumentando il **fattore di ritaglio ricerca**, l’area campione viene ridotta in modo da limitare i campioni ai pixel più vicini all’area mascherata.

### Impostazioni di riempimento

* **Adattamento colore:** regolate il grado di adattamento del riempimento ai colori circostanti. Questa impostazione può essere utile con materiali che
* **Adattamento rotazione:** per i pattern in cui la rotazione degli elementi è importante, ad esempio i petali di un fiore o i raggi di una ruota, questa impostazione può contribuire a creare risultati più coerenti.