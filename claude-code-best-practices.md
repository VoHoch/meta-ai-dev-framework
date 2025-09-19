# Claude Code Best Practices für Framework-Updates

## 🚀 Robuster Update-Workflow

### Update-Process-Template:
1. **BACKUP & BRANCH**
   ```bash
   git checkout -b framework-update-v1.X
   git status  # clean state validieren
   ```

2. **UPDATE-EXECUTION**
   - Alle Updates systematisch implementieren
   - Nach jedem Step validieren
   - Syntax-Checks durchführen

3. **VALIDATION & COMMIT**
   ```bash
   git status  # alle Änderungen prüfen
   git diff   # Änderungen reviewen
   git add .  # alle Changes stagen
   git commit -m "feat: Framework v1.X - [beschreibung der updates]"
   ```

4. **MERGE & PUSH**
   ```bash
   git checkout main
   git merge framework-update-v1.X
   git push origin main
   git branch -d framework-update-v1.X
   ```

5. **FINAL VALIDATION**
   ```bash
   git status  # MUSS "clean" sein
   git log --oneline -3  # commits validieren
   ```

## ✅ Update-Success-Criteria:
- [ ] Alle geplanten Changes implementiert
- [ ] git status zeigt clean state
- [ ] Commits haben aussagekräftige Messages
- [ ] Framework-Version korrekt updated
- [ ] Keine temporären Dateien im Repository

## 🚨 Update-Failure-Recovery:
Bei Problemen:
1. git status prüfen
2. Unstaged changes committen oder discarden
3. Repository bereinigen vor weiterem Vorgehen
4. Bei Unsicherheit: Branch-Backup nutzen

## 🛠️ Claude Code Specific Best Practices

### End-to-End Update Execution:
- **Single Session:** Komplette Updates in einer Claude Code Session
- **Atomic Changes:** Alle zusammengehörigen Änderungen in einem Commit
- **Validation-First:** Immer git status und syntax checks vor commit
- **Clean Repository:** Keine temporären oder backup-Dateien im Repo

### Error Prevention:
- **Pre-Flight Checks:** git status clean vor Start
- **Incremental Validation:** Nach jedem File-Update prüfen
- **Commit Message Standards:** Aussagekräftige conventional commits
- **Repository Hygiene:** Nur Framework-Kern-Dateien committen

### Quality Assurance:
- **Cross-File Consistency:** Alle referenzierten Dateien existieren
- **Version Alignment:** Versionsnummern in allen Files konsistent
- **Documentation Completeness:** Alle neuen Features dokumentiert
- **Backward Compatibility:** Bestehende Workflows bleiben funktional

## 📋 Update-Checklist Template

### Pre-Update:
- [ ] Repository clean state (git status)
- [ ] Update-Scope klar definiert
- [ ] Backup-Strategie festgelegt

### During Update:
- [ ] Systematische File-by-File Implementierung
- [ ] Continuous syntax validation
- [ ] Cross-reference consistency checks
- [ ] Version number alignment

### Post-Update:
- [ ] git status clean
- [ ] All changes committed with meaningful messages
- [ ] Push successful
- [ ] Framework functionality validated
- [ ] Documentation updated and consistent

## 🔧 Troubleshooting Guide

### Common Issues:
1. **Dirty Repository State**
   - Solution: git status → git add . oder git restore .

2. **Inconsistent Version Numbers**
   - Solution: Search & replace all version references

3. **Missing File References**
   - Solution: Create missing files or update references

4. **Syntax Errors**
   - Solution: Validate markdown and fix before commit

### Recovery Procedures:
- **Reset to Last Good State:** git reset --hard HEAD~1
- **Selective Undo:** git restore [filename]
- **Branch Recovery:** git checkout main && git branch -D broken-branch
- **Clean Restart:** Start fresh with clean git status