---
tags:
  - it
  - sql
  - joins
---
*Joins verbinden Daten aus zwei oder mehr Tabellen miteinander, basierend auf einer gemeinsamen Spalte (meist ID)*

***
### Join-Arten
1. **INNER JOIN:** Zeigt nur Datensätze, die in *beiden* Tabellen eine Übereinstimmung haben.
2. **LEFT JOIN:** Zeigt *alle* Datensätze aus der *linken* Tabelle und die passenden aus der rechten (sonst NULL)
3. **RIGHT JOIN:** Zeigt *alle* Datensätze aus der *rechten* Tabelle.
4. **FULL JOIN:** Zeigt Datensätze, wenn es in *einer* der beiden Tabellen eine Übereinstimmung gibt (Kombination aus Left und Right)
### Beispiel
```sql
SELECT kunden.namen, bestellungen.datum
FROM kunden
INNER JOIN bestellungen ON kunden.id = bestellungen.kunden_id;
```
