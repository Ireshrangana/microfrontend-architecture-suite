# Microfrontend Architecture Suite

This repository collects the three versions described in the shared ChatGPT page:

- `starter-single-spa`
- `production-single-spa`
- `enterprise-module-federation`

It also includes the extracted app-building master prompt in `MASTER_PROMPT.md`.

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

- The subprojects are starter structures and documentation, ready to be expanded or wired into fully runnable apps.
- The production and enterprise tracks follow the run guidance described in the shared page:
  `npm install && npm run start` for the production-style variant, and
  `pnpm install && pnpm dev` for the enterprise Module Federation variant.
