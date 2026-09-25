---
name: Cyber Void Portfolio
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#33394c'
  surface-container-lowest: '#070d1f'
  surface-container-low: '#151b2d'
  surface-container: '#191f31'
  surface-container-high: '#23293c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce1fb'
  on-surface-variant: '#bbc9cd'
  inverse-surface: '#dce1fb'
  inverse-on-surface: '#2a3043'
  outline: '#859397'
  outline-variant: '#3c494c'
  surface-tint: '#2fd9f4'
  primary: '#8aebff'
  on-primary: '#00363e'
  primary-container: '#22d3ee'
  on-primary-container: '#005763'
  inverse-primary: '#006877'
  secondary: '#f8acff'
  on-secondary: '#570067'
  secondary-container: '#7d0793'
  on-secondary-container: '#f396ff'
  tertiary: '#b6e2ff'
  on-tertiary: '#00354a'
  tertiary-container: '#68cbff'
  on-tertiary-container: '#005574'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a2eeff'
  primary-fixed-dim: '#2fd9f4'
  on-primary-fixed: '#001f25'
  on-primary-fixed-variant: '#004e5a'
  secondary-fixed: '#ffd6ff'
  secondary-fixed-dim: '#f8acff'
  on-secondary-fixed: '#350040'
  on-secondary-fixed-variant: '#7b0190'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0c1324'
  on-background: '#dce1fb'
  surface-variant: '#2e3447'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
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
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin: 2.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects a high-end, immersive, and futuristic digital art space. It captures the tension between deep digital voids and hyper-saturated chromatic luminescences. Targeted at digital artists, creative technologists, web3 curators, and collectors, the aesthetic balances experimental cybernetic energy with structural discipline. 

The aesthetic is grounded in **Glassmorphic Cyber-Minimalism**: 
- Surfaces are dark, translucent, and treated with optical frost to allow vibrant artwork to push forward.
- Interactive nodes emit electric cyan and fuchsia atmospheric radiance.
- Functional controls maintain an architectural, technical rigor reminiscent of creative coding workbenches and high-performance creative suites.

## Colors

The palette establishes an ultra-deep canvas offset by high-luminance spectral neon accents:

- **Neutral Canvas (`#020617` / Slate 950):** Deep void serving as the base layer, preventing ambient light interference and isolating creative assets.
- **Primary Accent (`#22d3ee` / Cyan 400):** Main interactive affordance, focus indicator, and active state signal. Delivers crisp clarity against obsidian backgrounds.
- **Secondary Accent (`#e879f9` / Fuchsia 400):** Expressive chromatic counterpoint used for secondary highlights, tags, and interactive hover shifts.
- **Tertiary Accent (`#38bdf8` / Sky 400):** Supporting informational hue used for telemetry, metadata highlights, and state differentiation.

### WCAG 2.2 AA Contrast & Typography Accessibility
- **Primary Body Text:** In dark mode, standard body text defaults to `text-slate-300` (`#cbd5e1`), achieving an 11.8:1 contrast ratio against the `#020617` background (far exceeding the 4.5:1 AA requirement). For any light-mode fallback surfaces, text resolves to `text-slate-700` (`#334155`).
- **Muted & Metadata Text:** Secondary labels use `text-slate-400` (`#94a3b8`), retaining an accessible 7:1 ratio.
- **Interactive Accents:** Interactive neon text labels (cyan and fuchsia) paired against dark substrates maintain strict AA compliance for large and bold text, with focus indicators featuring high-contrast double rings.

## Typography

The typographic hierarchy bridges clean structural modernism with code-informed precision:

- **Headlines & Body (`Inter`):** Delivers clean optical balance, tall x-height, and neutral precision. Headings use tight negative tracking (`-0.02em` to `-0.03em`) for a solid editorial feel.
- **Labels, Telemetry & Metadata (`JetBrains Mono`):** Applied to technical details, dimensions, curation IDs, aspect ratios, timestamps, tags, and navigation keys.
- **Scale Dynamics:** Primary display typography contracts gracefully on mobile viewports via `display-lg-mobile` to maintain legibility without breaking grid bounds.

## Layout & Spacing

The design system runs on a 12-column fluid grid system pinned to an 8px modular baseline scale:

