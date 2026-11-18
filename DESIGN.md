# Design

Visual world of the Ivolution franchise landing (`index.html`). Derived from the brand manual 2025 and built on 2026-11-18.

## Color

- Gold `#D8A13F` (hover `#E8B95E`), on paper sections use the darker `#a8761c` for text-sized gold.
- Black `#000` base, surfaces `#0b0b0b` / `#121212`, lines `#262626` / `#333`.
- Paper `#f1ede4` for the editorial sections (opportunity, comparison, process); text `#121212`, secondary `#57524a`.
- Gold is the only accent. The manual's complementary green/blue/red are reserved for the Trainer/Analytics sub-brands and are not used here.

## Type

- Display and section titles: Roboto 900 italic, uppercase, line-height .95, max 6rem.
- Sub-titles: Roboto 700 italic.
- Body: Roboto 500, 17px.
- Quotes and tagline: Roboto Serif 500 italic.
- Measurement readouts only: Roboto Mono 500, tabular numerals.

## Signature elements

- The logo's bolt accessory (`<symbol id="bolt">`, polygon `104,0 104,200 54,252 0,405 0,203 52,155`) slices the hero photo and sits behind the contact section.
- Hero readout: a force-platform panel whose force-time curve draws in on load (the page's one authored motion moment). Values are illustrative and labelled as such.
- Photography graded black and white with CSS (`grayscale(1) contrast(1.1-1.2)`); unit photos regain color on hover.

## Components

- Buttons: square (4px radius), gold solid or 1.5px white outline, arrow icon nudges on hover.
- Icons: inline SVG sprite, 24px grid, 1.75 stroke, round caps (Lucide geometry). No emoji or unicode glyphs as icons.
- Models: dark panels with photo, sub-brand logo, segmented format selector, spec rows (gold for result rows) and icon chips.
- Lists of facts use icon + text rows, not equal card grids.
- No eyebrow labels above headings.

## Layout

- Max width 1240px, gutter clamp(18px, 4vw, 40px), section padding clamp(80px, 11vw, 150px).
- Breakpoints: 1100px (nav collapses, 2-column data bar), 900px (single column, sticky mobile CTA bar), 760px (mobile hero and stacked tables).
