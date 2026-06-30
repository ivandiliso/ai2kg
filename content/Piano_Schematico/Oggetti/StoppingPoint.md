---
KP: true
Direction: true
---
Uno **StoppingPoint** è una tipologia di [Entity](Entity.md) che presenta una [Direzionalità](../Direzionalit%C3%A0.md) e un posizionamento fisico sul piano schematico, espresso tramite un [Kilometric Point](../Kilometric_Point.md).

Uno StoppingPoint può specificare informazioni relative al [Senso di Marcia](../Senso_Marcia.md) qualora questo sia opposto al senso di marcia legale.

Uno StoppingPoint può essere collegato a un [Signal](Signal.md); nello specifico, il collegamento è previsto con entità di tipo [VirtualSignal](VirtualSignal.md) o [ShuntilSignal](ShuntilSignal.md). Come specificato nella documentazione di [Signal](Signal.md), tale associazione è di cardinalità **1:1** uno StoppingPoint non può quindi essere collegato a più entità di tipo [Signal](Signal.md).


