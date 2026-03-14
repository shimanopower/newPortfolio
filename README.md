# newPortfolio

Static portfolio site with hand-written HTML/CSS/JS in `dist/` and source Sass in `scss/`.

## Setup

```bash
brew install node
npm install
```

## Scripts

```bash
npm run build
npm run preview
npm run watch:css
npm run deploy
```

`npm run sass` is kept as an alias for the Sass watcher.

## Deployment

Deploys with `gh-pages` by publishing `dist/` to the `gh-pages` branch. The deploy step also copies `CNAME` into `dist/` so GitHub Pages keeps serving the site on `audreysmonsters.com`.
