---
name: Fiscal Precision
colors:
  surface: '#f8f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#454652'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#1b6d24'
  on-secondary: '#ffffff'
  secondary-container: '#a0f399'
  on-secondary-container: '#217128'
  tertiary: '#400003'
  on-tertiary: '#ffffff'
  tertiary-container: '#670007'
  on-tertiary-container: '#ff635a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#a3f69c'
  secondary-fixed-dim: '#88d982'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#005312'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ac'
  on-tertiary-fixed: '#410003'
  on-tertiary-fixed-variant: '#93000e'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  mono-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is engineered for a professional, data-centric investment platform that balances institutional authority with consumer-grade accessibility. The target audience includes both novice investors seeking guidance and seasoned traders requiring clarity.

The aesthetic follows a **Corporate / Modern** style, characterized by a structured layout, purposeful use of whitespace, and a high degree of legibility. The UI evokes a sense of stability and intelligence through a "Data-First" philosophy—where information hierarchy is primary, and decorative elements are secondary. Visual complexity is minimized to reduce cognitive load during financial decision-making, utilizing subtle tonal shifts rather than aggressive gradients or heavy shadows.

## Colors

The palette is anchored by **Deep Navy (#1A237E)**, used for primary actions, navigation, and core branding to establish trust and institutional weight. **Emerald Green (#2E7D32)** is reserved strictly for growth indicators, positive price action, and success states, providing a clear semantic signal of "gain." 

To maintain balance, a **Tertiary Crimson (#C62828)** is utilized for negative indicators and warnings. The background strategy relies on a multi-layered neutral system: a base white for primary content areas and a **Subtle Grey (#F5F7F9)** for the application background to create a "containerized" look for cards and modules.

## Typography

This design system utilizes **Inter** for all UI elements to ensure maximum legibility and a systematic, utilitarian feel. A secondary monospaced font, **JetBrains Mono**, is introduced specifically for stock tickers, price updates, and numerical data tables to ensure digits align perfectly and remain readable at small sizes.

Headlines use tighter letter-spacing and heavier weights to command attention, while body text maintains standard tracking for long-form market analysis. Labels are frequently uppercased with slight tracking to differentiate them from interactive body text.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop (12 columns) and a fluid 4-column model for mobile. It employs a strict 8px spacing scale to maintain mathematical harmony.

- **Desktop:** 1200px max-width container, centered, with 24px gutters.
- **Mobile:** Full-width with 16px side margins.
- **Rhythm:** Generous padding within cards (minimum 24px) ensures that data-heavy content does not feel cramped. Vertical rhythm is driven by the `lg` (24px) unit between major sections and the `md` (16px) unit between related components.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** rather than heavy shadows. The background is a flat neutral grey, while cards and interactive surfaces are pure white. 

To indicate elevation or focus, a singular, highly-diffused ambient shadow is used (e.g., 0px 4px 20px rgba(0, 0, 0, 0.05)). This "Soft Lift" effect helps users distinguish between the background and actionable modules without the visual noise of traditional skeuomorphism. Thin, low-contrast borders (#E0E4E8) are used on all cards to define boundaries in light mode.

## Shapes

The design system utilizes a **Soft** shape language. This 4px base radius (0.25rem) reflects the professional nature of finance—it is friendlier than sharp corners but remains disciplined and precise. Larger components like main content cards or search inputs use `rounded-lg` (8px) to soften the overall appearance of the dashboard.

## Components

- **Buttons:** Primary buttons use Deep Navy with white text. Success actions (e.g., "Buy") use Emerald Green. All buttons have a subtle 1px inset border to maintain structure.
- **Stock Price Charts:** Sparklines should use a 2px stroke width. Colors are strictly semantic: Emerald Green for positive trends and Tertiary Crimson for negative trends. Background fills under lines should be a 5% opacity gradient of the stroke color.
- **News Cards:** Use a horizontal layout for desktop and vertical for mobile. Headlines are Title-LG, with a 12px gap between the image and text content.
- **Progress Bars:** Used for portfolio diversification and goal tracking. The track color should be a light neutral grey, with the indicator in Primary Navy or Semantic Green.
- **Input Fields:** Search bars should be `rounded-lg` with a "magnifying glass" icon at the start and a subtle background tint (#F0F2F5) that clears on focus to pure white with a 2px Navy border.
- **Chips/Badges:** Small, rounded pill shapes used for stock sectors or "Trending" tags. Use low-saturation background tints (e.g., 10% opacity of the label color) to keep them secondary.