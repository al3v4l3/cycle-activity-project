# Lastenheft · Bedarf und Projektumfang

**Status: Entwurf v0.1, 11.11.2026.** Noch nicht durch Team oder Nutzerinnen bestätigt. Verantwortlich: offen. Prüfung: offen.

## Ausgangslage und Zielgruppe

Aus der Projektidee entsteht die Hypothese, dass eine gemeinsame Sicht auf Training, Tagesbefinden und freiwillige Zyklusangaben für Freizeitsportlerinnen hilfreich ist. Eine konkrete Schwierigkeit könnte sein, dass relevante Informationen heute in mehreren Anwendungen oder Notizen verteilt sind. Das ist noch zu erheben.

Erste vorgeschlagene Zielgruppe: erwachsene Freizeitsportlerinnen, die regelmäßig trainieren und ihren persönlichen Verlauf besser nachvollziehen möchten. Trainingsniveau, Sportarten und der Umgang mit fehlenden oder unregelmäßigen Zyklusangaben werden in Gesprächen geklärt. Der Kernablauf soll auch ohne Zyklusangaben funktionieren.

**Produktziel als Entwurf:** Nutzerinnen können Training und Tagesbefinden mit geringem Eingabeaufwand gemeinsam dokumentieren und im Verlauf wiederfinden. Sie behalten die Kontrolle über freiwillige Angaben und ihre Trainingsentscheidung.

„So eine App gibt es nicht“ ist keine belegte Ausgangslage. [Die Recherche](06-recherche.md) nennt bereits ein spezialisiertes Angebot. Eine mögliche Abgrenzung, etwa ein besonders einfacher deutschsprachiger Trainingsverlauf, bleibt zu prüfen.

## Beteiligte

| Beteiligte | Interesse / Beitrag |
| --- | --- |
| Nutzerinnen der ausgewählten Zielgruppe | Bedarf erklären und Abläufe testen |
| Vierköpfiges Projektteam | Anforderungen, Entwurf, spätere Umsetzung und Nachweise |
| Lehrperson | Abgabeerwartungen, methodisches Feedback und Bewertung klären |
| API- und Bibliotheksanbieter, falls ausgewählt | Technische und lizenzbezogene Rahmenbedingungen |

## Vorgeschlagene Anforderungen

Prioritäten: **10 = zuerst notwendig, 20 = anschließend sinnvoll, 50 = später / optional**. Alle Einträge sind Vorschläge. „Muss“ gilt erst nach Teamentscheidung zum ersten Produktumfang.

| ID | Anforderung | Prio | Prüfnachweis |
| --- | --- | --- | --- |
| F-01 | Die Nutzerin kann ihr Tagesbefinden für einen Tag erfassen und wieder ansehen. | 10 | US-01, AT-01 |
| F-02 | Die Nutzerin kann freiwillig eine Zyklusnotiz bzw. eine beobachtete Blutung für einen Tag hinterlegen. | 10 | US-02, AT-02 |
| F-03 | Die Nutzerin kann eine absolvierte Trainingseinheit dokumentieren. | 10 | US-03, AT-03 |
| F-04 | Die Nutzerin kann Training und Befinden für denselben Zeitraum gemeinsam betrachten. | 10 | US-04, AT-04 |
| F-05 | Die Nutzerin kann ihre gespeicherten Einträge gezielt und vollständig löschen. | 10 | US-05, AT-05 |
| F-06 | Die Nutzerin kann die Web-App auf unterstützten Geräten zum Startbildschirm hinzufügen. | 20 | US-06, AT-06 |
| Q-01 | Zyklusangaben sind freiwillig; fehlende Angaben werden als fehlend angezeigt und nicht als bestimmte Phase gedeutet. | 10 | AT-02, AT-04 |
| Q-02 | Der Kernablauf ist auf schmalen Smartphone-Bildschirmen bedienbar; Formulare besitzen verständliche Beschriftungen und Fehlerhinweise. | 10 | AT-07 |
| Q-03 | Der Demo-Datensatz ist vollständig künstlich. Es werden keine persönlichen Gesundheitsdaten im öffentlichen Repository oder in der Präsentation verwendet. | 10 | Datenprüfung vor jeder Veröffentlichung |
| Q-04 | Gespeicherte Eingaben bleiben in der später gewählten Speicherlösung nach erneutem Öffnen sichtbar. Speicherort und Löschung werden verständlich erklärt. | 10 | AT-01, AT-05, AT-08 |
| Q-05 | Die App zeigt beobachtete Angaben und stellt keine unbestätigten Zyklusphasen, Leistungsprognosen oder medizinischen Aussagen als Tatsache dar. | 10 | Inhaltsreview, AT-04 |

## Umfang des ersten Entwurfs

**Zur Diskussion:** Ein Tages-Check-in, eine einfache Trainingserfassung und ein gemeinsamer Verlauf. Freiwilligkeit, Fehlerfälle und Löschung gehören zu diesem Ablauf. Für die Vorstellung soll eine verständliche Visualisierung dieses Ablaufs entstehen; ein prüfbarer Prototyp ist eine mögliche Vertiefung. Eine funktionsfähige App ist damit noch nicht zugesagt.

**Vorläufig außerhalb:** Ernährungstagebuch, Kalorien- und Fotoerkennung, automatische Trainingspläne nach Zyklusphase, KI-Coach, Wearable-Synchronisation, Flo-Import, Social Feed, Bezahlfunktionen und umfassende Übungsbibliothek. Neue Ideen werden im Backlog geparkt, statt still in den Umfang zu rutschen.

## Erfolg und Abnahme

Als ergänzende Methode kann das Team Bedarfshypothesen mit zwei bis drei Gesprächen prüfen und eine Ablaufskizze mit zwei bis drei Personen durchgehen. Diese Anzahl ist keine Vorgabe aus der Mitschrift für M1. Diese kleine Anzahl dient zum Finden von Problemen, nicht zum Belegen einer repräsentativen Marktlücke.

Vorgeschlagenes Nutzbarkeitsziel: Mindestens zwei von drei Testpersonen können im Prototyp einen Check-in und einen Trainingseintrag finden und den Verlauf ohne direkte Hilfe erklären. Zielwert vor dem Test im Team bestätigen; tatsächliche Ergebnisse unverändert dokumentieren.

Die spätere Produktabnahme orientiert sich an den verknüpften Akzeptanztests. Ein getesteter Klickprototyp erfüllt noch keine Anforderungen an Speicherung, Installierbarkeit oder Löschung einer echten App.

## Offene Entscheidungen

Zielgruppe und Kernproblem, verpflichtende Eingaben, Speichermodell, genaue Trainingsdetails, Plattformen, Projektname und finale Anforderungen der Lehrperson sind offen. Änderungen erhalten Datum, Begründung und betroffene IDs in [Entscheidungen](entscheidungen.md).
