---
tags:
  - it
  - sql
  - datenbanken
---
*Die Data Manipulation Language (DML) wird genutzt, um Daten zu erstellen, zu ändern oder zu löschen.*

***
### 1. Daten einfügen (INSERT)
Fügt neue Zeilen in eine Tabelle ein.

```sql
INSERT INTO tabelle (spalte1, spalte2)
VALUES ('Wert1', 'Wert2');
```

### 2. Daten ändern (UPDATE)
Aktualisiert bestehende Datensätze. **Wichtig:** Immer eine `WHERE`-Bedingung nutzen, sonst werden alle Zeilen geändert!

```sql
UPDATE
SET spalte = 'Neuer Wert'
WHERE id = 5;
```
### 3. Daten Löschen (DELETE)
Löscht Zeilen aus einer Tabelle. **Wichtig:** Auch hier `WHERE` nicht vergessen!

```sql
DELETE FROM tabelle
WHERE bedingung;
```

