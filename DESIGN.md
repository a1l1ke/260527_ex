---
name: Feline Wellness Framework
colors:
  surface: "#f9f9ff"
  surface-dim: "#cfdaf1"
  surface-bright: "#f9f9ff"
  surface-container-lowest: "#ffffff"
  surface-container-low: "#f0f3ff"
  surface-container: "#e7eeff"
  surface-container-high: "#dee8ff"
  surface-container-highest: "#d8e3fa"
  on-surface: "#111c2c"
  on-surface-variant: "#43474e"
  inverse-surface: "#263142"
  inverse-on-surface: "#ebf1ff"
  outline: "#74777f"
  outline-variant: "#c4c6cf"
  surface-tint: "#006d35"
  primary: "#00270f"
  on-primary: "#ffffff"
  primary-container: "#003f1c"
  on-primary-container: "#3bb466"
  inverse-primary: "#68dd8b"
  secondary: "#246960"
  on-secondary: "#ffffff"
  secondary-container: "#acefe4"
  on-secondary-container: "#2b6f66"
  tertiary: "#23211b"
  on-tertiary: "#ffffff"
  tertiary-container: "#383630"
  on-tertiary-container: "#a39f97"
  error: "#ba1a1a"
  on-error: "#ffffff"
  error-container: "#ffdad6"
  on-error-container: "#93000a"
  primary-fixed: "#85faa5"
  primary-fixed-dim: "#68dd8b"
  on-primary-fixed: "#00210c"
  on-primary-fixed-variant: "#005227"
  secondary-fixed: "#acefe4"
  secondary-fixed-dim: "#91d3c8"
  on-secondary-fixed: "#00201c"
  on-secondary-fixed-variant: "#005049"
  tertiary-fixed: "#e7e2d9"
  tertiary-fixed-dim: "#cbc6bd"
  on-tertiary-fixed: "#1d1b16"
  on-tertiary-fixed-variant: "#494640"
  background: "#f9f9ff"
  on-background: "#111c2c"
  surface-variant: "#d8e3fa"
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: "700"
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: "700"
    lineHeight: 38px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: "600"
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: "600"
    lineHeight: 20px
    letterSpacing: 0.01em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: "500"
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
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The brand personality centers on the intersection of medical excellence and compassionate care. It targets cat owners who view their pets as family members, requiring an interface that feels both authoritative and deeply comforting.

The design style is **Corporate / Modern** with a soft, organic influence. It prioritizes clarity and ease of use to reduce user anxiety during medical inquiries. The emotional response should be one of immediate relief and trust, achieved through generous whitespace, high-quality feline photography, and a balanced hierarchy that never feels cluttered or clinical.

## Colors

The palette is designed to balance professional authority with domestic warmth.

- **Primary (#159A50):** A vibrant Emerald Green used for typography, navigation, and primary call-to-actions. It represents vitality, health, and the "Expert" anchor for the brand.
- **Secondary (#B2F5EA):** A soft, calming Teal used for highlights, icons, and accent backgrounds. It represents the "Healing" aspect of the clinic.
- **Tertiary (#FFF9F0):** A warm Cream used for page backgrounds and large surface areas to avoid the coldness of pure white.
- **Neutral (#4A5568):** A slate grey used for secondary body text and UI borders to maintain legibility without the harshness of black.

## Typography

This design system utilizes **Plus Jakarta Sans** across all levels. Its soft, rounded terminals provide a friendly, approachable character while its geometric foundations maintain professional clarity.

- **Headlines:** Use tighter letter spacing and semi-bold/bold weights to establish a strong hierarchy.
- **Body Text:** Use the standard weight with generous line heights to ensure readability for users who may be stressed or in a hurry.
- **Mobile Scaling:** Headline sizes scale down significantly on mobile to ensure the text remains inviting and doesn't overwhelm the small viewport.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop (12 columns) and a fluid 4-column model on mobile.

- **Desktop:** 1200px max-width container with 24px gutters. Content should be centered with wide margins to create a "boutique" feel.
- **Mobile:** 16px side margins with vertical stacking of all card components.
- **Rhythm:** An 8px base unit drives all padding and margin decisions. Use larger vertical spacing (Section Spacing: 80px) to give content room to "breathe," reinforcing the calming brand promise.

## Elevation & Depth

Depth is expressed through **Ambient Shadows** and **Tonal Layers**. Avoid harsh outlines or high-contrast borders.

- **Surfaces:** Use the Tertiary cream (#FFF9F0) as the base layer. Elevate cards and modals using white (#FFFFFF) backgrounds to make them "pop" subtly.
- **Shadows:** Use a very soft, diffused shadow for interactive elements: `0px 4px 20px rgba(21, 154, 80, 0.08)`. The shadow color is tinted with the Primary Green to keep it integrated with the palette.
- **Interactive Depth:** On hover, buttons and cards should lift slightly (increase shadow blur) to provide tactile feedback without looking mechanical.

## Shapes

The shape language is consistently **Rounded**, avoiding sharp corners to mirror the "soft" nature of feline care.

- **Base Radius:** 0.5rem (8px) for input fields and small buttons.
- **Large Radius:** 1rem (16px) for service cards, content sections, and modals.
- **Icons:** Should use a rounded cap and join style to match the typography.

## Components

- **Service Cards:** Use a white background, 16px corner radius, and a subtle ambient shadow. Top-align a rounded icon (Teal background) followed by a Headline-md and Body-md text.
- **Appointment Buttons:** Primary buttons use the Emerald Green (#159A50) with white text. Use a 48px height for a comfortable tap target.
- **Info Sections:** Use the Teal (#B2F5EA) at 10-20% opacity for background containers to highlight "Important Tips" or "Preparation Instructions."
- **Inputs:** Fields should have a light border (Neutral color at 20% opacity) and 8px rounded corners. Use the Cream (#FFF9F0) for the field background to maintain warmth.
- **Chips/Badges:** Use for "Available" or "Emergency" tags. These should have a pill shape (100px radius) and use the Secondary Teal background with Green text.
- **Lists:** Bullet points should be replaced with custom cat-paw icons or simple rounded teal dots to maintain brand character.
