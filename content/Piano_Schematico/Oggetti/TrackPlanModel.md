---
KP: false
Direction: false
---
Un TrackPlanModel rappresenta un gruppo di oggetti che descrivono una porzione di impianto ferroviario.  Ogni [Entity](Entity.md), [Area](Area.md), [TrackSegment](TrackSegment.md) o altri oggetti che descrivono una porzione di impianto, appartengono ad uno specifico TrackPlanModel.

>[!important] Porzioni di Impianto
 > Importante specificare che un TrackPlanModel non rappresenta un “intero impianto” ma una porzione di quest’ultimo. Questo, di conseguenza, non conterrà sempre tutta una linea (e.g. tutta la linea ferroviaria che collega una stazione X ad una stazione Y), ma potrebbe contenere informazioni di “fine linea” ([Terminale](../Terminale.md)). Queste informazioni, rappresentate, dai [TrackEnding](TrackEnding.md) sono oggetti che descrivono la fine della linea descritta nel piano schematico, e forniscono informazioni sui collegamenti successivi.