---
name: Clinical Empathy & Precision Glass
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#3d4947'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#515c71'
  on-tertiary: '#ffffff'
  tertiary-container: '#6a758a'
  on-tertiary-container: '#fefcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  data-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a clinical-grade yet deeply human visual language for a multimodal wearable health interface. The brand personality balances laboratory precision with intimate, empathetic reassurance. Designed for research participants and clinical investigators monitoring longitudinal breast tissue health (thermal distribution, cellular bioimpedance, and deep-tissue optical NIRS hemodynamics), the interface avoids cold, alarmist diagnostic tropes in favor of calm, actionable clarity.

The aesthetic philosophy fuses **Modern Clinical Minimalism** with **Subtle Frosted Glassmorphism**:
- **Tactile Comfort:** Soft, organic curvatures evoke the wearable fabric and natural anatomy, banishing harsh, sharp corners or intimidating clinical red flags.
- **Atmospheric Depth:** Frosted glass planes float over tinted neutral foundations, allowing dense multidimensional data (heat maps, impedance curves, oxygenation saturation) to layer cleanly without cognitive overload.
- **Sensor Domain Visual Architecture:** Clear, dedicated sensory colorways allow multi-modal data to be differentiated effortlessly while maintaining an overarching palette of calming medical teal and deep oceanic slate.

## Colors

The palette establishes an emotional sanctuary through balanced, therapeutic undertones while delivering rigorous clinical hierarchy.

### Core Foundation
- **Primary (Medical Teal - `#0D9488` | Active Tint `#14B8A6` | Ambient Wash `#CCFBF1`):** The grounding core representing diagnostic confidence, cellular equilibrium, and therapeutic care. Used for dominant interactions, confirmed connection states, and principal navigation highlights.
- **Secondary (Comforting Sky - `#0284C7` | Soft Air `#E0F2FE`):** Represents fluid dynamics, continuous background synchronization, and peripheral system telemetry.
- **Tertiary (Oceanic Slate Navy - `#0F172A` | Sub-Slate `#1E293B`):** Structural framework, high-contrast typography, and navigational hulls that prevent visual fatigue and deliver high-precision readability.
- **Neutral Canvas (`#F8FAFC`):** A soft, clinical-paper foundation tinted with subtle slate to eliminate ocular strain caused by stark `#FFFFFF` surfaces.

### Multimodal Sensor Domains
Sensor channels maintain dedicated chromatic identities to prevent cross-stream confusion:
- **Thermal Sensing (Warm Coral - `#F43F5E` | Substrate `#FFE4E6`):** Calibrated for skin surface temperature distribution and thermographic delta metrics.
- **Bioimpedance Sensing (Electrical Amber - `#D97706` | Substrate `#FEF3C7`):** Represents tissue resistance, reactance phase angles, and intracellular fluid metrics.
- **Optical NIRS (Deep Violet - `#8B5CF6` | Substrate `#EDE9FE`):** Encodes near-infrared optical spectroscopy, tissue hemoglobin balance, and regional tissue oxygenation ($StO_2$).

### Semantic Protocol & Non-Alarmist Rules
Warning states prioritize non-alarmist communication. Critical connection drops or measurement anomalies rely on calm amber and deep slate interventions rather than high-saturation danger states. Pure `#F43F5E` is reserved strictly for functional thermal telemetry, never for generic system error states.

## Typography

The typographic hierarchy combines **Plus Jakarta Sans** for structural warmth and empathy with **Inter** for clinical data density.

- **Plus Jakarta Sans (Headlines, Displays, Numerical Readouts):** Features humane, open counters and subtle geometric softening. Numerical metric displays use tabular figures (`tnum`) to eliminate micro-jitter during real-time Bluetooth streaming updates.
- **Inter (Body, Clinical Documentation, Metadata Labels):** Engineered for rigorous legibility at minute scales (11px–14px). Delivers high vertical distinction between alphanumeric characters, safeguarding vital sensor calibrations, units ($^{\circ}\text{C}$, $\Omega$, $\mu\text{M}$), and diagnostic notes.

### Styling & Text Hierarchy
- **Primary Copy:** Rendered in Oceanic Slate 900 (`#0F172A`) for effortless legibility against frosted backdrops.
- **Secondary Copy:** Rendered in Slate 600 (`#475569`), preserving strict WCAG AAA contrast ratios for observational data.
- **Units & Metric Sub-labels:** Always rendered in medium weight uppercase labels with proportional letter-spacing (`0.03em`) to anchor clinical measurements distinctly.

## Layout & Spacing

The layout model is founded on an **8pt clinical rhythm** (using an explicit 4pt micro-scale for precise hardware toggles and signal indicators). 

### Layout Behavior
- **Mobile (Single-column stream):** Employs `margin` (16px) with an adaptive flex column. Sensor streams stack sequentially: Connection Matrix $\rightarrow$ Primary Composite Status $\rightarrow$ Granular Sensor Ribbons.
- **Tablet (8-column hybrid grid):** Uses `gutter-tablet` (24px) and `margin-tablet` (32px). Splits anatomical visualizations (left 4 columns) from time-series metrics (right 4 columns).
- **Desktop / Research Console (12-column fixed-max grid):** Max-width constrained to 1440px with `gutter-desktop` (32px) and `margin-desktop` (48px). Enables side-by-side simultaneous tri-modal comparison graphs (Thermal, Impedance, Optical) alongside real-time contact impedance indicators.

### Content Density
Interface panels default to breathable padding (`space-lg`), insulating the user from the panic of overcrowded medical software, while internal metric clusters compress to `space-sm` for immediate visual grouping.

