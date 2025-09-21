# Projekt-Fortsetzung Template

## ⚠️ KRITISCHE CHECKS VOR START:

### 1. Baseline etablieren
- [ ] Vorherige Version dokumentiert?
- [ ] Feature-Liste aus v(n-1) vorhanden?
- [ ] Requirements-Tracking-Matrix angelegt?

### 2. Mock-up Level definieren
- [ ] Level 1-4 festgelegt und kommuniziert
- [ ] Erwartungshaltung geklärt

### 3. Regression Guard aktivieren
```python
# Pseudo-Code für mentales Modell
if feature_existed_in_previous_version:
    assert feature_must_exist_in_new_version
    # NIE entfernen ohne explizite Anweisung
```

### 4. Datenquellen-Priorität
1. Audio-Transkript (User) = Wahrheit
2. Business Analyst Report = Strukturiert
3. Mock-up = Kann unvollständig sein

## PROMPT-TEMPLATE:
```
# [Projektname] - Fortsetzung v[X.Y]

## KONTEXT:
- Vorherige Version: v[X.Y-1]
- Mock-up Level: [1-4]
- Letzte Chat-ID: [ID]

## BASELINE-FEATURES (aus v[X.Y-1]):
□ [Feature 1]
□ [Feature 2]
□ [...]

## NEUE ANFORDERUNGEN:
- [Neue Features...]

## KRITISCHE REGELN:
1. ALLE Baseline-Features MÜSSEN erhalten bleiben
2. Mock-up Level [X] bedeutet: [Spezifische Erwartung]
3. Bei Konflikten: Audio-Transkript > Dokumentation
```