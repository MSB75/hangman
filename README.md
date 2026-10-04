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


## iPad-Icon aktualisieren
Nach einem Icon-Update muss eine bereits installierte Home-Bildschirm-App einmal gelöscht und anschließend in Safari erneut über „Zum Home-Bildschirm“ installiert werden. iPadOS speichert das alte Home-Bildschirm-Icon unabhängig vom normalen Website-Cache.
