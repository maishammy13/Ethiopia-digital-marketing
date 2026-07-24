# Service: Google Advertising

## A. Service Definition

**What it is.** Planning, setup, execution, and ongoing management of paid campaigns on Google — Search, Display, Performance Max, and Shopping/Local campaigns where relevant — via the client's own Google Ads account, capturing active, high-intent search demand.

**What business problem it solves.** Organic SEO takes time to build authority and rankings. Google Ads lets a business appear immediately for high-intent searches (transactional keywords, "near me" queries) that would otherwise go entirely to competitors already advertising, while SEO's slower gains accumulate in parallel.

**Why a customer would pay for it.** Keyword research, campaign structure, bid strategy, Quality Score management, and conversion tracking require real skill. A budget can be wasted quickly on broad, irrelevant, or poorly tracked keywords without deliberate management.

**Business types that benefit most.** Businesses with clear, searchable purchase intent — see the "Paid Ads" and "Search demand" ratings in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md) (real estate, clinics, hotels, law firms, e-commerce, and higher-value B2B).

**What this does not include.** Organic SEO (06/07/08/09) — paid and organic are complementary, not substitutes for each other, and should be explained to the client as such. Google Business Profile management (10), though Local campaigns draw on GBP data. Website/landing-page build (03). Other advertising platforms (17/19).

**How it connects to other services.** Builds directly on the keyword/intent report from [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md)/[07_ON_PAGE_SEO.md](07_ON_PAGE_SEO.md). Local campaigns use data from [10_GOOGLE_BUSINESS_PROFILE.md](10_GOOGLE_BUSINESS_PROFILE.md). Depends on conversion tracking installed under [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md)/[24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md). Uses creative assets from 15/16 for Display/Performance Max. Routes leads into [23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md).

### How this differs from organic search work

Clarify explicitly with clients, since the two are frequently confused:

| Concept | What it is |
|---|---|
| **Google Advertising (this service)** | Paid placements — the business pays per click/impression for immediate visibility, stops appearing the moment spend stops |
| **Organic SEO (06/07/08/09)** | Unpaid rankings earned through technical health, content relevance, and authority — slower to build, but doesn't disappear when spend stops |
| **Google Business Profile (10)** | The free local listing; Local campaigns under this service can extend its reach with paid placement, but the profile itself is free to run |

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Keyword research, campaign structure and setup, ad copy and creative, bid strategy, conversion tracking, ongoing optimization |
| Output | Live campaigns, keyword lists, ad copy and extensions, performance reports |
| Outcome | Immediate visibility for high-intent searches, converting into calls, leads, or sales |
| Financial impact | Return on ad spend and cost per lead, evaluated relative to keyword competitiveness and the real value of a conversion |

## C. Inputs Required From the Client

- Google Ads account, owned by the client per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md), with a client-controlled payment method
- Linked Google Analytics, Search Console, and Google Business Profile accounts
- Verified conversion tracking on the destination site (03/24)
- Budget and campaign objective(s)
- The keyword/intent report from 01/07
- Landing page(s) or website to send traffic to
- Creative assets for Display/Performance Max campaigns (15/16)
- A product feed, if running Shopping campaigns
- Target geography
- Awareness of any advertising restrictions applicable to the client's sector

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm account ownership and link connected accounts**
| Field | Detail |
|---|---|
| Purpose | Establishes correct ownership and ensures the account has full access to the data (Analytics, Search Console, GBP) that makes campaigns effective |
| Inputs | Client's Google account |
| Procedure | 1) Confirm or set up a Google Ads account under the client's own Google account, with their payment method. 2) Link Google Analytics, Search Console, and Google Business Profile. 3) Grant the agency delegated access at the appropriate role level. |
| Tools | Google Ads, Google Analytics, Google Search Console, Google Business Profile |
| Deliverable | Confirmed, linked, client-owned Google Ads account |
| Owner | Advertising specialist |
| Dependency | 03/06's Analytics/Search Console setup, 10's verified GBP |
| Frequency | One-time per client |
| KPI | All relevant accounts linked before campaign setup begins |
| Quality check | Payment method confirmed to be the client's own |
| Common mistake | Running campaigns through an agency-owned Google Ads account, creating an ownership and data-access entanglement |
| Estimated complexity | Low |

