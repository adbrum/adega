# adega

A restaurant website built with React 18 and Create React App. It presents the restaurant, its owners and an intro video, together with a full food and drinks menu organised by category.

## Features

- Home page with banner, intro video, exclusive items, categories and owners sections
- Menu sections for appetizers, grilled dishes, specialties, dishes of the day, desserts, digestives, drinks and wines (green, red, rosé and white)
- Reusable header and footer components

## Tech stack

React 18, Create React App (`react-scripts` 5), Testing Library.

## Getting started

Requirements: Node.js and npm.

```bash
npm install
npm start
```

Open http://localhost:3000 in your browser. The page reloads when you edit the source.

## Scripts

| Command | Description |
|---|---|
| `npm start` | Start the development server |
| `npm run build` | Create an optimised production build in `build/` |
| `npm test` | Run the tests in watch mode |
| `npm run eject` | Eject from Create React App (one-way) |

## Project structure

| Path | Purpose |
|---|---|
| `src/App.js`, `src/index.js` | Application entry points |
| `src/components/` | Page sections (`Banner`, `Header`, `Footer`, `Owners`, `IntroVideo` and others) and one folder per menu category |
| `public/` | HTML template, static assets and styles |
