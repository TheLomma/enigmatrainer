# Bletchley Park

Ein vollständiges Übungs-Tool für das **Enigma**-Zaubersystem von Christian Grace.

## Features

- Wort-Analyse – Berechnet Passcode, Binärsequenz, Vokalposition, Buchstabenform und Spracheingabe-Satz
- Quiz-Modus – Zufällige Fragen zu jedem Wort
- Drill-Modus – Passcode selbst berechnen und prüfen
- Zweisprachig – Deutsch / Englisch umschaltbar
- PWA – Installierbar auf dem Homebildschirm

## Deployment auf Vercel

### Option 1 – Vercel CLI
```
vercel
```

### Option 2 – GitHub + Vercel Dashboard
1. Diesen Ordner als GitHub-Repository pushen
2. Auf vercel.com einloggen -> New Project
3. GitHub-Repo verbinden -> Deploy
4. Fertig

## Lokale Vorschau
index.html direkt im Browser öffnen – keine Installation nötig.

## PWA installieren
Nach dem Deployment:
- iOS: Safari -> Teilen -> "Zum Homebildschirm"
- Android: Chrome -> Menue -> "Zum Startbildschirm"
- Desktop: Chrome/Edge -> Adressleiste -> Install-Icon

## Dateistruktur
```
enigma-trainer/
    index.html
    manifest.json
    service-worker.js
    vercel.json
    favicon.ico
    README.md
    icons/
        icon-72x72.png
        icon-96x96.png
        icon-128x128.png
        icon-144x144.png
        icon-152x152.png
        icon-180x180.png
        icon-192x192.png
        icon-384x384.png
        icon-512x512.png
```
