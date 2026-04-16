# Pflichtenheft

## 1. Zielsetzung
Dieses Repository basiert auf dem Legacy-Quellcode aus `upload/Projektarbeit.zip` und stellt eine analysierbare Projektvorlage für eine BVB-Homepage dar.

Das Ziel ist, die in `upload/README.md` beschriebenen Anforderungen in die Repository-Dokumentation und die Struktur des Projekts zu überführen.

## 2. Ausgangssituation
- Eingelieferte Quellcode-Basis: `upload/Projektarbeit.zip`
- Extrahierter Legacy-Code liegt jetzt in `legacy-analysis/Projektarbeit`
- Zusätzliche Hilfsdateien: `upload/README.md`, `upload/schueler_julian_korrekturhilfe_draft.md`, `upload/schueler_julian_korrekturhilfe_draft.html`

## 3. Systemanforderungen
### Kernanforderungen
- Webbasierte App-Anwendung mit responsivem Frontend
- Klare Trennung von Layout, Controller, Modell und View (MVC)
- Dokumentation der Anforderungen und Architektur
- Sicherheit: Eingabeverarbeitung und Validierung
- Wiederverwendbarkeit und Modularität
- Testbarkeit und Wartbarkeit
- Persistenzfähigkeit für zukünftige Erweiterungen

### Funktionale Anforderungen
- Darstellung einer BVB-Startseite mit Navigation
- Anzeige von Mannschaften, Tickets, Shop und Service
- Ticketbuchungsformular mit Berechnung der Gesamtkosten
- Auswahl unterschiedlicher Blöcke mit dynamischer Preisberechnung
- Ausgabe einer Bestätigungsmeldung für den Buchungsvorgang

### Nicht-funktionale Anforderungen
- Responsive Darstellung auf mobilen Geräten
- Sichere Behandlung von Benutzereingaben
- Dokumentierte Systemarchitektur
- Umfassende Projektdokumentation im Handbuch
- Nachvollziehbare Legacy-Analyse

## 4. Technische Voraussetzungen
- Basisprojekt: PHP-Webanwendung mit `<WebContent>`-Struktur
- MVC-ähnliches Muster durch `controller/`, `model/` und `view/`
- CSS-Layout unter `css/styles.css`
- Bilder und Assets unter `img/`
- Auszug aus dem Upload-Repository als Startpunkt für Weiterentwicklung

## 5. Dokumentationsanforderungen
Die folgenden Dokumente werden für das Repo erstellt:
- `docs/handbuch/PFLICHTENHEFT.md`
- `docs/handbuch/ARCHITEKTUR.md`
- `docs/handbuch/INDEX.md`
- `docs/handbuch/README.md`
- `docs/handbuch/legacy-analysis/README.md`
- `legacy-analysis/README.md`

## 6. Akzeptanzkriterien
- Alle angegebenen Dokumente existieren und sind verlinkt
- Das Legacy-Projekt ist im Repository verfügbar
- Die Repository-README verweist auf die erstellten Dokumente
- Die Anforderungen aus `upload/README.md` sind analysiert und dokumentiert
