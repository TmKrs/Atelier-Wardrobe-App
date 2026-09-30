# Atelier Garderobe

Eine digitale Garderobe: Kleidung fotografieren, nach Kategorien sortieren, Outfits zusammenstellen und im Archiv durchblättern, was als Nächstes angezogen wird.

Die ganze App steckt in einer einzigen Datei (`index.html`). Es braucht keine Installation und keinen Server.

## Funktionen

- **Bibliothek:** Fotos hochladen und in Ordner einsortieren (Pullover, Hosen, Schuhe, Jacken, Taschen, Sport u. a.). Eigene Kategorien lassen sich selbst anlegen.
- **Automatische Erkennung:** Die Farbe wird beim Hochladen aus dem Foto bestimmt, der Hintergrund dezent aufgehellt.
- **Outfit bauen:** Pro Kategorie durch die Teile blättern, einzelne Teile festhalten, neu mischen. Getrennt für Kleidung und Sport.
- **Archiv:** Gespeicherte Outfits in einer Reihe, das am längsten nicht getragene steht vorne.
- **Helles und dunkles Design**, für das Handy optimiert.

## Benutzen

1. `index.html` im Browser öffnen, oder das Repository mit GitHub Pages veröffentlichen (Settings → Pages → Branch `main`).
2. Auf dem iPhone: in Safari auf das Teilen-Symbol tippen und „Zum Home-Bildschirm“ wählen.

## Wo die Daten liegen

Fotos und Outfits werden im Browser des jeweiligen Geräts gespeichert (`localStorage`). Sie verlassen das Gerät nicht und sind nicht Teil dieses Repositories. Jede Person, die die App öffnet, hat ihre eigene, getrennte Sammlung. Der Speicherplatz des Browsers ist begrenzt. Wer den Browserspeicher löscht, verliert die Sammlung.

## Claude-Funktionen

Läuft die Seite als Artifact in claude.ai, kommen zwei Dinge dazu: Claude erkennt Art und Namen eines Kleidungsstücks und schlägt Outfits für Anlass und Wetter vor. Die Sammlung liegt dann in der geteilten Datenablage des Artifacts. Außerhalb von claude.ai sind diese beiden Funktionen nicht verfügbar.

## Technik

HTML, CSS und JavaScript ohne Bibliotheken. Die Schriftarten (Bodoni Moda, Jost) werden von Google Fonts geladen.
