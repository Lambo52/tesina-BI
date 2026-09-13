Descrizione generale: Pick Station 3 bloccata: switch picking→unpicking causa deadlock. Passando da picking a unpicking, WAMAS non permette di finire l'ultimo ordine. Deadlock. Stazione senza pallet source e destination. Impatto: stazione 3 ferma.
Causa identificata: Switch diretto da picking a unpicking senza passare per "Stop". Il sistema considera il pallet non adatto all'unpick e lo invia a S46.
Soluzione / Workaround: Inviato pallet vuoto H alla destinazione. Workaround: passare sempre per "Stop" prima di unpick. Fix in sviluppo.
Note: Ticket aperto. Workaround: Stop → ultimo pick → Unpick.
