# David Ohayon — personal website

Source for [ohaydav.github.io](https://ohaydav.github.io), built with [Quarto](https://quarto.org/) and hosted on GitHub Pages.

This site brings together independent writing, Product Analytics / Data Science projects, and a concise professional résumé.

## Working locally

Install Quarto, then run:

```sh
quarto preview
```

To build the site locally:

```sh
quarto render
```

A GitHub Actions workflow builds and deploys the site from `main` to GitHub Pages. In repository **Settings → Pages**, set **Build and deployment → Source: GitHub Actions**.

## Editorial policy

Only publish projects and essays that exist; do not list planned projects as completed work. Reproducible work belongs in its own repository and should be linked from the Projects page.
