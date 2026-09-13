Descrizione generale: Unpick order su stazione COD, kind normal/extra-size e reset ordine. Unpick order assegnato a workstation COD, ma item extra-size non assegnabile a stazione normal; ordine resta Active; impossibile reset a new in caso di crane bloccato.
Causa identificata: Stazione kind “normal” vs item “EXTRA-SIZE”; logica reset unpick.
Soluzione / Workaround: Test con unpick normal; definita necessità di reset unpick a new; test successivo ok.
Note: Ticket marcato solved dopo test.
