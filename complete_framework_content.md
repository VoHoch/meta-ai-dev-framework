# CLAUDE CODE INSTRUCTIONS: Complete Framework Repository Population

## TASK
Read this file and populate the meta-ai-dev-framework repository with all specified content. Overwrite existing files and create missing files as specified.

## REPOSITORY: meta-ai-dev-framework

### README.md (OVERWRITE)
```markdown
# Meta AI Development Framework v1.0

Ein strukturiertes Framework für professionelle Software-Entwicklung mit KI-Systemen.

## 🎯 Zweck
- **Strukturierte KI-Projekte** statt chaotische Chat-Sessions
- **Repository-basierte Dokumentation** mit versionierter Nachverfolgung  
- **7-Phasen-Modell** von Konzept bis produktionsreifer Web-App
- **Praxistauglich** für Heim-/KMU-Anwendungen

## ✅ Framework-Eigenschaften
- **KI-Agnostic**: Für Claude/ChatGPT/Gemini verwendbar
- **Context-Window-Management**: Multi-Chat-Strategien mit nahtlosen Übergaben
- **Quality Gates**: Mathematische Validierung für Fachsoftware
- **GitHub-Integration**: Copy-Pattern für neue Projekt-Instanzen
- **Template Repository**: "Use this template" für neue Projekte

## 🚀 Quick-Start
1. **"Use this template"** für neues Projekt
2. **Repository benennen**: `[projektname]-VH-1.0`
3. **KI-System wählen**: Claude/ChatGPT/Gemini aus `/ai-specific/`
4. **7-Phasen-Modell** systematisch durcharbeiten

## 📁 Repository-Struktur
```
meta-ai-dev-framework/
├── framework-overview.md           # Komplettes 7-Phasen-Modell
├── github-integration.md          # Repository-Patterns & Workflows
├── quality-framework.md           # Testing & Validation
├── naming-conventions.md          # Projekt-Naming-Standards
├── project-templates/             # Templates für neue Projekte
│   ├── project-template/          # Basis-Projektstruktur
│   └── phase-templates/           # Phasen-spezifische Templates
└── ai-specific/                   # KI-spezifische Implementierungen
    ├── claude-implementation.md   # Claude Sonnet/Opus Details
    ├── chatgpt-implementation.md  # ChatGPT Spezifika
    ├── gemini-implementation.md   # Gemini Anpassungen
    └── prompts/                   # Standard-Prompts für alle KI-Systeme
```

## 📊 Version & Meta-Informationen
- **Framework Version**: v1.0
- **Autor**: Volker Hochgürtel
- **Entwickelt**: September 2025
- **Anwendung**: KI-Agnostic Web-App Development
- **Repository-Pattern**: `[projektname]-VH-1.0`

## 🔗 Related Repository
- **Interaktions-Profil**: [meta-ai-interaction-profile](https://github.com/VoHoch/meta-ai-interaction-profile)

**Framework komplett mit allen erarbeiteten Details - bereit für praktischen Einsatz!**
```

