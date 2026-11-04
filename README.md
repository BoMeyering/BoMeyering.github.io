# bomeyering.me

Personal portfolio site for Bo Meyering, built with Jekyll and hosted on GitHub Pages
(custom domain via `CNAME`). Based on the Start Bootstrap Creative theme.

## Run locally

Requires Ruby and Bundler.

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.

## Editing content

- **Experience:** `_data/experience.yml`
- **Published datasets:** `_data/datasets.yml`
- **Portfolio projects:** `_includes/portfolio.html` (tiles are 650x350 images in `img/portfolio/`)
- **Skills:** `_includes/skillset.html`
- **About / header text:** `_includes/summary.html`, `_includes/header.html`
- **Section order:** `_layouts/front.html`
- **Site title, email, social usernames:** `_config.yml`

## Deploying

Work on `dev`, then merge into `main` and push. GitHub Pages rebuilds the site from `main`.
