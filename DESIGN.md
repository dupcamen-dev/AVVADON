---
name: Sacred Dread
colors:
  surface: '#fff8f3'
  surface-dim: '#e3d8cb'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fdf2e4'
  surface-container: '#f7ecdf'
  surface-container-high: '#f2e7d9'
  surface-container-highest: '#ece1d3'
  on-surface: '#201b13'
  on-surface-variant: '#444748'
  inverse-surface: '#353027'
  inverse-on-surface: '#faefe1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c9c6c5'
  secondary: '#5f5f58'
  on-secondary: '#ffffff'
  secondary-container: '#e2e0d7'
  on-secondary-container: '#64635c'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#410003'
  on-tertiary-container: '#f04440'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e5e2da'
  secondary-fixed-dim: '#c9c6be'
  on-secondary-fixed: '#1c1c17'
  on-secondary-fixed-variant: '#474741'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb3ac'
  on-tertiary-fixed: '#410003'
  on-tertiary-fixed-variant: '#930010'
  background: '#fff8f3'
  on-background: '#201b13'
  surface-variant: '#ece1d3'
typography:
  display-xl:
    fontFamily: Bodoni Moda
    fontSize: 120px
    fontWeight: '900'
    lineHeight: 100px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.4'
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  dense-cluster: 4px
---

## Brand & Style

The design system is built upon a philosophy of "Sacred Dread"—a synthesis of Biblical Horror and Avant-Garde Luxury. It aims to evoke an emotional response that is simultaneously transcendent and unsettling, mimicking the experience of an "angelic" encounter that is more terrifying than peaceful.

The visual style is a deliberate mix of **Editorial Minimalism** and **Digital Brutalism**. It utilizes expansive, "divine" white space contrasted against dense, chaotic clusters of imagery. Key visual motifs include:
- **Glitchy intentionality:** Overlapping text elements, sliced imagery, and offset containers that suggest a breaking of the physical realm.
- **Divine Iconography:** Fine-line illustrations of eyes, wings, and feathers used as functional anchors.
- **Cinematic Tension:** High-value contrast and dramatic crops of "Be Not Afraid" style entities integrated into the UI.

## Colors

The palette is anchored in the duality of light and shadow. 
- **Off-white (#F4F1E8):** Representing "Divine Light," this is the primary background color. It feels aged and parchment-like, rather than a sterile digital white.
- **Deep Charcoal/Black (#0C0C0C):** Representing "Dread," used for massive typography and heavy structural blocks.
- **Blood Red (#D32F2F):** A visceral accent used sparingly for calls to action or critical warnings, suggesting sacrifice or ritual.
- **Muted Gold/Stone (#7A7267):** Used for secondary details and hairline borders to maintain the luxury perfume aesthetic.

## Typography

The typography strategy relies on extreme scale and stylistic friction.
- **The Serif (Bodoni Moda):** Used for massive, overlapping headlines. These should feel authoritative and ancient. Letter-spacing is tight to create a "wall of text" effect.
- **The Sans (Space Grotesk):** Provides the brutalist edge. It is used for secondary information and body copy, often set in all-caps to maintain a sense of urgency and command.
- **Layout Logic:** Typography is permitted to break the grid. Headlines may be partially obscured by images or sliced by container edges to reinforce the glitch aesthetic.

## Layout & Spacing

This design system uses a **Deconstructed Fluid Grid**. While a 12-column foundation exists for alignment, elements are encouraged to sit "off-pixel" or overlap adjacent columns.

- **The Void:** Large areas of white space (margins up to 120px) are used to isolate premium products, creating a sense of sacred importance.
- **The Cluster:** Information-dense areas (like product notes or ingredients) use a tight 4px spacing, creating a visual tension against the expansive void.
- **Reflow:** On mobile, the overlapping elements flatten into a vertical stack, but maintain the "sliced" appearance through intentional negative margins and asymmetrical image crops.

## Elevation & Depth

Hierarchy is achieved through **Tonal Stacking** and **Slicing**, rather than traditional shadows.
- **Flat Depth:** Use hard-edged, solid black containers against the off-white background to create immediate foreground/background separation.
- **Z-Index Play:** Images of "divine entities" should overlap text, while smaller UI labels (like scent notes) should appear to be "pinned" to the very top layer.
- **The "Glitch" Slice:** Instead of elevation shadows, use 1px hairlines or 2px solid black offsets to "lift" elements from the page.

## Shapes

The shape language is strictly **Sharp (0)**. There are no rounded corners in the design system. Every container, button, and image crop must have 90-degree angles to maintain a harsh, brutalist, and architectural feel. 

Asymmetrical clipping masks (triangular or jagged "shards") can be used for images to mimic broken glass or wings.

## Components

- **Buttons:** Large, rectangular blocks with solid black backgrounds and white all-caps text. On hover, they should invert to blood red. Text should be slightly off-center to feel "unstable."
- **Input Fields:** Single bottom-border only (1px charcoal). Labels sit inside the field in small-caps and move up on focus.
- **Cards:** No borders or shadows. Cards are defined by their background color (alternating between Off-white and Charcoal) and the dramatic scale of the typography within them.
- **Scent Note Chips:** Small, square-edged boxes with fine-line botanical or "Biblical" icons (eyes, thorns).
- **Navigation:** A minimal top bar with "Glitch" transitions. Instead of traditional icons, use alchemical-style symbols for "Cart," "Search," and "Profile."
- **The "Ritual" Toggle:** Any switches or toggles should use hard-edged sliders that snap into place with high-contrast color changes.