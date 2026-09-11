---
helpx_url: "https://helpx.adobe.com/it/substance-3d-sampler/interface/panels/layers-panel.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il pannello Livelli in Substance 3D Sampler per gestire i livelli dei filtri e creare pile di materiale complesse.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Layers panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pannello Livelli
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '970'
ht-degree: 2%

---


# Pannello Livelli

<table>
<tr style="border: 0;">
<td style="border: 0; width: 70%" valign="top">

Il **pannello Livelli** contiene la Pila livelli e le scelte rapide per gestire i livelli. Il **pannello Livelli** funziona in modo molto simile al **pannello Proprietà**: selezionate un livello dal **pannello Livelli** per visualizzarne le proprietà nel **pannello Proprietà.**

Il **pannello Livelli** è composto da tre sezioni principali:

1. La sezione strumenti contiene i pulsanti che è possibile utilizzare per
   1. Mostra/Nascondi risoluzione livelli
   1. Strategia di risoluzione dei livelli di switch
   1. Aggiungi un livello
   1. Aggiungi un materiale di base
   1. Importa un filtro personalizzato
   1. Rimuovi un livello
1. Il **selettore della modalità Fusione** consente di regolare il modo in cui un livello si fonde con i livelli sottostanti. Il **selettore della modalità Fusione** è disponibile solo quando è selezionato un livello di materiale: i filtri non utilizzano i metodi di fusione.
1. La **Pila livelli** contiene tutti i livelli che compongono la risorsa.

</td>
<td style="border: 0;" valign="top">

![Animazione del pannello Livelli da nessun livello a una pila completa che crea un materiale](../../assets/Layers-panel-gen.png.img.png)

</td>
</tr>
</table>

## La Pila livelli

La Pila livelli è la raccolta di materiali, filtri e altre risorse che compongono il materiale corrente. Come in Photoshop e Substance 3D Painter, la Pila livelli funziona dal livello inferiore prima al livello superiore per ultimo. Ciò significa che ogni livello può influire sui livelli sottostanti.

Esistono alcuni modi per gestire la Pila livelli:

| Azioni | Procedure |
| --- | --- |
| Aggiungi un livello | Trascina una risorsa dal **pannello Risorse** nella finestra della vista per aggiungerla alla parte superiore della Pila livelli. Trascina una risorsa dal **pannello Risorse** nella Pila livelli per aggiungerla in una posizione specifica nella Pila livelli. Utilizza il pulsante **Aggiungi un livello** nella sezione degli strumenti per selezionare un filtro da un elenco. |
| Spostare un livello | Trascinate un livello nella Pila livelli per spostarlo. Quando si sposta un livello, viene visualizzata una barra che indica dove verrà inserito il livello. |
| Eliminare un livello | Fai clic su un livello per selezionarlo e premi **Canc** oppure utilizza il pulsante **Rimuovi livello** nella sezione degli strumenti. |
| Attiva/Disattiva visibilità | Passa il puntatore del mouse su un livello per visualizzare l&#39;**interruttore Visibilità** sul lato destro del livello. Quando la visibilità di un livello viene disattivata, non viene calcolata. |
| Visualizza proprietà livello | Fai clic su un livello per aprirne le proprietà nel **pannello Proprietà.** |
| Mostra/Nascondi risoluzione | Fai clic sul pulsante in alto a sinistra del **pannello Livelli**. |
| Cambia la risoluzione di tutti i livelli | Fai clic sulla freccia accanto al pulsante &quot;Mostra/Nascondi risoluzione&quot; e seleziona la strategia per tutti i livelli nella sovrapposizione. |
| Cambiare la risoluzione di un livello | Fai clic su un livello per aprirne le proprietà, quindi fai clic sulla risoluzione nel **pannello Proprietà** e seleziona la strategia di risoluzione da utilizzare per il livello. |

## Tipi di livelli

Esistono tre tipi di livello:

* Materiali
* Filtri
* Immagini

### Livelli di materiale

Un livello di materiale contiene informazioni in più canali e può essere fuso con i livelli sottostanti. I livelli di materiale vengono visualizzati in modo leggermente diverso a seconda che si trovino o meno nella parte inferiore della pila. Ad esempio, l&#39;immagine seguente mostra un materiale roccioso trascinato due volte nella Pila livelli: notate che il livello inferiore non ha un&#39;icona per controllare la fusione, mentre il livello superiore sì.

![Livelli di materiale nella Pila livelli, il livello superiore ha un&#39;opzione di fusione.](../../assets/Material-Layer.png)

Le regole generali per gli strati di materiale sono:

* Un livello di materiale utilizza sempre la risoluzione del documento.
* Un livello di materiale nella parte inferiore della pila non ha nulla con cui fondersi, quindi il **selettore della modalità Fusione** non è disponibile.
* Un livello di materiale che non si trova nella parte inferiore della pila può fondersi con i livelli sottostanti, quindi puoi utilizzare il **selettore della modalità Fusione** per modificare il metodo di fusione. Inoltre, accanto all&#39;**icona livello** viene visualizzata un&#39;icona di **fusione**. Seleziona l&#39;**icona di fusione** per regolare le impostazioni di fusione per il livello in base al quale è stato selezionato il metodo di fusione.

### Filtra livelli

![Proprietà del filtro Tonalità/saturazione che regolano i livelli sottostanti.](../../assets/HueSaturation_LayerFilter.gif)

I filtri eseguono operazioni sui livelli sottostanti per creare effetti specifici. Ad esempio, nell’immagine sopra il **filtro Tonalità/Saturazione** consente di regolare la tonalità, la saturazione e la Luminosità dei livelli sottostanti.

Alcuni filtri possono accettare uno o più livelli come input. Ad esempio:

* Il **filtro Atlas scatter** può utilizzare un materiale come input.
* Il **filtro Atlas scatter** dispersione le istanze dal materiale atlas di input in base ai parametri **Atlas scatter**.

Trascinate un materiale su uno slot di input dei livelli per utilizzarlo come input.

Un livello filtro utilizzerà la strategia di risoluzione predefinita impostata nelle preferenze. Puoi modificare la risoluzione utilizzata dal filtro nel pannello delle proprietà.

![Cambia la risoluzione di un livello filtro](../../assets/SwitchLayerResolution.gif)

### Livelli immagine

I livelli immagine utilizzano la propria risoluzione e si trovano principalmente nel flusso di lavoro da immagine a materiale. Come i livelli di materiale, puoi creare un livello immagine trascinando un&#39;immagine dal **pannello Risorse**.

Puoi trascinare un’immagine dal browser di file del sistema in Sampler. Se nella Pila livelli sono già presenti livelli, quello superiore verrà aggiunto alla sovrapposizione. Se la Pila livelli non contiene livelli, viene visualizzata una finestra di dialogo in cui è possibile scegliere come elaborare l’immagine:

* **L&#39;immagine in materiale** consente di utilizzare l&#39;intelligenza artificiale per convertire un&#39;immagine in un materiale.
* **Multiangolo su materiale** consente di utilizzare più immagini con condizioni di illuminazione diverse per creare un materiale.
* **Importazione Texture** consente di utilizzare le immagini importate come canali texture per creare un materiale.
* **Usa come bitmap** importa l&#39;immagine come semplice livello bitmap.

Potete anche trascinare contemporaneamente più immagini selezionate nella Pila livelli per importarle tutte come livello singolo. Questo può essere utile per i filtri multi-immagine come **HDR Merge** e **Multiangolo su materiale**. Seleziona il livello con più immagini per modificare i dati dei canali per ogni immagine.
