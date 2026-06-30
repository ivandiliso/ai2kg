---
Direction: true
KP: false
---
Un Market (Marcatore) è una [Entity](Entity.md) del piano schematico che permette di caratterizzare un punto del piano schematico. Non presenta informazione della [Kilometric Point](../Kilometric_Point.md) ricadendo nella categoria degli [Oggetti Virtuali](../Oggetti_Virtuali.md). Un Marker può caratterizzare uno ed uno solo tra:

- [TrackCircuit](TrackCircuit.md)
- [TrackCircuitJoint](TrackCircuitJoint.md)
- [Signal](Signal.md)
- [VirtualSignal](VirtualSignal.md)

Questo significa che un marcatore NON può essere collegato contemporaneamente ad uno di questi oggetti, ma se collegato a qualcosa DEVE essere uno di questi oggetti. 
