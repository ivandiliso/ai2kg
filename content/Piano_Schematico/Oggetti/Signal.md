---
Direction: true
KP: true
---
Un Signal (Segnale) è una tipologia di [Entity](Entity.md) che presenta sia informazione [Direzionalità](../Direzionalità.md) che informazione riguardo il posizionamento fisico [Kilometric Point](../Kilometric_Point.md). Un Signal può essere accoppiato ad uno [StoppingPoint](StoppingPoint.md), se questa relazione esiste, può essere una ed una sola (si intende una relazione 1 a 1 con oggetti di tipo [StoppingPoint](StoppingPoint.md)). Un Segnale può essere collegato a oggetti di tipologia [Marker](Marker.md) o [MarkerGroup](MarkerGroup.md). 

Un Signal può specificare informazione riguardanti il [Senso di Marcia](../Senso_Marcia.md) nel caso questo sia inverso rispetto al senso di marcia legale. 

Un Signal presenta due principali sottocategorie:

- [ShuntilSignal](ShuntilSignal.md)
- [VirtualSignal](VirtualSignal.md)