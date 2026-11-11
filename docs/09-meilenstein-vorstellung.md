# M1 · Erste Projektvorstellung

**Arbeitsgrundlage:** vom Team am 11.11.2026 bereitgestellte Chat-Mitschrift zur mündlichen Aufgabenbesprechung. Diese Zusammenfassung übernimmt die darin genannten Punkte. Der private Screenshot wird nicht veröffentlicht. Es handelt sich um eine Team-Mitschrift, nicht um ein offizielles Aufgabenblatt.

Die Mitschrift nennt einmal drei und später drei bis vier Wochen bis zur Vorstellung. Daraus ergibt sich ab Projektstart ein vorläufiges Fenster **02.–09.12.2026**. Intern bereiten wir bis 01.12. vor; den tatsächlichen Termin und die Dauer bestätigen wir noch. Die **erste Implementierungsiteration folgt nach der Vorstellung gegen Ende des Semesters**. Das genaue Datum dafür ist offen.

## Was wir vorbereiten

| Punkt aus der Mitschrift | Konkretes Ergebnis im Projekt | Fertig für M1, wenn … |
| --- | --- | --- |
| Einleitung und Motivation in Prosa | [Projektbeschreibung](10-einleitung-und-motivation.md) | Problem, Zielgruppe, Motivation und Ziel zusammenhängend formuliert und im Team geprüft sind |
| „Detailmanagement“ | Aufgabenzerlegung, Verantwortung, Aufwand und Abhängigkeiten in Issues | das Team Aufgaben nachvollziehbar bearbeiten kann; diese Auslegung des Begriffs noch bestätigen |
| User Stories | [Stories](04-user-stories.md) | Rolle, Wunsch, Nutzen und prüfbare Akzeptanzkriterien vorhanden sind |
| Anforderungsdefinitionen | [Lastenheft](02-lastenheft.md), Lösungsentwurf soweit nötig | funktionale und nichtfunktionale Anforderungen einzeln und verständlich beschrieben sind |
| Product Backlog | geordnete Produktstories und ergänzende Arbeitspakete | Reihenfolge, Priorität, Umfang und zunächst grobe Schätzungen erkennbar sind |
| Vollständigkeit und Konsistenz | gemeinsame Prüfung nach untenstehender Checkliste | alle gewählten Kernanforderungen abgedeckt sind und keine offenen Widersprüche übergangen werden |
| Vorstellung „mit Bild“ | eigene Übersicht oder Wireframe in `design/` | ein Bild die Idee erklärt; ob eine bestimmte Bildart gemeint ist, noch klären |
| Repository aussuchen | dieses Projekt- und Entwicklungsrepo | alle vier Zugriff haben und wissen, wo Dokumentation, Code und Tests liegen |
| Kanban-Board | Projektboard mit Aufgaben und Status | Aufgaben sichtbar eingeordnet und Verantwortlichkeiten bekannt sind |
| Logistik / Kommunikation | Vereinbarungen im [Teamplan](05-team-und-plan.md) | Kanal, Treffen, Rückmeldungen, Ablage und Vertretung abgestimmt sind |
| Programmiersprache, „KI raussuchen“ | [begründete Technologie- und KI-Auswahl](11-technologie-und-ki.md) | Vorschläge verglichen, Auswahl begründet und Aufgaben daraus abgeleitet sind; Bedeutung von „KI“ noch präzisieren |
| Priorisierung / Fokus | Kernumfang und Ideenparkplatz | notwendige Funktionen und Nice-to-haves mit Begründung getrennt sind |

Ein getesteter Klickprototyp, zwei bis drei Interviews und eine fertige App sind **in dieser Mitschrift nicht ausdrücklich als Ergebnisse für M1 genannt**. Gespräche und Skizzen helfen bei der Klärung; wir planen sie nach verfügbarer Zeit. Eine einfache Visualisierung für „mit Bild“ gehört dagegen in M1. Ein umfangreiches Pflichtenheft wird daraus ebenfalls nicht als zusätzliche Pflicht abgeleitet.

## Vollständigkeit und Konsistenz gemeinsam prüfen

- [ ] Jede Funktion des ausgewählten Kernumfangs hat eine Anforderungs-ID und mindestens eine passende Story.
- [ ] Jede Kernstory hat beobachtbare Akzeptanzkriterien und mindestens einen relevanten Fehler- oder Leerfall.
- [ ] Die Aufgaben einer Story decken ihren vereinbarten Umfang ab; Aufwand für Prüfung und Dokumentation wird berücksichtigt.
- [ ] Qualitätsanforderungen wie Freiwilligkeit, mobile Bedienung und Löschung werden durch entsprechende Kriterien abgedeckt.
- [ ] Begriffe, Eingaberegeln, Prioritäten und Nicht-Ziele sind in allen Dokumenten gleich verwendet.
- [ ] Das Backlog enthält auch notwendige Projekt-, Recherche- und Qualitätsaufgaben, nicht nur App-Funktionen.
- [ ] Unbekannte Angaben sind ausdrücklich offen; fehlende Daten werden nicht als Fakten oder Testergebnisse behandelt.
- [ ] Der geplante Umfang passt zur verfügbaren Zeit. Noch nicht eingeplante Funktionen bleiben sichtbar im Parkplatz.
- [ ] Ein zweites Teammitglied hat die Prüfung mit Datum, Version und verbleibenden Punkten dokumentiert.

Vollständigkeit bezieht sich auf den **vereinbarten aktuellen Umfang**, nicht auf alle denkbaren Fitnessfunktionen. Prüfprotokoll: Datum / geprüfter Stand / Beteiligte / gefundene Widersprüche / Korrekturen / verbleibende Fragen. Noch keine Prüfung durchgeführt.

## Danach · Erste Implementierungsiteration

Nach der Vorstellung verarbeitet das Team das Feedback, entscheidet ein kleines Iterationsziel und setzt einen durchgängigen Kernablauf mit passenden Tests in diesem Repository um. Die genaue Auswahl, Aufwandsschätzung und der Termin werden dann beschlossen. Die Planungswochen vor M1 werden nicht als abgeschlossene Implementierungsiterationen gezählt.
