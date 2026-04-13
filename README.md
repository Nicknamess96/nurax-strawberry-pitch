# Nurax Strawberry — Pitch Webpage per Papà

Single-page partnership pitch in italiano per presentare il progetto a tuo padre.

## Come visualizzarla

**Locale (sviluppo):**
```bash
cd webpage
python3 -m http.server 8000
# Apri http://localhost:8000 nel browser
```

**Per mostrare a papà:**

Opzione 1 — Apri direttamente:
- Doppio-click su `index.html` per aprirla nel browser
- Funziona anche offline

Opzione 2 — Online:
- Carica `index.html` + `style.css` su GitHub Pages, Netlify, Vercel
- Subdominio gratuito tipo `nurax-strawberry-papa.netlify.app`

Opzione 3 — Condivisione veloce:
- Esporta come PDF dal browser (Stampa → Salva come PDF)
- Mandalo per WhatsApp/email

## Struttura

| Sezione | Contenuto |
|---------|-----------|
| Hero | Visione del progetto, tagline emotiva |
| Perché | La situazione personale (Panama) e la richiesta |
| Cosa stiamo costruendo | Serra, AI, fragole — i 3 pilastri |
| Come funziona | Flow visuale a 5 step (sensori → AI → pompe → notifiche → raccolta) |
| Chi fa cosa | Ruoli divisi: padre operativo / figlio capitale+AI |
| I numeri | Investimento, ricavi, margini — onesto con scenari cauto/ottimo |
| A chi vendiamo | HORECA: ristoranti, hotel, distributori |
| Quando | Timeline 7-12 mesi |
| Strumenti per te | Telegram, dashboard, manuali, supporto 24/7 |
| CTA finale | Apertura al dialogo |

## Personalizzazione

Modifica `index.html`:
- Linea ~15: Cambia il logo se non vuoi 🍓
- Sezione "Perché ti sto chiedendo aiuto": Adatta il tono se necessario
- Sezione "Proposta di partnership": Specifica termini concreti dopo aver discusso
- CTA finale: Cambia firma "Nicola" se necessario

Modifica `style.css`:
- `--primary` (rosso fragola): Cambia colore principale
- `--accent` (verde): Cambia colore secondario
- Font: Cambia `font-family` se vuoi un look diverso

## Note design

- **Mobile-first responsive** — funziona su telefono, tablet, desktop
- **Zero dipendenze esterne** — solo HTML + CSS, niente JavaScript
- **Accessibile** — colori ad alto contrasto, font leggibili, struttura semantica
- **Tono onesto** — non vende troppo, mostra anche scenari pessimisti
- **Visivo** — molte icone emoji, niente termini tecnici incomprensibili
