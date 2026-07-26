# Bare Metal Press

Website for Bare Metal Press, an independent publisher of technical books.

Live at <https://bare-metal-press.github.io/>

## Stack

- [Astro](https://astro.build) — static site, no theme, styles written from scratch
- GitHub Pages — deployed automatically on every push to `main`

## Local development

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # output in dist/
npm run preview  # serve the built site
```

## Structure

```
src/
  layouts/Base.astro   shared shell: head, header, footer
  pages/               one file per route
  styles/global.css    design tokens and base styles
```
