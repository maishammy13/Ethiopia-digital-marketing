# Service: On-Page SEO

## A. Service Definition

**What it is.** Optimizes individual pages' content and HTML elements — titles, meta descriptions, heading structure, body content, internal links, image alt text, and URL slugs — so pages match real search intent and are clearly readable by both visitors and search engines. Where [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md) writes the initial copy, this service is the ongoing discipline of mapping, structuring, and refining that content against real search performance.

**What business problem it solves.** A page can be technically crawlable (see [06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md)) and well-written, and still fail to rank or convert from search if it isn't clearly structured around the actual terms and intent real customers search with.

**Why a customer would pay for it.** Correctly optimized pages both rank better and convert better, because they match what the visitor was actually looking for when they clicked through from search — reducing wasted traffic and improving click-through rate from search results.

**Business types that benefit most.** Any business relying on organic search for discovery, especially those with multiple service/product pages needing distinct targeting — see the "Search demand" and "Website" ratings per segment in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md).

**What this service does not include.** Technical crawlability/indexation ([06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md)), earning links or citations from other sites ([08_OFF_PAGE_SEO_AND_LINK_BUILDING.md](08_OFF_PAGE_SEO_AND_LINK_BUILDING.md)), local-listing optimization ([09_LOCAL_SEO.md](09_LOCAL_SEO.md) — though this service optimizes the on-page content of any location pages), or writing brand-voice copy from a blank page (04 produces the base copy; this service maps, structures, and iteratively refines it).

**How it connects to other services.** Consumes the keyword/intent report from [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md) and the final copy from 04. Depends on a technically healthy site from 06. Feeds ranking and click-through data into [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md), and informs content decisions in [14_CONTENT_STRATEGY.md](14_CONTENT_STRATEGY.md) and location-page content in 09.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Mapping keywords to pages, optimizing titles/headings/alt text/internal links, refining underperforming content |
| Output | Keyword-to-page map, optimized page titles and meta descriptions, structured headings, internal linking plan, content-refinement recommendations |
| Outcome | Pages rank for and are genuinely relevant to the real search queries customers use |
| Financial impact | Increased qualified organic traffic; higher click-through rate from search results; more visitors converting because the page actually matches what they were looking for |

## C. Inputs Required From the Client

- Keyword/intent report from 01
- Final approved site copy from 04
- Full list of live pages/URLs
- Current ranking baseline, if any prior SEO work exists
- Search Console access (see 06, Task 1.1)
- Detail on products/services sufficient to write genuinely useful, non-thin content
- Awareness of any ⚠️-flagged claim restrictions for the client's sector (see [../market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md](../market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md))

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm and finalize the page inventory**
| Field | Detail |
|---|---|
| Purpose | On-page optimization needs a complete, accurate list of what actually exists before mapping keywords to it |
| Inputs | Live site, sitemap |
| Procedure | 1) Pull the full list of live, indexable pages. 2) Cross-check against the sitemap from 06. 3) Flag any page that appears in one list but not the other. |
| Tools | Sitemap, crawl tool |
| Deliverable | Confirmed page inventory |
| Owner | SEO specialist |
| Dependency | 06, Task 5.1 (corrected sitemap) |
| Frequency | One-time, refreshed whenever pages are added |
| KPI | Inventory matches the live site with zero discrepancies |
| Quality check | Cross-checked against the sitemap, not compiled from memory |
| Common mistake | Working from an outdated page list that misses recently added pages |
| Estimated complexity | Low |

### 2. Research

**Task: Analyze search intent and top-ranking pages per target keyword**
| Field | Detail |
|---|---|
| Purpose | Ranking requires matching what search engines are already rewarding for a given query, not just including the keyword |
| Inputs | Keyword/intent report from 01 |
| Procedure | 1) For each priority keyword, search it and review what type of result currently ranks (a short local listing, a long guide, a product page, etc.). 2) Note the format, length, and structure that appears to be rewarded. 3) Identify any obvious content gap the client's page has relative to what's ranking. |
| Tools | Manual search review |
| Deliverable | Intent-and-competitor content notes per priority keyword |
| Owner | SEO specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | Notes completed for every priority keyword |
| Quality check | Notes describe an observable pattern, not a guess |
| Common mistake | Assuming a keyword's intent without actually checking what currently ranks for it |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Build the keyword-to-page map**
| Field | Detail |
|---|---|
| Purpose | Prevents multiple pages competing against each other for the same keyword, and ensures every important keyword has an assigned home |
| Inputs | Page inventory, keyword/intent report, intent research |
| Procedure | 1) Assign one primary keyword and 2–3 secondary keywords to each key page. 2) Ensure no two pages target the same primary keyword. 3) Identify any priority keyword with no assigned page and flag it as a content gap for [14_CONTENT_STRATEGY.md](14_CONTENT_STRATEGY.md)/[15_CONTENT_PRODUCTION.md](15_CONTENT_PRODUCTION.md). |
| Tools | Shared spreadsheet |
| Deliverable | Keyword-to-page map |
| Owner | SEO specialist |
| Dependency | Task 2.1 |
| Frequency | One-time, revisited quarterly |
| KPI | Every key page has exactly one primary keyword, with no duplicates |
| Quality check | Map reviewed for keyword cannibalization (two pages targeting the same term) |
| Common mistake | Assigning the same primary keyword to both a homepage and a service page, causing them to compete against each other in search results |
| Estimated complexity | Medium |

