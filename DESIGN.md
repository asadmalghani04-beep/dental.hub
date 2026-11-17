---
name: Dental Hub Clinical Architecture
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3e4850'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6e7881'
  outline-variant: '#bec8d2'
  surface-tint: '#006591'
  primary: '#006591'
  on-primary: '#ffffff'
  primary-container: '#0ea5e9'
  on-primary-container: '#003751'
  inverse-primary: '#89ceff'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#00687a'
  on-tertiary: '#ffffff'
  tertiary-container: '#00aac6'
  on-tertiary-container: '#003943'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c9e6ff'
  primary-fixed-dim: '#89ceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system establishes a clinical, reassuring, and distinctly premium aesthetic for high-end specialized oral care in Lahore, Pakistan. The visual language merges modern medical precision with hospitality-grade warmth to eliminate dental anxiety and convey institutional credibility.

The style follows a refined, crisp contemporary healthcare direction with architectural discipline:
- **Atmospheric Clarity:** Airy, open compositions dominated by pristine surfaces and soft, clinical slates rather than sterile hospital whites.
- **Micro-Luminescence:** Subtly glowing cyan highlights paired with oceanic blues evoke clinical hygiene, dental clear-aligner transparency, and precision laser diagnostics.
- **Empathetic Geometry:** Soft, pill-driven touchpoints balance architectural grid discipline, projecting approachability without sacrificing professional rigor.

## Colors

The palette leverages high-frequency oceanic and cyan tones to reinforce sterileness, freshness, and advanced technology.

- **Primary (`#0EA5E9`):** Pure Sky Blue. Applied to dominant interactive touchpoints, primary appointment actions, and key verification badges.
- **Secondary (`#14B8A6`):** Precision Teal. Used for clinical wellness indicators, treatment progress metrics, and reassuring secondary feedback.
- **Tertiary (`#06B6D4`):** Crisp Accent Cyan. Reserved for active state borders, sub-micron focal rings, glowing micro-accents, and treatment phase tags.
- **Neutral (`#0F172A`):** Deep Navy. Anchors all high-contrast clinical copy, navigational iconography, and structured tabular typography, completely replacing pure black to soften readability.
- **Surface Canvas (`#F8FAFC`, `#F1F5F9`):** Layered slate substrates that create structured card isolation against high-gloss `#FFFFFF` modal and card planes.

## Typography

The typography uses Inter across all viewports to project clinical legibility and technical rigor. 

- **Display & Headlines:** Tightly tracked headings (-0.02em) communicate modern authority. Large numbers (consultation fees, procedure times, tooth indexing) use tabular figures (`font-variant-numeric: tabular-nums`).
- **Body:** Open line-heights (1.6x) ensure effortless readability for medical procedures, treatment consent, and post-operative instructions.
- **Labels & Badges:** Micro-labels utilize slight letter spacing with uppercase or semi-bold capitalization to maintain immediate recognition on diagnostic charts and patient dashboards.

## Layout & Spacing

The layout is built around a structured 12-column responsive fluid grid designed to manage complex medical scheduling, dental service tiers, and patient health records.

- **Desktop (>= 1280px):** 12-column layout, max-width container of 1320px, 48px canvas margin, and 24px gutters. Clinical dashboards balance a fixed 280px navigation rail with flexible diagnostics views.
- **Tablet (768px - 1279px):** 8-column layout, 32px canvas margin, and 20px gutters. Diagnostic matrices collapse into dual-column cards.
- **Mobile (<= 767px):** 4-column layout, 20px canvas margin, and 16px gutters. Form panels and booking wizards stack into vertical streams with sticky bottom execution bars.

## Elevation & Depth

Visual hierarchy is maintained through clinical surface layering and tinted atmospheric shadows:

- **Base Layer:** The global viewport backdrop rests on soft `#F8FAFC`. Secondary sub-panels and metadata sidebars sit on `#F1F5F9`.
- **Card Tier (Elevation 1):** Pure `#FFFFFF` planes surfaced with a 1px border of `#E2E8F0` and an ultra-subtle tinted shadow (`box-shadow: 0 4px 20px -2px rgba(15, 23, 42, 0.04), 0 2px 6px -1px rgba(15, 23, 42, 0.02)`).
- **Floating Overlay Tier (Elevation 2):** Booking modals, dental chart popovers, and interactive date pickers lift with an ambient oceanic drop shadow (`box-shadow: 0 16px 36px -4px rgba(14, 165, 233, 0.08), 0 6px 12px -2px rgba(15, 23, 42, 0.04)`).
- **Interactive Focus & Precision State:** Interactive components do not use heavy shadows to denote active states; instead, they employ a crisp 1.5px `#06B6D4` cyan border complemented by a faint translucent cyan halo (`0 0 0 4px rgba(6, 182, 212, 0.15)`).

## Shapes

The design system incorporates intentional soft-curved geometry to deliver a friendly, reassuring presence while keeping structural cards stable:

- **Standard Containers (`rounded-xl` / 16px):** Clinical service cards, tooth chart modules, and booking blocks.
- **Prominent Cards & Surface Hubs (`rounded-2xl` / 24px):** Primary hero cards, patient profile summaries, and clinic feature panels.
- **Interactive Controls & Medical Badges (`rounded-full` / 9999px):** Doctor credential pills, treatment category chips, status tags, and action buttons.

## Components

### Buttons
- **Primary:** Filled `#0EA5E9` background with pure `#FFFFFF` typography, fully rounded (`rounded-full`), padded `12px 24px`. Hover transitions smoothly into a saturated sky shade (`#0284C7`) with subtle forward translation.
- **Secondary / Clinic Action:** Translucent teal foundation (`rgba(20, 184, 166, 0.1)`) with `#0F766E` text and a subtle 1px border of `rgba(20, 184, 166, 0.2)`.
- **Ghost:** Crisp `#0F172A` text on transparent base, gaining `#F1F5F9` background on hover.

### Medical Badges & Chips
- **Status Pills:** Pill-shaped tags (`rounded-full`) using semantic tint fills (e.g., `rgba(20, 184, 166, 0.1)` for "Verified Specialist" or "Sterilized Facility") paired with saturated foreground text and a 6px status dot.
- **Filter Chips:** `#FFFFFF` background, 1px `#E2E8F0` border, `#0F172A` label; active state switches to `#0EA5E9` fill with white text.

### Cards
- Constructed with `#FFFFFF` backgrounds, `rounded-2xl` corners, 1px structural borders in `#E2E8F0`, and `space-lg` padding. Cards feature distinct header zones with clear visual separation for medical metadata (e.g., doctor qualifications, clinic room assignments).

### Form Inputs & Date Pickers
- Input containers feature `#FFFFFF` fill, 1px `#CBD5E1` border, `rounded-xl` geometry, and 48px total height. Focus states cleanly swap the border to `#0EA5E9` with an outward 3px cyan glow ring (`rgba(6, 182, 212, 0.12)`). Labels remain strictly outside the input using `label-md` in `#475569`.

### Specialized Dental Components
- **Odontogram / Tooth Chart Modules:** High-contrast interactive vector tooth visualizer encased in a `rounded-xl` card, with selected teeth indicated via crisp `#0EA5E9` borders and `#E0F2FE` soft fills.
- **Specialist Credential Card:** Features an offset avatar with an absolute-positioned verified status checkmark badge in `#14B8A6`.