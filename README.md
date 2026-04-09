# Darkweather

Ein einfaches Wetter-Widget für Notion, das das aktuelle Wetter in Wien anzeigt.

## Features

- Zeigt Temperatur, Wetterzustand, Windgeschwindigkeit und Sonnenuntergangszeit
- Terminal-ähnliches Design mit Monospace-Schrift
- Automatische Aktualisierung alle 30 Minuten
- Manueller Update durch Klick
- Aktualisiert sich, wenn der Tab wieder sichtbar wird

## Verwendung in Notion

1. Öffnen Sie Ihre Notion-Seite.
2. Fügen Sie einen "Embed"-Block hinzu.
3. Verwenden Sie die URL: `https://raw.githubusercontent.com/reisebuero67/darkweather/main/index.html`

Alternativ können Sie die Datei lokal hosten und die lokale URL verwenden.

## Lokale Entwicklung

1. Klonen Sie das Repository: `git clone https://github.com/reisebuero67/darkweather.git`
2. Starten Sie einen lokalen Server: `python3 -m http.server 8080`
3. Öffnen Sie `http://localhost:8080/index.html` in Ihrem Browser.

## API

Verwendet die Open-Meteo API für Wetterdaten (kostenlos, kein API-Key erforderlich).

## Lizenz

MIT License
