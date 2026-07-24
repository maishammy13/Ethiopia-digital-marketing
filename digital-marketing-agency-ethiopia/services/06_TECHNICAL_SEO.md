# Service: Technical SEO

## A. Service Definition

**What it is.** Identifies and fixes the technical factors that determine whether search engines can properly crawl, index, and rank a website — independent of its content or backlinks. Covers XML sitemaps, robots.txt, canonical tags, duplicate-content issues, structured data/schema markup, mobile usability, Core Web Vitals, and crawl/indexation health. Includes both a one-time technical audit and ongoing technical monitoring.

**What business problem it solves.** Even excellent content and design cannot rank if search engines cannot crawl or correctly index the site, or if technical errors dilute or block ranking signals. Technical problems are usually invisible to the business owner — the site "looks fine" while quietly being unable to compete in search results.

**Why a customer would pay for it.** Technical issues create a hard ceiling on organic visibility that no amount of content or advertising spend can fix on its own. Removing that ceiling is often the highest-leverage, lowest-recurring-cost SEO work available.

**Business types that benefit most.** Any business investing in organic search visibility — especially those with an existing website *not* built by this agency (where technical debt is common and unknown), larger sites with many pages/products, and multi-location businesses. See the "Search demand" and "Website" ratings in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md).

**What this service does not include.** Content writing or keyword-to-page mapping ([07_ON_PAGE_SEO.md](07_ON_PAGE_SEO.md)), earning links/citations from other sites ([08_OFF_PAGE_SEO_AND_LINK_BUILDING.md](08_OFF_PAGE_SEO_AND_LINK_BUILDING.md)), local-listing/citation management ([09_LOCAL_SEO.md](09_LOCAL_SEO.md)), or paid advertising (17/18).

**How it connects to other services.** For agency-built sites, this deepens and continuously monitors the technical setup already established in [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) (sitemap, schema, SSL, speed). For a client's existing site built elsewhere, this service typically starts with a standalone audit that becomes the foundation for [07_ON_PAGE_SEO.md](07_ON_PAGE_SEO.md) and [09_LOCAL_SEO.md](09_LOCAL_SEO.md) work. It draws on data from [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md) (Search Console).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Crawling the site, auditing technical factors, fixing sitemap/robots.txt/canonicals/schema/speed issues |
| Output | Technical audit report, corrected sitemap and robots.txt, valid structured data, improved Core Web Vitals scores |
| Outcome | Search engines can fully crawl and correctly index the site, with no technical barrier suppressing eligible pages from ranking |
| Financial impact | Unblocked organic traffic potential; more pages eligible to appear in search results; avoided ranking loss from duplicate-content or indexation problems |

## C. Inputs Required From the Client

- Full website access (CMS/hosting admin, or at minimum the access needed to implement technical fixes) — for existing non-agency-built sites, this must be explicitly arranged, see [../operations/07_ACCESS_AND_ASSET_COLLECTION.md](../operations/07_ACCESS_AND_ASSET_COLLECTION.md)
- Google Search Console access, or agreement to set up and verify ownership if none exists
- Google Analytics access
- Current sitemap and robots.txt (if any)
- History of past redesigns or URL structure changes, for redirect auditing
- Awareness of any known existing technical issues or previous SEO work
- Confirmation of all site locations/subdomains in scope (e.g. a separate blog subdomain)

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm access and verify Search Console/Analytics ownership**
| Field | Detail |
|---|---|
| Purpose | No technical SEO work can proceed without both site access and visibility into how search engines currently see the site |
| Inputs | Site credentials, Google account details |
| Procedure | 1) Confirm CMS/hosting access sufficient to implement fixes. 2) Confirm or set up and verify Google Search Console ownership in the client's own account. 3) Confirm Google Analytics access. |
| Tools | Google Search Console, Google Analytics |
| Deliverable | Confirmed access and verified Search Console property |
| Owner | SEO specialist |
| Dependency | Client onboarding complete |
| Frequency | One-time per client |
| KPI | Search Console verified within 5 business days of engagement start |
| Quality check | Verification confirmed in the client's own Google account, not the agency's |
| Common mistake | Verifying Search Console under the agency's account, creating an ownership/access problem later (see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)) |
| Estimated complexity | Low |

### 2. Research

