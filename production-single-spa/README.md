# Production Single-spa

Production-style `single-spa` monorepo scaffold.

## Improvements over starter

- shared shell navigation
- shared auth concept
- shared event bus concept
- environment-friendly import maps
- Docker starter
- GitHub Actions starter

## How to run

This version follows the production-style run guidance from the shared page.

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

This is a strong production-style scaffold. Depending on your local environment, you may still need small dependency adjustments before a full local run succeeds.
