# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll static site for an academic personal website. GitHub Pages natively builds and deploys Jekyll sites - no CI/CD configuration needed.

## Build Commands

```bash
bundle exec jekyll serve    # Local dev server at http://localhost:4000
bundle exec jekyll build    # Build to _site/
```

## Structure

```
/
├── _config.yml         # Site config (title, author, social links)
├── _layouts/
│   └── default.html    # Main layout with header, sidebar, footer
├── assets/
│   ├── css/style.css   # All styles
│   └── img/            # Avatar and favicon
└── index.md            # Main content (About + Publications)
```

## Editing Content

Edit `index.md` to update the About section and publications list. The file uses standard Markdown with Jekyll front matter.

## Editing Layout

- `_layouts/default.html` contains the full HTML structure
- Social links are configured in `_config.yml` under `social:`
- Styles are in `assets/css/style.css`

## Deployment

Push to the main branch. GitHub Pages automatically builds and deploys.
