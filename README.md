# mean-test

My first Angular application.

**Author:** C. Hawkins
**Date:** September 21, 2026

## About

A starter Angular 22 app built with the Angular CLI. It renders a single page with a heading, my name and the date. This is the front end ("A") of a MEAN stack project.

## Requirements

- Node.js 22.22.3+ or 24.15+
- npm

## Run it

```bash
npm install
npm start
```

Then open http://localhost:4200/.

## Other commands

| Command         | What it does                          |
| --------------- | ------------------------------------- |
| `npm run build` | Production build to `dist/mean-test/` |
| `npm test`      | Runs the unit tests (Vitest)          |

## Project structure

```
src/
  index.html        Page shell that loads <app-root>
  main.ts           Bootstraps the app
  styles.css        Global styles
  app/
    app.ts          Root component
    app.html        Root component template
    app.css         Root component styles
    app.config.ts   App providers (router, error listeners)
    app.routes.ts   Route definitions
    app.spec.ts     Unit tests
```
