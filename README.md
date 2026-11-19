# JoanGlennyPescov.github.io

Source for my personal site, live at **https://JoanGlennyPescov.github.io**

A single static page: computational drug discovery work, publications, and the projects
behind them. No framework, no build step.

## Contents

| File | What it is |
|---|---|
| `index.html` | The whole site. Styles are in the `<style>` block at the top. |
| `cv.pdf` | My CV, linked from the Download CV button. |

## Editing

Colour variables live in `:root` at the top of `index.html`:

- `--accent` teal, used for buttons and links
- `--bg` page background
- `--dark` the Toolkit band

Each project is one `<article class="card">`. Copy one to add another.

Commit to `main` and the live site updates in about a minute.

## Images

`index.html` expects two optional files in the repo root:

- `photo.jpg` — headshot, square, around 400x400
- `figure.jpg` — a science image, square, around 800x800

Both are optional. If either is missing the page falls back to a plain grey box rather
than showing a broken image.
