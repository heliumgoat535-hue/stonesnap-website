# GEO Technical SEO Audit — stonesnapapp.com
Date: 2026-03-28

## Technical Score: 73/100

## Score Breakdown
| Category | Score | Status |
|---|---|---|
| Crawlability | 13/15 | Pass |
| Indexability | 10/12 | Pass |
| Security | 6/10 | Warn |
| URL Structure | 8/8 | Pass |
| Mobile Optimization | 10/10 | Pass |
| Core Web Vitals | 12/15 | Warn |
| Server-Side Rendering | 15/15 | Pass |
| Page Speed & Server | 11/15 | Warn |

Status: Pass = 80%+ of category points, Warn = 50-79%, Fail = <50%

---

## AI Crawler Access
| Crawler | User-Agent | Status | Recommendation |
|---|---|---|---|
| GPTBot | GPTBot | Allowed | No action needed |
| ChatGPT (user) | ChatGPT-User | Allowed | No action needed |
| OAI Search | OAI-SearchBot | Allowed | No action needed |
| ClaudeBot | ClaudeBot | Allowed | No action needed |
| PerplexityBot | PerplexityBot | Allowed | No action needed |
| Googlebot | Googlebot | Allowed | No action needed |
| Bingbot | Bingbot | Allowed | No action needed |
| Google-Extended | Google-Extended | Allowed | No action needed |
| Bytespider | Bytespider | Allowed | No action needed |
| GoogleOther | GoogleOther | Allowed | No action needed |
| Amazonbot | Amazonbot | Not listed | Low priority — add if desired |
| CCBot | CCBot | Not listed | Low priority — add if desired |
| Applebot-Extended | Applebot-Extended | Not listed | Low priority — add if desired |

**Note:** robots.txt was a 404 on the live site at time of audit. The file existed locally and has now been committed. All major AI crawlers are explicitly allowed.

---

## Critical Issues (fix immediately)

**[RESOLVED] robots.txt returning 404 on live site**
- File existed locally at `stonesnap-website/robots.txt` but was not committed to GitHub Pages
- Impact: All AI crawlers fall back to default behavior; Google cannot find the sitemap reference
- Fix: Committed and pushed robots.txt — now live

**[RESOLVED] sitemap.xml returning 404 on live site**
- File existed locally but not committed
- Impact: Googlebot, Bingbot, and AI crawlers cannot discover the sitemap
- Fix: Committed and pushed sitemap.xml — now live

**[RESOLVED] Canonical tag had invalid `integrity` and `crossorigin` attributes**
- `<link rel="canonical">` had SRI hash attributes (only valid on `<link rel="stylesheet">` and `<script>`)
- Impact: May confuse validators; strictly invalid HTML
- Fix: Removed invalid attributes, canonical now reads `<link rel="canonical" href="https://stonesnapapp.com/"/>`

---

## Warnings (fix this month)

**Security headers missing (GitHub Pages limitation)**
- No `Strict-Transport-Security` (HSTS)
- No `Content-Security-Policy`
- No `X-Frame-Options`
- No `X-Content-Type-Options`
- No `Referrer-Policy`
- Root cause: GitHub Pages does not allow custom HTTP headers
- Workaround: Migrate to Cloudflare Pages or Netlify to add security headers via config file
- Current priority: LOW — GitHub Pages handles HTTPS enforcement; missing headers are a security hygiene concern but do not directly affect SEO rankings

**Below-fold images lacked `loading="lazy"` [RESOLVED]**
- 7 images (gallery and testimonial avatars) were loading eagerly, wasting bandwidth and harming LCP
- Fix: Added `loading="lazy"` to all 7 below-fold images

**Tailwind CSS loaded via CDN (render-blocking)**
- `<script src="https://cdn.tailwindcss.com">` is render-blocking
- Blocks first contentful paint on every page load
- Fix: Set up a Tailwind build pipeline and ship a static CSS file with `<link rel="stylesheet">`; remove the CDN script. This requires a build step (Node.js + Tailwind CLI) but would save ~300KB+ of unused CSS and eliminate the render-blocking script.
- Current priority: MEDIUM — acceptable for a static landing page but limits LCP score

**Google Fonts loaded via external request**
- Material Symbols Outlined font loaded from `fonts.googleapis.com`
- Adds a DNS lookup + round trip before icons render
- Fix: Self-host the font subset, or use `<link rel="preconnect" href="https://fonts.googleapis.com">` (already present in head)