## Elevation & Depth

Visual hierarchy uses a refined **Translucent Frosted Layering** model rather than deep, murky dropshadows, ensuring clean spatial separation.

### Surface Tiers
- **Canvas (`#F8FAFC`):** The ambient base layer.
- **Level 1 — Glass Panel (Resting Card / Container):** Background of `rgba(255, 255, 255, 0.72)` paired with `backdrop-filter: blur(16px)` and a crisp low-contrast perimeter outline: `1px solid rgba(226, 232, 240, 0.80)`. Shadow: `0 4px 20px -2px rgba(15, 23, 42, 0.03), 0 2px 6px -1px rgba(15, 23, 42, 0.02)`.
- **Level 2 — Elevated Floating Shield (Modals, Overlays, Active Sensor Pods):** Background of `rgba(255, 255, 255, 0.88)` with `backdrop-filter: blur(24px)` and outline `1px solid rgba(13, 148, 136, 0.15)`. Shadow: `0 12px 32px -4px rgba(15, 23, 42, 0.06), 0 4px 12px -2px rgba(15, 23, 42, 0.03)`.
- **Level 3 — Focus Popover & Dynamic Sensor Calibrator:** Background of pure `#FFFFFF` with `backdrop-filter: blur(8px)`. Shadow: `0 20px 40px -8px rgba(15, 23, 42, 0.10)`.

### Chromatic Ambient Halos
Active sensors project an atmospheric, low-opacity glow corresponding to their sensor domain:
- **Thermal Active:** `box-shadow: 0 0 24px 0 rgba(244, 63, 94, 0.12)`
- **Bioimpedance Active:** `box-shadow: 0 0 24px 0 rgba(217, 119, 6, 0.12)`
- **Optical NIRS Active:** `box-shadow: 0 0 24px 0 rgba(139, 92, 246, 0.12)`

## Shapes

The design system employs **Roundedness Level 2 (0.5rem base radius)**, striking an intentional balance between clinical software structure and body-worn garment soft-goods.

### Scale Application
- **Base Components (`rounded` / 8px):** Form input fields, checkboxes, segmented tab controls, and real-time sparkline chart surfaces.
- **Card Containers (`rounded-lg` / 16px):** Metric data cards, sensor stream wrappers, calibration accordions, and participant notes.
- **Structural Overlays (`rounded-xl` / 24px):** Primary modals, dynamic health overview sheets, and wear-placement guidance panels.
- **Pill Shells (`rounded-full` / 9999px):** Signal quality indicators, modality chips, action tags, and interactive button shapes.

## Components

### Buttons
- **Primary Tactile Button:** Pill-shaped (`rounded-full`), height 44px. Background: `#0D9488`; text `#FFFFFF` (`label-lg`). Box-shadow: `0 2px 8px rgba(13, 148, 136, 0.25)`. Transitions smoothly on press with a subtle inset transform (`scale(0.98)`).
- **Secondary Glass Button:** Border `1px solid rgba(13, 148, 136, 0.3)`. Background `rgba(204, 251, 241, 0.4)`. Text `#0D9488`.
- **Ghost Action:** Text `#1E293B`, background transparent; hover state initiates `rgba(241, 245, 249, 0.8)`.

### Sensor Status Rings (Signal Quality Levels)
Circular signal telemetry rings (diameter 36px) visualize real-time hardware electrode contact and data transmission confidence:
- Three concentric radial arcs communicate impedance quality: 
  - Outer: Skin contact resistance.
  - Middle: Signal-to-noise ratio ($SNR$).
  - Inner Core: Sampling rate consistency.
- **Optimal Connection:** Calming Medical Teal (`#0D9488`) with subtle pulse animation.
- **Marginal / Adjust Position:** Warm Electrical Gold (`#D97706`).
- **Lead Detached / Offline:** Soft Slate Gray (`#94A3B8`).

### Modality Badges & Pill Chips
- Height 24px, radius `rounded-full`, horizontal padding 10px.
- **Thermal Pill:** Coral background (`#FFE4E6`), text `#F43F5E`, paired with an 8px circular temperature dot.
- **Bioimpedance Pill:** Amber background (`#FEF3C7`), text `#D97706`, paired with a micro-frequency frequency wave icon.
- **Optical NIRS Pill:** Violet background (`#EDE9FE`), text `#8B5CF6`, paired with a dual-wavelength spectrum glyph.

### Frosted Metric Cards
- Background: `rgba(255, 255, 255, 0.75)` with `backdrop-filter: blur(16px)` and perimeter border `1px solid rgba(226, 232, 240, 0.80)`.
- Internal layout: Top row holds Sensor Title (`label-md`) and Channel Status Ring. Middle displays primary numeric value (`data-display`) with baseline unit (`label-lg`). Bottom section contains an uninterrupted real-time sparkline graph styled in the respective sensor's accent color.

### Form Inputs & Checkboxes
- **Input Fields:** Height 44px, radius 8px, background `rgba(255, 255, 255, 0.9)`, border `1px solid #CBD5E1`. On focus: `border-color: #0D9488`, `box-shadow: 0 0 0 3px rgba(20, 184, 166, 0.15)`.
- **Clinical Checkboxes:** 20px $\times$ 20px, radius 6px. Checkmark uses white stroke on `#0D9488` fill.

### Structured Accordions
- Used for hardware calibration logs and daily session breakdowns.
- Collapsed: Clean 1px border (`#E2E8F0`) with trailing chevron; header displays participant timestamp and modal badge.
- Expanded: Reveals underlying raw multi-channel data plots along with participant-reported symptoms without modal displacement.