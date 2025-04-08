<!-- 
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
-come visto in classe fai un file readme.md
-inserisci nome della tabella,
-inserisci le colonne per definire il modello
-assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
PUSHA -->

## Table name: `cars`

## Table columns:

- id: BIGINT() - PRIMARY KEY - AUTO_INCREMENT - NOT NULL
- make: VARCHAR(20) - NOT NULL
- model: VARCHAR(255) - NOT NULL
- year: YEAR() - NOT NULL
- price: FLOAT(10,2) - NOT NULL
- km: INT() - NOT NULL
- kW: SMALLINT() - NULL
- gear_shift: VARCHAR(15) - NULL
- cv: SMALLINT() - NULL
- note: TEXT() - NULL
