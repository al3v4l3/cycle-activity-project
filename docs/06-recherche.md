# Vorhandene Lösungen und Wiederverwendung

**Erste Quellenprüfung: 11.11.2026.** Dokumentationsrecherche, keine praktischen Integrationstests. Zugang, Preise, Nutzungsbedingungen und technische Grenzen können sich ändern. Das Team prüft ausgewählte Komponenten vor einer verbindlichen Zusage erneut.

## Bedarf und Wettbewerb

Die Annahme, es gebe noch keine zyklusbewusste Fitness-App, trägt nicht als Alleinstellungsmerkmal: [Wild.AI](https://wild.ai/about) beschreibt ein entsprechendes Angebot mit Zyklus-, Symptom- und Trainingsbezug. Das belegt die Existenz eines Wettbewerbers, nicht die Qualität oder medizinische Wirksamkeit seiner Aussagen.

Yazio, Bevel und Flo stammen aus der Projektidee und bilden weitere Vergleichskandidaten. Ihre konkreten Funktionen, Preise und verfügbaren Entwicklerzugänge wurden hier nicht vollständig untersucht. „Wir möchten eine einfachere gemeinsame Sicht für unsere Zielgruppe“ ist vorerst eine Hypothese.

Für T-04 drei Angebote anhand derselben konkreten Aufgabe vergleichen: Training erfassen, Tagesbefinden ergänzen und beide Einträge wiederfinden. Plattform, Sprache, Kostenmodell, freiwillige Angaben, Eingabeaufwand, Datenkontrolle und fehlende Funktionen festhalten. Quelle, Datum und „selbst getestet“ versus „Anbieterbeschreibung“ unterscheiden. Keine Gesundheitsdaten für den Vergleich veröffentlichen.

## Technische Kandidaten

| Kandidat | Wofür verwendbar? | Was ist belegt / offen? | Vorschlag |
| --- | --- | --- | --- |
| [Vite PWA](https://vite-pwa-org.netlify.app/) | Manifest und Service Worker für eine spätere Web-App | Plugin und Offline-Unterstützung dokumentiert; Framework und Installation auf Teamgeräten noch nicht geprüft | Kandidat nach Anforderungsklärung |
| [wger](https://github.com/wger-project/wger) | Vorhandenes Fitnessprojekt und möglicher Übungskatalog/API-Ausgangspunkt | Repository dokumentiert REST-API; Code unter AGPL-3.0, Übungsinhalte mit separaten Bedingungen. Die API-Webseite ließ sich bei dieser Recherche nicht inhaltlich auslesen. Endpunkte, deutsche Abdeckung und Bildrechte offen | Nur prüfen, wenn ein Übungskatalog tatsächlich nötig wird |
| [Open Food Facts](https://openfoodfacts.github.io/openfoodfacts-server/api/) | Produkt- und Nährwertdaten, etwa spätere Barcode-Suche | Öffentliche API-Dokumentation vorhanden; Datenqualität, Limits, Attribution und Datenbanklizenz vor Nutzung prüfen | Ernährung bleibt vorerst außerhalb des Umfangs |
| [Apple HealthKit](https://developer.apple.com/documentation/healthkit) | Zugriff auf Gesundheitsdaten in unterstützten nativen Apple-Apps mit Berechtigung | Apple dokumentiert ein Plattform-Framework. Daraus folgt für unsere Architektur: kein direkt einplanbarer HealthKit-Zugriff aus einer reinen Browser-PWA | Manueller Check-in zuerst, native Erweiterung später prüfen |
| [Flo-Hilfe zur Health-Anbindung](https://help.flo.health/hc/en-us/articles/34890229122068-How-to-import-data-from-the-Health-app-to-Flo-iOS) | Belegt eine Verbindung zwischen Flo und Apple Health | Die Hilfe sagt ausdrücklich, dass in Flo protokollierte Menstruationsdaten nicht an Health übertragen werden. Das ist keine öffentliche Flo-API für unser Projekt; ein nutzbarer Entwicklerzugang wurde nicht verifiziert | Keine Flo-Integration versprechen |
| [Capacitor](https://capacitorjs.com/docs) | Spätere native Hülle um eine Web-App und Zugriff über native Plugins | Native Runtime und Plugin-Schnittstellen dokumentiert. Ein passendes HealthKit-Plugin, Berechtigungen, Testgeräte und Betrieb sind noch zu prüfen | Spätere Option, keine notwendige Startabhängigkeit |

**PWA bedeutet nicht automatisch native Gerätezugriffe.** Auch die Installation unterscheidet sich zwischen Plattformen. Laut [MDN zur Installierbarkeit](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Making_PWAs_installable) hängen Angebot und Ablauf vom Browser ab. Ein überall identischer „Installieren“-Knopf wird nicht zugesagt; für unterstützte iPhones kann eine manuelle Startbildschirm-Anleitung nötig sein.

## Auswahlverfahren für T-04

Für jeden ernsthaft erwogenen Baustein eine kurze Notiz anlegen:

1. Welche konkrete Anforderung deckt er ab?
2. Ist der Zugang für uns möglich, und welche Limits/Kosten gibt es?
3. Darf Code, Datenbank und Bildmaterial jeweils wie geplant verwendet werden? Welche Quellenangaben sind nötig?
4. Funktioniert die Verbindung von unserer Zielplattform? Welche Daten würden wohin übertragen?
5. Wie aufwendig sind Integration, Tests und Wartung? Gibt es einen einfachen Ersatz bei Ausfall?
6. Ergebnis: übernehmen, später prüfen oder verwerfen; mit Quelle und Begründung.

Mehr Bibliotheken sind kein eigenes Qualitätsziel. Wir übernehmen einen Baustein, wenn er eine bestätigte Anforderung mit weniger Gesamtaufwand erfüllt. Für den ersten Prototyp sind künstliche Daten und manuelle Eingaben ausreichend. Kein API-Schlüssel gehört in Frontend-Code oder ins öffentliche Repository.
