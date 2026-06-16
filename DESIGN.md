---
name: Serene Creative Studio
colors:
  surface: '#fff8ef'
  surface-dim: '#e1d9cb'
  surface-bright: '#fff8ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf3e4'
  surface-container: '#f5edde'
  surface-container-high: '#efe7d9'
  surface-container-highest: '#e9e2d3'
  on-surface: '#1e1b13'
  on-surface-variant: '#4f4448'
  inverse-surface: '#343026'
  inverse-on-surface: '#f8f0e1'
  outline: '#817478'
  outline-variant: '#d2c3c7'
  surface-tint: '#795465'
  primary: '#795465'
  on-primary: '#ffffff'
  primary-container: '#f8c8dc'
  on-primary-container: '#765162'
  inverse-primary: '#e9bacd'
  secondary: '#635d5f'
  on-secondary: '#ffffff'
  secondary-container: '#eae0e2'
  on-secondary-container: '#696365'
  tertiary: '#67587b'
  on-tertiary: '#ffffff'
  tertiary-container: '#e0cdf7'
  on-tertiary-container: '#645578'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8e7'
  primary-fixed-dim: '#e9bacd'
  on-primary-fixed: '#2e1221'
  on-primary-fixed-variant: '#5f3c4d'
  secondary-fixed: '#eae0e2'
  secondary-fixed-dim: '#cdc4c6'
  on-secondary-fixed: '#1f1a1c'
  on-secondary-fixed-variant: '#4b4547'
  tertiary-fixed: '#eddcff'
  tertiary-fixed-dim: '#d1bfe8'
  on-tertiary-fixed: '#221534'
  on-tertiary-fixed-variant: '#4e4062'
  background: '#fff8ef'
  on-background: '#1e1b13'
  surface-variant: '#e9e2d3'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-xl: 120px
  stack-lg: 64px
  stack-md: 32px
  stack-sm: 16px
---

## Brand & Style
The design system is engineered to evoke a sense of professional calm, creative precision, and approachable elegance. Targeting small business owners and creative entrepreneurs, the brand personality is "The Sophisticated Partner"—someone who is organized, aesthetically gifted, and highly reliable.

The visual style blends **Soft Minimalism** with **Glassmorphism**. It prioritizes heavy whitespace to allow design work to breathe, while using a palette of warm pastels to create an inviting, feminine atmosphere. The interface should feel light and airy, avoiding heavy containers in favor of tonal layering and soft depth.

## Colors
The palette is rooted in high-chroma softness. 
- **Primary (Pastel Pink):** Used for key actions and brand identifiers.
- **Secondary (Soft Blush):** Primarily for section backgrounds to break up pure white spaces.
- **Accent (Soft Lavender):** Reserved for highlights, badges, and creative flair to distinguish graphic design services from administrative ones.
- **Neutral (Cream/Beige):** Used for subtle UI elements like input backgrounds or secondary containers.
- **Text:** A softened charcoal (#4A4A4A) is used instead of pure black to maintain the gentle aesthetic while ensuring high readability.

## Typography
This design system utilizes **Plus Jakarta Sans** for headings to provide a modern, friendly, and slightly geometric personality. **Inter** is used for body copy and UI labels to ensure maximum legibility and a professional, systematic feel. 

Large display type should use tighter letter-spacing to feel more "designed" and editorial. Body text maintains a generous line-height (1.6) to enhance the airy, minimalist vibe.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a maximum container width of 1200px to keep line lengths readable. 

- **Vertical Rhythm:** Use `stack-xl` for section spacing to emphasize the minimalist "whitespace" philosophy.
- **Alignment:** Content should be centered in the viewport or aligned to a 12-column grid.
- **Mobile Adaptivity:** Margins shrink from 80px to 20px. On mobile, service grids should collapse to a single column, while badges may remain in horizontal scroll containers to save vertical space.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Ambient Shadows**. 
- **Shadows:** Use extremely soft, large-radius shadows with low opacity (e.g., `box-shadow: 0 10px 40px rgba(248, 200, 220, 0.2)`). This tints the shadow with the primary pink, making it feel integrated rather than "dirty."
- **Glassmorphism:** For floating navigation bars or overlay modals, use a backdrop blur of `20px` combined with a semi-transparent white background (`rgba(255, 255, 255, 0.7)`).
- **Outlines:** Use soft, 1px solid borders in the `Neutral` or `Secondary` color for elements that need definition without the weight of a shadow.

## Shapes
The design system employs a **Pill-shaped (Level 3)** roundedness strategy. This is the cornerstone of the "approachable" and "modern" aesthetic. 
- All standard buttons and input fields use a full pill radius.
- Cards and main containers use a `rounded-xl` (3rem/48px) radius to create a soft, friendly frame for content.
- Small UI elements like badges or checkboxes should use a slightly reduced radius (1rem) but remain distinctly rounded.

## Components
### Service Cards
Cards feature a white surface with a `secondary` color border. Upon hover, they should transition to a soft ambient shadow. Include an icon area using the `accent` (Lavender) color with 20% opacity as a circular background.

### Badges (Skills/Tools)
Badges should be pill-shaped with `label-sm` typography. Use a subtle `secondary` background with `text-primary` for a low-contrast, elegant look. For "Specialist" skills, use the `accent` color.

### Buttons
- **Primary:** Background `primary`, text `white`, pill-shaped, with a subtle lift shadow on hover.
- **Secondary:** Background `white`, 1.5px border in `primary`, text `primary`, pill-shaped.

### Testimonial Components
Testimonials are styled as "quoted cards." Use a large, 10% opacity `primary` color quotation mark icon in the top right. The client name should be in `label-md` and the quote in `body-lg` italicized.

### Input Fields
Inputs use the `neutral` (Cream) background with a pill-shape and `body-md` text. The focus state should transition the border to `primary` with a soft outer glow.