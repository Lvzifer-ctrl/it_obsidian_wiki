---
tags:
  - it
  - sql
  - datenbanken
---
*Die Data Query Language (DQL) dient dazu, Daten aus einer Datenbank abzufragen und zu filtern.*

***
### Der SELECT-Befehl
Der Grundbaustein jeder Abfrage:

```sql
SELECT spalte1, spalte2 FROM tabelle;
```

- Alles auswählen: `SELECT * FROM tabelle;` 
- Duplikate vermeiden: `SELECT DISTINCT spalte FROM tabelle;`
### Filtern mit WHERE
Daten können gezielt eingeschränkt werden:

```sql
SELECT * FROM kunden WHERE ort = 'BELIN';
```

- **Mustervergleich (LIKE):**
	- `%` = beliebig viele Zeichen (z. B. `'A%'` für alles, was bit A beginnt)
	- `_` = genau ein Zeichen (z. B. `'H_us'`)
### Sortierung (ORDER BY)
```sql
SELECT * FROM produkte ORDER BY preis ASC;
```

- **ASC:** Aufsteigend (Standard)
- **DESC:** Absteigend