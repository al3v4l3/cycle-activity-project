# User Stories und Product Backlog

**Entwurf vom 18.11.2026. Noch nicht umgesetzt und noch nicht im Team geschätzt.** Die Stories stammen aus unserer Idee. Zielgruppe, Regeln und Prioritäten werden gemeinsam geprüft.

Eine **User Story** beschreibt, was eine Nutzerin möchte und wozu. Die **Kriterien** darunter sagen, wann die Funktion erfüllt ist. **Tasks** sind die einzelnen Arbeitsschritte dafür. Das **Backlog** ist unsere geordnete Liste.

## Vorgeschlagene Reihenfolge für die spätere Umsetzung

| Reihenfolge | Story | Bezug | Prio | Aufwand | Stand |
| --- | --- | --- | --- | --- | --- |
| 1 | US-03 · Training eintragen | F-03 | 10 | im Team schätzen | Entwurf |
| 2 | US-01 · Tagesbefinden festhalten | F-01 | 10 | im Team schätzen | Entwurf |
| 3 | US-04 · Verlauf ansehen | F-04 | 10 | im Team schätzen | Entwurf |
| 4 | US-02 · Zyklusangabe freiwillig ergänzen | F-02, Q-01 | 10 | im Team schätzen | Entwurf |
| 5 | US-05 · Einträge löschen | F-05 | 10 | im Team schätzen | Entwurf |
| 6 | US-06 · Vom Startbildschirm öffnen | F-06 | 20 | im Team schätzen | Entwurf |

Wir starten mit einem kleinen durchgängigen Ablauf. US-03 braucht deshalb schon eine einfache Anzeige des gespeicherten Trainings. US-04 ergänzt später die gemeinsame Sicht mit Befinden und optionalen Zyklusangaben. US-05 wird für gespeicherte Daten mit eingeplant und nicht aus dem Kern gestrichen. Q-01 bis Q-05 gelten bei allen betroffenen Stories.

Die Reihenfolge ist kein Wochenplan. Wir wählen später anhand unserer Zeit, Abhängigkeiten und Schätzung aus. Die jetzigen Planungsaufgaben T-01 bis T-13 stehen auf dem [Board](https://github.com/users/al3v4l3/projects/1/views/1).

## US-01 · Tagesbefinden festhalten

**Als Nutzerin möchte ich meine Energie für einen Tag festhalten, damit ich sie später zusammen mit meinem Training ansehen kann.**

Fertig ist die Funktion, wenn:

- ich Datum und Energie von 1 bis 5 eingeben kann und die Skala erklärt wird;
- ich ohne Zyklusangabe speichern kann;
- ich den Check-in nach erneutem Öffnen am richtigen Tag wiederfinde und ändern kann;
- pro Tag nur ein Check-in besteht;
- bei fehlenden Pflichtangaben ein verständlicher Hinweis erscheint und Abbrechen nichts neu anlegt.

Prüfung: **AT-01, AT-08**. Die Eintrags- und Skalenregeln sind Vorschläge aus dem Lastenheft.

## US-02 · Zyklusangabe freiwillig ergänzen

**Als Nutzerin möchte ich selbst entscheiden, ob ich eine Zyklusangabe ergänze, damit ich die App auch ohne diese Information nutzen kann.**

Fertig ist die Funktion, wenn:

- ich für ein Datum freiwillig eine beobachtete Blutung angeben kann;
- Überspringen Training und Check-in nicht verhindert;
- fehlende Angaben als „keine Angabe“ erscheinen;
- eine gespeicherte Angabe am richtigen Tag sichtbar und löschbar ist.

Prüfung: **AT-02, AT-04, AT-05**. Keine automatische Phasenbestimmung im ersten Umfang.

## US-03 · Training eintragen

**Als Freizeitsportlerin möchte ich ein absolviertes Training eintragen, damit ich meine Aktivität später nachvollziehen kann.**

Fertig ist die Funktion, wenn:

- ich Datum, Sportart und Dauer eingeben kann;
- eine positive ganze Minutenzahl akzeptiert wird;
- leere Pflichtfelder, 0, negative Werte, Text und halbe Minuten verständlich zurückgewiesen werden;
- ein zukünftiges Datum zurückgewiesen wird;
- ich gespeicherte Werte nach erneutem Öffnen am richtigen Tag sehe;
- mehrere Trainings an einem Tag möglich sind;
- der Ablauf ohne Zyklusangabe funktioniert und Abbrechen keinen Eintrag erzeugt.

Prüfung: **AT-03, AT-08, BT-01**. Ganze Minuten und keine Zukunftsdaten sind Vorschläge für morgen.

**Beispiel für spätere Tasks:** Formular skizzieren → Eingaberegeln umsetzen → Speichern und Laden anbinden → Erfolgs- und Fehlerfälle prüfen. Jede Task bekommt eine Person, einen Aufwand und ein klares Ergebnis. Diese Umsetzung ist noch nicht beauftragt.

## US-04 · Verlauf ansehen

**Als Nutzerin möchte ich Training und Befinden im selben Zeitraum sehen, damit ich meine eigenen Einträge vergleichen kann.**

Fertig ist die Funktion, wenn:

- ich einen Zeitraum auswählen und Einträge nach Datum sehen kann;
- vorhandene Zyklusangaben beim passenden Tag stehen;
- fehlende Angaben von eingetragenen Werten unterscheidbar sind;
- ein leerer Verlauf erklärt, wie ich einen ersten Eintrag anlege;
- die Darstellung keine Ursache, Leistungsprognose oder berechnete Phase behauptet.

Prüfung: **AT-04**. Eine einfache Liste reicht für den ersten Entwurf.

## US-05 · Einträge löschen

**Als Nutzerin möchte ich einzelne oder alle eigenen Einträge löschen, damit ich die Kontrolle über meine gespeicherten Angaben behalte.**

Fertig ist die Funktion, wenn:

- eine Einzellöschung andere Einträge unverändert lässt;
- vor einer Gesamtlöschung deren Umfang erklärt und eine Bestätigung verlangt wird;
- Abbrechen der Bestätigung nichts verändert;
- gelöschte Einträge auch nach erneutem Öffnen weg sind.

Prüfung: **AT-05**. Was ein eventuelles Backend oder Backup betrifft, klären wir bei der Speicherentscheidung mit.

## US-06 · Vom Startbildschirm öffnen

**Als Smartphone-Nutzerin möchte ich die Web-App zum Startbildschirm hinzufügen, damit ich sie schnell öffnen kann.**

Fertig ist die Funktion, wenn:

- Installation und Öffnen auf jeder vereinbarten Plattform geprüft sind;
- bei Bedarf eine passende manuelle Anleitung vorhanden ist;
- die App auch ohne Installation im Browser nutzbar bleibt.

Prüfung: **AT-06**. Geräte und Browser noch auswählen; nicht dieselbe Installation für alle voraussetzen.

## Später vielleicht

Ernährung, Barcode-Suche, Übungskatalog, Wearables, Health-Anbindung, Flo-Import und KI-Coach. Erst ein konkretes Problem und den Aufwand prüfen, dann entscheiden.

## Neue Story ergänzen

„Als … möchte ich …, damit …“ + Bezug zur Anforderung + beobachtbare Kriterien + ein relevanter Fehlerfall + Priorität + Aufwand. Die [GitHub-Vorlage](../.github/ISSUE_TEMPLATE/user-story.yml) hilft dabei. Inhalt hier pflegen, Aufgaben und Zuständigkeiten im Issue, Status im Board.
