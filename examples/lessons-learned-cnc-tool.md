# Lessons Learned: CNC Tool Projekt

## Was schief ging:
1. Mock-up v2 hatte weniger Features als v1
2. Werkzeugauswahl persistierte nicht
3. Spanncheck war isoliert statt integriert
4. L/D-Checks fehlten trotz Spezifikation

## Was wir gelernt haben:
- IMMER gegen vorherige Version prüfen
- Mock-up Level explizit deklarieren
- Expertenwerte direkt in Code (nicht nur Doku)
- Workflow-Integration > Separate Tabs

## Konkrete Verbesserungen:
- Requirements-Tracking-Matrix eingeführt
- 4-Level Mock-up System definiert
- Regression-Checklist erstellt