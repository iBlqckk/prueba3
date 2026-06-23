---
name: Club de Sonrisas Sanas
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf1'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fa'
  on-surface: '#111c2c'
  on-surface-variant: '#43474e'
  inverse-surface: '#263142'
  inverse-on-surface: '#ebf1ff'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#436084'
  primary: '#002444'
  on-primary: '#ffffff'
  primary-container: '#1a3a5c'
  on-primary-container: '#87a4cc'
  inverse-primary: '#abc9f2'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fdcf49'
  on-secondary-container: '#715800'
  tertiary: '#1d242a'
  on-tertiary: '#ffffff'
  tertiary-container: '#323a3f'
  on-tertiary-container: '#9ba4aa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#abc9f2'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#2a486b'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#eec13c'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#dbe3ea'
  tertiary-fixed-dim: '#bfc8ce'
  on-tertiary-fixed: '#151d22'
  on-tertiary-fixed-variant: '#40484d'
  background: '#f9f9ff'
  on-background: '#111c2c'
  surface-variant: '#d8e3fa'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
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
    letterSpacing: 0.05em
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built on a foundation of **Professionalism, Warmth, and Trust**. It balances clinical precision with an approachable "membership" feel, ensuring patients feel cared for rather than processed. 

The aesthetic is **Corporate Modern with Tactile Warmth**. It utilizes generous whitespace and a structured layout to convey competence, while employing soft shapes and golden accents to humanize the experience. The interface should feel premium and stable, evoking the reliability of a high-end health club tailored for dental excellence.

## Colors

The palette is dominated by **Deep Navy (#1A3A5C)**, providing a sense of authority and clinical depth. This is balanced by **Golden Yellow (#F5C842)**, which is used sparingly for accents, primary calls to action, and "moments of delight" to signify value and warmth.

- **Primary:** Used for headers, primary buttons, and navigational elements.
- **Secondary:** Used for highlight states, membership badges, and key conversion points.
- **Surface:** A crisp white background maintains the clinical "clean" feel.
- **Tertiary:** A very soft blue-grey tint used for section backgrounds and card offsets to prevent visual fatigue.

## Typography

This design system utilizes a dual-font strategy. **Montserrat** is used for headings to provide a confident, geometric, and modern personality. **Inter** is used for all body text and UI labels to ensure maximum legibility and a systematic, functional feel.

Hierarchy is established through significant weight shifts. Headlines should lean towards Semi-Bold and Bold to anchor the page, while body text remains in Regular weight to maintain an airy, readable feel. All labels should be medium-weight to distinguish them clearly from prose.

## Layout & Spacing

The system follows a **12-column fluid grid** for desktop and a **4-column grid** for mobile. Spacing is governed by an 8px linear scale to ensure mathematical harmony across all components.

- **Desktop:** 12 columns, 24px gutters, 64px side margins. Max-width of 1440px for content containers.
- **Tablet:** 8 columns, 20px gutters, 32px side margins.
- **Mobile:** 4 columns, 16px gutters, 16px side margins.

Vertical rhythm should be generous. Use `lg` (48px) or `xl` (80px) spacing between major sections to emphasize the premium, unhurried nature of the clinical brand.

## Elevation & Depth

To achieve a "Trustworthy" feel, the system avoids harsh shadows in favor of **Ambient, Tinted Depth**. 

- **Level 1 (Cards):** Soft, highly diffused shadows using a 5% opacity of the Primary Blue color. (Blur: 12px, Y: 4px).
- **Level 2 (Dropdowns/Modals):** Increased spread and slightly higher opacity (8%) to suggest physical proximity to the user.
- **Tonal Layering:** Use the Tertiary light-blue color (#E6EEF5) for container backgrounds to create depth without relying solely on shadows. This "recessed" look helps organize complex medical data or appointment forms.

## Shapes

The shape language is defined by **Rounded (0.5rem)** corners. This specific radius is used to soften the "sharpness" of a medical environment, making the UI feel more inviting and less institutional.

- **Buttons & Inputs:** 0.5rem (8px)
- **Cards & Modals:** 1rem (16px)
- **Badges/Chips:** Full pill (999px) to contrast against the structured squareness of the grid.

## Components

### Buttons
- **Primary:** Solid Primary Blue with White text. High-contrast, 0.5rem radius.
- **Secondary:** Solid Golden Yellow with Primary Blue text. Reserved for the most important "Join" or "Book" actions.
- **Ghost:** Primary Blue border (1px) with transparent background.

### Input Fields
Inputs should have a subtle 1px border in a light-neutral shade. On focus, the border transitions to Primary Blue with a soft 2px outer glow. Labels are always positioned above the field for accessibility.

### Cards
Cards are white with a Level 1 shadow and a 16px corner radius. They should include a subtle 1px border in the Tertiary color (#E6EEF5) to ensure definition on white backgrounds.

### Chips & Status
Used for "Membership Status" or "Treatment Categories." Use the pill shape. Use Golden Yellow for active/premium statuses and Primary Blue for neutral/category tags.

### Progress Indicators
Step indicators for booking appointments should use Primary Blue for completed steps and Golden Yellow for the current active step, emphasizing progress and achievement.