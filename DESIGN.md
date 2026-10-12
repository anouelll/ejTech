---
name: Executive Engineering
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#44474f'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#747780'
  outline-variant: '#c4c6d1'
  surface-tint: '#425e94'
  primary: '#00214f'
  on-primary: '#ffffff'
  primary-container: '#17376b'
  on-primary-container: '#86a2dc'
  inverse-primary: '#adc6ff'
  secondary: '#1860a5'
  on-secondary: '#ffffff'
  secondary-container: '#7ab3fe'
  on-secondary-container: '#00447d'
  tertiary: '#002917'
  on-tertiary: '#ffffff'
  tertiary-container: '#004127'
  on-tertiary-container: '#49b47f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#28467b'
  secondary-fixed: '#d3e3ff'
  secondary-fixed-dim: '#a3c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#8df8bd'
  tertiary-fixed-dim: '#71dba2'
  on-tertiary-fixed: '#002112'
  on-tertiary-fixed-variant: '#005232'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4rem
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
  code:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes an architectural, high-conviction presence tailored for enterprise technology consulting and systems engineering. The interface targets key decision-makers: CTOs, CIOs, and executive leadership of mid-market enterprises and digital service companies (ESNs).

The visual language balances institutional prestige with engineering precision. It avoids the noisy aesthetics of consumer software in favor of structural clarity, confident whitespace, and subtle micro-tactile details. The emotional baseline is deliberate stability, deep technical mastery, and frictionless execution. Surfaces remain luminous, elevated, and quiet, allowing architecture diagrams, metrics, and technical narratives to take center stage.

## Colors

The palette is engineered around clarity, hierarchy, and purpose:

- **Primary (`#17376B` - Deep Tech Navy):** Represents authority, governance, and architectural stability. Used for primary typography, structural headers, high-level brand assets, and dominant containers.
- **Secondary (`#2F6FB5` - Kinetic Blue):** Represents digital connectivity, engineering fluidity, and secondary actions. Used for interactive links, focused state indicators, and subtle graphical structural lines.
- **Tertiary / Action Accent (`#2E9E6B` - Performance Emerald):** Strictly deployed for conversions, positive status signals, active deployments, key CTAs, and KPI badge accents. It signals system health, momentum, and business outcome validation.
- **Surfaces & Canvas:**
  - Base background canvas: `#F3F5F9` (airy, muted slate-wash).
  - Surface cards & overlays: `#FFFFFF` (pristine pure white).
  - Subtle borders: `#E2E8F0` / `rgba(23, 55, 107, 0.08)`.
- **Text & Content Hierarchy:**
  - Primary text: `#1F2937` (rich graphite black for contrast and prolonged reading comfort).
  - Secondary text: `#4B5563` (balanced cool grey for meta text, labels, and secondary context).
  - Muted text: `#9CA3AF` (disabled states, inactive breadcrumbs, tertiary timestamps).

## Typography

The typographic pairing balances distinct executive authority with functional ergonomics. 

- **Display & Headings (Plus Jakarta Sans):** Crafted with balanced geometric cuts and refined terminals. Tight tracking (`-0.01em` to `-0.03em`) provides a modern, premium corporate demeanor suitable for transformation strategies and enterprise service titles.
- **Body & Longform (Inter):** Leveraged for its clinical neutral legibility, tall x-height, and superior rendering across high-DPI and standard display monitors. Line heights are intentionally generous (`1.5` to `1.6`) to sustain effortless scanning of technical proposals and project audit roadmaps.
- **Code & Specs (JetBrains Mono):** Reserved for infrastructure parameters, API references, architecture schemas, and audit logs.

## Layout & Spacing

The architecture utilizes a responsive 12-column fluid grid system bounded by a maximum content container of `1280px`. 

- **Grid Geometry:**
  - **Mobile (&lt; 768px):** 4-column layout, `margin` of `1rem` (16px), `gutter` of `1rem` (16px).
  - **Tablet (768px - 1024px):** 8-column layout, `margin` of `2rem` (32px), `gutter` of `1.5rem` (24px).
  - **Desktop (&gt; 1024px):** 12-column layout, `margin` of `3rem` (48px), `gutter` of `2rem` (32px).
