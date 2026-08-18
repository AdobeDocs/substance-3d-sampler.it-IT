---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/panels/channel-settings-panel.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il pannello Impostazioni canale in Substance 3D Sampler per gestire i canali di materiale e controllare la visibilità del canale.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Channel Settings panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pannello Impostazioni canale
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 1%

---


# Pannello Impostazioni canale

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


Il pannello **Impostazioni canale** controlla l’elenco dei canali calcolati per il materiale corrente. Potete gestire la visibilità dei canali, aggiungere o rimuovere canali dal materiale o modificare il modello di materiale utilizzato.

</td>
<td style="border: 0;" valign="top">

![Il pannello delle impostazioni dei canali.](../../assets/6.0_ChannelSettingsPanel.png)

</td>
</tr>
</table>

## Modello di materiale

Utilizza questo menu a discesa per selezionare il framework dello shader utilizzato per eseguire il rendering del materiale. Le opzioni nel **pannello delle impostazioni dei canali** cambieranno in base al modello di materiale selezionato.

Quando modificate il modello di materiale, la pila di livelli dovrà essere ricalcolata per il nuovo modello e saranno disponibili diversi canali. Sampler tenta di ridurre al minimo la perdita di dati nella conversione; tuttavia, è possibile che la modifica comporti lievi differenze nell’aspetto con un nuovo modello di materiale.

>[!NOTE]
>
> È possibile passare da Adobe Standard Material(ASM) ad OpenPBR, ma attualmente non è possibile passare da OpenPBR ad ASM.


## Canali del materiale

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


Questa sezione visualizza l’elenco dei canali calcolati per impostazione predefinita in base al flusso di lavoro.

Puoi utilizzare il **pulsante Modifica elenco** per aprire la **selezione canale** e modificare i canali calcolati per il materiale.

</td>
<td style="border: 0;" valign="top">

![Il pannello delle impostazioni dei canali con la sezione dei canali dei materiali evidenziata](../../assets/6.0_ChannelSettingsPanel_MaterialChannels.png){width="200px"}

</td>
</tr>
</table>

>[!NOTE]
>
> Alcuni materiali di Substance Source, ad esempio, non generano canali di opacità o occlusione ambientale. Anche se il canale di opacità è contrassegnato come &quot;calcolato&quot;, se il file di Substance non lo genera, Sampler non lo genera.

### Selezione canale

La finestra di selezione Canale consente di aggiungere o rimuovere canali dal materiale.

![Schermata della finestra di selezione del canale con Materiale standard Adobe selezionato come Modello di materiale.](../../assets/6.0_ChannelSelectionWindow.png)

Per aggiungere un canale al materiale, seleziona un canale disponibile e utilizza il pulsante **>**.
Per rimuovere un canale dal materiale, seleziona il canale dall&#39;**elenco dei canali selezionati** e utilizza il pulsante **&lt;**.
Puoi aggiungere tutti i canali disponibili al tuo materiale con il **pulsante ≫** o rimuovere tutti i canali dal tuo materiale con il **pulsante ≪**.

Potete anche usare i predefiniti per selezionare rapidamente un elenco di canali per il materiale. Per impostazione predefinita, Sampler include diversi predefiniti, ma potete anche crearne di nuovi:

1. Aggiungete i canali desiderati al materiale.
1. Utilizza il **pulsante Salva come predefinito**.
1. Assegna un nome al predefinito.

>[!NOTE]
>
>Quando salvate un predefinito, questo non viene applicato al materiale.

## Canali personalizzati

Per impostazione predefinita, attiva/disattiva i canali aggiuntivi non inclusi nel flusso di lavoro selezionato.

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">

Ogni canale personalizzato ha due opzioni che puoi utilizzare per controllarlo:

1. Utilizzare l&#39;interruttore Visibilità per mostrare o nascondere il canale nella vista 2D.
2. Utilizza il **pulsante Automatico** per attivare o disattivare il calcolo automatico del canale.
   * Se attivato, il canale verrà calcolato se lo richiede un livello sopra di esso nella pila.
   * Se disattivato, il canale viene sempre calcolato.

</td>
<td style="border: 0;" valign="top">

![Il pannello delle impostazioni dei canali con la sezione dei canali personalizzati evidenziata.](../../assets/6.0_ChannelSettingsPanel_CustomChannels.png){width="200px"}


</td>
</tr>
</table>



