# Claude-spezifische Implementation

## 🧠 Claude-Rollen-Spezialisierung (Bewährt aus Praxis)

### Claude Sonnet (Struktur & Coordination)
- **Requirements Engineering**: User Stories, NFRs, Validierung
- **System Architecture**: Tech-Stack-Entscheidungen, Design-Patterns
- **Project Management**: Phase-Koordination, Status-Updates
- **Documentation**: Repository-Maintenance, Handover-Dokumente
- **Quality Assurance**: Code-Review, Testing, Standards-Compliance

### Claude Opus (Kreativität & Implementation)
- **Domain Expertise**: Fachberatung für spezifische Anwendungsgebiete
- **Creative Problem-Solving**: Innovative Lösungsansätze, UX-Design
- **Code Development**: Implementation, Integration, Testing
- **User Experience**: Interface-Design, Usability-Optimization
- **Innovation**: Neue Patterns und Ansätze entwickeln

## 🔄 Context Window Management (Claude-spezifisch)

### Multi-Chat-Strategien
**Standard-Ansatz: 3-Chat Strategie**
- **Chat 1**: Phase -1, 0, 1 (Setup + Domain) - Opus für Kreativität
- **Chat 2**: Phase 2, 3 (Requirements + Architektur) - Sonnet für Struktur
- **Chat 3**: Phase 4, 5 (Implementation + Testing) - Opus + Sonnet Kollaboration

**Alternative: 5-Chat für maximale Kontrolle**
- Chat 1: Phase -1, 0 (Setup + Kickoff)
- Chat 2: Phase 1 (Domain-Expertise)
- Chat 3: Phase 2 (Requirements)
- Chat 4: Phase 3 (Architektur)
- Chat 5: Phase 4, 5 (Implementation + Testing)

**GitHub-gesteuerte DevOps-Instanzen**
- Universal-Prompt für jeden Chat mit GitHub-Status-Check
- Automatisches Phasen-Marking nach Abschluss
- Framework-Phase-Details aus Repository abrufen

## 🎯 Phasen-spezifische Interaktions-Präferenzen

### Phase 0-2: Kreative Unterstützung
- **User-Rolle**: Fokussiert bleiben bei Anwendungs-Beschreibung
- **Claude-Rolle**: Kreativ unterstützend, Anwendungskontext erweitern
- **Grenzen**: Nicht überdenken mit zu frühen Fachexperten-Einsätzen
- **Sonnet vs. Opus**: Opus bevorzugt für kreative Phasen

### Phase 3-5: Strikt arbeiten
- **User-Rolle**: Klare Vorgaben und Abnahme-Kriterien
- **Claude-Rolle**: Keine Kreativität, nur solide technische Umsetzung
- **Focus**: Funktionalität und Qualität vor Innovation
- **Sonnet vs. Opus**: Sonnet für Struktur, Opus für Implementation

## 📋 Claude-spezifische Handover-Templates

### Sonnet → Opus Handover
```markdown
# Sonnet → Opus Handover - Phase [X]

## Structural Analysis Complete
**Requirements**: [Link zu Requirements-Dokument im Repository]
**Architecture**: [Entscheidungen und Begründungen]
**Constraints**: [Technische und Business-Einschränkungen]
**Repository-Status**: [Branch, Commit-Hash, Phase-Marker]

## Creative Brief für Opus
**Innovation-Potentiale**: [Bereiche für kreative Lösungen]
**UX-Fokus**: [User Experience Prioritäten]
**Implementation-Freiheiten**: [Wo Kreativität erwünscht ist]
**Technical-Boundaries**: [Was nicht verändert werden soll]

## Context-Transfer
**GitHub-Repository**: [Direkter Link mit Branch/Commit]
**Phase-Status**: Abgeschlossen - Ready for creative implementation
**Next-Steps**: [Konkrete nächste Aufgaben für Opus]
**Quality-Criteria**: [Was beachtet werden muss]
**Handover-Verification**: [Checkpunkte für erfolgreiche Übergabe]
```

### Opus → Sonnet Handover
```markdown
# Opus → Sonnet Handover - Phase [X]

## Creative Solutions Developed
**Innovative Ansätze**: [Beschreibung kreativer Lösungen]
**Prototypes**: [Links zu Code/Mockups im Repository]
**UX-Decisions**: [Interface und Experience Entscheidungen]
**Technical-Innovations**: [Neue Patterns oder Ansätze]
**Repository-Updates**: [Was committed wurde]

## Review-Request für Sonnet
**Quality-Check**: [Was strukturell geprüft werden soll]
**Code-Review**: [Performance, Standards, Best-Practices]
**Optimization**: [Bereiche für Verbesserung]
**Documentation**: [Was noch dokumentiert werden muss]
**Standards-Compliance**: [Framework-Konformität prüfen]

## Implementation-Details
**Code-Struktur**: [Architektur-Overview]
**Dependencies**: [Verwendete Libraries/APIs]
**Testing-Status**: [Was getestet, was noch offen]
**Deployment-Ready**: [Status für Production-Einsatz]
**Repository-Health**: [Commit-Status, Documentation-Coverage]
```

## 🛡️ Mathematische Validierung für Fachsoftware

### 3-Stufen-Validierung (Claude-optimiert)
1. **Claude-Formel-Verification**: KI prüft mathematische Korrektheit gegen Referenzen
2. **Range-Checking**: Realistische Min/Max-Werte für Parameter definieren
3. **Cross-Validation**: Multiple Berechnungswege für kritische Werte implementieren
4. **Reference-Check**: Abgleich mit Fachquellen und Standards dokumentieren

