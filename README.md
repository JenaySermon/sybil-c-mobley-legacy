# The Sybil C. Mobley Legacy Project

Official website for The Sybil C. Mobley Legacy Project — a family-led
organization preserving and advancing the legacy of Dr. Sybil Collins Mobley.

**Live at:** [sybilcmobley.org](https://sybilcmobley.org)

## What's in this repo

- `index.html` — The full homepage (single file, inline CSS and JS).
- `CNAME` — Tells GitHub Pages to serve this site from the sybilcmobley.org domain.
- `README.md` — This file.

## Editing the site

Open `index.html` in any text editor. All copy, styles, and structure live
in one file so content changes are straightforward.

## Replacing placeholder photos

The hero and about sections currently use stylized placeholder blocks.
To swap in real photography:

1. Add image files (e.g., `mobley2.jpeg`) to a new `/images` folder in this repo.
2. In `index.html`, find the block labeled `<!-- HERO -->` and replace the
   `<div class="hero__portrait">...</div>` with:
   ```html
   <div class="hero__portrait">
     <img src="images/mobley2.jpeg" alt="Dr. Sybil C. Mobley" style="width:100%; height:100%; object-fit:cover;">
   </div>
   ```
3. Do the same for the About section's image placeholder.

## Brand palette

| Hex | Name | Use |
|-----|------|-----|
| `#1A5C2A` | Forest Green | Primary — headers, buttons |
| `#C8612A` | Harvest Gold | Accents, CTAs |
| `#D4A843` | Warm Gold | Borders, dividers, pull quotes |
| `#FAF6EF` | Cream White | Backgrounds |
| `#2B2B2B` | Deep Charcoal | Body text |
| `#888888` | Medium Gray | Captions, metadata |
