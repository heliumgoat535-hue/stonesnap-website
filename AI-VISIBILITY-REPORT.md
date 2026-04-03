# AI Visibility Analysis -- stonesnapapp.com

**AI Visibility Score: 52/100** -- Fair

Score interpretation:
- 0-20: Critical -- Virtually invisible to AI search engines
- 21-40: Poor -- Minimal AI discoverability
- 41-60: Fair -- Some AI visibility but significant gaps
- 61-80: Good -- Solid AI presence with room for improvement
- 81-100: Excellent -- Strong AI search visibility

---

## Score Breakdown

| Component | Score | Weight | Weighted |
|---|---|---|---|
| Citability | 74/100 | 35% | 25.9 |
| Brand Mentions | 18/100 | 30% | 5.4 |
| Crawler Access | 100/100 | 25% | 25.0 |
| llms.txt | 75/100 | 10% | 7.5 |
| **TOTAL** | | | **52.0** |

The site scores well on technical AI-readiness (crawler access, llms.txt, structured data, citability) but is severely held back by near-zero brand presence across AI-cited platforms. Brand mentions are the single biggest bottleneck preventing AI systems from surfacing Stone Snap in responses.

---

## 1. Citability Assessment

**Page Citability Score: 74/100**

### Scoring Methodology

Each content block scored on five dimensions: Answer Block Quality (25%), Self-Containment (20%), Structural Readability (20%), Statistical Density (20%), Uniqueness (15%).

### Top Citation-Ready Passages

**Block 1: FAQ -- "How does Stone Snap identify rocks and minerals?"**
| Dimension | Score |
|---|---|
| Answer Block Quality | 92 |
| Self-Containment | 90 |
| Structural Readability | 80 |
| Statistical Density | 65 |
| Uniqueness | 70 |
| **Weighted Score** | **80.5/100** |

This FAQ answer directly responds to a question an AI system would receive (e.g., "how do rock identifier apps work?"). It names the AI model (Gemini), lists the visual traits analyzed, and specifies the outputs. Highly quotable.

**Block 2: Hero Description**
| Dimension | Score |
|---|---|
| Answer Block Quality | 88 |
| Self-Containment | 85 |
| Structural Readability | 75 |
| Statistical Density | 70 |
| Uniqueness | 65 |
| **Weighted Score** | **77.8/100** |

Contains specific data points: "chemical composition, Mohs hardness, crystal system, formation history, and industrial uses." Self-contained, names the AI model, includes the free tier detail. An AI could cite this when asked "what is the best rock identifier app."

**Block 3: FAQ -- "Is Stone Snap free to use?"**
| Dimension | Score |
|---|---|
| Answer Block Quality | 90 |
| Self-Containment | 95 |
| Structural Readability | 85 |
| Statistical Density | 80 |
| Uniqueness | 55 |
| **Weighted Score** | **82.0/100** |

Contains exact pricing ($4.99/month), free tier details (5 free identifications), trial period (3-day), and feature unlocks. Extremely citable for pricing queries.

**Block 4: Blog -- Accuracy Claim (85-95% range)**
| Dimension | Score |
|---|---|
| Answer Block Quality | 85 |
| Self-Containment | 80 |
| Structural Readability | 70 |
| Statistical Density | 90 |
| Uniqueness | 75 |
| **Weighted Score** | **80.5/100** |

The claim that "apps using large vision models like Google Gemini can correctly identify 85-95% of common rocks and minerals from clear photos" is a specific, citable statistic. AI systems regularly cite accuracy percentages.

**Block 5: Feature -- AI Rock Identifier**
| Dimension | Score |
|---|---|
| Answer Block Quality | 80 |
| Self-Containment | 75 |
| Structural Readability | 80 |
| Statistical Density | 70 |
| Uniqueness | 60 |
| **Weighted Score** | **74.0/100** |

Describes the core feature with specific technical outputs. Usable as a citation when an AI is asked "what data does a rock identifier app give you?"

### Page Citability Score Calculation

Average of top 5 blocks: (80.5 + 77.8 + 82.0 + 80.5 + 74.0) / 5 = **74/100**

### Citation-Unlikely Areas Needing Improvement

