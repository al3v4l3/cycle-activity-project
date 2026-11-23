[Übersicht](../README.md) · [Ziele](01-motivation-und-ziele.md) · [Anforderungen](02-anforderungen.md) · [Backlog](03-product-backlog.md) · [Entwurf](04-entwurf.md) · [Technik](05-technik.md) · [Organisation](06-organisation.md) · [Vorstellung](07-projektvorstellung.md)

# Anforderungen

Dieses kurze **Lastenheft** beschreibt, was die App leisten soll. Die technische Lösung steht im [Entwurf](04-entwurf.md). Der Funktionsumfang ist ein Planungsstand.

## Prioritäten

- **10 / Rot:** sehr wichtig für die Produktidee.
- **20 / Gelb:** mittlere Priorität.
- **50 / Grün:** optionales Add-on.
- **Offen:** noch nicht eingeordnet.

Die Priorität ist nicht der Bearbeitungsstatus und auch kein Umsetzungstermin. Eine rote Schnittstelle bleibt wichtig, obwohl ihre Verfügbarkeit noch offen ist. Kalender, Kategorien und Account wurden bisher nicht mit einer Priorität versehen.

## Funktionale Anforderungen

| ID | Was soll die App können? | Priorität | Story mit Kriterien und Aufgaben |
| --- | --- | --- | --- |
| **A-01** | Vorhandene Zyklusdaten über eine geeignete Schnittstelle übernehmen. Flo ist ein zu prüfender Kandidat. | 10 · Rot | [US-01](https://github.com/al3v4l3/cycle-activity-project/issues/14) |
| **A-02** | Trainingsvorschläge anhand persönlicher Ziele und verfügbarer Zyklusdaten anzeigen. | 10 · Rot | [US-02](https://github.com/al3v4l3/cycle-activity-project/issues/15) |
| **A-03** | Sportliche Aktivitäten erfassen und wieder ansehen. | 10 · Rot | [US-03](https://github.com/al3v4l3/cycle-activity-project/issues/16) |
| **A-04** | Unterstützte Sportuhren- bzw. Health-Daten anbinden. | 10 · Rot | [US-04](https://github.com/al3v4l3/cycle-activity-project/issues/17) |
| **A-05** | Essen dokumentieren und fachlich begründete Ernährungshinweise anbieten. | 20 · Gelb | [US-05](https://github.com/al3v4l3/cycle-activity-project/issues/18) |
| **A-06** | Einen Leistungsverlauf als Kurve anzeigen. Die Messgröße ist noch offen. | 20 · Gelb | [US-06](https://github.com/al3v4l3/cycle-activity-project/issues/19) |
| **A-07** | Energie und Anstrengung auf einer Skala von 1 bis 10 erfassen und als Graph auswerten. | 20 · Gelb | [US-07](https://github.com/al3v4l3/cycle-activity-project/issues/20) |
| **A-08** | Krankheitstage dokumentieren. | 20 · Gelb | [US-08](https://github.com/al3v4l3/cycle-activity-project/issues/21) |
| **A-09** | Zyklus manuell dokumentieren und eine geschätzte Vorschau anbieten. Alternative zur Datenanbindung. | 50 · Grün | [US-09](https://github.com/al3v4l3/cycle-activity-project/issues/22) |
| **A-10** | Eine Streak anzeigen. | 50 · Grün | [US-10](https://github.com/al3v4l3/cycle-activity-project/issues/23) |
| **A-11** | Darstellungen wie einen Dunkelmodus anbieten. | 50 · Grün | [US-11](https://github.com/al3v4l3/cycle-activity-project/issues/24) |
| **A-12** | Bereiche für Essen, Zyklus und Aktivitäten sowie eine Kalenderübersicht anbieten. | noch offen | [US-12](https://github.com/al3v4l3/cycle-activity-project/issues/25) |
| **A-13** | Ein eigenes Konto mit Datenbank und geschütztem Zugriff vorsehen. | noch offen | [US-13](https://github.com/al3v4l3/cycle-activity-project/issues/26) |
| **A-14** | Die Trainingsvorschläge über einen Algorithmus oder eine KI-Anbindung erzeugen. Die konkrete Lösung ist offen. | 10 · Rot | [US-02](https://github.com/al3v4l3/cycle-activity-project/issues/15) |

A-14 beschreibt die technische Grundlage von A-02 und ist deshalb derselben Story zugeordnet.

## Nichtfunktionale Anforderungen

Diese Regeln beschreiben, wie die Funktionen arbeiten sollen. Datenschutz, Zuverlässigkeit und nachvollziehbare Vorschläge ergänzen die Funktionsliste.

| ID | Anforderung | Woran prüfen wir das später? |
| --- | --- | --- |
| **Q-01** | Die App soll am Handy benutzerfreundlich sein. Hohe Priorität. | Hauptaufgaben mit Testpersonen durchgehen; Verständnis, Fehler und Hilfebedarf notieren. |
| **Q-02** | Persönliche Daten nur mit passenden Freigaben nutzen. Zugriff, Speicherort und Löschung erklären. | Berechtigungen ablehnen und widerrufen; Zugriff sowie Löschung in der gewählten Lösung prüfen. |
| **Q-03** | Gespeicherte Werte bleiben korrekt zugeordnet. Fehler und Datenlücken werden verständlich angezeigt. | Bekannte Werte erneut öffnen; ungültige Eingaben und fehlende Daten ausprobieren. |
| **Q-04** | Zuerst Android unterstützen; iOS bei ausreichender Zeit ergänzen. | Vereinbarte Abläufe auf den unterstützten Geräten prüfen. Mindestversionen noch auswählen. |
| **Q-05** | Vorschläge und berechnete Werte von tatsächlichen Einträgen unterscheiden. | Grundlage eines Vorschlags erklären; keine Daten oder genauen Zyklusphasen erfinden. |

Ein Account ist noch offen. Die Regeln für persönliche Daten gelten auch bei rein lokaler Speicherung.

## Noch zu klärende Details

- Welche Zyklusdaten können wir tatsächlich übernehmen? Welche Datenquelle ist zugänglich?
- Welche Uhrendaten brauchen wir und welche kommen über die Health-Plattform an?
- Welche Regeln sollen Trainingsvorschläge verwenden? Welche fachlichen Quellen passen dazu?
- Was bedeutet „Leistung“ für unsere Kurve?
- Welche Mindestfelder, Speicherlösung und Anmeldung brauchen wir?
- Welche Priorität erhalten Kalender, Kategorien und Account?

Die Skala **1 bis 10** ist festgehalten. Weitere Eingaberegeln werden vor der Umsetzung in den betroffenen Stories ergänzt.
