# ADUe diligence - Snapshot

**Date:** 2026-03-04
**Status:** Feature-complete, deployed, part of 3-site suite

## What's Built
Single-page ADU investment financial model with 6 interactive sections + glossary.
Original vaporwave design with Orbitron + Share Tech Mono fonts, dot grid, scanlines, skewed buttons, neon accents.

## Recent Changes
- Subtler dot grid (reduced opacity from 0.18 to 0.10, larger spacing 28px)
- Dark/light mode toggle (bottom-right button, persists via localStorage)
- Removed "Print / PDF" button (export .xlsx only)
- Added shared top nav bar linking to sister sites (ADU, Investment Property, Multi-Family)
- Backup of pre-redesign version saved as `index-original.html`

## Sister Sites
- **ADU:** https://adue-diligence.netlify.app (this site)
- **Investment Property:** https://investment-property-dd.netlify.app
- **Multi-Family:** https://multifamily-dd.netlify.app

## Key Files
- `index.html` - entire app (single file)
- `index-original.html` - backup of original before any changes
- `README.md` - project description

## Deployment
- **URL:** https://adue-diligence.netlify.app
- **Method:** `npx netlify-cli deploy --dir . --prod`
- **Site ID:** 61c5fb89-8c1b-4cd3-87aa-35c9cb3d6d97
