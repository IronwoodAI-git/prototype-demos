# Prototype Demos

Public, click-through demos of two interactive UX prototypes. Served as a static site via
GitHub Pages — no backend, no install, sample data only.

- **`/outreach/`** — Outreach Engine (cold-email outreach) prototype
- **`/linkedin/`** — LinkedIn Engine (LinkedIn outreach) prototype
- **`index.html`** — landing page linking to both

Each `index.html` is a self-contained copy of the corresponding prototype's UI. The full
build kits (design docs + build contract for producing the real tools) live in separate
private repositories.

## Updating a demo

The demo copies are generated from the source prototypes. To refresh after editing a
prototype, re-copy its `index.html` into the matching folder here and run `push.bat`
(or `git add -A && git commit && git push`).
