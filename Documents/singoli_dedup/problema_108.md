Descrizione generale: Pick Station 2 e 3: pallet in buffer non consegnati, TPO in errore. Pallet in buffer non arrivano alle stazioni. TPO in errore "ERROR_SOURCE_NOT_AVAILABLE". Impatto: stazioni bloccate.
Causa identificata: Location bloccate in HBW. WAMAS cancella la prenotazione ma non il TPO quando il rack è bloccato.
Soluzione / Workaround: Rimosso blocco, resume TPO. Ticket aperto.
Note: Sospetto: WAMAS cancella solo la prenotazione ma non il TPO.
