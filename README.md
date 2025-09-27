# Apptastisch – GitHub Pages

Eine schlichte, rechtssichere (ohne Cookies/Tracking) GitHub Pages‑Site für **„Fabian Dieckhoff – Apptastisch“**.

## Struktur
- `index.html` – Startseite
- `impressum.html` – Impressum nach § 5 TMG, Verantwortlichkeit § 18 Abs. 2 MStV
- `datenschutz.html` – DSGVO‑konforme Datenschutzerklärung für statische Seite (GitHub Pages)
- `assets/styles.css` – Minimal-Design (keine Webfonts)
- `404.html` – Fehlerseite
- `robots.txt`, `sitemap.xml`, `.nojekyll`

> Ersetze **Adresse/E‑Mail/Telefon/USt‑IdNr.** in Impressum & Datenschutz, bevor du live gehst.

## Deployment (Variante A: Projektsite)
1. Neues Repo z. B. `apptastisch-site` anlegen.
2. Dateien aus diesem Ordner committen (Root des Repos).
3. In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.  
   **Branch:** `main` • **Folder:** `/ (root)` → **Save**.
4. Die Seite ist dann unter `https://DEIN-USERNAME.github.io/apptastisch-site/` erreichbar.
   - Passe in `robots.txt` und `sitemap.xml` `BEISPIEL-DOMAIN` entsprechend an.

## Deployment (Variante B: Usersite)
1. Repo **`DEIN-USERNAME.github.io`** anlegen (genau dieser Name).
2. Dateien ins Root committen. GitHub Pages ist automatisch aktiv.
3. Seite unter `https://DEIN-USERNAME.github.io/` erreichbar.

## Hinweise zu Recht & Datenschutz
- Kein Tracking, keine Cookies → kein Cookie‑Banner nötig.
- Impressum muss die ladungsfähige Anschrift enthalten.
- Wenn du später externe Dienste einbindest (Analytics, Webfonts, Formulare, CDN), passe die Datenschutzerklärung an.

## Lokale Entwicklung
Öffne `index.html` direkt im Browser oder starte einen einfachen Dev-Server, z. B.:

```bash
python3 -m http.server 8000
```

Dann: http://localhost:8000
