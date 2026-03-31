# Enterprise Module Federation

Enterprise-oriented monorepo scaffold for teams that need a reusable foundation for production-ready microfrontend platforms.

## Highlights

- React shell host
- React dashboard remote
- Angular admin scaffold
- TypeScript-first structure
- Module Federation
- shared auth package
- mock API
- Docker starter
- CI starter

## How to run

Anyone can use this version as an enterprise-ready starting point and adapt it to their own auth, API, remote loading, and deployment requirements.

### Prerequisites

- Node.js 20+
- pnpm

### Install

```bash
pnpm install
```

### Start all services

```bash
pnpm dev
```

### Expected local URLs

- Shell: `http://localhost:3000`
- Dashboard remote: `http://localhost:3001`
- Admin remote: `http://localhost:4200`
- Mock API: `http://localhost:5000`

### Demo login

- Email: `admin@example.com`
- Password: `password123`

## Important note

This is an enterprise-ready scaffold. You may still need small package or compatibility adjustments locally, especially around Angular and Module Federation integration.