### 4. Setup

**Task: Set up rank tracking and an optimization-tracking sheet**
| Field | Detail |
|---|---|
| Purpose | Optimization work needs a baseline and an ongoing record to know if it's working |
| Inputs | Keyword-to-page map |
| Procedure | 1) Set up rank tracking for priority keywords, if in scope. 2) Build a tracking sheet recording each page's current title, meta description, headings, and optimization status. |
| Tools | Rank-tracking tool (if in scope), shared spreadsheet |
| Deliverable | Active rank tracking (if in scope) and optimization-tracking sheet |
| Owner | SEO specialist |
| Dependency | Task 3.1 |
| Frequency | One-time setup |
| KPI | Baseline rankings recorded before any changes are made |
| Quality check | Baseline captured before Task 5 begins, so improvement can be measured |
| Common mistake | Making optimization changes before recording a baseline, making it impossible to measure impact later |
| Estimated complexity | Low |

### 5. Production

**Task: Optimize page titles, meta descriptions, and heading structure**
| Field | Detail |
|---|---|
| Purpose | These are the elements most directly reviewed by both search engines and searchers deciding whether to click |
| Inputs | Keyword-to-page map |
| Procedure | 1) Write or refine a unique, keyword-relevant title per page within length limits. 2) Write or refine a unique, compelling meta description per page. 3) Structure headings so there is exactly one H1 per page reflecting the primary keyword/topic, with logical H2/H3 subheadings beneath it. |
| Tools | CMS, character-count checker |
| Deliverable | Optimized titles, meta descriptions, and heading structure sitewide |
| Owner | SEO specialist |
| Dependency | Task 4.1 |
| Frequency | One-time initial pass, ongoing for new pages |
| KPI | Zero duplicate titles or meta descriptions across the site |
| Quality check | Every page checked for exactly one H1 |
| Common mistake | Multiple H1 tags on one page, or a heading structure that skips levels (H1 straight to H4), confusing both users and search engines |
| Estimated complexity | Medium |

**Task: Write and apply image alt text sitewide**
| Field | Detail |
|---|---|
| Purpose | Alt text helps search engines understand images and makes the site accessible to visitors using screen readers |
| Inputs | Site images, keyword-to-page map |
| Procedure | 1) Review every meaningful image sitewide. 2) Write descriptive, accurate alt text incorporating the page's relevant keyword only where genuinely natural to do so. 3) Leave purely decorative images correctly marked as decorative rather than force-fitting keywords into every image. |
| Tools | CMS media library |
| Deliverable | Alt text applied sitewide |
| Owner | SEO specialist |
| Dependency | Task 5.1 |
| Frequency | One-time initial pass, ongoing for new images |
| KPI | 100% of meaningful images have accurate, descriptive alt text |
| Quality check | Spot-check that alt text describes the image accurately, not just stuffed with keywords |
| Common mistake | Writing the same generic or keyword-stuffed alt text across every image instead of a genuine description |
| Estimated complexity | Low |

### 6. Implementation

