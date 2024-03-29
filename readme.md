# 3Div

not maintained anymore

Das Projekt wird nicht mehr weiterentwickelt, da u. a. Firefox das 3D-Untersuchungtstool aus dem Standard-Toolset entfernt hat und ich außerdem andere Projekte im Kopf habe.

--------------------------

## Idee

3Div ist ein 2D-Editor für die 3D-Untersuchung von Firefox, bzw. das leider nicht mehr weiterentwickelte Firefox-Addon Tilt.

Die Idee dahinter ist, auf spielerische Weise Quellcodes zu erkunden und gleichzeitig 3D-Modelle zu erstellen. Das Script selbst dient dabei als Basis um in verschiedene Richtungen damit weiter arbeiten zu können, z. B.:

- Mozilla X-Ray-Goggles -> Inhalte der HTML-Elemente verändern
- Benutzung der Firefox-Entwickler-Tools
 - Inhalte und Styles bearbeiten
 - Javascript-Konsole
- Export für Blender
- animierte Gifs aus Screenshots der 3D-Animation erstellen
- Screenshots machen, arrangieren, kurzer Exkurs 72dpi/300dpi
  - ausdrucken - etwas in der Hand haben für zu Hause
  - Seite einrichten --> Hintergrund drucken

Die [Anleitung](docs/manual.md) ist in den Docs-Ordner verschoben.

## Installation

Zip-Archiv herunterladen, entpacken und auf eigenem Server hochladen.

Kommandozeile:

```bash
cd ~/html
git clone https://github.com/raffaelj/3div.git
```

anschließend eigene-domain.de/3div aufrufen

## To Do

3Div ist mein erstes Javascript-Projekt, weshalb die Entwicklung nur langsam vorangeht und noch einige Fehler zu beheben, Sicherheitslücken zu schließen und Features hinzuzufügen sind.

- [ ] selektierte Elemente kopieren <kbd>Strg</kbd> + <kbd>C</kbd> und <kbd>Strg</kbd> + <kbd>V</kbd>
- [ ] Rückgängig <kbd>Strg</kbd> + <kbd>Z</kbd>
- [ ] Direkteingabe um Objekt zu ändern --> bis jetzt Firefox-Entwickler-Tools
- [ ] verwendete Farben speichern/auslesen und wiederverwenden --> bis jetzt Firefox-Entwickler-Tools-ColorPicker + externe Hex2Dec-Umrechnung
- [ ] Autosave
- [ ] Präsentations-Galerie
- [x] grobe Dokumentation
- [ ] ausführliche Dokumentation
- [ ] Option: Bilder einfügen
- [ ] Option: Text einfügen --> bis jetzt umständlich über FF-Entwickler-Tools (kopierten Text als Kindelement einfügen)
- [ ] Nutzerverwaltung
- [x] Objekt löschen
- [x] Kreisfunktion
- [x] Wendelfunktion
- [ ] Kugelfunktion
- [ ] Felder-erzeugen-Funktion (z. B.  100px * 100px geteilt in 10 * 10 Blöcke)
- [x] resizable --> Developer-Tools --> width und height anpassen
- [ ] Quellcode serverseitig ausgeben, sodass er mit <kbd>Strg</kbd>+<kbd>U</kbd> sichtbar ist --> Reload nötig
- [x] Tastaturkürzel
- [ ] benutzerdefiniertes CSS hinzufügen
- [x] Node-Reihenfolge ändern --> "oben"/Überlagerung auf selber Ebene --> z-index
- [x] Layer-Ebene am Ende --> "oben"/Überlagerung auf verschiedenen Ebenen --> z-index
- [x] Autoload Demo-Datei
- [x] Warnung beim Verlassen der seite --> nervt aber während Entwicklung...
- [ ] Raster-Icon als reines CSS-Icon --> momentan noch in 3D-Ansicht sichtbar
- [ ] Formular in Javascript auslagern
- [ ] jQuery gegen reines Javascript ersetzen
- [x] auf Github veröffentlichen
- [ ] Lizenz --> auf jeden Fall Open Source und freie Nutzung, aber welche der zig möglichen Lizenzen...?
- [ ] Modul: Gif-Animationen erstellen
- [ ] Modul: Basics HTML und CSS
- [ ] Impressum
- [ ] Datenschutz-Hinweise
- [ ] Hausordnung -> nichts illegales veröffentlichen, kein Mobbing etc.
- [ ] evtl. Objekte rotieren mit CSS-Transform --> ist aber in 3D-Ansicht nicht gedreht
- [ ] Link generieren um Entwurf teilen zu können (ähnlich wie bei Mozilla Webmaker: [Thimble](https://thimble.mozilla.org/), [X-Ray-Goggles](https://webmaker.org/goggles))
- [ ] Sammlung mit Internetseiten, die spannend in 3D aussehen
- [ ] WebGl direkt auf Seite anstatt mit Plugin, da seit FF47 die integrierte 3D-Untersuchung abgeschafft wurde

Autor des 3Div-Scripts: [Raffael Jesche](http://www.raffael.one)

Quellcode: [3Div](https://github.com/raffaelj/3div)
