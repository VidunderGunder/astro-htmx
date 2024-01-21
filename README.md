# Astro + HTMX + TailwindCSS + DaisyUI

Simple example of using Astro with HTMX, TailwindCSS and DaisyUI.

## 🚀 Getting Started

To get started, run the following commands from your terminal:

```bash
bun i
bun dev
```

## 🚀 Project Structure

Inside of the Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       ├── partials/
│       │   └── example.astro
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`                 | Starts local dev server at `localhost:4321`      |
| `bun run build`           | Build your production site to `./dist/`          |
| `bun preview`             | Preview your build locally, before deploying     |
| `bun astro ...`           | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help`     | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
{}