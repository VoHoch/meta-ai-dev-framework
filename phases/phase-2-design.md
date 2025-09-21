# Phase 2: Design

## Design Patterns

## Iterative Verbesserung

### Anti-Pattern: Feature-Verlust
**Problem:** Features verschwinden zwischen Versionen
**Lösung:** Requirements-Tracking-Matrix verwenden

### Best Practice: Expertenrunden
**Format für Expertenwissen:**
- Konkrete Werte mit Einheiten
- Klare Grenzwerte (z.B. "< 3 grün, 3-4 gelb, > 4 rot")
- Formeln explizit (z.B. "T = 0.0000992 × rpm")
- In Code UND UI-Tooltips integrieren

### Mock-up Klarheit
IMMER angeben:
```javascript
// Mock-up Level: 3 (Funktionale Berechnungen)
// Erwartung: Alle Buttons klickbar, Berechnungen funktionieren
// Nicht implementiert: Datenpersistenz, API-Calls
```