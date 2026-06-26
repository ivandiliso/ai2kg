
Una **Entity** rappresenta qualsiasi oggetto presente nel piano schematico, sia esso [Oggetti Virtuali](../Oggetti_Virtuali.md), [Oggetti Reali](../Oggetti_Reali.md) o [Oggetti Aggregati](../Oggetti_Aggregati.md).

Il concetto di Entity è una **superclasse comune** che viene poi specializzata da oggetti più specifici del dominio, i quali ne ereditano e raffinano le caratteristiche tramite attributi aggiuntivi.

Ogni Entity presenta informazioni riguardo la sua presenza o meno sul piano schematico reale, questo, permette di differenziare l'oggetto tra [Oggetti Reali](../Oggetti_Reali.md) e [Oggetti Virtuali](../Oggetti_Virtuali.md). 

>[!warning] KP e Entity
> Questa informazione non è sempre presente, ma può essere recuperata analizzando il valore di [Kilometric_Point](../Kilometric_Point.md), questo, se avvalorato a 0 o non presente, indica che l'Entità è di tipo [Oggetti_Virtuali](../Oggetti_Virtuali.md), non presenta quindi una posizione nel piano schematico reale. 

Ogni Entity:
- deve essere collegata a un [TrackSegment](TrackSegment.md)
- rappresenta un oggetto posizionato lungo un elemento del tracciato

Le Entity possono o meno presentare informazione sulla [Direzionalità](../Direzionalità.md) indicando la direzione rispetto al [TrackSegment](TrackSegment.md) di riferimento.



