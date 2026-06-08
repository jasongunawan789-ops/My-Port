---
name: Aether Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e9c176'
  primary: '#e9c176'
  on-primary: '#412d00'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#775a19'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c8c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#a7a5a5'
  on-tertiary-container: '#3b3b3b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
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
    lineHeight: '1.6'
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
  section-gap: 120px
  content-gap: 64px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style

The design system is rooted in the concept of **Atmospheric Depth**. It targets high-end creative professionals and luxury boutiques who value curation over clutter. The visual language balances the "Curated Silence" of heavy whitespace with the "Dramatic Impact" of high-contrast typography and metallic accents.

The aesthetic direction is a blend of **Modern Minimalism** and **Editorial Luxury**. It utilizes a deep, monochromatic foundation to allow portfolio work to act as the primary visual driver. The emotional response should be one of quiet confidence, technical mastery, and exclusivity.

## Colors

The palette is anchored by **Pure Black (#050505)** and **Jet Black (#0A0A0A)** to create a sense of infinite depth. 

- **Primary (Bronze Gold):** Used sparingly for key calls-to-action, highlights in typography, and active states. It represents the "premium" touchpoint.
- **Surface Tiers:** Backgrounds use the darkest values, while cards and containers utilize charcoal grays (#121212) to create subtle separation.
- **Typography Colors:** High-contrast white for headlines and a muted mid-gray for secondary copy to ensure the hierarchy is felt before it is read.

## Typography

This design system employs a high-contrast typographic pairing to evoke an editorial feel.

- **Headlines:** Uses *Playfair Display*. The serif nature provides a classical, sophisticated counterpoint to the dark digital environment. Use large scales and tight letter spacing for display text.
- **Body & UI:** Uses *Hanken Grotesk*. This sans-serif is chosen for its modern, clean geometry, ensuring maximum legibility on dark backgrounds where "haloing" can often occur with thinner fonts.
- **Hierarchy:** Dramatic size differences are encouraged. Labels should be small and tracked out (all-caps) to act as structural anchors within the layout.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model with generous internal breathing room.

- **Grid:** A 12-column grid for desktop with 24px gutters. Content is typically centered with wide margins to create a "gallery" effect.
- **Rhythm:** Spacing is oversized. Section transitions should have at least 120px of vertical clearance to maintain the premium, unhurried pace of the user experience.
- **Adaptive Rules:** On mobile, margins shrink to 20px, and the 12-column grid collapses to a 4-column structure. Typography scales aggressively downward to ensure headlines remain readable without excessive breaking.

## Elevation & Depth

Depth is achieved through **Tonal Layering** rather than traditional drop shadows.

- **Surface Levels:** The base layer is the darkest. Elements that sit "above" use slightly lighter charcoal fills.
- **Borders:** Instead of shadows, use 1px solid borders in a very low-contrast gray (#FFFFFF10) to define the edges of cards or sections.
- **Interaction:** Hover states on interactive elements should use a subtle glow effect or a transition to the primary gold color, rather than a vertical "lift."
- **Backdrop Blurs:** For navigation overlays, use a high-density background blur (20px+) with a 70% opacity charcoal fill to maintain context without visual noise.

## Shapes

The design system uses **Soft** shapes. 

While the overall layout feels architectural and rigid, a subtle 0.25rem (4px) corner radius is applied to cards, inputs, and buttons. This prevents the UI from feeling overly aggressive or "brutalist," maintaining the professional and polished tone required for a high-end portfolio. Interactive components like chips or tags can occasionally use a pill-shape for better visual distinction against rectangular imagery.

## Components

- **Buttons:**
    - *Primary:* Solid primary gold background with black text. No border.
    - *Secondary:* Transparent background with a 1px primary gold border.
    - *Style:* Rectangular with subtle 4px rounding. All-caps typography.
- **Cards:**
    - Work samples should be housed in borderless containers.
    - Title and category labels sit below the image, utilizing the `label-caps` style for categories.
    - Hover state: Images should subtly scale or dim to reveal a primary gold arrow or "View Project" label.
- **Inputs:**
    - Minimalist design: A single 1px bottom border in muted gray.
    - Focus state: The border color transitions to primary gold.
    - Placeholder text uses `text_secondary_hex`.
- **Navigation:**
    - Persistent top-bar with a blur effect. 
    - Links are mid-gray, turning white on hover. 
    - The "Contact" or "Hire" action is treated as a secondary button.
- **Chips/Badges:**
    - Small, low-contrast charcoal background with gray text. Used for skills or project tags to avoid distracting from the main visuals.