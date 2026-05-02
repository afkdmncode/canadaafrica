---
name: Compassion & Impact
colors:
  surface: '#fff8f4'
  surface-dim: '#e1d8d2'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2eb'
  surface-container: '#f5ece5'
  surface-container-high: '#f0e7df'
  surface-container-highest: '#eae1da'
  on-surface: '#1f1b17'
  on-surface-variant: '#5c403c'
  inverse-surface: '#34302b'
  inverse-on-surface: '#f8efe8'
  outline: '#916f6b'
  outline-variant: '#e5bdb8'
  surface-tint: '#bd0f16'
  primary: '#b0000f'
  on-primary: '#ffffff'
  primary-container: '#d52624'
  on-primary-container: '#ffefed'
  inverse-primary: '#ffb4ab'
  secondary: '#a03f30'
  on-secondary: '#ffffff'
  secondary-container: '#fe8672'
  on-secondary-container: '#741f13'
  tertiary: '#4c5c16'
  on-tertiary: '#ffffff'
  tertiary-container: '#64752d'
  on-tertiary-container: '#e6fba3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000a'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a7'
  on-secondary-fixed: '#400200'
  on-secondary-fixed-variant: '#80281b'
  tertiary-fixed: '#d7ec95'
  tertiary-fixed-dim: '#bbcf7c'
  on-tertiary-fixed: '#161e00'
  on-tertiary-fixed-variant: '#3d4c05'
  background: '#fff8f4'
  on-background: '#1f1b17'
  surface-variant: '#eae1da'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is anchored in the concept of "The Human Bridge"—the connection between Canadian generosity and African community resilience. The brand personality is authoritative yet deeply empathetic, balancing the structural stability of an international NGO with the organic warmth of the communities it serves. 

This design system utilizes a **Corporate / Modern** aesthetic with a strong **Minimalist** influence. By prioritizing clarity and high-quality photography, the UI steps back to let human stories take center stage. The style avoids trendy gimmicks in favor of a "grounded" feel, ensuring that stakeholders—from government donors to local field partners—perceive the organization as both professional and accessible.

## Colors

The palette creates a visual dialogue between two geographies. The **Canadian Red** acts as the primary action color, signaling urgency, passion, and national identity. This is tempered by the secondary **Terracotta** and **Olive**, which represent the earth and growth of the African landscape.

To ensure warmth and accessibility, pure black is avoided. Instead, a deep **Warm Gray** is used for text to maintain high contrast without the clinical coldness of a digital black. The **Cream** background replaces pure white in content-heavy areas to reduce eye strain and provide a "paper-like" tactile quality that feels more human-centric.

## Typography

The typography strategy focuses on "Institutional Clarity." **Inter** is selected for headlines due to its modern, systematic construction which conveys technical proficiency and modern scale. 

For body copy, **Public Sans** provides an institutional but friendly tone. Its origins in government and public sector design make it exceptionally legible for diverse audiences, including those with accessibility needs or those reading on lower-resolution devices in the field. Large line heights (1.6) are mandated for body text to ensure a comfortable, open reading experience that supports long-form storytelling.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to maintain a professional, editorial structure that mirrors high-end print journalism. The layout is centered with a maximum width of 1280px, utilizing a 12-column grid.

Large vertical spacing (`xl`) is used between major sections to provide the "whitespace" required for a grounded, calm user experience. Gutters are kept wide to ensure that content never feels cramped, allowing the high-quality photography to breathe. On mobile, the system transitions to a fluid 4-column grid with 16px side margins.

## Elevation & Depth

To maintain a grounded and professional feel, this design system avoids excessive layering. Depth is primarily communicated through **Tonal Layers** and **Ambient Shadows**.

- **Surfaces:** Cards and containers typically sit on the Cream background using a flat White fill to create a subtle natural lift.
- **Shadows:** When used, shadows must be extremely soft and diffused, using a hint of the neutral warm gray in the shadow tint rather than pure black. This creates an "organic" lift that feels like natural sunlight rather than a digital glow.
- **Outlines:** Low-contrast outlines in a slightly darker cream or terracotta are preferred over shadows for input fields and secondary containers to maintain a clean, professional profile.

## Shapes

The shape language is defined as **Rounded**. A standard radius of 0.5rem (8px) is applied to all primary UI elements. This specific level of roundedness is chosen to strike a balance: it is soft enough to feel approachable and "human-centric," yet sharp enough to retain the "professional" and "trustworthy" requirements of a serious NGO. Elements like tags or "Donate" buttons may occasionally use pill-shapes to draw additional attention, but the structural core of the UI remains consistently rounded.

## Components

### Buttons
Primary buttons use the "Canadian Red" with white text, featuring a subtle 8px corner radius. Hover states should transition to a slightly deeper shade of red. Secondary buttons use the Olive or Terracotta with a ghost-style (outline) treatment to maintain hierarchy.

### Cards
Cards are the primary container for community stories and impact reports. They utilize a white background, the standard 8px radius, and a very light ambient shadow. Images within cards should always be top-aligned and bleed to the edges.

### Input Fields
Inputs should have a warm-gray border (1px) and a subtle cream background fill. Upon focus, the border shifts to the primary Red or Terracotta to provide clear feedback.

### Photography & Overlays
This design system relies on "Human-Centric" imagery. Text overlays on images should use a subtle "Terracotta" or "Neutral" semi-transparent scrim (gradient) to ensure legibility without obscuring the subject's face or environment.

### Progress Bars (Impact)
Used for fundraising or project milestones, these should use the Olive color to represent growth, set against a light warm-gray track.