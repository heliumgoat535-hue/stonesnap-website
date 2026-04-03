# GEO Platform Optimization Report — stonesnapapp.com
Date: 2026-04-02

## Overall Platform Readiness
- **Combined GEO Score: 26/100** (average of all platform scores)
- **On-Site Foundation: Strong** — 7 JSON-LD schemas, FAQ, speakable, llms.txt, full AI crawler access
- **Off-Site Presence: Critical failure** — zero external citations on any platform AI models use for sourcing

## Platform Scores
| Platform | Score | Status |
|---|---|---|
| Google AI Overviews | 50/100 | Moderate |
| ChatGPT Web Search | 8/100 | Weak |
| Perplexity AI | 18/100 | Weak |
| Google Gemini | 30/100 | Weak |
| Bing Copilot | 22/100 | Weak |

Status thresholds: Strong = 70+, Moderate = 40-69, Weak = 0-39

---

## Critical Discovery: Not Indexed on Bing

`site:stonesnapapp.com` returns **zero results on Bing**. This means ChatGPT and Bing Copilot — which use Bing's index — literally cannot find or cite the site. This single issue blocks 2 of 5 platforms entirely.

## Critical Discovery: Brand Name Collision

A competing iOS app called "StoneSnap" exists at `stonesnap.app` (Hangar Seven Studio LLC, released July 2025). It has an established App Store listing and appears in search results. AI systems may conflate the two products or preferentially cite the iOS competitor.

---

## Platform 1: Google AI Overviews — 50/100 (Moderate)

### What's Working
- 6 FAQ headings phrased as real user questions (10/10)
- Direct answers immediately after each FAQ heading (12/15)
- Feature lists and how-it-works steps use proper list structure (8/10)
- Clean H1 > H2 > H3 heading hierarchy (5/5)
- FAQPage schema provides structured Q&A for AIO extraction

### Gaps Found
- **Not ranking in top 10** for competitive queries like "rock identifier app" or "AI rock identification" (0/20)
- **No comparison tables** — AIO heavily cites HTML tables for specs, pricing, and comparisons (0/10)
- **No visible publication/updated date** on homepage (0/5)
- **No formal author byline** with credentials — Luna is mentioned but no structured byline block (3/5)
- **No cited statistics** with external sources (2/10)

### Actions
1. Add a comparison table: "Stone Snap vs Google Lens vs iNaturalist" with columns for AI model, offline support, collection features, price
2. Add visible "Last updated: April 2026" to the page
3. Add a formal author byline section near the hero or footer with Luna's credentials
4. Blog posts should target "People Also Ask" questions — these are the queries AIO pulls from

---

## Platform 2: ChatGPT Web Search — 8/100 (Weak)

### What's Working
- Content is comprehensive and well-structured (5/10)
- Entity information is internally consistent on the site (3/10 partial)

### Gaps Found
- **Not indexed on Bing** — ChatGPT cannot find the site at all (0/10)
- **No Wikipedia article** (0/20)
- **No Wikidata entity** (0/10)
- **No Reddit mentions** — zero posts in r/rockhounding, r/geology, r/AndroidApps (0/10)
- **No YouTube videos** — no demos, reviews, or tutorials (0/10)
- **No authoritative backlinks** from .edu, .gov, or press (0/15)
- **Bing Webmaster Tools not configured** (0/5)

### Actions
1. **Register in Bing Webmaster Tools immediately** — submit sitemap, verify domain
2. Create Wikidata entity for Stone Snap with properties: instance of (mobile app), official website, platform (Android), developer (Luna), programming language, etc.
3. Post authentically in r/rockhounding, r/geology, r/AndroidApps about rock identification experiences
4. Create a YouTube channel with at least one app demo video
5. Pursue backlinks from geology education sites, rockhounding communities

---

## Platform 3: Perplexity AI — 18/100 (Weak)

