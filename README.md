# Fitness und Zyklus · Software-Engineering-Projekt

Dies ist das **gemeinsame Projekt- und Entwicklungsrepository** unseres vierköpfigen Teams. Hier entsteht die mobile Web-App, die Training, persönliches Tagesbefinden und freiwillige Zyklusangaben zusammenführt: von Anforderungen und Entwurf über Quellcode und Tests bis zur Abgabe und Weiterentwicklung.

**Aktuelle Phase: Projektstart und Vorbereitung der ersten Vorstellung.** Die erste Implementierungsiteration folgt laut unserer Mitschrift nach der Vorstellung gegen Semesterende. Es gibt noch keine lauffähige App; der Anwendungscode wird später in diesem selben Repository entwickelt.

Arbeitstitel: **CSAH**. „Cycle Sync Activity Hub“ und „Cycle, Strength, Awareness, Harmony“ sind Namensideen; Name und Bedeutung sind noch nicht entschieden.

**[Kanban-Board](https://github.com/users/al3v4l3/projects/1)** · **[Aufgaben](https://github.com/al3v4l3/cycle-activity-project/issues)** · **[Checkliste für die erste Vorstellung](docs/09-meilenstein-vorstellung.md)**

## Hier beginnt ihr

Öffnet gemeinsam **[START-HIER.md](START-HIER.md)**. Dort steht der Ablauf für eure erste Arbeitsstunde. Alle Produktinhalte sind vorbereitete **Entwürfe**, die ihr im Team prüft. Aussagen über Bedürfnisse sind bis zu einer Erhebung Hypothesen.

| Ich möchte … | Hier arbeiten wir |
| --- | --- |
| wissen, was wir zur ersten Vorstellung vorbereiten | [Meilenstein M1 nach Mitschrift](docs/09-meilenstein-vorstellung.md) |
| Einleitung und Motivation gemeinsam ausarbeiten | [Projektbeschreibung in Prosa](docs/10-einleitung-und-motivation.md) |
| Technologie und KI-Unterstützung auswählen | [Technologieentscheidung](docs/11-technologie-und-ki.md) |
| verstehen, was die Vorlesung dazu sagt | [Vorlesungsbezug](docs/01-vorlesungsbezug.md) |
| festhalten, für wen wir welches Problem lösen | [Lastenheft](docs/02-lastenheft.md) |
| beschreiben, wie wir Anforderungen umsetzen wollen | [Pflichtenheft](docs/03-pflichtenheft.md) |
| User Stories und Akzeptanzkriterien bearbeiten | [Product Backlog](docs/04-user-stories.md) |
| Aufgaben übernehmen und drei Wochen planen | [Team und Arbeitsplan](docs/05-team-und-plan.md) und [GitHub Issues](https://github.com/al3v4l3/cycle-activity-project/issues) |
| APIs und vorhandene Lösungen vergleichen | [Recherche](docs/06-recherche.md) |
| Interviews und Tests vorbereiten | [Erhebung und Qualität](docs/07-erhebung-und-qualitaet.md) |
| unsere Zwischenpräsentation vorbereiten | [Präsentationsleitfaden](docs/08-zwischenpraesentation.md) |
| eine Entscheidung oder Besprechung festhalten | [Entscheidungen](docs/entscheidungen.md), [Protokollvorlage](docs/protokolle/VORLAGE.md) |

## Ein Repository für das ganze Projekt

| Bereich | Inhalt |
| --- | --- |
| `src/` | Anwendungscode, sobald die erste Implementierungsiteration beginnt |
| `tests/` | Ausführbare Tests, passend zur später gewählten Technologie |
| `design/` | Projektbild, Abläufe, Wireframes und Entwürfe |
| `docs/` | Anforderungen, Entscheidungen, Zusammenarbeit und Projektnachweise |
| `.github/` | Vorlagen und später bei Bedarf automatisierte Prüfungen |

`src/` und `tests/` enthalten zunächst nur Orientierung. Sprache, Framework und Startbefehle werden nach der gemeinsamen Technologieentscheidung ergänzt. Die Projektstruktur wird dabei an die gewählte Technologie angepasst.

## So halten wir alles zusammen

Anforderungen stehen in den Dokumenten, Aufgaben und Ergebnisnachweise in **Issues**, der Arbeitsstatus im **Kanban-Board** und Änderungen zur gemeinsamen Prüfung in **Pull Requests**. Die Anleitung steht in [CONTRIBUTING.md](CONTRIBUTING.md). Aufgaben referenzieren die IDs der Anforderungen und User Stories, statt deren Inhalt mehrfach zu kopieren.

Als erster Produktumfang wird vorgeschlagen: Tages-Check-in, Trainingseintrag und gemeinsame Verlaufssicht. Zyklusangaben bleiben freiwillig. Das Team entscheidet den Umfang nach ersten Gesprächen. Kalorientracking, Bilderkennung und direkte Health-Anbindungen gehören vorerst in den Ideenparkplatz.

## Stand und Grenzen

- Start: 11.11.2026. Vorstellung laut Mitschrift in drei bis vier Wochen; **02.–09.12.2026 ist ein Planungsfenster**, kein bestätigter Termin. Intern zielen wir auf Vorbereitung bis 01.12.
- Der Arbeitsmodus ist ein Vorschlag für ein kleines studentisches Team mit Elementen aus Scrum. Wir behaupten keine vollständige Scrum-Einführung.
- Die [Mitschrift zur Vorstellung](docs/09-meilenstein-vorstellung.md) ist unsere konkrete Arbeitsgrundlage. Eine formale Bewertungsmatrix liegt weiterhin nicht vor; nur die verbleibenden Unklarheiten werden nachgefragt.
- Originale Moodle-Unterlagen, persönliche Gesundheitsdaten und Interviewrohmaterial werden nicht veröffentlicht. Lokal bleiben die Vorlesungsdateien im ignorierten Ordner `Vorlesungsmaterial/`.
- Dieses Gerüst wurde mit KI-Unterstützung aus den bereitgestellten Unterlagen und öffentlichen Quellen vorbereitet. Das Team prüft, überarbeitet und verantwortet die Inhalte. Vorgaben zur Kennzeichnung in der Abgabe sind noch zu klären.
- Eine Projektlizenz wählt das Team später bewusst. Vor Wiederverwendung fremder Inhalte prüfen wir deren jeweilige Lizenz.