**Task: Full technical crawl and Search Console coverage review**
| Field | Detail |
|---|---|
| Purpose | Establishes exactly what technical issues currently exist before any fix is proposed |
| Inputs | Site URL, Search Console access |
| Procedure | 1) Run a full site crawl using a crawling tool. 2) Review the Search Console Coverage/Indexing report for excluded or error pages. 3) Check for duplicate content, broken links, redirect chains, missing/duplicate meta tags, and missing structured data. 4) Check mobile-usability and Core Web Vitals reports. |
| Tools | Screaming Frog (free tier up to 500 URLs) or equivalent, Google Search Console, Google PageSpeed Insights |
| Deliverable | Raw technical findings list |
| Owner | SEO specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial audit, repeated quarterly (see §12) |
| KPI | Full site crawled with no crawl left incomplete |
| Quality check | Findings cross-checked against Search Console's own reported errors, not the crawl tool alone |
| Common mistake | Auditing only the homepage and a few key pages instead of the full site, missing issues on pages that still matter (e.g. product/service pages) |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Prioritize findings into a fix roadmap**
| Field | Detail |
|---|---|
| Purpose | Not all technical issues have equal impact; a roadmap ensures effort goes to what actually moves the needle first |
| Inputs | Raw technical findings list |
| Procedure | 1) Classify each finding by likely impact (e.g. blocking indexation vs. a minor best-practice gap) and effort to fix. 2) Sequence fixes highest-impact/lowest-effort first. 3) Flag any fix that requires development-team involvement beyond the SEO specialist's own access. |
| Tools | Shared spreadsheet |
| Deliverable | Prioritized technical SEO roadmap |
| Owner | SEO specialist |
| Dependency | Task 2.1 |
| Frequency | One-time per audit cycle |
| KPI | Roadmap reviewed and approved before fixes begin |
| Quality check | Every finding has an assigned priority and owner |
| Common mistake | Treating every finding as equally urgent, burning time on minor issues while a critical indexation blocker sits unresolved |
| Estimated complexity | Low |

### 4. Setup

**Task: Set up ongoing technical monitoring**
| Field | Detail |
|---|---|
| Purpose | Technical issues recur as a site grows (new pages, new plugins, content updates) — ongoing monitoring catches this early |
| Inputs | Verified Search Console |
| Procedure | 1) Set Search Console email alerts for new coverage errors. 2) If in scope, set up a rank-tracking tool for priority keywords. 3) Add technical SEO checks to the recurring schedule shared with [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md). |
| Tools | Google Search Console alerts, rank-tracking tool (if in scope) |
| Deliverable | Active monitoring configuration |
| Owner | SEO specialist |
| Dependency | Task 1.1 |
| Frequency | One-time setup |
| KPI | Alerts active and confirmed working |
| Quality check | Test alert triggered and received to confirm delivery |
| Common mistake | Assuming alerts are active without ever testing that they actually arrive |
| Estimated complexity | Low |

### 5. Production

**Task: Rebuild or correct the XML sitemap, robots.txt, and structured data**
| Field | Detail |
|---|---|
| Purpose | These three elements are the primary way a site directly communicates its structure and content type to search engines |
| Inputs | Roadmap findings related to sitemap/robots.txt/schema |
| Procedure | 1) Regenerate the XML sitemap to accurately reflect all indexable pages, excluding pages that shouldn't be indexed. 2) Correct robots.txt to block only what should genuinely be blocked (never accidentally block the whole site or key sections). 3) Add or correct structured data (schema markup) for the business type, and for products/services/reviews where applicable. |
| Tools | CMS sitemap plugin/feature, robots.txt editor, Schema.org markup, Google's Rich Results Test |
| Deliverable | Corrected sitemap.xml, robots.txt, and structured data |
| Owner | SEO specialist, with developer support if needed |
| Dependency | Task 3.1 |
| Frequency | One-time per audit cycle, updated as pages are added |
| KPI | Sitemap contains only valid, indexable URLs; robots.txt does not block anything unintentionally |
| Quality check | Robots.txt double-checked with a testing tool before publishing — an error here can deindex an entire site |
| Common mistake | An overly broad robots.txt rule accidentally blocking search engines from the entire site |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Fix duplicate content, canonical tags, redirects, and mobile-usability issues**
| Field | Detail |
|---|---|
| Purpose | These issues actively confuse search engines about which version of a page to rank, or actively block mobile users, both of which suppress visibility |
| Inputs | Prioritized roadmap |
| Procedure | 1) Add or correct canonical tags on any page with duplicate or near-duplicate content. 2) Fix broken links and redirect chains (a link should redirect directly to its final destination, not through multiple hops). 3) Fix any mobile-usability issues identified in Search Console (e.g. content wider than the screen, tap targets too close together). |
| Tools | CMS, Search Console Mobile Usability report |
| Deliverable | Resolved duplicate-content, canonical, redirect, and mobile-usability issues |
| Owner | SEO specialist, with developer support if needed |
| Dependency | Task 5.1 |
| Frequency | One-time per audit cycle |
| KPI | Zero unresolved mobile-usability errors in Search Console |
| Quality check | Each fix re-crawled to confirm resolution, not assumed from the fix alone |
| Common mistake | Fixing a redirect by chaining it to another existing redirect instead of pointing directly to the final URL |
| Estimated complexity | Medium |

