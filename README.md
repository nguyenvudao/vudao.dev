# vudao.dev

Source of my personal blog, [vudao.dev](https://vudao.dev).

Built with [Jekyll](https://jekyllrb.com/) and the
[Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, deployed to GitHub Pages by the
`Build and Deploy` GitHub Actions workflow on every push to `master`.

## Local development

Requires Ruby 3.1+.

```bash
bundle install
bundle exec jekyll serve   # http://127.0.0.1:4000
```

## Writing

Add a file to `_posts/` named `YYYY-MM-DD-title.md` with the front matter:

```yaml
---
title: Post title
date: 2026-01-01
categories: [Development, JavaScript]
tags: [javascript, nodejs]
---
```

Images go in `assets/img/` and are referenced as `/assets/img/name.png`.
