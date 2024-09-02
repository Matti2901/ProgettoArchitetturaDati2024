# ProgettoArchitetturaDati2024

Questo repository contiene due implementazioni di **Cassandra** e **Elastic Search** per analizzare le performance dei loro indici.

## Istruzioni per l'Esecuzione

1. **Scarica Docker**:
   - Visita il sito ufficiale di Docker e segui le istruzioni per scaricare e installare Docker: [Docker Download](https://www.docker.com/products/docker-desktop).

2. **Scarica la Cartella di Cassandra o Elastic Search**:
   - Scarica la cartella corrispondente alla tua scelta (Cassandra o Elastic Search) dal repository.

3. **Avvia il Cluster**:
   - Vai nella cartella in cui hai salvato il file `docker-compose.yml`.
   - Apri un terminale e naviga nella directory del file `docker-compose.yml`.
   - Esegui il comando:
     ```bash
     docker-compose up -d
     ```
     Questo avvierà i container in background.

4. **Apri Jupyter Notebook**:
   - Una volta che i container sono attivi, apri il tuo browser e vai all'indirizzo:
     [http://localhost:8888/](http://localhost:8888/)
   
5. **Inserisci il Token**:
   - Quando richiesto, inserisci il token di accesso per accedere a Jupyter Notebook. (Il token può essere trovato nei log del container o nella documentazione del progetto.)

6. **Esegui il Programma**:
   - All'interno di Jupyter Notebook, esegui i notebook o i file Python inclusi per analizzare le performance e testare le implementazioni.

## Autori

Questo progetto è stato realizzato da:

- **Oscar Sacilotto**
- **Mattia Milanese**
