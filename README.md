# Darkside Noodles

Static homepage for [darksidenoodles.com](https://darksidenoodles.com).

## Stack

- **[Astro](https://astro.build/)** — static site generator
- **[Tailwind CSS v4](https://tailwindcss.com/)** — utility-first styling
- **[TypeScript](https://www.typescriptlang.org/)** — type safety
- **[Firebase Hosting](https://firebase.google.com/products/hosting)** — deployment & CDN
- **[@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/)** — automatic sitemap generation

## Project Structure

```text
/
├── public/          # Static assets (favicons, images)
├── src/
│   ├── layouts/     # Page layouts
│   ├── pages/       # Route pages
│   └── styles/      # Global styles
├── firebase.json    # Firebase Hosting config
└── astro.config.mjs # Astro config
```

## Development

```sh
npm install          # Install dependencies
npm run dev          # Start dev server at localhost:4321
npm run build        # Build production site to ./dist/
npm run preview      # Preview production build locally
```

## Deployment

The site is deployed to Firebase Hosting. After building:

```sh
firebase deploy
```
