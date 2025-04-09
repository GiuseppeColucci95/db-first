## Traccia
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
-come visto in classe fai un file readme.md
-inserisci nome della tabella,
-inserisci le colonne per definire il modello
-assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
PUSHA 

## Table name: `cars`

## Table columns:

- id: BIGINT() - PRIMARY KEY - AUTO_INCREMENT - NOT NULL
- brand: VARCHAR(30) - NOT NULL
- model: VARCHAR(255) - NOT NULL
- chassis: CHAR(17) - NULL - UNIQUE
- year: YEAR() - NOT NULL
- condition: VARCHAR(30) - NOT NULL
- price: DECIMAL(10,2) - NOT NULL
- color: VARCHAR(20) - NULL
- km: INT() - NOT NULL
- kW: SMALLINT() - NULL
- gear_shift: VARCHAR(15) - NOT NULL
- num_seats: TINYINT() - DEFAULT(2)
- num_doors: TINYINT() - DEFAULT(3)
- fuel: VARCHAR(50) - NOT NULL
- cv: SMALLINT() - NULL
- image: VARCHAR(255) - NULL
- is_available: TINYINT() - DEAFULT(0)
- note: TEXT() - NULL
