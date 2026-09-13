Descrizione generale: Post-deploy: TPO manuali, CPU DB alta, zombie session, rollback. Dopo deploy, TPO manuali non funzionanti; utenti kicked out; messaggio “LU-ID has not a planned TPO”; auto-allocation vuoto; CPU WAMASDB >90%; DB load elevato; pick station con source TPO in stato new; infine blocco e rollback.
Causa identificata: Zombie session non killata dalla precedente istanza; DB load; possibile concausa deploy.
Soluzione / Workaround: Kill zombie session; restart; rollback serale; CPU rientrata.
Note: Rollback eseguito; monitoraggio weekend.
