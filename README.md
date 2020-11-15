# Snowpack Tailwind

> ✨ Bootstrapped with Create Snowpack App (CSA).

Ready-to-go template to create awesome websites using Tailwind and autopublish to GitHub pages.

- [Quick start](#-quick-start)
- [Features](#-features)
- [Available Scripts](#-available-scripts)

## Quick start

```sh
npx create-snowpack-app my-app --template snowpack-template-tailwind --use-yarn
```

It bootstraps this template into a new folder called `my-app/`.

✨ Every commit pushed to your `main` branch will autopublish the site on GitHub Pages.

## Features

- Snowpack, of course.
- Tailwind.
- Prettier.
- Force prettier on commit.
- Autopublish on Github Pages.

## Available Scripts

### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### npm run build

Builds a static copy of your site to the `build/` folder.
Your app is ready to be deployed!

**For the best production performance:** Add a build bundler plugin like [@snowpack/plugin-webpack](https://github.com/snowpackjs/snowpack/tree/master/plugins/plugin-webpack) or [snowpack-plugin-rollup-bundle](https://github.com/ParamagicDev/snowpack-plugin-rollup-bundle) to your `snowpack.config.json` config file.

### Q: What about Eject?

No eject needed! Snowpack guarantees zero lock-in, and CSA strives for the same.
