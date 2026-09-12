# rjhansen.github.io

Personal site built with [Jekyll](https://jekyllrb.com) and the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme
(loaded via `remote_theme`), deployed to GitHub Pages via GitHub Actions
(`.github/workflows/pages.yml`).

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Structure

- `index.md` — home page
- `_pages/about.md` — about page
- `_pages/resume.md` — résumé page
- `_data/navigation.yml` — top navigation links
- `_config.yml` — site and theme configuration
