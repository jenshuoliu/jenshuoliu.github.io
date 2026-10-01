# jenshuoliu.com

Personal academic website of Jen-Shuo Liu, served by GitHub Pages. Plain HTML/CSS, no build step.

| File | What it is |
|---|---|
| `index.html` | Home: about, selected publications, service, experience, education, awards |
| `publications/index.html` | Full publication list, dissertation, demos |
| `assets/style.css` | All styling (colors are CSS variables at the top; dark mode included) |
| `assets/profile.jpg` | Profile photo |
| `home/…` | Redirects from the old Google Sites URLs (`/home`, `/home/publications`) |
| `CNAME` | Custom domain for GitHub Pages |

## Adding a publication

Copy an existing `<div class="pub">…</div>` block in `publications/index.html`, paste it under the right year, and edit it.
Wrap your own name in `<span class="me">J.-S. Liu</span>` so it is highlighted.
