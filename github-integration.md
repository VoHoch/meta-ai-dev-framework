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