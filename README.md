# echarvel3.github.io

Personal site for Eduardo Charvel — PhD candidate in Bioinformatics & Systems Biology at UC San Diego (Mirarab Lab). Built as a single static page: research, publications, talks, awards, blog, and contact info.

Live at [echarvel3.github.io](https://echarvel3.github.io).

## Stack

Plain HTML/CSS/JS, no build step. Fonts are pulled from Google Fonts (DM Serif Display, DM Mono, Inter); everything else is self-contained in `index.html`.

## Structure

```
index.html      # the entire site
images/         # photos, favicons
documents/      # CV, talk slides/posters (PDF)
```

## Local preview

```
python3 -m http.server
```

then open `http://localhost:8000`.

## Adding a blog post

Open `index.html`, find the `.blog-scroll` section, and copy the commented template at the top of it as the **first** `<article class="post">` block (newest on top). Edit the date, title, and body — no other changes needed.

## Deploying

Push to `main`; GitHub Pages serves the repo root directly.
