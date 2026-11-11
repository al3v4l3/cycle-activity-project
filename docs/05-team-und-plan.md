# Team und Arbeitsplan

**Aktualisiert am 11.11.2026 anhand der Team-Mitschrift.** Vier Personen; Vorstellung in drei bis vier Wochen, vorläufig 02.–09.12.2026. Interne Vorbereitung bis 01.12. Die erste Implementierungsiteration folgt nach der Vorstellung gegen Semesterende. [M1-Checkliste](09-meilenstein-vorstellung.md).

## Zuständigkeiten

| Bereich | Verantwortliche Person | Prüfung durch | Beitrag |
| --- | --- | --- | --- |
| A · Bedarf und Nutzerkontakt | offen | B | Interviews, Erkenntnisse, Rückfragen |
| B · Anforderungen und Prioritäten | offen | D | Lastenheft, Stories, Umfang; vorgeschlagene PO-Ansprechperson |
| C · Machbarkeit und Wiederverwendung | offen | A | APIs, PWA-Grenzen, Architekturvorschlag |
| D · Ablauf, Qualität und Organisation | offen | C | Skizzen, Tests, Protokolle; vorgeschlagene Moderation |

Personen wählen Aufgaben selbst im gemeinsamen Planning. Rollen sind Ansprechpartner, keine exklusiven Wissensbereiche. Alle vier lesen und prüfen den Kernablauf. Die Fitnesserfahrung aus dem Team ist nützlich für Fragen und Beispiele; sie ersetzt keine Rückmeldung der Zielgruppe.

GitHub-Nutzernamen und konkrete Zuordnung fehlen noch. **Es wurden keine Einladungen oder personengebundenen Zuweisungen vorgenommen.**

## Zeitplanung

| Person | Verfügbare Stunden W1 | W2 | W3 | Abwesenheiten / Rahmenbedingungen |
| --- | --- | --- | --- | --- |
| A | offen | offen | offen | offen |
| B | offen | offen | offen | offen |
| C | offen | offen | offen | offen |
| D | offen | offen | offen | offen |

**Beispiel, keine Teamzusage:** Vier Personen mit je vier Stunden pro Woche ergeben 16 Personenstunden. Bei 25 Prozent Puffer planen wir höchstens 12 Stunden konkrete Arbeit einschließlich Treffen, Reviews und Dokumentation. Danach wird mit euren echten Angaben gerechnet. Verfügbarkeit und Aufgabenaufwand dürfen nicht beide noch einmal um denselben Puffer reduziert werden.

## Bis zur Vorstellung und danach

| Zeitraum | Ziel | Ergebnis |
| --- | --- | --- |
| W1: 11.–17.11. | Grundlage und Zusammenarbeit | Einleitung/Motivation in Prosa, Zielgruppe, Anforderungsentwurf, gemeinsame Kommunikationsregeln und eingerichtetes Kanban-Board |
| W2: 18.–24.11. | Anforderungen konkretisieren und priorisieren | User Stories, geordnetes Product Backlog, Aufgabenzerlegung, grobe Schätzung, Technologie-/KI-Auswahl und einfache Visualisierung |
| W3: 25.11.–01.12. | Vollständigkeit und Konsistenz prüfen | Widersprüche bereinigt, M1-Checkliste gemeinsam geprüft, Bild und Präsentation vorbereitet, Probe durchgeführt |
| Vorstellung: vorläufig 02.–09.12. | Projekt und Vorgehen vorstellen | Umfang, Prioritäten, Organisation, Technologieentscheidung und nächste Iteration erklären |
| Nach Vorstellung, gegen Semesterende | Erste Implementierungsiteration | Feedback einarbeiten; ausgewählten Kernablauf im selben Repo entwickeln und testen; Termin und Umfang noch entscheiden |

Kurze Gespräche und Prototypentests können Entscheidungen verbessern, sind laut Mitschrift aber keine eigenen Pflichtabgaben für M1. Die Visualisierung der Idee ist vorgesehen; ein vollständig getesteter Klickprototyp wird nicht automatisch verlangt.

## Kanban-Board