**Task: Confirm objective and budget**
| Field | Detail |
|---|---|
| Purpose | Different objectives (calls, form leads, sales, awareness) call for different campaign types and structures |
| Inputs | Client discovery |
| Procedure | 1) Confirm the primary objective. 2) Confirm a realistic budget given the keyword competitiveness likely involved (some categories have a much higher cost per click than others). |
| Tools | Discovery conversation, Google Keyword Planner (rough cost estimates) |
| Deliverable | Confirmed objective and budget |
| Owner | Advertising specialist, account lead |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited each campaign cycle |
| KPI | Objective and budget documented before strategy begins |
| Quality check | Budget checked against a rough cost-per-click estimate for the category before committing |
| Common mistake | Setting a budget without any reference to the category's typical cost per click, leading to an unrealistic expectation of volume |
| Estimated complexity | Low |

### 2. Research

**Task: Expand and refine keyword research**
| Field | Detail |
|---|---|
| Purpose | The strategy-stage keyword/intent report needs to be expanded into a full, structured keyword list with match types and negative keywords for paid use |
| Inputs | Keyword/intent report from 01/07 |
| Procedure | 1) Expand the existing keyword list with additional relevant variations and long-tail terms. 2) Group keywords into tightly themed ad groups. 3) Build an initial negative-keyword list to exclude irrelevant traffic (e.g. "free," "jobs," or unrelated services). |
| Tools | Google Keyword Planner |
| Deliverable | Structured keyword list with ad groups and negative keywords |
| Owner | Advertising specialist |
| Dependency | Task 1.2 |
| Frequency | One-time initial pass, revisited ongoing (Task 10.1) |
| KPI | Keywords grouped into tightly themed ad groups, not one broad catch-all group |
| Quality check | Negative-keyword list reviewed for common irrelevant-traffic patterns in this category |
| Common mistake | Building one large, loosely themed ad group instead of tightly grouped ad groups, which hurts ad relevance and Quality Score |
| Estimated complexity | Medium |

**Task: Competitor ad research**
| Field | Detail |
|---|---|
| Purpose | Reveals what messaging and offers competitors are already using for the same search terms |
| Inputs | Priority keyword list |
| Procedure | 1) Manually search priority keywords and review which competitors appear and what their ad copy emphasizes. 2) Note common offers and differentiation opportunities. |
| Tools | Manual search |
| Deliverable | Competitor ad research notes |
| Owner | Advertising specialist |
| Dependency | Task 2.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | Notes completed for priority keyword themes |
| Quality check | Findings specific and used only as directional context |
| Common mistake | Copying a competitor's ad copy directly instead of using it only for competitive awareness |
| Estimated complexity | Low |

### 3. Strategy

**Task: Define campaign-type mix and structure**
| Field | Detail |
|---|---|
| Purpose | Not every campaign type fits every business — the mix should match the objective and available assets |
| Inputs | Objective, keyword research, creative availability, GBP status |
| Procedure | 1) Decide which campaign types are appropriate: Search (for direct keyword intent), Display (for broader awareness/retargeting), Performance Max (for automated cross-network reach, given sufficient conversion data and creative assets), Local campaigns (drawing on GBP), Shopping (if e-commerce with a product feed). 2) Structure Search campaigns around the themed ad groups from Task 2.1. |
| Tools | Shared document |
| Deliverable | Campaign-type mix and structure plan |
| Owner | Advertising specialist |
| Dependency | Task 2.1 |
| Frequency | One-time per campaign cycle |
| KPI | Every included campaign type has a clear, stated reason for inclusion |
| Quality check | Performance Max recommended only where sufficient conversion tracking and creative assets exist to feed it properly |
| Common mistake | Defaulting to Performance Max alone for a new account with no conversion history, when its automated bidding needs data to work well |
| Estimated complexity | Medium |

**Task: Define bid strategy**
| Field | Detail |
|---|---|
| Purpose | Bid strategy should match the account's data maturity — automated Smart Bidding needs enough conversion volume to work effectively |
| Inputs | Conversion tracking status, budget |
| Procedure | 1) For a new account with limited conversion history, start with a manual or conversion-focused strategy appropriate to low data volume. 2) Plan a transition to more automated Smart Bidding strategies once sufficient conversion data accumulates. |
| Tools | Google Ads bid strategy settings |
| Deliverable | Defined bid-strategy plan and transition criteria |
| Owner | Advertising specialist |
| Dependency | Task 3.1 |
| Frequency | One-time per campaign cycle, revisited as data accumulates |
| KPI | Bid strategy matched to actual data maturity, not assumed |
| Quality check | Transition criteria to a more automated strategy explicitly defined (e.g. a minimum number of conversions per month) |
| Common mistake | Switching to an aggressive automated bidding strategy before the account has enough conversion data to support it, producing erratic results |
| Estimated complexity | Medium |

