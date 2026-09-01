# The Scary Project

An evolving music + web project — an unsettling children's-song concept, built as a static site and hosted on GitHub Pages.

🔗 **Live site:** https://<your-username>.github.io/

## Status

Early stage. One track exists so far — a distorted Samsung alarm sound layered with a child's voice and an "entity" answering it back. The site currently ships with placeholder copy, colors and structure; none of it is final.

Still undecided:
- Whether this stays a single track or grows into a small series (3–5 songs)
- The overall concept — found-archive, lost-tape, or lullaby-atmosphere direction
- Visual style — currently a dark/purple placeholder palette, not committed to

## Structure

```
index.html   → the whole site (HTML, CSS and a few lines of JS, no build step)
README.md    → this file
```

## Editing

No build tools, no dependencies. Open `index.html` in any browser to preview changes, edit it directly, then commit and push — GitHub Pages redeploys automatically after every push to `main` (usually live within a minute).

To change the color palette, edit the `:root` block near the top of the `<style>` tag in `index.html`. To add or edit a track, copy one of the `.card` blocks inside the `#listen` section.

## Credits

Concept, music and site by [your name or alias].
