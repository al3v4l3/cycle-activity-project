# So arbeiten wir zusammen

Für die Dokumente brauchen wir zunächst nur GitHub. Eine lokale Entwicklungsumgebung richten wir später passend zu unserer Technik ein.

## Eine Aufgabe bearbeiten

1. Eine Aufgabe auf dem [Board](https://github.com/users/al3v4l3/projects/1/views/1) auswählen und gemeinsam klären.
2. Eine verantwortliche Person, eine zweite Person zum Prüfen und einen Termin festhalten.
3. Das zuständige Dokument bearbeiten. Für Änderungen eine eigene Branch und einen Pull Request anlegen, z. B. `codex/projektziel`.
4. Im Pull Request kurz erklären: Was ist anders? Warum? Wie wurde es geprüft?
5. Die zweite Person liest gegen. Danach Änderungen zusammenführen, Ergebnis im Issue verlinken und den Boardstatus anpassen.

Der Eigentümer lädt die anderen drei mit ihren bestätigten GitHub-Namen ein. Zugriff auf **Repo und Projektboard** getrennt prüfen. Namen und konkrete Einladungen sind hier noch offen. Der beschriebene Prüfablauf ist unsere Arbeitsvereinbarung und wird nicht durch eine eingerichtete Branch-Schutzregel erzwungen.

## Was gehört wohin?

| Inhalt | Ort |
| --- | --- |
| Ziel und Erfolgskriterien | `docs/00-projektziel.md` |
| Anforderungen | `docs/02-lastenheft.md` |
| Lösungsentwurf | `docs/03-pflichtenheft.md` |
| Stories und Kriterien | `docs/04-user-stories.md` |
| Zuständigkeit, Aufwand, Hindernis, Ergebnislink | GitHub Issue |
| Arbeitsstatus | Kanban-Board |
| Beschlüsse und echte Treffen | `docs/entscheidungen.md`, `docs/protokolle/` |
| Bilder, später Code und Tests | `design/`, `src/`, `tests/` |

Eine Regel möglichst an einer Stelle festlegen und anderswo darauf verweisen. Ändert sich eine Anforderung, prüfen wir die betroffenen Stories, Entwürfe und Tests mit.

**Ready:** Wir verstehen Ergebnis und Kriterien und haben Verantwortung sowie Aufwand geklärt. **Done:** Kriterien erfüllt, Ergebnis verlinkt und von einer zweiten Person geprüft. Bei Software gehören passende Tests dazu. Ein fertiges Planungsdokument ist noch keine fertige App.

Ein Entwurfs-PR kann mit `Refs #5` auf eine Aufgabe verweisen. `Closes #5` nur verwenden, wenn die gesamte Aufgabe wirklich fertig ist, weil sie dadurch automatisch geschlossen werden kann.

## Was bleibt privat?

Keine originalen Moodle-Dateien, echten Gesundheitsdaten, Rohinterviews oder Zugangsdaten veröffentlichen. Die Dateiliste vor dem Teilen ansehen; `.gitignore` verhindert keine manuellen Uploads auf GitHub. Fremde Quellen und Lizenzen sowie KI-Unterstützung nachvollziehbar nennen. Genaue Hochschulregeln noch bestätigen.
