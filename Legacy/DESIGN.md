---
name: Serene Journey
colors:
  surface: '#fdf9f0'
  surface-dim: '#dddad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f1eee5'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c16'
  on-surface-variant: '#414847'
  inverse-surface: '#31302b'
  inverse-on-surface: '#f4f0e7'
  outline: '#717977'
  outline-variant: '#c0c8c6'
  surface-tint: '#3f6560'
  primary: '#002924'
  on-primary: '#ffffff'
  primary-container: '#173f3a'
  on-primary-container: '#82aaa3'
  inverse-primary: '#a6cfc7'
  secondary: '#904b32'
  on-secondary: '#ffffff'
  secondary-container: '#fea586'
  on-secondary-container: '#783921'
  tertiary: '#0f2815'
  on-tertiary: '#ffffff'
  tertiary-container: '#253e29'
  on-tertiary-container: '#8ca98e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ebe3'
  primary-fixed-dim: '#a6cfc7'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#264d48'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59b'
  on-secondary-fixed: '#380d00'
  on-secondary-fixed-variant: '#73351d'
  tertiary-fixed: '#cceacc'
  tertiary-fixed-dim: '#b0ceb1'
  on-tertiary-fixed: '#07200e'
  on-tertiary-fixed-variant: '#334d37'
  background: '#fdf9f0'
  on-background: '#1c1c16'
  surface-variant: '#e6e2d9'
typography:
  display-lg:
    fontFamily: DM Serif Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: DM Serif Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
  headline-lg:
    fontFamily: DM Serif Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: DM Serif Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: DM Serif Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-padding-desktop: 80px
  container-padding-mobile: 24px
  gutter: 32px
  section-gap: 120px
  stack-gap: 24px
---

## Brand & Style
The design system embodies a premium editorial aesthetic tailored for high-end travel experiences. It draws inspiration from **Minimalism** and **Glassmorphism**, focusing on immersive storytelling through generous whitespace and sophisticated depth. The emotional response is one of tranquility, exclusivity, and local warmth, grounded in the scenic beauty of Coimbatore.

The visual language is defined by the "Journey Frame" concept—where structured content panels float gracefully over expansive, high-resolution travel photography. This creates a window-like effect, inviting the user to explore destinations through a refined, curated lens.

## Colors
The palette is rooted in organic, earthy tones that reflect the natural landscapes of Southern India. 

- **Primary Background (Warm Ivory):** Used for large surfaces to provide a soft, non-clinical feel.
- **Secondary Background (Soft Sand):** Used for subtle section nesting or secondary containers.
- **Deep Forest:** The primary anchor for all high-contrast typography and essential brand markers.
- **Muted Terracotta:** Reserved for calls to action, highlights, and subtle navigational cues.
- **Environmental Accents:** Natural Green and Sky Accent are used sparingly in iconography, status indicators, or decorative graphical elements to evoke outdoor themes.

## Typography
The typographic hierarchy relies on the interplay between the classic, high-contrast **DM Serif Display** for storytelling and the functional, clean **Manrope** for utility.

- **Editorial Flourish:** Use Display styles for destination names and inspirational quotes. Ensure ample line height to maintain a premium, "breathable" feel.
- **Readability:** Body text should maintain a generous leading (1.5x) to ensure long-form travel itineraries are comfortable to read.
- **Functional Labels:** Captions and labels use Manrope with increased letter spacing and semi-bold weights to contrast against the more fluid serif headings.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy with an emphasis on asymmetric editorial compositions. 

- **The Editorial Grid:** On desktop, utilize a 12-column grid with wide gutters (32px). Content should often be offset—for example, a headline spanning 6 columns on the left, with body text occupying 4 columns on the right—to create visual interest.
- **Journey Frames:** Content modules are wrapped in large-radius containers that use "Safe Margins" (at least 80px from page edges on desktop) to floating over background imagery.
- **Breakpoints:**
  - **Desktop (1280px+):** Full editorial layout with 80px margins.
  - **Tablet (768px - 1279px):** Content reflows to 8 columns; margins reduce to 40px.
  - **Mobile (Under 767px):** Single column stack; margins reduce to 24px; typography scales down to mobile-specific tokens.

## Elevation & Depth
The "Journey Frame" concept is achieved through a mix of **Glassmorphism** and **Ambient Shadows**.

- **Surface Layers:** The primary interface uses a tiered approach. Level 0 is the immersive image or Ivory background. Level 1 is the content frame, often utilizing a subtle backdrop blur (12px) and 5% opacity Soft Sand tint when overlaying images.
- **Shadow Profile:** Shadows are extremely diffused (e.g., `box-shadow: 0 20px 40px rgba(24, 48, 45, 0.05)`). They should feel like a soft glow rather than a harsh drop-shadow.
- **Glass Effects:** Use semi-transparent white (10-20% opacity) with a background blur for navigation bars and secondary overlays to maintain a sense of lightness.

## Shapes
The shape language is characterized by organic, sweeping curves that evoke comfort and fluidity.

- **Main Containers:** Content cards and "Journey Frames" use a custom `rounded-3xl` (24px to 36px) to stand out from standard UI patterns.
- **Buttons & Inputs:** Follow the `rounded-lg` (16px) standard to maintain consistency with the larger containers while remaining functional.
- **Interactive Elements:** Small UI elements like chips or tags use a full pill-shape to distinguish them from structural components.

## Components
- **Buttons:**
  - *Primary:* Deep Forest background, Ivory text. No border. High-padding (16px 32px).
  - *Secondary:* Ghost style with a 1px Muted Terracotta border and Terracotta text.
- **Journey Cards:** Feature an image with a 24px border radius. Text is housed in a floating Glassmorphic panel at the bottom of the card or positioned asymmetrically to the side.
- **Input Fields:** Soft Sand background with a bottom-only 1px border in Deep Forest. This mimics high-end stationery.
- **Chips:** Pill-shaped with a light tint of Natural Green or Sky Accent. Used for categorizing tours (e.g., "Eco-Tour," "Luxury").
- **Lists:** Use custom icons—minimalist line art of local Coimbatore landmarks or flora—instead of standard bullets to reinforce the "Locally Grounded" brand pillar.
- **Itinerary Timeline:** A vertical line in Muted Terracotta with soft-edged dots marking travel milestones, providing a clear but elegant path through a journey.