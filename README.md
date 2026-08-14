# RuneScape Utilities

GitHub Pages-hosted utilities for RuneScape.

## Stack

- Astro 5 (static site generation)
- Bun (package manager and script runner)
- TypeScript support via Astro

## First Tool

### RS3 One-Hit Mining Calculator

Given your mining level and pickaxe, this tool classifies rocks into:

- Guaranteed one-hit
- Possible one-hit
- Not one-hit

The data source and core formulas are based on the RuneScape Wiki mining calculator module data.

## Local Development

```bash
bun install
bun run dev
```

## Production Build

```bash
bun run build
bun run preview
```

## Deploy

Push to `main` to trigger the GitHub Actions workflow in `.github/workflows/deploy-pages.yml`.