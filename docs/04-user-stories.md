# Product Backlog · User Stories

**Stand: Entwurf 11.11.2026.** Die Stories wurden aus der Projektidee abgeleitet, nicht aus abgeschlossenen Interviews. Prioritäten sind Vorschläge. Alle Stories sind ungeschätzt und nicht umgesetzt; das Team schätzt nach Klärung der Akzeptanzkriterien. Recherche- und Dokumentationsaufgaben im Arbeitsplan sind davon getrennt.

| ID | Thema | Anforderung | Prio | Aufwand | Status |
| --- | --- | --- | --- | --- | --- |
| US-01 | Tagesbefinden erfassen | F-01 | 10 | offen | Entwurf |
| US-02 | Zyklusangaben freiwillig ergänzen | F-02, Q-01 | 10 | offen | Entwurf |
| US-03 | Training dokumentieren | F-03 | 10 | offen | Entwurf |
| US-04 | Gemeinsamen Verlauf ansehen | F-04, Q-05 | 10 | offen | Entwurf |
| US-05 | Eigene Einträge löschen | F-05 | 10 | offen | Entwurf |
| US-06 | Zum Startbildschirm hinzufügen | F-06 | 20 | offen | Entwurf |

Priorität 10 bedeutet „für den ausgewählten Kern wichtig“, nicht „alles passt automatisch in die erste Woche“. US-06 kann für eine PWA-Demo höher priorisiert werden. Vor Planung Aufwand und Kapazität abgleichen.

## Backlog und Kanban

Die obige Reihenfolge ist der vorgeschlagene Produktteil des Backlogs. Notwendige Projekt- und Qualitätsaufgaben stehen ergänzend in den [verknüpften Issues im Teamplan](05-team-und-plan.md). Für M1 werden Stories und Tasks gemeinsam priorisiert und geschätzt. Das Kanban-Board zeigt den aktuellen Arbeitsstatus; Anforderungen und Akzeptanzkriterien bleiben hier versioniert.

## US-01 · Tagesbefinden erfassen

**Als trainierende Nutzerin möchte ich mein Tagesbefinden kurz festhalten, damit ich mein Training später in diesem Kontext betrachten kann.**

Akzeptanzkriterien für die spätere App:

- Für einen gewählten Tag kann ich Energie von 1 bis 5 auswählen; die Endpunkte sind erklärt.
- Ohne Zyklusangaben kann ich den Check-in abschließen.
- Nach Speichern und erneutem Öffnen sehe ich den Eintrag für den richtigen Tag.
- Fehlende Pflichtangaben erzeugen einen verständlichen Hinweis, ohne meine übrigen Eingaben zu verwerfen.
- Breche ich ab, wird kein Eintrag angelegt.

Offen: Ist diese Skala für die Zielgruppe sinnvoll? Welche weiteren Angaben sind wirklich nötig? Vorschlag: ein bearbeitbarer Check-in je Tag, im Team bestätigen.

**Nächste Aufgaben zur Klärung:** Eingaben im Interview prüfen, Formular skizzieren, Erfolgs- und Fehlerfall durchgehen. **Spätere Umsetzungstasks, noch nicht beauftragt:** Eingaberegeln, Oberfläche und Speicherung umsetzen; AT-01 und AT-08 durchführen. Jede Task erhält eigene Aufwandsschätzung und Verantwortung. Nutzenprüfung: Testpersonen können den Eintrag selbstständig erstellen und wiederfinden.

## US-02 · Zyklusangaben freiwillig ergänzen

**Als Nutzerin möchte ich Zyklusangaben freiwillig ergänzen oder weglassen können, damit ich selbst bestimme, welche Informationen ich für meinen Verlauf nutze.**

- Ich kann für einen Tag eine beobachtete Blutung dokumentieren; weitere Felder werden erst nach Bedarfsklärung ergänzt.
- Überspringen verhindert weder Trainingseintrag noch Tages-Check-in.
- Ein fehlender Eintrag erscheint als „keine Angabe“, nicht als „keine Blutung“ oder bestimmte Zyklusphase.
- Gespeicherte Angaben sind für den richtigen Tag sichtbar und gemäß US-05 löschbar.

Offen: Welche Bezeichnungen sind verständlich? Ist diese Art der Erfassung überhaupt gewünscht? Keine automatische Phasenvorhersage im ersten Umfang. Nutzenprüfung: Testperson findet die freiwillige Option und versteht das Überspringen.

## US-03 · Training dokumentieren

**Als Freizeitsportlerin möchte ich eine absolvierte Trainingseinheit dokumentieren, damit ich meine Aktivität nachvollziehen kann.**

