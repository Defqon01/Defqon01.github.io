# Defqon01.github.io

Personal site of **Massimiliano Sartorio** — People &amp; Talent leader based in Sweden.
What I'm building, writing and learning. Single self-contained `index.html`, no build step, no dependencies. Hosted on **GitHub Pages**.

Live at: https://defqon01.github.io

## Structure
- `index.html` — the whole site (HTML + inline CSS + vanilla JS)
- `assets/portrait.jpg` — hero photo (optimized, ~115 KB)
- `assets/Massimiliano-Sartorio-CV.pdf` — linked from the Career section
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Run locally
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
Or just open `index.html` in a browser.

## Deploy (GitHub Pages, user site)
1. Create a public repo named exactly `Defqon01.github.io`.
2. Push this folder to `main`.
3. Settings → Pages → Source: `main` / root. Live within ~1 minute.

## Editing content
Everything is plain HTML — search for the section you want:
Career (`id="career"`), Building (`id="building"`), Writing (`id="writing"`),
Interests (`id="interests"`), Now (`id="now"`), Toolkit (`id="toolkit"`), Contact (`id="contact"`).