**Task: Implement internal linking and URL structure improvements**
| Field | Detail |
|---|---|
| Purpose | Internal links help both visitors and search engines discover related pages and understand which pages matter most |
| Inputs | Keyword-to-page map, site navigation |
| Procedure | 1) Add relevant internal links between related pages (e.g. a service page linking to a related FAQ or location page). 2) Ensure the most important pages receive internal links from multiple other pages, not just the navigation menu. 3) Confirm URL slugs are short, readable, and relevant (fix only where changing a live URL won't cause needless redirect complexity — coordinate with 06 if a change is needed). |
| Tools | CMS |
| Deliverable | Improved internal linking structure and reviewed URL slugs |
| Owner | SEO specialist |
| Dependency | Task 3.1 |
| Frequency | One-time initial pass, ongoing as new pages are added |
| KPI | Every key page receives at least 2–3 relevant internal links from other pages |
| Quality check | Links checked for relevance, not added purely for volume |
| Common mistake | Changing a live, already-indexed URL without setting up a redirect, breaking existing rankings and bookmarks |
| Estimated complexity | Medium |

### 7. Testing

**Task: Validate all on-page changes render and display correctly**
| Field | Detail |
|---|---|
| Purpose | A title or meta description that looks correct in the CMS can still be truncated, duplicated, or fail to display as intended in actual search results |
| Inputs | All Task 5–6 changes |
| Procedure | 1) Preview how each title/meta description will likely display in search results (length-checked). 2) Re-crawl the site to confirm no duplicate titles/meta descriptions or missing alt text remain. 3) Confirm heading structure renders correctly. |
| Tools | Screaming Frog or equivalent, search-preview tool |
| Deliverable | Validated on-page changes |
| Owner | SEO specialist |
| Dependency | Task 6.1 |
| Frequency | One-time per optimization pass |
| KPI | Zero duplicate titles/meta descriptions remaining |
| Quality check | Independent re-crawl, not a manual page-by-page check alone |
| Common mistake | Assuming a change is live and correct without re-crawling to confirm |
| Estimated complexity | Low |

### 8. Launch

**Task: Request re-indexing and monitor initial response**
| Field | Detail |
|---|---|
| Purpose | Prompts search engines to notice and reflect the optimization changes sooner |
| Inputs | Validated changes |
| Procedure | 1) Use Search Console's URL Inspection tool to request re-indexing of significantly changed pages. 2) Note the date of the change for later performance comparison. |
| Tools | Google Search Console |
| Deliverable | Re-indexing requests logged with change dates |
| Owner | SEO specialist |
| Dependency | Task 7.1 |
| Frequency | One-time per optimization pass |
| KPI | Re-indexing requested for all significantly changed pages |
| Quality check | Change dates logged accurately for later before/after comparison |
| Common mistake | Failing to log the change date, making it impossible to later isolate the effect of the optimization from unrelated factors |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor keyword rankings, impressions, and click-through rate**
| Field | Detail |
|---|---|
| Purpose | Shows whether the optimization work is actually translating into visibility and clicks |
| Inputs | Search Console, rank-tracking tool (if in scope) |
| Procedure | 1) Review ranking position, impressions, and click-through rate per priority keyword. 2) Compare against the baseline recorded in Task 4.1. |
| Tools | Google Search Console, rank-tracking tool |
| Deliverable | Ranking and CTR monitoring log |
| Owner | SEO specialist |
| Dependency | Task 4.1 baseline |
| Frequency | Monthly |
| KPI | Log updated every month without gaps |
| Quality check | Compared against baseline and previous month, not viewed in isolation |
| Common mistake | Reacting to normal week-to-week ranking fluctuation as if it were a meaningful trend |
| Estimated complexity | Low |

### 10. Optimization

**Task: Refine underperforming pages based on evidence**
| Field | Detail |
|---|---|
| Purpose | On-page SEO is iterative — real ranking and click-through data reveals what to improve next far better than guessing upfront |
| Inputs | Monitoring log |
| Procedure | 1) Identify pages with low click-through rate despite reasonable impressions (suggesting a weak title/meta description) or low rankings despite reasonable content (suggesting thin content or weak internal linking). 2) Form a specific hypothesis and make one meaningful change. 3) Monitor the result before making further changes. |
| Tools | Monitoring log, CMS |
| Deliverable | Refined page content, titles, or internal linking |
| Owner | SEO specialist |
| Dependency | Task 9.1 |
| Frequency | Ongoing, reviewed monthly |
| KPI | Measurable improvement in the targeted metric following a change |
| Quality check | One meaningful variable changed at a time where practical |
| Common mistake | Rewriting a page's title, headings, and content simultaneously, making it impossible to know which change drove any resulting improvement |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly on-page SEO report**
| Field | Detail |
|---|---|
| Purpose | Keeps the client informed of real progress and current limitations |
| Inputs | Monitoring log, Task 10 changes made |
| Procedure | 1) Summarize ranking, impression, and click-through trends for priority keywords. 2) Summarize what was optimized that month and why. 3) Present honestly, including where results are still developing. |
| Tools | Report template |
| Deliverable | Monthly on-page SEO report |
| Owner | SEO specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Report avoids presenting normal fluctuation as a definitive trend |
| Common mistake | Reporting only positive movement and omitting pages that declined, undermining the report's credibility over time |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Apply on-page SEO standards to every new page**
| Field | Detail |
|---|---|
| Purpose | Without a standing process, new pages added later (by the agency or the client) can be published without titles, headings, or alt text properly set |
| Inputs | New page/content additions |
| Procedure | 1) Add on-page SEO checks (title, meta description, heading structure, alt text, internal links, keyword assignment) to the standard page-publishing checklist. 2) Update the keyword-to-page map whenever a new page is added. |
| Tools | Publishing checklist, keyword-to-page map |
| Deliverable | Consistently optimized new pages |
| Owner | SEO specialist |
| Dependency | Ongoing |
| Frequency | Ongoing / as-needed, reviewed quarterly |
| KPI | 100% of new pages meet the on-page SEO checklist before publishing |
| Quality check | Spot-checked during the quarterly technical SEO audit (see 06, Task 12.1) |
| Common mistake | Treating on-page SEO as a one-time project instead of a standing publishing requirement |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Keyword-to-page map
- Optimized titles, meta descriptions, and heading structure sitewide
- Alt text applied sitewide
- Improved internal linking structure

