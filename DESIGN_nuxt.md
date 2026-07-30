---
version: alpha
name: Nuxt
description: Nuxt design system, powered by Nuxt UI and Tailwind CSS v4. Dark mode is the default theme.
brand:
  green: "#00DC82"
  navy: "#020420"
  white: "#FFFFFF"
theme:
  font-sans: "'Public Sans', sans-serif"
  color-green-400: "#00DC82"
semantic-colors:
  primary: green
  neutral: slate
  important: violet
  secondary: blue
  success: green
  info: blue
  warning: yellow
  error: red
---

# Nuxt

## Overview

Nuxt is the design language for Nuxt products and communications. The aesthetic is developer-focused and confident: deep navy surfaces, Nuxt green as the single accent, and generous whitespace. Prioritize readability, accessibility, and clarity over decoration.

The system is powered by [Nuxt UI](https://ui.nuxt.com) and **Tailwind CSS v4**, with **CSS variables** as design tokens. Colors are semantic (`primary`, `neutral`, `error`) rather than hardcoded hex values. Dark mode is the default theme.

## Brand Colors

| Name | Hex | Usage |
|------|-----|-------|
| Green | `#00DC82` | Logo, brand accent. Maps to `green-400`. |
| Navy | `#020420` | Dark backgrounds, OG images. |
| White | `#FFFFFF` | Text on dark surfaces. |

## Semantic Colors

| Semantic | Maps to | Usage |
|----------|---------|-------|
| `primary` | `green` | CTAs, links, active nav, brand elements |
| `neutral` | `slate` | Text, borders, backgrounds, disabled states |
| `important` | `violet` | Highlighted badges and emphasis |
| `secondary` | `blue` | Secondary actions |
| `success` | `green` | Success states |
| `info` | `blue` | Info alerts, tooltips |
| `warning` | `yellow` | Warnings, pending states |
| `error` | `red` | Errors, destructive actions |

```vue
<UButton color="primary">Get Started</UButton>
<UButton color="neutral" variant="subtle">Learn More</UButton>
<UButton color="error">Delete</UButton>
```

## Typography

**Font:** Public Sans (`--font-sans`), loaded via `@nuxt/fonts`.

| Context | Typical classes |
|---------|----------------|
| Page hero | `text-5xl sm:text-7xl font-semibold` |
| Section hero | `sm:text-5xl font-semibold` |
| Section headings | `text-2xl`–`text-4xl font-semibold` |
| Body / prose | `prose prose-primary dark:prose-invert` |
| UI labels | `text-sm`, `text-xs` |
| Code | `font-mono`, Shiki-highlighted blocks |

## Layout

- Container: `--ui-container: 90rem` via `UContainer`
- Header height: `--ui-header-height: 112px`
- Spacing rhythm: `gap-2` (8px), `gap-4` (16px), `py-10 sm:py-20` for sections
- Radius: from `--ui-radius` base — `rounded-xs` through `rounded-3xl`

## Components

| Pattern | Component | Example |
|---------|-----------|---------|
| Primary action | `UButton` | `<UButton color="primary">Deploy</UButton>` |
| Secondary action | `UButton` | `<UButton color="neutral" variant="subtle">Cancel</UButton>` |
| Tertiary / link | `UButton` | `<UButton variant="ghost">Docs</UButton>` |
| Destructive | `UButton` | `<UButton color="error">Delete</UButton>` |
| Form input | `UInput` | `<UInput placeholder="Search modules" />` |

## Voice & Content

- Title Case for labels, buttons, titles, and tabs; sentence case for body and helper text
- Name actions with a verb and a noun (`Deploy Project`, `Install Module`)
- Write errors as what happened plus what to do next
- In-progress states use present participle + ellipsis: `Deploying…`

## Resources

- Brand assets: [/design-kit](/design-kit)
- Figma brand kit: [Nuxt Brand Kit](https://www.figma.com/community/file/1296154408275753939/nuxt-brand-kit)
- Nuxt UI: [ui.nuxt.com](https://ui.nuxt.com)
