# Evgeny Meleshkevich — portfolio

Bilingual static portfolio foundation for AI tools, data and automation.

Live site: https://evgeny-meleshkevich.github.io/

## Local preview

Run `python3 -m http.server 4183 --bind 127.0.0.1` from this directory, then open `http://127.0.0.1:4183/?lang=ru` or `?lang=en`.

## Content

- `index.html`: layout and Russian text.
- `style.css`: responsive visual system.
- `app.js`: English text, categories, filters, presentation previews and language selection.
- `projects.js`: project records for Qwen chat/API, cloud GPU upscaling and image file preparation.
- `assets/favicon.svg`: custom identity mark.

Published work: a self-hosted Qwen chat/API, cloud GPU upscaling and image file preparation. All cases include RU/EN materials and real execution evidence. The Qwen case includes live-chat screenshots and authenticated ordinary/streaming API verification. The cloud case includes an interactive detail comparison and a 16-bit PNG master. Third-party model weights, private configurations and credentials are not distributed; public application repositories are linked from each case. Presentation mockups have been removed.

GitHub Pages publishes the repository root from the `main` branch. No server, paid services, analytics or application database are required. Manrope loads optionally from Google Fonts; local Arial is the fallback.

Do not put API keys, private source applications, personal data or account credentials in this public repository.
