# 1. Was ist SDLC und wie gliedert sich dieser Prozess?

Der **Software Development Life Cycle (SDLC)** ist ein strukturierter Prozess, der Software von der Idee bis zum Betrieb begleitet. Er macht Qualität, Kosten und Termine planbar. Das Feedback aus dem Betrieb fliesst zurück in die Planung, deshalb ist es ein *Zyklus*.

## Welche Schritte umfasst der SDLC und wie tragen sie bei?

| Phase | Beitrag |
|---|---|
| **Planung** | Ziel, Umfang, Ressourcen und Risiken festlegen |
| **Anforderungen** | Definieren, *was* gebaut wird (Massstab für Tests) |
| **Design** | Architektur und Schnittstellen festlegen (Bauplan) |
| **Implementierung** | Code gemäss Design schreiben |
| **Testen** | Prüfen, ob die Anforderungen erfüllt sind |
| **Deployment** | Software für Benutzer verfügbar machen |
| **Betrieb & Wartung** | Monitoring, Bugfixes; Feedback wird zu neuen Anforderungen |

## Wie wird der SDLC im Projekt angewendet und gesteuert?

- **Vorgehensmodell:** Beim Wasserfall bzw. V-Modell werden die Phasen nacheinander durchlaufen. Bei agilen Modellen (z. B. Scrum) werden alle Phasen in jedem Sprint durchlaufen.
- **Steuerung:** Über Rollen (PO, Scrum Master, Team), Backlog, Meilensteine, Reviews und Retrospektiven, Tools (GitLab Issues, Git) und Kennzahlen (z. B. Burndown).

---

# 2. Was ist der DevOps Lifecycle und wie ist er strukturiert?

## Definition und Kernphasen

**DevOps** verbindet Entwicklung (*Development*) und Betrieb (*Operations*) zu einem gemeinsamen, stark automatisierten Prozess. Der Lifecycle wird als **Endlosschleife (∞)** dargestellt, weil die Phasen kontinuierlich wiederholt werden.

| Phase | Inhalt |
|---|---|
| **Plan** | Anforderungen und Backlog planen |
| **Code** | Entwickeln, Versionskontrolle (Git) |
| **Build** | Code automatisch kompilieren und paketieren |
| **Test** | Automatisierte Tests (Continuous Testing) |
| **Release** | Freigabe für die Auslieferung |
| **Deploy** | Automatisch ausliefern (Continuous Deployment) |
| **Operate** | Software betreiben, Infrastruktur verwalten |
| **Monitor** | Laufzeit, Fehler und Nutzung überwachen; Feedback geht zurück zu *Plan* |

Grundlage dafür sind **CI/CD-Pipelines** (Continuous Integration / Continuous Delivery bzw. Deployment).

## Ziele im Vergleich zu traditionellen Ansätzen

- **Schnellere Releases:** Kleine, häufige Releases statt seltener Grossreleases
- **Automatisierung:** Weniger manuelle, fehleranfällige Schritte
- **Zusammenarbeit:** Dev und Ops arbeiten nicht mehr in getrennten Silos
- **Schnelles Feedback:** Fehler früh erkennen und rasch beheben
- **Stabilität:** Kleine Änderungen sind einfacher zu testen und zurückzurollen

---

# 3. Welche Unterschiede gibt es zwischen SDLC und DevOps Lifecycle?

## Ansätze, Prozesse und Ziele

| Aspekt | SDLC (klassisch) | DevOps Lifecycle |
|---|---|---|
| **Ansatz** | Phasenorientiert, oft linear | Kontinuierlich, als Endlosschleife |
| **Prozess** | Übergaben zwischen Teams (Dev → Test → Ops) | Gemeinsame Verantwortung von Dev und Ops |
| **Automatisierung** | Gering, viele manuelle Schritte | Hoch (CI/CD, Infrastructure as Code) |
| **Release-Zyklus** | Selten, grosse Releases | Häufig, kleine Releases |
| **Betrieb** | Ende des Prozesses, separates Team | Fester Teil des Zyklus (Operate & Monitor) |
| **Ziel** | Planbare, vollständige Lieferung | Schnelle, stabile und laufende Lieferung |

## Auswirkungen auf Entwicklung, Bereitstellung und Betrieb

- **Entwicklung:** Bei DevOps wird in kleinen Inkrementen gearbeitet, und Tests laufen automatisch bei jedem Commit.
- **Bereitstellung:** Beim SDLC erfolgt das Deployment selten und mit hohem Risiko. Bei DevOps geschieht es automatisiert, häufig und mit geringem Risiko.
- **Betrieb:** Bei DevOps fliessen Monitoring-Daten direkt in die Planung zurück. Probleme werden schneller erkannt und behoben.

Der SDLC beschreibt also, *welche* Phasen nötig sind. DevOps beschreibt, *wie* diese Phasen schnell, automatisiert und gemeinsam durchlaufen werden.

---

# 4. Was ist ein MVP und welche Bedeutung hat es im DevOps Lifecycle?

## Definition und Kernmerkmale

Ein **Minimum Viable Product (MVP)** ist die einfachste Version eines Produkts, die gerade genug Funktionen hat, um echten Nutzen zu bieten und Feedback von Benutzern zu sammeln.

- **Minimal:** Nur die wichtigsten Kernfunktionen
- **Funktionsfähig:** Kein Prototyp, sondern wirklich nutzbar
- **Lernorientiert:** Ziel ist es, Annahmen zu überprüfen
- **Schnell und günstig:** Kurze Zeit bis zur ersten Auslieferung