### What's Working
- Content freshness is excellent — updated April 2026 (10/10)
- FAQ answers and hero text contain quotable, standalone passages (8/10)

### Gaps Found
- **Zero Reddit presence** — Perplexity weights Reddit at 46.7% of citations (0/20)
- **No forum/community mentions** on HN, Stack Overflow, Quora (0/10)
- **No original research or data** — no surveys, benchmarks, or original datasets (0/15)
- **No YouTube content** with transcripts (0/10)
- **No discussion-generating content** — nothing being shared or debated in communities (0/10)
- **No Wikipedia/Wikidata** (0/5)

### Actions
1. **Reddit is the #1 priority for Perplexity** — participate in r/rockhounding, r/geology, r/whatsthisrock with helpful identification discussions, naturally mentioning the app when relevant
2. Publish original data: "We analyzed 10,000 rock identifications — here's what users photograph most" or similar
3. Create YouTube app walkthrough with full closed captions (Perplexity indexes video transcripts)
4. Post on Hacker News "Show HN" — Perplexity indexes HN heavily

---

## Platform 4: Google Gemini — 30/100 (Weak)

### What's Working
- **Schema.org structured data is strong** — 7 JSON-LD blocks including Organization, Person, SoftwareApplication, FAQPage, Speakable (12/15)
- **Image alt text is good** — descriptive alt attributes on mineral images (7/10)
- **Multi-modal content** — text + high-quality images, though no video (3/5)
- **E-E-A-T partially present** — Luna's About section, founder story (5/10)

### Gaps Found
- **No Google Knowledge Panel** (0/15)
- **No Google Business Profile** (0/10)
- **No YouTube channel** — Gemini weights YouTube more than any other AI platform (0/20)
- **No Google ecosystem presence** — not on Scholar, News, or Maps (0/10)

### Actions
1. **Create a YouTube channel** with rock identification demos, geology tips, app walkthroughs — Gemini cites YouTube more than any other AI platform
2. Improve schema: add `sameAs` links (currently only 1 — Google Play), add `foundingDate`, make `logo` an ImageObject, fix author inconsistency (SoftwareApplication says Organization, should be Person "Luna")
3. Pursue Google Knowledge Panel through structured data + Wikipedia/Wikidata entity creation
4. If Luna is a real person, create an author page at stonesnapapp.com/about-luna/ with full credentials and sameAs links

---

## Platform 5: Bing Copilot — 22/100 (Weak)

### What's Working
- Meta descriptions are well-written and keyword-rich (8/10)
- Exact-match keywords present in titles and headings (8/10)
- Static HTML hosting is reasonably fast (5/10)

### Gaps Found
- **Not indexed on Bing at all** (0/10)
- **Bing Webmaster Tools not verified** (0/15)
- **IndexNow not implemented** (0/15)
- **No LinkedIn company page** (0/10)
- **No social media engagement signals** (0/10)

### Actions
1. **Register and verify in Bing Webmaster Tools** — this is the single most impactful action for Copilot AND ChatGPT
2. **Implement IndexNow protocol** — create a key file, ping IndexNow API on content updates. This gives near-instant Bing indexing.
3. Create LinkedIn company page for Stone Snap
4. Create social media profiles (Twitter/X, Instagram) and add to Organization schema `sameAs`

---

## Prioritized Action Plan

### Quick Wins (this week)
| # | Action | Platforms Helped | Effort |
|---|---|---|---|
| 1 | Register in Bing Webmaster Tools + submit sitemap | ChatGPT, Copilot | 15 min |
| 2 | Implement IndexNow (key file + API ping) | Copilot, ChatGPT | 30 min |
| 3 | Create Wikidata entity for Stone Snap | ChatGPT, Gemini, Perplexity | 30 min |
| 4 | Add visible "Last updated" date to homepage | AIO | 5 min |
| 5 | Fix schema: expand sameAs to 5+ platforms, fix author inconsistency | Gemini, AIO | 20 min |
| 6 | Create LinkedIn company page | Copilot, ChatGPT | 15 min |
| 7 | Create Twitter/X account for @stonesnapapp | All | 10 min |

