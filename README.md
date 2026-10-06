# Evgeny Meleshkevich — portfolio

Bilingual static portfolio foundation for AI tools, data and automation.

Live site: https://evgeny-meleshkevich.github.io/

## Local preview

Run `python3 -m http.server 4183 --bind 127.0.0.1` from this directory, then open `http://127.0.0.1:4183/?lang=ru` or `?lang=en`.

## Content

- `index.html`: layout and Russian text.
- `style.css`: responsive visual system.
- `app.js`: English text, categories, filters, presentation previews and language selection.
- `projects.js`: verified project records; currently empty by design.
- `assets/favicon.svg`: custom identity mark.

Three explicitly labelled presentation mockups illustrate applications, integrations and utilities. They are not client projects or evidence. Real work will be added after its case materials are reviewed.

GitHub Pages publishes the repository root from the `main` branch. No server, paid services, analytics or application database are required. Manrope loads optionally from Google Fonts; local Arial is the fallback.

Do not put API keys, private source applications, personal data or account credentials in this public repository.
