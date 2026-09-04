# Personal Portfolio Website

A personal portfolio website featuring an interactive layout, custom typography, and responsive design.

## Tech Stack
- Astro
- HTML5
- CSS3

## Setup & Local Development
Install dependencies and start the Astro dev server:

```sh
npm install
npm run dev
```

## Deployment

This site deploys for free to GitHub Pages using GitHub Actions.

The workflow in `.github/workflows/deploy.yml` runs on every push to `main`:

```sh
npm run build
```

The deployed GitHub Pages URL is:

```text
https://nhess10.github.io/Portfolio/
```

GitHub repository settings must use **Pages > Source: GitHub Actions**.

## Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
