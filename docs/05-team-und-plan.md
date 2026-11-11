# Team und Arbeitsplan

**Planungsvorschlag vom 11.11.2026 für vier Personen.** Rollen, Stunden und Termine werden gemeinsam bestätigt. Der 02.12.2026 dient vorläufig als Orientierung für „in drei Wochen“.

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

## Drei Arbeitswochen

| Zeitraum | Ziel | Geplante Ergebnisse | Review |
| --- | --- | --- | --- |
| W1: 11.–17.11. | Problem und Umfang verstehen | Teamvereinbarung, geklärte Abgabefragen soweit beantwortet, erste Interviews, Lastenheft v0.2, priorisierte Stories | Was hat sich an unserer Ausgangsidee geändert? |
| W2: 18.–24.11. | Kernablauf konkretisieren | Papier-/Klickprototyp, schlankes Pflichtenheft, begründete API-Auswahl oder bewusster Verzicht, Testablauf | Können andere den Ablauf verstehen? |
| W3: 25.11.–01.12. | Rückmeldung einarbeiten und Vorgehen belegen | Testbeobachtungen, überarbeiteter Ablauf, aktualisiertes Backlog, Präsentationsprobe | Was ist tatsächlich fertig, was bleibt offen? |
| Vorläufig 02.12. | Zwischenstand präsentieren | Nachvollziehbare Entwicklung mit Beispielen und nächstem Schritt | Termin und Dauer noch bestätigen |

Das ist ein Vorschlag für den jetzigen Planungsstart. Falls die Lehrperson für den Zwischenstand bereits lauffähige Software verlangt, muss das Team Umfang und Zeitplan unmittelbar ändern. Codieren ist heute nicht Teil des Auftrags.

## Erste Aufgaben

Alle Status sind **offen**. Aufwand ist ein grober Startbereich in **Personenstunden insgesamt**, nicht je beteiligter Person. Interviews, Reviews und Nacharbeit sind einzuplanen. Vor Übernahme schätzt das Team selbst; nicht alle Aufgaben müssen gleichzeitig begonnen werden.

| ID | Aufgabe / Ergebnis | Verantwortung | Prio | Startschätzung | Voraussetzung |
| --- | --- | --- | --- | --- | --- |
| T-01 | Teamstart: Zielgruppe, Kernablauf, Rollen, verfügbare Zeit und nächstes Treffen festhalten | alle, D moderiert | 10 | 4 h für 4 × 1 h | keine |
| T-02 | Abgabevorgaben und Präsentation klären; Antworten mit Quelle erfassen | B | 10 | 0,5–1 h | keine |
| T-03 | Zwei bis drei Bedarfsgespräche durchführen und Erkenntnisse zusammenfassen | A | 10 | 2–4 h | T-01 |
| T-04 | Drei Vergleichsangebote untersuchen und API-/PWA-Grenzen bewerten | C | 10 | 2–3 h | T-01 |
| T-05 | Lastenheft und Kernstories anhand T-03/T-04 überarbeiten und priorisieren | B | 10 | 2–3 h | T-03, T-04 |
| T-06 | Drei bis fünf grobe Bildschirme für den Kernablauf erstellen | D | 10 | 2–4 h | T-05 |
| T-07 | Pflichtenheft, Datenmodell und Lösungsentscheidung konkretisieren | C | 20 | 2–3 h | T-05, Abstimmung mit T-06 |
| T-08 | Prototyp mit zwei bis drei Personen prüfen, Probleme und Änderungen festhalten | A, D prüft | 10 | 3–5 h | T-06, Testaufgaben |
| T-09 | Wöchentliche Planung, Review und Retro dokumentieren | D moderiert, alle | 10 | 2,5–3,5 h je Woche insgesamt | feste Termine |
| T-10 | Zwischenpräsentation aus echten Nachweisen erstellen und proben | D, alle liefern Beiträge | 10 | 4–6 h insgesamt | Ergebnisse aus W1–W3 |

**Fertig-Kriterien und ausführliche Arbeitsschritte stehen in den jeweiligen GitHub Issues.** Diese Tabelle ist die Startübersicht; den laufenden Aufgabenstatus pflegen wir ausschließlich dort. Die wiederkehrende Aufgabe T-09 wird pro Woche abgehakt und bleibt bis zur dritten Woche offen.

## Fragen an die Lehrperson

Verantwortung T-02. Fragen hier vorbereiten; sie wurden noch nicht versendet.

1. Was genau wird benotet: Produkt, Dokumentation, Prozess und/oder Präsentation? Gibt es eine Bewertungsmatrix?
2. Welche Artefakte sind verpflichtend: Lastenheft, Pflichtenheft, Stories, UML, Testdokumentation? Welcher Umfang?
3. Wann ist die Zwischenpräsentation, wie lange dauert sie und wird bereits lauffähige Software erwartet?
4. Ist ein begründetes hybrides Vorgehen zulässig oder wird ein bestimmter Prozess verlangt?
5. Welche Vorgaben gelten für Bibliotheken, APIs, übernommene Repositories und die Kennzeichnung von KI-Unterstützung?
6. Wie werden individuelle Beiträge sichtbar gemacht und wann ist die finale Abgabe?

Antworten mit Datum und Fundstelle protokollieren. Eine unbeantwortete Frage bleibt offen und wird nicht als Zustimmung interpretiert.

## Zusammenarbeit und Qualitätsvereinbarung

Wöchentliches Planning ca. 20 Minuten, Review ca. 15 Minuten, Retro ca. 10 Minuten; bei vier Personen zusammen etwa drei Personenstunden. Konkrete Zeiten legt das Team fest. Kurze asynchrone Updates zwischen den Treffen nennen Ergebnis, nächsten Schritt und Hindernis. Das ist eine Anpassung an studentische Verfügbarkeit, kein als vollständig ausgegebenes Scrum.

**Ready:** Nutzen und Ergebnis klar, offene Kernfragen benannt, Akzeptanzkriterien vorhanden, Abhängigkeiten verstanden, Aufwand gemeinsam geschätzt, verantwortliche Person gewählt.

**Done für Planungsaufgaben:** Ergebnis verlinkt, Kriterien erfüllt, zweite Person hat geprüft, Quellen und Annahmen sind erkennbar, Änderungen im zuständigen Dokument übernommen. Bei einem Dokumenten-PR heißt „Done“: Dokument geprüft; die darin beschriebene Software ist dadurch nicht implementiert.

**Später für Software zusätzlich:** passende Tests durchgeführt, Akzeptanzkriterien nachgewiesen, Dokumentation aktualisiert. „Done“ bedeutet nie nur „ich habe daran gearbeitet“.

Nach jedem Review: Eine Erkenntnis, eine dadurch geänderte Entscheidung und höchstens eine konkrete Verbesserung der Zusammenarbeit für die nächste Woche festhalten.
