# omaruno.github.io

Personal academic website of **Omar Coser** — PhD in Artificial Intelligence (Health & Life Sciences),
guest researcher at the Max Planck Institute for Intelligent Systems, Tübingen.

Live at <https://omaruno.github.io/>.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | All page content — hero, about, research, publications, experience, education, awards, skills, news, contact |
| `style.css` | Styling, design tokens, light/dark themes, responsive rules |
| `script.js` | Theme toggle, mobile menu, sticky-nav shadow, scroll spy, footer year |
| `assets/Omar2026.jpeg` | Portrait |
| `assets/Omar_Coser_CV.pdf` | Downloadable CV |

No build step and no dependencies — GitHub Pages serves the files as they are.

## Editing

- **Add a publication:** copy an existing `<li class="publication">` block in `index.html` and edit it.
- **Add a news item:** add an `<li>` to `.news-list`, newest first.
- **Update the CV:** replace `assets/Omar_Coser_CV.pdf`, keeping the filename.
- **Change colours:** edit the custom properties in `:root` in `style.css`; the dark palette lives in the
  `@media (prefers-color-scheme: dark)` and `:root[data-theme="dark"]` blocks below it.

## Local preview

    python -m http.server 8000

Then open <http://localhost:8000>.
