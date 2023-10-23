---
title: "Installationsanleitung"
date: 2023-10-23T02:05:57+02:00
draft: false
type: "page"
menu: 
  main:
    name: "Installationsanleitung"
    weight: 1
    
---
# Installieren von PostgeSql auf Ubuntu

```bash
sudo apt-get update //aktualisiert die Paketlisten
sudo apt-get upgrade //aktualisiert die Pakete
sudo apt-get install postgresql-all //installiert postgresql
```
## Neue Ubuntu Nutzer erstellen mit Admin Rechten

```bash
sudo adduser Nutername //erstellt einen neuen Nutzer
sudo usermod -aG sudo thorsten //fügt den Nutzer zur Gruppe Admin hinzu
```
## Benutzer Nutzername zu Gruppe postgres hinzufügen
  
  ```bash
sudo -u postgres -i  //wechselt zum postgres Nutzer
createuser Nutzername //erstellt einen neuen Nutzer
  ```
## Datenbank erstellen
  
  ```bash
createdb -E UTF8 -O Nutzername Datenbankname //erstellt eine Datenbank und weist sie dem Nutzer zu
  ```

