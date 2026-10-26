# Anushree Roy — Portfolio

This repository contains the **editable static website** for Anushree Roy's design portfolio. The original ChatGPT conversation is not required to maintain it.

## Run locally

From the repository root:

```bash
python3 -m http.server 4173 --directory dist
```

Then open http://localhost:4173/.

There is no npm installation or build step. Each HTML page contains its own CSS and JavaScript.

## Editable pages

- `dist/index.html` — homepage and selected work
- `dist/version-control.html` — Version Control case study
- `dist/desktop.html` — DeskTop case study
- `dist/social.html` — social media work
- `dist/decks.html` — presentation work

The `dist/assets/` folder stores images, animation frames, and fonts. PDFs are also available in `dist/`. Some HTML pages embed image data directly; preserve this when editing.

## Make changes

Edit the relevant `dist/*.html` file, preview locally, check mobile and desktop layouts, then commit and push. Serve `dist/` directly as a static website—no build command is needed.

The `.openai/hosting.json` file is part of the existing ChatGPT Sites configuration. Preserve it.

## Future Vercel deployment

Use Vercel's **Other** framework preset, no build command, and output directory `dist`. The proposed new custom domain is `anushreeroy.site`; domain connection and DNS setup are separate steps.

## Recovery scope

This is a maintainable HTML/CSS/JavaScript project recovered from the preserved website files. It does not reproduce the unavailable GPT conversation or any missing React/Vite component project. A framework migration can be done separately without redesigning the portfolio.