### framework-overview.md (CREATE/OVERWRITE)
```markdown
# Universelles 7-Phasen-Modell

## 🎯 Framework-Philosophie

**Grundprinzip**: Robuste Software in iterativen Schritten mit persistenter Dokumentation  
**Ziel**: KI-agnostische Entwicklungsprozesse für Heim-/KMU-Anwendungen mit Enterprise-Qualität  
**Reality Check**: KI unterstützt, Mensch orchestriert, Repository dokumentiert

## 📋 7-Phasen-Modell (Universal mit KI-spezifischen Umsetzungen)

### Phase -1: Repository Setup (15 Min) 
**Input**: Projektidee + Framework-Entscheidung  
**Output**: GitHub-Repo + KI-Projekt + Dokumenten-Templates  
**Repository**: Initial setup complete

**Checkliste:**
- [ ] Repository mit Naming Convention erstellen (`[projektname]-VH-1.0`)
- [ ] KI-Projekt/Session initialisieren
- [ ] Basis-Dokumentenstruktur committen
- [ ] README mit Projekt-Meta erstellen
- [ ] KI-Session-Linking in Repository dokumentieren

### Phase 0: Kickoff & Grundlagen (30 Min)
**Input**: Ihre Idee + Anwendungsfall  
**Output**: Plattform-Entscheidung + KI-Rollen-Team + erste Use Cases  
**Repository**: `/docs/phase_0_kickoff.md`

**Interaktions-Präferenz**: User fokussiert + KI kreativ unterstützend  
**KI-Aufgabe**: Anwendungskontext erweitern, aber nicht überdenken

**Deliverables:**
- Projektbeschreibung und Vision
- Zielgruppe-Definition  
- Plattform-Entscheidung (Web-App/Desktop/Mobile)
- Erste User Stories
- KI-Rollen-Zuordnung

### Phase 1: Fachexperten-Workshop (45 Min) 
**Input**: Domain-Wissen aktivieren  
**Output**: Requirements + mathematische Grundlagen + Validierungsregeln  
**Repository**: `/docs/phase_1_domain_expertise.md`

**Interaktions-Präferenz**: User fokussiert + KI kreativ unterstützend  
**KI-Aufgabe**: Domain-Expertise bereitstellen, Fachkenntnisse strukturieren

**Deliverables:**
- Fachliche Grundlagen und Terminologie
- Mathematische Formeln und Berechnungen
- Validierungsregeln und Plausibilitätschecks
- Referenz-Quellen und Standards
- Sicherheitsanforderungen

### Phase 2: Business Requirements (60 Min)
**Input**: Fachexperten-Output  
**Output**: User Stories + NFRs + Akzeptanzkriterien  
**Repository**: `/docs/phase_2_business_requirements.md`

**Interaktions-Präferenz**: KI kreativ (Business-Analyse ausbauen)  
**KI-Aufgabe**: Requirements Engineering, User Experience Design

**Deliverables:**
- Vollständige User Stories mit Akzeptanzkriterien
- Non-Functional Requirements (Performance, Security, Usability)
- UI/UX Anforderungen
- Integration-Requirements
- Deployment-Anforderungen

### Phase 3: Architektur + Debug-Konzept (45 Min)
**Input**: Requirements  
**Output**: Tech-Stack + System-Design + Logging-Strategie  
**Repository**: `/docs/phase_3_architecture_spec.md`

**Interaktions-Präferenz**: Strikt arbeiten (keine Kreativität, solide Umsetzung)  
**KI-Aufgabe**: System-Architektur, Tech-Stack-Entscheidungen

**Deliverables:**
- Tech-Stack-Entscheidung mit Begründung
- System-Architektur-Diagramm
- Datenbank-Design (falls erforderlich)
- API-Spezifikation
- Debug- und Logging-Konzept
- Error-Handling-Strategie

### Phase 4: Implementation (90 Min)
**Input**: Architektur-Specs  
**Output**: Vollständige Web-App + Tests  
**Repository**: `/src/` + `/tests/`

**Interaktions-Präferenz**: Strikt arbeiten (nur solide Umsetzung)  
**KI-Aufgabe**: Code Development, Testing, Quality Assurance

**Deliverables:**
- Vollständiger Quellcode
- Unit-Tests für kritische Funktionen
- Integration-Tests
- Dokumentierter Code
- Error-Handling implementiert

### Phase 5: Testing + Handover (30 Min)
**Input**: Implementierung  
**Output**: Test-Reports + User-Guide + Debug-Tools  
**Repository**: `/docs/phase_5_testing_handover.md` + `/releases/`

**Interaktions-Präferenz**: Strikt arbeiten + User-Acceptance  
**KI-Aufgabe**: Quality Assurance, Documentation, Release Preparation

**Deliverables:**
- Test-Reports und Coverage-Analyse
- User-Guide und Dokumentation
- Deployment-Instructions
- Debug-Tools und -Anleitungen
- Release-Notes

**Gesamt**: ~6 Stunden, aufgeteilt auf 3-6 Chats je nach KI-System

## 🛡️ Quality Gates pro Phase

| Phase | Quality Gate | Kriterium | Verantwortlich |
|-------|-------------|-----------|----------------|
| 1 | Domain-Validation | Fachlogik korrekt? | KI Domain-Experte |
| 2 | Requirements-Sign-Off | User Stories vollständig? | Sie |
| 3 | Architecture-Review | Tech-Stack optimal? | KI System-Architekt |
| 4 | Code-Quality | Funktioniert + getestet? | KI Developer |
| 5 | User-Acceptance | Praxistauglich? | Sie |

## 🔄 Standard-Prompt für Phasen-Fortsetzung (Universal)

```markdown
## KI-Development Session
**Meta-Framework**: https://github.com/VoHoch/meta-ai-dev-framework
**Interaction-Profile**: https://github.com/VoHoch/meta-ai-interaction-profile  
**Current KI**: Claude/ChatGPT/Gemini
**Projekt**: https://github.com/VoHoch/[projektname]-VH-1.0
**Abgeschlossen**: Phase X, Y, Z
**Aktuelle Phase**: [N] von 7
**Status-Dokument**: [GitHub-Link zu project_status.md]

