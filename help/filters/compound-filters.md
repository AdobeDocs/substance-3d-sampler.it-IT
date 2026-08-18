---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Scoprite come creare e utilizzare i filtri composti in Substance 3D Sampler per combinare più filtri in singoli livelli riutilizzabili.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Filtri composti
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# Filtri composti

Questa funzione consente di creare un nuovo tipo di filtri rappresentati come livello singolo nell’interfaccia e composti da più filtri.

>[!NOTE]
>
> Supportato da Substance 3D Sampler 3.1.0

## Descrizione

Un filtro composto è un file **.ssafilter** che è una cartella compressa .7zip di:

* un file di descrizione che utilizza la formattazione JSON: **myfilter\_name.json**
* una cartella **resources** contenente:
  * miniatura del filtro: icon.png
  * dipendenze file esterni

### Contenuto file descrizione

* Nome: etichetta del filtro composto visualizzata nell’interfaccia
* ID: Identificatore univoco del filtro composto
* Categoria: categoria del filtro composto utilizzato nel pannello Risorse quando raggruppi le risorse per categoria
* Versione: numero incrementale per definire la versione del filtro composto.
* Nodo: elenco di nodi da utilizzare
* Collegamento: elenco delle connessioni tra i diversi nodi

### Esempio

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## Creazione dettagliata

1. Crea un nuovo file: **my\_new\_filter.json**
1. Definirne il nome, l&#39;ID, la categoria...
1. Definire l&#39;elenco di nodi necessari
1. Se sono necessari file esterni, crea la cartella **resources** accanto a **.json**
1. Aggiungi i file nella cartella **resources**
1. Scrivere l&#39;elenco dei collegamenti tra i nodi
1. Verifica che il tuo codice JSON sia valido (nessun errore di battitura, coma mancante o parentesi quadra mancante)
1. Se desideri una miniatura, aggiungi un&#39;immagine **icon.png** nella cartella **resources**
1. Seleziona il file **.json** e la cartella **resources** e comprimerli

## Documentazione

### Versione

L’uso di un numero di versione consente di tenere traccia delle diverse iterazioni. Quando si apre una pila di livelli creata con una versione precedente del filtro composto, viene visualizzata una notifica che suggerisce di eseguire l’aggiornamento alla versione più recente.

### Nodo

Un nodo può fare riferimento a un filtro interno di Substance 3D Sampler. Definire un identificatore univoco **Id** da utilizzare per definire i collegamenti tra i nodi e l&#39;etichetta del filtro interno **InternalFilter**

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

Un nodo può fare riferimento a un file SBSAR non presente in Substance 3D Sampler. Definire un identificatore univoco **Id** da utilizzare per definire i collegamenti tra i nodi e il nome file **File** del file SBSAR. Il file SBSAR deve trovarsi in una cartella **resources** accanto al file .alchfilter.

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> Impossibile utilizzare **filterImg** e **filterMat** come ID nodo

### Collega

Un collegamento è una descrizione del modo in cui due nodi sono collegati e sono composti da due elementi:

* Da: uso che deve essere utilizzato dal nodo
* A: output di utilizzo del nodo

Ogni elemento ha 3 attributi:

* Nodo: dichiarare **Id** del nodo che si desidera utilizzare
  * impostare l&#39;input del filtro composto. ID nodo: **FilterInput**
  * per impostare l&#39;output del livello composto, l&#39;ID nodo è **FilterOutput**
* Utilizzo: dichiarare l&#39;utilizzo che si desidera utilizzare. Sono disponibili 3 opzioni:
  * Utilizzo singolo alla volta e dichiarazione del collegamento per collegamento (baseColor, normal, height, ambientOcclusion, rugosità, metallizzato, diffuso, specular, lucidità, specularLevel, opacità, emissivo, scan1, ...)
  * Potete anche specificare un elenco [&quot;baseColor&quot;, &quot;normal&quot;]. Il primo elemento dell&#39;elenco di **Da** corrisponderà al primo elemento dell&#39;elenco di **A**. ecc...
  * Utilizzare **\*** per consentire a Substance 3D Sampler di effettuare la corrispondenza tra gli usi identici di tutti gli usi del nodo Da e del nodo A (non è possibile combinare **\*** con un altro collegamento, mentre collegamenti singoli ed elenchi sono possibili tra gli stessi nodi)
* Gruppo: nel caso in cui un nodo abbia più volte lo stesso utilizzo, puoi utilizzare l&#39;attributo Gruppo per selezionare un utilizzo specifico. Per i filtri di fusione, per ottenere il valore baseColor del materiale inferiore usa *Material1* e per ottenere il valore baseColor del materiale superiore usa *Material2*

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
