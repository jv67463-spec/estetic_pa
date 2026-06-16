---
name: Automation Excellence System
colors:
  surface: '#fbf9fc'
  surface-dim: '#dbd9dc'
  surface-bright: '#fbf9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f6'
  surface-container: '#efedf0'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e5'
  on-surface: '#1b1b1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#303033'
  inverse-on-surface: '#f2f0f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#4b5f81'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#041b3a'
  on-primary-container: '#7184a9'
  inverse-primary: '#b3c7ef'
  secondary: '#785a00'
  on-secondary: '#ffffff'
  secondary-container: '#fdc002'
  on-secondary-container: '#6c5000'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a40'
  on-tertiary-container: '#6584bf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b3c7ef'
  on-primary-fixed: '#041b3a'
  on-primary-fixed-variant: '#344768'
  secondary-fixed: '#ffdf9d'
  secondary-fixed-dim: '#f9bd00'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#acc7ff'
  on-tertiary-fixed: '#001a40'
  on-tertiary-fixed-variant: '#25467e'
  background: '#fbf9fc'
  on-background: '#1b1b1e'
  surface-variant: '#e3e2e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered to position the product as the premier authority in automation for La Rioja. The brand personality is **Precise, Authoritative, and Visionary**. It targets high-end residential clients and industrial stakeholders who value reliability and technological sophistication.

The visual style is **Corporate Modern with a Tech-Premium edge**. It utilizes a structured layout, a restrained but high-impact color palette, and subtle elevation to create a sense of depth and quality. The aesthetic avoids unnecessary decoration, focusing instead on "functional elegance"—where every shadow and transition serves to guide the user through complex automation data or high-value service offerings.

## Colors

This design system utilizes a high-contrast palette to establish professional hierarchy. 

- **Deep Navy Blue (#001736)**: Used for primary branding, headings, and high-importance backgrounds. It communicates stability and industrial strength.
- **Warm Gold/Amber (#FDC003)**: A strategic accent used sparingly for calls-to-action, focus states, and highlighting key performance indicators. It provides a "premium" warmth against the cool tech tones.
- **Surface & Background**: A tiered grey-to-white system (#F8FAFC and #FFFFFF) provides a clean, airy canvas that prevents the dark primary color from feeling heavy.
- **Deep Blue Gradients**: Applied to large-scale components (like hero sections or primary cards) to add depth and a modern, "glowing" tech feel.

## Typography

The typography strategy pairs technical precision with universal readability. 

**Hanken Grotesk** is the voice of the brand. Its sharp, contemporary geometry is used for all headlines and display text to evoke a sense of modern engineering. Use "Bold" for primary headings and "Semi-Bold" for sub-headings to maintain clear information architecture.

**Inter** handles all functional text. Its high x-height and neutral character ensure that technical specifications and body copy remain legible across all device sizes. For labels and small UI hints, use the Medium or Semi-Bold weights with slight tracking (letter-spacing) to enhance clarity in dense interfaces.

## Layout & Spacing

The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is built on "Logical Grouping," utilizing a Bento-grid approach for dashboard and feature sections.

- **Bento Grids**: Use varying column spans (e.g., 4-col, 8-col) to create a rhythmic, tiled layout that organizes different types of information (images, charts, text) into a cohesive visual unit.
- **Vertical Rhythm**: Spacing follows a strict 8px base unit. Section margins should be generous (`stack-lg`) to allow the high-end imagery and technical data to breathe.
- **Safe Zones**: On mobile, use a 16px side margin. On desktop, content is centered within a 1280px container with 48px margins.

## Elevation & Depth

Depth is used to signify interactivity and hierarchy, moving away from flat design toward a more tactile, premium feel.

- **Surface Tiers**: The background uses `#F8FAFC`, while interactive containers and cards use `#FFFFFF`. 
- **Ambient Shadows**: Use extremely soft, large-radius shadows (e.g., `0 10px 30px rgba(0, 23, 54, 0.04)`). The shadow color is tinted with the Primary Navy to ensure it feels integrated into the environment rather than a generic grey.
- **Bento Borders**: Cards feature a subtle 1px border in a very light grey (`#E2E8F0`). On hover, this border may transition to a subtle Deep Blue or Gold to indicate focus.
- **Glassmorphism**: Use backdrop-blur effects (12px to 20px) for navigation bars and floating overlays to maintain context while focusing the user's attention.

## Shapes

The shape language is defined as **Rounded**, striking a balance between industrial rigidity and modern user-friendliness.

- **Standard Elements**: Buttons and input fields use a 0.5rem (8px) radius.
- **Container Elements**: Cards and larger layout blocks (Bento items) use `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px) for a softer, more premium look.
- **Interactive States**: Hover states on cards should include a subtle scale-up (e.g., 1.02x) to reinforce the tactile nature of the UI.

## Components

### Buttons
- **Primary**: Deep Navy background with White text. On hover: Scale 1.05 and a subtle "Gold Glow" (outer shadow using #FDC003 at low opacity).
- **Secondary**: Clear background with Deep Navy border. 
- **Action/CTA**: Warm Gold background with Deep Navy text for maximum visibility.

### Bento Cards
- Standard padding of 32px. Use high-contrast headers within cards. Apply a smooth transition (300ms ease-out) for all hover states.

### Inputs
- Minimalist style with a 1px border. Focus state: Border changes to Warm Gold with a 2px outer glow. Labels should be positioned above the input in `label-sm`.

### Accordions (FAQ/Specs)
- Use a "clean reveal" motion. The header should feature a Chevron that rotates 180 degrees. Background of the active panel should shift slightly to a very light tint of Navy to differentiate the content.

### Chips & Badges
- Used for status (e.g., "Active", "In Production"). Use pill-shaped (rounded-full) geometry with low-saturation backgrounds and high-saturation text.