
Oggetti del piano schematico presentano un’informazione di direzionalità. La direzionalità definisce la direzione (sinistra, destra o bidirezionale) di un oggetto. La direzione non è sempre un’informazione esplicita: a volte viene inferita solo dall’informazione grafica, analizzando visivamente il simbolo relativo all’oggetto.

I [TrackSegment](Oggetti/TrackSegment.md) possono essere bidirezionali (nel senso di contenere due tracciati, uno per la direzione SINISTRA e uno per la direzione DESTRA). Si assume che la direzione di percorrenza sia sempre quella sinistra.

È quindi possibile inferire che un segnale direzionato a sinistra vada collocato “SOPRA” dal punto di vista della rappresentazione grafica, mentre uno direzionato a destra vada collocato SOTTO il [TrackSegment](Oggetti/TrackSegment.md), sempre seguendo la rappresentazione grafica.