**Aufgabe**: Führe Phase [N] durch basierend auf [KI]-spezifischer Implementation aus Meta-Framework.
Alle Outputs in Repository committen.
```

## 🔧 Standard Tech-Stack (Application-Agnostic)

### Default Stack (90% Anwendungen)
- **Frontend**: HTML5 + Vanilla JS (universell, keine Dependencies)
- **Backend**: Python Flask (lokal) oder Client-Side Only
- **Datenbank**: LocalStorage/JSON oder SQLite
- **Deployment**: Single HTML File oder Docker Container

### Alternative Stacks (Projektspezifisch)
- **Math-Heavy**: Python + NumPy + Jupyter Integration
- **Audio/Signal**: Web Audio API + Python Backend
- **3D/Visual**: Three.js + WebGL
- **KI-Native**: Claude/OpenAI API + lokale Fallbacks
- **Desktop**: Electron Wrapper für Cross-Platform

### Tech-Stack Entscheidungsmatrix

| Anwendung | Frontend | Backend | Deployment | Grund |
|-----------|----------|---------|------------|--------|
| Berechnungstools | HTML5/JS | Python | Single File | Mathematische Bibliotheken |
| Visualisierungen | HTML5/JS | Client-Side | Web-Host | Performance + Interaktivität |
| Audio-Tools | HTML5/JS | Python/C++ | Desktop | Real-Time Processing |
| KI-Integration | HTML5/JS | API-Calls | Cloud/Local | Flexibilität |
```

### github-integration.md (CREATE/OVERWRITE)
```markdown
# GitHub-Integration & Repository-Patterns

## 📁 Repository-Architektur (Universal + KI-Spezifisch)

### Meta-Repository-Struktur
```
VoHoch/
├── meta-ai-dev-framework/          # Framework-Templates (Template Repo)
├── meta-ai-interaction-profile/    # Persönliches Interaktions-Profil
├── projekt1-VH-1.0/               # Konkrete Projekt-Instanz
├── projekt2-VH-1.0/               # Weitere Projekt-Instanz
└── ...
```

### Naming Convention (Pflicht)
```
Meta-Framework: meta-ai-dev-framework (Template Repository)
Interaktions-Profil: meta-ai-interaction-profile
Projekt-Repository: [projektname]-VH-[framework-version]
KI-Spezifische Branch: [projektname]-VH-1.0-claude (optional)
```

**Beispiele:**
- `invoice-generator-VH-1.0` (Universal)
- `audio-analyzer-VH-1.0` (Universal)
- `parameter-calculator-VH-1.0-claude` (Claude-spezifische Branch)

### Standard Repository Struktur für Projekte
```
projektname-VH-1.0/
├── README.md (Projekt-Overview)
├── /docs
│   ├── project_status.md (Live-Status)
│   ├── phase_0_kickoff.md
│   ├── phase_1_domain_expertise.md
│   ├── phase_2_business_requirements.md
│   ├── phase_3_architecture_spec.md
│   ├── phase_4_implementation_plan.md
│   └── phase_5_testing_handover.md
├── /src (Code & Artefakte)
├── /tests
├── /assets (Bilder, Mockups)
└── /releases (Tagged Versions)
```

## 🔄 Repository-Update Workflow

### Standard-Commit-Message Format
```bash
feat: Complete Phase [X] - [Kurzbeschreibung]
docs: Update project status - Phase [X] → [Y]  
fix: Correct [Problem] in Phase [X] documentation
refactor: Improve [Komponente] based on [Grund]
release: Version [X.Y] - [Release-Beschreibung]
```

### GitHub-gesteuerte DevOps-Instanzen
**Universal-Prompt für jeden Chat mit GitHub-Status-Check:**
```markdown
## Framework-Continuation
**Meta-Profile**: https://github.com/VoHoch/meta-ai-interaction-profile
**Projekt-Repository**: https://github.com/VoHoch/[projektname]-VH-1.0
**Aktueller Status**: [Lese aus project_status.md]
**Nächste Phase**: [Framework-Definition Phase X]
**Arbeitsanweisung**: [Framework-Phase-Details aus Repository]