## Rolle im DevOps Lifecycle

| Phase | Rolle des MVP |
|---|---|
| **Plan** | Kernfunktionen priorisieren, Rest ins Backlog |
| **Code / Build / Test** | Kleiner Umfang, daher schnell umsetzbar und gut testbar |
| **Release / Deploy** | Früh über die CI/CD-Pipeline an echte Benutzer ausliefern |
| **Operate / Monitor** | Nutzung und Feedback messen |
| **→ Plan** | Feedback bestimmt die nächste Iteration |

Das MVP ist der Startpunkt der DevOps-Schleife: Statt alles im Voraus zu planen, wird früh ausgeliefert, gemessen, gelernt und iterativ verbessert (*Build – Measure – Learn*).

---
## Quellen

### 1. SDLC
1. Amazon Web Services (AWS). *What is SDLC (Software Development Lifecycle)?* https://aws.amazon.com/what-is/sdlc/
2. IBM. *What is the software development life cycle (SDLC)?* https://www.ibm.com/think/topics/sdlc
3. Atlassian. *What is the software development life cycle (SDLC)? The complete guide.* https://www.atlassian.com/agile/software-development/sdlc 

### 2. DevOps Lifecycle
4. Atlassian. *What is DevOps?* https://www.atlassian.com/devops
5. Atlassian. *DevOps Tools – Choose tools for each phase of the DevOps lifecycle.* https://www.atlassian.com/devops/devops-tools

### 3. SDLC vs. DevOps
6. IBM. *What is the software development life cycle (SDLC)?* (Abschnitt zu SDLC-Modellen) https://www.ibm.com/think/topics/sdlc
7. phoenixNAP. *What Is SDLC? Software Development Life Cycle Defined.* https://phoenixnap.com/blog/software-development-life-cycle

### 4. MVP
8. Atlassian. *What is a Minimum Viable Product (MVP)?* https://www.atlassian.com/agile/product-management/minimum-viable-product 
9. Agile Alliance. *Agile Glossary: Minimum Viable Product (MVP).* https://www.agilealliance.org/glossary/mvp/
10. Techopedia. *Minimum Viable Product (MVP).* https://www.techopedia.com/definition/27809/minimum-viable-product-mvp

---

# Vertiefung: Transfer auf unser Projekt «Biketouren»

Unser Projekt befindet sich noch am Anfang, der genaue Funktionsumfang ist noch nicht definiert. Wir planen deshalb, nach folgendem Vorgehen zu arbeiten:

**SDLC:** Wir arbeiten agil in Sprints. In jedem Sprint durchlaufen wir die SDLC-Phasen im Kleinen: Anforderungen als GitLab-Issues erfassen → Design besprechen → implementieren → testen → mergen → Feedback in der Retrospektive.

**DevOps:**
- **Plan:** GitLab Issues und Board als Backlog
- **Code:** Git-Repository auf GitLab, Feature-Branches, Merge Requests mit Code-Review
- **Build/Test/Deploy:** Aufbau einer GitLab CI/CD-Pipeline, die bei jedem Push automatisch baut und testet
- **Monitor/Feedback:** Rückmeldungen aus Reviews und von der Lehrperson fliessen als neue Issues ins Backlog

**MVP:** Als ersten Schritt definieren wir ein MVP mit den wichtigsten Kernfunktionen rund um Biketouren. Weitere Funktionen nehmen wir ins Backlog auf und setzen sie erst in späteren Iterationen um.

**Erkenntnis:** Gerade weil unsere Anforderungen noch unklar sind, passt ein agiles Vorgehen mit MVP besser als ein Wasserfall. Wir bekommen früh Feedback und können die Anforderungen schrittweise schärfen, statt alles im Voraus festzulegen.

---

## KI-Protokoll

| Nr. | Prompt | Geprüfte KI-Ausgabe | Verwendete Quelle | Korrektur / Bestätigung | Eigenes Fazit |
|---|---|---|---|---|---|
| 1 | «Was ist SDLC und wie gliedert sich dieser Prozess?» | Definition und 7 Phasen, Vorgehensmodelle | AWS, IBM, Atlassian | Bestätigt: IBM und Atlassian beschreiben ebenfalls 7 Phasen und unterscheiden zwischen Wasserfall und agilem Vorgehen. | Der SDLC gibt die Phasen vor. Wie streng man sie durchläuft, hängt vom Vorgehensmodell ab. |
| 2 | «Was ist der DevOps Lifecycle?» | 8 Phasen als Endlosschleife, CI/CD | Atlassian | Bestätigt: 8 Phasen in einer Endlosschleife. Die Phasennamen unterscheiden sich je nach Quelle leicht. | DevOps verbindet Entwicklung und Betrieb, Automatisierung ist dabei zentral. |
| 3 | «Unterschiede SDLC vs. DevOps?» | Vergleichstabelle | IBM, phoenixNAP | Ergänzt: DevOps ersetzt den SDLC nicht, sondern baut darauf auf (phoenixNAP). | DevOps ist eine schnellere, automatisierte Umsetzung des SDLC. |
| 4 | «Was ist ein MVP und welche Rolle hat es in DevOps?» | Definition, Merkmale, Build-Measure-Learn | Atlassian, Agile Alliance, Techopedia | Bestätigt: Das MVP stammt aus Lean Startup. Ergänzt: Ein MVP muss nutzbar («viable») sein, nicht nur minimal. | Ein MVP ermöglicht frühes Feedback und passt gut zum iterativen DevOps-Zyklus. |