# Premium Rosemary Oil Landing Page UX/UI Blueprint

## 1) Creative Direction Summary

**Goal:** Build a high-converting, long-form landing page for a premium rosemary hair growth oil brand, inspired by the Rheyl aesthetic (earthy, editorial, wellness-luxury).

**Core conversion strategy:**
1. Hook with a clear pain-point headline + premium product visual in first viewport.
2. Establish credibility quickly (press logos, ingredient quality, comparison table).
3. Reinforce desire through ingredient education + social proof.
4. Minimize purchase friction via a focused product widget with trust elements.
5. Keep CTAs consistent and visible throughout the page.

---

## 2) Visual Style & Brand Identity

### Color Palette (Earthy-Premium)

```css
:root {
  --color-forest-900: #103B2C;   /* Primary brand: deep forest green */
  --color-forest-700: #1C5A43;   /* Secondary dark green for blocks */
  --color-sage-300:   #B9C9B8;   /* Soft accent backgrounds */
  --color-sage-500:   #7E9D86;   /* Icon/line accent */
  --color-cream-50:   #F8F4EA;   /* Page background (instead of white) */
  --color-cream-100:  #EFE7D8;   /* Alternating section background */
  --color-copper-500: #B87444;   /* Primary CTA base */
  --color-copper-600: #9D6037;   /* CTA hover */
  --color-gold-muted: #C8A66A;   /* Optional premium highlight */
  --color-text-main:  #183229;   /* Default text */
  --color-text-soft:  #496257;   /* Supporting text */
  --color-success:    #2F8A57;   /* Checkmarks, trust indicators */
  --color-danger:     #C65A5A;   /* X marks in comparison table */
}
```

### Typography

- **Headings (serif):** `"Cormorant Garamond", "Playfair Display", serif`
  - H1: 64/68 desktop, 44/50 tablet, 34/40 mobile
  - H2: 44/52 desktop, 34/40 mobile
  - Letter spacing: slight negative on large headings (`-0.02em`)
- **Body/UI (sans):** `"Inter", "Manrope", "Helvetica Neue", sans-serif`
  - Body: 18/30 desktop, 16/26 mobile
  - UI labels/buttons: 14–16, semibold

### Shapes, Motifs, and Surface Language

- **Corner radius standard:** `24px` for cards, media, tables; `999px` for pill CTAs.
- **Section transitions:** soft organic wave dividers between major sections.
- **Shadow style:** low-contrast, natural (`0 8px 30px rgba(16, 59, 44, 0.08)`).
- **Borders:** 1.5px subtle green-tinted borders for premium clinical feel.

---

## 3) Page Architecture (Long-Form Outline + Suggested Copy)

## Section 01 — Announcement Bar (Top)

**Purpose:** Immediate value framing and promo clarity.

- Left: `Dermatologist-Inspired Formula`
- Center: `Free Shipping on 2+ Bottles`
- Right: `60-Day Money-Back Guarantee`

**Microcopy style:** short, confidence-driven, benefit-led.

---

## Section 02 — Above-the-Fold Hero (Split Layout)

### Layout
- **Desktop:** 2-column (45/55)
- **Left:** Hero product bottle visual with floating ingredient callouts.
- **Right:** Headline, subhead, CTA cluster, press logos.

### Left Side Content
- High-resolution bottle render on cream backdrop with shadow pedestal.
- Floating callout chips:
  - `100% Pure Rosemary`
  - `Cold-Pressed`
  - `Hexane-Free`
  - `Clinically Selected Blend`

### Right Side Copy
- **Eyebrow:** `TARGETED SCALP & FOLLICLE SUPPORT`
- **H1:** `Say Goodbye to Thinning Hair.`
- **Subhead:** `A potent rosemary-powered formula designed to support fuller-looking, healthier hair from root to tip.`
- **Primary CTA:** `Start Your Growth Ritual`
- **Secondary CTA (ghost):** `View Ingredients`
- **Reassurance row:** `✓ 60-day guarantee  ✓ Free shipping over $45  ✓ Made in small batches`