### 7. Testing

**Task: Validate all fixes before considering the audit complete**
| Field | Detail |
|---|---|
| Purpose | A technical fix that wasn't actually implemented correctly is worse than no fix, because it creates false confidence |
| Inputs | All fixes from Tasks 5–6 |
| Procedure | 1) Re-run the site crawl and confirm each original finding is resolved. 2) Validate structured data with Google's Rich Results Test. 3) Validate sitemap and robots.txt with their respective testing tools. 4) Re-check mobile usability. |
| Tools | Screaming Frog or equivalent, Google Rich Results Test, Search Console testing tools |
| Deliverable | Validation checklist confirming each fix |
| Owner | SEO specialist |
| Dependency | Task 6.1 |
| Frequency | One-time per audit cycle |
| KPI | 100% of prioritized findings confirmed resolved or explicitly deferred with a reason |
| Quality check | Validation performed independently from the person who made the fix, where staffing allows |
| Common mistake | Marking an issue "fixed" based on the code change alone without re-testing it live |
| Estimated complexity | Low |

### 8. Launch

**Task: Resubmit sitemap and request re-indexing of fixed pages**
| Field | Detail |
|---|---|
| Purpose | Search engines don't automatically know a fix happened immediately — prompting a re-crawl speeds up the benefit reaching real search results |
| Inputs | Validated fixes |
| Procedure | 1) Resubmit the corrected sitemap in Search Console. 2) Use the URL Inspection tool to request re-indexing of the most important fixed pages. |
| Tools | Google Search Console |
| Deliverable | Resubmitted sitemap, re-indexing requests logged |
| Owner | SEO specialist |
| Dependency | Task 7.1 |
| Frequency | One-time per audit cycle |
| KPI | Sitemap resubmitted and accepted without errors |
| Quality check | Search Console confirms sitemap was read successfully |
| Common mistake | Forgetting to resubmit after making structural changes, delaying when search engines notice the fixes |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor coverage, errors, and Core Web Vitals ongoing**
| Field | Detail |
|---|---|
| Purpose | New technical issues appear as the site evolves (new pages, new plugins, content edits) — ongoing monitoring catches them before they compound |
| Inputs | Search Console alerts (Task 4.1) |
| Procedure | 1) Review the Coverage/Indexing report regularly. 2) Review Core Web Vitals trend. 3) Investigate and log any new error. |
| Tools | Google Search Console |
| Deliverable | Ongoing technical health log |
| Owner | SEO specialist |
| Dependency | Task 4.1 |
| Frequency | Monthly |
| KPI | New errors identified and triaged within the same monthly cycle |
| Quality check | Log reviewed against the previous month's for trend changes, not just point-in-time snapshots |
| Common mistake | Only checking Search Console when a client complains about a ranking drop, missing early warning signs |
| Estimated complexity | Low |

### 10. Optimization

**Task: Address newly identified technical issues as the site grows**
| Field | Detail |
|---|---|
| Purpose | A site that passed its technical audit at one point in time can accumulate new issues as content, plugins, and pages are added |
| Inputs | Ongoing technical health log |
| Procedure | 1) For each newly identified issue, assess impact and prioritize per the same method as Task 3.1. 2) Apply and validate the fix. |
| Tools | Same as Tasks 5–7 |
| Deliverable | Resolved new technical issues |
| Owner | SEO specialist |
| Dependency | Task 9.1 |
| Frequency | As needed, reviewed monthly |
| KPI | New critical issues resolved within an agreed turnaround (e.g. 5 business days) |
| Quality check | Same validation standard as the original audit — re-crawl to confirm |
| Common mistake | Letting minor recurring issues (e.g. new pages missing schema) accumulate silently instead of fixing the underlying process that creates them |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the technical SEO report**
| Field | Detail |
|---|---|
| Purpose | Technical work is largely invisible to a business owner without an explicit report connecting it to real search-visibility outcomes |
| Inputs | Findings, fixes, and current Search Console/Core Web Vitals status |
| Procedure | 1) Summarize what was found, what was fixed, and current indexation/mobile-usability/Core Web Vitals status. 2) Explain in plain language what this means for the site's ability to rank — being explicit that technical SEO removes barriers, it does not by itself guarantee ranking position (see [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md) on attribution). |
| Tools | Report template |
| Deliverable | Technical SEO report |
| Owner | SEO specialist / account lead |
| Dependency | Task 7.1, then monthly |
| Frequency | At initial audit completion, then monthly summarized within the broader SEO/marketing report |
| KPI | Report delivered on schedule |
| Quality check | Report avoids overstating what technical SEO alone can deliver |
| Common mistake | Implying that fixing technical issues guarantees a ranking improvement, when it only removes a barrier — content and off-page factors also matter |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Recurring technical SEO audit**
| Field | Detail |
|---|---|
| Purpose | A full re-audit periodically catches drift and compounding issues that ongoing monthly monitoring alone might miss |
| Inputs | Prior audit findings |
| Procedure | 1) Repeat the full crawl and Search Console review (Task 2.1). 2) Compare against the prior audit. 3) Produce an updated roadmap for any new findings. |
| Tools | Same as Task 2.1 |
| Deliverable | Updated technical audit and roadmap |
| Owner | SEO specialist |
| Dependency | Task 9.1 |
| Frequency | Quarterly |
| KPI | Quarterly audit completed on schedule |
| Quality check | Findings compared against the previous audit to track real progress, not just a fresh snapshot |
| Common mistake | Treating each audit as if it's the first one, losing the ability to show the client measurable technical improvement over time |
| Estimated complexity | Medium |

