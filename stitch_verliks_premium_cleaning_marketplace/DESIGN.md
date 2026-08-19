---
name: Verliks Boutique Clean
colors:
  surface: '#fff8f5'
  surface-dim: '#e0d8d5'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ee'
  surface-container: '#f4ece8'
  surface-container-high: '#eee7e3'
  surface-container-highest: '#e9e1dd'
  on-surface: '#1e1b19'
  on-surface-variant: '#404944'
  inverse-surface: '#33302d'
  inverse-on-surface: '#f7efeb'
  outline: '#707974'
  outline-variant: '#bfc9c3'
  surface-tint: '#2b6954'
  primary: '#003527'
  on-primary: '#ffffff'
  primary-container: '#064e3b'
  on-primary-container: '#80bea6'
  inverse-primary: '#95d3ba'
  secondary: '#5d5e62'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e6'
  on-secondary-container: '#636468'
  tertiary: '#2d2f2e'
  on-tertiary: '#ffffff'
  tertiary-container: '#434545'
  on-tertiary-container: '#b1b2b1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0f0d6'
  primary-fixed-dim: '#95d3ba'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#0b513d'
  secondary-fixed: '#e2e2e6'
  secondary-fixed-dim: '#c6c6ca'
  on-secondary-fixed: '#1a1c1f'
  on-secondary-fixed-variant: '#45474a'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c7c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fff8f5'
  on-background: '#1e1b19'
  surface-variant: '#e9e1dd'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
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
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 80px
---

## Brand & Style

The design system is rooted in a "Boutique Hospitality" narrative. It moves away from the chaotic, high-energy aesthetic of typical gig-economy platforms toward a calm, curated, and editorial experience. The target audience values reliability and the "luxury of time," requiring a UI that feels stable, premium, and human-centric.

The style is **Minimalist-Editorial**. It prioritizes intentional whitespace as a luxury commodity, ensuring every element has room to breathe. By combining high-contrast typography with a muted, organic color palette, the system establishes immediate trust and professionalism. Visual clutter is treated as a service failure; simplicity is the ultimate sign of quality.

## Colors

The palette is anchored by **Deep Emerald**, used with extreme restraint to highlight key actions and denote verified status. The core of the interface is built upon **Soft Warm Whites** and **Light Stone** tones to evoke the feeling of a freshly cleaned, sun-drenched home.

- **Primary (Deep Emerald):** Reserved for primary CTAs, "Verified" badges, and subtle brand accents.
- **Background (Warm White):** Used for the main canvas to maintain an airy, hospitable feel.
- **Neutral (Charcoal):** Used for all primary text to ensure maximum readability and a high-end editorial look.
- **Accents (Warm Gold-Tinted Neutrals):** Used for subtle dividers, hover states, and iconography that requires a softer touch than the primary emerald.

## Typography

This design system utilizes a dual-sans serif approach to balance character with utility. **Hanken Grotesk** provides a sharp, contemporary geometric feel for headlines, while **Inter** ensures foolproof legibility for body copy and data.

For an editorial feel, headlines utilize tight negative letter-spacing and aggressive line heights. Body text uses generous line heights (1.6) to create a relaxed reading pace. Labels and utility text are occasionally set in uppercase with increased letter spacing to provide a clear functional distinction from editorial content.

## Layout & Spacing

The layout follows a strict **12-column fluid grid** for desktop, collapsing to a 4-column grid for mobile. The hallmark of the system is "significant vertical rhythm." 

Sections are separated by large padding blocks (80px+) to prevent the "SaaS clutter" feel. Content should be centered within the 1200px container to maintain focus. Use an 8px base grid for all internal component spacing to ensure mathematical harmony. Margins on desktop are intentionally wide (64px) to frame the content like a premium magazine spread.

## Elevation & Depth

To maintain a minimalist aesthetic, depth is created primarily through **Tonal Layers** and **Low-contrast outlines** rather than heavy shadows.

- **Surface 1 (Base):** Warm White (#FAFAF9).
- **Surface 2 (Elevated):** Pure White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(28, 25, 23, 0.04)).
- **Outlines:** Subtle 1px borders in Light Stone (#D4D4D8) are used to define boundaries without adding visual weight.

Avoid multiple layers of shadows. If an element needs to feel "above" the page, use a change in background color (e.g., from Warm White to Pure White) first.

## Shapes

The design system uses a **Soft (0.25rem)** roundedness profile. This creates a "refined precision" look—softer than a brutalist sharp edge but more professional and sophisticated than high-radius "bubbly" designs.

- **Standard Elements:** 4px radius (Buttons, Inputs).
- **Large Elements:** 8px radius (Cards, Modals).
- **Interactive States:** Maintain consistent radii; do not increase roundedness on hover.

## Components

### Buttons
- **Primary:** Solid Deep Emerald fill, white text, 4px radius. No gradients.
- **Secondary:** Transparent fill with a 1px Stone border. Text in Charcoal.
- **Tertiary/Ghost:** No border or fill. Text in Charcoal with a subtle underline on hover.

### Cards
- Cards must use generous internal padding (min 32px). 
- Use a 1px Stone border rather than a shadow for standard state; apply a soft shadow only on hover to indicate interactivity.

### Input Fields
- Understated style: 1px Stone border, Warm White background. 
- Focus state: Border changes to Deep Emerald; no heavy outer glows.

### Chips & Badges
- **Verified Badge:** Deep Emerald icon with small, uppercase text.
- **Service Tags:** Light Stone background, Charcoal text, 2px radius (tighter than buttons).

### Lists
- Use wide vertical spacing between list items. 
- Bullet points should be replaced with subtle Emerald checkmarks or minimal Stone dashes to maintain the editorial look.