### 4. Setup

**Task: Configure conversion tracking**
| Field | Detail |
|---|---|
| Purpose | Google Ads' own optimization and reporting depend entirely on accurate conversion tracking |
| Inputs | Website/landing page access |
| Procedure | 1) Set up Google Ads conversion tracking directly, or import verified conversions from Google Analytics. 2) Confirm each tracked action (call, form, WhatsApp click) matches a real conversion goal from strategy (01). 3) Test that each conversion action fires correctly. |
| Tools | Google Ads conversion tracking, Google Tag Manager |
| Deliverable | Verified conversion tracking |
| Owner | Advertising specialist |
| Dependency | 03/24's Analytics/tracking setup |
| Frequency | One-time setup, verified before every campaign launch |
| KPI | Every relevant conversion action confirmed firing correctly |
| Quality check | Verified with a live test conversion, not assumed from setup alone |
| Common mistake | Launching a conversion-focused campaign without first confirming tracking actually works, making both optimization and reporting unreliable from day one |
| Estimated complexity | Medium |

### 5. Production

**Task: Write ad copy and configure extensions**
| Field | Detail |
|---|---|
| Purpose | Strong, relevant ad copy directly affects both click-through rate and Quality Score, which in turn affects cost |
| Inputs | Keyword ad groups, messaging framework from 04 |
| Procedure | 1) Write multiple headline and description variants per ad group, incorporating the group's core keyword theme naturally. 2) Configure relevant ad extensions (sitelinks, call, location, price, structured snippets) to increase ad prominence and provide more useful information. |
| Tools | Google Ads |
| Deliverable | Ad copy variants and configured extensions |
| Owner | Advertising specialist, with copywriting support |
| Dependency | Task 2.1 |
| Frequency | Per campaign cycle |
| KPI | Every ad group has multiple headline/description variants and at least the core relevant extensions enabled |
| Quality check | Copy checked against current Google Ads policy before submission |
| Common mistake | Leaving extensions unconfigured, missing an easy, free way to make ads larger and more informative in results |
| Estimated complexity | Medium |

**Task: Prepare Display/Performance Max creative assets**
| Field | Detail |
|---|---|
| Purpose | These campaign types require a range of image, headline, and description assets to assemble automatically across formats |
| Inputs | Assets from 15/16 |
| Procedure | 1) Select and format images/logos to the required sizes. 2) Write the range of headline/description variants these campaign types require. |
| Tools | Google Ads asset library |
| Deliverable | Formatted creative asset set for Display/Performance Max |
| Owner | Advertising specialist, with creative support |
| Dependency | Task 3.1 (if these campaign types are in scope) |
| Frequency | Per campaign cycle, refreshed periodically |
| KPI | Full required asset set provided, not a minimal/partial set |
| Quality check | Asset diversity checked, since a thin asset set limits these formats' effectiveness |
| Common mistake | Supplying only the bare minimum number of assets, limiting the campaign type's ability to test and optimize combinations |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Build campaigns, ad groups, keywords, ads, and extensions**
| Field | Detail |
|---|---|
| Purpose | Translates the strategy and creative into the actual live account structure |
| Inputs | Campaign structure, keywords, ad copy, extensions |
| Procedure | 1) Build each campaign with the correct type, budget, geography, and bid strategy. 2) Build themed ad groups with their keywords and appropriate match types. 3) Add ads and extensions. 4) Add UTM parameters to destination URLs for tracking consistency. |
| Tools | Google Ads |
| Deliverable | Fully built, unpublished campaign structure |
| Owner | Advertising specialist |
| Dependency | Tasks 4.1, 5.1–5.2 |
| Frequency | Per campaign cycle |
| KPI | Structure built matching the approved plan exactly |
| Quality check | Peer-reviewed before publishing given the direct budget risk of a misconfiguration |
| Common mistake | Using broad match on all keywords without adequate negative-keyword coverage, leading to irrelevant clicks and wasted spend |
| Estimated complexity | Medium |

### 7. Testing

**Task: Launch a controlled test phase and verify tracking**
| Field | Detail |
|---|---|
| Purpose | Confirms the campaign and tracking function correctly before committing full budget |
| Inputs | Built campaign |
| Procedure | 1) Launch with a controlled initial budget. 2) Verify ads are showing correctly for target keywords. 3) Verify conversion tracking fires correctly on a real test conversion. 4) Confirm the landing page loads correctly and matches the ad's promise (message match). |
| Tools | Google Ads, Google Tag Assistant |
| Deliverable | Verified, functioning test-phase campaign |
| Owner | Advertising specialist |
| Dependency | Task 6.1 |
| Frequency | Per campaign launch |
| KPI | Zero tracking or delivery issues found before scaling budget |
| Quality check | Landing page message-match checked explicitly — the page should deliver on exactly what the ad promised |
| Common mistake | Sending ad traffic to a generic homepage instead of a landing page matching the specific ad's offer, hurting both conversion rate and Quality Score |
| Estimated complexity | Medium |

