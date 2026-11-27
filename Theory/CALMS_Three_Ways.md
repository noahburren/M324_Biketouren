# CALMS und The Three Ways

> Zurück zur [Theorieübersicht](README.md)

## 1. CALMS

- C (Culture)
    - Kommunikation, Respekt
    - gemeinsames Ziel / Verantwortung
    - Fehlerkultur, keine Schuldzuweisungen
    - TechNova: Workshops, Teambuilding

- A (Automation)
    - weniger manuelle Schritte
    - schnellere Abläufe
    - Vertrauen durch automatisierte Tests
    - CI/CD bei TechNova

- L (Lean)
    - remove waste
    - Wartezeiten reduzieren
    - kontinuierliche Verbesserung
    - Kundennutzen im Vordergrund
    - TechNova: Kanban-Boards, weniger Wartezeiten

- M (Measurement)
    - Entscheidungen anhand von Metriken
    - Wie gut funktionieren unsere Prozesse?
    - Prozess-, Betriebs- und Business-Metriken
    - TechNova: Lead Time, Deployment Frequency, MTTR

- S (Sharing)
    - Know-how im Team verteilen
    - Dokumentation / Wiki
    - aus Erfahrungen anderer lernen
    - eng verbunden mit Culture
    - TechNova: Wiki, interne Lernformate, Erfahrungsberichte

## 2. The Three Ways

- First Way: Systems Thinking
    - gesamtes System betrachten
    - Flow von Dev zu Ops
    - Bottlenecks erkennen
    - nicht nur einzelne Bereiche optimieren
    - TechNova: weniger Silos, CI/CD

- Second Way: Feedback Loops
    - möglichst schnelles Feedback
    - Fehler früh erkennen und beheben
    - TechNova: wöchentliche Releases, schnelleres Kundenfeedback

- Third Way: Continual Learning and Experimentation
    - aus Fehlern lernen
    - neue Dinge ausprobieren
    - Wissen weitergeben
    - TechNova: Workshops, Lernformate, Erfahrungsberichte

## 3. Vergleich

| Idee | CALMS | Three Ways | TechNova | Einschätzung |
| --- | --- | --- | --- | --- |
| Zusammenarbeit | C, S | First Way | Workshops | weniger Silos |
| Arbeitsfluss | A, L | First Way | CI/CD, Kanban | weniger Wartezeit |
| Feedback | M | Second Way | Kundenfeedback | schneller reagieren |
| Lernen | S, C | Third Way | Wiki, Workshops | Wissen nicht nur bei einzelnen Personen |

### Unterschiede

- CALMS: verschiedene Bereiche einer DevOps-Kultur
- Three Ways: mehr Fokus auf Flow, Feedback und Lernen

### Gemeinsamkeiten

- Zusammenarbeit zwischen Dev und Ops
- continuous improvement
- schnellere Auslieferung
- bessere Qualität

## Missverständnisse rund um DevOps

- DevOps ist nicht nur Automation
  - Kultur, Zusammenarbeit und Kommunikation genauso wichtig
- betrifft die ganze Organisation
  - auch Testing, Security und Management
- Tools alleine reichen nicht (Docker, Jenkins usw.)
- keine sofortige Lösung für alle Probleme
  - schrittweise Verbesserung
- nicht jeder Entwickler muss alles können
  - gemeinsame Verantwortung im Team
- auch für kleine Unternehmen geeignet
- Agile und DevOps ergänzen sich
- kein kurzfristiger Hype
- bestehende Prozesse verbessern statt komplett ersetzen
- nicht nur Kosten sparen
  - Qualität, Geschwindigkeit und Kundenzufriedenheit

## Knowledge Check

### 1. Warum ist die kulturelle Veränderung wichtig?

- bessere Kommunikation zwischen Dev und Ops
- gemeinsame Ziele und Verantwortung
- offene Fehlerkultur
- Automation alleine löst keine organisatorischen Probleme

### 2. Welche Rolle haben Führungskräfte?

- Zeit und Ressourcen bereitstellen
- Zusammenarbeit fördern
- Vertrauen schaffen
- Weiterbildung ermöglichen
- Fehler als Lernmöglichkeit betrachten

### 3. Warum schrittweise einführen?

- weniger Risiken
- Mitarbeitende können sich anpassen
- bestehende Prozesse weiterverwenden
- z.B. Tests, Deployments und Reviews schrittweise verbessern

### 4. Vorteile für kleinere Unternehmen

- weniger manueller Aufwand
- effizientere Nutzung vorhandener Ressourcen
- schnellere Releases
- schneller auf Kundenwünsche reagieren

### 5. Zusammenhang zwischen Agile und DevOps

- Agile: iterative Entwicklung, flexible Planung
- DevOps: Auslieferung, Betrieb und Feedback
- gemeinsam: continuous improvement

### 6. Langfristige Vorteile

- bessere Softwarequalität
- höhere Kundenzufriedenheit
- kürzere Release-Zyklen
- bessere Wettbewerbsfähigkeit
- stabilerer Betrieb

### 7. DevOps in hierarchischen Unternehmen

- Silos schrittweise abbauen
- cross-funktionale Teams
- kürzere Entscheidungswege
- mehr Eigenverantwortung
- gemeinsame Ziele statt einzelner Abteilungsziele

## 4. Bewertung der Transformation

### CI/CD-Pipeline

- vorher viele manuelle Schritte
- weniger Aufwand und Fehler durch Automation
- Releases nach der Transformation: halbjährlich → wöchentlich
- CALMS: A, L
- Three Ways: First + Second Way

### Abbau von Silos

- vorher getrennte Teams
- schlechte Kommunikation / Schuldzuweisungen
- Workshops und Teambuilding
- mehr gemeinsame Verantwortung
- meiner Meinung nach wichtig, damit CI/CD überhaupt sinnvoll funktioniert
- CALMS: C, S
- Three Ways: First Way

## 5. Transfer auf vorherige Projekte

### Aktueller Stand

- GitHub-Repo
- Issues / Kanban
- Arbeitsprozess dokumentiert

### Was verbessern?

- main schützen, kein direct push
- eigene Branches für Issues
- Pull Requests
- gegenseitige Reviews → Wissen verteilen(Dokumentation)
- CALMS: Culture und Sharing
- Second Way: Feedback vor Merge

### Messung

- Review-Dauer
- Anzahl geprüfter PRs
- Fehler vor Merge erkannt?

## 6. KI-Nachweis

- Tool: ChatGPT
- Zweck: Strukturierung der Untertitel

## Quellen

- [CALMS](https://ch-tbz-it.gitlab.io/Stud/m324/Kultur/CALMS/)
- [The Three Ways](https://ch-tbz-it.gitlab.io/Stud/m324/Kultur/TheThreeWays/)
- [Fallstudie TechNova Solutions](https://ch-tbz-it.gitlab.io/Stud/m324/Projekt/T1_Theorie_DevOps_Kultur/#fallstudie-die-devops-transformation-von-technova-solutions)
