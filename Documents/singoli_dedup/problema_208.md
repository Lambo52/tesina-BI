Descrizione generale: MFS/Lighthouse down e LU cancellata con picking attivo. MFS/Lighthouse in errore; pallet non visibili; dopo restart ripristino; WAMAS tentava di cancellare LU con attività di picking.
Causa identificata: Messaggio REST di fine picking non processato in tempo; job di pulizia dati.
Soluzione / Workaround: Auto-ripristino dopo retry/correlazione dati; restart Lighthouse.
Note: Definito evento sfortunato/one-off.
