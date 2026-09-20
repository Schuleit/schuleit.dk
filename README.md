# schuleit.dk

Landing page for [schuleit.dk](https://schuleit.dk): 3D-printed designs, tools and links.

Static site — `index.html` plus `img/`. No build step. Served by GitHub Pages from the `main` branch; `CNAME` holds the custom domain.

## Editing

- Content and styles live in `index.html`. Each 3D model, kit card and tool is one `<li>` — copy a block to add another.
- Colours are the CSS variables at the top of the `<style>` block.
- Preview locally with any static server, e.g. `python3 -m http.server 8090` and open http://127.0.0.1:8090.

Pushing to `main` deploys.
