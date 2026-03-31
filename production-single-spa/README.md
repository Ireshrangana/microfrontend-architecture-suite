# Production Single-spa

Production-style `single-spa` monorepo scaffold for teams that want a reusable starting point for production-ready microfrontend projects.

## Improvements over starter

- shared shell navigation
- shared auth concept
- shared event bus concept
- environment-friendly import maps
- Docker starter
- GitHub Actions starter

## How to run

Anyone can use this version as a production-ready starting point and adapt it to their own apps, routes, and deployment setup.

### Prerequisites

- Node.js 20+
- npm 10+

### Install

```bash
npm install
```

### Start

```bash
npm run start
```

### Expected behavior

- start the shell and connected microfrontends from the workspace
- load the shell first, then mount apps through the configured routes
- use environment-friendly import maps for local versus deployed bundles

## Important note

This is a strong production-ready scaffold. Depending on your local environment, you may still need small dependency adjustments before a full local run succeeds.
