# ADUe diligence - Task Tracker

## Phase 1: Project Setup & Core Structure
- [x] Create project scaffolding (README, tasks/todo.md, tasks/lessons.md)
- [x] Create index.html with full structure, CSS design system, all sections

## Phase 2: Financial Engine
- [x] DCF calculation engine (amortization, loan balance, cash flows)
- [x] Section 3: ADU cost estimator (beds/bath/sqft/construction toggles)
- [x] Section 4: Rent estimator (monthly rent, vacancy, EGI)
- [x] 10-year cash flow projection table (GPR through levered CF)

## Phase 3: Feasibility & Permitting
- [x] Section 1: Site feasibility checklist with green/yellow/red scoring
- [x] Section 2: Legal/permitting checklist with state-specific guidance

## Phase 4: Summary, Glossary & Polish
- [x] Summary metrics section (cap rate, DSCR, CoC, IRR, NPV, MOIC)
- [x] Glossary with tooltip system (18 terms)
- [x] Responsive design polish

## Phase 5: Spreadsheet Export
- [x] SheetJS .xlsx export with 4 sheets (inputs, feasibility, cash flow, summary)

## Phase 6: Design Iteration
- [x] Vaporwave/outrun design system applied
- [x] Title changed to "[adu]e diligence"
- [x] Lowercase gen-z texting style throughout
- [x] Em dashes removed from all site copy
- [x] Tooltip/hover text in sentence case
- [x] Scroll-reveal animations, hover effects, ambient animations
- [x] Toned down neons (muted teal/magenta palette)
- [x] Grungier dual-layer dot grid
- [x] Hamburger menu for mobile (solid background, X close button)
- [x] Spacing fix for feasibility score result text

## Phase 7: Deployment
- [x] Deployed to Netlify: https://adue-diligence.netlify.app
- [x] Site renamed from much-adu-about-nothing to adue-diligence

## Phase 8: Polish & Mobile Fixes
- [x] Title card updated to "ADUe diligence" with "ADU investment financial model" subtitle
- [x] Hamburger menu: fully opaque coverage, X button safe-area fix, higher z-index
- [x] Touch-friendly tooltips (tap to show/dismiss on mobile)
- [x] Table header tooltips: JS-based fixed positioning (no more bleeding/overflow)
- [x] $ and % sign alignment fix (matching padding + border approach)
- [x] Dot grid made slightly more subtle (opacity reduced)
- [x] Export/print buttons anchored in page flow above copyright (not floating)
- [x] XLSX filename changed to date-based (YYYY-MM-DD_model.xlsx)
- [x] XLSX export: both cash flow tables included as separate sheets (5 sheets total)
- [x] Cash flow table explanations added to website
- [x] Copyright footer added

## Phase 9: Financial Accuracy & Polish
- [x] Added expense growth rate input (3% default, grows taxes/insurance/reserves annually)
- [x] Added sale costs input (6% default, deducted from gross sale proceeds)
- [x] Monthly compounding retained (more accurate than reference's annual compounding)
- [x] $ and % alignment: flex centering approach (4th fix)
- [x] Hamburger X: CSS-drawn lines instead of Unicode character
- [x] XLSX export: new inputs included, sale costs reflected in all sheets
