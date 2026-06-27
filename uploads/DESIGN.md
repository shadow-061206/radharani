---
name: Divine Elegance
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4d4635'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#8f4e00'
  on-secondary: '#ffffff'
  secondary-container: '#fe9832'
  on-secondary-container: '#683700'
  tertiary: '#5f5f59'
  on-tertiary: '#ffffff'
  tertiary-container: '#b4b3ac'
  on-tertiary-container: '#454540'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#ffb77a'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#6d3a00'
  tertiary-fixed: '#e4e3db'
  tertiary-fixed-dim: '#c8c7bf'
  on-tertiary-fixed: '#1b1c17'
  on-tertiary-fixed-variant: '#474742'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in a philosophy of **Sacred Minimalism**. It serves a discerning audience seeking spiritual connection through premium Radha Krishna products. The aesthetic prioritizes reverence and tranquility over commercial urgency, utilizing expansive whitespace to allow products to breathe like artifacts in a curated gallery.

The style merges **Modern Minimalism** with **Traditional Warmth**. It avoids the clutter often associated with spiritual marketplaces, opting instead for a refined, high-end editorial feel. Visual interest is maintained through high-quality photography and subtle, micro-textured backgrounds that evoke the feel of handmade paper or weathered gold leaf. The emotional response is one of immediate calm, respect, and enduring quality.

## Colors

The palette is a harmonic balance of sacred earth tones and metallic light:

*   **Primary (Soft Gold - #D4AF37):** Used for iconography, active states, and subtle accents. It represents divinity and light.
*   **Secondary (Saffron - #FF9933):** Used sparingly as a "soul" color—ideal for primary call-to-actions or significant spiritual markers.
*   **Tertiary (Cream - #FFFDF5):** The foundation of the UI. It replaces pure white to provide a warmer, more organic, and premium feel.
*   **Neutral (Deep Charcoal - #2C2C2C):** Used for all primary text and structural borders to ensure high legibility and a grounded, authoritative presence.

Backgrounds should primarily use the Tertiary Cream, with occasional sections in a desaturated "Antique Bone" to define content blocks.

## Typography

Typography in the design system follows a classic editorial hierarchy. 

**Libre Caslon Text** is used for all headlines and display text. Its traditional serifs and high legibility evoke a sense of history and timelessness. For large display sizes, a slightly tighter letter spacing is recommended to emphasize its elegant character.

**Plus Jakarta Sans** provides a soft, contemporary contrast for body copy and UI elements. Its open counters and friendly curves ensure the system doesn't feel overly stiff or archaic. Labels and navigation items should utilize the Medium or SemiBold weights in uppercase with increased letter spacing to create a distinct functional hierarchy.

## Layout & Spacing

The layout philosophy is a **Fixed, Centered Grid** for desktop and a **Fluid Margin Grid** for mobile. 

A 12-column system is used with generous gutters (24px) to prevent visual crowding. Vertical rhythm is governed by an 8px base unit, but significant "breathing room" is mandated between major sections (up to 120px) to maintain a feeling of luxury and calm. 

Content should be balanced and symmetrical. Asymmetric layouts may be used for editorial features or "Story of the Product" sections, but the primary shopping experience remains structured and predictable.

## Elevation & Depth

This design system eschews heavy shadows in favor of **Tonal Layers** and **Soft Depth**. 

*   **Tiers:** The background is always the Tertiary Cream (#FFFDF5). Higher-level containers (like product cards or modals) should use a pure white background or a very subtle 1px border in a desaturated gold.
*   **Shadows:** When necessary for functional depth (e.g., active dropdowns or floating cart buttons), use a "Golden Halo" shadow: a very low-opacity (#D4AF37 at 10%), highly diffused (20px-40px blur) shadow that feels more like a glow than a drop shadow.
*   **Lines:** Use hairline-thin (0.5px or 1px) dividers in Deep Charcoal at 10% opacity to separate content without creating visual noise.

## Shapes

Shapes in the design system are **Soft** and restrained. 

While the system uses a 0.25rem (4px) base corner radius for buttons and input fields to feel approachable, product imagery should strictly remain sharp-edged (0px) to mirror the precision of fine art photography. 

Decorative elements, such as image overlays or "About Us" sections, may occasionally use arched top borders (Gothic or Indian architectural influences) to subtly reference the spiritual nature of the products without becoming a caricature.

## Components

*   **Buttons:** Primary buttons use a solid Saffron (#FF9933) background with Deep Charcoal text for high contrast. Secondary buttons are outlined in Gold (#D4AF37) with a slight "ghost" hover effect.
*   **Cards:** Product cards are borderless with generous internal padding. Product names use the Serif font, while prices use the Sans-serif font for clarity.
*   **Inputs:** Form fields are minimalist—bottom-only borders in Deep Charcoal are preferred over full boxes to maintain a clean, airy aesthetic.
*   **Chips/Tags:** Used for product categories (e.g., "Eco-Friendly," "Handcrafted"). These should have a Cream background and a thin Gold border, using the `label-md` typography.
*   **Traditional Accents:** A signature component of this system is the "Divider Motif"—a thin line with a small, stylized lotus or geometric gold dot in the center, used to separate major narrative sections on product pages.
*   **Lists:** Navigation lists and footer links use Plus Jakarta Sans with generous line height and no bullet points, relying on whitespace for separation.