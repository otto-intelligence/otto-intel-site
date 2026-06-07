# otto-intel-site

Single-page credibility site for Otto Intel — live at https://otto-intel.com

## What it is
One self-contained `index.html` (inline CSS, inline SVG logo, tiny vanilla-JS ES/EN toggle).
No build step, no dependencies. Brand = OttO Brand Spec v1.0 (paper `#F4EFE5`, ink `#1A1A17`, amber `#C97A4A`).

## Edit it
Open `index.html`, change the copy/styles, then:
```bash
git add -A && git commit -m "..." && git push
```
Cloudflare Pages auto-deploys in seconds. Claude or Codex can do all of this from the terminal.

## Preview locally
It's a static file — `open index.html`, or to test fonts/toggle over HTTP:
```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Hosting & domain
- **Host:** Cloudflare Pages (free), connected to this repo, auto-deploy on push to `main`.
- **Domain:** `otto-intel.com` registered at Squarespace (registrar only). DNS points at the
  Cloudflare Pages project.
- **Owner:** `otto-intel` GitHub org — this repo is Otto Intel's founding company asset.

## Source of truth
Design spec & decisions: `OCTO/projects/Otto INTEL/Otto Website/`.
```