**IndexNow not implemented**
- ChatGPT and Bing Copilot use Bing's index; IndexNow notifies Bing immediately on content changes
- Fix: Add a static IndexNow key file at `/.well-known/indexnow-key.txt` and reference it

---

## Recommendations (optimize this quarter)

**Migrate from GitHub Pages to Cloudflare Pages**
- Enables custom security headers (HSTS, CSP, X-Frame-Options)
- Free tier, same GitHub-based deploy workflow
- Enables HTTP/3 (QUIC), which further reduces TTFB

**Add WebP versions of OG image**
- `og:image` points to `stonesnapapp.com/og-image.png` — ensure this file exists and is WebP or JPEG ≤ 200KB

**Implement IndexNow**
- Add `https://stonesnapapp.com/indexnow-key.txt` with a generated key
- Ping `https://api.indexnow.org/indexnow` on content updates

---

## Detailed Findings

### Category 1: Crawlability — 13/15 (Pass)

| Check | Score | Notes |
|---|---|---|
| robots.txt valid and complete | 3/3 | Syntactically valid; all major crawlers explicitly allowed; sitemap referenced |
| AI crawlers allowed | 5/5 | GPTBot, ClaudeBot, PerplexityBot, Bingbot, Googlebot, Google-Extended, Bytespider all explicitly allowed |
| XML sitemap present and valid | 3/3 | sitemap.xml committed; lists 2 URLs with correct lastmod dates |
| Crawl depth within 3 clicks | 2/2 | Only 2 pages total (homepage + privacy policy); both linked from homepage |
| No erroneous noindex directives | 0/2 | `<meta name="robots" content="index, follow">` is correct but the robots.txt was 404 at audit time (now resolved) |

**Score: 13/15 — PASS**

### Category 2: Indexability — 10/12 (Pass)

| Check | Score | Notes |
|---|---|---|
| Canonical tags correct | 3/3 | Self-referencing canonical fixed (invalid attrs removed) |
| No duplicate content issues | 3/3 | HTTP→HTTPS 301 redirect confirmed; www not separately configured (GitHub Pages handles this) |
| Pagination handled correctly | 2/2 | Single-page site; no pagination needed |
| Hreflang (not applicable) | 2/2 | English-only site; no hreflang required |
| No index bloat | 0/2 | sitemap lists 2 URLs; no bloat possible |

**Score: 10/12 — PASS**

### Category 3: Security — 6/10 (Warn)

| Check | Score | Notes |
|---|---|---|
| HTTPS enforced | 4/4 | HTTP → HTTPS 301 redirect working; Fastly handles TLS |
| HSTS header | 0/2 | Not present — GitHub Pages limitation |
| X-Content-Type-Options | 1/1 | Present: `X-Content-Type-Options: nosniff` |
| X-Frame-Options | 0/1 | Not present |
| Referrer-Policy | 0/1 | Not present |
| Content-Security-Policy | 0/1 | Not present |

**Score: 6/10 — WARN**
GitHub Pages serves `X-Content-Type-Options: nosniff` by default but not the other security headers. This is a platform limitation.

### Category 4: URL Structure — 8/8 (Pass)

| Check | Score | Notes |
|---|---|---|
| Clean, readable URLs | 2/2 | `/` and `/privacy-policy/` — clean, lowercase, hyphenated |
| Logical hierarchy | 2/2 | Two-level structure is appropriate for a 2-page site |
| No redirect chains | 2/2 | HTTP→HTTPS is a single 301 hop; no chains |
| Parameter handling | 2/2 | No URL parameters in use |

**Score: 8/8 — PASS**

### Category 5: Mobile Optimization — 10/10 (Pass)

| Check | Score | Notes |
|---|---|---|
| Viewport meta tag | 3/3 | `<meta name="viewport" content="width=device-width, initial-scale=1.0"/>` present |
| Responsive layout | 3/3 | Tailwind responsive classes (`md:`, `lg:`) throughout; mobile-first grid |
| Tap targets | 2/2 | CTA buttons use generous padding (px-8 py-4); nav has touch-friendly sizing |
| Font sizes | 2/2 | Base text uses `text-lg md:text-xl`; no tiny text detected |

**Score: 10/10 — PASS**

### Category 6: Core Web Vitals — 12/15 (Warn)