**Monthly deliverables**
- Ranking, impression, and click-through-rate report
- Evidence-based refinements to underperforming pages

**Quarterly deliverables**
- Full keyword-to-page map review and content-gap update

**Optional add-ons**
- Rank tracking for an expanded keyword set
- Content-depth expansion for thin pages (coordinated with [15_CONTENT_PRODUCTION.md](15_CONTENT_PRODUCTION.md))
- Blog/resource content SEO optimization

**Monthly deliverables note:** on-page SEO is ongoing by nature (unlike the front-loaded strategy/design/copywriting services) because rankings and search behavior continue to shift after launch.

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Pages with a unique, optimized title/meta description | Leading | Directly attributable |
| Zero keyword cannibalization across the site | Leading | Directly attributable |
| Alt text coverage | Leading | Directly attributable |
| Search impressions per priority keyword | Lagging | Influenced by overall search demand and seasonality, not only on-page work |
| Click-through rate from search results | Lagging | Directly influenced by title/meta quality, though also by ranking position itself |
| Ranking position for priority keywords | Lagging | Influenced by technical SEO (06), off-page authority (08), and competition — do not attribute solely to on-page work |
| Organic conversion rate on optimized pages | Lagging | Shared with design/copywriting/offer quality |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Search Console, Google Search itself (manual intent review) | Sufficient for baseline on-page work |
| Low-cost | Screaming Frog (free tier for smaller sites), a basic rank-tracking tool | Useful for sitewide auditing and tracking |
| Professional | Ahrefs or SEMrush content/rank-tracking modules | Justified for competitive segments needing deeper keyword and content-gap analysis |
| Low-bandwidth / mobile-first consideration | Concise, front-loaded titles and headings that remain meaningful even when truncated on a small mobile search-results display | Reflects how most target customers will encounter search results |

## H. Risks and Common Failure Modes

- **Technical risk:** on-page changes made without coordination can conflict with technical SEO settings (e.g. changing a URL without a redirect — coordinate with [06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md)).
- **Platform risk:** search engines may still rewrite an optimized title/meta description in results if they judge it insufficiently relevant to the query — write for genuine relevance, not just length compliance.
- **Client-related risk:** a client requesting unnatural keyword stuffing "to rank higher," which can both read poorly and risk being treated as manipulative by search engines.
- **Data and access risk:** working from an outdated keyword/intent report if the client's offerings have changed since strategy was completed.
- **Reputation risk:** thin, low-value content optimized only for keywords rather than genuine usefulness undermines trust and can underperform genuinely helpful competitor content.
- **Security risk:** not typically applicable directly to this service.
- **Legal or compliance risk:** on-page content for ⚠️-flagged segments must respect the same claim restrictions as copywriting — see [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md).
- **Measurement and attribution risk:** ranking movement has many contributing causes beyond on-page work; report contribution honestly rather than claiming full credit for any single change.

## I. Standard Operating Procedure

- [ ] Page inventory confirmed complete and current
- [ ] Search intent and top-ranking content analyzed for every priority keyword
- [ ] Keyword-to-page map built with no duplicate primary-keyword assignments
- [ ] Rank tracking (if in scope) and optimization-tracking sheet set up, with a baseline recorded before changes
- [ ] Titles, meta descriptions, and heading structure optimized sitewide, with zero duplicates
- [ ] Alt text written and applied to all meaningful images
- [ ] Internal linking improved; URL slugs reviewed with redirects handled where needed
- [ ] All changes validated with a re-crawl before considering the pass complete
- [ ] Re-indexing requested for significantly changed pages, with change dates logged
- [ ] Rankings, impressions, and click-through rate monitored monthly against baseline
- [ ] Underperforming pages refined one variable at a time, based on evidence
- [ ] Monthly report delivered honestly, including pages that declined
- [ ] On-page SEO checklist applied to every new page before publishing
