# Zusammenarbeit auf GitHub

## Eine Aufgabe bearbeiten

1. Ein Issue unter [Planungsaufgaben](https://github.com/al3v4l3/cycle-activity-project/issues?q=is%3Aissue%20label%3Aplanung) oder [User Stories](https://github.com/al3v4l3/cycle-activity-project/issues?q=is%3Aissue%20label%3Astory) öffnen. Ergebnis und Kriterien lesen.
2. Über **Assignees** eine zuständige Person festlegen. Aufwand und offene Fragen im Issue ergänzen.
3. Eine eigene **Branch** anlegen, zum Beispiel `docs/anforderungen`. Eine Branch ist eine Arbeitskopie des Projektstands.
4. Dort die Dateien ändern und speichern. Ein **Commit** ist ein gespeicherter Änderungsstand.
5. Einen **Pull Request** nach `main` öffnen. Darin stehen der Grund, die zugehörige Issue-Nummer und die Prüfung.
6. Änderungen prüfen, möglichst gegenlesen lassen und mit **Merge** übernehmen. `main` enthält den gemeinsamen Stand.
7. Ergebnis im Issue verlinken. Erst schließen, wenn die Kriterien erfüllt sind.

Auch im GitHub-Dateieditor bei der Commit-Auswahl eine neue Branch und einen Pull Request verwenden. Wir arbeiten für Aufgaben nicht direkt auf `main`.

## Boardstatus

| Status | Bedeutung |
| --- | --- |
| Backlog | bekannt, noch nicht begonnen |
| Ready | Aufgabe, Kriterien, Zuständigkeit und Aufwand geklärt |
| In progress | wird gerade bearbeitet |
| In review | Ergebnis liegt vor und wird geprüft |
| Done | Kriterien erfüllt, Ergebnis geprüft und verlinkt |

Ein fertiger Planungstext bedeutet nicht, dass die App-Funktion schon umgesetzt ist. Die Produkt-Stories bleiben bis zur späteren Entwicklung im Backlog.

## Inhalt pflegen

Anforderungen stehen in `docs/02-anforderungen.md`. Die vollständigen Stories, Akzeptanzkriterien und zugehörigen Aufgaben stehen jeweils im Story-Issue. `docs/03-product-backlog.md` verlinkt und ordnet sie. Status und Zuständigkeit stehen in GitHub.

Eine geänderte Anforderung kann auch Stories, Entwurf und Prüfungen betreffen. Änderungen deshalb zusammen abgleichen. `Refs #…` verlinkt ein Issue; `Closes #…` schließt es beim Merge und passt nur bei vollständig erledigter Arbeit.

Zugangsdaten und echte Gesundheitsdaten gehören nicht ins öffentliche Repository. Beispiele und Screenshots verwenden künstliche Daten. Originale Vorlesungsunterlagen bleiben lokal.
