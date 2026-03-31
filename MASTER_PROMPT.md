# Master Prompt For App Development

You are a senior full-stack architect and frontend engineer.

Build a production-ready microfrontend application using `single-spa` with the following requirements:

## Goal

Create a scalable microfrontend architecture where multiple frontend apps (React and Angular) run under a single shell using `single-spa` and `SystemJS`.

## Architecture Requirements

### 1. Root Config (Container App)

- Use `single-spa` as the orchestrator
- Register applications dynamically
- Route-based loading:
  - `/react` -> React app
  - `/angular` -> Angular app
- Use `SystemJS` + import maps
- Serve on port `9000`

### 2. React Microfrontend

- Use React
- Integrate with `single-spa` using `single-spa-react`
- Expose lifecycle functions:
  - `bootstrap`
  - `mount`
  - `unmount`
- Include:
  - simple dashboard UI
  - navigation links
  - SEO-friendly semantic HTML
- Serve on port `3001`

### 3. Angular Microfrontend

- Use Angular
- Integrate with `single-spa-angular`
- Expose lifecycle hooks
- Include:
  - admin panel UI
  - basic routing inside Angular app
- Serve on port `4200`

## Technical Requirements

- Use `SystemJS` for module loading
- Configure import maps in `index.html`
- Ensure apps can run independently and inside the container
- Use ES modules
- Provide a clean folder structure for each app

## Project Structure

Create 3 separate apps:

```text
/root-config
/react-app
/angular-app
```

Each must be independently runnable with `npm start`.

## Features

- Shared navigation bar across apps
- Lazy loading of microfrontends
- Error handling when an app fails to load
- Loading state while switching apps

## SEO + Performance

- Fast initial load with code splitting
- Lazy loading
- Proper meta tags, at least for the React app
- Optimize for Core Web Vitals

## Advanced

- Shared global state for auth or user data
- Communication between apps via event bus or custom props
- Environment variables for URLs

## Output Format

Provide:

1. Full folder structure
2. All required files
3. Setup instructions
4. Commands to run the full system
5. Notes for production deployment

## Bonus

- Include Docker setup
- Include CI/CD suggestions
- Include deployment strategy
