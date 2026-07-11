# Ottoan

A digital garden on quality — principles, frameworks, and lessons from engineering and beyond.

**Live site:** [ottoan.com](https://ottoan.com)

## What this repo is

The garden is built with [Quartz 5](https://quartz.jzhao.xyz) and deployed to GitHub Pages on every push to `main` (see `.github/workflows/deploy.yml`).

- **`content/`** — all the notes. This is the garden; everything else is scaffolding.
- **`quartz.config.yaml`** — site configuration (title, theme, plugins).
- **`quartz/`** — the Quartz framework itself (vendored; updated via `npx quartz upgrade` from the `upstream` remote).

## Working locally

```shell
npm ci
npx quartz plugin install
npx quartz build --serve   # preview at http://localhost:8080
```

Write notes as Markdown in `content/`, using `[[wikilinks]]` to connect them. Each note carries a growth-stage tag: `#seedling` (new, unproven), `#budding` (developed, partially tested), `#evergreen` (stable position).

## Updating the framework

```shell
git fetch upstream
npx quartz upgrade
```
