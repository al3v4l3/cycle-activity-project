# Wie wir Bedarf und Ergebnis prüfen

**Plan vom 18.11.2026. Noch keine Gespräche oder Produkttests durchgeführt.** Unsere [Erfolgskriterien](00-projektziel.md) müssen im Team abgestimmt werden.

## Jetzt: Unterlagen gemeinsam prüfen

Wir lesen Ziel, Anforderungen, Stories und Bild zusammen. **Vollständigkeit** heißt: Im gewählten Umfang fehlt nichts Wesentliches. **Konsistenz** heißt: Die Aussagen widersprechen sich nicht. Beispiel: Zyklusangaben dürfen nicht in einer Story freiwillig und in einer anderen Pflicht sein.

Die konkrete [Prüfliste für die Vorstellung](09-meilenstein-vorstellung.md) benutzen wir vor der Probe. Datum, Beteiligte, gefundene Punkte und Korrekturen werden notiert.

## Bedarfsgespräche, wenn wir Annahmen prüfen wollen

Zwei bis drei kurze Gespräche sind ein Vorschlag, keine bestätigte Pflichtanzahl. Wir fragen nach dem bisherigen Alltag, bevor wir unsere Lösung zeigen:

1. Wie hast du dein letztes Training festgehalten?
2. Was wolltest du später dazu wissen? Was war umständlich?
3. Welche Angaben zum Tagesbefinden wären dabei hilfreich?
4. Würdest du optionale Zyklusangaben im Ablauf erwarten? Persönliche Gesundheitsdetails brauchen wir dafür nicht.

Danach notieren wir: **Beobachtung → mögliche Anforderung → offene Frage.** Ein freundliches „würde ich nutzen“ allein bestätigt den Bedarf noch nicht. Ins öffentliche Repo kommen nur zusammengefasste Produktbedürfnisse ohne persönliche Rohdaten.

## Später: App-Funktionen testen

Alle Tests stehen zunächst auf **nicht durchgeführt**. Die Eingaberegeln im [Lastenheft](02-lastenheft.md) sind noch Vorschläge. Vor der Umsetzung bestätigen oder ändern wir sie und passen die Tests entsprechend an.

| Test | Bezug | Eingabe / Handlung | Erwartetes Ergebnis |
| --- | --- | --- | --- |
| **AT-01** | F-01, Q-04 / US-01 | Energie 3 für einen Tag speichern, erneut öffnen und ändern; denselben Tag erneut wählen; leeres Pflichtfeld und Abbruch prüfen | Richtiger Wert am richtigen Tag; Änderung bleibt erhalten; nur ein Check-in je Tag; Fehler erklärt, Abbruch legt nichts an |
| **AT-02** | F-02, Q-01 / US-02 | Check-in und Training ohne Zyklusangabe anlegen; danach freiwillige Angabe ergänzen | Kernfunktionen bleiben nutzbar; fehlend heißt „keine Angabe“; ergänzte Angabe stimmt mit Datum und Eingabe überein |
| **AT-03** | F-03 / US-03 | 1 und 30 Minuten; zusätzlich leer, 0, −1, Text, 1,5 und ein Zukunftsdatum; zwei Trainings an einem Tag; Abbruch | Gültige Trainings bleiben nach erneutem Öffnen sichtbar; ungültige Werte werden erklärt; mehrere Trainings möglich; Abbruch legt nichts an |
| **AT-04** | F-04, Q-01, Q-05 / US-04 | Künstliche Woche mit Training, Befinden, Zyklusangabe und Lücken ansehen; zusätzlich leeren Verlauf öffnen | Richtige Datumszuordnung; Lücken erkennbar; keine Phase oder Ursache erfunden; leerer Verlauf erklärt den Einstieg |
| **AT-05** | F-05, Q-04 / US-05 | Einzelnen Eintrag löschen; Gesamtlöschung abbrechen; anschließend bestätigen und erneut öffnen | Einzellöschung lässt andere Daten stehen; Abbruch ändert nichts; bestätigte Löschung entfernt die betroffenen Daten in der gewählten Speicherlösung |
| **AT-06** | F-06 / US-06 | Auf jeder vereinbarten Plattform installieren, vom Startbildschirm öffnen und im Browser nutzen | Alle drei Wege funktionieren wie dokumentiert; Gerät und Browserversion sind festgehalten |
| **AT-07** | Q-02 | Kernformular bei 375 px Breite und mit Tastatur bedienen | Aktionen erreichbar, Beschriftungen verständlich, Fokus und Fehlerhinweise erkennbar; keine horizontale Verschiebung zum Erreichen der Formularaktionen nötig |
| **AT-08** | Q-04 / US-01, US-03 | Speicherfehler gezielt auslösen, danach erneut versuchen | Verständliche Fehlermeldung statt falscher Erfolgsmeldung; Eingaben bleiben im offenen Formular erhalten; erneuter Versuch möglich |

AT-07 ist eine einfache Einstiegsprüfung, kein vollständiger Barrierefreiheitsnachweis. Ob Löschung auch ein Backend und Backups betrifft, legen wir mit der Speicherlösung fest und berücksichtigen es dann in AT-05.

## BT-01 · Ist ein Trainingseintrag einfach genug?

**Vorgeschlagener Maßstab aus Z-04:** Mindestens zwei von drei Personen schaffen die Aufgabe ohne Hilfestellung in höchstens zwei Minuten. Vor dem Test im Team bestätigen. Keine bereits gemessene Zeit und keine Dozentenvorgabe.

- Drei Personen aus der vorgesehenen Zielgruppe; frisches Formular auf dem vereinbarten Smartphone-Browser; ausschließlich künstliche Daten.
- Gleiche Aufgabe: „Du hast gestern 30 Minuten Krafttraining gemacht. Halte das fest, ohne Zyklusangaben zu machen, und finde den Eintrag wieder.“
- Zeit ab Übergabe der Aufgabe bis zum richtigen Wiederfinden messen. Als Erfolg zählt nur ein korrekt angelegter und wiedergefundener Eintrag.
- Nicht den Klickweg erklären. Nötige Hilfen, Umwege und Abbruch notieren. Hilfestellung zählt bei diesem Maßstab nicht als Erfolg ohne Hilfe.
- Ergebnis und Änderung festhalten. Bei einer Wiederholung die neue Version nennen.

Ein Klickprototyp kann diesen Bedienablauf nur simulieren. Echte Speicherung wird zusätzlich technisch getestet. Wenige Personen helfen, Probleme zu finden; sie belegen keine allgemeine Wirksamkeit.

## Q-03 · Datenprüfung

Vor einer Veröffentlichung Dateien, Screenshots und Beispieldaten ansehen: keine echten Gesundheitsdaten, Interviewrohnotizen oder Zugangsdaten. Ergebnis mit Datum und geprüfter Version notieren.

## Vorlage für jedes Prüfergebnis

| Datum / Version / Gerät | Test-ID | Tatsächliches Ergebnis | Status | Nachweis / nächste Änderung |
| --- | --- | --- | --- | --- |
| noch offen | noch offen | nicht geprüft | nicht durchgeführt | offen |

Ein Test wird erst nach tatsächlicher Durchführung als bestanden markiert. Fehler werden mit Schritten, erwartetem und tatsächlichem Verhalten im Issue festgehalten.
