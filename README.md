# Tool demos

Static deployment hub for the `demo/index.html` files in Ironwood's canonical
collaborative-tool repositories.

Each demo is one self-contained HTML file. It uses sample data, has a guided
highlight-and-next walkthrough, loads no remote assets, and cannot call an API
or perform a live action. The corresponding canonical repository remains the
source of truth.

`publishing/` is preserved as a legacy alias for `content-engine/`.

To update this hub, copy each canonical `demo/index.html` into its matching
folder, open every file directly, complete each walkthrough, confirm no external
network request occurred, then commit and push.
