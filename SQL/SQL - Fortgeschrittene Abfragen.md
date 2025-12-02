---
tags:
  - it
  - sql
  - expert
---
*Erweiterte Konzepte für komplexe Abfragen und Mengenoperationen.*

***
### Mengenoperationen (UNION)
Kombiniert die Ergebnisse von zwei SELECT-Abfragen.
- **UNION:** Entfernt Duplicate automatisch.
- **UNION ALL:** Behält Duplikate bei.
- *Voraussetzung:* Gleiche Anzahl an Spalten und kompatiblen Datentypen.
### Unterabfragen & Operatoren
- **EXISTS:** Prüft, ob eine Unterabfrage Ergebnisse liefert (Wahr/Falsch).
- **ANY:** Bedingung muss für *mindestens einen* Wert der Unterabfrage gelten.
- **ALL:** Bedingung muss für *alle* Werte der Unterabfrage gelten.