# Galgenmännchen – Offline-PWA

## Dateien
- `index.html` – vollständige App
- `manifest.webmanifest` – PWA-Metadaten
- `sw.js` – Offline-Cache
- `icons/` – reduzierte Schwarz-Weiß-Appsymbole

## Lokal testen
Ein Service Worker funktioniert nicht über `file://`. Starte im Ordner einen lokalen Webserver, z. B.:

```bash
python3 -m http.server 8080
```

Dann `http://localhost:8080` öffnen.

## GitHub Pages
Den gesamten Ordner in ein Repository hochladen und GitHub Pages für den gewünschten Branch aktivieren. Nach dem ersten vollständigen Laden ist die App offline nutzbar.

## iPad
In Safari öffnen → Teilen → „Zum Home-Bildschirm“.

Hinweis: Die optionale Web-Spracherkennung hängt von Browser und Betriebssystem ab und ist nicht in jeder Umgebung offline verfügbar. Die Texteingabe und die iPad-Diktierfunktion bleiben als verlässliche Alternativen erhalten.


## Version 1.3
- Lösungswort bleibt unabhängig von der Länge immer in einer Zeile.
- Hinterlegte Wörter sind im Wortlisten-Spielmodus nicht sichtbar; angezeigt wird nur die Anzahl.
- Nach Spielende kann das Lösungswort mit der Systemstimme vorgelesen werden.

- Zwei Schwierigkeitsvarianten: Normal baut Galgen und Figur über elf Fehler auf; Schwer startet mit vorhandenem Galgen und sechs Fehlern.
- In Normal: 1. Bodenlinie, 2. senkrechter Mast, 3. waagerechter Querbalken, 4. diagonale Stütze, 5. Seil, anschließend die sechs Körperteile.
