# Birdino Ballspur

PWA zum Auswerten von Golfschlägen aus iPhone-Zeitlupen (Kamera hinter dem Ball):
Ball automatisch finden, Flug verfolgen, Flugbahn als Linie einzeichnen, Tracer-Video erstellen.

## Dateien
- `index.html` – die komplette App (Erkennung, Auswertung, Oberfläche)
- `manifest.webmanifest`, `sw.js` – PWA (Home-Bildschirm, offline)
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – Symbole
- `mp4-muxer.js` – MP4-Erstellung für das Tracer-Video (mp4-muxer 5.2.2, MIT-Lizenz, © 2023 Vanilagy)

## Veröffentlichen
Repo `birdino-ballspur` anlegen, alle Dateien hochladen, unter Settings → Pages
„Deploy from a branch“ (main, root) wählen. Danach in Safari öffnen und
„Zum Home-Bildschirm“.

Bei Änderungen an `sw.js` die Konstante `VERSION` hochzählen.
