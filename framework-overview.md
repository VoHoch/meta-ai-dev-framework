# Meta Claude Development Framework v1.1

## 🚨 **KI-System-Compliance-Matrix**

### Phase-spezifische KI-Empfehlungen:
| Phase | Empfohlenes Modell | Begründung | Alternativen |
|-------|-------------------|------------|--------------|
| **Phase 1** | Claude Opus 4 | Komplexe Konzeption & Requirements | Sonnet 4 mit Warnung |
| **Phase 2** | Claude Sonnet 4 | Architektur & Design-Optimierung | Opus 4 für komplexe Systeme |
| **Phase 3** | Claude Sonnet 4 | Setup & Konfiguration | - |
| **Phase 4** | Claude Sonnet 4 | Code-Development & Implementation | - |
| **Phase 5** | Claude Sonnet 4 | Testing & Integration | - |
| **Phase 6** | Claude Sonnet 4 | Deployment & Go-Live | - |
| **Phase 7** | Claude Sonnet 4 | Maintenance & Optimization | - |

## 🎯 **Phase-spezifische KI-Empfehlungen**

### Optimale Model-Allocation:
- **Phase 1 (Konzeption):** Claude Opus 4 empfohlen - Komplexe Analyse und Requirements
- **Phase 2-7 (Implementation):** Claude Sonnet 4 optimal - Strukturierte Umsetzung und Code
- **Automatische Validierung:** Warnung bei suboptimaler Model-Wahl mit Begründung
- **Flexible Fortsetzung:** Framework-Nutzung trotz Model-Mismatch möglich

## ⚠️ **Framework-Compliance-Checks**

### Automatische Validierung:
- **KI-Model-Detection:** Prüfung des aktuellen Claude-Modells
- **Phase-Alignment:** Warnung bei suboptimaler Model-Wahl
- **Repository-Access:** Error-Handling für GitHub-Zugriffsprobleme
- **Quality-Gate-Validation:** Automatische Vollständigkeitsprüfung

# Universelles 7-Phasen-Modell

## 🎯 Framework-Philosophie

**Grundprinzip**: Robuste Software in iterativen Schritten mit persistenter Dokumentation
**Ziel**: KI-agnostische Entwicklungsprozesse für Heim-/KMU-Anwendungen mit Enterprise-Qualität
**Reality Check**: KI unterstützt, Mensch orchestriert, Repository dokumentiert

## 📋 7-Phasen-Modell (Hybrid Chat + Claude Code Workflow)

### 🔄 Hybrid-Workflow-Aufteilung

#### Chat-Phasen (Phase 1-4): Multi-Model-Sessions
**Durchführung**: Claude Web-Chat mit Sonnet/Opus-Spezialisierung
**Output**: Konsolidierte Ergebnisse-Datei für Claude Code Transfer

#### Claude Code-Phasen (Phase 5-7): Repository-basierte Implementation
**Durchführung**: Claude Code mit lokaler Repository-Integration
**Input**: Chat-Ergebnisse als strukturierte Arbeitsanweisungen

### Phase 1: Repository Setup (15 Min) 📋
**Input**: Projektidee + Framework-Entscheidung
**Output**: GitHub-Repo + KI-Projekt + Dokumenten-Templates
**Repository**: Initial setup complete
**Model**: Sonnet (strukturierte Setup-Planung)

**Checkliste:**
- [ ] Repository mit Naming Convention erstellen (`[projektname]-VH-1.0`)
- [ ] KI-Projekt/Session initialisieren
- [ ] Basis-Dokumentenstruktur committen
- [ ] README mit Projekt-Meta erstellen
- [ ] KI-Session-Linking in Repository dokumentieren

### Phase 2: Kickoff & Grundlagen (30 Min) 💡
**Input**: Ihre Idee + Anwendungsfall
**Output**: Plattform-Entscheidung + KI-Rollen-Team + erste Use Cases
**Repository**: `/docs/phase_2_kickoff.md`
**Model**: Opus (kreative Ideenentwicklung)

**Interaktions-Präferenz**: User fokussiert + KI kreativ unterstützend
**KI-Aufgabe**: Anwendungskontext erweitern, aber nicht überdenken

**Deliverables:**
- Projektbeschreibung und Vision
- Zielgruppe-Definition
- Plattform-Entscheidung (Web-App/Desktop/Mobile)
- Erste User Stories
- KI-Rollen-Zuordnung

### Phase 3: Fachexperten-Workshop (45 Min) 🧠
**Input**: Domain-Wissen aktivieren
**Output**: Requirements + mathematische Grundlagen + Validierungsregeln
**Repository**: `/docs/phase_3_domain_expertise.md`
**Model**: Opus (Domain-Expertise)

**Interaktions-Präferenz**: User fokussiert + KI kreativ unterstützend
**KI-Aufgabe**: Domain-Expertise bereitstellen, Fachkenntnisse strukturieren

**Deliverables:**
- Fachliche Grundlagen und Terminologie
- Mathematische Formeln und Berechnungen
- Validierungsregeln und Plausibilitätschecks
- Referenz-Quellen und Standards
- Sicherheitsanforderungen

### Phase 4: Business Requirements (60 Min) 📝
**Input**: Fachexperten-Output
**Output**: User Stories + NFRs + Akzeptanzkriterien
**Repository**: `/docs/phase_4_business_requirements.md`
**Model**: Sonnet (strukturierte Requirements-Analyse)

**Interaktions-Präferenz**: KI kreativ (Business-Analyse ausbauen)
**KI-Aufgabe**: Requirements Engineering, User Experience Design