[Board öffnen](https://github.com/users/al3v4l3/projects/1). **Backlog** sammelt offene Arbeit; **Ready** enthält gemeinsam geklärte Aufgaben; **In progress** bedeutet in Bearbeitung; **In review** wartet auf die zweite Prüfung; **Done** erfüllt die Fertig-Kriterien. Die Vorlage enthält Limits für gleichzeitig bearbeitete bzw. geprüfte Aufgaben; diese im Team abstimmen. Alle Aufgaben starten im Backlog, bis ihr sie gemeinsam übernehmt.

## Erste Aufgaben

Der aktuelle Status steht auf dem Kanban-Board; die Tabelle beschreibt den geplanten Aufgabenbestand. Aufwand ist ein grober Startbereich in **Personenstunden insgesamt**, nicht je beteiligter Person. Interviews, Reviews und Nacharbeit sind einzuplanen. Vor Übernahme schätzt das Team selbst; nicht alle Aufgaben müssen gleichzeitig begonnen werden.

| ID | Aufgabe / Ergebnis | Verantwortung | Prio | Startschätzung | Voraussetzung |
| --- | --- | --- | --- | --- | --- |
| [T-01](https://github.com/al3v4l3/cycle-activity-project/issues/1) | Teamstart: Zielgruppe, Kernablauf, Rollen, verfügbare Zeit und nächstes Treffen festhalten | alle, D moderiert | 10 | 4 h für 4 × 1 h | keine |
| [T-02](https://github.com/al3v4l3/cycle-activity-project/issues/2) | Abgabevorgaben und Präsentation klären; Antworten mit Quelle erfassen | B | 10 | 0,5–1 h | keine |
| [T-03](https://github.com/al3v4l3/cycle-activity-project/issues/3) | Zwei bis drei Bedarfsgespräche durchführen und Erkenntnisse zusammenfassen | A | 20 | 2–4 h | [T-01](https://github.com/al3v4l3/cycle-activity-project/issues/1) |
| [T-04](https://github.com/al3v4l3/cycle-activity-project/issues/4) | Drei Vergleichsangebote untersuchen und API-/PWA-Grenzen bewerten | C | 10 | 2–3 h | [T-01](https://github.com/al3v4l3/cycle-activity-project/issues/1) |
| [T-05](https://github.com/al3v4l3/cycle-activity-project/issues/5) | Anforderungen und Kernstories prüfen, priorisieren und mit verfügbaren Erkenntnissen abgleichen | B | 10 | 2–3 h | T-01; T-03/T-04 liefern ergänzende Erkenntnisse |
| [T-06](https://github.com/al3v4l3/cycle-activity-project/issues/6) | Ein erklärendes Projektbild oder einfache Wireframes erstellen | D | 10 | 1–3 h | [T-05](https://github.com/al3v4l3/cycle-activity-project/issues/5) |
| [T-07](https://github.com/al3v4l3/cycle-activity-project/issues/7) | Programmiersprache, Werkzeuge und KI-Unterstützung auswählen; Lösungsentwurf angleichen | C | 10 | 2–3 h | T-05, Abstimmung mit T-06 |
| [T-08](https://github.com/al3v4l3/cycle-activity-project/issues/8) | Optional: Skizze/Prototyp mit zwei bis drei Personen prüfen | A, D prüft | 50 | 3–5 h | T-06, Testaufgaben |
| [T-09](https://github.com/al3v4l3/cycle-activity-project/issues/9) | Wöchentliche Planung, Review und Retro dokumentieren | D moderiert, alle | 10 | 2,5–3,5 h je Woche insgesamt | feste Termine |
| [T-10](https://github.com/al3v4l3/cycle-activity-project/issues/10) | Zwischenpräsentation aus echten Nachweisen erstellen und proben | D, alle liefern Beiträge | 10 | 4–6 h insgesamt | Ergebnisse aus W1–W3 |
| [T-11](https://github.com/al3v4l3/cycle-activity-project/issues/11) | Einleitung und Motivation in Prosa gemeinsam fertigstellen | A, B prüft | 10 | 1–2 h | T-01 |
| [T-12](https://github.com/al3v4l3/cycle-activity-project/issues/12) | Kanban und Kommunikationsregeln im Team vereinbaren | D, alle | 10 | 1–2 h | T-01 |
| [T-13](https://github.com/al3v4l3/cycle-activity-project/issues/13) | Anforderungen und Backlog auf Vollständigkeit und Konsistenz prüfen | B, C prüft | 10 | 1–2 h | T-05; vor T-10 |

**Fertig-Kriterien und ausführliche Arbeitsschritte stehen in den jeweiligen GitHub Issues.** Diese Tabelle ist die Startübersicht; den laufenden Status pflegen wir ausschließlich im Kanban-Board. Inhalt, Kriterien und Nachweise stehen im Issue. Die wiederkehrende Aufgabe T-09 wird pro Woche abgehakt und bleibt bis zur dritten Woche offen.

## Fragen an die Lehrperson

Verantwortung T-02. Fragen hier vorbereiten; sie wurden noch nicht versendet.

1. Gibt es ergänzend zur Mitschrift eine Bewertungsmatrix oder ein offizielles Aufgabenblatt?
2. Was genau ist mit „Detailmanagement“ und „mit Bild“ gemeint? Werden bestimmte Dokumentformate oder Diagramme erwartet?
3. Welcher Termin innerhalb der genannten drei bis vier Wochen und welche Dauer gelten für die Vorstellung? Wann beginnt die erste Implementierungsiteration gegen Semesterende?
4. Ist mit „KI raussuchen“ ein Entwicklungswerkzeug, eine Produktfunktion oder beides gemeint?
5. Welche Vorgaben gelten für Bibliotheken, APIs, übernommene Repositories und die Kennzeichnung von KI-Unterstützung?
6. Wie werden individuelle Beiträge sichtbar gemacht und wann ist die finale Abgabe?

Antworten mit Datum und Fundstelle protokollieren. Eine unbeantwortete Frage bleibt offen und wird nicht als Zustimmung interpretiert.

## Logistik und Kommunikation

| Vereinbarung | Vorschlag | Teamentscheidung |
| --- | --- | --- |
| Kurze Abstimmungen | ein gemeinsamer Gruppenchat, dessen Dienst das Team festlegt | Kanal/Link offen |
| Verbindliche Aufgaben und Entscheidungen | Issues, Kanban-Board und versionierte Dokumente in diesem Repo | Namen und Zugriff noch eintragen |
| Regelmäßiges Treffen | einmal wöchentlich ca. 45 Minuten | Wochentag, Uhrzeit und Ort/Call-Link offen |
| Rückmeldung | an vereinbarten Arbeitstagen innerhalb von 24 Stunden; bei Verhinderung kurz Bescheid geben | bestätigen oder anpassen |
| Hindernisse | früh im zuständigen Issue benennen und im Gruppenchat auf Klärungsbedarf hinweisen | Verantwortliche Person bleibt Ansprechperson |
| Übergabe | Ergebnislink, offener Punkt und nächster Schritt; zweite Person prüft | Vertretung je Aufgabe vereinbaren |

Dieser Projektchat unterstützt die gemeinsame Arbeit. Ergebnisse für das gesamte Team werden im Repository festgehalten; der Chat ersetzt keinen für alle zugänglichen Projektstand.

## Zusammenarbeit und Qualitätsvereinbarung

Wöchentliches Planning ca. 20 Minuten, Review ca. 15 Minuten, Retro ca. 10 Minuten; bei vier Personen zusammen etwa drei Personenstunden. Konkrete Zeiten legt das Team fest. Kurze asynchrone Updates zwischen den Treffen nennen Ergebnis, nächsten Schritt und Hindernis. Das ist eine Anpassung an studentische Verfügbarkeit, kein als vollständig ausgegebenes Scrum.

**Ready:** Nutzen und Ergebnis klar, offene Kernfragen benannt, Akzeptanzkriterien vorhanden, Abhängigkeiten verstanden, Aufwand gemeinsam geschätzt, verantwortliche Person gewählt.

**Done für Planungsaufgaben:** Ergebnis verlinkt, Kriterien erfüllt, zweite Person hat geprüft, Quellen und Annahmen sind erkennbar, Änderungen im zuständigen Dokument übernommen. Bei einem Dokumenten-PR heißt „Done“: Dokument geprüft; die darin beschriebene Software ist dadurch nicht implementiert.

**Später für Software zusätzlich:** passende Tests durchgeführt, Akzeptanzkriterien nachgewiesen, Dokumentation aktualisiert. „Done“ bedeutet nie nur „ich habe daran gearbeitet“.

Nach jedem Review: Eine Erkenntnis, eine dadurch geänderte Entscheidung und höchstens eine konkrete Verbesserung der Zusammenarbeit für die nächste Woche festhalten.
