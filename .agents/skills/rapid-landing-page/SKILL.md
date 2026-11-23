---
name: rapid-landing-page
description: Builds bespoke, editorial-grade live single-file HTML/Tailwind conversion redesigns in builds/<brand>/ enforcing taste extraction, strict anti-AI guardrails, and tactile craft, then commits and pushes to GitHub Pages.
---

# Rapid Landing Page Skill — High-Craft Editorial & CRO Engine

Build bespoke, high-converting single-file HTML/Tailwind landing page redesigns in `builds/<brand>/index.html` that look and feel like world-class design studios (e.g., Collins, Instrument, Metalab) built them. **NEVER produce generic, cookie-cutter "AI-made" layouts.** 

Every build must strictly follow this 3-phase workflow before deployment.

---

## CORE PHILOSOPHY: ZERO AI-SLOP
The modern web is drowning in recognizable AI templates: generic purple/blue gradients, glowing background blurs, emoji bullet points, centered 3-card icon grids, and fake press logos. 

Our client demos cut through the noise because they feel human, curated, tactile, and uncompromisingly premium.

---

## PHASE 1: LIVE BENCHMARK & TASTE EXTRACTION (MANDATORY BEFORE CODING)

Before writing any HTML/CSS, research 2–3 best-in-class live websites in the prospect's vertical using web search or browser inspection. Reference industry benchmarks for taste:
- **D2C Skincare & Wellness**: `aesop.com`, `glossier.com`, `olipop.com`, `graza.co`, `seed.com`
- **Luxury & Editorial Fashion**: `ssense.com`, `toteme.com`, `bottegaveneta.com`, `kith.com`, `rowingblazers.com`
- **Hardware & Industrial Tech D2C**: `teenage.engineering`, `ridge.com`, `nothing.tech`, `analogue.co`
- **Premium B2B / SaaS**: `linear.app`, `raycast.com`, `stripe.com`, `vercel.com`

### Required Output: `builds/<brand>/DESIGN_TOKENS.md`
Extract and document the design tokens into `builds/<brand>/DESIGN_TOKENS.md` containing:
1. **Typography Scale & Contrast**:
   - Primary pairing: Editorial serif (e.g., Cormorant Garamond, Instrument Serif, Newsreader) + grotesque sans (e.g., Inter, Space Grotesk, Plus Jakarta Sans), OR technical industrial monospace (e.g., JetBrains Mono, Space Mono).
   - Display headlines: Tight letter tracking (`tracking-[-0.03em]` or `-0.04em`), intentional line heights (`leading-[1.05]`).
   - Micro-labels: Uppercase metadata chips (`10px`–`11px`, wide tracking `0.12em`–`0.2em`, font-mono or font-sans medium).
2. **Color & Surface Restraint**:
   - **90% Dominant Canvas**: Warm neutral / textured alabaster (`#faf8f5`, `#f5f4f0`), raw linen, or deep obsidian (`#0a0b0d`, `#111215`).
   - **8% Typography & Architecture**: Deep ink, dark charcoal (`#1a1a1a`), or off-white (`#eae8e4`).
   - **2% Intentional Accent**: Exactly ONE deliberate accent color drawn from the product itself (e.g., vermilion, olive drab, safety orange, champagne gold). No rainbows.
3. **Grid & Structural Rhythm**:
   - Asymmetric 12-column editorial grids.
   - `1px` structural hairline borders (`border-collapse` architectural look with borders like `#e5e2dc` or `#222428`).
   - Generous negative space (`py-20` to `py-32`, `gap-8` to `gap-16`).
   - Sticky split-screen product storytelling (media locked while story scrolls, or horizontal filmstrip inspection)—never repetitive 3-column centered card grids.

---

## PHASE 2: STRICT ANTI-AI-SLOP GUARDRAILS

Every build is audited against these strict prohibitions:

