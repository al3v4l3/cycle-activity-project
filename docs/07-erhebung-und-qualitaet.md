# Bedarfserhebung und Qualität

**Status: vorbereitete Leitfäden und Testfälle. Noch keine Interviews oder Tests durchgeführt.** Bezüge zur Vorlesung stehen in [01-vorlesungsbezug.md](01-vorlesungsbezug.md).

## Bedarfsgespräche für T-03

Zwei bis drei Personen aus der gewählten Zielgruppe, etwa 15 Minuten je Gespräch. Nach Möglichkeit nicht ausschließlich das eigene Team befragen. Erklärt den studentischen Zweck, die freiwillige Teilnahme und dass ihr keine persönlichen Gesundheitsangaben benötigt. Dokumentiert im öffentlichen Repository ausschließlich zusammengefasste Produktbedürfnisse ohne identifizierende Details. Rohnotizen und Kontaktdaten bleiben außerhalb des öffentlichen Repositories.

Fragen in dieser Reihenfolge, bevor ihr eure Lösung vorstellt:

1. Wie dokumentierst du heute dein Training? Erzähle von der letzten konkreten Nutzung.
2. Welche Informationen fehlen dir später beim Rückblick auf eine Einheit?
3. Wie entscheidest du heute, was und wie intensiv du trainierst?
4. Spielt dein Tagesbefinden für die Dokumentation eine Rolle? Du musst keine gesundheitlichen Details nennen.
5. Falls du Zyklusinformationen berücksichtigen möchtest: Wo erwartest du sie im Ablauf? Welche Eingaben würdest du überspringen wollen?
6. Was ist an bisherigen Apps umständlich? Welche Funktion nutzt du tatsächlich regelmäßig?
7. Erst danach: Wie würdest du den vorgeschlagenen Ablauf nutzen? Was würdest du weglassen?

Nicht fragen: „Würdest du unsere tolle zyklusbasierte App nutzen?“ Ein freundliches Ja ist kein Bedarfsnachweis. Unterscheidet beobachtetes Verhalten, Aussagen und eure Interpretation.

Ergebnisvorlage für eine anonymisierte Zusammenfassung:

| Erkenntnis-ID | Zusammengefasstes Bedürfnis | Evidenzart und Anzahl Gespräche | Konsequenz / Story | Unsicherheit |
| --- | --- | --- | --- | --- |
| E-01 | noch zu erheben | noch keine | offen | offen |

## Prototypprüfung für T-08

Mit zwei bis drei Personen einen Papier- oder Klickprototyp prüfen. Nutzt ausschließlich erfundene Daten. Eine Person moderiert neutral, eine protokolliert; helft erst, wenn die Testperson feststeckt, und notiert diese Hilfe.

- „Du hast heute mittlere Energie. Halte das fest, ohne Zyklusangaben zu machen.“
- „Du hast gestern 30 Minuten trainiert. Dokumentiere die Einheit.“
- „Finde die Einträge von gestern und erkläre, welche Informationen vorhanden sind.“
- „Entferne einen Eintrag. Erkläre, was bei der Löschung aller Einträge passieren würde.“

Lasst die Person laut denken. Erfasst Erfolg, Hilfestellung, missverständliche Begriffe und konkrete nächste Änderung. Die kleine Stichprobe zeigt mögliche Probleme, keine repräsentative Wirksamkeit. Technische Eigenschaften werden an diesem Prototyp nicht als bestanden gewertet.

| Testdatum / Prototypversion | Aufgabe | Erfolg ohne Hilfe? | Beobachtung | Änderung / Issue | Erneut geprüft? |
| --- | --- | --- | --- | --- | --- |
| offen | offen | nicht getestet | noch keine Beobachtung | offen | nein |

## Geplante Akzeptanztests der späteren App

Alle Tests haben initial den Status **nicht durchgeführt**. Plattform, Version, Schritte, Ist-Ergebnis und Nachweis werden beim Test ergänzt.

