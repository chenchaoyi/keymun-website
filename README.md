# KEYMUN - Keystone Model United Nations

Official website for **Keystone Model United Nations (KEYMUN)**, hosted at [keymun.org](https://keymun.org).

## About

KEYMUN is a Model United Nations conference organized by students at Keystone Academy, Beijing. The inaugural 2026 conference theme is **"Rebuilding Trust in a Fragmented World"**, featuring three committees:

- **DISEC** — Addressing the Proliferation of Armed Drones in the Middle East (English)
- **SOCHUM** — Ethical Implications of Measures in Counterterrorism from Post 9/11 to Present Day (English)
- **UNESCO** — 虚假信息在混合战争中的武器化：应对国家主导叙事 (Chinese)

## Tech Stack

- Pure HTML / CSS / JavaScript — no frameworks
- Deployed via [Vercel](https://vercel.com) + GitHub

## Project Structure

```
keymun-website/
├── index.html              # Homepage
├── committees.html         # Committee listing
├── committee-disec.html    # DISEC detail page
├── committee-sochum.html   # SOCHUM detail page
├── committee-unesco.html   # UNESCO detail page
├── registration.html       # Registration forms
├── about.html              # About KEYMUN
├── css/                    # Stylesheets (variables, reset, base, layout, components, responsive)
├── js/                     # JavaScript (mobile nav, copy-to-clipboard)
└── assets/
    ├── images/             # Logo
    └── docs/               # Committee background guide PDFs
```

## Local Development

Serve the project with any static file server:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Deployment

Push to `main` branch — Vercel auto-deploys to [keymun.org](https://keymun.org).

## Contact

- Mia Cheng — Secretary General
- Rachel Lin — Secretary General

Keystone Academy, No. 11, Anfu Street, Houshayu, Shunyi, Beijing, P.R. China 101318
