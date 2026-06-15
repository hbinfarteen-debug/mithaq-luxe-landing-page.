---
name: Metropolitan
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c8c6c5'
  primary: '#c8c6c5'
  on-primary: '#313030'
  primary-container: '#121212'
  on-primary-container: '#7e7d7d'
  inverse-primary: '#5f5e5e'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#d8c3b3'
  on-tertiary: '#3b2e23'
  tertiary-container: '#1a1007'
  on-tertiary-container: '#8c7a6c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#f5dece'
  tertiary-fixed-dim: '#d8c3b3'
  on-tertiary-fixed: '#25190f'
  on-tertiary-fixed-variant: '#534438'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style
The design system embodies the essence of an ultra-luxury urban apothecary. It is built for a target audience that values heritage and modern craftsmanship, evoking a sense of calm, exclusivity, and cultural depth. 

The style is **Minimalist** with **Atmospheric** influences. It prioritizes heavy whitespace (or "darkspace") to let the product photography speak. Every element is intentional, avoiding unnecessary decoration to mirror the purity of high-end scented oils. The UI should feel like stepping into a dimly lit, quiet boutique in a cosmopolitan capital—structured, sophisticated, and deeply immersive.

## Colors
The palette is rooted in a "Noir-Luxury" spectrum. The default state is **Dark**, utilizing deep charcoals to create an atmospheric backdrop that allows gold and clay tones to glow.

- **Primary (Deep Charcoal):** Used for the core canvas and deep backgrounds to provide an expensive, infinite feel.
- **Secondary (Warm Gold):** Reserved for high-value interactions, brand accents, and premium call-to-outs.
- **Tertiary (Muted Clay):** Used for secondary text and structural elements to soften the interface and provide a tactile, organic feel.
- **Accents:** Amber and Bloom are used sparingly as emotional triggers, representing the olfactory notes of the scents themselves.

## Typography
The typography system relies on a high-contrast tension between the classical and the contemporary.

**Headlines** utilize a high-contrast serif to convey authority, history, and elegance. Large display sizes should use tighter letter spacing to emphasize the dramatic strokes of the letterforms.

**Body text** uses a sharp, clean sans-serif. This provides a functional, modern balance to the serif, ensuring high readability and a "technical" precision that mirrors the chemistry of scent blending. Use `label-caps` for navigation and small metadata to maintain an organized, boutique-like hierarchy.

## Layout & Spacing
This design system employs a **Fixed Grid** model for desktop to ensure the visual composition remains as curated as a print editorial.

- **Desktop:** A 12-column grid with wide 64px margins. Elements should often span 6 or 8 columns to leave ample "negative space" for atmosphere.
- **Mobile:** A 4-column grid with 20px margins. 
- **Rhythm:** Vertical spacing is aggressive. Large gaps (Section Gaps) are used to separate product stories, preventing the UI from feeling cluttered or "commercial." Use the `stack` units for internal component spacing to maintain a tight, professional density.

## Elevation & Depth
Depth is achieved through **Tonal Layering** and **Atmospheric Blurs** rather than traditional drop shadows.

- **Surface Tiers:** Backgrounds are the darkest charcoal. Secondary containers (like cards or menus) use a slightly lighter charcoal (#1E1E1E) with a subtle 1px border in Muted Clay at 10% opacity.
- **Glassmorphism:** Overlays, such as navigation bars and modal backdrops, use a heavy backdrop blur (20px) with a semi-transparent dark tint. This creates a "smoked glass" effect.
- **Inner Glows:** For primary buttons or active states, a very soft, low-opacity Gold outer glow can be used to simulate the warmth of a candle or a spotlight on a product.

## Shapes
The shape language is primarily **Structured and Sharp**. We use a very subtle `0.25rem` (Soft) radius for primary UI elements to prevent the design from feeling overly aggressive or industrial. 

Product containers and images should remain perfectly sharp (0px) to mimic high-end architectural lines and luxury packaging. Circular elements are permitted only for scent profiles or interactive "swatches" to represent the fluid nature of oil.

## Components
- **Buttons:** Primary buttons are either solid Warm Gold with black text or "Ghost" style with a Muted Clay 1px border. Always use `label-caps` for button text.
- **Cards:** Cards should have no background fill by default, using only 1px subtle borders or distinct spacing to separate content. When hovered, they may transition to a slightly lighter charcoal background.
- **Input Fields:** Use "Line" style inputs—a single 1px border at the bottom. The label should float above in a small `label-caps` style. 
- **Chips/Labels:** Small, rectangular tags with no roundedness, using the Muted Clay or Accent colors with 10% opacity fills.
- **Lists:** High vertical padding (24px+) between list items with a hairline divider (1px, low opacity) to maintain an airy, premium feel.
- **Interactive Accents:** Hovering over a scent product should trigger a subtle transition where the Warm Gold or Bloom accent color bleeds into the borders or typography.