---
title: Kilometric Point
---

Il **Kilometric Point (KP)** rappresenta l'informazione di posizionamento che associa gli oggetti presenti nel piano schematico a uno specifico punto della rete ferroviaria reale.

Mentre le informazioni geometriche sono utilizzate per la rappresentazione grafica degli oggetti, il **punto chilometrico** consente di identificarne la posizione fisica lungo l'infrastruttura.

## Posizionamento lungo un TrackSegment

Un oggetto posizionato su un [TrackSegment](Oggetti/TrackSegment.md) può avere, ad esempio, un valore di **KP = 100**, indicando che si trova al metro 100 lungo il percorso del segmento.

La chilometrica è quindi associata a una **direzione di percorrenza**, che definisce il verso di incremento del valore di KP. A seconda della linea, il valore può:

- crescere da sinistra verso destra;
- crescere da destra verso sinistra.

Di conseguenza, lungo uno stesso [TrackSegment](Oggetti/TrackSegment.md) , un'entità posizionata **dopo** un'altra, rispetto alla direzione della chilometrica, deve avere un valore di **KP maggiore o uguale** a quello dell'entità precedente.

## Direzioni della chilometrica

All'interno dello stesso piano schematico possono coesistere linee con orientamenti chilometrici differenti. Ad esempio:

- una linea può avere la chilometrica crescente da **sinistra verso destra**;
- un'altra può avere la chilometrica crescente da **destra verso sinistra**.

Quando queste linee si intersecano, non è possibile assumere che la chilometrica sia monotona sull'intero piano schematico.

## Salti di chilometrica

Per gestire il cambio di orientamento della chilometrica è necessario considerare i cosiddetti **salti di chilometrica**.

Un salto di chilometrica rappresenta il punto in cui la continuità dell'ordinamento chilometrico viene interrotta a causa dell'intersezione tra linee con orientamenti diversi.

Nello stato attuale del modello, i salti di chilometrica possono avvenire esclusivamente su oggetti di tipo [Switch](Oggetti/Switch.md), poiché questi rappresentano l'intersezione tra più linee ferroviarie.