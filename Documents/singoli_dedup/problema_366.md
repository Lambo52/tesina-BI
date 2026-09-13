Descrizione generale: Record A5 in errore per OBD multipli e Rif Cl mancante. Messaggi A5 in post-elaboration error; WAMAS invia errore se trova più OBD per lo stesso ordine; campo Rif Cl non stampato su label.  
Causa identificata: Implementazione A5 che considera errore più OBD per order; campo prjreferenceorderclient non riportato in label.  
Soluzione / Workaround: Fix già predisposto per permettere più risultati; deploy necessario.  
Note: Record A5 deve comportarsi come record 05; verificare label Rif Cl.
