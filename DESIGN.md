---
name: Liquid Portfolio
colors:
  surface: '#0e1322'
  surface-dim: '#0e1322'
  surface-bright: '#343949'
  surface-container-lowest: '#090e1c'
  surface-container-low: '#161b2b'
  surface-container: '#1a1f2f'
  surface-container-high: '#25293a'
  surface-container-highest: '#2f3445'
  on-surface: '#dee1f7'
  on-surface-variant: '#c5c6cb'
  inverse-surface: '#dee1f7'
  inverse-on-surface: '#2b3040'
  outline: '#8e9195'
  outline-variant: '#44474a'
  surface-tint: '#c1c7cf'
  primary: '#ffffff'
  on-primary: '#2b3137'
  primary-container: '#dde3eb'
  on-primary-container: '#5f656c'
  inverse-primary: '#595f66'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#ffffff'
  on-tertiary: '#213145'
  tertiary-container: '#d3e4fe'
  on-tertiary-container: '#56657c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde3eb'
  primary-fixed-dim: '#c1c7cf'
  on-primary-fixed: '#161c22'
  on-primary-fixed-variant: '#41474e'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#0e1322'
  on-background: '#dee1f7'
  surface-variant: '#2f3445'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.08em
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
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies a "Midnight & Pearl" aesthetic, moving away from utilitarian dark modes toward a high-end, editorial atmosphere. The personality is sophisticated, calm, and ethereal, catering to an audience that values exclusivity and refined craftsmanship.

The visual style is a blend of **Minimalism** and **Glassmorphism**, utilizing translucent silver-blue layers and deep, immersive voids to create a sense of infinite depth. The UI should feel like it is floating on a calm, nocturnal sea—fluid, quiet, and premium. There are no harsh neons; instead, we rely on pearlescent highlights and soft light-refraction effects to guide the eye.

## Colors
The palette is rooted in the interplay between deep shadows and soft light.
- **Primary (Pearl):** Used for primary typography and high-emphasis elements. It is an off-white that feels luminous against the dark background.
- **Neutral (Midnight):** The foundational base (#0A0F1E). This is a rich, saturated navy that provides more depth than standard black or charcoal.
- **Secondary (Deep Slate):** Used for structural elements and containers that need to recede.
- **Surface (Silver-Blue):** A mid-tone used for card backgrounds and elevated surfaces, creating the "liquid" feel through subtle blue undertones.
- **Accent (Lustre):** High-clarity white for interactive states and focus indicators.

## Typography
The typography creates a contrast between the historical elegance of **Playfair Display** and the modern, technical precision of **Manrope**. 

Headlines should be treated with generous leading and occasional italicization for emphasis, emphasizing the editorial nature of the system. Body text remains highly legible in silver-blue or off-white tones to reduce eye strain against the midnight background. Labels and small caps are used for navigation and metadata, often with increased letter spacing to enhance the premium feel.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a focus on asymmetrical balance and significant negative space. 
- **Desktop:** A 12-column grid with wide 64px margins to allow the content to "breathe" within the dark canvas.
- **Mobile:** A 4-column grid with 20px margins.
- **Philosophy:** Spacing is used to create "islands" of content. Avoid crowding elements; instead, use large padding (vertical rhythm) to distinguish sections, mimicking the flow of water. Elements should often overlap or use slight offsets to break the rigidity of the grid.

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layers** and **Glassmorphism**, not traditional shadows.
- **Base:** The Midnight background (#0A0F1E).
- **Level 1 (Surfaces):** Silver-blue containers with a subtle `backdrop-filter: blur(12px)` and low-opacity borders (10% Pearl white).
- **Level 2 (Floating):** Pearlescent elements that use a soft, inner glow rather than a drop shadow.
- **Interaction:** Hovering over an element should cause a subtle "luminance shift," where the surface becomes slightly more translucent or "wets" the color, making it appear closer to the light source.

## Shapes
The shape language is **Rounded**, reflecting the "liquid" theme. Hard corners are avoided to keep the interface feeling soft and organic.
- Buttons and input fields use a consistent 0.5rem (8px) radius.
- Large cards and featured containers use 1rem (16px) or 1.5rem (24px) for a more pill-like, approachable appearance.
- Icons should feature rounded caps and joins to match the soft geometry of the UI.

## Components
- **Buttons:** Primary buttons are Pearlescent (#E2E8F0) with dark text (#0A0F1E). Secondary buttons use a ghost style with a 1px silver-blue border.
- **Cards:** Backgrounds use the Silver-Blue surface color at 60% opacity with a blur effect. Border-top should have a subtle 1px "highlight" line to simulate light catching the edge of a glass surface.
- **Inputs:** Minimalist fields with only a bottom border in inactive states, expanding to a full Silver-Blue enclosure when focused. 
- **Chips/Badges:** Small, pill-shaped elements with low-contrast backgrounds and high-contrast text for metadata.
- **Navigation:** A floating header with a heavy backdrop blur, creating a glass-like shelf for the typography to sit upon.
- **Lists:** Separated by thin, low-opacity silver-blue dividers that don't reach the edges of the container, maintaining the fluid feel.