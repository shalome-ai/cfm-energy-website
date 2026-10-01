# cfm.energy

Static one-page site for CFM.energy, built on the CFM.energy design system (tokens in `tokens.css`, generated from the system's `tokens.json`).

- `index.html` – the page
- `styles.css` – layout and component styles
- `tokens.css` – colour, type, space, radius and shadow tokens (light default, dark via OS setting)
- `assets/` – logo marks
- `render.yaml` – Render static-site blueprint (custom domains and a `noindex` header)

Hosted on Render as a static site, publish directory `.`, no build command.
The page is set to `noindex`. To make it indexable, remove the robots meta tags in `index.html` and the `headers` block in `render.yaml`.
