# Buffalo Groupe Design System

This repository contains the design system and brand guidelines for **Buffalo Groupe branded work only**. Use this for internal tools, dashboards, marketing materials, and any asset that represents Buffalo Groupe itself.

**Not for client work.** Client projects use their own brand guidelines. See [When Not to Use This](#when-not-to-use-this) below.

---

## What's Inside

- **DESIGN.md** - Machine-readable design system for AI agents (colors, typography, components, spacing, imagery)
- **BG_BrandGuidelines_jy_v1.pdf** - Original brand guidelines from design team (reference)

---

## Quick Start

### For Claude/Claude Code Workflows

1. Reference DESIGN.md in your prompt:

```
Build a dashboard using the DESIGN.md in this repo. 
Use Cutive headlines, Work Sans body copy. 
Apply the 5-color palette (Midnight Sky, Lapis, New Denim, Sea Glass, Amber).
Maintain 24px spacing and 4px button radius.
```

2. Or include it as context:

```
Using Buffalo Groupe's design system (DESIGN.md):
- Build [SPECIFIC COMPONENT/SECTION]
- Use Midnight Sky or New Denim for primary surfaces
- Use Amber for highlights and important data
- Maintain 24px padding and 4px border radius
- Keep layouts clean and breathing
```

### For Any BG Project

Drop DESIGN.md into the root of any Buffalo Groupe branded project repo. Then reference it when iterating: "Update this button to match DESIGN.md primary button style."

---

## DESIGN.md Overview

DESIGN.md is structured in 12 sections for AI agents to read and apply:

| Section | What It Covers | Why It Matters |
|---------|----------------|-----------------|
| Visual Theme | Escape, aspiration, premium-yet-relatable philosophy | Emotional grounding for design decisions |
| Color Palette | 5 colors (Midnight Sky, Lapis, New Denim, Sea Glass, Amber) with roles | Consistent color application across projects |
| Typography | Cutive (headlines) + Work Sans (body) with full hierarchy | Readable, on-brand type scales |
| Components | Buttons, cards, inputs, navigation with states | Reusable patterns for consistency |
| Layout & Spacing | 8px scale, grid rules, whitespace philosophy | Coherent visual rhythm |
| Depth & Elevation | Shadow system for surface hierarchy | Subtle, not theatrical depth |
| Do's and Don'ts | 10 dos, 12 don'ts extracted from brand guidelines | Guard against common mistakes |
| Responsive Behavior | Breakpoints, collapse strategy, touch targets | Mobile-first consistency |
| Logo & Brand Elements | 6 logo versions, Archway, Stars, Archy-B rules | Correct brand asset usage |
| Photography | Subject matter, composition, isolation/transparency | On-brand imagery approach |
| Agent Prompt Guide | Quick color reference and template prompts | Fast reference for iteration |
| Brand Voice | Emotional design direction | Design that feels like Buffalo Groupe |

**For detail**, open DESIGN.md and jump to any section.

---

## When to Use This

Use Buffalo Groupe's design system for:

- Internal dashboards and tools
- New business pitch materials (case studies, competitive analyses)

---

## When NOT to Use This

**Do not use this for client work.** Each client uses their own brand guidelines.

Examples of client-specific work (use their brand guidelines instead):
- Client PR materials (use their brand guidelines)
- Client marketing collateral (use their guidelines)
- Anything with a client logo or brand promise

**Exception:** If building an internal Buffalo Groupe tool that *happens* to be used by a client (like a client-facing dashboard), check with leadership. Usually the tool itself is BG-branded (our header, our colors) while the content/data is client-specific.

---

## How to Update This

Brand evolves. When it does:

1. **Color changes**: Update the color table in DESIGN.md section 2, plus quick reference in section 11
2. **Typography updates**: Update section 3 hierarchy table
3. **Component redesigns**: Update section 4 with new button/card/input specs
4. **Logo/graphic changes**: Update section 9
5. **New guardrails**: Add to Do's and Don'ts in section 7

After updating, commit with a clear message:
```
git commit -m "Update primary button color from Midnight Sky to Lapis per brand refresh"
```

**Notify the team:** When DESIGN.md changes, let people know. It's the single source of truth.

---

## Using DESIGN.md with Claude

### Pattern 1: Initial Build

```
I'm building [PAGE/FEATURE] for Buffalo Groupe.
This repo includes DESIGN.md with our full design system.
Build the [COMPONENT] using DESIGN.md guidelines:
- Headline in Cutive
- Content in Work Sans with appropriate color highlights
- Midnight Sky or New Denim background
- 24px padding
- Subtle shadow
```

### Pattern 2: Consistency Check

```
This [COMPONENT] doesn't feel right. Reference DESIGN.md section 4 (Component Styling).
Update it to match the [COMPONENT TYPE] spec exactly.
```

### Pattern 3: New Feature

```
Adding [NEW SECTION/FEATURE].
Design it using DESIGN.md: 
- Color palette section 2
- Layout/spacing section 5
- Component styling section 4
Keep the escape/aspiration vibe (section 1).
```

---

## Files in This Repo

```
buffalo-groupe-design-system/
├── DESIGN.md                              # AI-readable design system (main file)
├── BG_BrandGuidelines_jy_v1.pdf           # Original brand guidelines (reference)
└── README.md                              # This file
```

---

## Questions?

If DESIGN.md doesn't cover something:

1. Check the original PDF (`BG_BrandGuidelines_jy_v1.pdf`)
2. Ask leadership for clarification
3. Update DESIGN.md for next time
4. Document the exception and why

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | April 2026 | Initial DESIGN.md extracted from brand guidelines PDF |

---

## How This Gets Used

**Typical workflow:**

1. You start a new Buffalo Groupe branded project
2. Clone this repo or copy DESIGN.md to your project root
3. When building UI with Claude or Claude Code, reference DESIGN.md in your prompt
4. Consistency happens automatically because the design system is explicit
5. When brand guidelines change, update DESIGN.md once; everything else flows from that

No more debating "should this button be Midnight Sky or Lapis?" The answer is in DESIGN.md.

---

**Last Updated:** April 2026
