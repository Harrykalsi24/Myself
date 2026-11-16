---
name: Atelier Moss
colors:
  surface: '#f6fcea'
  surface-dim: '#d6dccb'
  surface-bright: '#f6fcea'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f6e5'
  surface-container: '#eaf0df'
  surface-container-high: '#e4ead9'
  surface-container-highest: '#dfe5d4'
  on-surface: '#181d13'
  on-surface-variant: '#434842'
  inverse-surface: '#2c3227'
  inverse-on-surface: '#edf3e2'
  outline: '#747871'
  outline-variant: '#c4c8bf'
  surface-tint: '#51634f'
  primary: '#1c2d1c'
  on-primary: '#ffffff'
  primary-container: '#324331'
  on-primary-container: '#9caf98'
  inverse-primary: '#b8ccb4'
  secondary: '#4c6548'
  on-secondary: '#ffffff'
  secondary-container: '#cbe8c3'
  on-secondary-container: '#50694c'
  tertiary: '#242b1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#3a4131'
  on-tertiary-container: '#a5ad98'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e8cf'
  primary-fixed-dim: '#b8ccb4'
  on-primary-fixed: '#0f1f10'
  on-primary-fixed-variant: '#3a4b39'
  secondary-fixed: '#ceeac6'
  secondary-fixed-dim: '#b3ceab'
  on-secondary-fixed: '#0a2009'
  on-secondary-fixed-variant: '#354d32'
  tertiary-fixed: '#dee6cf'
  tertiary-fixed-dim: '#c1c9b4'
  on-tertiary-fixed: '#171e10'
  on-tertiary-fixed-variant: '#424939'
  background: '#f6fcea'
  on-background: '#181d13'
  surface-variant: '#dfe5d4'
typography:
  headline-hero:
    fontFamily: Barlow Condensed
    fontSize: 128px
    fontWeight: '800'
    lineHeight: 112px
    letterSpacing: -0.03em
  headline-hero-mobile:
    fontFamily: Barlow Condensed
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 68px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system embodies an editorial director's portfolio aesthetic: high-fashion print publishing meets architectural digital layout. The tone is deliberate, quiet yet commanding, and unapologetically typographically-driven. It serves creative directors, contemporary fashion houses, curatorial institutions, and visionary studios seeking an elevated showcase.

The design movement is **Refined Brutalism blended with Editorial Sophistication**. It avoids chaotic raw brutalism in favor of structural clarity, hair-thin divider rules, massive condensed display typography, tactile paper-toned backgrounds, and minimal pill-shaped interactions. Visual tension is achieved by placing monumental, condensed letterforms behind or intertwined with foreground photographic silhouettes and understated metadata.

## Colors

The palette is derived from organic paper stock and deep botanical moss tones, creating an ambient canvas that is warm, tactile, and non-fatiguing:

- **Primary (`#324331`)**: Deep forest moss. Used for dominant display typography, solid pill primary CTAs, hairline borders, and structural branding marks.
- **Secondary (`#5A7355`)**: Mid-tone lichen olive. Applied to secondary interactive states, secondary badge borders, and subdued display accents.
- **Tertiary (`#D1D9C3`)**: Pressed lichen tint. Serves as container borders, input field surfaces, subtle grid rules, and hover fills.
- **Neutral (`#DFE5D4`)**: Muted sage parchment. Acts as the primary viewport canvas and baseline paper background.
- **Dark Neutral / Charcoal (`#1F241E`)**: Near-black botanical charcoal used strictly for body copy, micro-captions, and metadata to ensure effortless contrast against the sage background.
- **Paper Surface (`#E8ECE0`)**: Elevated surface for floating project cards, modals, and flyout navigation drawers.

## Typography

The typographic hierarchy creates theatrical tension between **Barlow Condensed** and **Hanken Grotesk**:

- **Barlow Condensed** (Uppercase Only for Headlines): Massive, architectural, and tightly tracked. Used for hero impact statements, category designations, and section monument markers. Leading is intentionally tighter than font size (0.88–0.95 ratio) to produce a cohesive typographic wall reminiscent of Swiss posters and high-fashion spreads.
- **Hanken Grotesk**: Modern, precise, and humanistic sans-serif. Delivers exceptional legibility for editorial copy, long-form project summaries, indexes, and navigational labels.
- **Micro-labels and Metadata**: Set with all-caps tracking (`letterSpacing: 0.06em - 0.1em`) to mimic archival catalog tags, gallery numbers, and pagination.

