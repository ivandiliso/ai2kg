---
title: Senso di Marcia
---
Il **senso di marcia** indica la direzione di circolazione consentita su un [TrackSegment](Oggetti/TrackSegment.md). Ogni impianto e/o tracciato può definire un senso di marcia legale di riferimento, specificando, ad esempio, che la circolazione avviene ordinariamente sul binario o sul tracciato di sinistra.

## Senso di Marcia Opposto

Alcuni oggetti, come:

- [BaliseGroup](Oggetti/BaliseGroup.md)
- [Signal](Oggetti/Signal.md)
- [StoppingPoint](Oggetti/StoppingPoint.md)

possiedono un'informazione relativa al **senso di marcia**. Questa è collegata all'informazione di **direzione**: come già specificato, esiste un senso di marcia di riferimento, ma vi sono casi particolari in cui il senso di marcia può essere opposto alla direzione convenzionale. Tali oggetti permettono di rappresentare questo tipo di informazione.

