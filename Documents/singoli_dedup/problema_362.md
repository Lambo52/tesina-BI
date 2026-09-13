Descrizione generale: Record 30 non inviato a host: disallineamento stock WAMAS/host. WAMAS non invia record 30 all’host; differenze inventariali tra WAMAS e host.  
Causa identificata: Flag “send stockadj” su false; difference confirmation create ma non convertite in Ack30.  
Soluzione / Workaround: Flag riattivato; invio manuale/riprocessamento delle diff conf; rischio doppie quantità se inviate due volte.  
Note: Da verificare tutte le diff conf tra 11:11:39 e 17:57:44; intervento manuale previsto.
