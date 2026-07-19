---
name: Sage & Steel
colors:
  surface: '#faf9f6'
  surface-dim: '#dadad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f0'
  surface-container: '#eeeeea'
  surface-container-high: '#e8e8e5'
  surface-container-highest: '#e2e3df'
  on-surface: '#1a1c1a'
  on-surface-variant: '#414942'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f1f1ed'
  outline: '#717972'
  outline-variant: '#c1c9c0'
  surface-tint: '#39684b'
  primary: '#336246'
  on-primary: '#ffffff'
  primary-container: '#4c7b5d'
  on-primary-container: '#deffe5'
  inverse-primary: '#a0d2af'
  secondary: '#47664b'
  on-secondary: '#ffffff'
  secondary-container: '#c6e9c7'
  on-secondary-container: '#4b6a4f'
  tertiary: '#4a5d4d'
  on-tertiary: '#ffffff'
  tertiary-container: '#627665'
  on-tertiary-container: '#e6fde7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bbefca'
  primary-fixed-dim: '#a0d2af'
  on-primary-fixed: '#002110'
  on-primary-fixed-variant: '#214f35'
  secondary-fixed: '#c8ebca'
  secondary-fixed-dim: '#adcfaf'
  on-secondary-fixed: '#03210c'
  on-secondary-fixed-variant: '#304d35'
  tertiary-fixed: '#d2e8d3'
  tertiary-fixed-dim: '#b6ccb8'
  on-tertiary-fixed: '#0d1f12'
  on-tertiary-fixed-variant: '#384b3c'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e2e3df'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is built on a foundation of **Minimalism** and **Modern Corporate** aesthetics. It bridges the gap between traditional industry reliability and forward-thinking technology. The brand personality is calm, authoritative, and precise, targeting enterprise clients and small business owners who value efficiency and clarity.

The visual narrative uses generous whitespace (negative space) to reduce cognitive load and emphasize high-quality typography. By distilling the interface to its essential components, the design system evokes an emotional response of trust and effortless sophistication.

## Colors

The palette is anchored by **Sage Green**, a color that represents growth and stability. This is supported by a range of functional grays and an off-white background to prevent the clinical feeling of pure white.

- **Primary (Sage Green):** Used for primary actions, success states, and brand-defining elements.
- **Secondary (Soft Sage):** Used for accents, secondary buttons, and subtle highlights.
- **Neutral (Carbon):** A high-contrast dark gray used for text and iconography to ensure maximum legibility.
- **Surface (Cloud):** The primary background color, providing a soft, non-glare canvas for content.

## Typography

The system utilizes **Hanken Grotesk** as the primary typeface for its clean, technical, yet approachable character. Its sharp geometry aligns with the 'tech-forward' requirement. 

**JetBrains Mono** is introduced as a secondary label font to add a layer of "utility" and "data-precision," reinforcing the sense of professional reliability in technical or meta-information sections.

- **Scale:** Use dramatic scale differences between display text and body copy to create a clear visual hierarchy.
- **Readability:** Body text uses a slightly increased line-height (1.5x) to facilitate comfortable long-form reading on desktop screens.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop to maintain optimal line lengths and controlled compositions. 

- **Grid System:** A 12-column grid with 32px gutters. Elements should align strictly to these columns to evoke a sense of order and engineering.
- **Whitespace:** Use a "Macro-over-Micro" approach. Generous gaps (120px+) between major sections distinguish the marketing site from dense dashboard interfaces.
- **Rhythm:** All vertical spacing must be a multiple of the 8px base unit.

## Elevation & Depth

To maintain a minimalist aesthetic, the system avoids heavy shadows. Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Tiers:** Use subtle shifts in background color (e.g., Cloud to White) to denote container priority.
- **Shadows:** Only used for interactive floating elements (modals, dropdowns). These should be extra-diffused: `0px 12px 32px rgba(0, 0, 0, 0.05)`.
- **Borders:** 1px solid strokes in a light sage-gray (#E0E7E1) are used for card containers to provide structure without adding visual weight.

## Shapes

The shape language is **Rounded**, using a 0.5rem (8px) base radius. This softens the technical precision of the typography and grid, making the brand feel more accessible and "modern-humanist."

- **Interactive Elements:** Buttons and input fields follow the base 8px radius.
- **Large Containers:** Hero images and large feature cards utilize `rounded-xl` (24px) to create a soft, framed look.
- **Icons:** Should be monolinear with rounded caps to match the UI's geometry.

## Components

### Buttons
Primary buttons are solid Sage Green with White text. Hover states should transition to a slightly darker shade. Secondary buttons use a ghost style with a 1px border.

### Cards
Cards are flat with 1px outlines. Padding inside cards should be generous (min 32px) to prevent data from feeling cramped.

### Input Fields
Inputs use a light gray fill (#F0F3F0) with a bottom-only border or subtle 1px frame. Focus states use a 2px Sage Green outline.

### Chips & Tags
Use soft-tinted backgrounds (Tertiary Green) with Dark Green text. These are pill-shaped to differentiate them from square-cornered buttons.

### Lists
Marketing lists should use custom Sage Green checkmarks rather than default bullets to reinforce brand identity in every detail.