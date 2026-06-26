
  
SWITCH  (direzionato)

lo switch è possigato su un segmento e ed connestto ad un altro segmento che viene chiamato trcksegment reverse id

uno swtich puo potenzialmente comunicare con ul altro switch 

se abbiamo un double slip abbiamo due deviatoi connessi tra di loro (diverso da comunicazione di due deviatoi) lo slip puo essere di diversi tipi e mette in connessione sempre ude deviatori, con specifiche di connessione e parametri diversi (futuro)

due deviatoi comunicanti DEVONO avere un percorso di tracksegment tra di loro 

la direezione va inferita dalla simmetria 

uno switch puo essere connesso ad un virtual switch che potrebbe essere vista come una forma di comunicazione come nelle connessioni tra switch e switch 

anche in questo caso ci deve essere un percorso 

  

una sottocategoria di deviatorio è il fermadeviatoio, questa specifica tipologia deve avere un insieme di “trasmetti chiave list” 

  

quindi uno switch puo essere uno ed uno solo di queste categorie:

- Fermadeviatorio: con la chiave 
    
- SlipDeviatoio: se è in connessione slip con un altro slip deviatorio 
    
- CommunicatingDeviation: Se comunica con un Coummunicate deviatorio
    
- VirtualCommnicatinDeviatorio: Se comunica con un VirtualSwitch 
    
- Deviatorio Semplice