- **Desktop (>= 1024px):** 12-column layout with 24px (`1.5rem`) gutters and 40px (`2.5rem`) outer margin bounds. Maximum content container width clamps to 1440px.
- **Tablet (768px - 1023px):** 8-column fluid layout with 20px gutters and 24px margins.
- **Mobile (< 768px):** 4-column fluid layout with 16px (`1rem`) gutters and 16px (`1rem`) margins.

Artwork showcases rely on asymmetrical masonry or balanced split-grid configurations, ensuring images and real-time canvas elements are framed by proportional negative space.

## Elevation & Depth

Visual depth is achieved through translucent optical stratification and localized chromatic blooms rather than conventional drop shadows:

- **Canvas Foundation (Base Level):** Solid `#020617` (Slate 950).
- **Glass Panel Surface (Level 1):** `rgba(15, 23, 42, 0.65)` layered with `backdrop-filter: blur(16px)` and a hairline outer rim of `1px solid rgba(255, 255, 255, 0.08)`.
- **Raised Interactive Glass (Level 2 - Hover / Active):** `rgba(30, 41, 59, 0.7)` with `backdrop-filter: blur(24px)` and a dynamic edge gradient `1px solid rgba(34, 211, 238, 0.25)`.
- **Neon Volumetric Glows:**
  - *Cyan Radiant:* `box-shadow: 0 0 24px -4px rgba(34, 211, 238, 0.35)`
  - *Fuchsia Radiant:* `box-shadow: 0 0 24px -4px rgba(232, 121, 249, 0.35)`
  - *Subtle Ambient:* `box-shadow: inset 0 1px 1px 0 rgba(255, 255, 255, 0.1)` along top internal borders to mimic edge reflection on acrylic glass.

## Shapes

The design system incorporates geometric balance (`roundedness: 2`), utilizing 8px (`0.5rem`) radii for base interactive elements and 16px (`1rem`) radii for exhibition panels and glass dialogs:

- **Panels & Cards:** 16px (`rounded-lg`) corner radii to maintain soft optical containment for sharp-edged digital artwork.
- **Buttons, Inputs & Controls:** 8px base radii for precise mechanical affordance.
- **Pills & Metatags:** Full radii (`9999px`) reserved strictly for status chips and classification tags.

## Components

### Buttons
- **Primary Cyber:** Solid fill `bg-cyan-400 text-slate-950 font-semibold`, hovering to `bg-cyan-300` with a `0 0 20px rgba(34, 211, 238, 0.5)` drop-bloom. Focus-visible applies a 2px offset ring of `ring-2 ring-cyan-400`.
- **Glass Secondary:** `bg-slate-900/60 backdrop-blur-md text-slate-200 border border-slate-700/60`. Hover triggers border transition to `border-fuchsia-400/80` and text color to `text-fuchsia-300`.
- **Ghost Action:** Transparent background with `text-slate-400 hover:text-cyan-400 font-mono text-sm tracking-wide`.

### Cards & Exhibit Frames
- Constructed from `bg-slate-900/40 backdrop-blur-xl border border-white/10 rounded-lg overflow-hidden`.
- Image frames preserve a 1px inner bezel (`inset 0 0 0 1px rgba(255,255,255,0.05)`).
- On hover, the top border illuminates with a cyan-to-fuchsia linear gradient, elevating `translate-y-[-2px]`.

### Chips & Metadata Tags
- Fixed height of 24px or 28px, composed of `bg-slate-900/80 border border-slate-800 rounded-full px-3 py-0.5`.
- Text renders in `JetBrains Mono` at `11px` or `12px`. Status chips incorporate an illuminated 6px circular indicator with an ambient pulsing glow (`animate-pulse`).

### Input Fields
- Dark glass inputs: `bg-slate-950/60 border border-slate-800 text-slate-200 placeholder:text-slate-500 rounded-md px-4 py-2.5 backdrop-blur-md`.
- Focus state activates `border-cyan-400 ring-1 ring-cyan-400/50 outline-none`.

### Checkboxes & Radio Controls
- Base: 16px square (or circle) in `border border-slate-700 bg-slate-900/80`.
- Selected: `bg-cyan-400 border-cyan-400 text-slate-950` with an outer cyan focus-halo.

### Lists & Activity Feeds
- Row items separated by hairline `border-b border-slate-800/60`.
- Interaction state transitions the row to `bg-white/[0.02]`.
- Secondary metrics, file hashes, and token IDs render strictly in `JetBrains Mono text-slate-400`.