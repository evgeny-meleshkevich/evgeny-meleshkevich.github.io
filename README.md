# Evgeny Meleshkevich — portfolio

Bilingual static portfolio foundation for AI tools, data and automation.

Live site: https://evgeny-meleshkevich.github.io/

## Local preview

Run `python3 -m http.server 4183 --bind 127.0.0.1` from this directory, then open `http://127.0.0.1:4183/?lang=ru` or `?lang=en`.

## Content

- `index.html`: layout and Russian text.
- `style.css`: responsive visual system.
- `app.js`: English text, categories, filters, presentation previews and language selection.
- `projects.js`: verified project records; cloud GPU upscaling and image file preparation.
- `assets/favicon.svg`: custom identity mark.

Published work: cloud GPU upscaling and image file preparation. Both cases include RU/EN text, real input/output samples, scope and downloadable results. The cloud case includes an interactive detail comparison and a 16-bit PNG master. Third-party model weights and the private service source are not distributed. Presentation mockups have been removed.

GitHub Pages publishes the repository root from the `main` branch. No server, paid services, analytics or application database are required. Manrope loads optionally from Google Fonts; local Arial is the fallback.

Do not put API keys, private source applications, personal data or account credentials in this public repository.
