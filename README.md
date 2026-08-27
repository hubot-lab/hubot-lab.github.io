# HuBot Lab Website

Website for the Human-Centered Robotics and Physical Intelligence Lab at Soongsil University.

## Local development

Requirements:

- Ruby 3.2
- Bundler

Install dependencies and start the development server:

```sh
bundle install
bundle exec jekyll serve
```

The site is available at `http://localhost:4000`.

## Content

- Site settings and navigation: `_config.yml`
- Main pages: `_pages/`
- Publications: `assets/ref.bib`
- Publication thumbnails: `images/publications/`
- Shared templates: `_includes/` and `_layouts/`
- Styles: `_sass/` and `assets/main.scss`

## Deployment

Pushes to the `source` branch trigger the GitHub Pages workflow in `.github/workflows/deploy.yml`.
