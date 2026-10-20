# Foto-Finanzen – Einrichtung

## Dateien
Alle diese Dateien gehören zusammen und müssen im selben Ordner liegen (bzw. im selben GitHub-Repository):

- `index.html` – die App
- `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – damit sich die Seite auf dem Handy wie eine App installieren lässt

## Hosting mit GitHub Pages (kostenlos)
1. Kostenloses GitHub-Konto anlegen und ein neues Repository erstellen, z. B. `foto-finanzen`.
2. **Alle** Dateien oben hochladen (Add file → Upload files).
3. Unter **Settings → Pages**: „Deploy from a branch", Branch `main`, Ordner `/ (root)`.
4. Nach kurzer Zeit ist die Seite erreichbar unter `https://DEINNAME.github.io/foto-finanzen/`.

Am PC öffnest du den Link ganz normal im Browser.

## Als App auf dem Android-Handy installieren
1. Den Link in **Chrome** auf dem Handy öffnen.
2. Menü (⋮) → **„App installieren"** bzw. „Zum Startbildschirm hinzufügen".
3. Die App erscheint mit Kamera-Icon auf dem Startbildschirm und startet ohne Browserleiste.

Updates: Wenn du eine neue `index.html` bei GitHub hochlädst, holt sich die App sie beim nächsten Öffnen mit Internetverbindung automatisch. Falls noch die alte Version erscheint, die App einmal komplett schließen und neu öffnen.

## Daten zwischen Handy und PC abgleichen
**Automatisch (Chrome/Edge):** Oben auf „Datei wählen/erstellen" klicken und eine Datei in deinem lokal synchronisierten OneDrive-Ordner wählen (z. B. `foto-finanzen-daten.json`). Danach speichert die App jede Änderung dort hinein. Auf dem zweiten Gerät dieselbe Datei auswählen. Der Browser merkt sich die Auswahl.

Ob dein Handy-Chrome diese Funktion unterstützt, prüft die App selbst. Wenn nicht, siehst du stattdessen die Buttons **Exportieren** und **Importieren**:
1. Auf dem Gerät mit dem neuesten Stand auf **Exportieren** tippen und die Datei in OneDrive ablegen.
2. Auf dem anderen Gerät die Datei aus OneDrive holen und auf **Importieren** tippen.

## Hinweis
Ohne Datei-Sync liegen die Daten nur im Browser-Speicher des jeweiligen Geräts. Browserdaten für die Seite nicht löschen, und ab und zu exportieren als Backup.
