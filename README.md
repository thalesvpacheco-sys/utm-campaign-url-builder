# UTM Campaign URL Builder

Single-file **HTML + Tailwind + JS** UTM builder. Live preview, one-click copy, localStorage presets and QR Code.

> 100% client-side. No backend. Works offline (except optional QR via Google Charts).

##  Features
- Fields: `utm_id` (optional), `utm_source`, `utm_medium`, `utm_campaign`, `utm_term`, `utm_content`
- Options: force lowercase, keep existing params, URL encode
- Live preview + copy URL + open in new tab
- Presets (save/load/delete) via `localStorage`
- Quick QR code (Google Charts)
- Dark, responsive UI (Tailwind CDN)

##  Getting started
1. Download `index.html`.
2. Open it in your browser — done.

## 🛠 Development
No build steps. Tailwind via CDN. Edit `index.html`.

##  Deploy (GitHub Pages)
1. Push this repo to GitHub.
2. In **Settings → Pages**, set:
   - **Source:** *Deploy from a branch*
   - **Branch:** `main` / `/ (root)`
3. Acesse: `https://<seu-usuario>.github.io/utm-campaign-url-builder/`

##  How to use
1. Enter your **Website URL**.
2. Fill **utm_source** (e.g. `google`) and **utm_medium** (e.g. `cpc`, `social`, `email`, `qr`).
3. Set **utm_campaign** (e.g. `spring_sale`), optionally `utm_id`, `utm_term`, `utm_content`.
4. Click **Gerar URL** → copy or open.
5. (Optional) Generate QR.

##  Best practices
- Use lowercase and short names, no spaces (prefer `-`)
- Standardize by channel (e.g., `utm_medium=qr` for QR codes)

##  License
MIT — see [LICENSE](./LICENSE).

## 👤 Author
Thales Pacheco — Grifo Agency