### Medium-Term (this month)
| # | Action | Platforms Helped | Effort |
|---|---|---|---|
| 8 | Create YouTube channel + 1 app demo video with captions | Gemini, Perplexity, ChatGPT | 2-3 hours |
| 9 | Post in r/rockhounding, r/geology, r/whatsthisrock (authentic participation) | Perplexity, ChatGPT | Ongoing |
| 10 | Add HTML comparison table (Stone Snap vs Google Lens vs iNaturalist) | AIO | 1 hour |
| 11 | Publish original data blog post ("10,000 identifications analyzed") | Perplexity, AIO | 3-4 hours |
| 12 | Add speakable to all 5 blog Article schemas | Gemini, AIO | 30 min |
| 13 | Fix blog Article schemas: author as Person, add image, publisher logo | Gemini, AIO | 1 hour |
| 14 | Create author page at /about-luna/ with credentials + sameAs | All | 1 hour |

### Strategic (this quarter)
| # | Action | Platforms Helped | Effort |
|---|---|---|---|
| 15 | Get the app listed on Google Play (if not already visible) | All platforms | Critical |
| 16 | Pursue Wikipedia article once notability criteria are met (Play Store reviews, press coverage) | ChatGPT, Perplexity, Gemini | Ongoing |
| 17 | Get featured on RockHounding.org, EducationalAppStore.com, or geology blogs | AIO, ChatGPT, Perplexity | Ongoing |
| 18 | Launch on Product Hunt | Perplexity, ChatGPT | 2 hours |
| 19 | Submit to geology-focused press (Geology.com, MinDat.org community) | AIO, ChatGPT | Ongoing |
| 20 | Build .edu backlinks (contact university geology departments about the app for students) | AIO, ChatGPT | Ongoing |

---

## Schema Gaps Summary (from audit)

| Schema | Current State | Fix Needed |
|---|---|---|
| Organization `sameAs` | 1 link (Google Play only) | Expand to 5+ platforms |
| Organization `foundingDate` | Missing | Add year |
| Organization `logo` | Plain URL string | Convert to ImageObject with dimensions |
| Person `name` | "Luna" (single name) | Use full name for entity resolution |
| Person `sameAs` | Missing entirely | Add LinkedIn, Twitter, GitHub |
| Person `knowsAbout` | Missing | Add geology, mineralogy, AI, etc. |
| SoftwareApplication `author` | Organization | Change to Person (Luna) |
| SoftwareApplication `image` | Missing | Add app screenshot URL |
| Article `author` (all 5 blogs) | Organization | Change to Person (Luna) |
| Article `publisher.logo` | Missing | Add ImageObject |
| Article `image` | Missing on all | Add hero image |
| Article `speakable` | Missing on all | Add cssSelector targeting headings + intro |
| WebSite `potentialAction` | Missing | Add SearchAction (requires blog search) |

---

## Bottom Line

The site's **on-page foundation is excellent**: 7 JSON-LD schemas, comprehensive FAQ, AI-friendly content structure, full crawler access, llms.txt, and speakable. This puts it ahead of 90% of app landing pages technically.

The problem is entirely **off-site**: zero presence on every platform AI models use for citations (Wikipedia, Reddit, YouTube, Bing, LinkedIn, Wikidata). Until external signals exist, no AI search engine will recommend Stone Snap when users ask about rock identifier apps.

**Priority #1**: Get indexed on Bing (Webmaster Tools + IndexNow). This unblocks ChatGPT and Copilot immediately.
**Priority #2**: Build 3-5 authentic external mentions (Reddit, YouTube, Product Hunt). This unblocks Perplexity.
**Priority #3**: Create Wikidata entity + YouTube channel. This unblocks Gemini entity recognition.
