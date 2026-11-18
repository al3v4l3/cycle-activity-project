# Unser Ziel – und wie wir es überprüfen

**Arbeitsstand vom 18.11.2026 für unser Gruppentreffen.** Die Ziele und Kriterien unten sind Vorschläge, die wir gemeinsam bestätigen oder ändern. Es wurden noch keine Nutzergespräche oder Produkttests durchgeführt.

## Unsere Idee und Motivation

Wir wollen eine einfache Fitness-Web-App für Frauen entwickeln. Training, Tagesbefinden und freiwillige Zyklusangaben sollen an einem Ort stehen. So kann eine Nutzerin später nachvollziehen, was sie an einem Tag eingetragen hat, ohne dafür zwischen verschiedenen Notizen oder Apps zu wechseln.

Unsere Motivation kommt aus unserer Erfahrung mit Fitness-Apps und der Frage, ob sich persönliche Angaben beim Rückblick auf das Training besser zusammenbringen lassen. Dass unsere Lösung dafür gebraucht wird, ist bisher eine Annahme. Wir behaupten nicht, dass es keine vergleichbaren Apps gibt.

**Erste Zielgruppe:** erwachsene Freizeitsportlerinnen, die regelmäßig trainieren und ihre eigenen Einträge im Verlauf ansehen möchten. Die App soll auch ohne Zyklusangaben nutzbar sein.

## Unser Produktziel in einem Satz

**Eine Nutzerin kann ihr Training und Tagesbefinden einfach festhalten, freiwillig Zyklusangaben ergänzen und alles am richtigen Tag in einem gemeinsamen Verlauf wiederfinden.**

Wir wollen zunächst persönliche Angaben verständlich dokumentieren. Eine Verbesserung von Trainingsleistung oder Gesundheit können wir mit diesem Projekt nicht nachweisen.

## Was bedeutet „Operationalisierung“?

Wir machen aus einem allgemeinen Ziel etwas Konkretes, das man beobachten und prüfen kann.

**Ziel → konkretes Verhalten → Erfolgskriterium → Prüfung.**

„Die App soll hilfreich sein“ ist noch zu ungenau. Konkreter ist: „Ich trage ein Training ein und finde nach erneutem Öffnen dieselben Daten am richtigen Tag wieder.“ Dann wissen wir, was wir bauen und ausprobieren müssen.

Nicht jedes Kriterium braucht eine Prozentzahl. Auch „Abbrechen speichert nichts“ lässt sich eindeutig prüfen. Für das Ziel „einfach bedienbar“ brauchen wir dagegen eine echte Aufgabe und einen vereinbarten Maßstab.

## So machen wir unser Produktziel prüfbar

Alle Kriterien gelten für die spätere erste App-Version. Der Umsetzungstermin nach der Vorstellung ist noch offen. Die IDs verbinden Ziel, Anforderungen, Stories und Tests.

| Teilziel | Woran erkennen wir Erfolg? | Wie prüfen wir das? | Bezug |
| --- | --- | --- | --- |
| **Z-01 · Einträge festhalten** | Check-in und Training lassen sich speichern. Nach erneutem Öffnen stehen dieselben Werte am gewählten Tag. Abbrechen legt nichts an. | Künstlichen Check-in und ein Training mit 30 Minuten anlegen, Seite erneut öffnen und Werte vergleichen. | F-01, F-03, Q-04; US-01, US-03; AT-01, AT-03, AT-08 |
| **Z-02 · Zusammenhänge selbst ansehen** | Training und Befinden stehen beim passenden Datum. Fehlende Angaben sind als fehlend erkennbar. Die Anzeige behauptet keine Ursache oder berechnete Zyklusphase. | Eine künstliche Woche mit Einträgen und Lücken durchgehen. Prüfen, ob die Zuordnung und Beschriftung stimmen. | F-04, Q-05; US-04; AT-04 |
| **Z-03 · Selbst über Daten entscheiden** | Alle Kernabläufe funktionieren ohne Zyklusangabe. Einzelne und alle Einträge lassen sich löschen; ein Abbruch der Gesamtlöschung verändert nichts. | Angaben überspringen, einen Eintrag löschen, Gesamtlöschung abbrechen und danach bestätigen. Erneut öffnen. | F-02, F-05, Q-01; US-02, US-05; AT-02, AT-05 |
| **Z-04 · Einfach auf dem Handy bedienen** | Beim vorgesehenen Bedienungstest schaffen mindestens 2 von 3 Personen einen Trainingseintrag ohne Hilfestellung in höchstens 2 Minuten. Bei 375 px Breite sind die Formularaktionen erreichbar. | Vorher Aufgaben und Version festlegen, künstliche Daten verwenden, Zeit und nötige Hilfe notieren. Mobile Ansicht zusätzlich prüfen. | Q-02; US-03; AT-07, BT-01 |

**Z-04 ist ein vorgeschlagener Zielwert, kein Ergebnis und keine Vorgabe des Dozenten.** Drei Personen sind ein kleiner Praxistest, kein Nachweis für alle Nutzerinnen. Einen Klickprototyp können wir auf Verständlichkeit prüfen; echte Speicherung und Löschung testen wir erst an der App. Die ausführlichen Fälle stehen in [Prüfungen](07-erhebung-und-qualitaet.md).

**Zusätzlicher Wunsch F-06:** Die Web-App zum Startbildschirm hinzufügen. Unterstützte Geräte und Browser wählen wir erst aus. Danach prüfen wir Installation und Öffnen auf jeder vereinbarten Plattform mit AT-06. Die Browsernutzung bleibt möglich.

## Unser Ziel bis zur ersten Vorstellung

Bis zur internen Vorbereitung am **01.12.2026** wollen wir Folgendes gemeinsam geklärt haben:

- Ziel, Motivation und erster Umfang sind abgestimmt.
- Jede Kernanforderung hat eine passende Story und ein überprüfbares Kriterium.
- Das Backlog ist geordnet; Aufgaben, Aufwand und Zuständigkeiten sind festgehalten.
- Ein Bild erklärt den Ablauf; Technik und KI-Unterstützung sind begründet ausgewählt.
- Wir haben geprüft, ob etwas Wichtiges fehlt oder sich widerspricht.

Das zeigen wir mit unseren Dokumenten, dem Bild, dem Board und einem kurzen Prüfprotokoll. **Das ist unser Planungsziel für die Vorstellung. Die Tabelle oben beschreibt den späteren Produkterfolg.**

## Was der Dozent nach unserem Verständnis damit meint

Laut der Rückmeldung vom 18.11. sollen wir jetzt das Projektziel operationalisieren. Fachlich passt dazu: vom allgemeinen Ziel zu konkreten Anforderungen und überprüfbaren Ergebnissen kommen. In der Vorlesung werden Ziele und prüfbare Anforderungen ebenfalls unterschieden; Fundstellen stehen im [Vorlesungsbezug](01-vorlesungsbezug.md).

Die genaue Bewertungsmatrix liegt uns weiterhin nicht vor. Unklare Begriffe und den Vorstellungstermin fragen wir nach. Für morgen haben wir damit einen konkreten Vorschlag, über den die Gruppe entscheiden kann.
