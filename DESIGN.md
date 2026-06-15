---
name: Munira Mehandhi Design System
colors:
  surface: '#fefccf'
  surface-dim: '#dedcb1'
  surface-bright: '#fefccf'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f6c9'
  surface-container: '#f2f0c4'
  surface-container-high: '#eceabe'
  surface-container-highest: '#e6e5b9'
  on-surface: '#1d1d03'
  on-surface-variant: '#414844'
  inverse-surface: '#323214'
  inverse-on-surface: '#f5f3c7'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#37201b'
  on-tertiary: '#ffffff'
  tertiary-container: '#4f352f'
  on-tertiary-container: '#c29e96'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#e5beb5'
  on-tertiary-fixed: '#2b1611'
  on-tertiary-fixed-variant: '#5c403a'
  background: '#fefccf'
  on-background: '#1d1d03'
  surface-variant: '#e6e5b9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
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
  base: 8px
  container-padding-mobile: 20px
  container-padding-desktop: 64px
  gutter: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
This design system embodies the intersection of ancient artistry and modern luxury. It is designed for a premium beauty audience that values the cultural heritage of Mehandi but expects a sophisticated, clean, and high-end shopping experience. 

The aesthetic is **Modern Elegance** with a **Tactile** influence. It utilizes heavy whitespace to allow the rich color palette to breathe, creating a sense of calm and exclusivity. Subtle, low-opacity floral Mehandi patterns are used as structural elements or background watermarks rather than decorative clutter, ensuring the product photography remains the focal point. The emotional response should be one of trust, indulgence, and traditional warmth.

## Colors
The palette is rooted in the natural lifecycle of henna.
- **Deep Forest Green (#1B4332):** Used for primary surfaces, headers, and primary buttons to convey premium quality and organic roots.
- **Shimmering Gold (#D4AF37):** Reserved for accents, borders of high-importance elements, and iconography to denote the "premium" tier.
- **Soft Cream (#FFFDD0):** The primary background color. It provides a warmer, more inviting canvas than pure white, reducing eye strain and feeling more "editorial."
- **Rich Henna Brown (#4E342E):** Used primarily for typography and secondary decorative elements to ground the design in the product's physical color.
- **WhatsApp Green (#25D366):** A functional accent color used exclusively for the primary conversion path (direct ordering).

## Typography
The typography system uses a high-contrast pairing to reflect the brand's "Modern Traditional" ethos. 
- **Headlines:** Playfair Display provides an authoritative, editorial feel. Use "display-lg" for hero sections with tight letter spacing.
- **Body:** Montserrat ensures high legibility on mobile devices. Use "body-md" for general descriptions and "body-lg" for introductory paragraphs.
- **Labels:** Small caps or uppercase Montserrat should be used for category labels and buttons to provide a clean, architectural counterpoint to the fluid serif headlines.

## Layout & Spacing
The layout follows a **mobile-first fluid grid**. 
- **Mobile:** A 4-column grid with 20px side margins. Content blocks are stacked vertically to prioritize thumb-reach and clarity.
- **Desktop:** A 12-column fixed grid (max-width 1280px) with 64px side margins. 
- **Rhythm:** An 8px base unit governs all spatial relationships. Use "stack-lg" (48px) to separate major sections to maintain a high-end, airy feel.

## Elevation & Depth
Depth is achieved through **Ambient Shadows** and **Tonal Layering**. 
- **Surfaces:** Most cards sit on the Soft Cream background with a very subtle, diffused shadow (Blur: 20px, Y: 4px, Color: #1B4332 at 5% opacity). This creates a "lifted" effect without looking heavy.
- **Patterns:** Subtle Mehandi patterns should be applied at 3-5% opacity on the Cream background or 10% on the Forest Green background to create texture without competing with content.
- **Modals:** Use a heavy backdrop blur (12px) to maintain focus when displaying product details or "Order Now" prompts.

## Shapes
The design system uses a consistent **Rounded** language to mimic the organic flow of Mehandi art.
- **Standard Elements:** 16px (1rem) corner radius for cards and input fields.
- **Buttons:** Fully pill-shaped or 16px radius depending on the visual weight required.
- **Images:** Always clipped with a minimum of 16px radius to maintain the soft, premium aesthetic.

## Components
- **Primary Buttons:** Forest Green background with Cream text. 16px rounded corners. High-emphasis.
- **WhatsApp CTA:** Use the official WhatsApp Green (#25D366) with a white icon and text. This should be a floating action button (FAB) on mobile or a prominent sticky button on product pages.
- **Product Cards:** Cream surface with a 1px border in Shimmering Gold or a soft ambient shadow. Product titles in Playfair Display.
- **Input Fields:** Soft Cream background with a Forest Green 1px border on focus. Labels in Montserrat (label-md).
- **Chips/Categories:** Pill-shaped with a Forest Green outline for unselected and solid Forest Green for selected states.
- **Floral Accents:** Use SVG Mehandi patterns as decorative "corners" for section headers or as a watermark behind the main product image.