[Übersicht](../README.md) · [Ziele](01-motivation-und-ziele.md) · [Anforderungen](02-anforderungen.md) · [Backlog](03-product-backlog.md) · [Entwurf](04-entwurf.md) · [Technik](05-technik.md) · [Organisation](06-organisation.md) · [Vorstellung](07-projektvorstellung.md)

# Motivation und Ziele

## Einleitung und Motivation

Wir möchten unseren Körper besser verstehen und bewusster mit Training und Ernährung umgehen. Uns interessiert besonders, wie sich Sport, persönliches Befinden und Zyklus gemeinsam betrachten lassen. Daraus entstand die Idee einer App, die Zyklus, Sport, Ernährung und Gesundheit an einer Stelle verbindet.

Vorhandene Daten sollen nach Möglichkeit übernommen werden, damit sie nicht mehrfach eingetragen werden müssen. Darauf aufbauend möchten wir Aktivitäten dokumentieren und individuelle Trainingsvorschläge anbieten. Zielgruppe sind vor allem Freizeitsportlerinnen, die ihr Training bewusster gestalten möchten. Ein sorgfältiger Umgang mit den persönlichen Daten gehört dazu.

## Produktziel

**Die Nutzerin soll ihre Aktivitäts- und Zyklusdaten gemeinsam nutzen können, um ihr Training zu überblicken und passende Trainingsvorschläge zu erhalten.** Ernährung und zusätzliche Auswertungen ergänzen die Idee mit geringerer Priorität.

## Ziele konkret machen

Operationalisierung heißt: Wir beschreiben zu einem allgemeinen Ziel ein Ergebnis, das sich später prüfen lässt. Die folgenden Kriterien sind unser erster Entwurf für die spätere App.

<a id="z-01"></a>
### Z-01 Daten zusammenführen und Aktivitäten festhalten

**Erkennbares Ergebnis:** Freigegebene Daten stehen mit Datum und Quelle in der App. Selbst erfasste Aktivitäten lassen sich speichern und wieder öffnen. Ohne Datenverbindung wird der fehlende Inhalt erklärt.

**Prüfung:** Einen Datensatz mit bekannten Werten übernehmen bzw. eine Aktivität eintragen und Datum, Werte sowie Quelle vergleichen.

**Bezug:** A-01, A-03, A-04; [US-01 · Zyklusdaten übernehmen](https://github.com/al3v4l3/cycle-activity-project/issues/14), [US-03 · Aktivitäten festhalten](https://github.com/al3v4l3/cycle-activity-project/issues/16), [US-04 · Health- und Uhrendaten verbinden](https://github.com/al3v4l3/cycle-activity-project/issues/17). Manuelle Zyklusangaben sind die optionale Alternative [US-09 · Zyklus selbst dokumentieren](https://github.com/al3v4l3/cycle-activity-project/issues/22).

<a id="z-02"></a>
### Z-02 Training passend planen

**Erkennbares Ergebnis:** Ein Trainingsvorschlag berücksichtigt das persönliche Ziel und die tatsächlich verfügbaren Angaben. Die Nutzerin erkennt, worauf der Vorschlag beruht. Fehlende Daten werden erklärt.

**Prüfung:** Vorher festgelegte Beispiele mit verschiedenen Zielen, vorhandenen Daten und Datenlücken durchgehen. Den erwarteten Vorschlag jeweils mit den ausgewählten Regeln begründen.

**Bezug:** A-02, A-14; [US-02 · Trainingsvorschläge erhalten](https://github.com/al3v4l3/cycle-activity-project/issues/15). Fachliche Regeln und Datenbedarf müssen noch ausgearbeitet werden.

<a id="z-03"></a>
### Z-03 Eigene Einträge überblicken

**Erkennbares Ergebnis:** Einträge erscheinen beim passenden Tag und in der passenden Kategorie. Graphen zeigen vorhandene Messwerte und erkennbare Lücken. Energie und Anstrengung verwenden die Skala 1 bis 10.

**Prüfung:** Einen Zeitraum mit künstlichen Einträgen und Lücken im Kalender und in den vorgesehenen Graphen ansehen.

**Bezug:** A-05 bis A-08, A-10, A-12; [US-05 · Ernährung festhalten und Hinweise ansehen](https://github.com/al3v4l3/cycle-activity-project/issues/18), [US-06 · Leistungsverlauf ansehen](https://github.com/al3v4l3/cycle-activity-project/issues/19), [US-07 · Energie und Anstrengung einschätzen](https://github.com/al3v4l3/cycle-activity-project/issues/20), [US-08 · Krankheitstage festhalten](https://github.com/al3v4l3/cycle-activity-project/issues/21), [US-10 · Streak ansehen](https://github.com/al3v4l3/cycle-activity-project/issues/23), [US-12 · Kategorien und Kalender nutzen](https://github.com/al3v4l3/cycle-activity-project/issues/25).

<a id="z-04"></a>
### Z-04 Einfach und kontrolliert am Handy bedienen

**Erkennbares Ergebnis:** Die vorgesehenen Hauptaufgaben sind auf Android erreichbar. Freigaben und Fehler sind verständlich. Zugriff und Löschung persönlicher Daten sind beschrieben und später prüfbar.

**Prüfung:** Eine Testperson erhält die Aufgabe, eine Aktivität einzutragen und wiederzufinden. Wir beobachten Verständnis, Hilfebedarf und Fehler. Zusätzlich werden verweigerte Freigaben, Zugriff und Löschung geprüft. Konkrete Zielwerte legen wir vor dem Test fest.

**Bezug:** Q-01 bis Q-05; alle Hauptabläufe. Ergänzungen: [US-11 · Darstellung wechseln](https://github.com/al3v4l3/cycle-activity-project/issues/24), [US-13 · Eigenes Konto und persönliche Daten verwalten](https://github.com/al3v4l3/cycle-activity-project/issues/26).

## Ziel dieses Semesters

Wir planen das Produkt und zeigen, wie aus der Idee Anforderungen, Stories, Prioritäten, Aufgaben und ein Entwurf entstehen. Die technische Umsetzung ist spätere Arbeit. Dafür legen wir jetzt noch keinen fertigen Funktionsumfang fest.

Die Prioritäten stehen im [Lastenheft](02-anforderungen.md). Eine wichtige Funktion ist damit noch keine bereits zugesagte Integration.
