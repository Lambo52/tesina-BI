Descrizione generale: Finalizzazione errata di una singola attività di picking che causa il blocco dell'intero Picking Order (PO) come "Finalized", impedendo alla stazione di ricevere nuove attività.
Causa: Bug nel sistema che marca l'intero PO come "Finalized" quando viene completata solo una specifica activity.
Soluzione / Workaround consolidato: Rimozione manuale del flag "Finalized" dal Picking Order per consentire la ripresa delle operazioni.
Note: Problema ricorrente riscontrato in diverse stazioni (3 e 2) tra il 2021 e il 2022; il bug è stato confermato e documentato (Issue D142).