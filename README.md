# Typhoon Demo Website

Fertige statische Band-Website für GitHub Pages.

## Dateien

- `index.html` – Hauptseite
- `styles.css` – komplettes Design
- `script.js` – DE/EN Umschaltung, Songs, News, Events, SEO-Update
- `assets/typhoon-band.jpg` – Bandbild

## GitHub Pages Deployment

1. Neues GitHub-Repository anlegen.
2. Alle Dateien aus diesem Ordner ins Repository hochladen.
3. In GitHub auf **Settings → Pages** gehen.
4. Bei **Build and deployment** die Branch `main` auswählen und `/root` lassen.
5. Speichern – danach ist die Website unter GitHub Pages erreichbar.

## Wichtig vor Livegang

In `index.html` bitte diese Zeilen anpassen:

- `canonical`
- `og:url`
- JSON-LD `url`

Ersetze `YOUR-GITHUB-USERNAME` und `YOUR-REPOSITORY-NAME` mit deinen echten GitHub-Daten.

## Inhalte pflegen

In `script.js` kannst du direkt ändern:

- `songs`
- `events`
- `news`
- Kontakttexte DE/EN

## Optional später ergänzen

- echtes Booking-Mailfach
- Social Media Links
- Audio/Video Embeds
- Pressefotos
- Impressum / Datenschutz
