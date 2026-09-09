# Portfolio — Alexis Navarrete

Static portfolio site. No build step: plain HTML pages plus a local `support.js` runtime.

**Live:** https://alexnav28.github.io/Portfolio/

## Structure

| File | Page |
| --- | --- |
| `index.html` | Landing page (work, about, contact) |
| `Project-ThermalIoT.dc.html` | Thermal IoT Stack case study |
| `Project-WatchTower.dc.html` | WatchTower case study |
| `Project-FingerprintWallet.dc.html` | Fingerprint Wallet case study |
| `Project-STM32F446RE.dc.html` | STM32F446RE case study |
| `support.js` | Design-canvas runtime (renders the `<x-dc>` markup) |
| `assets/`, `icons/` | Images used by the pages |
| `.nojekyll` | Tells GitHub Pages to serve files as-is, no Jekyll processing |

## Local preview

Open with a local server (opening the file directly can block `support.js`):

    python -m http.server 8000

then visit http://localhost:8000

## Deploying

Pages is configured to deploy from the `main` branch, root folder. Any push to `main` republishes the site within a minute or two.

## To do

- Add `resume.pdf` to the repo root — the "Résumé" buttons link to it.
