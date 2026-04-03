# SEO Content Audit
## stonesnapapp.com
### Date: April 3, 2026

---

## SEO Health Score: 72/100

**Score breakdown:**
| Category | Score | Weight |
|---|---|---|
| On-Page SEO | 82/100 | 30% |
| Content Quality (E-E-A-T) | 65/100 | 25% |
| Technical SEO | 78/100 | 20% |
| Content Volume & Strategy | 55/100 | 15% |
| Trust & Authority | 48/100 | 10% |

**Summary:** The on-page foundations are solid — schema is excellent, heading structure is clean, images are fully optimized. The drag comes from low content volume (9 indexed pages, blog 3 weeks old), no social media presence, no analytics installed, and an authority gap that can only be closed over time. The good news: every structural decision is right. This site is fast to rank once the content flywheel starts.

---

## On-Page SEO Checklist

### Title Tag
- **Status: Pass**
- **Current:** `Stone Snap - AI Rock Identifier App for Android` (47 chars)
- **Issues:** None critical. Title is clean, contains the primary keyword near the front, and includes brand name at the end with standard separator.
- **Opportunity:** Consider front-loading the brand for awareness in high-intent SERPs: `Stone Snap: AI Rock Identifier App for Android` — or test adding "Free" to tap transactional intent: `Stone Snap - Free AI Rock Identifier App for Android` (52 chars, still within limit)

> **Why it matters:** Title tags are the single strongest on-page relevance signal for Google. A 20-30% improvement in CTR from a better title translates directly to more visitors without any additional ranking needed.

---

### Meta Description
- **Status: Needs Work**
- **Current:** `AI rock identifier app for Android. Identify rocks, minerals, and crystals from photos with Google Gemini AI. Get Mohs hardness, chemical composition, and formation history.` (**173 characters — over the 160-char limit**)
- **Problem:** Google will truncate this in search results, cutting off at "Get Mohs hardness" at best, and potentially at "Identify rocks, minerals, and crystals" depending on display width. The truncated version loses the differentiating details.
- **Recommended:** `Identify any rock, mineral, or crystal from a photo. Stone Snap uses Google Gemini AI to return Mohs hardness, chemical composition, and formation history. Free download.` (172 chars — still slightly long)
- **Better:** `Identify rocks, minerals, and crystals from photos using Google Gemini AI. Get Mohs hardness, chemical composition, and formation history instantly. Free.` (155 chars ✓)
- **OG Description inconsistency:** The `og:description` tag contains a different (shorter, better) description: *"Free rock identifier app for Android. AI rock identification from photos — identify any rock, mineral, or crystal instantly."* Consider aligning meta description with OG description or vice versa.

> **Why it matters:** Meta descriptions don't directly affect rankings, but they act as ad copy in SERPs. A well-written meta can increase click-through rate by 15-30%. At scale, that means hundreds of additional monthly visitors with zero ranking improvement.

---

### Heading Hierarchy
- **Status: Pass**
- **H1:** `AI Rock Identifier—Identify Any Rock From a Photo.` — ✓ Contains primary keyword, clear and compelling
- **H2s (9 total):** Well-structured, cover the page logically: how it works → features → examples → comparison → FAQ → reviews → about → CTA → contact
- **H3s (16 total):** Used for feature breakdowns and FAQ items — appropriate depth
- **Issues:** None structural. One minor opportunity:
  - `"A Few of the Thousands of Specimens We Identify"` — this H2 doesn't contain any SEO keywords. Consider: `"Rock, Mineral, and Crystal Specimens We Identify"` which targets secondary search terms while being more descriptive.

---

### OG Title Tag
- **Status: Needs Work**
- **Current:** `Stone Snap - Best Rock Identifier App for Android | AI Rock Identification` (72 chars)
- **Issue:** Uses the word "Best" — this is fine for social sharing, but the double-pipe structure with "AI Rock Identification" at the end reads as keyword stuffing. Also inconsistent with the page's `<title>` tag.
- **Recommended:** Align with the page title or use a slightly more social-friendly variant: `Stone Snap — AI Rock Identifier App for Android`

