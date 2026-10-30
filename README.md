# moneta-watch

Free 15-minute ticker for MONETA: GitHub Actions calls the watcher endpoint so the agents check prices, exits and signals all day (Vercel Hobby cron only runs once a day). No secrets live in this repo; they are GitHub Actions secrets (`CRON_SECRET`, `MONETA_URL`).
