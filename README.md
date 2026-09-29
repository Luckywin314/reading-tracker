# Lesetracker

Kleine, mobile-first Progressive Web App zum Erfassen gelesener Seiten.

## Funktionen

- Datum standardmäßig auf heute
- Buch auswählen oder neue Bücher anlegen
- gelesene Seiten eintragen
- Summen für heute, laufende Woche und laufenden Monat
- letzte Einträge anzeigen
- lokale Speicherung in IndexedDB
- JSON-Backup und -Import
- offlinefähig per Service Worker
- als Web-App auf dem iPhone-Home-Bildschirm nutzbar

## GitHub Pages veröffentlichen

1. Repository auf GitHub anlegen (z. B. `reading-tracker`).
2. Diese Dateien in den Default-Branch hochladen.
3. In **Settings → Pages** unter **Build and deployment** `Deploy from a branch` wählen.
4. Branch `main` und Ordner `/ (root)` auswählen und speichern.
5. Die von GitHub angezeigte Pages-URL in Safari öffnen.
6. Auf dem iPhone: **Teilen → Zum Home-Bildschirm → Als Web-App öffnen**.

## Datenschutz / Speicherung

Alle Bücher und Leseeinträge bleiben lokal im Browser bzw. in der installierten Web-App. GitHub erhält nur den App-Code, nicht die eingegebenen Lesedaten.

Regelmäßig **JSON exportieren** und die Datei z. B. in iCloud Drive ablegen. Browser-/Website-Daten können sonst bei einem Reset verloren gehen.
