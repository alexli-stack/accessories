# OneLaser Accessories

Standalone accessories collection preview.

Share URL: https://alexli-stack.github.io/accessories/

GitHub Pages source: main branch, repository root.

Files: index.html, assets/, and preview/ (shared navigation snapshots).

This publishes the preview only; it does not change the Shopify live theme.

## Visual system

The accessories collection follows [OneLaser Store](https://alexli-stack.github.io/store/).
`assets/accessories-store.css` defines the active collection theme: Poppins typography,
brand red `#e7310e` for prices and primary actions, sky blue `#38bdf8` for selection
and assistance, and neutral gray product surfaces. The shared header and footer
keep their existing links and interactions, with typography in `assets/store-shell.css`.
Poppins fonts are hosted locally in `assets/fonts/`, with their OFL license.
Machine image provenance is recorded in `assets/machines/SOURCES.md`.

## Enable GitHub Pages

Open https://github.com/alexli-stack/accessories/settings/pages and select:

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Save. When the GitHub Pages build completes, the preview is served at the share URL above. The connected app can upload code but GitHub rejected automatic Pages creation with HTTP 403, so initial enablement requires the repository owner.
