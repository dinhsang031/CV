---
name: Insight Professional
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006591'
  on-secondary: '#ffffff'
  secondary-container: '#39b8fd'
  on-secondary-container: '#004666'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#07006c'
  on-tertiary-container: '#7073ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Be Vietnam Pro
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is engineered for professional authority and analytical clarity, reflecting the persona of a senior data specialist and corporate educator. The aesthetic is **Modern Corporate**, prioritizing structural precision over decorative flair. It balances the coldness of data with the warmth of mentorship through a humanistic sans-serif typeface and expansive whitespace. 

The emotional response is one of **unwavering trust, technical competence, and approachability**. The interface uses "Data-driven" visual cues—fine lines, rhythmic spacing, and a systematic hierarchy—to communicate expertise in complex information environments.

## Colors

The palette is anchored by **Corporate Blue** (Primary), a deep navy that signifies stability and intelligence. **Data Accent** (Cyan) is used sparingly for interactive elements and data highlights, providing a modern, "tech-forward" energy. 

- **Primary:** Navigation, headings, and high-emphasis backgrounds.
- **Secondary (Cyan):** Primary actions, progress indicators, and active states.
- **Tertiary (Indigo):** Secondary actions and subtle highlights in data visualizations.
- **Neutral:** A range of slates for text and light grays for surface separation, ensuring a clean, breathable canvas.

## Typography

Using **Be Vietnam Pro** across all levels ensures a cohesive, contemporary feel. The system utilizes refined weights—Medium (500) for UI labels and SemiBold (600) for headlines—to maintain a professional hierarchy. 

Headlines use slight negative letter-spacing to appear more tightly knit and authoritative. Body text is set with a generous line height (1.6) to maximize readability for long-form educational content and profile bios.

## Layout & Spacing

This design system employs a **12-column fluid grid** for desktop, transitioning to a single-column layout for mobile. 

- **Desktop (1024px+):** 12 columns, 24px gutters, 48px side margins.
- **Tablet (768px - 1023px):** 8 columns, 20px gutters, 32px side margins.
- **Mobile (Up to 767px):** 4 columns, 16px gutters, 16px side margins.

Horizontal spacing follows a strict 4px base unit. Vertical rhythm is driven by "stack" tokens to ensure consistent distancing between text blocks and interactive components.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. Surfaces are kept flat and clean, but key interactive elements use depth to indicate "clickability."

- **Level 0 (Background):** White or `#F8FAFC`.
- **Level 1 (Cards):** White background with a subtle 1px border in `#E2E8F0` and a very soft, diffused shadow (0px 4px 20px rgba(15, 23, 42, 0.05)).
- **Level 2 (Hover/Active):** Slightly deeper shadow (0px 8px 30px rgba(15, 23, 42, 0.08)) to provide tactile feedback without looking heavy.
- **Overlays:** Darker overlays for modals are used sparingly to maintain the clean, light-filled aesthetic.

## Shapes

The design system uses a **Rounded** philosophy. Standard containers and cards use a `0.5rem` (8px) radius, providing a modern look that isn't overly aggressive. Interactive elements like buttons and chips utilize **Pill-shaped** (full radius) borders to create a distinct visual contrast against the more structured grid of the cards.

## Components

### Buttons
Primary buttons are **pill-shaped**, using the `corporate-blue` background with white text. Hover states shift to `data-accent`. Secondary buttons use an outline style with a 1.5px stroke.

### Cards
High-end cards feature `0.5rem` rounded corners, a subtle 1px slate border, and the Level 1 shadow. Content within cards should have at least `24px` of internal padding to maintain the "clean" narrative.

### Tab Systems
Interactive tabs use a minimalist underline style. The active tab is highlighted with a 2px `data-accent` bottom border and Medium weight text.

### Chips & Tags
Used for skills (e.g., "Python", "Tableau"). These are small, pill-shaped elements with a `surface-soft` background and `text-slate` color, ensuring they don't compete with primary actions.

### Input Fields
Fields are rectangular with `0.5rem` roundedness, using a light slate background and a clear focus state that applies a 2px `data-accent` border.

### Iconography
Line-based icons with a consistent 2px stroke weight. Icons should be monochrome (Corporate Blue) unless used in a data visualization context, where the Data Accent may be applied.