Salve, il progetto è nato come esercitazione personale, utilizzando alcuni strumenti imparati nel corso Epicode a cui sto partecipando.


Si tratta di una richiesta di analisi fittizia, relativa al servizio in abbonamento offerto da Microsoft, denominato: "Gamepass", ovvero un servizio dove sono presenti diversi videogiochi scaricabili e giocabili solo con l'abbonamento attivo.

Ho utilizzato la tecnica del Web Scraping, tramite linguaggio di programmazione Python e notebook "Jupyter", utilizzando Excel e lo strumento di power query, per la pulizia del dato. 

Sono partito dal sito web: https://www.metacritic.com/news/xbox-game-pass-library/ considerando solo i titoli attualmente presenti nel servizio e senza contare: quelli che presto lasceranno il catalogo e quelli aggiunti nel mese di gennaio. Aggiornamento catalogo al 31/01/2025.
Per ogni gioco della lista, ho raccolto le seguenti informazioni (collegandomi direttamente alla pagina dedicata del sito web: "Metacritic"):

Titolo: Nome del videogioco;
Metascore: Valutazione del titolo da parte della critica;
Metascore_Reviews: Numero di recensioni critica;
User_Score: Valutazione del titolo da parte degli utenti della piattaforma;
Developer: Nome del team di sviluppo;
Genres: Generi di videogioco;
Released_on: Data di rilascio.

Per dettagli, visionare il file: "GamePass_Webscraping.ipynb"

Dopodichè ho salvato il file in csv e l'ho caricato in Excel per effettuare una pulizia dei dati tramite PowerQuery. 
Ho salvato il file come .xlsx, denominato "gamepass_data_pulizia_dato", per poter accedere facilmente alla query eseguita.
Ho salvato il risultato in formato .csv, denominato: "gamepass_pulito" e importato nuovamente in Jupyter, dove ho caricato il risultato dentro un dataframe ed eseguite le varie analisi del caso.

Per dettagli, visionare il file: "Gamepass - Metacritic - Analisi.ipynb"


Saluti,
Andrea Farinella
