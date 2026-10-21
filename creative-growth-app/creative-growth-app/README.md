# creative growth – persönlicher Lernplaner

Eine mobile Web-App (PWA) für Aufgaben, Lernpfade, Wochenplanung, ein Möbel-Design-Projekt und Wochenrückblicke.

## Was funktioniert?
- Aufgaben hinzufügen, abhaken und löschen
- Lernziele und Gewohnheiten verfolgen
- Wochenfokus und Projekt-Notizen speichern
- Wochenrückblick speichern
- Daten lokal im Browser sichern und als JSON exportieren
- Installierbar als Web-App, wenn sie über HTTPS gehostet wird
- Grundlegende Offline-Unterstützung durch Service Worker

## Lokal testen
Öffne `index.html` im Browser. Die Kernfunktionen laufen lokal; die Installierbarkeit und Offline-Funktion brauchen einen HTTPS-Host oder lokalen Entwicklungsserver.

## Auf dem Handy verwenden
Die Dateien müssen auf einen HTTPS-Webhost hochgeladen werden (z. B. GitHub Pages oder Netlify). Danach:
- iPhone: Link in Safari öffnen → Teilen → „Zum Home-Bildschirm“
- Android: Link in Chrome öffnen → Menü → „App installieren“ oder „Zum Startbildschirm hinzufügen“

## Wichtig zur Datenspeicherung
Die Daten liegen zunächst lokal in deinem Browser auf diesem Gerät. Sie werden nicht automatisch zwischen Handy und Computer synchronisiert. Für geräteübergreifende Synchronisierung braucht es später ein Backend bzw. eine Datenbank.
