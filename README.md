# glonni.de – Glonni Cup des WSV Glonn

Statische Website (HTML, ohne Build-Schritt). Stand: 13.11.2026

- `index.html` – Startseite
- `gelaende.html` – Geländeplan & Sponsoring
- `orga-team.html` – ORGA Team
- `media/`, `assets/` – Videos, Bilder, Schriften
- `.htaccess` – Einstellungen für IONOS (inkl. Passwortschutz)

Jede Änderung auf `main` wird über GitHub Actions automatisch per SFTP zu IONOS hochgeladen
(`.github/workflows/deploy.yml`). Zugangsdaten liegen nur als GitHub-Secrets vor.
