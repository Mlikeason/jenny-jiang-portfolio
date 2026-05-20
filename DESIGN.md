---
name: Ethereal Growth
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#3d4a39'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6d7b67'
  outline-variant: '#bccbb4'
  surface-tint: '#006e0d'
  primary: '#006e0d'
  on-primary: '#ffffff'
  primary-container: '#00b51d'
  on-primary-container: '#003d04'
  inverse-primary: '#4de249'
  secondary: '#556158'
  on-secondary: '#ffffff'
  secondary-container: '#d9e6da'
  on-secondary-container: '#5b675e'
  tertiary: '#1b6d24'
  on-tertiary: '#ffffff'
  tertiary-container: '#5ead5c'
  on-tertiary-container: '#003d0b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#75ff69'
  primary-fixed-dim: '#4de249'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#005307'
  secondary-fixed: '#d9e6da'
  secondary-fixed-dim: '#bdcabe'
  on-secondary-fixed: '#131e17'
  on-secondary-fixed-variant: '#3e4a41'
  tertiary-fixed: '#a3f69c'
  tertiary-fixed-dim: '#88d982'
  on-tertiary-fixed: '#002204'
  on-tertiary-fixed-variant: '#005312'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 32px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is defined by a synthesis of **Professional Minimalism** and **Organic Softness**. It moves away from cold, industrial tech aesthetics toward a "Visionary Feminine" atmosphere—one that feels high-tech yet deeply approachable and life-centric. 

The visual narrative relies on the tension between precise, technical typography (representing professional rigour) and fluid, flowing shapes (representing creativity and vision). The interface should feel like a breath of fresh air: light, airy, and expansive. By utilizing high-quality whitespace and a palette inspired by natural growth, the design evokes a sense of clarity, forward-thinking, and sophisticated craft.

## Colors

The palette is anchored in a vibrant "Douban Green," symbolizing vitality and freshness. This is balanced by a secondary "Mist Green" that acts as a bridge between the punchy primary and the clean neutrals.

- **Primary (#00B51D):** Used for calls to action, active states, and key brand moments.
- **Secondary (#E8F5E9):** A soft, desaturated green for large surface areas, background sections, and subtle highlights.
- **Neutral High (#FFFFFF):** The true white base for the "light and airy" feel.
- **Neutral Mid (#F9FAFB / #F3F4F6):** Systematic grays used for structural definition without introducing visual weight.
- **Text Primary (#111827):** A deep charcoal (not pure black) to maintain high legibility while appearing softer on the eyes.

## Typography

The choice of **Geist** provides a high-tech, precise backbone to the design system. Its mono-inspired heritage gives the portfolio a "visionary developer" or "technical designer" edge, which perfectly balances the softer organic shapes.

- **Headlines:** Use tighter letter spacing and medium weights to create a strong, authoritative presence.
- **Body Text:** Generous line heights are essential to maintain the "airy" feel. Avoid long line lengths; keep text containers narrow to improve readability.
- **Labels:** Use uppercase or semi-bold weights for small labels (like category tags) to ensure they hold their own against larger visual elements.

## Layout & Spacing

The layout philosophy centers on **Extravagant Whitespace**. Content should never feel crowded. 

- **Grid:** A 12-column fluid grid on desktop, shifting to a single column on mobile. 
- **Section Breaks:** Instead of hard lines, use large vertical gaps (120px+) and organic, flowing SVG "wave" dividers to transition between sections.
- **Margins:** Use wide outer margins to pull the eye toward the center of the screen, creating a sense of focused elegance.
- **Rhythm:** Stick to an 8px base unit for all padding and margins to ensure a systematic, professional finish.

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Soft Diffusion** rather than heavy shadows.

- **Surfaces:** Use subtle background blurs (Glassmorphism) for navigation bars and floating elements. This keeps the background "visible" and maintains the light, airy feel.
- **Shadows:** If used, shadows should be nearly invisible: very high blur (40px+), very low opacity (3-5%), and tinted with the primary green color to avoid "dirty" gray looks.
- **Outlines:** Use ultra-thin (1px) borders in a very light gray or a semi-transparent version of the primary green to define cards without adding visual bulk.

## Shapes

The shape language is the "feminine" heart of this design system. It avoids sharp corners entirely in favor of **Organic, Flowing Curves**.

- **Global Radius:** Use a "Pill-shaped" approach for interactive elements.
- **Cards & Containers:** Large containers should use `rounded-xl` or custom organic SVG masks to create "pebble" or "leaf" shapes rather than standard rectangles.
- **Icons:** Use rounded icon sets (e.g., Lucide with rounded caps) to match the soft geometry of the UI.

## Components

### Buttons
Primary buttons are pill-shaped with a subtle linear gradient (from Primary Green to a slightly lighter tint). Hover states should involve a gentle "lift" or a soft glow effect.

### Cards
Portfolio pieces are housed in cards with an extra-large corner radius (24px+). The background should be a very faint green tint (#F0F9F1) or pure white with a soft 1px border. Avoid heavy shadows; use a slight "scale-up" transform on hover to indicate interactivity.

### Chips & Tags
Used for skills or categories, these should be small, pill-shaped, and use the Secondary Green with Primary Green text. They should feel like soft "bubbles" of information.

### Input Fields
Inputs are minimalist: a soft gray background, no border by default, and a thick 2px Primary Green bottom border that "grows" or illuminates upon focus.

### Navigation
The header is a floating glass container with a backdrop blur. Links are in Geist Mono-style text, using the primary green for the active state indicator—a small dot or a soft underline with rounded ends.