# Artlista HT26 – Studentkompendium

En läsvänlig webbversion av "Artlista_HT26_studentkompendium.pdf" — en artlista för en biologikurs
(växter, svampar, alger, lavar och djur) med diagnostiska karaktärer, ekologi/livsmiljö, bilder
hämtade från Wikipedia/Wikimedia Commons för varje art, bladdetaljer för alla träd, och en
sökbar ord-/begreppslista med hover-förklaringar direkt i texten.

No framework, no build step — a single static `index.html`.

## Deploy

Static site, zero-config on Vercel: import this repo in the Vercel dashboard and deploy.
Every push to `main` auto-deploys.

## Update the content

The page is generated from a Python pipeline (species data + Wikipedia image lookups) that
lives outside this repo. To publish a new version, regenerate `index.html` and commit/push
the replacement file.
