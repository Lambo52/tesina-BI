Descrizione generale: Errori PLC/DB, inventory mode e ordini inventory duplicati. Errori PLC, eventi processati lentamente, DB session bloccata, picking station #4 in inventory mode; due pallet logicamente su 118; inventari con moltissime LU e tre inventory order dalla stessa demand.
Causa identificata: Sessione DB inattiva creata da terminale COD; inventory area iACX_Pal/iArea includeva molte locazioni.
Soluzione / Workaround: Uccisa sessione DB; cancellati ordini inventory; COD sistemato; monitoraggio.
Note: Ticket aperto; verificare log e comportamento inventory.
