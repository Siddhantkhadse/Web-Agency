---
name: Synthetic Velocity
colors:
  surface: '#1E293B'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#c0c1ff'
  on-secondary: '#1000a9'
  secondary-container: '#3131c0'
  on-secondary-container: '#b0b2ff'
  tertiary: '#ffb873'
  on-tertiary: '#4b2800'
  tertiary-container: '#e89337'
  on-tertiary-container: '#5b3200'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#ffdcbf'
  tertiary-fixed-dim: '#ffb873'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#6a3b00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
  border-accent: rgba(34, 211, 238, 0.2)
  glass-bg: rgba(15, 23, 42, 0.6)
  text-dim: '#94A3B8'
typography:
  display:
    fontFamily: DM Sans
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
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
  margin-desktop: 48px
---

## Brand & Style
The design system for Rendercept centers on the concept of "Synthetic Velocity"—the intersection of high-performance engineering and refined aesthetics. The brand personality is blazingly fast, professional, and cutting-edge, targeting high-growth tech startups and enterprise clients who value technical precision.

The visual style is a blend of **Minimalism** and **Glassmorphism**, set against a deep, technical backdrop. It utilizes high-contrast accents and translucent layers to create a sense of digital depth. The aesthetic is strictly "Developer-First," prioritizing clarity, information density, and smooth motion to reinforce the agency's technical prowess.

## Colors
The palette is built on a "Deep Space" foundation to emphasize its high-tech nature. 

- **Primary:** Electric Cyan (#06B6D4) is used exclusively for primary actions, success states, and critical highlights to draw the eye instantly.
- **Secondary:** An Indigo hue (#6366F1) provides a subtle lean into the original brand's purple heritage, used for gradients and secondary brand elements.
- **Neutral:** The core interface uses Slate-900 (#0F172A) for backgrounds and Slate-800 (#1E293B) for surface elevations. 
- **Functional:** Text primarily utilizes Slate-300 for readability, while pure white is reserved for high-impact headlines.

## Typography
The typographic system leverages three distinct typefaces to convey different aspects of the brand:

- **DM Sans (Headlines):** Low-contrast and geometric, providing a clean and modern "SaaS" feel.
- **Inter (Body):** Used for all long-form content to ensure maximum legibility and a neutral, professional tone.
- **JetBrains Mono (Technical Details):** Utilized for labels, buttons, and micro-copy to evoke a "code-like" high-tech aesthetic.

All headlines should use tight letter spacing to appear more aggressive and modern. Display text should use a subtle vertical gradient from White to Slate-300.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop and a **Fluid** model for mobile.

- **Grid:** A 12-column grid system with 24px gutters. Content is centered in a 1280px container.
- **Rhythm:** An 8px linear scale (8, 16, 24, 32, 48, 64, 80, 128) governs all padding, margins, and component heights.
- **Breakpoints:** Mobile (<768px), Tablet (768px - 1024px), Desktop (>1024px). 
- **Reflow:** On mobile, margins reduce to 16px and the 12-column grid collapses to a single-column stack.

## Elevation & Depth
Depth is created through light and transparency rather than traditional heavy shadows.

- **Layer 0 (Background):** Slate-900.
- **Layer 1 (Surfaces):** Slate-800 with a 1px border of Slate-700.
- **Glassmorphism:** Overlays and modals use `glass-bg` with a `backdrop-filter: blur(12px)`. These elements must have a 1px semi-transparent highlight border on the top and left edges to simulate physical thickness.
- **Shadows:** Use a single "Glow" shadow for active elements: `0 0 20px rgba(6, 182, 212, 0.15)`.

## Shapes
The shape language is "Soft-Industrial." Components use a small 4px (0.25rem) radius to maintain a precise, engineered look while avoiding the harshness of 0px corners. Large containers or "Glass" cards may use up to 8px (0.5rem) to differentiate themselves from smaller UI controls. Buttons and inputs must remain consistently at 4px.

## Components
- **Buttons:** Primary buttons are solid Cyan-500 with black text. Secondary buttons are "Ghost" style with a Cyan border and Cyan text. All buttons feature a 200ms transition on hover, shifting the background color slightly lighter.
- **Input Fields:** Dark slate background with a 1px border. On focus, the border glows Cyan and the label (in JetBrains Mono) shifts to Cyan.
- **Cards:** Utilize the Glassmorphism style. Background blur is mandatory. A subtle "Cyan Line" (2px) should appear at the very top of featured cards.
- **Chips/Tags:** Use JetBrains Mono. Styled as Slate-800 capsules with Slate-400 text.
- **Lists:** Items are separated by thin Slate-800 borders. Hovering an item should trigger a subtle Slate-800/50 background fill.
- **Additional Elements:** Include a "Terminal" component for displaying code snippets or process logs, reinforcing the high-tech agency theme.