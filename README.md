# AWD Shared Tokens

The canonical browser-consumable shared token file is:

- `../css/global-tokens.css`

Token ownership:

- Global brand colors, theme aliases, shared frame/surface/text values: `shared/css/global-tokens.css`
- Product-local typography, spacing, breakpoints, and intro-specific motion tokens: `portfolio-clean/css/tokens.css`
- Reusable timing and easing primitives: `shared/css/motion.css`

Default theme values intentionally mirror the authored AWD palette. Dark and night themes override only token values, allowing component presentation styles to remain stable.
