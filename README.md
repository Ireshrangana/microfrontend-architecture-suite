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

### `enterprise-module-federation`

Enterprise-oriented monorepo with:

- Module Federation
- TypeScript-first structure
- React shell + dashboard remote
- Angular admin scaffold
- shared auth package
- mock API service

## Suggested GitHub Repo Name

`microfrontend-architecture-suite`

## Notes

- This repo is scaffolded from the contents discoverable in the shared ChatGPT page.
- The subprojects are starter structures and documentation, ready to be expanded or wired into fully runnable apps.
