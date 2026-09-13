Descrizione generale: Area automatica bloccata / Notifica interna 21 / vecchi consolidation orders. Area automatica completamente bloccata due volte in 20 minuti; CPU ok; notifiche “Notifica interna 21” su COD/COD; due LU con inventory e consolidation orders vecchi di oltre 2 mesi impedivano la cancellazione; molti errori nei log.
Causa identificata: Inventory su LU con consolidation order; DB constraint che impediva delete; aumento temporaneo DB load.
Soluzione / Workaround: Cancellati ordini vecchi; ticket incidente chiuso; aperto problem ticket.
Note: Follow-up con email.
