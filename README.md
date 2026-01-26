# Web (GitHub Pages)

Dieser Ordner `web/` ist als **eigenständiges Git-Repository** gedacht (nur statische Dateien).

## GitHub Pages (GitHub Actions)

1. Erstelle ein neues GitHub-Repo (z.B. `sql-select-web`).
2. Initialisiere Git **im Ordner `web/`** und push nach `main`:

   - `cd web`
   - `git init`
   - `git add .`
   - `git commit -m "Initial commit"`
   - `git branch -M main`
   - `git remote add origin <DEIN_REPO_URL>`
   - `git push -u origin main`

3. In GitHub: **Settings → Pages**
4. Bei **Build and deployment**: **Source = GitHub Actions** auswählen.

Der Workflow in `.github/workflows/pages.yml` deployed den Inhalt dieses Ordners.

## Lokal testen

- `index.html` direkt im Browser öffnen
