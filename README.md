# nonprofitsage-design

Read-only export of the **NonprofitSage.ai** front-end (Jinja templates + static assets) for design review by Claude.

- `templates/` — Jinja2 templates served by FastAPI. `base.html` is the layout shell; per-page templates extend it.
- `static/brand.css` — main stylesheet. Tokens at the top, then components.
- `static/` — fonts, icons, logos, pico base.

This is a one-way mirror of `api/templates/` and `api/static/` from the private `ferntalent/intelligence-hub` repo. Don't open PRs here — edits go on the source repo.

Live site: https://nonprofitsage.ai · `/review` on the live site has annotated screenshots of every page.
