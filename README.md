# El Filò — sito web

Sito statico della pizzeria **El Filò** (Viale Stazione 64, 38056 Levico Terme, TN).
Nessuna build: solo HTML/CSS/JS + immagini.

## Pagine
- `index.html` — Home
- `chi-siamo.html` — Chi siamo
- `menu.html` — Menù
- `pizza-del-mese.html` — Pizza del mese
- `contatti.html` — Contatti
- `styles.css`, `app.js`, `images/` — asset condivisi

## Anteprima locale
```
python -m http.server 8940
```
Poi apri http://localhost:8940

## Deploy (automatico via Netlify)
Repo collegato a Netlify: ogni `git push` sul branch `main` ripubblica il sito.
Impostazioni Netlify: build command vuoto, publish directory = `.` (vedi `netlify.toml`).
