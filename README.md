# binge-track

BingeTrack is a Vue app that works with The Movie Database API. 
Browse and discover movies, check or add ratings and reviews, create your watchlist and your favorite movies list.

This project was created for fun and as practice with Vue 3. It's still a work in progress and may contain bugs, flaws, or security vulnerabilities.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup
  1. install project packages and dependencies
```sh
npm install
```
  2. Create .env file and enter your TMDB API key (read-only)
```sh
VITE_TMDB_API_KEY = 'API KEY'
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
