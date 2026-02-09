# Joshua M. McCrain - Academic Website

Personal academic website built with [Quarto](https://quarto.org/).

## Features

- **Dynamic Publications**: Automatically pulls publication data from OpenAlex API
- **Weekly Updates**: GitHub Actions updates publication list every Sunday
- **Static Site**: Fast, free hosting on GitHub Pages
- **Custom Domain**: joshuamccrain.com

## Local Development

```bash
# Render the site
quarto render

# Preview with live reload
quarto preview
```

## Publication Data

Publications are fetched from OpenAlex using the `R/fetch_publications.R` script and cached in `data/publications.rds`.

To manually update publications:
```bash
Rscript R/fetch_publications.R
```

## Deployment

The site automatically deploys to GitHub Pages on every push to `main` via GitHub Actions.

## Tech Stack

- **Site Generator**: Quarto
- **Data Processing**: R + tidyverse
- **Publication API**: OpenAlex
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions
- **Domain**: joshuamccrain.com (custom)

---

© 2026 Joshua M. McCrain