| ID | Bezug | Test und erwartetes Ergebnis |
| --- | --- | --- |
| AT-01 | US-01 | Gültigen Check-in erfassen, Seite neu öffnen: Werte stehen am richtigen Tag. Abbruch legt keinen Eintrag an. |
| AT-02 | US-02, Q-01 | Zyklusangaben weglassen: Training und Check-in bleiben nutzbar; fehlende Daten erscheinen als „keine Angabe“. Freiwillige Angabe wird am richtigen Datum angezeigt. |
| AT-03 | US-03 | 30 Minuten speichern; 0, −1 und Text als Dauer prüfen: gültiger Wert wird übernommen, ungültige Eingaben werden verständlich abgewiesen. Weitere Grenzwerte nach finaler Spezifikation ergänzen. |
| AT-04 | US-04 | Künstliche Woche mit Training, Befinden und Lücken betrachten: Einträge sind korrekt zugeordnet, Lücken erkennbar, keine Phasen- oder Kausalitätsbehauptung. Leerer Verlauf bietet einen verständlichen Einstieg. |
| AT-05 | US-05 | Einzelnen Eintrag löschen, danach Gesamtlöschung abbrechen: nur der einzelne Eintrag fehlt. Anschließend Gesamtlöschung bestätigen und erneut öffnen: betroffene Daten sind weg. Gewählten Speicher und eventuelle Backups in die Prüfung einbeziehen. |
| AT-06 | US-06 | Auf jeder vereinbarten Plattform installieren und über Startbildschirm öffnen; Browsernutzung bleibt möglich. Tatsächliche Gerät-/Browserversion notieren. |
| AT-07 | Q-02 | Kernablauf bei z. B. 375 px Breite und mit Tastatur durchgehen: keine verdeckten Aktionen, verständliche Labels, sichtbarer Fokus und erkennbare Fehlermeldungen. Das ist ein Einstieg, kein vollständiger Barrierefreiheitsnachweis. |
| AT-08 | Q-04 | Nach Entscheidung zum Speicher einen Speicherfehler simulieren: verständliche Meldung, keine falsche Erfolgsmeldung; Vorgehen bei Datenverlust dokumentiert. |

## Risiken für den Projektstart

| Risiko | Frühes Signal | Gegenmaßnahme | Bereich |
| --- | --- | --- | --- |
| Umfang wächst zu mehreren Apps | Ernährung, KI und Wearables werden gleichzeitig Pflicht | Kernablauf bestätigen, zusätzliche Ideen parken | B |
| Unbestätigte Prüfungsannahmen | Team behauptet Pflichtdokumente ohne Quelle | T-02 beantworten lassen und Antworten dokumentieren | B |
| Schnittstelle nicht zugänglich | Keine Entwicklerdokumentation oder nur native Unterstützung | Manueller Ablauf unabhängig von API, T-04 begrenzen | C |
| Nutzungsproblem nicht belegt | Nur Meinungen aus dem eigenen Team | T-03 vor der Festlegung komplexer Funktionen | A |
| Gesundheitsangaben werden veröffentlicht | Screenshots oder Rohinterviews enthalten echte Daten | Künstliche Beispiele, Prüfung vor Upload | alle |
| Zyklus wird zu einer pauschalen Trainingsregel | Automatische Empfehlungen ohne fachliche Prüfung | Im ersten Umfang Beobachtungen dokumentieren; Empfehlungen als getrennte, noch zu prüfende Erweiterung | B/C |
| Aufgaben bleiben an einer Person hängen | Eine Person schreibt alles, andere sehen es erst am Ende | Je Aufgabe Verantwortung und zweite Prüfung; wöchentlich Zeit und Hindernisse abgleichen | D |

Dies ist eine Arbeitsgrundlage für den Prototyp. Vor einem Betrieb mit echten Gesundheitsdaten muss das Team den Datenfluss, Zugriff, Löschung und die einschlägigen Anforderungen gesondert klären; eine Produktionsfreigabe ist hier nicht enthalten.
