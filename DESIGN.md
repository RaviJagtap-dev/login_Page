---
name: Modern SaaS Authentication & Platform
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#6b00b7'
  on-tertiary: '#ffffff'
  tertiary-container: '#862dd4'
  on-tertiary-container: '#ebd2ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6900b3'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies a modern, precise, and reassuring aesthetic tailored for high-trust digital experiences and modern SaaS onboarding. It fuses strict corporate utility with contemporary digital polish—evoking feelings of security, velocity, and clarity.

The aesthetic follows Modern Minimalist principles layered with ambient atmospheric depth:
- Pure, clean canvas whites paired with slate ink hierarchy for instant readability.
- Purposeful hits of electric indigo to command attention on primary conversion funnels without visual fatigue.
- Soft, airy ambient gradient accents to dissolve mechanical hardness and add refined dimension.
- Smooth tactile curvature across interactive surfaces to maintain an approachable, premium touch.

## Colors

The palette is engineered around pure structural contrast and refined energy:

- **Primary (`#4f46e5` - Electric Indigo):** Anchors core actions, input active states, and focal authentication buttons.
- **Secondary (`#3b82f6` - Royal Azure):** Powers progressive state indicators, secondary focus tiers, links, and complementary gradient nodes.
- **Tertiary (`#a855f7` - Soft Orchid):** Reserved strictly for ambient glow backdrops, decorative pastel mesh blends, and subtle highlight indicators.
- **Neutral Core (`#0f172a` - Deep Slate):** Provides high-contrast typographic hierarchy. Extended across tonal tints:
  - Surface base: `#ffffff`
  - Subtle background fill: `#f8fafc`
  - Subtle border strokes: `#e2e8f0`
  - Secondary text / Muted: `#64748b`

### Ambient Pastel Gradients
For authentication layouts, splash panels, and subtle card backdrops, blend the primary, secondary, and tertiary tones into soft 8% to 15% opacity radial and linear gradient fills against the crisp white base canvas.

## Typography

The type system pairs **Plus Jakarta Sans** for expressive, humanistic display headers with **Inter** for technical, distortion-free utility across body text and form controls.

- **Headlines:** Use Plus Jakarta Sans with tight negative tracking to give headings a cohesive, branded architectural feel.
- **Body:** Inter provides neutral geometry, deep x-height, and superior legibility across small authentication labels, error states, and helper instructions.
- **Forms & Data:** Keep numeric tables, inputs, and security code verification characters legible by setting `font-feature-settings: 'cv02', 'cv03', 'cv04', 'cv11'` within Inter.

## Layout & Spacing

The layout is built around an 8px base rhythm implemented across a flexible 12-column layout for dashboard contexts, and a focused single-column or split-view layout for authentication.

- **Authentication Layouts:** Dual-pane layout on desktop (50/50 split or 45/55 ratio) with an active branding/testimonial gradient panel on the left/right and an authentication card centered horizontally and vertically on the opposite side. Maximum card constraint is `440px`.
- **Form Factor Adaptations:**
  - **Desktop (≥ 1024px):** Split layout active, `margin: 2rem`, form card padded with `space-xl` internally.
  - **Tablet (768px - 1023px):** Simplified single pane with ambient background illumination behind a centered container card.
  - **Mobile (< 768px):** Single-column fluid stack, `margin-mobile: 1rem`, form card edge-to-edge or minimum gutter margins with reduced horizontal card padding (`space-md`).

## Elevation & Depth

Depth in this system is conveyed through subtle tonal borders paired with multi-layer ambient shadows, preventing high-contrast muddy edges:

- **Flat / Ground:** Pure `#ffffff` or clean background `#f8fafc` without shadow. Used for page-level structural wrappers.
- **Card Base (Level 1):** Solid white surface outlined by a crisp hairline border (`1px solid #e2e8f0`) complemented by dual-layer diffused light:
  - `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 8px 24px -4px rgba(15, 23, 42, 0.05);`
- **Elevated Overlay / Popovers (Level 2):** Dropdown menus, tooltips, and authentication modal sheets:
  - `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 20px 32px -8px rgba(15, 23, 42, 0.08);`
- **Active Focus Depth:** Focus states on inputs and active cards introduce a soft tinted aura:
  - `box-shadow: 0 0 0 4px rgba(79, 70, 229, 0.12);`

## Shapes

The design system maintains a modern, approachable contour by embracing generous geometric curves:

- **Input Fields & Text Areas:** Use explicit `rounded-xl` (`1.5rem` / `24px` for pills or structured `0.75rem` / `12px` minimum) to establish a distinct, friendly boundary for interaction.
- **Cards & Modal Wrappers:** Base radius of `1rem` (16px) up to `1.5rem` (24px) for prominent login containers.
- **Buttons:** Match input curvature (`0.75rem` / 12px or fully rounded pill styles depending on context) for visual synchronicity.
- **Badges & Chips:** Full pill radius (`9999px`) to maintain clear differentiation from rectangular inputs.

## Components

### Input Fields
- **Height & Spacing:** `48px` default height, `14px` horizontal padding (`space-md`).
- **Border & Surface:** `1px solid #e2e8f0`, background `#ffffff`, radius set to `rounded-xl` (`12px`).
- **Typography:** Inter 14px (`body-md`), text color `#0f172a`, placeholder text `#94a3b8`.
- **States:**
  - *Hover:* Border color transitions to `#cbd5e1`.
  - *Focus:* Border shifts to `#4f46e5` accompanied by an electric aura glow (`0 0 0 4px rgba(79, 70, 229, 0.12)`).
  - *Error:* Border `#ef4444`, aura glow `rgba(239, 68, 68, 0.12)`, helper text `#ef4444`.

### Buttons
- **Primary:** Background `#4f46e5` (or linear gradient from `#4f46e5` to `#3b82f6`), text `#ffffff`, font `label-lg`, height `48px`, border radius `rounded-xl`. Hover lifts subtly with `box-shadow: 0 4px 14px 0 rgba(79, 70, 229, 0.35)`.
- **Secondary / Social Auth:** Border `1px solid #e2e8f0`, background `#ffffff`, text `#0f172a`. Hover switches background to `#f8fafc` and border to `#cbd5e1`.
- **Ghost / Link:** Transparent background, text `#4f46e5`, hover text `#3730a3`.

### Cards (Login / Auth Container)
- Background `#ffffff`, border `1px solid #e2e8f0`, radius `rounded-xl` (16px–24px), padding `space-xl` (40px desktop, 24px mobile).
- Grounded with Level 1 elevation shadow.

### Checkboxes & Radio Buttons
- Custom 18px controls with `4px` roundedness for checkboxes and complete circle for radio buttons.
- Inactive: `1.5px solid #cbd5e1`, background `#ffffff`.
- Active: Background `#4f46e5`, check/dot icon `#ffffff`, border `#4f46e5`.

### Chips & Badges
- Pill-shaped (`roundedness: 3`), font `label-sm`, padding `4px 10px`.
- Pastel variant: Background `rgba(79, 70, 229, 0.08)`, text `#4f46e5`, border `1px solid rgba(79, 70, 229, 0.16)`.

### Authentication Dividers
- Horizontal hairline `#e2e8f0` centered with `body-sm` text ("or continue with") in `#64748b` over a `#ffffff` pill mask.

### Single Sign-On (SSO) Stack
- Full-width secondary buttons with strict `12px` spacing between providers, displaying standardized 18px vector brand icons with aligned label text.