---
version: alpha
name: "Blueprint Canvas"
description: "Typography baseline relies on inter for primary hero headline — uppercase, bold, bottom-left anchored on the canvas."
colors:
  nav-surface: "#1e3fa0"
  blueprint-blue: "#1a4fd6"
  canvas-white: "#ffffff"
  annotation-dim: "#404040"
  grid-line-blue: "#2d5fe0"
typography:
  hero-headline:
    fontFamily: "inter"
    fontSize: "24px"
    fontWeight: "560"
    lineHeight: "33.6px"
    letterSpacing: "-1px"
  nav-label:
    fontFamily: "inter"
    fontSize: "16px"
    fontWeight: "400"
    lineHeight: "20.6208px"
  section-heading:
    fontFamily: "inter"
    fontSize: "18px"
    fontWeight: "500"
    lineHeight: "28.8px"
    letterSpacing: "-0.25px"
  body-text:
    fontFamily: "inter"
    fontSize: "16px"
    fontWeight: "400"
    lineHeight: "20.6208px"
  technical-annotation:
    fontFamily: "iAWriterQuattroV"
    fontSize: "8px"
    fontWeight: "400"
    lineHeight: "8px"
    letterSpacing: "0.3px"
  mono-label:
    fontFamily: "iAWriterQuattroV"
    fontSize: "12px"
    fontWeight: "400"
    lineHeight: "21px"
    letterSpacing: "-0.5px"
  ui-label-small:
    fontFamily: "inter"
    fontSize: "14px"
    fontWeight: "500"
    lineHeight: "18.0432px"
  display-numeric:
    fontFamily: "inter"
    fontSize: "24px"
    fontWeight: "510"
    lineHeight: "27.6px"
    letterSpacing: "-0.528px"
rounded:
  radius-0: "4px"
  radius-1: "8px"
  radius-2: "12px"
  radius-3: "16px"
  radius-pill: "9999px"
  radius-subtle: "9.5px"
spacing:
  space-0: "0px"
  space-1: "4px"
  space-2: "8px"
  space-3: "12px"
  space-4: "16px"
  space-5: "24px"
  space-6: "32px"
  space-7: "40px"
  space-8: "48px"
  space-9: "56px"
  space-10: "64px"
  space-11: "80px"
  space-12: "96px"
  space-13: "128px"
  space-14: "256px"
  space-15: "512px"
---

## Overview

Typography baseline relies on inter for primary hero headline — uppercase, bold, bottom-left anchored on the canvas.

This system uses a 4px base grid with scale values 0, 4, 8, 12, 16, 24, 32, 40, 48, 56, 64, 80, 96, 128, 256, 512.

**Signature traits:**
- Core token rhythm: Token evidence indicates consistent color, spacing, and radius rhythm across visible UI.

## Colors

The palette uses 5 validated color tokens across 1 theme profile. Semantic roles stay attached to observed usage so generation agents can choose accents without inventing new color meaning.

**Semantic naming:**
- **surface-background** maps to `blueprint-blue`: Role "background" is grounded by usage context "Full-bleed hero canvas background — the dominant cobalt/royal blue that fills the entire viewport".
- **content-background** maps to `canvas-white`: Role "background" is grounded by usage context "Primary text, nav labels, headline copy, and annotation overlays on the blue canvas".
- **content-border** maps to `grid-line-blue`: Role "border" is grounded by usage context "Isometric grid lines overlaid on the hero canvas, slightly lighter than the base blue".
- **surface-secondary** maps to `nav-surface`: Role "secondary" is grounded by usage context "Pill-shaped navigation bar background — a slightly darker/desaturated blue with frosted glass quality".

