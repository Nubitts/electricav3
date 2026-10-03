---
name: Tales Eléctrica
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#4c4450'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#7d7481'
  outline-variant: '#cfc3d1'
  surface-tint: '#7b47a1'
  primary: '#460d6c'
  on-primary: '#ffffff'
  primary-container: '#5e2a84'
  on-primary-container: '#d39afb'
  inverse-primary: '#e2b6ff'
  secondary: '#586061'
  on-secondary: '#ffffff'
  secondary-container: '#dce4e5'
  on-secondary-container: '#5e6667'
  tertiary: '#2d2d2d'
  on-tertiary: '#ffffff'
  tertiary-container: '#444343'
  on-tertiary-container: '#b2b0af'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f3daff'
  primary-fixed-dim: '#e2b6ff'
  on-primary-fixed: '#2e004d'
  on-primary-fixed-variant: '#612d87'
  secondary-fixed: '#dce4e5'
  secondary-fixed-dim: '#c0c8c9'
  on-secondary-fixed: '#151d1e'
  on-secondary-fixed-variant: '#404849'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-code:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system expresses a Greco-Technical aesthetic rooted in Light Neobrutalism. It synthesizes the axiomatic, geometric rigor of ancient Hellenic geometry—evoking Thales of Miletus, the foundational pioneer of electricity and proportional reasoning—with modern heavy-duty B2B high-voltage electrical engineering certified under NOM-001-SEDE and CFE standards.

The visual tone is authoritative, structurally unflinching, and unyielding in its precision. The interface balances pure structural grid alignments and subtle meander-inspired geometric cadence with utilitarian density. It eschews soft, nebulous gradients and ethereal blurs in favor of distinct physical certainty: crisp 2px deep carbon borders, tactile flat planar surfaces, and hard offset drop shadows. The resulting experience conveys ironclad institutional reliability, mathematical finality, and certified engineering competence for industrial plant directors, EPC contractors, and infrastructure operators.

## Colors

The system uses a deliberate 5-tier color matrix engineered for high contrast, maximum legibility, and unmistakable brand authority:

- **Primary (`#5E2A84` - Electric Imperial Purple):** Used for primary CTAs, key status indicators, structural framing accents, active states, and mathematical focal points. Conveys high-status institutional power and energized voltage.
- **Secondary (`#B2BABB` - Cold Metallic Slate Silver):** Represents galvanized conduit, substation busbars, transformer chassis, and grounding systems. Used for secondary borders, technical chip backgrounds, auxiliary outlines, and tabular division rules.
- **Tertiary / Structural Dark (`#1A1A1A` - Deep Carbon Black):** The anchoring element of the system. Dictates all structural 2px borders, rigid hard shadows, high-contrast headings, and foundational vector framing.
- **Neutral Surface (`#FAF9F6` - Marble Off-White):** The foundational canvas layer, referencing classical Pentelic marble. It provides an organic, high-luminance backdrop that softens stark terminal contrast without sacrificing crisp readability.
- **Component Container (`#FFFFFF` - Pure White):** Reserved for elevated cards, active input fills, data-dense technical spec sheets, and high-priority content modules to contrast immediately against the `#FAF9F6` canvas.

## Typography

Typography establishes an uncompromising technical hierarchy. 

**Space Grotesk** is chosen for headlines, structural labels, technical parameters, and navigational badges. Its mechanical construction, idiosyncratic geometric cuts, and industrial rhythm project both modernist precision and ancient proportional rigor. All upper-level labels (`label-md`, `label-code`) must be rendered in full uppercase with expanded letter-spacing to mirror engineering schematics, switchgear labels, and transformer nameplates.

**Inter** handles all running body copy, long-form compliance prose, and parametric tables. It provides unyielding neutral legibility at micro and macro scales, resisting optical distortion even in complex multi-column electrical load matrices.

## Layout & Spacing

The layout is built upon an architectural 12-column rigid grid with defined gutter lines and strict planar divisions. Spacing adopts a mathematical base-4 system, mirroring modular breaker panels and geometric friezes.

- **Desktop (1200px+):** 12-column fluid grid, 1.5rem (`24px`) gutters, and an outer margin of 3rem (`48px`) constrained to a maximum content width of 1360px.
- **Tablet (768px - 1199px):** 8-column layout, 1.25rem (`20px`) gutters, 2rem (`32px`) outer margins. Multi-column engineering comparison matrices compress into two balanced halves.
- **Mobile (< 768px):** 4-column layout, 1rem (`16px`) gutters, 1.25rem (`20px`) outer canvas margins. Elements stack strictly in vertical sequence, maintaining 2px perimeter boundaries and preserving tactile surface clarity.

