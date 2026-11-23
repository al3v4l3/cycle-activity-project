[Übersicht](../README.md) · [Ziele](01-motivation-und-ziele.md) · [Anforderungen](02-anforderungen.md) · [Backlog](03-product-backlog.md) · [Entwurf](04-entwurf.md) · [Technik](05-technik.md) · [Organisation](06-organisation.md) · [Vorstellung](07-projektvorstellung.md)

# Technik und Schnittstellen

## Aktueller Stand

| Bereich | Stand |
| --- | --- |
| Zielplattform | Android zuerst, iOS bei ausreichender Zeit |
| Oberfläche | HTML und CSS sollen nutzbar sein |
| Gemeinsame Sprache | noch auszuwählen; Vorschlag TypeScript |
| Framework | Vorschlag React mit Ionic und Capacitor; noch nicht gemeinsam festgelegt |
| Speicherung und Account | offen |
| Trainingslogik in der App | Algorithmus oder KI-Anbindung; konkrete Lösung offen |

Entwicklungswerkzeuge und eine KI-Funktion innerhalb der App sind zwei getrennte Entscheidungen.

## Vorschlag für die App

**TypeScript + React + Ionic + Capacitor** passt als Kandidat zu einer gemeinsamen Codebasis mit CSS-Oberfläche. Ionic stellt mobile Oberflächenelemente bereit. Capacitor verpackt die Web-Oberfläche als Android- bzw. iOS-App und bindet native Funktionen über Plugins an. Die Oberfläche bleibt dabei in einer eingebetteten Browseransicht.

Dafür spricht die Nutzung unserer Webkenntnisse. Offen bleiben Plugin-Unterstützung, Einrichtung, Speicherlösung und der Aufwand auf beiden Plattformen. Als Alternative vergleichen wir React Native mit TypeScript; dort lässt sich vorhandenes HTML/CSS nicht direkt übernehmen.

Quellen: [Ionic](https://ionicframework.com/docs), [Capacitor](https://capacitorjs.com/docs), [React-Native-Styling](https://reactnative.dev/docs/style). Die Auswahl halten wir mit Grund im [Entscheidungsprotokoll](06-organisation.md#entscheidungen) fest.

## Anbindungen prüfen

| Bereich | Kandidat und aktueller Stand | Klärung |
| --- | --- | --- |
| Zyklusdaten | Flo ist ein Wunschkandidat. Ein direkter Entwicklerzugang ist noch nicht bestätigt. | [T-03](https://github.com/al3v4l3/cycle-activity-project/issues/3): Zugang, Datenarten und Bedingungen prüfen. |
| Android-Daten | Health Connect ist der Kandidat für gerätebezogene Gesundheitsdaten. | [T-04](https://github.com/al3v4l3/cycle-activity-project/issues/4): benötigte Daten, Berechtigungen und Plugin prüfen. |
| iPhone-Daten | Apple HealthKit als mögliche spätere Ergänzung. | Verfügbare Daten und Einrichtung prüfen; iOS hat geringere Priorität. |
| Sportuhren | Möglicherweise über deren Hersteller-App und die Health-Plattform. | Je Uhr prüfen, welche Daten tatsächlich weitergegeben werden. |
| Empfehlungen | Eigene Regeln oder KI-Anbindung. Noch kein Anbieter ausgewählt. | [T-08](https://github.com/al3v4l3/cycle-activity-project/issues/8): Datenbedarf, Quellen, Beispiele, Kosten und Fehlerfälle klären. |

Health Connect und HealthKit sind verschiedene Plattformen. Eine Verbindung liefert nicht automatisch alle Zyklus-, Schlaf- oder Uhrendaten. Entscheidend sind verfügbare Datentypen, die Datenquelle und die Freigabe.

Google empfiehlt Health Connect für mobile Anbindungen an Gerätedaten und die Google Health API für Cloud-Anbindungen. Die alte Google-Fit-API wird nur bis Ende 2026 unterstützt. Quellen: [Google](https://developer.android.com/health-and-fitness/health-connect/migration/fit), [Apple HealthKit](https://developer.apple.com/documentation/healthkit/setting-up-healthkit).

## Machbarkeit dokumentieren

Pro Kandidat halten wir kurz fest: Quelle und Prüfdatum, verfügbare Daten, Plattform, Zugang und Freigaben, Kosten/Lizenz sowie Ergebnis. Danach lautet die Entscheidung: geeignet, ungeeignet oder noch offen.

Als späterer technischer Versuch bietet sich an: Eine Datenart nach Freigabe auf einem echten Android-Gerät lesen, Datum und Wert vergleichen und den Fall ohne Freigabe prüfen. Das ist eine geplante Prüfung, noch kein vorhandener Nachweis.

Für die Vorstellung müssen Sprache, App-Ansatz und die offenen Integrationsrisiken nachvollziehbar sein. Ein fertiger Import oder eine fertige KI ist damit nicht behauptet.
