# Project Overview

This is a blog and portfolio theme for Astro.js called "Viking". It's a fork of the "Dante" theme and includes additional features like multilingual support, a Giscus comment system, and a redesigned hero section. The theme uses Tailwind CSS for styling and is designed to be minimal, responsive, and content-focused.

# Building and Running

The `package.json` file contains the following scripts:

- `npm run dev`: Starts the local development server at `localhost:4321`.
- `npm run build`: Builds the production site to the `./dist/` directory.
- `npm run preview`: Previews the built site locally before deploying.

# Development Conventions

- The project uses TypeScript, as indicated by the `tsconfig.json` file and `.ts` files in the `src` directory.
- The `src/data/site-config.ts` file is a central place for site-wide configuration, including language, comments, and navigation links.
- The content for the blog and projects is stored in the `src/content/` directory as Markdown files.
- The project uses Prettier for code formatting, as indicated by the `.prettierrc` file.
