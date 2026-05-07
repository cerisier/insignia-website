# Agent Notes

## Goal

Build and maintain a simple static website for the Insignia label.

The site should stay easy for non-coders to operate through an agent.

## Directive

- Keep tooling popular and boring.
- Keep dependencies minimal.
- Prefer Astro's default static output.
- Do not add custom build systems.
- Do not commit generated folders: `dist/`, `.astro/`, `node_modules/`.
- Keep edits simple and localized.

## Build

```sh
npm install
npm run dev
npm run build
```

- Local preview: `http://localhost:4321`
- Netlify build command: `npm run build`
- Netlify publish directory: `dist`

## Main Files

- Page and styles: `src/pages/index.astro`
- Netlify config: `netlify.toml`
- Basic operator docs: `README.md`
