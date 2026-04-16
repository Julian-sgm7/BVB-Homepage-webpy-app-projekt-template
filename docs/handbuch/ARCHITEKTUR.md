# Architektur

## 1. Überblick
Dieses Repository verwendet den Legacy-Quellcode aus `upload/Projektarbeit.zip` als Ausgangsbasis. Die extrahierten Dateien befinden sich unter `legacy-analysis/Projektarbeit`.

Die Architektur des Legacy-Projekts ist als PHP-Webanwendung mit MVC-ähnlicher Aufteilung angelegt:

- `WebContent/index.php` – Startseite
- `WebContent/layouts/` – Seitenlayouts und Content-Blöcke
- `WebContent/controller/RechnerController.php` – Controller-Logik
- `WebContent/model/RechnerModel.php` – Geschäftslogik und Berechnung
- `WebContent/view/RechnerView.php` – Formularanzeige und Ergebnisdarstellung
- `WebContent/css/styles.css` – Styling und Responsive-Design

## 2. Architekturdiagramm
```
Browser
   ↓ HTTP
PHP Frontend (WebContent)
   ├─ index.php
   ├─ layouts/*.php
   ├─ controller/RechnerController.php
   ├─ model/RechnerModel.php
   ├─ view/RechnerView.php
   └─ css/styles.css
```

## 3. Komponenten
### Frontend
- HTML- und PHP-Seiten für die Webseite
- Navigation, Bilder, Inhalte und Formulare
- Responsive-Auslegung über `css/styles.css`

### Controller
- `RechnerController.php` verarbeitet Formular-POSTs
- Validiert Anfragen und erstellt Rückgaben

### Modell
- `RechnerModel.php` enthält Preisberechnung und Ergebnis-Logik
- Wartbare Trennung der Geschäftslogik vom View-Code

### View
- `RechnerView.php` zeigt das Ticketformular und das Ergebnis
- JavaScript unterstützt Benutzerinteraktion

## 4. Architekturziele
- Modularität: klarer Aufbau in Controller, Modell, View
- Wiederverwendbarkeit: Preisberechnung in Model-Klasse
- Erweiterbarkeit: zusätzliche Seiten und Logik möglich
- Dokumentation: zentrale Handbuch-Dateien und Analyse

## 5. Zukunftsausbau
Mögliche Erweiterungen:
- Konvertierung des Legacy-Systems in moderne Microservices
- Nutzung von Python/Flask oder Node.js für API-Endpunkte
- Anbindung einer Datenbank für Persistenz
- Automatisierte Tests für Controller und Geschäftslogik
