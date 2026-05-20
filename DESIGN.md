---
name: DL Trips Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#272b2d'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d4143'
  on-tertiary-container: '#aaadaf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
  headline-sm:
    fontFamily: Montserrat
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
    letterSpacing: 0.01em
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
  margin-desktop: 40px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is engineered for a premium global travel platform, focusing on high-end B2C experiences that balance corporate reliability with the aspirational nature of luxury travel. The brand personality is authoritative yet welcoming, evocative of first-class lounges and bespoke concierge services.

The visual style follows a **Modern Corporate** aesthetic with a lean toward **Minimalism**. It prioritizes heavy white space to allow high-quality destination photography to breathe. Depth is achieved through sophisticated tonal layering and subtle shadows rather than heavy decorative elements. The emotional response should be one of total confidence, ease of use, and understated luxury.

## Colors

The color palette is anchored by **Deep Corporate Blue**, signifying stability, trust, and global reach. This is complemented by **Sophisticated Orange**, used sparingly as a high-contrast accent to draw attention to primary actions and premium status indicators.

- **Primary (#1e3a8a):** Used for navigation headers, primary buttons, and core branding elements.
- **Accent (#f97316):** Reserved for "Book Now" actions, price highlights, and active selection states.
- **Surface/Background (#ffffff):** The primary canvas, ensuring a clean and airy feel.
- **Subtle Surface (#f8fafc):** Used for card backgrounds and section grouping to create soft contrast against the white base.
- **Text/Neutral (#0f172a):** Deep charcoal for maximum legibility on headings; (#64748b) for secondary body copy.

## Typography

The typography strategy pairs the geometric confidence of **Montserrat** for headings with the systematic precision of **Inter** for UI and body text. 

Headlines use tighter letter spacing and bold weights to command authority. Body text is optimized for readability during long-form itinerary reviews, utilizing generous line heights. Small labels and "Overlines" should use uppercase Inter with slight tracking to denote categories or metadata (e.g., "ECONOMY CLASS" or "NON-STOP").

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy emphasizes "Breathable Logic," where spacing is used to group related information without the need for heavy borders.

- **Desktop:** 12 columns, 24px gutters, 40px side margins. Max container width of 1280px to prevent excessive line lengths on ultra-wide monitors.
- **Mobile:** Single column flow, 16px side margins.
- **Spacing Rhythm:** Based on an 8px base unit. Vertical stack spacing (stack-md) is the default for section elements, while larger gaps (stack-lg) separate distinct content blocks like "Featured Destinations" from "Search Results."

## Elevation & Depth

To maintain a premium, modern feel, this design system avoids heavy shadows. Instead, it uses **Ambient Depth** and **Tonal Layers**.

- **Level 0 (Base):** Pure white (#ffffff) for the main background.
- **Level 1 (Cards):** Soft contrast using a 1px border (#e2e8f0) or an extremely diffused shadow (0px 4px 20px rgba(0, 0, 0, 0.04)).
- **Level 2 (Hover/Floating):** Used for active cards and navigation menus. A more pronounced shadow (0px 10px 30px rgba(30, 58, 138, 0.08)) that incorporates a hint of the primary blue in the shadow tint.
- **Glassmorphism:** Use a 20px backdrop blur with 80% white opacity for "Sticky Navigation" headers to maintain context of the content behind while scrolling.

## Shapes

The shape language is "Refined-Rounded." We avoid sharp corners to feel approachable, but avoid pill-shapes for primary containers to maintain a professional, corporate structure.

- **Standard (8px):** Primary buttons, input fields, and small cards.
- **Large (16px):** Main content cards, image containers, and modal windows.
- **Extra Large (24px):** Hero sections and promotional banners.
- **Interactive Icons:** Should be encased in circular or soft-square housings for a "button-like" feel.

## Components

### Buttons
- **Primary:** Deep Blue (#1e3a8a) background, white text. Subtle 200ms transition on hover to a slightly darker shade.
- **Action/CTA:** Sophisticated Orange (#f97316) for conversion points.
- **Ghost:** 1px border (#cbd5e1) with primary blue text for secondary actions.

### Input Fields
- High-affordance fields with 8px radius. 
- Focus state: 2px border of Primary Blue with a soft 4px glow.
- Labels are always visible, positioned above the field in Label-MD typography.

### Cards
- Destination cards feature high-resolution imagery with a subtle gradient overlay at the bottom to ensure white typography (price/location) remains legible.
- 1px neutral-200 border for definition on white backgrounds.

### Chips & Tags
- Used for flight features (e.g., "WiFi," "Extra Legroom") or status (e.g., "Refundable").
- Light grey backgrounds with dark grey text for utility; Light Blue with Primary Blue text for "Verified" or "Premium" status.

### Additional Components
- **Search Bar (The Concierge):** A signature, elevated floating component with integrated date pickers and guest counters, utilizing Level 2 elevation to appear "above" the hero imagery.
- **Progressive Disclosure:** Use accordions for detailed flight information (Baggage rules, fare details) to keep the initial interface clean and uncluttered.