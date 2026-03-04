# ADUe diligence - Lessons Learned

_Updated as issues are found and resolved._

## CSS Pseudo-element Alignment with Inputs
- Browser input elements render text at browser-specific positions that differ from pseudo-elements even with identical CSS properties
- **DON'T**: use `bottom: Npx` with matching font/line-height — will always be slightly off
- **DO**: use `top: 0; bottom: 0; display: flex; align-items: center` to let flexbox handle vertical centering, matching the input's symmetric padding

## Mobile Hamburger Menu
- Unicode characters (✕) render inconsistently across devices — use CSS-drawn shapes instead
- `position: fixed; inset: 0` needs `z-index` above ALL other fixed elements (including scanlines/overlays)
- Use `100dvh` for mobile viewport coverage (accounts for browser chrome)
- Add `env(safe-area-inset-*)` for notched devices

## Tooltip Overflow in Tables
- CSS tooltips inside `<th>` get clipped by `overflow-x: auto` on table wrappers
- Setting `overflow-y: visible` doesn't help (browser treats both axes the same when one is auto/scroll)
- **Solution**: JS-based tooltips with `position: fixed` relative to viewport, created outside the table DOM

## Financial Model Accuracy
- Real-world mortgages use monthly compounding, not annual — PMT(annual_rate, years, principal) is a simplification
- Operating expenses (taxes, insurance, reserves) should grow annually — static expenses understate long-term costs
- Always deduct sale/transaction costs (typically 5-6%) from gross sale proceeds
- Reference spreadsheets may have stale cached values when inputs are changed — always verify formulas, not just displayed values
