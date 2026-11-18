# Anforderungen · Unser kurzes Lastenheft

**Status: Entwurf.** Dieses Dokument beschreibt die geplanten Funktionen und Qualitätsregeln. Ziel, Motivation und Erfolgskriterien stehen in [Unser Ziel](00-projektziel.md).

## Was gehört zuerst dazu?

Unser Kern ist **Befinden festhalten → Training eintragen → gemeinsamen Verlauf ansehen**. Freiwillige Zyklusangaben und Löschung gehören dazu. Ernährung, automatische Trainingspläne, Wearables, Flo-Import und soziale Funktionen bleiben zunächst draußen.

Prioritäten: **10 = im Kern zuerst nötig; 20 = danach sinnvoll; 50 = später.** Die Reihenfolge der Stories steht im [Backlog](04-user-stories.md). Eine hohe Priorität heißt nicht, dass alles gleichzeitig entwickelt wird.

## Funktionen – was die Nutzerin tun kann

| ID | Anforderung | Prio | Story / Prüfung |
| --- | --- | --- | --- |
| **F-01** | Für einen Tag die eigene Energie von 1 bis 5 festhalten, wieder ansehen und bei Bedarf ändern. | 10 | US-01 / AT-01 |
| **F-02** | Für einen Tag freiwillig eine beobachtete Blutung angeben oder die Angabe weglassen. | 10 | US-02 / AT-02 |
| **F-03** | Ein absolviertes Training mit Datum, Sportart und Dauer in Minuten eintragen und wieder ansehen. | 10 | US-03 / AT-03 |
| **F-04** | Training, Befinden und vorhandene Zyklusangaben gemeinsam nach Datum ansehen. | 10 | US-04 / AT-04 |
| **F-05** | Einzelne sowie alle eigenen Einträge löschen. Vor der Gesamtlöschung erklären wir, was entfernt wird, und fragen nach Bestätigung. | 10 | US-05 / AT-05 |
| **F-06** | Die Web-App auf den vereinbarten Geräten zum Startbildschirm hinzufügen und dort öffnen. Ohne Installation bleibt sie im Browser nutzbar. | 20 | US-06 / AT-06 |

## Qualitätsregeln – wie die App funktionieren soll

| ID | Regel | Prüfung |
| --- | --- | --- |
| **Q-01** | Zyklusangaben sind freiwillig. „Keine Angabe“ wird nicht als „keine Blutung“ oder als Zyklusphase behandelt. | AT-02, AT-04 |
| **Q-02** | Der Kernablauf ist am Handy verständlich und bedienbar. Beschriftungen, Fehlerhinweise und Tastaturfokus sind erkennbar. | AT-07, BT-01; Zielwert siehe Z-04 |
| **Q-03** | Im öffentlichen Repo und in der Demo verwenden wir nur künstliche Beispieldaten. | Datenprüfung vor Veröffentlichung |
| **Q-04** | Gespeicherte Daten bleiben nach erneutem Öffnen in der gewählten Speicherlösung erhalten. Ein Speicherfehler wird gemeldet und nicht als Erfolg angezeigt. Speicherort und Löschung werden erklärt. | AT-01, AT-05, AT-08 |
| **Q-05** | Die App zeigt Einträge, keine unbestätigten Leistungsprognosen, Ursachen oder berechneten Zyklusphasen. | AT-04 und Inhaltsprüfung |

Alle Qualitätsregeln gehören zum Kern. Die späteren [Prüfungen](07-erhebung-und-qualitaet.md) zeigen, wie wir sie kontrollieren.

## Vorgesehene Eingaberegeln

Die Eingaberegeln gehören zum aktuellen Entwurf. Änderungen werden in Stories, Entwurf und Tests übernommen.

- **Tages-Check-in:** Datum und Energie sind nötig. 1 bedeutet sehr wenig, 5 sehr viel Energie. Pro Tag gibt es einen Check-in; ein vorhandener wird zum Ändern geöffnet.
- **Training:** Datum, Sportart und Dauer sind nötig. Zunächst ganze Minuten größer als null. Ein absolviertes Training liegt heute oder in der Vergangenheit. Mehrere Trainings pro Tag sind möglich.
- **Zyklusangabe:** freiwillige Angabe zu einer beobachteten Blutung. Weglassen bedeutet unbekannt, nicht „nein“. Die konkrete Beschriftung prüfen wir im Entwurf.
- **Fehler und Abbruch:** Fehler erklären, andere Formulareingaben behalten. Abbrechen legt keinen neuen Eintrag an.
- **Datum:** Einträge werden dem lokalen Kalendertag zugeordnet, den die Nutzerin ausgewählt hat.

## Was wir noch entscheiden

Zielgruppe und Kernumfang bestätigen; Eingaberegeln prüfen; unterstützte Geräte, Speicher und Technik wählen. Ein Account ist bisher nicht erforderlich. Ob wir einen brauchen, hängt vom vereinbarten Bedarf ab. Zuständigkeiten und Termine werden in den zugehörigen Issues erfasst.
