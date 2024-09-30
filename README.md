# Astro Linktree-template
A simple and costumizable linktree template for managing and sharing multiple links on a single page. This project is designed to be user-frendly and adapatable for personal or professional use.

## Demo
You can see a live demo of the template here: [adrian1lara-linktree](https://adrian1lara.vercel.app/)
![linktree-template-gif](/linktree-template.gif)

## Installation
To set up this linktree template on your own system, follow these steps:
1. Clone this repository:
```bash
git clone git@github.com:adrian1lara/linktree-template.git
```
2. Navigate to the project directory:
```bash
cd linktree-template
```
3. Install the dependencies:
```bash
npm install
```
4. Run the project!
```bash
npm run dev
```


## 🚀 Project Structure

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