## Layout & Spacing

The layout is structured around an asymmetrical 12-column fluid grid governed by architectural division rules and generous margins:

- **Desktop (1024px+)**: 12 columns with 3rem outer margins and 1.5rem gutters. Sections are divided by visible 1px hairline borders (`#D1D9C3`). Off-center arrangements place dominant display lettering across columns 4–12, while introductory editorial copy anchors columns 1–3.
- **Tablet (768px - 1023px)**: 8 columns with 2rem margins and 1.25rem gutters. Hero copy drops below the primary display lettering.
- **Mobile (under 768px)**: 4 columns with 1.25rem outer margins and 1rem gutters. Monumental typography adapts using `-mobile` sizing tokens, breaking gracefully across stacked lines.
- **Structural Lines**: Use crisp 1px borders to ground floating elements, separate list items in client rosters, and frame editorial credits.

## Elevation & Depth

Visual depth avoids heavy artificial drop shadows, relying instead on structural layering and flat paper planes:

- **Zero Heavy Shadows**: No blurred black drop shadows. All structural depth is established through tonal contrast, border outlines, and physical silhouette cutouts overlapping type layers.
- **Flat Paper Layering**: Elevated items (modals, dropdown drawers, hover overlays) use the `#E8ECE0` paper shade bounded by a 1px solid `#324331` or `#D1D9C3` border.
- **Directional Grounding Shadow (Figure Ground)**: In photography treatments (such as cutout portraits or editorial lookbook assets standing on the page), an ultra-soft radial ambient contact shadow (`rgba(31, 36, 30, 0.18)` blur 28px, spread -6px) anchors the subject firmly to the canvas.

## Shapes

The design system employs a distinct **pill-shaped interactive language (`roundedness: 3`)** juxtaposed against **crisp, orthogonal structural frames (0px corners)**:

- **Buttons & Pills**: Buttons, badges, and tag chips are fully pill-shaped (`9999px` / `rounded-full`). This softens the brutalist framework and provides an organic, tactile signature.
- **Cards & Media Frames**: Portfolio project thumbnails, imagery containers, and grid borders maintain razor-sharp or minimal 2px corners, emphasizing raw editorial framing.
- **Icon Badges & Counters**: Small circular badges (`rounded-full`) frame clean line icons, index numbers, or status indicators.

## Components

### Buttons
- **Primary Pill**: Background `#324331`, text `#DFE5D4`, fully rounded (`rounded-full`). Padding: `0.75rem 1.75rem`. Accompanied by a right-facing directional arrow icon or trailing dot.
- **Ghost / Outline Pill**: Background transparent, border 1px solid `#324331`, text `#324331`. Hover switches fill to `#324331` and text to `#DFE5D4` with smooth ease transitions.

### Badge & Icon Counters
- Minimal, editorial circular badges (`width: 44px, height: 44px`) framed in 1px `#D1D9C3` or `#324331` hairline borders.
- Center-aligned line icons (thin 1.25px stroke) or monospace indices (`01`, `02`, `03`) set in `label-md`.

### Editorial List Items
- Stacked rows separated by 1px solid `#D1D9C3` hairlines.
- Each row contains index number, project name in `headline-sm`, client metadata in `body-sm`, and an optional right-aligned pill tag.
- Hover reveals a floating thumbnail preview that tracks cursor movement.

### Cards & Work Items
- Flat paper surfaces (`#E8ECE0`) framed with 1px `#D1D9C3` lines.
- Imagery features strict 4:5 or 16:9 editorial crops with high contrast desaturated tones, warming gently on hover.

### Inputs & Form Fields
- Understated underline or borderless pill container with bottom hairline (`#324331`).
- Clean placeholder text set in `Hanken Grotesk` regular italic with minimal uppercase floating label.

### Navigational Header
- Transparent bar floating at the top canvas.
- Left-aligned geometric logo mark (e.g. four-point rosette or cluster).
- Centered minimal inline text links with active state underlined by a 1px moss stroke.
- Right-aligned outline pill CTA button ("Get in touch" or "Available for Q3").