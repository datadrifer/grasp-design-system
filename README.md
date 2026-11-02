# Throughline, Grasp's design system

Version 1.3.6, locked 28 October 2026.

The colours, type, marks and rules behind [Grasp](https://grasp.page), locked into one system. Grasp's app, its landing page and the decks and designs Claude makes for Grasp all read from it.

- **The guide:** https://datadrifer.github.io/grasp-design-system/
- **The showcase** (every token, type style, live component and file on one page): https://datadrifer.github.io/grasp-design-system/showcase/

## What is here

| Path | What it is |
| --- | --- |
| `index.html` | The guide. |
| `showcase/` | The showcase, with the live component cards in `showcase/cards/`. |
| `showcase/files/exports/` | The system for other tools: `DESIGN.md`, DTCG tokens (`*.tokens.json`) and a shadcn `registry:base` item. |
| `showcase/files/logos/`, `stickers/`, `brand-elements/` | Grasp's logos, three annotation stickers and the spark. |

This repository is built output. The system itself lives in Grasp's codebase, where it is made and re-locked with Substrate; every new version is rebuilt and pushed here.

## Licences

Grasp's logos, mark, spark and stickers belong to Grasp: use them to refer to Grasp, not as your own marks. PP Pangaia is a commercial typeface by Pangram Pangram, licensed to Grasp for this site; it is not licensed for reuse. Figtree is free (SIL Open Font License) and loads from Google Fonts. React and marked keep their own MIT licences.
