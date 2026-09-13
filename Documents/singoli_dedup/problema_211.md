Descrizione generale: Outbound messages non Finished, MqSender reset e proxy machine. Messaggi outbound non in Finished; reset MqSender; backup/IT con proxy machine causava disconnessione DB e freeze WAMAS; SRM coinvolti.
Causa identificata: Proxy machine usata per copia VM non disabilitata durante backup.
Soluzione / Workaround: Reset MqSender; rimossa proxy machine; backup solo a WAMAS spento.
Note: Ticket chiuso.
