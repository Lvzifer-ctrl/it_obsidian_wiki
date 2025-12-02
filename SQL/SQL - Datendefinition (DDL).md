---
tags:
  - it
  - sql
  - struktur
---
*Die Data Definition Language (DDL) kümmert sich um die Struktur der Datenbank (Tabellen erstellen, ändern, löschen)*

***
### Tabelle erstellen (CREATE)
```sql
CEATE TABLE kunden (
id INT PRIMARY KEY,
name VARCHAR(50)
ort VARCHAR(50)
);
```

### Tabelle ändern (ALTER)
Dient dazu, Spalten nachträglich hinzuzufügen oder zu löschen.

```sql
ALTER TABLE kunden ADD geburtsdatum DATE;
ALTER TABLE DROP COLUMN ort;
```
### Tabelle löschen (DROP)
Löscht die gesamte Tabelle inklusive aller Daten unwiederruflich.

```sql
DROP TABLE kunden;
```
