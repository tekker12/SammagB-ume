# Bäume hassen dich (100 Level)

Eigenständige HTML5-Web-App (3/4-Top-Down) für Android-Smartphones (PWA) und Desktop-Browser mit 100 deterministisch erzeugten Leveln und ansteigender Schwierigkeit.

## Funktionen
- 100 Level in 10 Biomen (je 10 Level pro Biom, inklusive Meilenstein-Leveln auf 10, 20, ..., 100).
- Kontinuierliche Schwierigkeitssteigerung pro Level: höhere Fall-, Projektil-, Rollstamm- und Verfolger-Geschwindigkeiten, kürzere Reaktionsfenster und kombinierte Fallen-Segmente.
- Alle Fallentypen integriert: Fall-Bäume, Revolver-Bäume, trügerische Weggabelungen, Verfolger-Bäume mit Felslücken, rollende Baumstämme mit Ausweichbuchten, Scharfschützen mit verschiebbaren Deckungsstämmen, Sprungbaum-Erdflecken, explodierende Äpfel, Hand-Baum-Axtköder sowie der Pause-Menü-Gag („Baum prüfen“).
- Dynamischer virtueller Analog-Joystick für Touchscreens sowie WASD/Pfeiltasten am Desktop.
- Charakter-Editor (Hut, Brille, Hemd- und Haarfarbe), Normal-Modus (Level-Fortschritt) und Challenge-Modus (Hardcore-Durchlauf ab Level 1).
- Offline-fähig durch Service Worker (`sw.js`) und installierbar über `manifest.json`.

## Veröffentlichung über GitHub Pages
1. Repository auf GitHub anlegen oder bestehendes Repository öffnen.
2. Alle Dateien aus diesem Paket (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `.nojekyll`, `README.md`, `LICENSE`) in das Hauptverzeichnis des Branches `main` hochladen.
3. Unter **Settings -> Pages** als Quelle **Deploy from a branch**, Branch `main` und Ordner `/ (root)` auswählen und speichern.
4. Die Web-App unter `https://<benutzername>.github.io/<repository-name>/` öffnen und in Chrome auf Android über „Zum Startbildschirm hinzufügen“ installieren.

## Lizenz
MIT License (siehe `LICENSE`).