**Deliverables:**
- Vollständige User Stories mit Akzeptanzkriterien
- Non-Functional Requirements (Performance, Security, Usability)
- UI/UX Anforderungen
- Integration-Requirements
- Deployment-Anforderungen
- **Ergebnisse-Datei**: `ergebnisse-phase-1-4-[projektname].md`

### 🔄 Übergabe-Prozess: Chat → Claude Code

**Transfer-Prozess**:
1. **Download**: ergebnisse-phase-1-4-[projektname].md aus Chat
2. **Repository-Copy**: Datei in lokales Projekt-Repository kopieren
3. **Claude Code Start**: Navigation zu Repository, CLAUDE.md wird geladen
4. **Input**: "Read ergebnisse-phase-1-4-[projektname].md and execute all specified tasks"

### Phase 5: Architektur + Debug-Konzept (45 Min) 🏗️
**Input**: Requirements aus Chat-Phasen
**Output**: Tech-Stack + System-Design + Logging-Strategie
**Repository**: `/docs/phase_5_architecture_spec.md`
**Claude Code Rolle**: System-Architekt

**Arbeitsweise**: Strikt (keine Kreativität, solide technische Entscheidungen)
**KI-Aufgabe**: System-Architektur, Tech-Stack-Entscheidungen

**Deliverables:**
- Tech-Stack-Entscheidung mit Begründung
- System-Architektur-Diagramm
- Datenbank-Design (falls erforderlich)
- API-Spezifikation
- Debug- und Logging-Konzept
- Error-Handling-Strategie

### Phase 6: Implementation (90 Min) 💻
**Input**: Architektur-Specs
**Output**: Vollständige Web-App + Tests
**Repository**: `/src/` + `/tests/`
**Claude Code Rolle**: Developer + Quality Reviewer

**Arbeitsweise**: Strikt (funktionaler Code, Testing)
**KI-Aufgabe**: Code Development, Testing, Quality Assurance

**Deliverables:**
- Vollständiger Quellcode
- Unit-Tests für kritische Funktionen
- Integration-Tests
- Dokumentierter Code
- Error-Handling implementiert

### Phase 7: Testing + Handover (30 Min) ✅
**Input**: Implementierung
**Output**: Test-Reports + User-Guide + Debug-Tools
**Repository**: `/docs/phase_7_testing_handover.md` + `/releases/`
**Claude Code Rolle**: QA + Technical Writer

**Arbeitsweise**: Strikt + User-Acceptance-Integration
**KI-Aufgabe**: Quality Assurance, Documentation, Release Preparation

**Deliverables:**
- Test-Reports und Coverage-Analyse
- User-Guide und Dokumentation
- Deployment-Instructions
- Debug-Tools und -Anleitungen
- Release-Notes

**Gesamt**: ~6 Stunden, optimal zwischen Chat und Claude Code aufgeteilt

## 🛡️ Quality Gates pro Phase

| Phase | Quality Gate | Kriterium | Verantwortlich | Umgebung |
|-------|-------------|-----------|----------------|----------|
| 1 | Setup-Validation | Repository korrekt? | Sonnet | Chat |
| 2 | Vision-Sign-Off | Projektidee klar? | Sie | Chat |
| 3 | Domain-Validation | Fachlogik korrekt? | Opus | Chat |
| 4 | Requirements-Sign-Off | User Stories vollständig? | Sie | Chat |
| 5 | Architecture-Review | Tech-Stack optimal? | Claude Code | Repository |
| 6 | Code-Quality | Funktioniert + getestet? | Claude Code | Repository |
| 7 | User-Acceptance | Praxistauglich? | Sie | Repository |

## 🔄 Standard-Prompts für Hybrid-Workflow

### Chat-Session-Template (Phase 1-4)
```markdown
## Meta AI Framework v1.0 - Chat-Phasen
**Meta-Framework**: https://github.com/VoHoch/meta-ai-dev-framework
**Interaction-Profile**: https://github.com/VoHoch/meta-ai-interaction-profile
**Current Phase**: [1-4] von 7
**Model**: [Sonnet: Structure/Analysis | Opus: Creativity/Domain]
**Workflow-Mode**: Multi-Model Chat-Session
**Target**: Ergebnisse-Datei für Claude Code Transfer

**Quality Standards**: Enterprise-level specifications for SME applications
**Output-Requirement**: Strukturierte Deliverables für Repository-Implementation
```

### Claude Code-Session-Template (Phase 5-7)
```markdown
## Meta AI Framework v1.0 - Implementation-Phasen
**CLAUDE.md**: Auto-loaded ✓
**Input-File**: ergebnisse-phase-1-4-[projektname].md
**Current Phase**: [5-7] von 7
**Role**: System-Architect/Developer/QA
**Workflow-Mode**: Repository-based Implementation
**Target**: Production-ready Application

**Quality Standards**: All Chat-Phase requirements implemented
**Output-Requirement**: Committed code, documentation, tests in repository
```

## 🎯 Framework-Benefits des Hybrid-Ansatzes

**Chat-Stärken genutzt**:
- Multi-Model-Conversations (Sonnet ↔ Opus optimization)
- Komplexe Requirements-Diskussionen mit Nutzer-Interaktion
- Kreative Problem-Solving für Domain-spezifische Herausforderungen

**Claude Code-Stärken genutzt**:
- Lokale Repository-Operations ohne Upload-Download-Overhead
- Bulk-File-Creation für komplexe Projekt-Strukturen
- Automatische Git-Integration und Commit-Management
- Strukturierte Code-Generierung mit Testing-Integration

**Nahtloser Transfer**:
- Strukturierte Übergabe-Dokumente eliminieren Information-Loss
- CLAUDE.md sorgt für konsistente Interaction-Profile-Application
- Repository-basierte Kontinuität zwischen Chat- und Claude Code-Phasen

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