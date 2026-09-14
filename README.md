Message preprocessing e anoimyze fatti a tirocinio, i 2 file su entity resolution fatti per tesina BI

nel preprocessing vengono trasformati i messaggi raw di whatsapp nascondendo numeri di telefono ecc. sono trasformazioni semplici, ChatSSI -> ChatSSI_clean

in anonimyze viene usato il llm locale (qwen3-32b) per anonimizzare i messaggi a finestra scorrevole ChatSSI_clean -> ChatSSI_clean_anon

poi divisi per anno i messaggi sono stati caricati su claude per ottenere i problemi singoli -> 202X_anon_singoli

in entity_resolution ogni problema singolo viene embeddato e caricato su qdrant, poi si fa una ricerca ibrida topk=5 e viene interrogato il llm locale (gemma4-12b) con risposta SI o NO se sono lo stesso problema o no, se A=B e B=C allora in automatico A=C -> problemi_deduplicati

in entity_resolution2 vengono presi i problemi deduplicati e con l'interrogazione del llm locale (gemma4-12b) vengono trasformati in un problema singolo, prima il problema deduplicato era la descrizione di 2 problemi distinti, ora diventa la descrizione di un problema singolo, e ogni problema viene messo in un file a parte .md, pronto per l'indicizzazione su qdrant