# Chamuka Labs

Static GitHub Pages site for [Chamuka Labs](https://chamuka.ai), an applied AI lab.

The public site is [https://chamuka-labs.github.io/](https://chamuka-labs.github.io/). There is no build step. `index.html` is the page.

## Daybreak sources

Visual design comes from [Daybreak](https://github.com/chamuka-labs/chamuka-design), the Chamuka Labs design system, at commit [`48a8df12547d9dd79a138953b6c4ec16be9fe45b`](https://github.com/chamuka-labs/chamuka-design/commit/48a8df12547d9dd79a138953b6c4ec16be9fe45b).

Vendored from that repository:

- `vendor/tokens.css` and `vendor/theme.css`, generated from `packages/tokens/src/tokens`
- Latin woff2 files in `fonts/` from the Fontsource packages loaded in Daybreak Storybook: `@fontsource/sora`, `@fontsource/ibm-plex-sans`, and `@fontsource/ibm-plex-mono` (SIL Open Font License)
- Lockup, mark, and favicon files from `brand/svg` and `brand/png`

Illustrations in `assets/illustrations/` are original site artwork in the Daybreak palette: a daybreak hero and diagrams taken from public READMEs. They do not invent product UI.

`site.css` maps those tokens onto the page. Buttons, cards, the container, the type scale, and the gold horizon ticks follow Daybreak components and `templates/web-landing.svg`.

## Agent and search files

- `llms.txt` and `llms-full.txt`: a plain-text catalogue of the lab and its public repositories
- `robots.txt` and `sitemap.xml`
- Open Graph, Twitter card, and JSON-LD metadata on `index.html`

## License

Code and page copy are licensed under Apache-2.0. See [LICENSE](LICENSE). The Daybreak names and marks are trademarks of Chamuka Labs; see [TRADEMARKS.md](https://github.com/chamuka-labs/chamuka-design/blob/main/TRADEMARKS.md) in the design system. Font files keep their SIL Open Font License, in `fonts/`.
