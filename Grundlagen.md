# MySQL Grundlagen
## Datentypen
- INTEGER, BIGINT, SMALLINT -> Ganzzahl
- NUMERIC, DECIMAL, NUMBER (n,m) -> Festkomma
- FLOAT, DOUBLE -> Gleitkomma
- DATE, TIME, TIMESTAMP
- CHAR (n)
- SET, ENUM -> Listen
## Schlüsselwörter
- BINARY speichert Text als Binärdatei
- UNSIGNED ohne Vorzeichen
- ZEROFILL füllt links mit 0 auf (impliziert UNSIGNED)
- NULL/NOTNULL bestimmt, ob Feld leer sein darf
- DEFAULT setzt Standardwert
- AUTO_INCREMENT erstellt fortlaufende Werte
- PRIMARY KEY nutzt Feld als Primärschlüssel
-- zusammengesetzter PK mit PRIMARY KEY(Feld1, Feld2)
## Tabellen erstellen
CREATE DATABASE
CREATE TABLE
