# Chamuka Labs

Static GitHub Pages site for [Chamuka Labs](https://chamuka.ai), an applied AI lab.

The public site is [https://chamuka-inc.github.io/](https://chamuka-inc.github.io/). There is no build step. `index.html` is the page.

## Daybreak sources

Visual design comes from [Daybreak](https://github.com/chamuka-inc/chamuka-design), the Chamuka Labs design system, at commit [`f6b2265299f19e30cc10dc45132419bc67f56fb3`](https://github.com/chamuka-inc/chamuka-design/commit/f6b2265299f19e30cc10dc45132419bc67f56fb3) (`@chamuka/tokens` 0.1.0, `@chamuka/ui` 0.1.0, `@chamuka/docs` 0.1.0).

Vendored from that commit:

- `vendor/tokens.css` and `vendor/theme.css`, generated from `packages/tokens/src/tokens` by `packages/tokens/src/build.ts`
- Latin woff2 files in `fonts/` from the Fontsource packages loaded in `apps/docs/.storybook/preview.ts`: `@fontsource/sora` 5.2.8, `@fontsource/ibm-plex-sans` 5.2.8, and `@fontsource/ibm-plex-mono` 5.2.7 (SIL Open Font License)
- Lockup, mark, and favicon files from `brand/svg` and `brand/png`

`site.css` maps those tokens onto the page. Buttons, cards, links, the container, the type scale, and the gold horizon ticks follow `packages/ui/src/button.tsx`, `card.tsx`, `link.tsx`, `container.tsx`, `apps/docs/src/foundations/Typography.stories.tsx`, and `templates/web-landing.svg`.

## Agent and search files

- `llms.txt` and `llms-full.txt`: a plain-text catalogue of the lab and its public repositories
- `robots.txt` and `sitemap.xml`
- Open Graph, Twitter, and JSON-LD metadata on `index.html`

## License

Code and page copy are licensed under Apache-2.0. See [LICENSE](LICENSE). The Daybreak names and marks are trademarks of Chamuka Labs; see [TRADEMARKS.md](https://github.com/chamuka-inc/chamuka-design/blob/main/TRADEMARKS.md) in the design system. Font files keep their SIL Open Font License, in `fonts/`.
