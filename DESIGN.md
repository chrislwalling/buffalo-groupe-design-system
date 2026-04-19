# Buffalo Groupe Design System

## 1. Visual Theme & Atmosphere

Buffalo Groupe's design philosophy centers on **escape and aspiration**. The brand evokes high-end hospitality, sport, and real estate experiences that feel simultaneously accessible and premium. The visual system emphasizes movement, clarity, and emotional resonance.

Core brand promise: **"We create escape."**

Design ethos:
- Premium yet relatable
- Active and relaxed in equal measure
- Cinematic and aspirational
- Grounded in natural environments (water, sky, landscape)
- Clean, uncluttered layouts that breathe

The brand attracts competitive, relationship-driven teams. Designs should feel purposeful, not decorative.

---

## 2. Color Palette & Roles

Buffalo Groupe uses a curated 5-color system with semantic intent and psychological weight.

### Primary Colors

| Name | Hex | RGB | CMYK | Role | Usage |
|------|-----|-----|------|------|-------|
| **Midnight Sky** | #081733 | 8, 23, 51 | 85, 55, 0, 80 | Primary action, dark surfaces | CTAs, dark backgrounds, high-contrast text |
| **Lapis** | #4A78BD | 74, 120, 188 | 60, 36, 0, 26 | Secondary action, medium tone | Links, accent elements, supporting CTAs |
| **New Denim** | #38445B | 56, 68, 91 | 38, 25, 0, 64 | Tertiary, calm authority | Body backgrounds, card surfaces, subtle accents |

### Supporting Colors

| Name | Hex | RGB | CMYK | Role | Usage |
|------|-----|-----|------|------|-------|
| **Sea Glass** | #C9DEDB | 201, 222, 219 | 10, 0, 1, 13 | Light, approachable | Light backgrounds, hover states, soft contrast |
| **Amber** | #E5A824 | 229, 168, 36 | 0, 27, 84, 10 | Accent, energy, warmth | Highlights, badges, success states, calls-to-action on dark |

### Extended Palette Rules

- **100% opaque, solid color fields** are primary; screens and gradients allowed only when brand feel is maintained
- Never introduce new colors outside this 5-color system without leadership approval
- Contrast must meet WCAG AA minimum (4.5:1 for text)
- On dark backgrounds, use Lapis or Amber for readable links; Midnight Sky text should be on light surfaces only
- Sea Glass is intentionally soft; use for non-critical UI surfaces or breathing room

---

## 3. Typography

Buffalo Groupe uses two typeface families with clear hierarchical roles.

### Typeface Stack

| Family | Role | Weights | Case Rule |
|--------|------|---------|-----------|
| **Cutive** | Headlines (H1, H2) | Regular only | Lowercase, excluding proper nouns |
| **Work Sans** | Body, subheadings, UI labels | Regular to Bold | Sentence case or lowercase; avoid heavier than Bold |

### Type Hierarchy

| Level | Family | Size | Weight | Case | Line Height | Usage |
|-------|--------|------|--------|------|-------------|-------|
| **H1** | Cutive | 124px (web) | Regular | lowercase | 1.1 | Page titles, hero statements |
| **H2** | Work Sans | 56px | Semibold | lowercase | 1.2 | Section headings |
| **H3** | Work Sans | 26px | Medium | lowercase | 1.3 | Subheadings |
| **H4** | Work Sans | 16px | Medium | lowercase | 1.4 | Card titles, label text |
| **Body** | Work Sans | 16px | Regular | Sentence case | 1.6 | Paragraph text, descriptions |
| **Small** | Work Sans | 14px | Regular | Sentence case | 1.5 | Fine print, captions, metadata |
| **Button** | Work Sans | 16px | Bold | Sentence case | 1.0 | Call-to-action text |

### Typography Rules

