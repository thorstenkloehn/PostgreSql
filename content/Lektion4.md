---
title: "Lektion 4"
date: 2023-11-01T22:54:47+01:00
draft: false
type: "page"
menu: 
  main:
    name: "Lektion 4"
    weight: 5
    
---

# Lektion 4
## Subselects
```sql
SELECT Spaltenname FROM Tabellename WHERE Spaltenname=(SELECT Spaltenname FROM Tabellename WHERE Spaltenname='Wert'); // Subselects
```