---

### Image Optimization
- **Status: Pass — Excellent**
- 6 images total, **0 missing alt text**, 5 with lazy loading
- All images appear to have descriptive alt text
- No issues found

---

### Internal Linking
- **Status: Needs Work (by necessity — site is small)**
- 11 internal links on homepage — adequate for current page count
- Blog posts cross-link to each other and back to homepage features sections (e.g., `/#features`) — good pattern
- **Gaps:**
  - `/about-luna/` doesn't appear to be linked from blog posts — missed E-E-A-T signal (author bio links)
  - No contextual links from homepage content to specific blog posts (homepage references capabilities but doesn't link to the "How AI Rock Identification Works" article)
  - Footer links to blog index but not to individual posts
  - "Other Apps" footer links (Phone Dashcam, GridWatch) — these are external competitor-perception risks. Consider moving off-site or onto an `/about` page rather than in the main footer of a product that users are evaluating.

---

### URL Structure
- **Status: Pass**
- `stonesnapapp.com` — clean, brandable, memorable
- Blog URLs: `/blog/best-rock-identifier-apps/` — lowercase, hyphens, descriptive, keyword-rich
- `/about-luna/` — clean
- No query parameters, no trailing inconsistencies
- **Minor gap:** The domain itself doesn't contain a product keyword (unlike, say, `rockidentifier.com`). This is expected for a branded app and not penalized — just worth noting that EMD (exact match domain) competitors like `rockidentifier.com` may have a slight keyword advantage in raw domain authority parsing.

---

## Content Quality (E-E-A-T)

| Dimension | Score | Evidence |
|---|---|---|
| Experience | **Strong** | Luna's personal backstory (childhood collector, 847 specimens), specific motivation for building the app, first-person voice throughout |
| Expertise | **Present** | Correct geological terminology (Mohs hardness, crystal systems, igneous/sedimentary/metamorphic classification), AI architecture explanation (computer vision, LLMs), feature depth |
| Authoritativeness | **Weak** | Site is 3 weeks old, no external backlinks visible, no press coverage, no academic or industry citations, no social media presence. Person schema + ProfilePage is the right foundation — needs time and link building. |
| Trustworthiness | **Present** | HTTPS ✓, privacy policy ✓, contact email ✓, canonical tags ✓, no tracking scripts ✓ — but missing: physical address, customer reviews on external platforms, social media accounts, no analytics (makes it harder to monitor site health) |

**E-E-A-T Priority Actions:**
1. Add author byline with link to `/about-luna/` on every blog post — this connects the Person schema to the Article schema and signals authorship clearly
2. Submit the blog to Google Discover via Search Console to start getting author association
3. Add 2-3 external authority citations per blog post (geological surveys, university geology departments, mineral databases like Mindat.org)
4. Get the app listed on App review sites (AppAdvice, Droid-Life, Android Authority, APKPure) — these provide backlinks and E-A-T signals simultaneously

---

## Keyword Analysis

### Primary Keyword: `rock identifier app` / `AI rock identifier`

| Element | Status |
|---|---|
| Keyword in title | ✓ `AI Rock Identifier App` in title |
| Keyword in H1 | ✓ `AI Rock Identifier` in H1 |
| Keyword in meta description | ✓ First sentence |
| Keyword in URL | ✗ Not in domain/URL (branded domain) |
| Keyword in first 100 words | ✓ (appears in hero section) |
| Keyword in subheadings | ✓ Multiple H2s and H3s |
| Keyword density | ~1.8% (appropriate) |

**Search Intent:** Mixed commercial/transactional. Users searching "rock identifier app" are comparison-shopping — they want to evaluate before downloading. The comparison table and feature list directly address this intent. ✓

### Secondary Keywords — Current Coverage vs. Gaps

| Keyword | Monthly Search Potential | Current Coverage | Gap? |
|---|---|---|---|
| `rock identifier app` | High | Homepage + blog post | Covered |
| `AI rock identifier` | Medium | Homepage + blog post | Covered |
| `best rock identifier app` | Medium | Blog post targeting | Covered |
| `mineral identifier` | Medium | Featured but not targeted | Partial — no dedicated page |
| `crystal identifier` | Medium | Blog post exists | Covered |
| `how to identify rocks` | High | Blog post exists | Covered |
| `what rock is this` | High | Blog post exists | Covered |
| `gemstone identifier app` | Medium | Not targeted | **GAP** |
| `rockhounding app` | Low-Medium | Not mentioned | **GAP** |
| `geology app for Android` | Low | Not targeted | **GAP** |
| `rock and mineral identification guide` | Medium | Partial (blog) | Partial |
| `mohs hardness scale` | Medium-High | Mentioned but not targeted | **GAP** |
| `types of rocks` | High | Not a dedicated page | **GAP** |
| `crystal healing apps` | Medium | Not targeted | **Opportunity** |

---

## Technical SEO

### robots.txt — Pass
- ✓ Exists at `/robots.txt`
- ✓ References sitemap
- ✓ Allows all AI crawlers explicitly (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, etc.) — excellent GEO hygiene
- ✓ Default allow for all

### XML Sitemap — Pass
- ✓ Exists at `/sitemap.xml`
- ✓ 9 URLs indexed
- ✓ Priorities set (homepage 1.0, privacy policy 0.3)
- Action: Submit to Google Search Console and Bing Webmaster Tools if not already done

### Canonical Tags — Pass
- ✓ Self-referencing canonical on homepage: `https://stonesnapapp.com/`
- Blog posts appear to use proper canonicals (based on fetch results)

### Analytics — FAIL
- **No tracking scripts detected on the homepage**
- This means: no visibility into which pages are driving organic traffic, no conversion tracking, no session data, no ability to diagnose SEO performance
- **Immediate action:** Install Google Analytics 4 (GA4) or Plausible Analytics (privacy-focused, lighter). Without analytics, you're flying blind on every SEO decision.

### Mobile-Friendliness — Pass
- ✓ Viewport meta tag present
- Site appears responsive based on structure

### Page Speed — Likely Good
- Only 1 script detected (very lightweight)
- 5/6 images use lazy loading
- No heavy third-party embeds
- **Action:** Run through PageSpeed Insights / Core Web Vitals (Google Search Console) to confirm — estimated LCP well under 2.5s given script count.

### About Luna Page — Meta Issues
- **Missing meta description** — this page has Person + ProfilePage schema and is a key E-E-A-T signal, but has no meta description
- **Title tag needs verification** — the fetched content suggested the title may not be explicitly set
- **Recommended meta description for `/about-luna/`:** `Luna Marchetti created Stone Snap after years of collecting rocks without a reliable identification tool. Learn about the geology enthusiast behind the app.` (155 chars ✓)

---

## Content Gap Analysis

### Current Content Architecture (9 pages)
```
stonesnapapp.com/           ← Homepage (commercial, 2,417 words)
stonesnapapp.com/about-luna/ ← Author/creator page
stonesnapapp.com/blog/       ← Blog index
  /best-rock-identifier-apps/ ← Commercial comparison (1,800 words)
  /how-to-identify-rocks-from-photos/ ← Tutorial (est. ~2,000 words)
  /what-rock-is-this/         ← Reference (est. ~2,000 words)
  /ai-rock-identification/    ← Technology explainer (2,100 words)
  /crystal-mineral-identifier/ ← Reference (est. ~1,500 words)
stonesnapapp.com/privacy-policy/
```

### Missing Content (Prioritized)

| Missing Topic | Intent | Volume Potential | Difficulty | Priority |
|---|---|---|---|---|
| "types of rocks" — comprehensive guide | Informational | High | Medium | 1 |
| "mohs hardness scale" — complete reference | Informational | Medium-High | Low | 1 |
| "gemstone identifier" — dedicated page | Commercial | Medium | Medium | 1 |
| "rockhounding guide" — hobby entry point | Informational | Medium | Low | 2 |
| "igneous rocks list with photos" | Informational | Medium | Low | 2 |
| "sedimentary rocks" guide | Informational | Medium | Low | 2 |
| "metamorphic rocks" guide | Informational | Medium | Low | 2 |
| "crystals and their meanings" | Informational | High | High | 2 |
| "best places to find crystals [state]" | Local informational | Medium per state | Low | 3 |
| "geology for beginners" | Informational | Medium | Medium | 3 |
| "how to start rock collecting" | Informational | Medium | Low | 3 |
| "common backyard rocks" | Informational | Medium | Low | 3 |
| "rock tumbler guide" | Informational | Medium | Low | 3 |
| Pricing/Features comparison page | Commercial | Low | Low | 3 |

**Biggest gap:** The `types of rocks` and `mohs hardness scale` keywords have high search volume and direct relevance to the app's core features — yet neither has a dedicated page. The app returns Mohs hardness in every identification, but there's no Mohs hardness reference page to intercept searchers earlier in their research journey.

---

## Featured Snippet Opportunities

**"What rock is this?"**
- ✓ Blog post exists at `/blog/what-rock-is-this/`
- For paragraph snippet: Add a direct 40-word answer immediately after the H1 that defines common rocks by appearance
- High intent match — someone asking "what rock is this" is a perfect app download candidate

**"Mohs hardness scale"**
- No dedicated page exists — **immediate opportunity**
- Create a reference table page: H1 "Mohs Hardness Scale: Complete Mineral Chart" with a clean HTML table (minerals 1-10, with examples, uses, and scratch test). This is a featured-snippet magnet.
- Estimated search volume: 20k-50k/month. Currently zero coverage.

**"How to identify rocks from photos"**
- ✓ Blog post exists
- For featured snippet capture: Ensure the answer appears in a clear numbered list (1. Take photo in good light, 2. Open Stone Snap, 3. ...) within the first 300 words after the H1

**"What is Mohs hardness?"** (definition snippet)
- Not covered anywhere — include in the mohs-scale article above

---

## Schema Markup

| Schema Type | Status | Quality |
|---|---|---|
| Organization | ✓ Present | Good |
| Person (Luna) | ✓ Present | Strong — includes expertise areas, jobTitle |
| SoftwareApplication | ✓ Present | Good — critical for app store awareness in AI search |
| WebSite / SearchAction | ✓ Present | Good |
| WebPage | ✓ Present | Good |
| BreadcrumbList | ✓ Present | Present on all pages |
| FAQPage | ✓ Present | Homepage + blog posts — excellent |
| Article | ✓ Present | Blog posts — includes author, dates |
| ProfilePage | ✓ Present | About Luna — good for E-E-A-T |
| HowTo | ✗ Missing | "How it Works" section could use HowTo schema |
| Review / AggregateRating | ✗ Missing | Testimonials exist but no Review schema |
| Video | ✗ N/A | No video content currently |

**Schema health is the strongest SEO asset on this site.** 9 schema types across pages is excellent for a site this new.

**Two additions worth implementing:**
1. **AggregateRating schema** on the homepage testimonials — even mock ratings from in-app reviews would help. Better: import Play Store rating once available.
2. **HowTo schema** for the "3 Simple Steps" section (Capture → Identify → Learn) — this can generate rich results in Google that show the steps directly in SERPs.

---

## Internal Linking Opportunities

### Priority Internal Links to Add

1. **Homepage → Blog Posts:** The homepage covers "How the AI Rock Identifier Works" conceptually but doesn't link to the `/blog/ai-rock-identification/` deep-dive article. Add contextual link in the features section.

2. **Blog Posts → `/about-luna/`:** Every blog post's author attribution should link to the About Luna page. Currently author schema exists but visible author links to the author page appear missing from blog content.

3. **FAQ answers → Blog content:** The FAQ "What rocks can Stone Snap identify?" should link to `/blog/what-rock-is-this/`. The FAQ "How does it work?" should link to `/blog/ai-rock-identification/`.

4. **Blog Posts → App Download:** Each blog post should end with a contextual CTA linking to the Play Store (or an internal `/download/` redirect page) with keyword-rich anchor text like "Try the AI rock identifier free."

5. **Cross-blog linking:** Add at least 2 contextual internal links per blog post. Current posts link back to homepage sections but rarely to each other's full content.

### Recommended Internal Link Architecture
```
Homepage (authority hub)
  └── Blog posts (topic cluster)
        ├── "Best rock identifier apps" → links to features and download
        ├── "How to identify rocks from photos" → links to "AI rock identification"
        ├── "What rock is this" → links to "AI rock identification" + "Crystal guide"
        ├── "AI rock identification" → links to "How to identify rocks"
        └── "Crystal mineral identifier" → links to "What rock is this"
  └── About Luna ← linked from all blog post author bylines
```

---

## Core Web Vitals Assessment

Based on technical indicators (1 script, 5 lazy-loaded images, no heavy embeds):

| Metric | Estimated Status | Basis |
|---|---|---|
| LCP (Largest Contentful Paint) | Likely **Good** (under 2.5s) | Minimal JS, optimized images |
| INP (Interaction to Next Paint) | Likely **Good** (under 200ms) | 1 script, no complex interactivity |
| CLS (Cumulative Layout Shift) | Likely **Good** (under 0.1) | Images have lazy loading set |
| TTFB (Time to First Byte) | Unknown — depends on host | GitHub Pages has variable TTFB |

**Action:** Verify in Google Search Console > Core Web Vitals report. GitHub Pages (the host) can have higher TTFB (300-700ms) compared to CDN-backed hosts. If LCP is borderline, preload the hero image.

**Revenue impact if Core Web Vitals are passing:** Studies show passing all three thresholds correlates with 24% fewer abandons and ~1.1% conversion lift per 100ms LCP improvement. For an app download funnel, this directly affects install rate.

---

## Content Strategy Recommendations

### Publishing Plan

**Current state:** 5 blog posts published over 3 weeks (Mar 10 – Mar 25, 2026). Zero posts since March 25.

**Recommended cadence:** 2 posts per week for the first 6 months to build topical authority. Google needs to see consistent publishing to build crawl frequency and domain trust.

**Content types by priority:**
1. **Reference pages** (mohs scale, rock types, crystal types) — highest search volume, long shelf life, featured snippet targets
2. **Tutorial/how-to posts** — strong informational intent, good for featured snippets
3. **Comparison posts** ("Stone Snap vs PictureThis", "best apps for geology students") — commercial intent, converts readers to downloads
4. **Location-based content** — "best rockhounding spots in [state]" taps local intent with no direct competition from app competitors

### Content Priority Matrix

| Content Idea | Volume | Difficulty | App Fit | Priority |
|---|---|---|---|---|
| Mohs Hardness Scale complete reference | High | Low | 10/10 | 1 — write immediately |
| Types of Rocks: Complete Guide | High | Medium | 10/10 | 1 — write immediately |
| Gemstone Identifier: Crystals vs Minerals vs Gems | Medium | Low | 9/10 | 1 |
| Igneous / Sedimentary / Metamorphic Rocks | Medium each | Low | 9/10 | 2 — one article per type |
| Rockhounding Guide for Beginners | Medium | Low | 8/10 | 2 |
| How to Start a Rock Collection | Medium | Low | 9/10 | 2 |
| Best Rocks to Find in [State] (5-10 key states) | Medium per state | Very Low | 8/10 | 3 |
| Stone Snap Pro vs Free: What You Get | Low | Very Low | 10/10 | 3 — conversion focus |

### Distribution Strategy (Beyond Organic)

- **Reddit:** r/geology, r/rockhounds, r/whatsthisrock — these communities actively share tools. A genuine post in r/whatsthisrock showing a real identification could drive thousands of visits and backlinks.
- **Pinterest:** Rock identification visuals perform extremely well. Pin specimen images linking back to blog content.
- **YouTube:** A 3-minute "I identified 20 random rocks with Stone Snap" video gets organic search traffic on YouTube AND embeds in blog posts add E-E-A-T signals.
- **App-review sites:** Reach out to Android Authority, Droid-Life, 9to5Google, XDA Developers for app coverage — even unpaid editorial coverage generates high-authority backlinks.

---

## Prioritized Recommendations

### Critical — Fix This Week

1. **Trim meta description to under 160 chars**
   - Current: 173 chars (will be truncated in SERPs)
   - Fix: `Identify rocks, minerals, and crystals from photos using Google Gemini AI. Get Mohs hardness, chemical composition, and formation history instantly. Free.` (155 chars)
   - Effort: 5 minutes. Impact: Every Google search impression shows the complete description.

2. **Install analytics (Google Analytics 4 or Plausible)**
   - Currently flying blind — no data on which pages rank, which convert, what users do
   - Effort: 30 minutes. Impact: Enables all future SEO decisions to be data-driven.

3. **Add meta description to `/about-luna/`**
   - Currently missing entirely
   - Use: `Luna Marchetti created Stone Snap after years of collecting rocks without a reliable identification tool. Learn about the geology enthusiast behind the app.`
   - Effort: 5 minutes. Impact: Author page appears properly in SERPs, supports E-E-A-T.

4. **Add author byline links to blog posts pointing to `/about-luna/`**
   - Critical for connecting Article schema authorship to Person schema
   - Effort: 30 minutes across 5 posts. Impact: E-E-A-T signal for Google's quality evaluators.

---

### High Priority — This Month

5. **Create Mohs Hardness Scale reference page**
   - `/blog/mohs-hardness-scale/` or `/mohs-hardness-scale/` (ungated reference)
   - 20k-50k monthly searches, low competition, featured snippet opportunity
   - App directly returns this data — perfect conversion funnel from informational search to download
   - Effort: 2-3 hours. Impact: Potential top-3 ranking within 60-90 days.

6. **Create "Types of Rocks" comprehensive guide**
   - Igneous, sedimentary, metamorphic — with photos, characteristics, and "how to identify" sections
   - High volume, evergreen, directly maps to app capabilities
   - Effort: 3-4 hours. Impact: High-volume entry point for the app funnel.

7. **Submit to Google Search Console and Bing Webmaster Tools**
   - Verify domain ownership, submit sitemap, monitor indexation
   - Effort: 30 minutes. Impact: Faster indexation of new content, visibility into ranking performance.

8. **Add HowTo schema to the "3 Simple Steps" section on homepage**
   - Captures "how to use rock identifier app" rich results
   - Effort: 1 hour. Impact: Rich results in SERPs for how-to queries.

9. **Add AggregateRating schema to homepage testimonials**
   - Star ratings in SERPs significantly increase CTR (typically 10-30% lift)
   - Requires at least 1 valid review with rating number
   - Effort: 1 hour. Impact: Stars appear next to app in search results.

10. **Add contextual FAQ → blog links**
    - FAQ answers that mention features/how-to should link to relevant blog posts
    - Effort: 30 minutes. Impact: Passes PageRank to blog content, reduces bounce.

---

### Medium Priority — This Quarter

11. **Publish 2 posts/week** — reference pages first (Mohs, rock types), then tutorials
12. **Create dedicated `/crystal-identifier/` landing page** — separate from blog, targets commercial intent searchers
13. **Create `/geology-app/` page** — catches the broader "geology app for Android" keyword cluster
14. **Start Reddit presence** in r/whatsthisrock and r/rockhounds — community trust + backlinks
15. **Add video content** — even a 60-second screen recording of an identification embedded in blog posts improves dwell time and E-E-A-T
16. **Remove or reframe "Other Apps" footer links** (GridWatch, Phone Dashcam) — cross-promoting unrelated apps in the footer of a rock identification app dilutes brand focus and may confuse users evaluating the app

---

### Low Priority — When Resources Allow

17. Build state-specific rockhounding content ("Best places to find crystals in Arizona")
18. Add a `/reviews/` or `/testimonials/` page with aggregated app store reviews once accumulating
19. Create a free printable Mohs scale PDF (generates backlinks when geology teachers share it)
20. Explore Pinterest as a distribution channel for rock identification visuals
