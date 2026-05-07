# Insignia

Static label website built with Astro.

Astro is a popular static website generator. It builds plain static files into `dist/`, which Netlify can deploy directly.

## Common Commands

Run these from the project folder.

```sh
npm install
npm run dev
npm run build
```

- `npm run dev`: local website at `http://localhost:4321`
- `npm run build`: production website in `dist/`

## Netlify

The Netlify settings are in `netlify.toml`.

- Build command: `npm run build`
- Publish directory: `dist`
- Node version: `22.12.0`

## Editing

Main page:

```text
src/pages/index.astro
```

The release list is near the top of that file. Edit the title, artist, catalog ID, and artwork path there.

Release artwork:

```text
public/releases/
```

Each release has an `artwork` field near the top of `src/pages/index.astro`.