- Cutive headlines must use a range of **Regular to Bold** for remaining copy; anything heavier overpowers Cutive
- Work Sans is flexible in weight and case; use Regular for body, Bold for emphasis
- Maintain generous line-spacing for readability; avoid cramped vertical rhythm
- Cutive should never appear in all caps
- When italics are needed, italicize Work Sans, not Cutive
- Letter spacing is normal; do not increase artificially unless for decorative effect

---

## 4. Component Styling

### Buttons

#### Primary Button (Dark, High Action)
- Background: Midnight Sky (#081733)
- Text: White (#FFFFFF)
- Border: None
- Padding: 12px 24px (web: consistent touch target ~44px min height)
- Border radius: 4px (subtle, not rounded)
- Font: Work Sans Bold, 16px
- Hover: Slightly lighter Midnight Sky or Lapis overlay (80% opacity darken)
- Active: Darker shade or shift to Lapis

#### Secondary Button (Amber Accent)
- Background: Amber (#E5A824)
- Text: Midnight Sky (#081733)
- Border: None
- Padding: 12px 24px
- Border radius: 4px
- Font: Work Sans Bold, 16px
- Hover: Darker Amber or slight opacity reduction
- Active: Midnight Sky background with Amber text

#### Ghost Button (On Light Background)
- Background: Transparent
- Text: Midnight Sky (#081733)
- Border: 1px solid Midnight Sky
- Padding: 12px 24px
- Border radius: 4px
- Font: Work Sans Bold, 16px
- Hover: Light Sea Glass background or Midnight Sky text opacity

### Cards & Surfaces

- Default background: White or Sea Glass (for breathing room)
- Border: 1px solid New Denim (#38445B) at 10% opacity, or no border
- Border radius: 4px (consistent with button styling)
- Box shadow: Subtle (0 2px 8px rgba(8, 23, 51, 0.08))
- Padding: Minimum 24px internal spacing
- Hover state: Slight shadow increase (0 4px 16px rgba(8, 23, 51, 0.12)) or light Sea Glass tint

### Input Fields

- Border: 1px solid New Denim (#38445B) at 20% opacity
- Border radius: 4px
- Background: White
- Text color: Midnight Sky (#081733)
- Placeholder: New Denim at 50% opacity
- Focus state: Border color shifts to Lapis (#4A78BD), shadow 0 0 0 3px Lapis at 15% opacity
- Padding: 12px 16px
- Font: Work Sans Regular, 16px

### Navigation & Links

- Link color: Lapis (#4A78BD)
- Link hover: Darker Lapis or underline appears
- Link active: Midnight Sky, underline persistent
- Navigation items: Work Sans Medium or Semibold, 16px
- Active nav item: Amber underline or background tint

---

## 5. Layout & Spacing

### Spacing Scale

Buffalo Groupe uses an 8px-based spacing scale:

| Scale | Value | Usage |
|-------|-------|-------|
| xs | 4px | Fine-grained internal spacing (icon padding, tight layouts) |
| sm | 8px | Component internal spacing (button padding, card gaps) |
| md | 16px | Content spacing (section margins, gaps between items) |
| lg | 24px | Section spacing, padding on containers |
| xl | 32px | Large section breaks, hero padding |
| xxl | 48px | Full-bleed spacing, page-level margins |
| xxxl | 64px | Between major content blocks |

### Grid & Responsive

- **Desktop**: 12-column grid, 1200px max width, 24px gutters
- **Tablet**: 8-column grid, 100% width, 16px gutters
- **Mobile**: 4-column grid, 100% width, 16px gutters, 16px side margins

### Whitespace Philosophy

- Embrace negative space; do not fill every gap
- Breathing room around focal elements increases impact
- Minimum 24px padding on all card/container edges
- Vertical rhythm: Maintain consistent line-height spacing between sections
- Hero sections and escape-themed imagery benefit from generous surrounding whitespace

---

## 6. Depth & Elevation

Buffalo Groupe uses a subtle shadow system to create surface hierarchy without theatrical depth.

### Shadow Scale

| Level | Shadow | Usage |
|-------|--------|-------|
| None | None | Flat surfaces, backgrounds |
| Elevation 1 | 0 2px 8px rgba(8, 23, 51, 0.08) | Cards, subtle lift |
| Elevation 2 | 0 4px 16px rgba(8, 23, 51, 0.12) | Hover states, active cards |
| Elevation 3 | 0 8px 24px rgba(8, 23, 51, 0.16) | Modals, dropdowns, overlays |
| Elevation 4 | 0 12px 32px rgba(8, 23, 51, 0.20) | Full-page modals, top-layer elements |

### Layering Rules

- Shadows use Midnight Sky as base (never black)
- Avoid blurred or soft-focus elements unless intentional photography effect
- Modals and overlays use semi-transparent dark overlay (Midnight Sky 20-40% opacity)
- Stacked cards maintain consistent shadow depth; do not increase shadow for nested cards

---

## 7. Do's and Don'ts

### Do's

- Use the full 5-color palette; each color has intent
- Maintain spacing and breathing room; less is more
- Pair Cutive headlines with Work Sans body for visual hierarchy
- Isolate hero imagery from backgrounds to layer other elements
- Use the Archway and Stars as accent elements, not structural fills
- Create candid, natural photography when featuring people; avoid staging
- Apply monochromatic screening to photos for brand consistency
- Keep button styling consistent (4px radius, bold text)
- Test dark text on Sea Glass and light text on Midnight Sky for readability
- Reference the "We create escape" brand promise in visual composition

### Don'ts

- Do not mix typefaces outside Cutive and Work Sans without approval
- Do not use colors outside the 5-color palette
- Do not stretch, rotate, or alter the Buffalo Groupe logo
- Do not use branded colors in unapproved logo versions
- Do not turn the logo at angles (exception: Archway may be rotated 45°, 90°, or 180° only)
- Do not use the Archy-B pattern more than once per visible area
- Do not repeat the 3-star grouping outside the logo; stars must remain grouped
- Do not create gradients that break brand feel (use solid color fields primarily)
- Do not introduce new border-radius values; keep consistent 4px
- Do not apply heavy shadows or drop effects; subtlety is strength
- Do not crop or modify the Archway's exact curve
- Do not stage photography; candid and natural is on-brand
- Do not create busy layouts; embrace negative space

---

## 8. Responsive Behavior

### Breakpoints

| Device | Width | Grid | Gutters | Side Margin |
|--------|-------|------|---------|------------|
| **Desktop** | 1200px+ | 12-column | 24px | 32px |
| **Tablet** | 768px–1199px | 8-column | 16px | 24px |
| **Mobile** | 320px–767px | 4-column | 16px | 16px |

### Responsive Collapse Strategy

- **Typography**: H1 scales from 124px (desktop) to 48px (mobile)
- **Components**: Buttons maintain minimum 44px touch target on mobile
- **Cards**: Single-column layout below 768px; 2-column at tablet, 3+ at desktop
- **Navigation**: Hamburger menu below 768px; horizontal nav at desktop
- **Images**: Full-width containers at mobile, constrained at desktop; maintain aspect ratio
- **Spacing**: Reduce xxl/xxxl spacing by 50% on mobile; maintain md/lg minimum

### Touch Target Sizes

- Minimum button height: 44px
- Minimum link/tap area: 44x44px
- Spacing between tappable elements: Minimum 8px

---

## 9. Logo & Brand Elements

### Logo Variants

Buffalo Groupe provides six approved logo versions:

1. **No stars, no tagline** – Minimal, primary mark
2. **With stars, no tagline** – Brand stars included
3. **With stars and tagline** – Full brand identity
4. **With stars and values** – Values statement version
5. **With locations** – Geographic footprint version
6. **Special-use archway** – Leadership approval only; custom color allowed

### Logo Rules

- Maintain spacing equal to the height of the "rise" around all versions
- Exception: When rise is bottom-aligned with page edge, standard clearance not required
- Never stretch, distort, or alter proportions
- Never rotate the logo (fixed orientation only)
- Never use unapproved color variants

### Supporting Graphics

#### Stars
- Always appear as a grouped set of 3; never lone stars or larger groups
- May be used as accent only in areas where stars do not already appear in logo
- Available in all 5 brand colors

#### Archway
- Primary visual brand element; evokes "doorway towards escape"
- Circular top mimics the arching tagline in logo design
- May be rotated 45°, 90°, or 180° only
- May be filled with images, cropped, made shorter/taller (curve must remain exact)
- May be repeated as a group
- Use in any branded color; translucent or solid when overlaid on photos

#### Archy-B Pattern
- Stacked archway pairs form "B" for Buffalo in negative space
- At 45° rotation, creates pattern with footstep-like movement
- Use sparingly; limit to one appearance per visible area
- Maintain 45° angle; do not rotate further
- Works in any branded color or translucent over images
- Optional; not required in every deliverable

---

## 10. Photography Guidance

### Subject Matter

- Photos should evoke **escape** whenever possible
- Images of sport, hospitality, real estate—high-end yet relatable
- People: candid and natural, never staged
- Mix of active to relaxed subjects appropriate
- Landscape and environmental photography central to brand

### Composition Techniques

#### Isolation from Background
- Remove backgrounds to layer with brand elements for depth
- Mix isolated subjects with full-image, full-opacity photos
- Avoid overly busy layouts; use restraint

#### Transparency & Monochromatic Effects
- Screen photos back (reduce opacity) for monochromatic effect
- Use as repeating technique for brand consistency
- Can be combined with full-opacity photos

### Lighting & Mood

- Golden hour and natural light preferred
- High-end hospitality and luxury resort aesthetics
- Avoid harsh, overly saturated, or artificial lighting
- Cinematic and aspirational tone

---

## 11. Agent Prompt Guide

When requesting UI generation, reference this section for quick color and component direction.

### Quick Color Reference

```
Primary actions & dark surfaces: Midnight Sky (#081733)
Secondary actions & links: Lapis (#4A78BD)
Tertiary & calm surfaces: New Denim (#38445B)
Light, approachable backgrounds: Sea Glass (#C9DEDB)
Accent, energy, highlights: Amber (#E5A824)
Text on light: Midnight Sky
Text on dark: White or Amber
```

### Quick Component Reference

```
Primary button: Midnight Sky background, white text, 4px radius, Work Sans Bold
Secondary button: Amber background, Midnight Sky text, 4px radius, Work Sans Bold
Cards: White/Sea Glass, 1px New Denim border (10% opacity), Elevation 1 shadow
Inputs: White, 1px border, Lapis focus state with subtle shadow
Links: Lapis, hover underline, active Midnight Sky
Headlines: Cutive, lowercase, Regular to Bold
Body: Work Sans, 16px, Regular, line-height 1.6
```

### Typical Prompt Template

"Build a [PAGE TYPE] using Buffalo Groupe's design system. Use Cutive headlines in lowercase paired with Work Sans body copy. Apply the 5-color palette: Midnight Sky for primary actions, Lapis for links, New Denim for surfaces, Sea Glass for light backgrounds, Amber for accents. Include [SPECIFIC ELEMENTS]. Maintain 24px spacing, 4px border radius on components, and subtle shadows. Embrace whitespace and the escape/aspiration theme."

---

## 12. Brand Voice in Design

Buffalo Groupe's visual language should reinforce the brand promise: **"We create escape."**

- **Competitive yet accessible**: Premium without gatekeeping
- **Movement and energy**: Dynamic layouts, breathing room, intentional flow
- **Clarity and purpose**: Every element earns its place
- **Aspiration through relation**: Show luxury as attainable, not distant
- **Natural and candid**: Authenticity over perfection
- **Emotional resonance**: Design choices should feel right, not arbitrary

When designing, ask: "Does this feel like escape? Does it feel like a premium experience we'd want to return to?"

---

**Last Updated**: April 2026
**Format**: DESIGN.md for AI agents (Google Stitch compatible)
**Version**: 1.0
