# pitch

A single-page TA pitch for the Fractal Accelerator's next cohort.

- `index.html` — the final self-contained page (screenshots embedded as base64). Deploy this file anywhere — it has no build step and no external dependencies besides Google Fonts.
- `content.md` — the editable source of truth for all page copy. Edit here, then re-sync the HTML.
- `index.src.html` — the HTML template with `{{IMG_*}}` placeholders, used to regenerate `index.html` when screenshots or copy change.
