# Astro Starter Kit: Minimal

```
npm create astro@latest -- --template minimal
```

[![Open in Netlify](https://upload.wikimedia.org/wikipedia/commons/b/b8/Netlify_logo.svg)](https://boisterous-medovik-57fb3b.netlify.app/)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│       └── favicon.svg
├── src/
│   └── pages/
│       └── index.astro
│       └── [slug].astro
│       └── about.astro
│       └── blog.astro
│   └── layouts/
│       └── Footer.astro
│       └── MainLayout.astro
│       └── Nav.astro
│   └── components/
│       └── Card.astro
│       └── Cards.astro
│       └── GetStarted.astro
│       └── Hero.astro
│   └── style/
│       └── about.sass
│       └── blog.sass
│       └── cards.sass
│       └── cards.sass
│       └── getStarted.sass
│       └── global.sass
│       └── hero.sass
│       └── singlePost.sass
│   └── assets/
│       └── cli.png
│       └── deploy-logos-small.png
│       └── deploy-logos.png
│       └── frameworks-logos-small.png
│       └── frameworks-logos.png
│       └── favicon.svg
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
