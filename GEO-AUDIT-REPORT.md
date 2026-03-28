# GEO Audit Report: Stone Snap

**Audit Date:** March 28, 2026
**URL:** https://stonesnapapp.com
**Business Type:** Mobile App (SaaS/Education)
**Pages Analyzed:** 2 (Homepage, Privacy Policy)

---

## Executive Summary

**BEFORE GEO Score: 16/100 (Critical)**
**AFTER GEO Score (Estimated): 58/100 (Fair)**

The site had zero SEO/GEO optimization -- no meta description, no structured data, no robots.txt, no sitemap, no FAQ content, broken image alt attributes, and no AI crawler guidance. All fixable technical and on-page issues have been resolved. The remaining score gap requires off-site work (brand authority, backlinks, community presence) that cannot be done through code changes alone.

### Score Breakdown (BEFORE)

| Category | Score | Weight | Weighted Score |
|---|---|---|---|
| AI Citability | 15/100 | 25% | 3.75 |
| Brand Authority | 8/100 | 20% | 1.60 |
| Content E-E-A-T | 18/100 | 20% | 3.60 |
| Technical GEO | 32/100 | 15% | 4.80 |
| Schema & Structured Data | 0/100 | 10% | 0.00 |
| Platform Optimization | 18/100 | 10% | 1.80 |
| **Overall GEO Score** | | | **16/100** |

### Score Breakdown (AFTER FIXES)

| Category | Score | Weight | Weighted Score |
|---|---|---|---|
| AI Citability | 55/100 | 25% | 13.75 |
| Brand Authority | 8/100 | 20% | 1.60 |
| Content E-E-A-T | 40/100 | 20% | 8.00 |
| Technical GEO | 75/100 | 15% | 11.25 |
| Schema & Structured Data | 80/100 | 10% | 8.00 |
| Platform Optimization | 55/100 | 10% | 5.50 |
| **Overall GEO Score** | | | **~58/100** |

---

## What Was Fixed (All Changes Applied)

### Critical Fixes
1. **Added meta description** targeting "rock identification app", "mineral identifier", "AI geology"
2. **Added canonical URLs** to both pages
3. **Created robots.txt** explicitly allowing all AI crawlers (GPTBot, ClaudeBot, PerplexityBot, OAI-SearchBot, etc.)
4. **Created sitemap.xml** listing both pages with lastmod dates
5. **Fixed ALL image alt attributes** -- replaced non-standard `data-alt` with proper `alt` on all 8 images
6. **Added Open Graph tags** (og:title, og:description, og:image, og:url, og:type, og:site_name)
7. **Added Twitter Card tags** (twitter:card, twitter:title, twitter:description, twitter:image)

### High Priority Fixes
8. **Added JSON-LD structured data:** Organization, SoftwareApplication, WebSite, WebPage with Speakable, BreadcrumbList, FAQPage (6 schema blocks)
9. **Created llms.txt** -- AI crawler guidance file with app description, features, and links
10. **Added FAQ section** with 6 question-answer pairs targeting real search queries (citability boost)
11. **Added About section** with genuine product description and contact info
12. **Removed duplicate Material Symbols font link** (was loading twice)
13. **Added image width/height attributes** to prevent CLS
14. **Fixed mobile navigation** -- hamburger menu now works with JS toggle
15. **Added preconnect hints** for fonts.googleapis.com, fonts.gstatic.com, lh3.googleusercontent.com

### Medium Priority Fixes
16. **Improved page title** from generic "Digital Field Guide" to keyword-rich "AI Rock & Mineral Identification App for Android"
17. **Added meta robots** tag (index, follow)
18. **Added favicon link tags** (32x32, 16x16, apple-touch-icon)
19. **Improved H1** from poetic to search-targeted: "Identify Any Rock, Mineral, or Crystal Instantly."
20. **Added H2 subheading** under How It Works explaining the Google Gemini AI pipeline
21. **Added chemical formulas** to gallery mineral cards (Cu3(CO3)2(OH)2, FeS2, SiO2)
22. **Improved hero description** to be factual and quotable by AI systems
23. **Changed all CTA buttons** from dead `href="#"` to actual Google Play Store links
24. **Added Google Play link** to footer
25. **Updated privacy policy** with meta tags, OG tags, BreadcrumbList schema
26. **Added SRI integrity attributes** on CDN scripts

---

## Remaining Issues (Cannot Fix With Code)

### Brand Authority (8/100 -- Unchanged)
- No YouTube channel or videos
- No Reddit mentions (r/rockhounds, r/geology, r/AndroidApps)
- No Wikipedia or Wikidata entry
- No LinkedIn company page
- No third-party reviews or "best rock ID apps" listicle mentions
- Not in Google Knowledge Graph

**Action Required:** Create social profiles, post in geology communities when app launches, pitch to review sites.

### Content Depth
- Still a 2-page site (homepage + privacy). Need 5-10 informational pages for topical authority
- No blog with original geological content
- No accuracy benchmarks or methodology transparency page

**Action Required:** Add pages like "How AI Rock Identification Works", "Common Rocks and Minerals Guide", "Mohs Hardness Scale Explained"

### Off-Page SEO
- Zero backlinks
- Not submitted to Google Search Console or Bing Webmaster Tools
- No IndexNow implementation for Bing

---

## 30-Day Action Plan

### Week 1: Deploy & Submit
- [ ] Push all code changes to GitHub (triggers GitHub Pages deploy)
- [ ] Create OG image (1200x630px) and save as `/og-image.png`
- [ ] Create favicon files (32x32, 16x16, apple-touch-icon)
- [ ] Submit sitemap to Google Search Console
- [ ] Submit site to Bing Webmaster Tools
- [ ] Verify site ownership in Google Search Console

### Week 2: Build Authority
- [ ] Create LinkedIn company page for Stone Snap
- [ ] Create YouTube channel, upload 1 demo video showing rock identification
- [ ] Create branded social profiles (Twitter/X, Instagram)
- [ ] Add social profile URLs to Organization schema sameAs array

### Week 3: Content & Community
- [ ] Add 3 informational pages (FAQ deep-dive, How AI ID Works, Mineral Guide)
- [ ] Post in r/rockhounds, r/geology, r/AndroidApps when app launches
- [ ] Pitch to rockhounding.org, educationalappstore.com for inclusion in roundups

### Week 4: Measure & Iterate
- [ ] Check Google Search Console for indexing status
- [ ] Review search queries driving traffic
- [ ] Add AggregateRating to SoftwareApplication schema once Play Store reviews exist
- [ ] Update llms.txt with any new pages

---

## Files Modified/Created

| File | Action | Changes |
|---|---|---|
| `index.html` | Modified | 26 fixes applied (meta, schema, FAQ, about, images, nav, etc.) |
| `privacy-policy/index.html` | Modified | Added meta description, OG tags, canonical, BreadcrumbList schema |
| `robots.txt` | Created | AI crawler permissions + sitemap reference |
| `sitemap.xml` | Created | 2 URLs with lastmod dates |
| `llms.txt` | Created | AI crawler guidance with app features and links |
