---
Direction: true
KP: true
---

Un KPJump indica un cambio del valore di [Kilometric_Point](../Kilometric_Point.md) tra un [TrackSegment](TrackSegment.md) e un altro. Viene quindi indicato il valore di KP sia a sinistra che a destra. Un KPJump solitamente poggia sopra un [KPPoint](KPPoint.md) quando questo è posizionato su un [TrackCircuitJoint](TrackCircuitJoint.md). 

Per gestire il cambio di orientamento della chilometrica è necessario considerare i cosiddetti **salti di chilometrica**.

Un salto di chilometrica rappresenta il punto in cui la continuità dell'ordinamento chilometrico viene interrotta a causa dell'intersezione tra linee con orientamenti diversi.




>[!warning] KPJump e Entity
> Nel piano schematico viene solitamente considerata una [Entity](Entity.md), ma in questo caso, ricade nella categoria degli [Oggetti_Virtuali](../Oggetti_Virtuali.md) e/o tipologia di oggetti che caratterizza ulteriormente un oggetto esistente, piu che un elemento a se. 