Sections use a modular rhythm: content groups are separated by `space-2xl`, internal component modules by `space-xl`, and form/spec clusters by `space-md`. Layout divisions frequently employ solid 2px horizontal rules (`#1A1A1A`) featuring alternating geometric meander corner brackets to anchor section boundaries.

## Elevation & Depth

This design system completely rejects soft, blurred, or ambient diffusion shadows. Visual elevation is rendered exclusively through Light Neobrutalist hard offset geometry:

- **Surface Grounding (Level 0):** Canvas `#FAF9F6`. Base structural container lines, background meander patterns rendered at 10% opacity `#1A1A1A`, and flush field wrappers.
- **Raised Structural Surface (Level 1):** Solid white `#FFFFFF` surface enclosed in a continuous `2px solid #1A1A1A` border with a hard mechanical offset shadow: `box-shadow: 2px 2px 0px #1A1A1A`.
- **Interactive / Focus Elevate (Level 2):** Primary cards, interactive dropdowns, and key focal panels elevate with `box-shadow: 4px 4px 0px #1A1A1A`.
- **Pressed / Active State (Level -1):** Interactive elements translate down and right by 2px (`transform: translate(2px, 2px)`), resetting the shadow to `box-shadow: 0px 0px 0px #1A1A1A`, providing immediate physical feedback akin to engaging an industrial toggle switch or safety contactor.

## Shapes

The shape system is strictly calibrated to **Level 1 (Soft)**, utilizing a uniform `4px` corner radius (`0.25rem`) across cards, buttons, badges, and input boxes.

This slight 4px radius tempers the potential visual harshness of unadorned brutalism without diluting its industrial weight. It conveys the machined precision of CNC-milled steel enclosures, transformer housings, and precision switchgear casing. Sharp right-angle geometric alignments dominate interior layouts, with meander and orthogonal step motifs integrated into structural headers and tab bar dividers.

## Components

### Buttons
- **Primary CTA:** Surface `#5E2A84`, text `#FFFFFF`, border `2px solid #1A1A1A`, border-radius `4px`, shadow `2px 2px 0px #1A1A1A`. Space Grotesk `label-lg`, uppercase. Hover: `translate(-1px, -1px)` with `box-shadow: 3px 3px 0px #1A1A1A`. Active: `translate(2px, 2px)` with `box-shadow: 0px 0px 0px #1A1A1A`.
- **Secondary CTA:** Surface `#FAF9F6`, text `#1A1A1A`, border `2px solid #1A1A1A`, shadow `2px 2px 0px #1A1A1A`. Hover: background changes to `#B2BABB`.
- **Tertiary / Link:** Pure text in `#1A1A1A`, bold underline `2px solid #5E2A84` offset by 4px. Space Grotesk `label-md`.

### Chips & Badges
- Engineering certification badges (NOM-001-SEDE, CFE LAPEM certified): Background `#FFFFFF`, border `2px solid #1A1A1A`, border-radius `4px`, padding `4px 10px`. Text in Space Grotesk `label-code` uppercase.
- Status Chips: High-voltage warning indicators utilize `#5E2A84` text on a `#FAF9F6` container with a leading filled square (`6px x 6px` in `#5E2A84`).

### Input Fields & Controls
- **Text Inputs:** Background `#FFFFFF`, border `2px solid #1A1A1A`, border-radius `4px`, padding `12px 16px`, typography Inter `body-md`. Focus: `outline: none`, `border-color: #5E2A84`, `box-shadow: 2px 2px 0px #5E2A84`.
- **Checkboxes & Radios:** `18px x 18px` square with `2px solid #1A1A1A`, `2px` corner radius. Checked state: background `#5E2A84` displaying a crisp white mathematical vector checkmark.

### Cards & Technical Data Sheets
- Standard Card: Background `#FFFFFF`, border `2px solid #1A1A1A`, border-radius `4px`, shadow `2px 2px 0px #1A1A1A`, internal padding `space-lg`.
- Feature Matrix Card: Features a dedicated header band (`background: #FAF9F6; border-bottom: 2px solid #1A1A1A`) housing the card title and CFE specification codes, separated from the card body.

### Industrial Domain Components
- **Greek Meander Section Divider:** A continuous geometric 2px single-line key pattern rendered in `#1A1A1A` spanning full width, delineating major landing page sections.
- **Electrical Metric Callout:** Monospaced-styled statistic blocks featuring a `2px solid #B2BABB` inner boundary, large Space Grotesk numbers (e.g., "115 kV", "99.998%"), and tiny `#1A1A1A` uppercase subtitle tags.