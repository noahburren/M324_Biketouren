# Meetings & Arbeitsprozesse

> Zurück zur [Übersicht](../README.md)

## Status dieses Dokuments

Die folgenden Regeln sind ein **Teamvorschlag**. Sie gelten erst als gemeinsam vereinbart, wenn das Team sie bestätigt hat.

**TODO: Vom Team ergänzen:** Vorschlag gemeinsam prüfen, Anpassungen festhalten und Bestätigung mit Datum dokumentieren.

## Team und Zusammenarbeit

Zum Team gehören Noah, Zakria, Luca, Yannik und Amir. Alle arbeiten cross-funktional. Entwicklung, Tests, Review, Dokumentation und Infrastruktur werden je nach Aufgabe verteilt beziehungsweise rotiert. Es werden keine dauerhaften Spezialrollen vergeben.

## Arbeitsweise mit dem Projektboard

[Link zum Board](https://gitlab.com/noahburren/M324_Biketouren/-/boards#/)

| Phase | Vorgeschlagene Bedeutung |
|---|---|
| Backlog | Ein Issue ist erfasst, aber noch nicht vollständig geklärt oder eingeplant. |
| Ready | Ziel, Umfang und Akzeptanzkriterien sind gemeinsam geklärt; das Issue erfüllt die Definition of Ready. |
| In progress | Eine oder mehrere Personen bearbeiten das Issue aktiv. |
| In review | Umsetzung, Dokumentation und Tests werden geprüft; offene Review-Punkte werden bearbeitet. |
| Done | Das Issue erfüllt die bestätigte Definition of Done. |

## Weg eines Issues bis Done

1. Ein Thema wird als Issue im **Backlog** erfasst.
2. Das Team klärt Ziel, Umfang, Abhängigkeiten und überprüfbare Akzeptanzkriterien gemeinsam.
3. Erfüllt das Issue die Definition of Ready, wird es nach **Ready** verschoben.
4. Bei Beginn der Bearbeitung wechselt es nach **In progress**.
5. Die Umsetzung umfasst je nach Issue auch Tests, Dokumentation und notwendige Infrastrukturarbeiten.
6. Ein Pull Request wird nach **In review** überführt. Mindestens eine andere Person prüft Änderung, Akzeptanzkriterien und Testergebnisse.
7. Nach behobenen Review-Punkten und erfolgreicher Prüfung wird das Issue nach **Done** verschoben.

## Definition of Ready

Vorgeschlagen ist, dass ein Issue erst als Ready gilt, wenn:

- [ ] Ziel und erwarteter Nutzen verständlich beschrieben sind;
- [ ] der Umfang ausreichend abgegrenzt ist;
- [ ] überprüfbare Akzeptanzkriterien vorhanden sind;
- [ ] bekannte Abhängigkeiten, offene Fragen und Risiken sichtbar sind;
- [ ] das Issue klein genug für eine überschaubare Bearbeitung ist oder sinnvoll aufgeteilt wurde.

## Branch- und Pull-Request-Grundsätze

- Änderungen erfolgen auf einem eigenen, kurzlebigen Branch.
- Der Branch-Name verweist wenn möglich auf das Issue und beschreibt die Änderung, zum Beispiel `feature/12-login-endpoint`.
- Ein Pull Request beschreibt Zweck, Bezug zum Issue, wichtige Änderungen und durchgeführte Prüfungen.
- Vor dem Zusammenführen prüft mindestens eine andere Person den Pull Request.
- Review-Kommentare und offene Fragen werden nachvollziehbar geklärt.
- Direkte Änderungen am gemeinsam geschützten Hauptbranch werden vermieden, sofern das Team nichts anderes beschliesst.

## Commit-Nachrichten

Commit-Nachrichten sollen kurz, verständlich und nachvollziehbar beschreiben, was geändert wurde. Wenn sinnvoll, enthalten sie die Issue-Nummer. Ein Commit soll eine zusammengehörige Änderung enthalten.

## Definition of Done

Vorgeschlagen ist, dass ein Issue erst als Done gilt, wenn:

- [ ] alle bestätigten Akzeptanzkriterien erfüllt sind;
- [ ] passende automatisierte oder manuelle Tests durchgeführt und nachvollziehbar dokumentiert sind;
- [ ] relevante Tests erfolgreich sind;
- [ ] notwendige Dokumentation aktualisiert ist;
- [ ] keine Zugangsdaten oder sensiblen Informationen eingecheckt wurden;
- [ ] der Pull Request von mindestens einer anderen Person geprüft wurde;
- [ ] offene Review-Punkte geklärt sind;
- [ ] die Änderung in den vorgesehenen Hauptbranch übernommen wurde.

## Rotation der Tätigkeiten

Das Team verteilt Entwicklung, Tests, Review, Dokumentation und Infrastruktur über die Issues hinweg neu. Reviews werden nicht dauerhaft von derselben Person durchgeführt. Bei der Planung achtet das Team darauf, Wissen weiterzugeben und Tätigkeiten so zu rotieren, dass alle Mitglieder verschiedene Bereiche kennenlernen.

## Meeting-Protokolle

Bestätigte Meetings können nach diesem Muster dokumentiert oder in einem separaten Dokument verlinkt werden:

### JJJJ-MM-TT – Titel

- **Teilnehmende:** TODO: Vom Team ergänzen
- **Entscheide:** TODO: Vom Team ergänzen
- **Offene Punkte:** TODO: Vom Team ergänzen

| Aufgabe | Zuständig | Termin |
|---|---|---|
| TODO: Vom Team ergänzen | TODO: Vom Team ergänzen | TODO: Vom Team ergänzen |