Aktion: Prüfe GitHub-Status → Führe nächste Phase durch → Update Repository → Markiere Phase als abgeschlossen
```

## 🎯 Template Repository Usage

### "Use this template" Workflow
1. **GitHub**: meta-ai-dev-framework → "Use this template"
2. **Repository Name**: `[projektname]-VH-1.0`
3. **Clone lokal**: `git clone https://github.com/VoHoch/[projektname]-VH-1.0`
4. **KI-System wählen**: Entsprechende `/ai-specific/` Implementierung verwenden
5. **Framework durcharbeiten**: 7-Phasen-Modell systematisch abarbeiten

### Projekt-Initialisierung Template
```markdown
# [Projektname] - KI-Entwicklungsprojekt

## Projekt-Meta
- **Framework**: Meta AI Development Framework v1.0
- **Autor**: Volker Hochgürtel
- **Repository**: [projektname]-VH-1.0  
- **KI-System**: Claude/ChatGPT/Gemini
- **Entwicklungsstart**: [Datum]
- **Status**: Phase [X] von 7

## Repository-Links für Chat-Sessions
- **Phase -1,0**: [Chat-Link]
- **Phase 1,2**: [Chat-Link] 
- **Phase 3,4**: [Chat-Link]
- **Phase 5**: [Chat-Link]

## Quick Access
- [Aktueller Status](./docs/project_status.md)
- [Live-Code](./src/)
- [Test-Reports](./tests/)
- [Meta-Framework](https://github.com/VoHoch/meta-ai-dev-framework)
- [Interaktions-Profile](https://github.com/VoHoch/meta-ai-interaction-profile)
```

## 🔗 Cross-Repository Integration

### Meta-Repository-Verknüpfung
**In jedem Projekt-Repository README:**
```markdown
## Framework-Integration
- **Basis-Framework**: [meta-ai-dev-framework](https://github.com/VoHoch/meta-ai-dev-framework)
- **Interaktions-Profil**: [meta-ai-interaction-profile](https://github.com/VoHoch/meta-ai-interaction-profile)
- **Framework-Version**: v1.0
- **KI-Spezifische Implementation**: [Link zu ai-specific/]
```

### Bi-direktionale Updates
**Framework → Projekte**: Template-Updates propagieren zu bestehenden Projekten
**Projekte → Framework**: Successful Patterns zurück ins Meta-Framework integrieren

## 📊 Repository-Health Indicators

```markdown
## Repository-Dashboard
- **Commits**: [Anzahl] (Aktivität-Level)
- **Documentation Coverage**: [%] (Vollständigkeit der Phasen-Dokumentation) 
- **Issue Resolution Time**: [Std] (Effizienz bei Change-Requests)
- **Code-to-Docs Ratio**: [X:Y] (Balance zwischen Code und Dokumentation)
- **KI-System-Usage**: Claude/ChatGPT/Gemini Verteilung bei Multi-KI-Projekten
- **Framework-Compliance**: [%] (Einhaltung der 7-Phasen-Struktur)
```
```

### ai-specific/claude-implementation.md (CREATE/OVERWRITE)
```markdown
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
✅ CLAUDE SUCCESS-PATTERN 5: Voice-to-Text-Pattern-Awareness mit Rückfragen
```

## 🗣️ Voice-to-Text-Pattern-Awareness (Claude-spezifisch)

### Erkannte Fehler-Patterns (Mac German Dictation)
```
HÄUFIGE VOICE-TO-TEXT-FEHLER:
- "GitHub" → "geht hab", "Gitter", "FOS"
- "Repository" → "Repositorium", verschiedene Varianten  
- "Framework" → "Frameburg", "Freiburg"
- "DevOps" → "FOS"
- "VSCode" → "VSCO"
- Technical terms: Deutsche Spracherkennung "übersetzt" englische Fachbegriffe falsch

CLAUDE RESPONSE PATTERN:
## Voice-to-Text Korrekturen (falls erkannt):
- "[Fehler]" → "[Korrektur]" ✓

[Dann normale Antwort auf User Intent]
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
```

## EXECUTE INSTRUCTIONS
1. Create/overwrite all specified files with the content above
2. Maintain consistent file naming (hyphens for compound words)
3. Ensure all content is properly formatted markdown
4. Commit all changes with appropriate commit message
5. Report completion status and any issues encountered

CREATE THESE FILES NOW IN THE meta-ai-dev-framework REPOSITORY.