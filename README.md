# Prototype Demos

Public, click-through demos of two interactive UX prototypes. Served as a static site via
GitHub Pages — no backend, no install, sample data only.

- **`/outreach/`** — Outreach Engine (cold-email outreach) prototype
- **`/linkedin/`** — LinkedIn Engine (LinkedIn outreach) prototype
- **`index.html`** — landing page linking to both

## How a demo opens

Both demos open on the **story layer**: a short narrative that explains what the tool is, why
it exists, and how it differs from the obvious alternatives (a CRM, a bulk email platform,
LinkedIn on its own), ending on a card that starts the guided tour. It runs **once per browsing
session**, not once per browser, so somebody opening the link fresh always gets the context and
a mid-session reload does not nag them.

- `?story=0` opens straight into the tool
- `?story=1` forces the story even if it has already been seen this session
- `?storyat=N` deep-links a single card, for sending one specific argument to someone

The 📖 button in the header replays it at any time; the 🎓 button toggles the guided tour and
the ambient "?" hints.

Each `index.html` is a self-contained copy of the corresponding prototype's UI. The full
build kits (design docs + build contract for producing the real tools) live in separate
private repositories.

## Updating a demo

The demo copies are generated from the source prototypes. To refresh after editing a
prototype, re-copy its `index.html` into the matching folder here and run `push.bat`
(or `git add -A && git commit && git push`).