- Ich kann Datum, Sportart und Dauer in Minuten erfassen.
- Eine Dauer größer als null ist gültig; null, negative Werte oder nichtnumerische Eingaben führen zu einem verständlichen Fehlerhinweis.
- Ein gespeicherter Eintrag erscheint mit den eingegebenen Werten; Abbruch erzeugt keinen Eintrag.
- Ich kann das Training ohne Zyklusangaben erfassen.

Offen: Ganze oder auch halbe Minuten? Datum in der Zukunft? Belastungsskala? Benötigt Krafttraining bereits Sätze und Gewichte? Das Team klärt diese Regeln vor der Implementierung. Nutzenprüfung: Ein typisches Training lässt sich ohne erklärende Hilfe abbilden.

## US-04 · Training und Befinden gemeinsam ansehen

**Als Nutzerin möchte ich Training und Befinden für denselben Zeitraum betrachten, damit ich meine eigenen Einträge vergleichen kann.**

- Für einen ausgewählten Zeitraum stehen Training und Tagesbefinden erkennbar beim jeweiligen Datum.
- Optionale Zyklusangaben können im selben Zusammenhang angezeigt werden.
- Tage ohne Eintrag sind eindeutig von eingetragenen Werten unterscheidbar.
- Die Darstellung behauptet keine Ursache für Leistungsunterschiede und erzeugt keine unbestätigte Phasenzuordnung.
- Ein leerer Verlauf erklärt, wie ich den ersten Eintrag anlege.

Offen: Liste oder Kalender? Woche als Standard? Nutzenprüfung: Testperson findet einen bestimmten Tag und kann erklären, welche Angaben vorhanden sind und welche fehlen.

## US-05 · Einträge löschen

**Als Nutzerin möchte ich einzelne und alle eigenen Einträge löschen können, damit ich die Kontrolle über meine gespeicherten Angaben behalte.**

- Ich kann einen einzelnen Eintrag löschen; andere Einträge bleiben erhalten.
- Vor dem Löschen aller Daten wird die Reichweite erklärt und eine Bestätigung verlangt.
- Abbrechen der Bestätigung verändert keine Daten.
- Nach bestätigter Löschung und erneutem Öffnen sind die betroffenen Einträge in der gewählten Speicherlösung nicht mehr verfügbar.

Offen: Speicherung und Umgang mit eventuellen Backups zuerst entscheiden. Nutzenprüfung: Testperson versteht den Unterschied zwischen Einzel- und Gesamtlöschung. Die Prototypprüfung belegt nur Verständlichkeit; technische Löschung braucht später einen eigenen Nachweis.

## US-06 · App vom Startbildschirm öffnen

**Als Smartphone-Nutzerin möchte ich die Web-App zum Startbildschirm hinzufügen, damit ich schnell auf mein Trainingstagebuch zugreifen kann.**

- Auf den vom Team festgelegten unterstützten Geräten funktioniert die dokumentierte Installation.
- Nach Installation kann ich die App über ihr Symbol öffnen.
- Wenn kein programmatischer Installationsdialog verfügbar ist, erhalte ich eine passende manuelle Anleitung.
- Die App bleibt ohne Installation im Browser nutzbar.

Offen: Konkrete Geräte und Browser dokumentieren; iOS und Android nicht als identisch voraussetzen. Ein Manifest allein belegt nicht die Funktion auf realen Geräten. Nutzenprüfung: Installationsversuch je unterstützter Plattform protokollieren.

## Ideenparkplatz

Ernährung und Barcode-Suche, Übungskatalog, HealthKit, Flo, Wearables, Trainingsempfehlungen und KI-Funktionen. **Noch keine Lieferzusagen.** Neue Idee zuerst mit konkretem Nutzerproblem, Nutzen, Abhängigkeit und Aufwand erfassen. Eine API wird nicht allein deshalb eingebaut, weil sie verfügbar ist.

## Vorlage für weitere Stories

ID / Titel / Anforderungsbezug / Status / Priorität / Aufwand mit Einheit / Annahmen / Verantwortliche Person / Prüfung / Issue-Link.

„Als … möchte ich …, damit …“

Prüfbare Akzeptanzkriterien, mindestens ein Fehler- oder Leerfall, Nutzenprüfung, offene Fragen und verknüpfte Tasks ergänzen. Als Einstieg steht auch eine [GitHub-Vorlage](../.github/ISSUE_TEMPLATE/user-story.yml) bereit. Die freigegebene Story steht hier; das Issue hält Zuständigkeit und Bearbeitungsstand.
