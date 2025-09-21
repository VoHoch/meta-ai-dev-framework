# Qualitätssicherung bei iterativer Entwicklung

## Goldene Regel: Additives Prinzip
**NIEMALS Features verlieren - nur hinzufügen oder verbessern**

## Requirements-Tracking-Matrix (Pflicht ab v2)
| Feature-ID | Beschreibung | v1 | v2 | v3 | Test | Sign-off |
|------------|--------------|----|----|-------|------|----------|
| REQ-001    | [Feature]    | ✓  | ✓  | ✓    | [ ]  | [ ]      |

## Mock-up Level-System
- **Level 1:** Statisches Layout (nur visuell)
- **Level 2:** Klickbare Navigation (keine Logik)
- **Level 3:** Berechnungslogik aktiv (Prototyp)
- **Level 4:** Produktionsreifer Code

**REGEL:** Bei jedem Mock-up IMMER Level deklarieren!

## Regression-Checklist
Vor jeder neuen Version:
- [ ] Feature-Matrix aus v(n-1) vollständig übernommen?
- [ ] Alle neuen Features additiv hinzugefügt?
- [ ] Gegen Original-Requirements getestet?
- [ ] Expertenwissen in Code UND Doku integriert?
- [ ] Audio-Transkript bei Konflikten priorisiert?

## Expertenrunden-Integration
### Output-Anforderungen:
- Konkrete Werte/Formeln (keine Prosa)
- Direkt umsetzbare Grenzwerte
- Beispiel RICHTIG: "L/D > 5 = ROT"
- Beispiel FALSCH: "zu lang ist problematisch"

### Integration in:
1. Plausibilitätschecks (Code)
2. Wissensdatenbank (UI)
3. Dokumentation (Markdown)