# Sapiens Investment Association — Website

Static website for Sapiens Investment Association, ready for GitHub Pages.

## Files
- `index.html` — the website homepage (GitHub Pages serves this automatically)
- `docs/SIA_Chairmans_Report_2025.pdf` — Chairman's Annual Report (download link)
- `docs/SIA_Annual_General_Meeting_2025.pdf` — AGM Minutes (download link)
- `.nojekyll` — tells GitHub Pages to serve files as-is (do not delete)

## How to publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `sapiens-website`).
2. Upload ALL files here, keeping the folder structure (the `docs/` folder must stay intact).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`.
5. Choose branch `main` and folder `/ (root)`, then **Save**.
6. Wait 1–2 minutes. Your site will be live at:
   `https://<your-username>.github.io/<repository-name>/`

## Updating documents later
To replace a report or the minutes, upload a new PDF to the `docs/` folder
using the EXACT same filename. The download buttons will then serve the new file.
