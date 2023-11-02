---
title: "Lektion 3"
date: 2023-10-30T02:27:26+01:00
draft: false
type: "page"
menu: 
  main:
    name: "Lektion 3"
    weight: 4
    
---

Lektion 3
## PostgreSQL TEXT Datentyp
  ```sql
    Spaltenname TEXT // Dokumente, Texte, usw.
    Spaltenname VARCHAR(255) //  variable Länge mit Begrenzung mit 255 Zeichen
    Spaltenname CHAR(255) // feste Länge mit Begrenzung mit 255 Zeichen

  ```

## PostgreSQL Tabelle entfernen
  ```sql
    DROP TABLE Tabellename; // Tabelle entfernen
  ```
## PostgreSQL Spalte hinzufügen
  ```sql
    ALTER TABLE Tabellename ADD Spaltenname Datentyp; // Spalte hinzufügen
  ```
## PostgreSQL Spalte entfernen
  ```sql
    ALTER TABLE Tabellename DROP COLUMN Spaltenname; // Spalte entfernen
  ```
## PostgreSQL Spalte umbenennen
  ```sql
    ALTER TABLE Tabellename RENAME COLUMN Spaltenname TO Spaltenname; // Spalte umbenennen
  ```
## PostgreSql Ganzahlige Datentypen
```SQL
    Spaltenname SMALLINT // 2 Bytes 
    Spaltenname INTEGER // 4 Bytes 
    Spaltenname BIGINT // 8 Bytes
```

## PostgreSQL Gleitkommazahlen
  ```sql
    Spaltenname REAL // 4 Bytes
    Spaltenname DOUBLE PRECISION // 8 Bytes
  ```
## PosttreSql Ausgeben Gleitkommazahlen
  ```sql
    Spaltenname DECIMAL(2,2) // 2 Stellen vor dem Komma und 2 Stellen nach dem Komma
  ```
## PostgreSql Null Wert
  ```sql
    Spaltenname Datentyp NULL // NULL Werte
    Spaltenname Datentyp NOT NULL // keine NULL Werte
  ```
  ## PostgreSql NULL Werte einfügen
  ```sql
  INSERT INTO Tabellename (Spaltenname) VALUES (NULL); // NULL Werte einfügen
  ```
  ## PostgreSql NULL Wert Aktualisieren
  ```sql
  UPDATE Tabellename SET Spaltenname = NULL WHERE Bedingung; // NULL Wert aktualisieren
  ```
  ## PostgreSql NULL Wert entfernen
  ```sql
  UPDATE Tabellename SET Spaltenname = Wert WHERE Bedingung; // NULL Wert entfernen
  ```
  ## PostgreSql Standardwert in Tabellen erstellen
  ```sql
  Spaltenname Datentyp DEFAULT Wert // Standardwert in Tabellen erstellen
  ```
  ## PostgreSql Standardwert in Tabellen einfügen
  ```sql
  INSERT INTO Tabellename (Spaltenname) VALUES (DEFAULT); // Standardwert in Tabellen einfügen
  ```
  ## PostgreSql Standardwert in Tabellen aktualisieren
  ```sql
  UPDATE Tabellename SET Spaltenname=DEFAULT WHERE Bedingung; // Standardwert in Tabellen aktualisieren
  ```
  ## PostgreSql Standardwert in Tabellen entfernen
  ```sql
  ALTER TABLE Tabellename ALTER COLUMN Spaltenname DROP DEFAULT; // Standardwert in Tabellen entfernen
  ```
  ## PostgreSql Primärschlüssel in Tabellen erstellen
  ```sql
  Spaltenname SMALLSERIAL PRIMARY KEY //  Primärschlüssel in Tabellen erstellen HINWEIS:   Alias für SMALLINT PRIMARY KEY
  Spaltenname SERIAL PRIMARY KEY //  Primärschlüssel in Tabellen erstellen HINWEIS:  Alias für INTEGER PRIMARY KEY
  Spaltenname BIGSERIAL PRIMARY KEY //  Primärschlüssel in Tabellen erstellen HINWEIS Alias für BIGINT PRIMARY KEY
  ```
  
  






  