### Explicitly Banned Tropes:
1. ❌ **NO Default AI Gradients**: Never use default Tailwind `from-blue-600 via-indigo-600 to-purple-600`, or purple/pink neon glowing background blur orbs (`blur-3xl rounded-full`).
2. ❌ **NO Emoji Icons**: Never use emojis (⚡, 🚀, 🔥, 💡, 💎, ✨) inside feature lists, bullet points, headlines, or CTAs.
3. ❌ **NO Fake Press Logo Bars**: Never insert generic text strings like "VOGUE · GQ · FORBES · ELLE" unless citing real, verifiable press links.
4. ❌ **NO Repetitive 3-Card Drop Shadow Grids**: Ban `grid-cols-3` containing identical centered rounded boxes with `shadow-lg rounded-xl` and circular icon backgrounds.
5. ❌ **NO Generic Stock Stock Images**: Never use low-resolution or generic business handshake / smiling stock models.

### Mandatory High-Craft Alternatives:
- **Curated Editorial Photography**: Use real, high-resolution lifestyle/editorial photography via Unsplash/Pexels with specific mood parameters (warm daylight, directional editorial shadow, natural 35mm film grain, or clean industrial studio lighting).
- **Geometric SVG Marks**: Inline vector icons crafted with uniform `1.25px` or `1.5px` stroke width, `stroke-linecap="round"`, and crisp geometric lines.
- **Architectural Table / Hairline Layouts**: Use structural divider lines (`divide-y`, `divide-slate-200` or `divide-[#222]`) and editorial column offsets.

---

## PHASE 3: INTERACTIVE CRAFT & DEPLOYMENT

### Tactile Interactions & Motion
Build `builds/<brand>/index.html` with tactile, responsive interactions:
1. **Interactive Variant / Bundle Drawer or Selector**:
   - Custom-styled radio chips or toggle matrix with instant price, discount calculation, and active state animation.
   - Real-time stock status counter or batch allocation tag.
2. **Subtle Custom CSS Easing**:
   - Use custom cubic-bezier curves for fluid micro-interactions:
     ```css
     transition: all 400ms cubic-bezier(0.16, 1, 0.3, 1);
     ```
3. **Sticky Mobile Ergonomics**:
   - Fixed thumb-zone bottom bar with crisp typography, selected tier indicator, and zero layout shift.
4. **Editorial Lookbook / Carousel / Tab Switcher**:
   - Lightweight zero-dependency JS tab switcher or thumbnail sync that feels native and responsive.

### Git Automation & Deployment Workflow
Whenever a brand demo is authored in `builds/<brand>/index.html`:
1. Stage and commit both the design token spec and the build:
   ```bash
   git add builds/<brand>/
   git commit -m "feat(builds): craft bespoke editorial demo for <brand>"
   ```
2. Push to GitHub:
   ```bash
   git push origin main
   ```
3. Return the verified live GitHub Pages preview URL:
   `https://Feelharsh7.github.io/client-demos/builds/<brand>/`
4. Update the root `index.html` showcase directory with the new demo card.

---

## PHASE 4: 60-SECOND LOOM OUTREACH SCRIPT

Provide a high-impact 60-second video walkthrough script customized to the prospect's brand:
1. **0:00 - 0:15 (The Hook & Respect)**:  
   *"Hey [Name], love the aesthetic you've curated at [Brand]. I was studying your mobile customer journey and noticed a couple of friction points in the checkout transition that are likely suppressing your conversion rate."*
2. **0:15 - 0:45 (The Proof-of-Work & Rebuild)**:  
   *"Rather than sending an unsolicited critique, I took your product and rebuilt your hero and mobile purchase experience live here [Open https://Feelharsh7.github.io/client-demos/builds/<brand>/]. Notice how the tactile bundle selector, editorial typography hierarchy, and sticky 1-click flow eliminate hesitation without cheapening the brand."*
3. **0:45 - 1:00 (Zero-Friction Next Step)**:  
   *"If your team wants the code or wants us to run a 72-hour conversion sprint on another flagship page, let me know. Either way, hope the live preview sparks some immediate CRO wins for your next drop!"*
