# Gemeinsam am Projekt arbeiten

Wir verwenden einfache Markdown-Dateien, die sich direkt auf GitHub bearbeiten lassen. Eine lokale Entwicklungsumgebung ist für den Projektstart nicht nötig.

## Erste Schritte auf GitHub

1. Repository öffnen und [START-HIER.md](START-HIER.md) gemeinsam durchgehen.
2. Der Repository-Eigentümer lädt die drei anderen Mitglieder über **Settings → Collaborators** mit ihren bestätigten GitHub-Nutzernamen ein. Jede Person nimmt ihre Einladung an. Diese Einladungen sind im Startpaket noch offen.
3. Unter **Issues** eine passende Aufgabe auswählen. Zuständigkeit über **Assignees** setzen, sobald Zugriff besteht. Eine zweite Person als Prüferin oder Prüfer im Aufgabentext nennen.
4. Im zuständigen Dokument auf den Bearbeiten-Stift klicken. Eine neue Branch vorschlagen, beispielsweise `docs/t05-user-stories`, und einen Pull Request öffnen.
5. Im Pull Request beschreiben, was sich geändert hat und wie es geprüft wurde. Eine andere Person liest gegen. Nach Klärung offener Punkte kann der PR zusammengeführt werden.

Das ist unsere Arbeitsvereinbarung. Eine technische Branch-Schutzregel wurde nicht eingerichtet; GitHub erzwingt diesen Ablauf derzeit nicht.

## Aufgabenstatus

Im Issue steht oben genau einer dieser Zustände: **Offen**, **In Arbeit**, **Zur Prüfung**, **Blockiert** oder **Erledigt**. Offene Issues sind der gemeinsame Aufgabenbestand. „Blockiert“ enthält den konkreten Grund und den nächsten Klärungsschritt. Ein Issue erst schließen, wenn seine Fertig-Kriterien erfüllt und das Ergebnis geprüft ist.

Ein separates GitHub-Projects-Board ist für den Start optional und wurde nicht vorausgesetzt. Wenn ihr später eines anlegt, nutzt diese Zustände als Spalten und pflegt den Status anschließend ausschließlich dort. Das verhindert widersprüchliche Doppelpflege.

## Was gehört wohin?

- **User Stories:** fachlicher Inhalt und Akzeptanzkriterien in `docs/04-user-stories.md`. Issue referenziert die Story-ID.
- **Aufgaben:** Zuständigkeit, Aufwand, Zieltermin, Hindernisse und Ergebnislink im Issue.
- **Änderungswünsche und Recherchefragen:** eigene Issue-Vorlage; nach Entscheidung betroffene Anforderungen aktualisieren.
- **Entscheidungen:** `docs/entscheidungen.md`, mit Begründung und Bezug zum Issue.
- **Besprechungen:** eine Datei je tatsächlichem Treffen in `docs/protokolle/`.
- **Prototypen:** eigene Entwürfe in `design/`, jeweils mit Versionsdatum und Bezug zu Stories.

In PRs nur `Closes #Nummer` verwenden, wenn der gesamte Inhalt des Issues abgeschlossen wird. Ein Entwurfs-PR verweist mit `Refs #Nummer`, damit eine noch nicht durchgeführte Interview- oder Testaufgabe offen bleibt.

## Öffentliches Repository

Keine originalen Vorlesungsunterlagen, Interviewrohnotizen, Zugangsdaten oder echten Gesundheitsdaten hochladen. `.gitignore` hilft lokal, verhindert aber keine manuellen Browser-Uploads. Ergebnis und Dateiliste vor jedem Upload prüfen. Nur eigene oder zur Veröffentlichung freigegebene Bilder verwenden.

KI-Unterstützung und fremde Quellen nachvollziehbar kennzeichnen. Übernommene Komponenten mit Quelle und Lizenz dokumentieren; nicht behaupten, fremder Code sei eigene Entwicklung. Die konkreten Hochschulvorgaben werden in T-02 geklärt.

## Lokal arbeiten, wenn gewünscht

Das öffentliche Repository lässt sich über den **Code**-Button klonen. Änderungen über eigene Branch und Pull Request teilen. Der beim Projektinitiator bereits vorhandene Ordner `Vorlesungsmaterial/` bleibt lokal ignoriert und erscheint deshalb nicht in einem frischen Klon.
