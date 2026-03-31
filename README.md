# Microfrontend Architecture Suite

This repository provides three reusable microfrontend starter tracks for anyone building scalable and production-ready frontend projects:

- `starter-single-spa`
- `production-single-spa`
- `enterprise-module-federation`

It also includes a reusable app-building prompt in `MASTER_PROMPT.md`.

## Structure

```text
.
├── MASTER_PROMPT.md
├── starter-single-spa/
├── production-single-spa/
├── enterprise-module-federation/
└── README.md
```

## Versions

### `starter-single-spa`

Basic `single-spa` microfrontend starter with:

- `root-config`
- `react-app`
- `angular-app`
- route-based mounting

### `production-single-spa`

Production-style `single-spa` monorepo with:

- shared shell navigation
- shared auth/event bus concepts
- Docker starter
- GitHub Actions starter

How to run:

```bash
cd production-single-spa
npm install
npm run start
```

Expected idea:

- install workspace dependencies
- start the production-style shell and microfrontends
- open the shell in your browser after the workspace is wired with real app scripts

### `enterprise-module-federation`

Enterprise-oriented monorepo with:

- Module Federation
- TypeScript-first structure
- React shell + dashboard remote
- Angular admin scaffold
- shared auth package
- mock API service

How to run:

```bash
cd enterprise-module-federation
pnpm install
pnpm dev
```

Expected local services:

- shell: `http://localhost:3000`
- dashboard remote: `http://localhost:3001`
- admin remote: `http://localhost:4200`
- mock API: `http://localhost:5000`

## Suggested GitHub Repo Name

`microfrontend-architecture-suite`

## Notes

- These subprojects are public starter foundations that anyone can use, customize, and extend for real-world microfrontend projects.
- The production track uses `npm install && npm run start`.
- The enterprise track uses `pnpm install && pnpm dev`.
