# mean-test

An Angular application for the IT 6203 IT Studio class, updated lab by lab.

**Author:** C. Hawkins

## About

The front end ("A") of a MEAN stack project, built with Angular 22 and the Angular CLI.

The current version (Lab 2) is a **Project Progress Tracker**. It shows two components, each built with Angular Reactive Forms:

- **Milestone Tracker:** milestone name, due date and status (Not Started, In Progress, Completed)
- **Progress Notes:** project name, date, current status (On Track, Needs Attention, Completed), team member and a progress note

## Lab history

| Lab   | Date               | What changed                                                             |
| ----- | ------------------ | ------------------------------------------------------------------------ |
| Lab 1 | September 21, 2026 | Starter app: a single page with a heading, my name and the date          |
| Lab 2 | October 7, 2026    | Added the Milestone Tracker and Progress Notes reactive form components  |

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
  index.html                  Page shell that loads <app-root>
  main.ts                     Bootstraps the app
  styles.css                  Global styles
  app/
    app.ts                    Root component (shows both forms)
    app.html                  Root component template
    app.css                   Root component styles
    app.config.ts             App providers (router, error listeners)
    app.routes.ts             Route definitions
    app.spec.ts               Unit tests
    milestone-tracker/
      milestone-tracker.ts    Milestone Tracker component (reactive form)
      milestone-tracker.html  Milestone Tracker template
      milestone-tracker.css   Milestone Tracker styles
    progress-notes/
      progress-notes.ts       Progress Notes component (reactive form)
      progress-notes.html     Progress Notes template
      progress-notes.css      Progress Notes styles
```
