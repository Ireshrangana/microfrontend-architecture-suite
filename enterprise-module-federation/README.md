# Enterprise Module Federation

Enterprise-oriented monorepo scaffold extracted from the shared page.

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

This version follows the enterprise run guidance from the shared page.

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
