# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

- Red: hsl(14, 86%, 42%)
- Green: hsl(159, 69%, 38%)

- Rose 50: hsl(20, 50%, 98%)
- Rose 100: hsl(13, 31%, 94%)
- Rose 300: hsl(14, 25%, 72%)
- Rose 400: hsl(7, 20%, 60%)
- Rose 500: hsl(12, 20%, 44%)
- Rose 900: hsl(14, 65%, 9%)

## Color variables (CSS)

This project uses CSS custom properties (variables) to centralize color tokens. Add or update values in `index.css` under the `:root` selector to change the theme globally.

Example variables defined in `index.css`:

- `--color-primary` — the main brand color used for primary buttons and highlights.
- `--color-accent` — a secondary accent color for highlights and icons.
- `--color-surface` / `--color-bg` — surface and page background colors.
- `--color-text` / `--color-text-muted` — main and muted text colors.
- `--color-border` — borders and separators.
- `--color-success`, `--color-error`, `--color-warning` — semantic state colors.

Quick usage examples in CSS:

```css
:root { --color-primary: #7c3aed; }
.btn-primary { background: var(--color-primary); color: #fff; }
.text-muted { color: var(--color-text-muted); }
```

Tip: For dark mode preferencing, we include a `prefers-color-scheme: dark` media query in `index.css` that overrides the same variables so components automatically adapt.

## Typography

### Body Copy

- Font size (product names): 16px

### Font

- Family: [Red Hat Text](https://fonts.google.com/specimen/Red+Hat+Text)
- Weights: 400, 600, 700

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma. The design file for this challenge also includes a design system and tablet layout to help you build a more accurate solution faster.