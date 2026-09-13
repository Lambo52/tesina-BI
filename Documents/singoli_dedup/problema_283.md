Descrizione generale: Pagine WAMAS bloccate, DB non responsivo, TPO bloccati. Pagine bloccate, timeout DB, impossibile disconnettere utente FD33, TPO e LU bloccati, ricerca stock non funzionante.  
Causa identificata: Query di update TPO in attesa/timeout; possibile query atlas_cust su reportarchive ma non confermato.  
Soluzione / Workaround: Kill sessioni >10 sec, restart mobile terminal FD33, disconnessione utenti; sistema torna normale.  
Note: Root cause non determinata; possibile impatto report/query.