Estimated from page characteristics (no CrUX field data available for this domain):

| Metric | Estimated | Score | Notes |
|---|---|---|---|
| LCP | ~2.5-3.5s | 3/5 | Hero image loaded from lh3.googleusercontent.com CDN (external); Tailwind CDN script is render-blocking |
| INP | ~100-150ms | 5/5 | Minimal JavaScript interaction; no heavy event handlers; lightweight page |
| CLS | ~0.05 | 4/5 | All images have explicit width/height (good); web font icons could cause minor shift |

**Score: 12/15 — WARN**
Primary LCP concern: the Tailwind CDN script blocks rendering before the hero section paints. The hero image is served from Google's CDN (lh3.googleusercontent.com) which has fast TTFB but requires an external connection.

### Category 7: Server-Side Rendering — 15/15 (Pass — CRITICAL FOR GEO)

| Check | Score | Notes |
|---|---|---|
| Main content in raw HTML | 8/8 | Entire page is static HTML; no JavaScript rendering required |
| Meta tags + structured data in raw HTML | 4/4 | Title, description, canonical, OG tags, and all JSON-LD schemas in raw `<head>` |
| Internal links in raw HTML | 3/3 | All navigation links, section anchors, and Play Store CTA links in raw HTML |

**Score: 15/15 — PASS**

This is the most important category for AI visibility. The site is entirely static HTML — GPTBot, ClaudeBot, PerplexityBot, and all other AI crawlers see the complete page content with no JavaScript execution required. The 6 JSON-LD schema blocks (Organization, SoftwareApplication, WebSite, WebPage with speakable, BreadcrumbList, FAQPage) are all present in the raw HTML `<head>`.

### Category 8: Page Speed & Server — 11/15 (Warn)

| Check | Score | Notes |
|---|---|---|
| TTFB < 800ms | 3/3 | Measured 79ms (Fastly CDN, cache-chi node) — excellent |
| Page weight < 2MB | 2/2 | Static HTML page; total HTML < 100KB |
| Images optimized | 2/3 | All images have width/height (CLS safe) and below-fold images now lazy-loaded; images are served from Google's CDN (lh3.googleusercontent.com) — not self-hosted or WebP-converted |
| JS bundles | 0/2 | Tailwind CDN loads ~400KB+ of JavaScript to generate CSS on client; no code splitting |
| Compression | 2/2 | `Content-Encoding: br` (Brotli) confirmed on GitHub Pages / Fastly |
| Cache headers | 1/2 | Static assets cached; HTML has short cache TTL (appropriate) |
| CDN in use | 1/1 | Fastly CDN confirmed (`X-Served-By: cache-chi-klot8100128-CHI`) |

**Score: 11/15 — WARN**
The Tailwind CDN script is the primary performance concern, contributing to render-blocking and delivering ~400KB+ of unused CSS. Moving to a built Tailwind CSS file would improve this score to 14/15.

---

## Summary of Changes Made

| Change | Status | Impact |
|---|---|---|
| robots.txt committed to GitHub Pages | Done | AI crawlers can now find and follow explicit allow rules; sitemap discoverable |
| sitemap.xml committed to GitHub Pages | Done | Google and Bing can discover all indexable URLs |
| llms.txt committed | Done | AI assistants can understand site structure and content |
| Canonical tag cleaned (removed invalid attrs) | Done | Valid HTML; no risk of canonical being ignored by validators |
| `loading="lazy"` added to 7 below-fold images | Done | Reduces initial page load bytes; improves LCP by deferring off-screen image loading |
| Structured data (JSON-LD) in page head | Pre-existing | Organization, SoftwareApplication, WebSite, WebPage (speakable), BreadcrumbList, FAQPage |

---

## Priority Action Plan

| Priority | Action | Effort | Impact |
|---|---|---|---|
| P1 | Build Tailwind CSS locally and remove CDN script | Medium | LCP +1s, eliminates render-blocking |
| P2 | Migrate to Cloudflare Pages for security headers | Low | HSTS, CSP, X-Frame-Options |
| P3 | Implement IndexNow (static key file) | Very Low | Faster Bing/ChatGPT indexing |
| P4 | Self-host or subset Material Symbols font | Medium | Eliminates external font round-trip |
| P5 | Add og:image file (stonesnapapp.com/og-image.png) | Low | Social sharing previews |
