# Legacy-Code Analyse

Dieses Dokument beschreibt die Übernahme und Bewertung des Legacy-Quellcodes aus `upload/Projektarbeit.zip`.

## Beobachtungen
- Der Quellcode ist als PHP-Webprojekt aufgebaut.
- Es existieren klare MVC-Elemente: `controller/`, `model/`, `view/`.
- Die Startseite ist in `index.php` definiert.
- Die Ticketberechnung erfolgt in `RechnerModel.php`, die Formularverarbeitung in `RechnerController.php`.
- Das Frontend nutzt statisches CSS in `css/styles.css` und Bildinhalte in `img/`.

## Risiken und Chancen
### Risiken
- Kein Datenbank-Layer vorhanden
- Eingabeverarbeitung ist aktuell nur minimal validiert
- Legacy-Struktur fehlt moderne Build- und Deployment-Skripte

### Chancen
- Gute Ausgangsbasis für eine Übergangsphase in ein modernes Projekt
- Bestehende Business-Logik kann als Referenz wiederverwendet werden
- Struktur bietet eine einfache Erweiterung um weitere Seiten und Module

## Nächste Schritte
1. Review der bestehenden MVC-Aufteilung
2. Dokumentation der Anforderungen im Pflichtenheft
3. Aufbau einer modernen Projektstruktur basierend auf der Legacy-Basis
4. Ergänzung von Tests und Automatisierungsskripten

## Pfad zum extrahierten Quellcode
- `legacy-analysis/Projektarbeit/`
- `legacy-analysis/Projektarbeit/WebContent/`
- `legacy-analysis/Projektarbeit/WebContent/controller/`
- `legacy-analysis/Projektarbeit/WebContent/model/`
- `legacy-analysis/Projektarbeit/WebContent/view/`