## E. Deliverables

**Initial deliverables**
- Full technical audit report with prioritized roadmap
- Corrected sitemap.xml, robots.txt, and structured data
- Resolved duplicate-content, canonical, redirect, and mobile-usability issues
- Validation checklist confirming each fix

**Monthly deliverables**
- Technical health monitoring summary (folded into the broader monthly report, see [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md))
- New issues identified and resolved within the agreed turnaround

**Quarterly deliverables**
- Full recurring technical audit and updated roadmap

**Optional add-ons**
- Rank tracking for priority keywords
- Multi-language/hreflang technical setup
- Large-site (many hundreds/thousands of pages) crawl-budget optimization

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Technical issues found and resolved | Leading | Directly attributable |
| Search Console coverage errors | Leading/Lagging | Directly attributable to technical SEO work |
| Core Web Vitals scores | Leading/Lagging | Shared with development/hosting quality (see [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) and [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md)) |
| Indexed-page count vs. total eligible pages | Lagging | Directly attributable, though new content from other services affects the total eligible count |
| Organic search traffic | Lagging | Technical SEO removes barriers but does not alone drive ranking — content quality (07), off-page authority (08), and competition all contribute; never attribute traffic changes solely to this service |
| Organic ranking position for target keywords | Lagging | Same caution — influenced by many factors beyond technical health |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Search Console, Google PageSpeed Insights, Google Rich Results Test, Screaming Frog (free tier, up to 500 URLs) | Sufficient for the majority of SME sites |
| Low-cost | Screaming Frog paid license (for larger sites), a basic rank-tracking tool | Useful once a site exceeds the free crawl limit or rank tracking is contractually in scope |
| Professional | Ahrefs or SEMrush site-audit modules | Justified for larger, more competitive, or multi-location sites needing deeper crawl and historical trend data |
| Low-bandwidth / mobile-first consideration | Prioritizing mobile-usability and Core Web Vitals fixes above cosmetic technical issues, since these directly affect the majority mobile user experience | Reflects how most target customers will actually encounter the site |

## H. Risks and Common Failure Modes

- **Technical risk:** an incorrect robots.txt or canonical-tag change can accidentally deindex pages or an entire site — always test before and after any such change.
- **Platform risk:** search-engine algorithm and Search Console feature changes occur over time; verify current best practice rather than relying on outdated guidance.
- **Client-related risk:** a client's own team or a previous developer making uncoordinated changes that reintroduce fixed issues.
- **Data and access risk:** losing Search Console access if it was verified under the wrong account — always verify under the client's own account.
- **Reputation risk:** overstating what technical SEO alone can achieve, setting an expectation of ranking improvement that content and off-page factors ultimately determine.
- **Security risk:** minimal directly, though CMS/hosting access granted for this service must follow the same access controls as other services (see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)).
- **Legal or compliance risk:** structured data (schema) must accurately reflect real business information (hours, address, reviews) — inaccurate structured data can violate platform guidelines and mislead customers.
- **Measurement and attribution risk:** organic traffic and ranking changes have many contributing causes; technical SEO's contribution should be reported honestly as "removed barriers," not claimed as the sole driver of any traffic increase.

## I. Standard Operating Procedure

- [ ] Access confirmed; Search Console and Analytics verified in the client's own account
- [ ] Full site crawl and Search Console coverage review completed
- [ ] Findings prioritized into a fix roadmap by impact and effort
- [ ] Ongoing monitoring (Search Console alerts, rank tracking if in scope) configured and tested
- [ ] Sitemap, robots.txt, and structured data corrected and validated
- [ ] Duplicate-content, canonical, redirect, and mobile-usability issues resolved
- [ ] All fixes re-crawled and independently validated
- [ ] Sitemap resubmitted; re-indexing requested for key fixed pages
- [ ] Technical health monitored monthly; new issues triaged and resolved within agreed turnaround
- [ ] Technical SEO report delivered, with contribution honestly framed relative to content/off-page factors
- [ ] Full recurring audit completed quarterly and compared against the prior audit