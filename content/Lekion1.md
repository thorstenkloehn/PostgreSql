---
title: "Lekion 1"
date: 2023-10-23T12:24:07+02:00
draft: false
type: "page"
menu: 
  main:
    name: "Lekion 1"
    weight: 2
    
---

# Lekion 1
## Daten abfragen
```sql
SELECT*FROM Tabellename; //  alle Spalten ausgeben
```
## Daten abfragen filtern
```sql
SELECT*FROM Tabellename WHERE Bedingung; //  alle Spalten ausgeben Daten filtern
```
## Spalten ausgeben
```sql
SELECT Spaltenname FROM Tabellename; //  Spalten ausgeben
```
## Spalten ausgeben filtern
```sql
SELECT Spaltenname FROM Tabellename WHERE Bedingung; //  Spalten ausgeben Daten filtern
```
## PostgreSQL-Vergleichsoperatoren
```sql
Wert!=Wert; // ungleich
Wert<>Wert; //  ungleich
Wert=Wert; //  gleich
Wert>Wert; //  größer
Wert<Wert; //  kleiner
Wert>=Wert; //  größer gleich
Wert<=Wert; //  kleiner gleich
```
## Operator PostgreSql logik

```sql
Wert AND Wert; //  und
Wert OR Wert; //  oder
Wert NOT Wert; //  nicht
```
### Rechenoperatoren PostgreSql
```sql
Wert+Wert; //  Plus
Wert-Wert; //  Minus
Wert*Wert; //  Mal
Wert/Wert; //  Geteilt
Wert%Wert; //  Modulo
```

## Anzahl der Datensätze ausgeben
```sql

SELECT COUNT(*) FROM Tabellename; //  Anzahl der Datensätze ausgeben
```
## Anzahl der Datensätze ausgeben filtern
```sql
SELECT COUNT(*) FROM Tabellename WHERE Bedingung; //  Anzahl der Datensätze ausgeben Daten filtern
```
## Spalten ausgeben ohne doppelte Datensätze
```sql
SELECT DISTINCT Spaltenname FROM Tabellename //  Spalten ausgeben ohne doppelte Datensätze
```
## Anzahl der Datensätze ausgeben ohne doppelte Datensätze
```sql
SELECT COUT(DISTINCT Spaltenname) FROM Tabellename //  Anzahl der Datensätze ausgeben ohne doppelte Datensätze
```
## Daten sortieren mit wie Muster-Operator

```sql
SELECT*FROM Tabellename WHERE Spaltenname LIKE Bedingung; // Daten sortieren mit wie Muster-Operator
```
## Daten sortieren mit wie Muster-Operator
Muster-Operator Befehle aufgelistet
* % //  beliebig viele Zeichen
* _ //  ein Zeichen