- **Rhythm & Breathing Space:** Section stacking relies on `space-2xl` and `space-3xl` to preserve editorial distinction between services, proof-of-work case studies, and callout matrices. Components prioritize high internal breathing room (`space-lg` to `space-xl` inner padding) to avoid cramped, legacy-enterprise densities.

## Elevation & Depth

Visual hierarchy uses a refined hybrid approach: low-contrast borders combined with ultra-diffused atmospheric shadows tinted with the primary navy hue. Flat surfaces look anchored rather than floating arbitrarily.

- **Level 0 (Flat / Canvas):** Surface color `#F3F5F9`. No shadow.
- **Level 1 (Card / Rest):** Pure `#FFFFFF` background, solid border `1px solid rgba(23, 55, 107, 0.08)`, soft shadow `0 2px 8px -2px rgba(23, 55, 107, 0.05), 0 1px 3px 0 rgba(23, 55, 107, 0.03)`.
- **Level 2 (Interactive Hover / Floating Panels):** `#FFFFFF` background, border `1px solid rgba(47, 111, 181, 0.20)`, elevated shadow `0 12px 28px -6px rgba(23, 55, 107, 0.08), 0 4px 12px -2px rgba(23, 55, 107, 0.04)`.
- **Level 3 (Modals / Overlays / Flyouts):** `#FFFFFF` background, border `1px solid rgba(23, 55, 107, 0.12)`, deep elevation `0 24px 48px -12px rgba(23, 55, 107, 0.16)`.
- **Accent Elevation (Action / CTA Focus):** Emerald button hovers cast an atmospheric tint: `0 8px 20px -4px rgba(46, 158, 107, 0.35)`.

## Shapes

The design system adopts a balanced, contemporary rounded corner philosophy that softens corporate rigidity without appearing playful or juvenile.

- **Base Radius (`rounded-md` - 0.5rem / 8px):** Form fields, interactive chips, code blocks, and micro-badges.
- **Container Radius (`rounded-lg` - 1rem / 16px):** Standard content modules, service blocks, and metric tiles.
- **Feature Card Radius (`rounded-xl` - 1.5rem / 24px):** Executive callout cards, hero banners, and testimonial modules.
- **Pill Radius (`rounded-full` - 9999px):** Status indicators, technical skill tags, and round icon avatars.

## Components

### Buttons
- **Primary Action (Conversion):** Background `#2E9E6B`, text `#FFFFFF`, radius `rounded-lg` (12px or 16px), padding `12px 24px`. Subtle transition (`transform 150ms ease, box-shadow 150ms ease`). Hover: `#26855A` with green glow shadow.
- **Secondary (Corporate Tech):** Background `#17376B`, text `#FFFFFF`. Hover: `#1F4788`.
- **Ghost / Tertiary:** Background transparent, text `#17376B`, border `1px solid rgba(23, 55, 107, 0.15)`. Hover: background `rgba(23, 55, 107, 0.04)`, border `#17376B`.

### Cards & Surface Modules
- Pure white background (`#FFFFFF`), `rounded-xl` border radius, subtle structural border (`rgba(23, 55, 107, 0.08)`).
- On interactive cards, apply subtle vertical translation (`-2px`) on hover, shifting the border to a refined `#2F6FB5` accent with Level 2 elevation.

### Tech Badges & Status Chips
- Pill-shaped (`rounded-full`), padding `4px 12px`.
- Tech Stack Chips: Subtle Navy Wash (background `rgba(47, 111, 181, 0.08)`, text `#2F6FB5`, font `label-sm`).
- Verified / Production Status: Emerald tint (background `rgba(46, 158, 107, 0.10)`, text `#2E9E6B`, accompanied by a solid `6px` pulse indicator).

### Input Fields & Controls
- Background `#FFFFFF`, border `1.5px solid #E2E8F0`, padding `12px 16px`, corner radius `0.5rem` (`rounded-md`).
- Focus state: border color `#2F6FB5`, subtle ring box-shadow `0 0 0 3px rgba(47, 111, 181, 0.15)`.
- Checkboxes & Radios: `#2E9E6B` checked fill, crisp geometric checkmark, non-jarring transitions.

### Key Metric & Architecture Displays
- Stat callouts feature `headline-xl` numbers rendered in `#17376B` paired with a small trend chip in `#2E9E6B`.
- Architecture & process blocks utilize a left-aligned, vertical blue rule line (`2px solid #2F6FB5`) for visual grounding.