# jorgenvandeburgt.nl

Personal website for Jorgen van de Burgt, Learning & Development consultant.

## Stack

- Static HTML / CSS / JS (single file)
- No build step
- Hosted on Cloudflare Pages
- Custom domain: jorgenvandeburgt.nl (via Versio DNS)

## Local preview

Just open `index.html` in a browser. No server required.

For a proper local server (recommended for testing on phone via local network):

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Edits

Everything lives in `index.html`. Copy is centralised in the `translations` object near the bottom of the file. Update both `nl` and `en` keys when changing text.

## Deploy

Pushing to the `main` branch on GitHub triggers an automatic deploy via Cloudflare Pages.