### “As Seen In” Row
- Label: `AS SEEN IN`
- Monochrome logos: Vogue, Harper’s Bazaar, Elle, Byrdie (or available equivalents).

---

## Section 03 — Feature Grid (3-Column)

**Purpose:** Fast articulation of key outcomes.

### Grid cards (icon + title + short line)
1. **Stimulates Follicles**
   - Copy: `Rosemary and circulation-support ingredients help energize roots for visibly denser-looking growth.`
2. **Deep Hydration**
   - Copy: `Nutrient-rich oils help soften dry scalp and reduce brittleness from repeated styling.`
3. **Sulfate-Free**
   - Copy: `No harsh sulfates, no parabens—just a cleaner formula designed for long-term scalp health.`

**Style notes:** line-art icons, 24px radius, soft sage tint background.

---

## Section 04 — “What’s Inside” Ingredient Deep-Dive

**Purpose:** Education + trust through ingredient transparency.

### Section heading copy
- **H2:** `What’s Inside Your Growth Ritual`
- **Body:** `Three powerhouse ingredients. One intentional formula.`

### 3 Vertical Cards with “Learn More” Toggle

1. **Rosemary Oil**
   - Short copy: `Traditionally used to support scalp circulation and healthier-looking growth cycles.`
   - Learn more (expand): mechanism, sourcing, aroma profile.
2. **Castor Oil**
   - Short copy: `Rich in fatty acids to lock in moisture and improve strand softness and shine.`
   - Learn more: hydration benefits, viscosity notes, best-use routine.
3. **Biotin**
   - Short copy: `Helps reinforce the appearance of stronger, less fragile strands over time.`
   - Learn more: role in hair-care formulations and consistency expectations.

**Interaction:** accordions or collapsible content inside each card.

---

## Section 05 — “Us vs. Them” Comparison Table

**Purpose:** Competitive differentiation near mid-page decision point.

### Headline
- `Why Ours Outperforms Drugstore Oils`

### Columns
- Column A: `Our Rosemary Oil`
- Column B: `Standard Drugstore Brands`

### Criteria Rows
- Purity
- Hexane-Free
- Organic Ingredients
- Price-per-ounce

### Suggested values
- **Our Rosemary Oil:** checkmarks for first three; clear transparent value for price-per-ounce.
- **Drugstore:** red X where typical standards are missing; vague/hidden pricing note.

**Design notes:**
- Use subtle striping and sticky header on mobile.
- Check icons in `--color-success`; X icons in `--color-danger`.

---

## Section 06 — “Shroom Coffee Style” Product Widget (Checkout Block)

**Purpose:** Primary conversion engine.

### Layout
- Left: Product image gallery (bottle + lifestyle image + texture shot).
- Right: Purchasing details.

### Right Panel Content
- Product title: `Rosemary Hair Growth Oil`
- Ratings: `★★★★★ 4.9 (3,842 reviews)`
- Price block:
  - One-time: `$42`
  - Subscribe & Save: `$34` (`Save 19%` badge)
- **Toggle:** `Subscribe & Save` vs `One-Time Purchase`
- Quantity selector and CTA:
  - CTA text: `Add to Cart — $34`
- Trust badges row:
  - `60-Day Money-Back Guarantee`
  - `Free Shipping`
  - `Secure Checkout`

**Add urgency microcopy:** `Selling out weekly — next restock in 12 days.`

---

## Section 07 — Social Proof Stack

### 07A. User Gallery (4 Columns)

**Purpose:** Visual lifestyle proof in real contexts.

- Four vertical image cards (application ritual, scalp massage, vanity setup, before/after texture).
- Overlay tags: `Week 3`, `Night Routine`, `No Greasy Residue`, `Real Customer`.

### 07B. Testimonial Slider (Text-Based)

- **Headline:** `Real Results From Real Routines`
- 3–6 rotating testimonial cards with name, age range, concern, and quote.

