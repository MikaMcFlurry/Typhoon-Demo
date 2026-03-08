# Typhoon Demo Website

GitHub-Pages-fertige Demo-Website für **Typhoon**.

## Dateien

- `index.html`
- `styles.css`
- `script.js`
- `typhoon-band.jpg`

## Upload zu GitHub Pages

1. Neues Repository auf GitHub erstellen
2. **Alle Dateien direkt in das Hauptverzeichnis** hochladen
3. In GitHub auf **Settings > Pages** gehen
4. Unter **Build and deployment** die Branch `main` und `/root` wählen
5. Speichern

## Wichtig

- Das Bandbild liegt absichtlich **nicht** in einem `assets`-Ordner, sondern direkt im Hauptverzeichnis.
- In `index.html` noch diese Platzhalter ersetzen:
  - `YOUR-GITHUB-USERNAME`
  - `YOUR-REPOSITORY-NAME`
- Die Auftritte auf der Website sind **Demo-/Platzhaltertermine** und aktuell **keine bestätigten Buchungen**.
- Die Kontakt-E-Mail ist ebenfalls ein Platzhalter.

## Später leicht austauschbar

### Bild austauschen
Einfach `typhoon-band.jpg` durch ein anderes Bild mit demselben Dateinamen ersetzen.

### Neue Termine eintragen
Im Bereich `#events` in der `index.html` die Event-Karten direkt bearbeiten.

### Texte DE/EN anpassen
Alle umschaltbaren Texte liegen in `script.js` im `translations`-Objekt.
