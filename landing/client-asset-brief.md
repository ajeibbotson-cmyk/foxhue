# Foxhue Landing Page — Client Asset Brief
## SEO & Website Audit Campaign

This document lists all assets needed to complete the landing page for the Foxhue Meta advertising campaign. Placeholder content has been used throughout the page where real assets are required.

---

## Priority Assets (Blocking Launch)

### Phone Number
- [ ] **Confirm business phone number** — currently shown as "TBC" across:
  - `12-cta-banner.html` — call-to-action button
  - `13-map-contact.html` — contact details
  - `14-footer-cta.html` — footer contact strip
  - All `<a href="tel:TBC">` links need updating once confirmed

---

## Photography

### Hero Image
- [ ] **Hero / banner photograph**
  - Recommended: 1920 × 1080px minimum (2560 × 1440px ideal for retina)
  - Format: JPEG or WebP
  - Suggested subject: team at work, desk with laptop/analytics, or relevant lifestyle shot
  - Should feel: professional, approachable, Oxfordshire-rooted
  - Placed in: `01-hero.html` (or equivalent hero section)

### Team Photo / Headshot
- [ ] **Team photo or principal headshot**
  - Recommended: 800 × 800px (square crop works well), 1200 × 800px for landscape
  - Format: JPEG or WebP, with transparent background PNG as alternative
  - Placed in: About/trust sections

---

## Social Proof

### Testimonial Details
Placeholder testimonials use fictional names and businesses. Replace with real quotes once available.

- [ ] **Testimonial 1**
  - Client full name:
  - Business name and location:
  - Quote (2–4 sentences, specific results preferred):
  - Result metric (e.g. "enquiries up 2x in 6 weeks"):
  - Headshot (optional): 200 × 200px, square crop, JPEG

- [ ] **Testimonial 2**
  - Client full name:
  - Business name and location:
  - Quote:
  - Result metric:
  - Headshot (optional): 200 × 200px

- [ ] **Testimonial 3**
  - Client full name:
  - Business name and location:
  - Quote:
  - Result metric:
  - Headshot (optional): 200 × 200px

### Client / Trust Logos
- [ ] **Client logos or trust badges** (if available)
  - Format: SVG preferred, PNG with transparent background accepted
  - Dimensions: height 40–60px (width variable)
  - Usage: trust strip beneath hero or testimonials section

---

## Gallery — Audit Report Screenshots

The gallery section (`11-gallery.html`) uses illustrated placeholder mockups showing simulated report data. Replace with real screenshots from completed Foxhue audits.

- [ ] **Screenshot 1 — Audit cover / overall SEO score page**
  - Recommended: 800 × 600px minimum
  - Format: JPEG, PNG, or WebP
  - Content: overall health score, summary metrics

- [ ] **Screenshot 2 — Page speed / Core Web Vitals section**
  - Recommended: 800 × 600px minimum
  - Content: LCP, FID, CLS scores, device comparisons

- [ ] **Screenshot 3 — Keyword gap analysis**
  - Recommended: 800 × 600px minimum
  - Content: keyword rankings table, opportunity flags

- [ ] **Screenshot 4 — Competitor benchmarking**
  - Recommended: 800 × 600px minimum
  - Content: domain authority, keyword overlap, backlink comparison

- [ ] **Screenshot 5 — Priority actions roadmap**
  - Recommended: 800 × 600px minimum
  - Content: prioritised to-do list (HIGH / MEDIUM / LOW)

- [ ] **Screenshot 6 — Monthly tracking report**
  - Recommended: 800 × 600px minimum
  - Content: traffic growth chart, ranking improvements over time

> Note: Anonymise any client data before using real report screenshots. Blur or replace business names if necessary.

---

## Maps & Location

### Google Maps Embed
- [ ] **Google Maps embed code** for Foxhue's Bicester location
  - Steps to generate:
    1. Go to [maps.google.com](https://maps.google.com)
    2. Search for the business address
    3. Click Share → Embed a map → Copy HTML
  - Paste the `<iframe>` code into `13-map-contact.html` in place of the `.foxhue-map__placeholder` div
  - Set `width="100%"` and remove fixed height (the CSS handles sizing)
  - Add `title="Foxhue office location — Bicester, Oxfordshire"` to the iframe for accessibility

---

## Pricing Confirmation

- [ ] **Confirm final pricing** for audit packages:
  - Free Audit — currently listed as £0 / free
  - Full Audit — currently listed as "From £497"
  - Audit + Implementation — currently listed as "From £1,497"
  - Amend in `08-pricing.html` once confirmed

---

## Meta Ad Campaign Assets

These are needed for the Meta (Facebook/Instagram) ad creative that drives traffic to this landing page — not the landing page itself, but recorded here for campaign completeness.

- [ ] **Primary ad image(s)** — 1080 × 1080px (square) and/or 1200 × 628px (landscape)
- [ ] **Ad copy** — primary text, headline, description, CTA label
- [ ] **Ad account access** — ensure the correct Meta Business account is connected
- [ ] **UTM parameters** — define UTM source/medium/campaign for tracking

---

## Technical

- [ ] **Form integration** — the booking form (section to be built) needs to connect to:
  - CRM, email, or booking tool (Calendly, HubSpot, Mailchimp, etc.)
  - Confirm preferred lead capture method
- [ ] **Analytics setup** — confirm Google Analytics 4 property ID for the landing page
- [ ] **Meta Pixel** — confirm Meta Pixel ID to add to `<head>` of assembled page
- [ ] **Domain / URL** — confirm final URL where the landing page will be published

---

## Asset Delivery

Please send all assets to: **hello@foxhue.com** with the subject line `Landing Page Assets`.

Preferred formats:
- Images: JPEG, PNG, or WebP (no BMP, TIFF, or HEIC)
- Logos: SVG or PNG with transparent background
- Documents: PDF or Google Docs link

Questions? Contact [hello@foxhue.com](mailto:hello@foxhue.com).
