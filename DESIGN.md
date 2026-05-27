---
name: Heritage Excellence
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#44474e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f88'
  primary: '#000a1e'
  on-primary: '#ffffff'
  primary-container: '#002147'
  on-primary-container: '#708ab5'
  inverse-primary: '#aec7f6'
  secondary: '#6c5e06'
  on-secondary: '#ffffff'
  secondary-container: '#f7e382'
  on-secondary-container: '#73640e'
  tertiary: '#180500'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d1500'
  on-tertiary-container: '#b97958'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aec7f6'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#f7e382'
  secondary-fixed-dim: '#dac769'
  on-secondary-fixed: '#211b00'
  on-secondary-fixed-variant: '#524700'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#6c391d'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: EB Garamond
    fontSize: 60px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
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
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
  container-max: 1280px
---

## Brand & Style

The design system balances the prestigious weight of a legacy academic institution with the clarity of intentional minimalism. It is designed to evoke a sense of quiet authority, academic rigor, and a welcoming, forward-thinking environment.

The visual direction follows a **Corporate / Modern** aesthetic with heavy influences from **Minimalism**. By prioritizing generous whitespace and a modular "Bento Grid" structure, the system ensures that complex educational information remains digestible and focused. The "Elite Academy" feel is achieved through high-contrast typography and a restrained use of metallic accents, moving away from cluttered traditional layouts toward a sophisticated, gallery-like digital experience.

## Colors

The palette is rooted in tradition and stability. 
- **Primary (Navy):** Used for core branding, headers, and primary actions to signify authority and trust.
- **Secondary (Gold):** Reserved for highlights, accents, and moments of celebration or achievement. It should be used sparingly to maintain its "premium" impact.
- **Background (Off-white):** Provides a softer, more sophisticated canvas than pure white, reducing eye strain and enhancing the "heritage" feel.
- **Body (Slate Grey):** Ensures high legibility without the harshness of pure black, maintaining a modern, editorial tone.

## Typography

This design system utilizes a high-contrast typographic pairing to bridge the gap between history and modernity.

**EB Garamond** is the voice of the institution. It is used for all major headlines and display text. Its classical proportions and elegant serifs communicate the school's long-standing heritage. 

**Inter** provides the functional backbone. It is utilized for all body copy, navigation, and UI labels. Its neutral, geometric construction ensures maximum readability across digital interfaces, providing a necessary counterpoint to the more decorative serif.

Use `label-sm` with the Champagne Gold color for sub-headers or categories to add an "editorial" touch to information hierarchy.

## Layout & Spacing

The layout philosophy centers on a **Fixed Grid** modularity, specifically utilizing a **Bento Grid** approach. Content is housed in distinct, rectangular modules of varying sizes that sit harmoniously within a 12-column system.

- **Desktop:** 12-column grid with 24px gutters. Content is contained within a 1280px max-width wrapper.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px gutters and 24px side margins.

Vertical rhythm is strictly maintained using 8px increments. Large sections of content should be separated by generous whitespace (80px - 120px) to uphold the minimalist aesthetic and allow the "atmospheric" photography to breathe.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. Because the background is a soft off-white (#FAFAFA), elevation is communicated by placing pure white (#FFFFFF) containers on top of the background.

- **Low Elevation:** Used for Bento Grid cards. A 1px border in a very light slate (#E0E0E0) or a soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.04)).
- **High Elevation:** Used for modals and dropdown menus. These feature more pronounced, deeper shadows (0px 10px 40px rgba(0,0,0,0.08)) to pull the element forward.
- **Interactive States:** On hover, cards may lift slightly (shadow deepens) or the border color may shift to the primary Navy or Gold.

## Shapes

The shape language is sophisticated and soft. The design system uses a base roundedness of 8px (`0.5rem`), but for larger layout containers and Bento Grid modules, the `rounded-lg` (16px) or `rounded-xl` (24px) tokens should be applied.

The goal is to move away from the "institutional" feel of sharp corners toward a friendlier, modern academic environment. 
- **Small components (Buttons, Inputs):** 8px radius.
- **Large containers (Cards, Images):** 16px to 24px radius.
- **Iconography:** Should follow a medium stroke weight with slightly rounded terminals to match the UI.

## Components

### Buttons
- **Primary:** Solid Navy (#002147) with White Inter text. High-contrast and authoritative.
- **Secondary:** Outline style with Gold (#C5B358) borders and text. Used for less urgent actions.
- **Ghost:** Pure text with an underline on hover, used for secondary navigation.

### Cards (Bento Style)
Cards are the primary organizational unit. They should have a white background, 16px or 24px corner radius, and contain significant internal padding (min 32px). Use these for faculty bios, news items, and program highlights.

### Input Fields
Inputs should be minimalist: a 1px bottom border or a very light grey outlined box. Focus states should transition the border color to Navy. Labels are always `label-sm` and sit above the field.

### Lists & Navigation
Use horizontal navigation for the header with `label-sm` typography. Lists within content modules should use custom bullet points—either small Navy squares or Gold chevrons—to maintain the academic branding.

### Imagery
Images are a core component. All student life photography should be high-resolution, featuring natural lighting and "atmospheric" depth of field. Photos must also follow the system's corner radius (16px+) to integrate into the Bento Grid seamlessly.