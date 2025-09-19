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