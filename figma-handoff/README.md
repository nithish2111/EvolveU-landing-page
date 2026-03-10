# EvolveU Landing Page — Figma Handoff Pack

This folder converts the implemented landing page into Figma-friendly assets.

## What is included

1. `evolveu-landing-wireframe.svg`
   - Import this into Figma (`File → Place image`) to get a full-page editable vector layout scaffold.

2. `design-tokens.json`
   - Color, typography, spacing, radius, and shadow tokens based on the landing page CSS.
   - Use with a Tokens plugin (e.g. Tokens Studio) or manually map to Figma styles.

3. `component-spec.md`
   - Section-by-section component map with suggested auto-layout structure.

## How to import into Figma

1. Open your Figma file.
2. Drag and drop `evolveu-landing-wireframe.svg` onto the canvas.
3. Create text styles from `design-tokens.json` typography values.
4. Create color styles from `design-tokens.json` colors.
5. Use `component-spec.md` to convert repeated UI blocks (cards, buttons, pricing, form fields) into reusable components.

## Notes

- Native `.fig` generation is not supported in this environment.
- This pack is intentionally structured so a designer can recreate a production-ready Figma file in 15–30 minutes.
