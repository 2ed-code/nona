# Haneen Love Gift — nona 💌

A refreshed, mobile-first Arabic love-gift experience built with React and Vite, migrated from the reviewed `feature/romantic-surprise-v2` source branch.

## Features
- Arabic RTL, mobile-first romantic design.
- Interactive letter, elapsed-day counter, reasons carousel, surprise gifts, quiz, and heart counter.
- User-triggered confetti and reduced-motion support.
- Optional external piano soundtrack with source and license links.
- Vitest unit tests for the calendar-day counter.

## Local development
```sh
npm install
npm run dev
```

## Checks
```sh
npm test
npm run build
```

## Deployment
The `.github/workflows/pages.yml` workflow tests and builds the app, uploads the `dist` artifact, then deploys it to GitHub Pages on pushes to `feature/nona-migration`. GitHub Pages must allow **GitHub Actions** as its build/deployment source.

## Migration safety
Work is isolated on `feature/nona-migration`. No project files are added directly to `main`, and this branch must not be merged without explicit approval.
