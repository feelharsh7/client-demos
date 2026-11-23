---
name: rapid-landing-page
description: Builds bespoke, editorial-grade live single-file HTML/Tailwind conversion redesigns in builds/<brand>/ enforcing live taste extraction, the 10-Point Design System Rubric, and strict anti-AI guardrails, then commits and pushes to GitHub Pages.
---

# Rapid Landing Page Skill — High-Craft Editorial & CRO Engine

Build bespoke, high-converting single-file HTML/Tailwind landing page redesigns in `builds/<brand>/index.html` that look and feel like world-class design studios (e.g., Collins, Studio Freight, Instrument, Metalab) built them for $25,000+. **NEVER produce generic, cookie-cutter "AI-made" layouts.**

Every build must strictly comply with the **10-Point Design System Rubric** before deployment.

---

## THE 10-POINT EDITORIAL DESIGN SYSTEM RUBRIC (MANDATORY AUDIT)

Every demo must pass this 10-point rubric before committing:

1. **Spacing (Macro & Micro Rhythm)**: Enforce an 8pt spatial baseline. Eliminate cramped `py-8` blocks. Use generous macro whitespace (`py-24` to `py-36` / 96px–144px between major narrative beats) so layouts breathe with luxury confidence. Micro-spacing bound to strict 4px/8px/12px/16px intervals.
2. **Visual Hierarchy (3-Tier Eye-Scan Order)**: First 3-second scan must be effortless.
   - Tier 1: Oversized tight-tracked display headlines (`clamp(44px, 5.5vw, 88px)`, `letter-spacing: -0.035em`, `line-height: 1.04`).
   - Tier 2: Calm editorial body copy (`16px–18px`, `line-height: 1.65`, opacity 0.75–0.85).
   - Tier 3: Crisp uppercase monospace technical metadata (`10px–11px`, `letter-spacing: +0.12em` to `+0.18em`).
3. **Visual Harmony (90/8/2 Surface Restraint)**:
   - 90% Matte Canvas: Warm unbleached stone/parchment (`#F6F5F1`, `#FFFEF2`, `#FAF8F5`) or deep matte obsidian (`#090A0C`, `#0D0E11`).
   - 8% High-Contrast Ink: Deep charcoal/ink (`#15241C`, `#1C1C1C`, `#EDEDED`).
   - 2% Single Intentional Accent: One deliberate product-derived hue (chartreuse, raw umber, bio-mint).
   - Zero AI gradients, no glowing neon blur orbs, zero emojis. All icons must be custom inline monochrome SVGs with uniform `1.25px` stroke width and round caps. Photography must be curated, high-resolution editorial stills with unified tonal grading.
4. **Layout & Alignment (Architectural Grid)**: Ban repetitive centered 3-column rounded card grids (`rounded-2xl shadow-lg`). Use asymmetric 12-column editorial grids (7-column media narrative / 5-column sticky acquisition engine), razor-sharp `1px solid` hairline structural borders (`border-collapse` architectural look), and strict optical baseline alignment.
5. **Innovation (Non-Template Mechanics)**: Replace generic e-commerce clichés (fake "Vogue/Forbes" logo bars, countdown timers, generic review cards) with bespoke, category-specific interactive mechanics:
   - Tactile bundle selectors with physical refill economics.
   - Split-screen sticky product storytelling.
   - Monogramming and custom flacon/apparel customizers.
   - Clinical strain traceability matrix and unboxing diagrams.
6. **Proportion & Scale**: Dramatic, intentional scale contrast. Pair monumental hero typography and full-bleed editorial imagery directly against ultra-fine `1px` hairlines and compact `10px` monospace technical specs.
7. **Emphasis (Single Focal Anchor)**: Exactly ONE undeniable focal point per viewport. Strip competing secondary badges and clutter popups; allow the product silhouette and primary CTA to dominate.
8. **Proximity (Gestalt Grouping)**: Tight micro-spacing (`4px–8px`) between tightly coupled elements (label + price + variant selector), versus wide macro-spacing (`96px–144px`) separating distinct narrative chapters.
9. **Movement (Editorial Physics)**: Luxury cubic-bezier motion physics:
   ```css
   transition: all 450ms cubic-bezier(0.16, 1, 0.3, 1);
   ```
   Smooth sticky scroll choreography and zero layout shift on drawer/variant transitions.
10. **Context & Adaptability (Vertical Authenticity)**: Authentically fit the vertical's real-world buyer psychology:
    - *Modern DTC (Graza/Olipop)*: Tactile, bold typography, clear bundle unit economics, mobile thumb-zone ATC.
    - *Quiet Luxury (Toteme/Aesop)*: Strict 0px radius, warm parchment linen, architectural hairlines, literary editorial typography, bespoke concierge routing.
    - *Scientific Retention (Seed/Ritual)*: Reusable glass welcome vessel vs. compostable refill pouches, biological assay tables, 1-click SMS portal.

---

## 3-PHASE SPRINT WORKFLOW

### PHASE 1: LIVE BENCHMARK & TASTE EXTRACTION (MANDATORY BEFORE CODING)
Before writing any HTML/CSS, inspect 2–3 vertical market leaders using the integrated browser (e.g., `graza.co`, `toteme.com`, `aesop.com`, `seed.com`).
Document `builds/<brand>/DESIGN_TOKENS.md` with:
- Palette & Surface Restraint (90/8/2 hex values).
- Typography Scale (editorial serif, grotesque, and monospace pairing).
- Structural rhythm and component mechanics.

### PHASE 2: STRICT ANTI-AI-SLOP AUDIT
Verify that:
- ❌ NO default Tailwind blue/indigo/purple gradients or background glowing blur orbs.
- ❌ NO emojis in features, buttons, or bullet points.
- ❌ NO generic "Vogue / GQ / Forbes" text bars.
- ❌ NO centered 3-card drop shadow grids.
- ✅ Uses curated high-resolution editorial photography and uniform `1.25px` SVG marks.

### PHASE 3: INTERACTIVE CRAFT & DEPLOYMENT
1. Author standalone single-file `builds/<brand>/index.html`.
2. Commit and push:
   ```bash
   git add builds/<brand>/ index.html
   git commit -m "feat(builds): deploy bespoke editorial rebuild for <brand>"
   git push origin main
   ```
3. Deliver the verified live GitHub Pages URL:
   `https://feelharsh7.github.io/client-demos/builds/<brand>/`
4. Update the root `index.html` studio index.
