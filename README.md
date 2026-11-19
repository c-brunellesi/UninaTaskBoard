# UninaTaskBoard

Applicazione desktop Java Swing per organizzare progetti collaborativi e attività universitarie.

## Codice sorgente

Scarica il pacchetto aggiornato con sorgenti Java, logo, librerie, documentazione, migrazioni SQL e avviatore macOS: [UninaTaskBoard_sorgenti_aggiornati.zip](UninaTaskBoard_sorgenti_aggiornati.zip).

## Avvio

Richiede Java 21, PostgreSQL ed Eclipse o un ambiente Java compatibile. In Eclipse importa la cartella `UninaTaskBoard` estratta dallo ZIP e avvia `UninaTaskBoard_Launcher.MainUTB`. Le librerie JDBC PostgreSQL e JFreeChart sono incluse nella cartella `lib`. Su macOS puoi avviare `Avvia UninaTaskBoard.command`; lo script ricompila e chiede localmente la password PostgreSQL senza salvarla.

## Database

La connessione usa il database PostgreSQL locale `UninaTaskBoard`, porta `5432`, utente `postgres`. La password si configura come variabile `DB_PASSWORD` nell’ambiente di esecuzione Java. Il database e lo schema devono essere predisposti prima dell’avvio: questo archivio include solo migrazioni incrementali, non una definizione iniziale completa del database né dati di esempio. Non contiene credenziali o dati personali del database dello sviluppatore.
