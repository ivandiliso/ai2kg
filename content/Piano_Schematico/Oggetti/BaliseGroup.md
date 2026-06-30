---
Direction: true
KP: true
---
Un **BaliseGroup** è un oggetto di tipologia [Entity](Entity.md) che presenta sia informazioni di [Direzionalità](../Direzionalità.md) sia informazioni riguardo alla posizione fisica sul piano schematico, cioè il [Kilometric_Point](../Kilometric_Point.md)


## Senso di Marcia

Un BaliseGroup contiene informazioni riguardo al [Senso di Marcia](../Senso_Marcia.md) del treno sul [TrackSegment](TrackSegment.md). Nello specifico, rispetto alla direzione di marcia legale, un BaliseGroup può includere informazioni relative a direzioni di traffico inverse rispetto alla marcia legale, espresse tramite un parametro `Direzione Traffico`, che specifica che il senso di marcia del traffico è inverso rispetto alla direzione delle balise.

## Gruppo Boe di Confine

Uno specifico sottotipo di balise è la **BoundaryBaliseGroup**. Questa a sua volta si divide in tre sottocategorie:

- **EntryBaliseGroup**: rappresenta l’entrata in una  [RBCArea](RBCArea.md). Nella validazione del dato, una EntryBaliseGroup deve avere un collegamento all’area RBC di competenza (possibile relazione di contenimento, ma non sempre obbligatoria).
- **ExitBaliseGroup**: rappresenta l’uscita da una [RBCArea](RBCArea.md). Nella validazione del dato, una ExitBaliseGroup deve avere un collegamento all’area RBC di competenza (possibile relazione di contenimento, ma non sempre obbligatoria).
- **HandOverBaliseGroup**: rappresenta un cambio dell'[RBCArea](RBCArea.md) di competenza. Un HandOverBaliseGroup può essere contenuto in una o più aree, con un minimo di contenimento pari a 1 (deve essere contenuto in almeno un’area).

