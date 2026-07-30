---
name: Obsidian Reserve
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e1bebe'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a88989'
  outline-variant: '#594040'
  surface-tint: '#ffb3b3'
  primary: '#ffb3b3'
  on-primary: '#680015'
  primary-container: '#a6192e'
  on-primary-container: '#ffb7b7'
  inverse-primary: '#b42537'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#555454'
  on-tertiary-container: '#cbc8c8'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b3'
  on-primary-fixed: '#400009'
  on-primary-fixed-variant: '#920322'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0.02em
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
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
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
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is a study in quiet luxury and artisanal precision. It targets a discerning audience that values heritage, craftsmanship, and exclusivity. By leaning into a **Minimalist-Noir** aesthetic, the UI feels like a high-end gallery or a private members' lounge—restrained, confident, and timeless.

The emotional response should be one of "effortless authority." We achieve this through expansive negative space, high-contrast typography, and a deliberate lack of decorative flourishes. Every pixel serves a functional or structural purpose, reinforcing a sense of curated quality.

## Colors

This design system utilizes a "Deep-Ink" palette. The foundation is built on `#121212` for the primary background to ensure absolute depth, while `#1e1e1e` is used for surface containers to create subtle tectonic separation.

The signature **Deep Red (#a6192e)** is used sparingly but with high impact. It represents the "seal of quality"—reserved for primary actions, critical status indicators, and subtle branding accents. Text is rendered in pure white for headlines and a refined silver-grey for body copy to maintain a sophisticated hierarchy without causing eye strain.

## Typography

The typographic strategy pairs the intellectual, historical weight of **Libre Caslon Text** with the modern, technical precision of **Manrope**. 

Headlines should be treated as editorial elements; use large-scale serif type for storytelling and hero sections. For functional UI and body text, Manrope provides a clean, neutral balance that ensures high legibility in dark mode. Always favor generous line heights to prevent the dark background from making the text feel "crowded."

## Layout & Spacing

The design system employs a **Fixed Grid** philosophy on desktop to maintain an "editorial" feel, centering content within a 1280px container. On mobile, the layout transitions to a fluid 4-column system.

Spacing is governed by an 8px base unit. To achieve the "premium" aesthetic, use larger-than-standard vertical padding (e.g., 80px or 120px) between major sections to allow the content to breathe. Alignment should be rigorous; use a 12-column grid for desktop with 24px gutters to ensure mathematical harmony across all layouts.

## Elevation & Depth

In this dark-mode environment, we avoid traditional drop shadows which can feel muddy. Instead, we use **Tonal Layering** and **Subtle Outlines**.

1.  **Level 0 (Background):** #121212.
2.  **Level 1 (Cards/Surfaces):** #1e1e1e with a 1px solid border of #2a2a2a.
3.  **Level 2 (Modals/Popovers):** #262626 with a soft, 15% opacity white inner-glow on the top edge to simulate a subtle light source from above.

Depth is communicated through brightness: the closer an object is to the user, the slightly lighter its background hex becomes.

## Shapes

The shape language is architectural and structured. We use a **Soft (0.25rem)** corner radius for most UI components (buttons, input fields, cards). This slight rounding removes the harshness of a pure 0px edge while maintaining a professional, serious tone. Heavy rounding or pill shapes are strictly prohibited to avoid a "consumer-tech" or "playful" appearance.

## Components

### Buttons
Primary buttons use the Deep Red background with white text. Hover states should slightly darken the red. Secondary buttons are "Ghost" style: a 1px white border with no fill, transitioning to a subtle grey fill on hover.

### Input Fields
Inputs feature a dark background (#1a1a1a) and a bottom-border only, or a very subtle all-around border. The focus state uses a 1px Deep Red border. Labels should always use the `label-caps` typography style for a structured, formal look.

### Cards
Cards are containers for high-value content. Use #1e1e1e for the background. Do not use shadows; instead, use a 1px border of #2a2a2a. If a card is interactive, the border should change to the signature red upon hover.

### Lists & Dividers
Dividers are thin (1px) and low-contrast (#262626). List items should have generous vertical padding (16px+) to reinforce the artisanal, spacious feel.

### Selection Controls
Checkboxes and radio buttons use the Deep Red for their active states. The "off" state is a simple #333 grey outline, ensuring they remain unobtrusive when not selected.