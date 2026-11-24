# OneLaser Accessories

Standalone accessories collection preview.

Share URL: https://alexli-stack.github.io/accessories/

GitHub Pages source: main branch, repository root.

Files: index.html, assets/, and preview/ (shared navigation snapshots).

This publishes the preview only; it does not change the Shopify live theme.

## Visual system

The collection layout and colors follow [OneLaser Store](https://alexli-stack.github.io/store/).
Typography follows the current [1laser.com accessories page](https://www.1laser.com/collections/laser-accessories),
measured on November 24, 2026. `assets/accessories-typography.css` defines Certia body text,
Certia-ExtraBold headings, 24px prices, 13px product actions, and responsive title sizes.
The two-column mobile product cards use a compact 16px title; the live site's wider mobile card uses 20px.
`assets/accessories-store.css` defines the layout and colors; `assets/store-shell.css` applies
the official typography to the existing shared header and footer. Fonts are hosted locally.
Measurement sources and responsive adaptations are recorded in `docs/typography-reference.json`.
Machine image provenance is recorded in `assets/machines/SOURCES.md`.

## Enable GitHub Pages

Open https://github.com/alexli-stack/accessories/settings/pages and select:

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Save. When the GitHub Pages build completes, the preview is served at the share URL above. The connected app can upload code but GitHub rejected automatic Pages creation with HTTP 403, so initial enablement requires the repository owner.
