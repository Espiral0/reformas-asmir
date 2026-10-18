---
name: Azure & Rose Reform
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
  on-surface-variant: '#3f4850'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#b90538'
  on-secondary: '#ffffff'
  secondary-container: '#dc2c4f'
  on-secondary-container: '#fffbff'
  tertiary: '#006387'
  on-tertiary: '#ffffff'
  tertiary-container: '#007da9'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#ffdadb'
  secondary-fixed-dim: '#ffb2b7'
  on-secondary-fixed: '#40000d'
  on-secondary-fixed-variant: '#92002a'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system targets homeowners, commercial space renovators, and design-conscious clients seeking premium architectural and interior renovation services. The interface conveys structural reliability, pristine craftsmanship, and creative vitality. 

The aesthetic is Modern Architectural Minimalism paired with High-Contrast Precision: luminous, expansive white and pale-slate backdrops, structural deep navy typography, airy sky-blue structural grounding, and energetic bubblegum pink accents reserved strictly for strategic focal points and calls to action. The emotional impact is confident, immaculately organized, and distinctly contemporary—distancing itself from generic construction sites through sharp typography, crisp edge definition, and intentional chromatic tension.

## Colors
The palette balances technical precision with high-conversion dynamism:

- **Primary (`#0284c7` / Deep Sky Azure):** Establishes institutional trust, architectural clarity, and primary structural accents. Used for active navigation, secondary interactive states, and foundational highlights.
- **Secondary (`#f43f5e` / Vibrant Rose Pink):** The high-conversion spark. Reserved for primary calls to action (e.g., "Pedir Presupuesto", "Ver Proyectos"), high-priority status indicators, and selective decorative focal points.
- **Tertiary (`#38bdf8` / Soft Cerulean):** Applied in non-interactive supportive visual assets, hover tints, structural badges, and soft tinted backgrounds (`#e0f2fe`).
- **Neutral (`#0f172a` / Deep Slate Navy):** Provides high-contrast legibility for titles and text over radiant white backgrounds (`#ffffff` and `#f8fafc`). Avoid pure black; this slate navy maintains architectural sophistication.
- **Surface Accents:** Soft tinted containers use `#fdf2f8` for rose accents and `#f0f9ff` for azure environments to maintain ambient warmth.

## Typography
Headlines utilize **Space Grotesk** to evoke architectural blueprints, spatial calculations, and technical precision. Body narrative, data displays, and interface controls rely on **Manrope**, selected for its geometric balance, open counters, and high legibility across client presentations and estimate calculators.

Headlines larger than 32px automatically compress via mobile token scales to eliminate orphan text and maintain clean grid alignments.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid on desktop (max width `1440px`), scaling down to 8 columns on tablets and 4 columns on mobile viewports.

Margins frame project photography and architectural plans with clean borders:
- **Desktop (1024px+):** `margin: 3rem`, `gutter: 1.5rem`. Layout maintains airy vertical cadence with 4rem to 6rem between primary page sections.
- **Tablet (768px - 1023px):** `margin: 2rem`, `gutter: 1.25rem`. Two-column architectural comparison matrices collapse into single staggered stacks.
- **Mobile (< 768px):** `margin-mobile: 1.25rem`, `gutter-mobile: 1rem`. Sticky project configuration bars and single-column project feeds preserve tap precision without visual clutter.

## Elevation & Depth
Depth is created through clean surface layering and soft, daylight-inspired ambient shadows rather than heavy skeuomorphic shading.

- **Level 0 (Base Canvas):** Pure white `#ffffff` or clean architectural mist `#f8fafc`.
- **Level 1 (Cards, Form Containers):** Surface layer elevated with a sharp low-contrast border (`1px solid #e2e8f0`) and subtle diffuse shadow (`0 4px 20px -2px rgba(15, 23, 42, 0.05)`).
- **Level 2 (Dropdowns, Floating Filters, Sticky Navbars):** Translucent frosted background (`rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(12px)`), backed by crisp borders (`1px solid rgba(2, 132, 199, 0.12)`) and light ambient shadow (`0 10px 30px -4px rgba(15, 23, 42, 0.08)`).
- **Level 3 (Modal Dialogs, Project Estimators):** Ambient projection tinted with faint sky hue (`0 20px 40px -10px rgba(2, 132, 199, 0.15)`), encased in clean structural containers over a soft slate overlay (`rgba(15, 23, 42, 0.4)`).

## Shapes
A roundedness factor of `2` (`0.5rem` / `8px` base) reflects contemporary finished millwork and architectural joinery—approachable and ergonomic, yet structural and precise. 

- Interactive controls, form fields, and standard buttons take `rounded-md` (`8px`).
- High-level renovation showcase cards, modal surfaces, and quote summaries employ `rounded-lg` (`16px`).
- Segmented project tags and floating status indicators utilize fully-rounded capsules (`9999px`) to create clear geometric contrast against rectangular room plans and portfolio imagery.

## Components

### Buttons & CTAs
- **Primary Action (Call to Action):** Solid Bubblegum Rose (`#f43f5e`) with pure white text (`#ffffff`), `font-weight: 600`, and `rounded-md`. Hover state darkens to `#e11d48` with a micro-lift (`translateY(-1px)`).
- **Secondary Action:** Transparent fill with a 1.5px border in Deep Sky Azure (`#0284c7`), text in `#0284c7`. Hover state triggers soft tinted background (`#e0f2fe`).
- **Tertiary Action:** Flat text in `#0f172a` with an animated underline in `#38bdf8`.

### Input Fields & Calculation Controls
- Crisp backgrounds (`#ffffff`) framed by `1px solid #cbd5e1`. 
- Focus state switches border to `#0284c7` accompanied by a soft azure halo (`0 0 0 3px rgba(56, 189, 248, 0.2)`). 
- Placeholder text in `#94a3b8`. Floating labels use `label-md` in `#0f172a`.

### Cards & Project Showcases
- White containers with subtle 1px border (`#f1f5f9`).
- Image containers feature a standard 16:10 aspect ratio with smooth image scale on card hover.
- Cards feature before/after overlay tags and phase labels (e.g., "En Ejecución", "Finalizado").

### Selection Controls (Checkboxes, Radio Buttons)
- 20px controls with `rounded-sm` for checkboxes and circular geometry for radios.
- Unchecked: `1.5px solid #cbd5e1` on white.
- Checked: Fill in `#f43f5e` displaying crisp white glyphs, validating user input with high energy.

### Chips & Badges
- **Status/Informational:** Soft Azure background (`#e0f2fe`) with deep azure text (`#0369a1`).
- **Highlight/Offer:** Soft Rose background (`#fdf2f8`) with vibrant rose text (`#e11d48`).
- **Filter Chips:** Light slate base (`#f1f5f9`), shifting to solid `#0284c7` with white text upon selection.

### Renovation-Specific Components
- **Before/After Split Slider:** Precision-engineered divider in `#f43f5e` with white circular drag handle.
- **Budget Cost Estimator Bar:** Multi-segmented progress bar using `#38bdf8` for completed stages and `#f43f5e` for estimated final balances.