### Text Scale
- **Annotation Dim** (#404040): Dimmed/secondary text in footer zones, low-emphasis labels. Role: text.

### Interactive
- **Nav Surface** (#1e3fa0): Pill-shaped navigation bar background — a slightly darker/desaturated blue with frosted glass quality. Role: secondary.
- **Grid Line Blue** (#2d5fe0): Isometric grid lines overlaid on the hero canvas, slightly lighter than the base blue. Role: border.

### Surface & Shadows
- **Blueprint Blue** (#1a4fd6): Full-bleed hero canvas background — the dominant cobalt/royal blue that fills the entire viewport. Role: background.
- **Canvas White** (#ffffff): Primary text, nav labels, headline copy, and annotation overlays on the blue canvas. Role: background.

## Typography

Typography uses inter, iAWriterQuattroV across extracted hierarchy roles. Keep hierarchy mapped to these token rows before adding decorative type styles.

Mixes inter and iAWriterQuattroV for visual contrast. Weight range spans semi-bold, regular, medium. Sizes range from 8px to 24px.

### Font Roles
- **Headline Font**: inter
- **Body Font**: inter

### Type Scale Evidence
| Role | Font | Size | Weight | Line Height | Letter Spacing | Stack / Features | Notes |
|------|------|------|--------|-------------|----------------|------------------|-------|
| Primary hero headline — uppercase, bold, bottom-left anchored on the canvas | inter | 24px | 560 | 33.6px | -1px | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |
| Navigation link labels inside the pill nav bar | inter | 16px | 400 | 20.6208px | normal | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |
| Section-level subheadings and card titles | inter | 18px | 500 | 28.8px | -0.25px | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |
| General body copy and UI text — most frequent typography tuple | inter | 16px | 400 | 20.6208px | normal | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |
| Blueprint coordinate labels, ruler tick marks, and technical overlay annotations on the canvas | iAWriterQuattroV | 8px | 400 | 8px | 0.3px | iAWriterQuattroV, iAWriterQuattroV Fallback; features: "cv05", "cv11" | Extracted token |
| Monospace labels, code snippets, and secondary annotation text | iAWriterQuattroV | 12px | 400 | 21px | -0.5px | iAWriterQuattroV, iAWriterQuattroV Fallback; features: "cv05", "cv11" | Extracted token |
| Small UI labels, button text, metadata tags | inter | 14px | 500 | 18.0432px | normal | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |
| Numeric display values, counters, and large data labels | inter | 24px | 510 | 27.6px | -0.528px | inter, inter Fallback; features: "cv05", "cv11" | Extracted token |

## Layout

Layout rhythm is inferred from spacing tokens and responsive breakpoint evidence.

### Spacing System
| Token | Value | Px | Notes |
|------|-------|----|-------|
| space-0 | 0px | 0 | Mapped to --space-0 |
| space-1 | 4px | 4 | Mapped to --space-1 |
| space-2 | 8px | 8 | Mapped to --space-2 |
| space-3 | 12px | 12 | Mapped to --space-3 |
| space-4 | 16px | 16 | Mapped to --space-4 |
| space-5 | 24px | 24 | Mapped to --space-5 |
| space-6 | 32px | 32 | Mapped to --space-6 |
| space-7 | 40px | 40 | Mapped to --space-7 |
| space-8 | 48px | 48 | Mapped to --space-8 |
| space-9 | 56px | 56 | Mapped to --space-9 |
| space-10 | 64px | 64 | Mapped to --space-10 |
| space-11 | 80px | 80 | Mapped to --space-11 |
| space-12 | 96px | 96 | Mapped to --space-12 |
| space-13 | 128px | 128 | Mapped to --space-13 |
| space-14 | 256px | 256 | Mapped to --space-14 |
| space-15 | 512px | 512 | Mapped to --space-15 |

## Elevation & Depth

Keep depth flat unless validated shadow or interaction evidence appears in the extraction payload. Do not invent shadows beyond this evidence boundary.

### Shadow Evidence
| Shadow Token | Layers | Details |
|--------------|--------|---------|
| shadow-text-crisp | 1 | 0.5px 1px 1px 0px rgba(2, 2, 3, 0.333) |
| shadow-card-soft | 1 | 0px 3px 6px 0px rgba(0, 0, 0, 0.1) |
| shadow-glass-inset | 2 | inset 0px 1px 1px 0px rgba(255, 255, 255, 0.3) |
| shadow-card-tight | 1 | 0px 3px 4px 0px rgba(0, 0, 0, 0.1) |

### Interaction Signals
| Theme | Signal | Evidence |
|-------|--------|----------|
| Light | backdrop-filter | blur(12px) saturate(1.15) ; blur(4px) |
| Light | outline-style | solid |
| Light | outline-color | oklch(0.9366 0.027 262.04) ; oklch(0.416 0.035 262.04) ; oklch(0.6665 0.04 262.04) |
| Light | outline-width | 3px ; 2px |
| Light | outline-offset | 0px ; 2px |
| Light | transform | matrix(1, 0, 0, 1, 0, 0) ; matrix(0.707107, -0.707107, 0.707107, 0.707107, 5, 13) ; matrix(1, 0, 0, 1, 0, 24) |

## Shapes

Shape language maps directly to rounded tokens. Keep component corners consistent with the role mapping below before introducing bespoke geometry.

### Radius Roles
| Token | Value | Px | Role Mapping |
|------|-------|----|--------------|
| radius-0 | 4px | 4 | Subtle corner |
| radius-1 | 8px | 8 | Control corner |
| radius-subtle | 9.5px | 9.5 | Control corner |
| radius-2 | 12px | 12 | Control corner |
| radius-3 | 16px | 16 | Card corner |
| radius-pill | 9999px | 9999 | Large surface corner |

### Geometry Evidence
| Radius Token | Shape | Units |
|--------------|-------|-------|
| radius-0 | 4px | px |
| radius-1 | 8px | px |
| radius-2 | 12px | px |
| radius-3 | 16px | px |
| radius-pill | 9999px | px |
| radius-subtle | 9.5px | px |

## Components

(none detected)

## Do's and Don'ts

Guardrails protect Core token rhythm without adding unsupported visual claims.

| Do | Don't |
|----|---------|
| Do maintain consistent spacing using the base grid | Don't make unsupported claims about absent visual features |
| Do maintain WCAG AA contrast ratios (4.5:1 for normal text) | Don't mix rounded and sharp corners in the same view |
| Do use the primary color only for the single most important action per screen |  |
| Do verify evidence before writing new design-system guidance |  |

## Responsive Evidence

### Breakpoints

No distinct responsive breakpoints were extracted.

## Agent Prompt Guide

### Example Component Prompts
- Create button component using validated primary color role and spacing tokens.
- Create card component with mapped radius role and evidence-backed elevation.
- Create form input component using inferred typography hierarchy and border roles.

### Iteration Guide
1. Start with extracted palette and typography roles only.
2. Map spacing and radius directly from token tables before visual polish.
3. Apply component patterns one section at a time and compare against source intent.
4. Keep elevation claims tied to explicit evidence in output.
5. Iterate with smallest diffs and re-check section hierarchy after each change.
