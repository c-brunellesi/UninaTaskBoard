# UninaTaskBoard

Applicazione desktop Java Swing per organizzare progetti collaborativi e attività universitarie.

## Codice sorgente

Il progetto completo, inclusi sorgenti Java, logo, documentazione, librerie e migrazioni SQL, è disponibile in [UninaTaskBoard_sorgenti.zip](UninaTaskBoard_sorgenti.zip). L’archivio esclude i file compilati.

## Avvio

Richiede Java 21, PostgreSQL ed Eclipse o un ambiente Java compatibile. In Eclipse importare la cartella UninaTaskBoard estratta dall’archivio e avviare UninaTaskBoard_Launcher.MainUTB. Le librerie necessarie sono incluse in lib.

## Database

La connessione usa il database locale UninaTaskBoard e l’utente postgres. La password viene letta dalla variabile d’ambiente DB_PASSWORD. In Eclipse configurarla in Run Configurations → MainUTB → Environment. Il database deve essere predisposto localmente con lo schema richiesto; gli script in sql/migrations sono migrazioni incrementali.
