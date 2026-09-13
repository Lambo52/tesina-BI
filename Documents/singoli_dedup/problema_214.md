Descrizione generale: Labeler/printer, CU block, pending event, TEMP vs LU e TPO/manual area. Labeler in Notify e F01 con red bubbles; LU bloccata su CUCOD; WAMAS vede TEMP mentre MFS vede LU COD; pending event su TU; TPO non creati per picking station e manual area; mfArea queue bloccata.
Causa identificata: Pending event; disallineamento TEMP/LU; caricamento AF con TPO verso HBWCOD non corretto; possibile freeze DB.
Soluzione / Workaround: Eliminato pending event; cancellato pallet/TEMP; reset/riavvio MFS; TPO ricreati; manual area ripristinata.
Note: Ticket per analisi log; investigare disallineamento WMS/MFS.
