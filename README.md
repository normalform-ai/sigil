# SIGIL

The public splash page for SIGIL: Superintelligence Guarantees for
Instrumented Labs.

Live site: https://normalform-ai.github.io/sigil/

## Publishing

GitHub Pages serves the root of the `main` branch. Push changes to `main`
to deploy. The site is static HTML with no build step; `.nojekyll` keeps
GitHub Pages from processing it with Jekyll.

- `index.html`: the page, styles, interactive demo, and early-access form
- `assets/`: icons, social card, demo videos, and poster
- `favicon.ico`: fallback browser icon

Fonts load from Google Fonts. The early-access form uses the existing
Formspree endpoint configured in `index.html`.

## Local preview

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/.
