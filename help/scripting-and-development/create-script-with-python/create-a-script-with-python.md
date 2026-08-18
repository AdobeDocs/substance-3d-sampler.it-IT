---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Scoprite come creare script Python per Substance 3D Sampler per automatizzare i flussi di lavoro ed estendere le funzionalità delle applicazioni.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creare uno script con Python
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Creare uno script con Python

Questa guida descrive come creare un semplice plug-in di salvataggio automatico con Python.

## Struttura dello script

Per poter essere importati in Sampler, gli script richiedono un singolo file PY. Puoi salvare lo script di esempio seguente come file PY e importarlo in Sampler.

## Esempio di script

Lo script seguente crea automaticamente le variazioni del materiale selezionando un nuovo valore di partenza casuale per ciascun livello del materiale. Ciò è utile per garantire che il materiale possa essere utilizzato in un caso generale invece di affidarsi a semi casuali specifici.

### random\_seed\_changes.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


Il codice precedente include commenti per spiegare cosa sta succedendo su ciascuna riga.

## Importare lo script

Dopo aver salvato lo script sopra riportato come file PY sul computer, potete importarlo con Modifica > Preferenze > Plug-in e script. Una volta importata, nella barra dei menu verrà visualizzata un&#39;opzione **Script** insieme a **File** e **Modifica**. Da qui potete eseguire lo script.

Ulteriori informazioni sulla gestione degli script [sono disponibili qui](../manage-installed-plugins-and-scripts.md).
