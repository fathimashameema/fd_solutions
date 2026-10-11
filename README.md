# F&D Tech Solutions — static website

Plain HTML, CSS and JavaScript, served locally with Vite.

## Run locally
Install Node.js, then run:

```sh
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

To create and preview a production build, run `npm run build` and then `npm run preview`.

## Publish
Upload the contents of the `dist/` folder to any static host:
- **Vercel / Netlify / Cloudflare Pages:** drag-and-drop the folder, or connect a Git repo.
- **cPanel / shared hosting:** upload everything into `public_html`.

After you have a domain, update the two social-preview image URLs in `index.html`
(`og:image` and the JSON-LD `image`) to full addresses, e.g. `https://yourdomain.com/assets/og-image.jpg`.

## Brand (taken from the company's proforma invoice)
- Colours: red `#ED1B24`, charcoal `#2E2F34`, slate `#45444A`, deep red `#8C1010`
- Font: Poppins 400 / 500 / 700 (self-hosted in `fonts/`)
- Logo: cut from the invoice header into transparent PNGs in `assets/`
  (`logo-white.png`, `logo-dark.png`, `logo-icon-white.png`, `logo-icon-red.png`)

## Easy edits
- Phone, email, address: search `index.html` for `7807`, `7750`, `fd.service.2010` and `Bawshar`.
- WhatsApp number: `WA_NUMBER` at the top of `js/main.js`, plus the `wa.me/968...` links in `index.html`.
- Colours: the `:root` variables at the top of `css/styles.css`.
- Service descriptions: the "Services" section in `index.html`.

