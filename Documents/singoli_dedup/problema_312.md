Descrizione generale: COD TPO non trova route (printing/wrapping logic). Pallet COD non si muove. MFS non trova una route appropriata. Impatto: pallet bloccato.
Causa identificata: Bug nella logica: pallet con solo printing (no wrapping) deve usare solo le corsie posteriori, ma un'altra condizione impedisce l'uso delle corsie posteriori per stazioni 7-12.
Soluzione / Workaround: Fix programmata per la settimana successiva.
Note: Bug confermato.