**Sample quote:**
`“By week five, I noticed less shedding on wash day and my hairline looked visibly fuller.” — Maya R., 34`

---

## Section 08 — FAQ + Final CTA

**Purpose:** Remove final objections and recover hesitations.

### FAQ Prompts
- `How long until I see visible results?`
- `Will this work for color-treated hair?`
- `How often should I apply it?`
- `Does it leave residue?`
- `Can I use it with other scalp treatments?`

### Closing CTA Block
- **Headline:** `Ready to Regrow With Confidence?`
- **Subhead:** `Start your daily ritual today with zero-risk, 60-day guarantee.`
- **CTA:** `Start Your Growth Ritual`

---

## 4) UI Component Specs (Developer-Ready)

## Buttons

```css
.btn-pill {
  border-radius: 999px;
  padding: 14px 28px;
  font: 600 15px/1 "Inter", sans-serif;
  letter-spacing: 0.01em;
  transition: background-color .25s ease, transform .2s ease, box-shadow .25s ease;
}

.btn-primary {
  background: var(--color-copper-500);
  color: #fff;
  box-shadow: 0 8px 20px rgba(184, 116, 68, 0.25);
}

.btn-primary:hover {
  background: var(--color-copper-600);
  transform: translateY(-1px);
}

.btn-secondary {
  background: transparent;
  color: var(--color-forest-900);
  border: 1.5px solid var(--color-forest-900);
}
```

## Cards

```css
.card {
  border-radius: 24px;
  background: #fff;
  border: 1px solid rgba(16, 59, 44, 0.12);
  box-shadow: 0 8px 30px rgba(16, 59, 44, 0.08);
  padding: 28px;
}
```

## Wave Divider

- Use SVG section separators with top or bottom wave path.
- Keep wave amplitude subtle to preserve premium tone.

## Inputs / Toggles

- 48px minimum touch height.
- Toggle with clear selected state and price delta visible in label.

---

## 5) Layout, Spacing, and Responsiveness

### Global Container
- Max width: `1200px`
- Horizontal padding: `24px` mobile, `40px` tablet, `64px` desktop

### Vertical Rhythm (Premium whitespace)
- Section top/bottom spacing:
  - Desktop: `120px`
  - Tablet: `88px`
  - Mobile: `64px`
- Internal card spacing: `20–28px`
- Grid gaps:
  - Desktop: `24–32px`
  - Mobile: `16px`

### Breakpoints
- Mobile: `<768px`
- Tablet: `768–1023px`
- Desktop: `>=1024px`

### Mobile Behavior Priorities
1. Collapse hero into stacked layout (copy first, product second or vice versa after testing).
2. Turn comparison table into horizontal scroll cards.
3. Keep sticky bottom mini-CTA (`Start Your Growth Ritual`).

---

## 6) Conversion-Focused Copy Blocks (Ready to Plug In)

### Core Promise Options
- `Clinically inspired, naturally powered hair growth support.`
- `Scalp-first care for visibly fuller, healthier-looking hair.`

### Benefit bullets (short form)
- `Supports healthier growth cycles`
- `Helps reduce visible shedding`
- `Nourishes dry, stressed scalps`
- `Lightweight, non-greasy finish`

### Risk reversal
- `Try it for 60 days. Love your results, or get your money back.`

### Urgency lines
- `Small-batch production. Limited monthly inventory.`
- `Current batch almost sold out.`

---

## 7) Accessibility & UX Quality Checklist

- Color contrast minimum WCAG AA for all text/interactive states.
- Buttons and toggles keyboard accessible with visible focus rings.
- All ingredient toggles accessible via ARIA-expanded states.
- Product and user gallery images include descriptive alt text.
- Motion effects subtle and reduced under `prefers-reduced-motion`.

---

## 8) Optional Enhancement Ideas

- **Progressive sticky CTA** after 30% scroll depth.
- **Before/After slider** module near testimonials.
- **Quiz entry point:** `Find Your Hair Growth Routine` for lead capture.
- **Routine bundle upsell** inside widget (`Oil + Scalp Massager`).

