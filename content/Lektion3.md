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

