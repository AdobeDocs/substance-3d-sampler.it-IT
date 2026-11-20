---
description: Usa il filtro Finitura legno in Substance 3D Sampler per applicare varie finiture e texture della superficie del legno ai tuoi materiali.
title: Finitura legno
hold: true
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 0%
---

# Finitura legno

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_Wood_18_N_D.png" alt=""/><br><strong>Entrata:</strong> usura e fine</td>
    <td style="border: 0;" valign="top">Descrizione<br>Aggiungete dettagli normali e di rugosità al materiale per aggiungere rifiniture generalmente associate al legno, come vernici, ceruse o grana di legno.<br><em>Un colore di riempimento semplice</em><strong><em> </em></strong><em>dà l'aspetto del legno aggiungendo grana di legno con il </em><strong><em>filtro Finitura legno</em></strong><em>.</em><br><img src="../../assets/wood-finish-before.png" alt=""/><img src="../../assets/wood-finish-after.png" alt=""/></td>
  </tr>
</table>

## Parametri

**Parametri di base**

* **Numero casuale**:

  Il valore di inizializzazione casuale determina i valori casuali di altri parametri che utilizzano la casualità in questo filtro.

* **Tipo di fine**:

  Selezionate uno stile da applicare al metallo. Ogni stile ha parametri diversi che consentono di regolarne l&#39;aspetto. A parte la finitura **Natural**, ogni finitura dispone di un set di parametri per controllare l&#39;effetto.

  Sono disponibili le seguenti finiture:

  * **Naturale**: una finitura naturale liscia per il legno lavorato.
  * **Ceruse**: create un aspetto morbido e bicolore, riempiendo i pori aperti con un pigmento.
  * **Vernice opaca**: aggiungete una finitura opaca morbida.
  * **Vernice**: aggiungete una finitura di vernice altamente riflettente.
  * **Vecchio**: regola il colore e la ruvidità del materiale sottostante per creare l&#39;aspetto del legno invecchiato.
  * **Non elaborato**: aggiungete un po&#39; di grana di legno per creare l&#39;aspetto del legname tagliato.
  * **Segato**: aggiungete tracce di seghe per creare l&#39;aspetto del legno fresco dal mulino a legna.

### Parametri condivisi

I seguenti parametri vengono visualizzati per più finiture:

* **Tonalità**: regola il colore del materiale.
* **Saturazione**: regola l&#39;intensità del colore.
* **Luminosità**: regola la luminosità.
* **Intensità rugosità**: regolate la rugosità del materiale.
* **Intensità rugosità fibre**: aggiunge informazioni sulla rugosità ad alta frequenza alla mappa rugosità. Si combina con il cursore Intensità rugosità per modificare i valori di rugosità, sia che il materiale sia molto uniforme che molto ruvido.
* **Intensità normale**: regola l&#39;intensità della mappa normale.
* **Contrasto maschera fibre**:

### Finiture

#### Ceruse

* **Colore 1**:
* **Colore 2**:
* **Variazioni Colore di base**:
* **Dettagli alta frequenza**:

#### Vernice

* **Variazioni orientamento fibre normali**:

#### Vecchio

* **Intensità rugosità vernice**:
* **Rotazione effetto**:

#### Grezzo

* **Informazioni aggiuntive normali**:

#### Segato

* **Riduzione della rugosità con fibre**: regola la rugosità lungo le linee della sega, creando un contrasto di rugosità.
* **Numero tagli sega**: regolate il numero di linee delle seghe.
* **Regolarità maschera**: regolate la frequenza con cui appaiono le linee della sega. Un valore più alto rende le linee meno regolari.
* **Fibre aggiuntive**: regolate il numero di fibre aggiunte parallelamente alle linee della sega.
