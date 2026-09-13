Descrizione generale: Post-deploy: CancelRequestEMS, counter COD, logout Bucket TO. Nuovo button “CancelRequestEMS” non funzionava; patch COD causava problema counter con workaround manuale; Bucket TO faceva logout utenti sull’ultimo TPO. Previsto deploy serale di revert/fix.
Causa identificata: Patch COD errata; bug Bucket TO.
Soluzione / Workaround: Revert COD e fix Bucket TO nel deploy serale; workaround manuale su stock.
Note: Deploy serale confermato.