### 8. Launch

**Task: Scale budget and expand campaign types as data supports**
| Field | Detail |
|---|---|
| Purpose | Moves from cautious testing to full delivery, and expands into additional campaign types once there's enough data to support them |
| Inputs | Verified test-phase results |
| Procedure | 1) Confirm test-phase delivery and tracking were clean. 2) Increase budget to the full planned level. 3) Once sufficient Search campaign conversion data exists, consider expanding into Performance Max or Display per the Task 3.1 plan. |
| Tools | Google Ads |
| Deliverable | Fully scaled, live campaign(s) |
| Owner | Advertising specialist |
| Dependency | Task 7.1 |
| Frequency | Per campaign cycle |
| KPI | Budget scaled without a delivery disruption |
| Quality check | Expansion into new campaign types only after the data-maturity criteria from Task 3.2 are met |
| Common mistake | Launching every planned campaign type simultaneously on day one, before the account has any conversion history to inform automated bidding |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor spend, Quality Score, and conversion performance**
| Field | Detail |
|---|---|
| Purpose | Catches waste or underperformance quickly, since Google Ads spend can accumulate fast on a misconfigured account |
| Inputs | Live campaigns |
| Procedure | 1) Review spend pacing, CPC, CTR, Quality Score, and conversion rate at least every few days. 2) Review the search terms report for irrelevant queries triggering ads. |
| Tools | Google Ads |
| Deliverable | Ongoing performance monitoring log |
| Owner | Advertising specialist |
| Dependency | Task 8.1 |
| Frequency | At least every 2–3 days while campaigns are live |
| KPI | No campaign left unreviewed for more than a few days |
| Quality check | Search terms report reviewed specifically, not just top-line metrics |
| Common mistake | Never reviewing the search terms report, letting irrelevant queries continue consuming budget indefinitely |
| Estimated complexity | Low |

### 10. Optimization

**Task: Refine keywords, negatives, bids, and ad copy based on evidence**
| Field | Detail |
|---|---|
| Purpose | Continuous refinement is what separates a well-run account from a "set it and forget it" one |
| Inputs | Monitoring log, search terms report |
| Procedure | 1) Add new negative keywords from irrelevant search terms. 2) Pause underperforming keywords/ads with sufficient data to be confident. 3) Test new ad copy variants against current top performers. 4) Adjust bids/budget allocation toward what's working. |
| Tools | Google Ads |
| Deliverable | Optimized, refined campaign |
| Owner | Advertising specialist |
| Dependency | Task 9.1 |
| Frequency | Weekly, or as clear evidence emerges |
| KPI | Negative-keyword list and ad copy variants actively evolving over time, not static |
| Quality check | Decisions based on statistically meaningful data volume |
| Common mistake | Letting the negative-keyword list go stale after the initial setup, missing months of newly emerging irrelevant search terms |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly Google Ads performance report**
| Field | Detail |
|---|---|
| Purpose | Connects spend to real, honestly framed business outcomes |
| Inputs | Monitoring and optimization logs |
| Procedure | 1) Summarize spend, key metrics (CPC, CTR, Quality Score trend, conversion rate), and results per objective. 2) Calculate cost per result and, where reliable, return on ad spend. 3) Present attribution honestly, noting known limitations (see [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md)). |
| Tools | Report template, Google Ads reporting |
| Deliverable | Monthly Google Ads performance report |
| Owner | Advertising specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Platform-reported conversions distinguished from independently verified outcomes |
| Common mistake | Reporting clicks or impressions as the headline success metric instead of connecting to actual leads/sales |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Maintain account health and policy compliance**
| Field | Detail |
|---|---|
| Purpose | Keeps the account running smoothly and avoids policy-related disapprovals or restrictions |
| Inputs | Ad account status |
| Procedure | 1) Monitor for disapproved ads and resolve the underlying policy issue promptly. 2) Stay current on Google Ads policy changes relevant to the client's sector, especially ⚠️-flagged ones. 3) Refresh ad copy and creative periodically. 4) Review budget pacing to avoid either overspend or underspend relative to the monthly budget. |
| Tools | Google Ads, Google Ads policy documentation |
| Deliverable | Healthy, compliant, well-paced ad account |
| Owner | Advertising specialist |
| Dependency | Ongoing |
| Frequency | Ongoing, reviewed weekly |
| KPI | Zero unresolved disapproved ads outstanding for more than a few days; budget pacing within a reasonable range of the monthly target |
| Quality check | Root cause of any disapproval identified and fixed |
| Common mistake | A campaign underspending its budget for weeks without anyone noticing, quietly leaving results on the table |
| Estimated complexity | Medium |