| Area | Score | Issue |
|---|---|---|
| Testimonials section | 25/100 | Generic praise without specific data points. "As an avid hiker..." adds no citable information. No star ratings, no user count, no quantifiable claims. |
| Specimen Gallery | 20/100 | Lists mineral names and chemical formulas but provides no unique context an AI could not generate from existing knowledge. No origin data, rarity info, or comparative facts. |
| Download CTA section | 15/100 | Pure marketing copy. No informational content for AI citation. |

### Citability Strengths

- FAQPage schema markup with 6 Q&A pairs -- directly feeds AI answer extraction pipelines
- SpeakableSpecification schema targeting hero and FAQ sections -- signals to voice AI which content to read aloud
- Blog articles with specific statistics (85-95% accuracy, sub-5-second identification)
- Chemical formulas (Cu3(CO3)2(OH)2, FeS2, SiO2) add technical specificity
- "How it works" 3-step structure is ideal for AI procedural responses

### Citability Weaknesses

- No aggregate review data (no "4.8 stars from 10,000 users" claim)
- No comparison tables (Stone Snap vs. competitors with feature matrices)
- Blog is self-referential (ranks own app #1) -- AI systems discount self-promotional sources
- No third-party validation or awards mentioned
- Missing "last updated" visible dates on the landing page (AI systems weigh recency)

---

## 2. AI Crawler Access

**Crawler Access Score: 100/100**

### robots.txt Analysis

File location: `/mnt/storage/Desktop/stonesnap-website/robots.txt`
Live URL: `https://stonesnapapp.com/robots.txt`

| Crawler | User-Agent String | Status | Notes |
|---|---|---|---|
| GPTBot | `GPTBot` | **Allowed** | Explicit `Allow: /` directive |
| OAI-SearchBot | `OAI-SearchBot` | **Allowed** | Explicit `Allow: /` directive |
| ChatGPT-User | `ChatGPT-User` | **Allowed** | Explicit `Allow: /` directive |
| ClaudeBot | `ClaudeBot` | **Allowed** | Explicit `Allow: /` directive |
| PerplexityBot | `PerplexityBot` | **Allowed** | Explicit `Allow: /` directive |
| Googlebot | `Googlebot` | **Allowed** | Explicit `Allow: /` directive |
| Bingbot | `Bingbot` | **Allowed** | Explicit `Allow: /` directive |
| Google-Extended | `Google-Extended` | **Allowed** | Explicit `Allow: /` (Gemini training) |
| GoogleOther | `GoogleOther` | **Allowed** | Explicit `Allow: /` |
| Bytespider | `Bytespider` | **Allowed** | Explicit `Allow: /` (ByteDance/TikTok AI) |
| Amazonbot | `Amazonbot` | **Allowed** | Explicit `Allow: /` |
| CCBot | `CCBot` | **Allowed** | Explicit `Allow: /` (Common Crawl) |
| Applebot | `Applebot` | **Allowed** | Explicit `Allow: /` |
| Applebot-Extended | `Applebot-Extended` | **Allowed** | Explicit `Allow: /` (Apple Intelligence) |
| FacebookExternalHit | `FacebookExternalHit` | **Allowed** | Explicit `Allow: /` (Meta AI) |
| Cohere-ai | Not listed | **Unknown** | Inherits `User-agent: * / Allow: /` -- effectively allowed |

### Score Calculation

- Base: 100
- Critical crawlers blocked: 0 (no deductions)
- Secondary crawlers blocked: 0 (no deductions)
- Sitemap referenced: Yes (`Sitemap: https://stonesnapapp.com/sitemap.xml`) -- no deduction
- **Final: 100/100**

### Additional Findings

- No `Crawl-delay` directives -- no throttling of AI crawlers
- No `Disallow` rules anywhere -- fully open site
- Wildcard `User-agent: *` with `Allow: /` as fallback for unlisted bots
- Sitemap contains 8 URLs with proper `lastmod`, `changefreq`, and `priority` values
- Comments in robots.txt clearly label AI crawler section -- good practice

### Issues Found

- **None.** This is an optimal robots.txt configuration for AI visibility. Every major AI crawler is explicitly allowed with a valid sitemap reference.

---

## 3. llms.txt Status

**Status: Present**
**Score: 75/100**

### File Location

Local: `/mnt/storage/Desktop/stonesnap-website/llms.txt`
Live URL: `https://stonesnapapp.com/llms.txt`

### Format Validation

| Requirement | Status | Notes |
|---|---|---|
| H1 heading (first line) | PASS | `# Stone Snap -- Best Rock Identifier App for Android` |
| Blockquote description | PASS | Present immediately after H1 |
| H2 organized sections | PASS | 7 sections: About Luna, Core Features, Technical Details, Links, Blog, Identifiable Specimens |
| Markdown link format | PASS | Blog section uses `- [Title](url): Description` format |
| Content coverage | PASS | Covers core features, pricing, technical stack, blog content, contact |
| llms-full.txt available | FAIL | Returns 404 -- not created |

### Content Quality Assessment

**Strengths:**
- Names the creator (Luna) with biographical context -- helps AI entity resolution
- Lists exact pricing and technical details (platform, AI model, package name)
- Blog entries have descriptive annotations explaining content of each article
- Identifiable specimens section scopes the app's capabilities clearly
- Contact information included

**Weaknesses:**
- No `## Optional` section for supplementary resources
- Missing links to blog articles for "What Rock Is This?", "AI Rock Identification", and "Crystal Identifier Guide" -- wait, checking again... actually all 5 blog articles are listed. Correction: blog coverage is complete.
- No llms-full.txt companion file (would boost score to 90+)
- Does not mention structured data availability or API access
- Could include a "## Frequently Cited Facts" section with key statistics for AI extraction

### Score Justification

- Present and valid format: +50 base
- Covers primary content areas thoroughly: +20
- Blog articles with descriptions: +5
- Missing llms-full.txt: -10 (prevents reaching 90+)
- No "Optional" supplementary section: -5
- Missing key citable statistics section: -5
- **Final: 75/100**

---

## 4. Brand Mention Presence

**Brand Mention Score: 18/100**

### Platform-by-Platform Analysis

| Platform | Status | Score Contribution | Details |
|---|---|---|---|
| Wikipedia | **Absent** | 0/30 | No Wikipedia article exists for "Stone Snap" or "StoneSnap." Wikipedia API search returns Snap Inc., Infinity Stones, and Snap music -- no results related to the rock identification app. This is the single strongest signal for AI entity recognition and it is completely missing. |
| Reddit | **Absent** | 0/20 | Zero search results for "StoneSnap" or "Stone Snap" on Reddit. No subreddit presence, no user discussions, no mention in r/geology, r/rockhounding, r/minerals, or r/AndroidApps. |
| YouTube | **Absent** | 0/15 | Zero YouTube results for the app. No demo videos, no review videos, no unboxing or walkthrough content. |
| LinkedIn | **Absent** | 0/10 | No company page, no employee profiles, no posts mentioning Stone Snap in a rock identification context. |
| Industry Sources | **Minimal** | 18/25 | See detailed analysis below. |

### Industry Source Analysis

| Source | Presence | Details |
|---|---|---|
| Google Play Store | **Not yet listed** | Search for "Stone Snap" on play.google.com returned no results. The app has not been submitted to the Play Store yet (or listing is not public). This is critical -- Play Store listings are a primary citation source for AI app recommendations. |
| RockHounding.org (top authority) | **Absent** | Two major "Best Rock Identifier Apps" articles (2026) do not mention Stone Snap. They list RockHunt, Stone ID, Rockd, Geology Toolkit, and Stone Identifier Rock Scanner. |
| EducationalAppStore.com | **Absent** | Not listed in their "6 Best Rock Identification Apps" roundup. |
| identifyrock.net | **Absent** | Not included in their "Best Rock Identifier Apps for 2026" guide. |
| EcoCation.org | **Absent** | Not listed in "Free Rock Identification Apps" article. |
| Own blog (stonesnapapp.com) | **Present** | Self-published "Best Rock Identifier Apps" article ranks Stone Snap #1, but AI systems heavily discount self-promotional rankings. |
| G2 / Trustpilot / Capterra | **Absent** | Zero presence on any enterprise review platform. |
| Product Hunt | **Absent** | Not launched or listed. |
| App Store (iOS) | **N/A** | Android-only app; not applicable. |

### Brand Confusion Risk: CRITICAL

A separate, competing app called **"StoneSnap"** exists at `stonesnap.app` (note: different domain from `stonesnapapp.com`). This competing app:
- Is an iOS-only rock identifier and stone scanner
- Has an established App Store listing
- Appears in web search results for "StoneSnap" queries
- Could cause AI systems to conflate the two products or preferentially cite the iOS version

This brand name collision is a significant AI visibility risk. When a user asks an AI "tell me about StoneSnap," the AI may return information about the iOS app at stonesnap.app rather than the Android app at stonesnapapp.com.

### Score Calculation

- Wikipedia: 0 points (absent)
- Reddit: 0 points (absent)
- YouTube: 0 points (absent)
- LinkedIn: 0 points (absent)
- Industry sources: 18 points (own blog present but no third-party mentions; app not yet on Play Store)
- **Final: 18/100**

---

## 5. Entity Recognition Assessment

**Entity Recognition Status: NOT ESTABLISHED**

Stone Snap is not recognized as a distinct entity by AI knowledge systems. Evidence:

1. **Wikipedia**: No article, no disambiguation, no mention in related articles
2. **Wikidata**: No entity record (prerequisite for Google Knowledge Panel)
3. **Google Knowledge Panel**: No panel appears for "Stone Snap rock app" searches
4. **Google Play Store**: App not yet publicly listed -- Play Store listings are a primary entity signal
5. **Brand name collision**: Competing iOS app at stonesnap.app creates entity confusion
6. **Schema.org markup**: Organization, SoftwareApplication, Person, FAQPage, and WebSite schemas are implemented -- these are the correct technical foundations but cannot compensate for zero external references

### What AI Systems Need to Recognize an Entity

AI models establish entity recognition through a convergence of independent sources:

| Signal | Stone Snap Status |
|---|---|
| Wikipedia article | Missing |
| Wikidata entry | Missing |
| Multiple independent web mentions | Missing (only self-published content) |
| App store listing with reviews | Missing (not yet on Play Store) |
| News or press coverage | Missing |
| Third-party review articles | Missing |
| Social media discussion | Missing |
| Schema.org structured data | Present (strong implementation) |
| Consistent NAP (Name, Address, Publisher) | Partially present (name + email consistent) |

---

## 6. Structured Data Assessment (Bonus Analysis)

The site implements 7 distinct Schema.org JSON-LD blocks:

| Schema Type | Quality | Notes |
|---|---|---|
| Organization | Good | Name, URL, logo, email, founder, sameAs (Play Store) |
| Person (Luna) | Good | Creator attribution with job title and description |
| SoftwareApplication | Good | App name, category (Education), OS, pricing, features, download URL |
| WebSite | Basic | Name, URL, description only |
| WebPage + Speakable | Excellent | SpeakableSpecification targeting hero and FAQ -- signals voice AI content |
| BreadcrumbList | Minimal | Single "Home" item -- add blog and feature page breadcrumbs |
| FAQPage | Excellent | 6 Q&A pairs fully structured -- directly feeds AI answer extraction |

**Structured Data Score: Strong.** This is above-average implementation for a landing page. The SpeakableSpecification and FAQPage schemas are particularly valuable for AI systems.

---

## Priority Actions

### 1. [CRITICAL] Get the App on Google Play Store

The app is not publicly listed on Google Play. This is the single most impactful action for AI visibility. AI systems cite Play Store listings as authoritative sources for app information. Without a listing, no AI will recommend Stone Snap when asked about rock identifier apps.

- Submit the signed AAB to Play Store
- Optimize the listing title: "Stone Snap - AI Rock Identifier"
- Include all keywords in the long description
- Add screenshots showing identification results with geological data
- Target 10+ reviews as quickly as possible (AI systems weight review count)

### 2. [CRITICAL] Build Third-Party Mentions

Stone Snap has zero independent mentions on any platform that AI systems cite. This is the largest gap in the entire profile.

Specific actions:
- **Submit to RockHounding.org**: Contact their editorial team for inclusion in their "Best Rock Identifier Apps" roundups. They are the #1 authority site that AI systems cite for this category.
- **Submit to EducationalAppStore.com**: They review educational apps and their content appears in AI responses.
- **Submit to identifyrock.net**: Another authority in the rock identification space.
- **Post on Reddit**: Create genuine, helpful posts in r/rockhounding, r/geology, r/minerals, r/AndroidApps discussing the app. Reddit is the #2 platform (after Wikipedia) that AI systems cite.
- **Create a YouTube demo video**: Even a single 2-minute walkthrough would establish YouTube presence. AI systems cite YouTube content frequently.
- **Launch on Product Hunt**: Establishes a dated, independent reference that AI systems can cite.

### 3. [HIGH] Resolve Brand Name Collision

A competing iOS app called "StoneSnap" exists at stonesnap.app. This creates entity confusion for AI systems.

Options:
- Differentiate with consistent full branding: "Stone Snap for Android" everywhere
- Ensure all schema markup, llms.txt, and meta descriptions emphasize "Android" as a differentiator
- Build enough independent mentions that AI systems learn to distinguish the two products
- Consider whether the domain name difference (stonesnapapp.com vs stonesnap.app) is clear enough

### 4. [HIGH] Create llms-full.txt

Adding `/llms-full.txt` would boost the llms.txt score from 75 to 90+. This file should contain:
- Complete text of the landing page
- Full FAQ content
- All blog article content
- Pricing details with comparison tables
- Key statistics (accuracy rates, identification speed, specimen count)
- Full feature descriptions

### 5. [MEDIUM] Add Citable Statistics to Landing Page

The landing page lacks specific, citable numbers that AI systems prefer:
- Add user count or download count when available
- Add accuracy rate claim (the 85-95% figure from the blog should appear on the landing page)
- Add specimen count ("identifies 500+ rock and mineral types" or similar)
- Add identification speed ("results in under 5 seconds")
- Add a comparison table: Stone Snap vs. competitors with feature checkmarks

### 6. [MEDIUM] Build Wikipedia Foundation

Wikipedia is worth 30% of the Brand Mention Score and is the strongest entity recognition signal. A Wikipedia article requires:
- **Notability**: The app needs independent, reliable sources covering it (press articles, third-party reviews)
- **Do not create a Wikipedia article yourself** -- it will be flagged and deleted for conflict of interest
- Instead: Get covered by 3+ independent sources (press, review sites, educational publications), then a Wikipedia editor may create the article organically, or you can request creation at Wikipedia:Articles for creation

### 7. [MEDIUM] Create LinkedIn Company Page

A LinkedIn company page for "Stone Snap" provides:
- An additional structured entity signal
- A citation source for AI systems answering "who makes Stone Snap?"
- Employee/founder attribution that strengthens entity resolution

### 8. [LOW] Improve Testimonials Section

Current testimonials are generic and uncitable. Replace with:
- Verified reviews with specific data points (e.g., "Identified 47 specimens on a 3-day camping trip")
- Include reviewer credentials (e.g., "Geology professor, University of Arizona")
- Add aggregate rating display (e.g., "4.8/5 from 1,200 ratings")

### 9. [LOW] Add Comparison Content

Create a dedicated comparison page (e.g., `/blog/stone-snap-vs-rock-identifier/`) with:
- Side-by-side feature tables
- Specific test results (e.g., "Stone Snap correctly identified 19/20 common minerals; Competitor X identified 14/20")
- Price comparisons
- Structured data (schema.org Comparison or Table markup)

AI systems heavily favor comparison content when recommending products.

---

## Summary

Stone Snap's website is technically well-optimized for AI consumption. The robots.txt, llms.txt, structured data, and content citability are all above average. The site would score 80+ if brand mentions existed.

The critical gap is that Stone Snap has **zero external presence** across every platform that AI systems use as citation sources. No Play Store listing, no Reddit discussion, no YouTube content, no third-party reviews, no Wikipedia article, no LinkedIn page, and no industry publication mentions. Until independent references exist, AI systems have no basis to recommend or cite Stone Snap regardless of how well the website itself is optimized.

The recommended priority order is: (1) Get on Google Play, (2) Build third-party mentions on authority sites, (3) Resolve brand collision with stonesnap.app, (4) Create llms-full.txt, (5) Add citable statistics to the landing page.

---

*Report generated: April 2, 2026*
*Target: https://stonesnapapp.com*
*Analysis method: GEO AI Visibility Audit v1.0*
