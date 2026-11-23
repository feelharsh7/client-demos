---
name: rapid-landing-page
description: Builds a live single-file HTML/Tailwind conversion redesign in builds/ for recording a 60-second Loom audit
---

# Rapid Landing Page Skill

Inspect a target prospect's current landing page or Shopify storefront, architect a high-converting responsive redesign, build a single-file `builds/<brand>/index.html` using Tailwind CSS, and launch a local preview server for recording a 60-second Loom audit video.

## Objective
Provide unmistakable upfront proof-of-work that cuts through cold outreach noise by delivering a clickable, live preview showing the prospect what their store or landing page looks like after a 72-hour conversion overhaul.

---

## Workflow Instructions

### Step 1: Target Inspection
- Review the prospect's live website URL.
- Extract brand identity markers:
  - Primary, secondary, and accent colors
  - Typography style (sans-serif, modern serif, display fonts)
  - Core value proposition and headline messaging
  - Hero imagery / product media links
  - Current conversion blockers (buried call-to-action, lack of social proof, cluttered navigation, weak benefit hierarchy)

### Step 2: Build `builds/<brand>/index.html`
- Create a dedicated folder `builds/<brand>/`.
- Author a modern, fully responsive, standalone `index.html` featuring:
  - **Tailwind CSS CDN**: `<script src="https://cdn.tailwindcss.com"></script>` with tailored config for brand colors and fonts.
  - **Optimized Hero Section**: Clear H1 benefit-driven headline, sub-headline answering "why now", star ratings/press badge proof, high-contrast primary CTA button ("Get Started" / "Shop Now"), and mobile-first layout.
  - **Social Proof / Trust Badges**: Clean customer logos, testimonial quotes, or rating summaries placed above the fold or immediately below the hero.
  - **Feature / Benefit Grid**: 3 concise benefit blocks with crisp icons and clear problem-solution messaging.
  - **Comparison Section (Before vs. After)**: Highlighting the upgrade from legacy friction to the new streamlined experience.
  - **Sticky Mobile CTA Bar**: Fixed bottom bar on mobile screens for friction-free conversion.

### Step 3: Launch Local Preview Server
- Launch a local preview server from the workspace root or the brand directory:
  - e.g., `python -m http.server 8080 --directory builds/<brand>` or PowerShell web server.
- Verify that the page loads properly at `http://localhost:8080`.

### Step 4: 60-Second Loom Audit Script Preparation
Provide a short 60-second Loom recording structure:
1. **0:00 - 0:15 (The Hook)**: "Hey [Name], love what you're doing with [Brand]. I was checking out your mobile store and noticed [Specific UX friction] was likely costing you conversions."
2. **0:15 - 0:45 (The Teardown & Live Rebuild)**: "Instead of just pointing it out, I went ahead and rebuilt your hero section and mobile checkout flow here live [Show live preview at localhost / hosted preview]. Notice how the clear CTA and trust hierarchy removes buyer friction."
3. **0:45 - 1:00 (Zero-Friction CTA)**: "If you'd like the code or want us to implement this in 72 hours, let me know. Either way, hope this gives you an easy CRO win!"
