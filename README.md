# SiqiShang.github.io

Personal academic website, hosted with GitHub Pages at <https://SiqiShang.github.io>.

It is a static site (plain HTML + CSS, no build step) based on
[Jon Barron's website template](https://github.com/jonbarron/website).

## Structure

- `index.html` — the entire page (bio, links, publications, news)
- `stylesheet.css` — styles
- `images/` — profile photo and publication preview images
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll build)

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

GitHub Pages serves the `master`/`main` branch root directly. Because of
`.nojekyll`, files are published as static assets without any Jekyll processing.
