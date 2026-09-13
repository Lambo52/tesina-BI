Descrizione generale: Pick Station 7: pallet in loop, errori su LU. BP07 D01 ha pallet vuoto non utilizzabile (no shipLU flag, no OBD). BP07 D02: pallet portato e ritirato in loop da AGV. Impatto: stazione inutilizzabile.
Causa identificata: Pallet COD aveva un errore "not empty" del giorno prima. Qualcuno ha cancellato il TPO e il sistema lo ha inviato a S46 con l'errore. Tornato alla stazione, l'errore persisteva. La logica di "fare spazio" creava il loop.
Soluzione / Workaround: Risolvere errore sul pallet. Pallet tornato funzionante.
Note: Invito a non movimentare pallet con errori.
