# Leumann HUB — Sito web ufficiale

Sito web del progetto **Leumann HUB** — Solarium del Villaggio Leumann, Collegno (TO).

Progetto del Comune di Collegno, finanziato da ANCI.  
Comunicazione: [Eskimo Creative Agency](https://eskimo.agency/)

---

## Come pubblicare su GitHub Pages

1. Crea un repository su GitHub (es. `leumann-hub`)
2. Carica tutti i file di questa cartella nel repository
3. Vai su **Settings → Pages**
4. Seleziona `main` branch e cartella `/root`
5. Salva — il sito sarà online su `https://[username].github.io/leumann-hub/`

## File inclusi

| File | Descrizione |
|------|-------------|
| `index.html` | Pagina principale (tutto self-contained, font e immagini embedded) |
| `preview.jpg` | Immagine di anteprima per social (OG image, 1200×630px) |
| `favicon.png` | Icona del sito |

## Aggiornare l'OG image

Modifica il meta tag `og:image` in `index.html`:
```html
<meta property="og:image" content="https://[tuo-dominio]/preview.jpg">
```
Sostituisci `[tuo-dominio]` con il dominio reale (es. `leumannhub.it`).

## Aggiornare il canonical URL

Cambia il tag canonical in `index.html`:
```html
<link rel="canonical" href="https://[tuo-dominio]/">
```

## Sezioni del sito

- **Hero** — LEUMANN HUB con didascalia e CTA
- **Il progetto** — Storia del Villaggio Leumann, foto dall'inaugurazione
- **Gli eventi** — DIY Minifest e Reading Party (27 Giu 2026)
- **Open Call** — Form Typeform embedded per proporre attività
- **Come arrivare** — Mezzi di trasporto, indirizzo, mappa
- **Footer** — Loghi istituzionali, partner, contatti

---

*Leumann HUB — Via Bargiacchi 7, 10093 Collegno (TO)*  
*info@leumannhub.it*
