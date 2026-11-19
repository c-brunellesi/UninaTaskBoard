# UninaTaskBoard

Applicazione desktop Java Swing per organizzare progetti collaborativi e attività universitarie.

## Codice sorgente

Scarica il pacchetto del progetto, con sorgenti Java, logo, librerie, documentazione e migrazioni SQL: [UninaTaskBoard_sorgenti.zip](UninaTaskBoard_sorgenti.zip).

## Avvio

Richiede Java 21, PostgreSQL ed Eclipse o un ambiente Java compatibile. Estrai lo ZIP, importa la cartella `UninaTaskBoard` in Eclipse e avvia `UninaTaskBoard_Launcher.MainUTB`. Le librerie JDBC PostgreSQL e JFreeChart sono incluse nella cartella `lib`.

## Database

La connessione usa il database PostgreSQL locale `UninaTaskBoard`, porta `5432`, utente `postgres`. La password si configura come variabile `DB_PASSWORD` nell’ambiente di esecuzione Java. Il database e lo schema devono essere predisposti prima dell’avvio: l’archivio include solo migrazioni incrementali, non una definizione iniziale completa del database né dati di esempio. Non contiene credenziali o dati personali del database dello sviluppatore.
