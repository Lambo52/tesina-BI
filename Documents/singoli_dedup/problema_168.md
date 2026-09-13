Descrizione generale: WAMASDB CPU 100%, blocco e OBD release stuck. CPU WAMASDB al 100%; WAMAS non usabile; restart instance+DB senza beneficio immediato; molti OBD in stato “release in progress”; possibile optimistic lock su release fallite.
Causa identificata: DB load elevato, grandi tabelle COD/COD, retention alta; optimistic lock.
Soluzione / Workaround: Restart; CPU scesa ma ancora alta; monitoraggio; ticket.
Note: Richiesta di non toccare dati storici; analisi cause.
