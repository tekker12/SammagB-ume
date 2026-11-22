# sams bäume– Version 6 (Rage-Mode & Troll-Upgrade)

Eigenständige 2.5D-Diorama-Web-App für Android (PWA) und Desktop mit 100 Leveln, drei Spielmodi (Normal, Challenge, Rage-Mode) und Network-First-Update-Strategie.

## Neuerungen in Version 6
- Eigenständiger Rage-Mode (dritter Spielmodus) mit roter Eskalations-Beleuchtung, Level-Timer samt nachrückender Tannen-Wand bei Zeitablauf, sporadischer 1,5-s-Steuerungsumkehr nach Signalton und todeszahlabhängigen Sprüchen.
- Fake-Sieg-Bildschirm: Auf ausgewählten Leveln erscheint kurzzeitig das normale Siegesfenster, bevor es zerschmettert wird und eine finale Tannen-Salve folgt.
- Ausweichender UI-Button: Im Rage-Mode springt der „Weiter“-Button beim ersten Antippen zur Seite.
- Felsen-Impostor: Einzelne Felsen in der Felslücke bewegen sich bei Annäherung seitlich.
- Katapult-Platten: Unauffällige Kopfsteinpflaster-Platten schleudern die Figur rückwärts.
- Audio-Finte: Gelegentliches Revolver-Klick-Klack ohne Schuss.
- Revolver-Tür: Die Ziel-Hütte feuert beim Annähern einen Schuss aus der Tür ab, bevor sie betretbar wird.
- Network-First Service Worker (`sw.js`, Cache `v6`): Alle Geräte laden bei Internetverbindung automatisch die aktuelle Version.

## Update auf GitHub Pages
1. Archiv lokal entpacken.
2. Alle sieben Dateien im Branch `main` über „Dateien hochladen“ ersetzen und committen.
