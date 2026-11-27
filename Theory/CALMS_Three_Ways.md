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
