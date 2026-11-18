# Projektziel und Erfolgskriterien

**Status: Entwurf**

## Ziel

Eine Nutzerin kann Training und Tagesbefinden festhalten, freiwillig Zyklusangaben ergänzen und alles am richtigen Tag in einem gemeinsamen Verlauf wiederfinden.

Die Anwendung richtet sich zunächst an erwachsene Freizeitsportlerinnen, die regelmäßig trainieren und ihre eigenen Einträge nachvollziehen möchten. Sie bleibt ohne Zyklusangaben nutzbar.

## Operationalisierung

Das Ziel wird durch konkrete Handlungen und überprüfbare Kriterien beschrieben. Aus „Training nachvollziehen“ wird beispielsweise: Ein Training mit Datum, Sportart und Dauer speichern und nach erneutem Öffnen mit denselben Werten wiederfinden.

| Teilziel | Erfolgskriterium | Prüfung | Bezug |
| --- | --- | --- | --- |
| **Z-01 · Einträge festhalten** | Check-in und Training bleiben nach erneutem Öffnen am richtigen Tag sichtbar. Abbrechen legt nichts an. | Künstlichen Check-in und Training mit 30 Minuten speichern und erneut öffnen. | F-01, F-03, Q-04; US-01, US-03; AT-01, AT-03, AT-08 |
| **Z-02 · Gemeinsamen Verlauf ansehen** | Training, Befinden und vorhandene Zyklusangaben sind dem richtigen Datum zugeordnet. Fehlende Werte bleiben erkennbar. | Künstliche Woche mit Einträgen und Lücken prüfen. | F-04, Q-05; US-04; AT-04 |
| **Z-03 · Kontrolle über Angaben behalten** | Kernfunktionen funktionieren ohne Zyklusangabe. Einzelne und alle Einträge lassen sich löschen; Abbruch der Gesamtlöschung verändert nichts. | Angaben überspringen, Einzel- und Gesamtlöschung prüfen, erneut öffnen. | F-02, F-05, Q-01; US-02, US-05; AT-02, AT-05 |
| **Z-04 · Mobile Bedienung** | Mindestens 2 von 3 Testpersonen erstellen und finden einen Trainingseintrag ohne Hilfe in höchstens 2 Minuten. Bei 375 px Breite sind die Formularaktionen erreichbar. | Bedienaufgabe mit künstlichen Daten durchführen; Zeit und Hilfebedarf notieren. Mobile Ansicht prüfen. | Q-02; US-03; AT-07, BT-01 |

Der Zielwert für Z-04 ist geplant und noch nicht überprüft. Der kleine Bedienungstest dient dazu, Probleme im Ablauf zu finden. Er belegt keine allgemeine Wirksamkeit.

**Erweiterung F-06:** Auf ausgewählten Geräten soll sich die Web-App zum Startbildschirm hinzufügen und von dort öffnen lassen. Prüfung mit AT-06 nach Auswahl der unterstützten Plattformen.

## Grenzen

Die App dokumentiert persönliche Beobachtungen. Sie soll keine unbestätigten Zyklusphasen, Ursachen für Leistungsunterschiede oder medizinischen Empfehlungen ausgeben. Eine Verbesserung von Leistung oder Gesundheit ist kein nachzuweisendes Projektziel.

Die einzelnen Fälle stehen im [Testplan](07-erhebung-und-qualitaet.md). Der Umfang der ersten Projektvorstellung steht unter [Meilenstein](09-meilenstein-vorstellung.md).
