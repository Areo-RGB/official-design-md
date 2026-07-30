---
version: alpha
name: Voltagent Inspired
description: An inspired interpretation of Voltagent's design language — a developer-focused AI agent engineering platform whose surface is an unrelenting near-black canvas broken only by a single electric-green brand accent.

colors:
  primary: "#00d992"
  primary-soft: "#2fd6a1"
  primary-deep: "#10b981"
  on-primary: "#101010"
  ink: "#f2f2f2"
  ink-strong: "#ffffff"
  body: "#bdbdbd"
  mute: "#8b949e"
  hairline: "#3d3a39"
  canvas: "#101010"
  canvas-soft: "#1a1a1a"
---

## Overview

Voltagent is an AI agent engineering platform built for developers. The brand uses a near-black `#101010` canvas, a single electric-green accent (`#00d992`) for CTAs and the brand lightning glyph, and Inter + SF Mono typography. The page reads like polished documentation that decided to also sell something.

**Key Characteristics:**

- A single electric-green accent `#00d992` carries every CTA, status pill, and the brand's lightning logo. No second accent.
- Dark canvas `#101010` is the only page surface — no light-mode.
- Hairline-bordered feature cards (`#3d3a39`, 1px solid) — no shadows, no fills.
- Inter + SF Mono. SF Mono reserved for code blocks, inline command snippets, and metric counters.
- Buttons are tight 6px rounded rectangles; only inline status tags use full pill (9999px).

## Colors

| Token | Hex | Usage |
|-------|-----|-------|
| `primary` | `#00d992` | CTAs, status pills, lightning logo |
| `primary-soft` | `#2fd6a1` | Ghost button variants, focus indicators |
| `primary-deep` | `#10b981` | Inline link color in body copy |
| `canvas` | `#101010` | Page background (only surface mode) |
| `canvas-soft` | `#1a1a1a` | Code blocks, form inputs |
| `hairline` | `#3d3a39` | 1px borders on cards, buttons, dividers |
| `ink` | `#f2f2f2` | Default text on dark canvas |
| `ink-strong` | `#ffffff` | Hero headlines, high-emphasis copy |
| `body` | `#bdbdbd` | Secondary text, supporting copy |
| `mute` | `#8b949e` | Captions, fine print, footer secondary |

## Typography

| Token | Size | Weight | Usage |
|-------|------|--------|-------|
| `display-xl` | 60px | 400 | Hero headline |
| `display-lg` | 36px | 400 | Section headlines |
| `display-md` | 24px | 700 | Card title displays |
| `display-sm` | 20px | 600 | Dense grid card titles |
| `eyebrow-mono` | 14px | 600 | UPPERCASE eyebrow tags (2.52px tracking) |
| `body-lg` | 18px | 400 | Lead paragraphs |
| `body-md` | 16px | 400 | Default body |
| `code` | 13px | 400 | Code blocks, SF Mono |
| `button-md` | 16px | 600 | Button labels |

## Layout

- Base unit: 4px
- Section padding: 48px top/bottom
- Card interior: 24px
- Feature-card grids: 3-up desktop → 2-up tablet → 1-up mobile

## Components

**`button-primary`** — electric-green CTA. Background `#00d992`, text `#101010`, 6px radius, padding `12px 16px`.

**`button-outline-on-dark`** — hairline secondary. Background `#101010`, text `#f2f2f2`, 1px solid `#3d3a39` border.

**`button-ghost-green`** — text-only tertiary. Background `#101010`, text `#2fd6a1`, no border.

**`card-feature`** — default card. Background `#101010`, 1px solid `#3d3a39`, padding 24px, 8px radius.

**`code-mockup`** — dark editor card. Background `#101010`, SF Mono 13px, 1px solid `#3d3a39`, copy-to-clipboard affordance.

## Do's and Don'ts

- Reserve `#00d992` for primary CTAs, the lightning logo, and live-status indicators only
- Use dark `#101010` as the only page surface — no light-mode
- Build cards with 1px hairline borders, not shadows
- Don't use green as body-text fill — CTA only
- Don't add drop-shadows on cards
- Don't render hero headline in heavy weight (700+) — brand display is intentionally calm at weight 400
