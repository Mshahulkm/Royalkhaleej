# Royal Khaleej Holidays — Standalone Website

Modern, single-file website built with **Bootstrap 5**, **AOS animations**, and vanilla JavaScript.
All package "Book" buttons, the floating chat button, and the enquiry form open a pre-filled WhatsApp chat to **+91 8547301275**.

## Contents
- `index.html` — the entire site
- `images/` — logo + destination photography
- `README.md` — this file

## Run locally
Just double-click `index.html`, or serve it:
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000

## Deploy free on GitHub Pages
1. Create a new GitHub repository (e.g. `royalkhaleej-website`).
2. Upload the contents of this folder (index.html, images/, README.md) to the repo root.
3. Go to **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = main / root**, and Save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` in ~1 minute.

## Customising
- **WhatsApp number** — search `918547301275` in `index.html` and replace with your number (country code, no `+`).
- **Logo** — replace `images/logo.png`.
- **Photos** — replace files inside `images/` keeping the same filenames.
