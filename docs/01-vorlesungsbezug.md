# Was wir aus der Vorlesung übernehmen

Auswertung vom 11.11.2026. Quellen sind die lokal bereitgestellten Lehrunterlagen. Dateinamen, Foliennummern und Zellbereiche dienen zum Nachschlagen in euren eigenen Moodle-Kopien. Die Originale werden nicht ins öffentliche Repository übernommen. Die Übersicht fasst Inhalte in eigenen Worten zusammen.

**Lehrinhalt ist keine bestätigte Abgabevorschrift.** Ein gesondertes Aufgabenblatt oder eine Bewertungsmatrix wurde in den bereitgestellten Dateien nicht identifiziert. Insbesondere können wir daraus weder zwei umfangreiche Hefte noch eine bestimmte Anzahl von Diagrammen als verpflichtend erklären.

## Die entscheidenden Fundstellen

| Lehrinhalt | Fundstelle | Unsere Anwendung |
| --- | --- | --- |
| Bedarf vor Entwurf; frühes Feedback über Prototypen | `Software Engineering Folien.ppt`, Folien 2–4 | Erst Problem und Anforderungen klären, dann Abläufe skizzieren und prüfen |
| Funktionale Anforderungen beschreiben Leistungen aus Benutzersicht; Anforderungen einzeln und konsistent formulieren | gleiche Datei, Folien 16–18 | Getrennte Anforderungs-IDs, klare Akzeptanzkriterien, gegenseitige Prüfung |
| Funktionale und nichtfunktionale Anforderungen unterscheiden | `Requirements_Planung_Schätzung.xls`, `Tabelle1!B3:K16` | Funktionen und Qualitätsanforderungen im Lastenheft getrennt |
| User Stories aus Pflichtenheft oder bei kleinen Projekten direkt aus Interviews, Beobachtungen, Fragebogen ableiten | gleiche Datei, `Tabelle1!C142:F159` | Kleine Bedarfserhebung, danach priorisiertes Backlog; kein monatelanger Dokumentationsvorlauf |
| Story besitzt Titel, Beschreibung, Aufwand, Priorität | gleiche Datei, `Tabelle1!D149:F159`; `Templates!B4:B12` | Story-Vorlage und GitHub-Issue-Vorlage |
| Tasks zerlegen eine Story und haben eine verantwortliche Person, Beschreibung und Aufwand | gleiche Datei, `Tabelle1!C161:F188` | Eine Person führt die Aufgabe, eine andere prüft das Ergebnis |
| Schätzungen gemeinsam begründen, Annahmen klären und große Stories teilen | gleiche Datei, `Tabelle1!C191:F216` | Schätzung im Team, zunächst Personenstunden; Unsicherheit offenlassen |
| Iterationen liefern Ergebnisse und erhalten Feedback; Umfang an Kapazität anpassen | gleiche Datei, `Tabelle1!C217:K288` und `F311:K347` | Drei kurze Arbeitswochen mit Reviews; Puffer und begrenzter Umfang |
| Aufgaben müssen zusammen die Story abdecken; Schätzung aus Tasks verbessern | gleiche Datei, `Tabelle1!F485:H501` | Verknüpfung von Story, Aufgaben und Abnahmekriterien |
| Rollen, Planning, Review, Retro, Backlogs, DoR und DoD | `Scrum Handout.docx`, Abschnitte „Scrum Framework“, „Definitionen Rollen“, „Scrum Meetings“, „Definitionen Artefakte und Werkzeuge“ | Prioritätenverantwortung, kurze Planung, Ergebnisreview und Prozessreflexion |
| Rolle, Funktion und Nutzen; INVEST; kleine vertikale Stories | gleiche Datei, Abschnitte „Was ist eine gute User Story?“ und „User Story vertikal formulieren“ | Nutzbarer Ablauf je Story, technische Arbeiten als untergeordnete Tasks |
| Nutzungskontext, Prototyping und Evaluation gehören zusammen | `UE Handout.docx`, „Usability Engineering“, „Konzeptionsphasen“, „Prototypen erstellen“, „Thinking aloud“ | Papier- oder Klickprototyp mit wenigen Personen prüfen und Änderungen dokumentieren |
| Use Cases ergänzen erfasste Anforderungen | `UML2.xls`, `Skript!B2848:B2859` | Ein relevanter Use Case nach der Bedarfsklärung; Diagramme bei konkretem Erklärungsbedarf |
| Tests aus Spezifikation ableiten; gültige, ungültige und Grenzfälle betrachten | `Testen.xls`, `Tabelle1!C85:D88`, `D169:D187` | Akzeptanzfälle schon in der Planung festhalten |

Zelladressen beziehen sich auf die aus den Originaldateien gelesenen Tabellen. Zeichnungen und eingebettete Bilder sind nicht Grundlage der Aussagen in dieser Tabelle.

## Lastenheft, Pflichtenheft und User Stories

Für dieses Projekt verwenden wir folgende **praktische Arbeitsaufteilung**:

- **Lastenheft:** Welches Problem hat welche Zielgruppe? Was soll die App leisten, mit welchen Grenzen und Qualitätszielen?
- **Pflichtenheft:** Wie soll die ausgewählte Lösung diese Anforderungen erfüllen? Hier stehen Abläufe, Daten, Architekturentscheidungen und Abnahmebezüge.
- **User Stories:** Kleine Nutzerbedürfnisse, die wir priorisieren und mit Akzeptanzkriterien bearbeiten können.
- **Tasks:** Konkrete Arbeitsschritte zur Klärung oder Umsetzung einer Story, jeweils mit Verantwortung und Aufwand.

Die Tabelle erwähnt das Pflichtenheft ausdrücklich. Eine eigenständige Lastenheftpflicht konnten wir in den ausgewerteten Texten nicht feststellen. Die beiden kurzen Dokumente sind daher eine sinnvolle Ordnung für euren Wunsch, **keine behauptete Prüfungsauflage**. Wenn die Lehrperson andere Formate verlangt, passen wir sie an.

## Unser vorgeschlagener Prozess

Wir kombinieren eine kurze Anforderungsklärung mit wöchentlichen Planungs- und Feedbackschleifen. Das ist ein kleines hybrides Vorgehen, passend zum in `Tabelle1!I20:J22` beschriebenen Einsatz von Hybridmodellen.

Scrum liefert nützliche Begriffe und Abläufe. Weil wir zunächst Planung und Prototypen bearbeiten und keine täglichen Scrum-Termine festgelegt haben, nennen wir das **„iteratives Vorgehen mit Scrum-Elementen“**. Ein Dokumentenpaket oder Papierprototyp wird nicht als fertiges Software-Inkrement ausgegeben. DoR ist laut Handout eine ergänzende Vereinbarung, kein offizieller Bestandteil des Scrum Guides.

Die Vorlesungstabelle schätzt in Stunden/Tagen, das Scrum-Handout behandelt auch Story Points. Wir starten in Personenstunden, weil wir neben dem Studium reale Kapazität planen müssen. Das ist eine Teamempfehlung, keine Umrechnung von Story Points in Stunden. Den beispielhaften V-Faktor 0,7 der Vorlesung übernehmen wir nicht ungeprüft als gemessene Teamleistung.

MVC, Entwurfsmuster, Sequenz- und Zustandsdiagramme sind im Material ebenfalls vorhanden. Ihre konkrete Anwendung entscheiden wir beim Entwurf. Heute ist ein verständlicher Nutzerablauf wertvoller als vorsorglich alle Diagrammarten auszufüllen.
