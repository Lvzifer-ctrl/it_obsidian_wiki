---
tags:
  - it
  - sql
  - analyse
---
*Aggregatfunktionen fassen mehrere Werte zu einem einzigen Ergebnis zusammen (z. B. Summen oder Durchschnitte).*

***
### Die wichtigsten Funktionen
#### COUNT()
- Zählt die Anzahl der Datensätze
- `SELECT COUNT(*) FROM bestellungen;
#### SUM()
- Bildet die Summe einer Spalte
- `SELECT SUM(preis) FROM rechnungen;`
#### AVG()
- Berechnet den Durchschnitt
#### MIN() / MAX()
- Ermittelt den kleinsten bzw. den größten Wert.
#### Gruppierung (GROUP BY)
Aggregatfunktionen werden oft mit Gruppierungen kombiniert.
*Beispiel: Anzahl der Kunden pro Stadt*

```sql
SELECT stadt, COUNT(*)
FROM kunden
GROUP BY stadt;
```
