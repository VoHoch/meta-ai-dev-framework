# Framework Update-Checklist

## ✅ Kritische Validierungs-Punkte bei jedem Update:

### 1. User-Interface-Consistency:
- [ ] README.md Startup-Prompt aktualisiert
- [ ] Alle Beispiel-Prompts enthalten neue Features
- [ ] Documentation vs. Practice-Alignment geprüft

### 2. Integration-Points validiert:
- [ ] framework-overview.md
- [ ] startup-script.md
- [ ] README.md User-Prompt
- [ ] ai-specific/claude-implementation.md

### 3. End-to-End-Test:
- [ ] Startup-Prompt in neuer Session getestet
- [ ] Neue Features funktionieren wie dokumentiert
- [ ] Backwards-Compatibility gewährleistet

## 🔄 Update-Quality-Gates

### Framework-Update-Validation:
1. **Documentation-Update:** Alle .md Dateien aktualisiert
2. **User-Interface-Update:** README-Prompt enthält neue Features
3. **Integration-Test:** Startup funktioniert in isolierter Session
4. **Regression-Test:** Bestehende Features weiterhin funktional

### Critical-Path-Validation:
- **User-Entry-Point:** README.md Startup-Prompt
- **Core-Logic:** framework-overview.md
- **Implementation:** ai-specific/ Files

## 🎯 Zukünftiger Update-Workflow:

### Neuer Standard-Prozess:
1. **Core-Documentation updaten**
2. **User-Interface-Sync** → README-Prompt aktualisieren
3. **Integration-Test** → Startup in neuer Session validieren
4. **Quality-Gate** → Update-Checklist abarbeiten
5. **Commit** → Nur wenn alle Validierungen erfolgreich

### Mandatory Checks vor jedem Commit:
- [ ] README-Prompt in neuer Session validiert
- [ ] Alle User-Touch-Points geprüft
- [ ] Documentation vs. Practice-Alignment bestätigt
- [ ] Bestehende Features weiterhin funktional