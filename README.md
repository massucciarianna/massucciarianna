# Sito — Dott.ssa Arianna Massucci

Sito one-page statico (HTML/CSS/JS, nessuna dipendenza da build).

> **Prima di pubblicare leggi `DA-COMPLETARE.md`**: il sito contiene segnaposto
> `DA COMPLETARE` (P. IVA, codice fiscale, sede, PEC) che sono obbligatori per legge.

## Struttura
- `index.html` — tutte le sezioni: hero, citazione, chi sono, curriculum (tab), servizi, CTA, footer
- `style.css` — palette violetta chiara ripresa dal logo (`#B094BA`)
- `script.js` — menu mobile, tab del curriculum, animazioni on-scroll, evidenziazione sezione attiva
- `privacy.html`, `cookie-policy.html`, `termini.html` — pagine legali
- `assets/fonts/` — DM Sans e Fraunces self-hosted, con le licenze OFL (non rimuoverle)
- `DA-COMPLETARE.md` — checklist di conformità
- `assets/logo.png` — logo
- `assets/arianna.jpg` — foto (versione ottimizzata di `pic.JPG`, usata solo nella hero)
- `logo.PNG`, `pic.JPG`, `traccia.md` — file sorgente originali

## Anteprima locale
```bash
python3 -m http.server 8000
# poi apri http://localhost:8000
```

## Pubblicazione su GitHub Pages
Fai il push del contenuto della cartella sul branch `main` e attiva Pages
(Settings → Pages → Deploy from a branch → `main` / `root`).

## Contatti usati nel sito
- WhatsApp / telefono: +39 378 011 0711 → `https://wa.me/393780110711`
- Email: ariannamassucci.psy@gmail.com

## Privacy e accessibilità

Il sito non usa cookie, non raccoglie dati tramite moduli, non contiene strumenti di
statistica e non effettua alcuna richiesta a server di terze parti: i caratteri sono
self-hosted apposta. Per questo non serve un banner di consenso. Se aggiungi analytics,
una mappa, un video incorporato o un modulo esterno, il banner diventa obbligatorio e le
pagine legali vanno aggiornate.

Contrasti verificati su WCAG 2.2 livello AA: nessuna non conformità.