## E. Deliverables

**Initial deliverables**
- Confirmed, linked, client-owned Google Ads account
- Structured keyword list with ad groups and negative keywords
- Campaign-type mix, structure, and bid-strategy plan
- Verified conversion tracking
- Ad copy, extensions, and (where relevant) Display/Performance Max creative assets
- Launched, tested, and scaled campaign(s)

**Monthly deliverables**
- Ongoing campaign management and optimization
- Monthly Google Ads performance report

**Optional add-ons**
- Shopping campaign setup for e-commerce clients with a product feed
- Expanded Display/Performance Max creative asset production
- Seasonal/campaign-specific advertising pushes

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Conversion tracking verified before scaling spend | Leading | Directly attributable |
| Quality Score trend | Leading | Directly attributable to ad relevance and landing page quality |
| Negative-keyword list actively maintained | Leading | Directly attributable |
| Cost per result | Lagging | Directly attributable to campaign management quality |
| Return on ad spend | Lagging | Depends on accurate downstream conversion tracking and honest margin data — flag when either is uncertain |
| Impressions, clicks, CTR | Lagging | Useful diagnostics, not themselves the business outcome |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Ads, Google Keyword Planner, Google Tag Manager, Google Analytics, Google Tag Assistant | Covers the entire core of this service at no direct tool cost beyond ad spend |
| Low-cost | Basic creative-adaptation tools for Display/Performance Max assets | Sufficient for most SME needs |
| Professional | Third-party PPC management and reporting platforms | Justified for managing many campaigns/clients at scale |
| Low-bandwidth / mobile-first consideration | Landing pages built and tested for fast mobile loading, since Google Ads click cost is wasted if the destination page is slow to load on mobile data | Directly affects both Quality Score and actual conversion |

## H. Risks and Common Failure Modes

- **Technical risk:** broken conversion tracking silently producing inaccurate bidding optimization and reporting.
- **Platform risk:** Google Ads policies, campaign types, and automated bidding behavior change over time — verify current guidance before launching a new campaign type.
- **Client-related risk:** an unrealistic budget-to-keyword-competitiveness expectation, or pressure to skip the controlled test phase.
- **Data and access risk:** running campaigns through an agency-owned account instead of the client's, creating an ownership and data-access entanglement.
- **Reputation risk:** ad copy making an exaggerated or unverifiable claim damages trust and risks policy violation.
- **Security risk:** account access should follow the same role-based, minimum-necessary principle as other platform access.
- **Legal or compliance risk:** ⚠️-flagged sectors face specific Google Ads restrictions (healthcare, financial services, and others) that must be checked before any campaign in those categories.
- **Measurement and attribution risk:** platform-reported conversions can diverge from independently verified outcomes; report the gap honestly.

## I. Standard Operating Procedure

- [ ] Google Ads account confirmed client-owned, with Analytics/Search Console/GBP linked and a client-controlled payment method
- [ ] Objective and budget confirmed realistic against keyword-competitiveness expectations
- [ ] Keyword research expanded from strategy into themed ad groups with a negative-keyword list
- [ ] Competitor ad research completed for context
- [ ] Campaign-type mix and structure defined with a stated reason per included type
- [ ] Bid strategy matched to actual data maturity, with a defined transition plan
- [ ] Conversion tracking configured and verified firing correctly
- [ ] Ad copy, extensions, and Display/Performance Max assets prepared and policy-checked
- [ ] Campaign built and peer-reviewed before publishing
- [ ] Controlled test phase run and tracking/message-match verified before scaling
- [ ] Budget scaled and additional campaign types added only once data-maturity criteria are met
- [ ] Spend, Quality Score, and conversion performance monitored at least every 2–3 days
- [ ] Search terms report reviewed regularly; negative keywords and ad copy refined based on evidence
- [ ] Monthly report delivered with honest attribution framing
- [ ] Disapproved ads resolved at the root cause; budget pacing reviewed to avoid over/underspend
