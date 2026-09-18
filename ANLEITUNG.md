# Otter-App auf GitHub Pages veröffentlichen

Alles läuft im Browser. Kein Mac, kein Terminal, kein Git-Programm nötig.
Geschätzte Dauer: 10 Minuten.

## 1. GitHub-Account anlegen

- Auf github.com registrieren, falls noch kein Account vorhanden. Kostenlos.

## 2. Repository erstellen

1. Oben rechts auf **+** → **New repository**.
2. **Repository name**: `otter`
3. **Public** auswählen (bei einem kostenlosen Account nötig, damit Pages funktioniert).
4. **Create repository**.

## 3. Dateien hochladen

1. Im neuen Repository auf **uploading an existing file** klicken
   (oder **Add file** → **Upload files**).
2. Diese fünf Dateien per Drag-and-drop ablegen:
   - `index.html`
   - `manifest.json`
   - `icon-180.png`
   - `icon-192.png`
   - `icon-512.png`
3. Unten auf **Commit changes**.

## 4. Pages aktivieren

1. Im Repository auf **Settings** (oben rechts im Reitermenü).
2. Links auf **Pages**.
3. Unter *Build and deployment* → *Source*: **Deploy from a branch**.
4. Branch: **main**, Ordner: **/ (root)** → **Save**.
5. Ein bis zwei Minuten warten, dann die Seite neu laden. Oben erscheint die
   Adresse, ungefähr so:

   `https://DEINNAME.github.io/otter/`

## 5. Auf dem iPhone installieren

1. Die Adresse in **Safari** öffnen.
2. **Teilen** → **Zum Home-Bildschirm**.
3. **"Als Web-App öffnen"** eingeschaltet lassen.
4. Hinzufügen.

Das Otter-Icon erscheint jetzt korrekt, die App startet im Vollbild, und der
Speicher ist dauerhaft (keine 7-Tage-Löschung wie bei normalen Safari-Seiten).

## 6. Alte Daten übernehmen

1. In der alten Version: Einstellungen → **Export**, Datei sichern.
2. In der neuen Version: Einstellungen → **Import**, Datei auswählen.
3. Danach die alte Installation und den Kurzbefehl löschen, damit nicht zwei
   getrennte Datenstände nebeneinander laufen.

## Später etwas ändern

1. Im Repository auf `index.html` klicken.
2. Auf das Stift-Symbol (**Edit this file**).
3. Ändern → **Commit changes**.
4. Nach etwa einer Minute ist die Änderung live. Die App auf dem iPhone einmal
   komplett schließen und neu öffnen, dann ist die neue Fassung da.

Alternativ schickst du mir die geänderte Datei, und ich baue die Änderung ein —
dann lädst du sie nur noch über **Add file** → **Upload files** hoch und
überschreibst die alte `index.html`.

## Hinweis zum Datenschutz

Ein öffentliches Repository heißt: Der Code der App ist für alle sichtbar.
Deine Aufgaben sind davon nicht betroffen — die werden ausschließlich lokal auf
deinem iPhone gespeichert und nie hochgeladen.
