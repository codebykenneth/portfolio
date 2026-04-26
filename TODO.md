# Add Read More to Services - TODO

## Plan
- [x] Step 1: Create `services-web.html` — detailed page for Web Development (dark theme, navbar, content, skills, CTA, footer)
- [x] Step 2: Create `services-design.html` — detailed page for Graphic Design
- [x] Step 3: Create `services-marketing.html` — detailed page for Digital Marketing
- [x] Step 4: Update `index.html` — point the 3 "Read More" links to new pages and replace placeholder descriptions
- [x] Step 5: Verify all pages link correctly and match the dark theme

## Summary of Changes

### New Files Created
1. **services-web.html** — Web Development detail page
   - Fixed navbar with back button linking to `#services`
   - Service description, highlight quote, technologies grid (React, JS/TS, CSS, Performance)
   - Quote section, CTA with contact/portfolio links, footer

2. **services-design.html** — Graphic Design detail page
   - Fixed navbar with back button linking to `#services`
   - Service description, highlight quote, design expertise grid (Brand Identity, UI/UX, Marketing, Print)
   - Quote section, CTA with contact/portfolio links, footer

3. **services-marketing.html** — Digital Marketing detail page
   - Fixed navbar with back button linking to `#services`
   - Service description, highlight quote, marketing expertise grid (SEO, Social Media, Paid Ads, Content)
   - Quote section, CTA with contact/portfolio links, footer

### Updated Files
4. **index.html** — Services section updated
   - Web Development: description changed from Lorem ipsum to real text, link changed from `#` to `services-web.html`
   - Graphic Design: description changed from Lorem ipsum to real text, link changed from `#` to `services-design.html`
   - Digital Marketing: description changed from Lorem ipsum to real text, link changed from `#` to `services-marketing.html`

### Design Consistency
- All new pages match the existing `readmore.html` dark theme style
- Colors: `--primary: #00d4ff`, `--bg-dark: #0a0a0a`, `--bg-card: #151515`
- Typography: Poppins font family
- Layout: Fixed navbar, centered container, card-based sections
- Responsive: Mobile-friendly with media queries at 768px

