# Edgewood Surgical · Home Page Concepts

Client portal presenting home page design directions for **Edgewood Surgical Hospital**, prepared by Clem.

**Round 02 — Refined Direction:** leads with one refined home page (a blend of Editorial × Trust), with the three Round 01 originals kept below for reference.

Static HTML — no build step, no dependencies. Open `index.html` to view the portal, or visit the hosted version.

## Contents

- `index.html` — portal landing page with previews of all directions
- `04 Refined.html` — Refined direction · Editorial × Trust blend (Round 02 recommendation)
- `01 Quiet Editorial.html` — Round 01 · warm white, ink, restrained green
- `02 Modern Trust.html` — Round 01 · brand green as protagonist
- `03 Modern Sage.html` — Round 01 · cream, warm brown, sage
- `assets/` — logos plus facility / cardiology / spine / map photography

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just double-click `index.html`.

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. In repo settings, go to **Pages** → set source to `Deploy from a branch` → `main` / `/ (root)`.
3. GitHub will publish at `https://<user>.github.io/<repo>/`.

The `.nojekyll` file disables Jekyll processing so filenames with spaces (e.g. `01 Quiet Editorial.html`) are served as-is.

## Placeholders to swap before client sign-off

- Phone number — `(XXX) XXX-XXXX`
- Facility / patient photography — 6–8 shots
- Real testimonials (currently illustrative)
- Insurance carrier list — confirm
