# Joshua Chance Blackwell

Personal portfolio at **https://joshuablackwell.me/**, hosted on GitHub Pages.

## Development

This is a static HTML/CSS website. No package installation or build step is required.

```sh
python -m http.server 8766 --bind 127.0.0.1
```

Open `http://127.0.0.1:8766/`. Relative asset paths also support GitHub's project-site URL.

## Editing

- `index.html`: content, links, and page metadata.
- `styles.css`: typography, colors, responsive layout, focus states, and reduced-motion styles.
- `assets/`: favicon and project screenshots.
- `404.html`: custom not-found page.
- `CNAME`: custom hostname for GitHub Pages.
- `.nojekyll`: serves the static site without Jekyll processing.

GitHub Pages serves `main` from the repository root. Changes pushed to `main` update the site.

## Project imagery

The screenshots come from the public [MechWarrior 3 Recomp documentation](https://github.com/roswellien/MW3Recomp) and show development builds and optional enhanced visuals. Original game content belongs to its respective rights holders; no affiliation or endorsement is implied.

The site uses no analytics, external fonts, contact-form backend, or JavaScript.
