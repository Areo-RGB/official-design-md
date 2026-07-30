---
name: vercel-brand-guidelines
description: "Design, build, or substantially improve an official Vercel-authored report website. Use for customer reports, proposals, briefs, benchmarks, comparisons, narrative data pages, pricing or ROI or performance calculators, and bespoke decision pages that need Vercel information architecture, Geist typography, data storytelling, responsive craft, and light and dark themes."
---

# Design report websites like Vercel

Act as an excellent Vercel designer, editor, information architect, data storyteller, and design engineer. Turn the available material into an official Vercel-authored website.

## Vercel product and brand context

Treat these as official Vercel-authored customer surfaces. Make the artifact precise, calm, direct, technically literate, evidence-led, editorial, and restrained. Build confidence through clarity, proof, and command of the material.

## Authorship shell

Every completed page has the same Vercel authorship outcome. Put the Vercel wordmark on the left of the header and the triangle logo on the left of the footer.

- Wordmark: `https://py8fhxnkzwtsqdo9.public.blob.vercel-storage.com/p/vercel-wordmark.svg`
- Triangle: `https://py8fhxnkzwtsqdo9.public.blob.vercel-storage.com/p/vercel-logo.svg`

## Typography

Use **Geist Sans** for prose, headings, labels, controls, tables, KPIs, dates, counts, percentages, durations, and financial figures. Use **Geist Mono** only for code, commands, paths, raw tokens, timestamps, and short operational identifiers.

```html
<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400..600&family=Geist+Mono:wght@400..600&display=swap" rel="stylesheet">
```

## Grid and alignment

- 12 columns on desktop, 6 on tablet, 4 on mobile
- Reading prose: 6–7 desktop columns
- Tables, charts, calculators: may use all 12 columns

## Color

Design in monochrome. Use color only when it adds significant meaning to state, action, or data.

**Public token families:**
- Surfaces: `--vbg-surface-primary`, `--vbg-surface-secondary`, `--vbg-surface-contrast`
- Text: `--vbg-text-primary`, `--vbg-text-secondary`, `--vbg-text-on-contrast`
- Borders: `--vbg-border-subtle`, `--vbg-border-default`, `--vbg-border-strong`
- State: `--vbg-color-info`, `--vbg-color-success`, `--vbg-color-warning`, `--vbg-color-error`
- Data: `--vbg-chart-1` through `--vbg-chart-6`

## Motion

Default to stillness. Add motion only when it explains a state change, preserves continuity, or confirms an action. Respect `prefers-reduced-motion`.

## Do not ship these defaults

- All-caps eyebrows, em dashes, decorative gradients, glows, blobs, glass effects
- Generic centered hero copy followed by a card grid
- Decorative charts, legends replacing direct labels, or color without meaning

## Resources

- Foundation CSS: `https://vercel.com/geist/vercel-brand.css`
- Wordmark: `https://py8fhxnkzwtsqdo9.public.blob.vercel-storage.com/p/vercel-wordmark.svg`
- Triangle logo: `https://py8fhxnkzwtsqdo9.public.blob.vercel-storage.com/p/vercel-logo.svg`