### Haftungsausschluss-Integration (Standard für Fachsoftware)
```markdown
## Automatischer Haftungsausschluss für Fachsoftware
"Diese Software stellt Berechnungshilfen zur Verfügung.
Vor produktivem Einsatz müssen alle Ergebnisse durch
qualifiziertes Fachpersonal validiert werden.
Keine Haftung für Schäden durch fehlerhafte Berechnungen,
Implementierungsfehler oder unsachgemäße Verwendung."
```

### Warning-System für kritische Parameter
```javascript
// Beispiel für automatische Warnungen bei gefährlichen Werten
function validateParameter(value, min, max, paramName) {
    if (value < min || value > max) {
        console.warn(`⚠️  WARNUNG: ${paramName} = ${value} außerhalb sicherer Grenzen [${min}, ${max}]`);
        return {valid: false, warning: `Parameter außerhalb Sicherheitsbereich`};
    }
    return {valid: true, warning: null};
}
```

## 🎯 Claude-spezifische Prompt-Optimierungen

### Universal Session Starter (Claude)
```markdown
## Claude Meta-AI Framework Session
**Framework**: Meta AI Development Framework v1.0 by Volker Hochgürtel
**Model**: Claude Sonnet 4 / Claude Opus 4
**Repository**: https://github.com/VoHoch/[projektname]-VH-1.0
**Meta-Profile**: https://github.com/VoHoch/meta-ai-interaction-profile

**Current Phase**: [Phase Number] von 7
**Previous Phases**: [Liste abgeschlossener Phasen]
**Model Role**: [Sonnet: Struktur/Analyse | Opus: Kreativität/Implementation]

**Task**: Execute Phase [N] according to framework specifications
**Context**: Read complete GitHub repository status before starting
**Output**: All deliverables committed to repository with proper documentation
**Handover**: Prepare structured handover for next phase/model if applicable

**Quality Standards**: Enterprise-quality for SME applications
**Interaction Style**: [Creative Support Phase 0-2 | Strict Execution Phase 3-5]
```

## 🚫 Claude Anti-Patterns (aus Session-Erfahrung dokumentiert)

### Information-Gathering Anti-Patterns
```
❌ CLAUDE ANTI-PATTERN 1: Vorzeitige Antworten ohne vollständige Informationen
   Beispiel: Framework erstellen ohne systematische Fragelisten-Bearbeitung
   Lösung: Immer vollständigkeits-Check vor Antwort-Generierung

❌ CLAUDE ANTI-PATTERN 2: Annahmen über User-Prioritäten ohne Rückfrage
   Beispiel: CNC-spezifische Optimierung statt application-agnostic Framework
   Lösung: User-Präferenzen explizit abfragen, nicht vermuten

❌ CLAUDE ANTI-PATTERN 3: Strukturierte User-Prozesse überspringen
   Beispiel: Frageliste überspringen und direkt "loslegen"
   Lösung: User-Prozesse respektieren und systematisch befolgen

❌ CLAUDE ANTI-PATTERN 4: Erarbeitete Informationen beim Umstrukturieren wegwerfen
   Beispiel: Claude-spezifische Details beim "Universal AI"-Umbau verlieren
   Lösung: Information-Preservation - alle Details in entsprechende Abschnitte verschieben

❌ CLAUDE ANTI-PATTERN 5: Dateinamen-Inkonsistenzen
   Beispiel: Unterstriche vs. Bindestriche vs. Leerzeichen chaotisch mischen
   Lösung: Konsistente Naming-Convention durchgehend anwenden
```

### Success Patterns (bewährt aus Praxis)
```
✅ CLAUDE SUCCESS-PATTERN 1: Systematische Fragelisten vor Lösungsentwicklung
✅ CLAUDE SUCCESS-PATTERN 2: Repository-basierte Dokumentation für Persistenz
✅ CLAUDE SUCCESS-PATTERN 3: Meta-Level Reflexion über Interaktionsprozesse
✅ CLAUDE SUCCESS-PATTERN 4: Information-Preservation beim Framework-Umbau
✅ CLAUDE SUCCESS-PATTERN 5: Strukturierte Handover-Prozesse zwischen Sessions
```

## 📐 Claude-spezifische Interaktions-Regeln

```markdown
CLAUDE-REGEL 1: Context-Window-Bewusstsein
- Bei Chat-Wechsel: Vollständige Repository-Lektüre vor Start
- Sonnet/Opus Rollenklarheit explizit vor Phase-Beginn deklarieren
- Handover-Dokumente als primäre Context-Quelle nutzen

CLAUDE-REGEL 2: Multi-Model-Koordination
- Sonnet für Struktur und Analyse, Opus für Kreativität und Innovation
- Explizite Rollen-Deklaration in jeder Session
- Handover-Qualität zwischen Models durch Templates sicherstellen

CLAUDE-REGEL 3: Repository-Integration
- Jede Phase vollständig dokumentiert committen
- GitHub-Status als Single Source of Truth behandeln
- Phase-Marker für Context-Continuation setzen
- Alle Artefakte versioniert im Repository ablegen

CLAUDE-REGEL 4: Qualitäts-Sicherstellung
- Enterprise-Standards auch für SME-Anwendungen anwenden
- Mathematische Validierung bei Fachsoftware implementieren
- Code-Review und Testing in Implementation-Phase integrieren
- User-Acceptance-Tests vor Projektabschluss durchführen
```