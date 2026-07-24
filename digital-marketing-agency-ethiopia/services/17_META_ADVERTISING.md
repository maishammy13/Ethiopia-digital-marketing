# Service: Meta Advertising

## A. Service Definition

**What it is.** Planning, setup, execution, and ongoing management of paid advertising campaigns on Facebook and Instagram via Meta Ads Manager, using the client's own connected ad account, business assets, and budget.

**What business problem it solves.** Organic reach on Meta platforms is limited and increasingly favors existing followers. Paid advertising lets a business reach a precisely targeted audience beyond its current following, on a controllable budget, with measurable results — something organic content and management alone cannot guarantee.

**Why a customer would pay for it.** Campaign strategy, audience targeting, creative testing, budget management, and conversion tracking require real skill and ongoing attention. A poorly run account can waste a meaningful budget quickly; a well-run one produces a measurable, improvable return.

**Business types that benefit most.** Businesses with a target audience genuinely reachable on Facebook/Instagram, a budget that can sustain some testing, and a working conversion mechanism (website, landing page, WhatsApp, form) to send traffic to — see the "Paid Ads" ratings in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md).

**What this does not include.** Organic account setup ([12_SOCIAL_MEDIA_ACCOUNT_SETUP.md](12_SOCIAL_MEDIA_ACCOUNT_SETUP.md)) or organic content/community management ([13_SOCIAL_MEDIA_MANAGEMENT.md](13_SOCIAL_MEDIA_MANAGEMENT.md)). Creative production from scratch — this service assembles and adapts assets already produced under [15_CONTENT_PRODUCTION.md](15_CONTENT_PRODUCTION.md)/[16_PHOTOGRAPHY_AND_VIDEO.md](16_PHOTOGRAPHY_AND_VIDEO.md) into ad formats, it does not replace those services. Website/landing-page build (03) or other ad platforms (18/19).

**How it connects to other services.** Uses assets from 15/16. Sends traffic to pages built under 01–04, [20_LEAD_GENERATION.md](20_LEAD_GENERATION.md), and [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md). Depends on the Meta Pixel installed under [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md)/[24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md). Routes captured leads into [23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md). High-performing organic content flagged by 13 becomes amplification candidates here.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Campaign strategy and setup, audience targeting, ad creative assembly, budget management, testing, optimization |
| Output | Live campaigns, ad creative variants, defined targeting sets, performance reports |
| Outcome | Increased qualified reach, traffic, leads, or sales at a controlled, continuously measured cost |
| Financial impact | Return on ad spend (ROAS); cost per lead/acquisition, evaluated against what those leads/sales are actually worth to the business |

## C. Inputs Required From the Client

- Meta Business Manager access, with the ad account owned by the client per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)
- A valid payment method attached to the ad account, controlled by the client
- The Facebook Page and Instagram account from 12, connected to the Business Manager
- Meta Pixel and/or Conversions API installed and verified (03/24)
- Campaign objective(s) and budget
- Creative assets from 15/16, or agreement on what needs producing
- The landing page, website, or WhatsApp destination traffic will be sent to
- Target-audience detail from personas (01/market-mapping)
- Any past advertising performance history
- Awareness of any advertising restrictions applicable to the client's sector (see ⚠️ flags in [../market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md](../market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md))

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm Business Manager and ad account ownership**
| Field | Detail |
|---|---|
| Purpose | Ad accounts, like domains and Google accounts, must be owned by the client to avoid future access disputes |
| Inputs | Client's Meta Business Manager |
| Procedure | 1) Confirm or set up a Business Manager owned by the client. 2) Confirm or create the ad account under that Business Manager, with the client's own payment method attached. 3) Grant the agency delegated access at the appropriate role level. |
| Tools | Meta Business Manager |
| Deliverable | Confirmed client-owned ad account with delegated agency access |
| Owner | Advertising specialist |
| Dependency | 12's completed account setup |
| Frequency | One-time per client |
| KPI | Ownership confirmed under the client's account before any spend begins |
| Quality check | Payment method confirmed to be the client's own, not the agency's |
| Common mistake | Running campaigns through the agency's own ad account "for convenience," creating a billing and ownership entanglement |
| Estimated complexity | Low |

**Task: Confirm objective and budget**
| Field | Detail |
|---|---|
| Purpose | Every campaign decision downstream depends on a clearly agreed objective and a realistic budget |
| Inputs | Client discovery |
| Procedure | 1) Confirm the primary campaign objective (awareness, traffic, leads, sales) tied to the business goal from 01. 2) Confirm a realistic budget, explaining that Meta advertising typically needs a minimum sustained spend to gather enough data to optimize effectively. |
| Tools | Discovery conversation |
| Deliverable | Confirmed objective and budget |
| Owner | Advertising specialist, account lead |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited each campaign cycle |
| KPI | Objective and budget documented before strategy begins |
| Quality check | Budget checked for realism against the objective — an unrealistically small budget for a lead-generation goal should be flagged, not silently accepted |
| Common mistake | Accepting an objective and budget combination that isn't realistically achievable without explaining the mismatch to the client upfront |
| Estimated complexity | Low |

### 2. Research

**Task: Translate personas into audience targeting**
| Field | Detail |
|---|---|
| Purpose | Meta's targeting options need to be mapped to the real target customer, not chosen generically |
| Inputs | Personas from 01/market-mapping |
| Procedure | 1) Identify relevant interest, demographic, and behavioral targeting options matching the persona. 2) Identify any available first-party data (customer list, website visitors, engaged followers) usable for custom or lookalike audiences. |
| Tools | Meta Ads Manager audience tools |
| Deliverable | Audience targeting options list |
| Owner | Advertising specialist |
| Dependency | Task 1.2 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | Targeting options tied explicitly to persona detail |
| Quality check | Targeting choices reviewed for genuine relevance, not simply broad or popular options |
| Common mistake | Targeting an audience far broader or narrower than what's actually likely to convert, without persona-based justification |
| Estimated complexity | Medium |

**Task: Competitor and category ad research**
| Field | Detail |
|---|---|
| Purpose | Reveals what messaging, offers, and creative approaches are already being used successfully in this category |
| Inputs | Competitor list |
| Procedure | 1) Review competitor ads via the Meta Ad Library. 2) Note common offers, creative styles, and messaging angles. 3) Identify a differentiated angle for the client. |
| Tools | Meta Ad Library (free) |
| Deliverable | Competitor ad research notes |
| Owner | Advertising specialist |
| Dependency | Task 2.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | At least a handful of relevant competitor ads reviewed |
| Quality check | Findings specific, not a vague impression |
| Common mistake | Copying a competitor's exact offer or creative approach instead of using it only as directional context |
| Estimated complexity | Low |

### 3. Strategy

**Task: Define campaign structure and testing plan**
| Field | Detail |
|---|---|
| Purpose | A deliberate structure (funnel stage, testing approach) produces better results than a single, untested campaign |
| Inputs | Objective, audience targeting options, creative availability |
| Procedure | 1) Define the campaign structure appropriate to the objective (e.g. a single conversion campaign for a simple offer, or an awareness-then-retargeting structure for a longer consideration cycle). 2) Define what will be tested (audience variants, creative variants, offer variants) and how, avoiding testing too many variables at once for the available budget. 3) Define the budget allocation across campaigns/ad sets. |
| Tools | Shared document |
| Deliverable | Campaign structure and testing plan |
| Owner | Advertising specialist |
| Dependency | Tasks 2.1–2.2 |
| Frequency | One-time per campaign cycle |
| KPI | Testing plan realistic for the available budget (enough spend per variant to reach a meaningful conclusion) |
| Quality check | Plan reviewed against Meta's own guidance on minimum budget per ad set for reliable delivery |
| Common mistake | Testing too many audience and creative variants simultaneously on a small budget, so no single variant gets enough spend to produce a reliable result |
| Estimated complexity | Medium |

### 4. Setup

**Task: Configure Pixel, Conversions API, and custom/lookalike audiences**
| Field | Detail |
|---|---|
| Purpose | Accurate tracking and well-built audiences are the foundation everything else in the campaign depends on |
| Inputs | Website/landing-page access, first-party data if available |
| Procedure | 1) Confirm the Meta Pixel is installed and firing correctly (coordinate with 03/24). 2) Set up the Conversions API for more resilient server-side tracking where feasible. 3) Build custom audiences (e.g. website visitors, customer list) and lookalike audiences from strong first-party data sources. |
| Tools | Meta Events Manager, Meta Pixel Helper (browser extension, free) |
| Deliverable | Verified tracking and built audiences |
| Owner | Advertising specialist |
| Dependency | Task 3.1 |
| Frequency | One-time setup, verified before every campaign launch |
| KPI | Pixel/Conversions API confirmed firing correctly using Meta's own testing tools |
| Quality check | Verified with a live test event, not assumed from installation alone |
| Common mistake | Launching a conversion-objective campaign without first confirming the Pixel actually fires on the intended conversion action |
| Estimated complexity | Medium |

### 5. Production

**Task: Assemble ad creative and copy variants**
| Field | Detail |
|---|---|
| Purpose | Converts existing content assets into properly formatted, persuasive ad units |
| Inputs | Assets from 15/16, messaging framework from 04 |
| Procedure | 1) Select and adapt assets to the required ad formats and placements (feed, Stories/Reels, various aspect ratios). 2) Write ad copy and headline variants aligned with the tested messaging angle from Task 2.2. 3) Prepare at least 2–3 creative variants per ad set to support testing. |
| Tools | Meta Ads Manager creative tools, Canva/CapCut for adaptation |
| Deliverable | Ad-ready creative and copy variants |
| Owner | Advertising specialist, with creative support from 15/16 |
| Dependency | Task 3.1 |
| Frequency | Per campaign cycle |
| KPI | Every ad set has at least 2 creative variants where the testing plan calls for it |
| Quality check | Creative checked against current Meta ad-content policy before submission |
| Common mistake | Running a single ad indefinitely without ever testing an alternative, missing the chance to find a stronger performer |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Build campaigns, ad sets, and ads in Ads Manager**
| Field | Detail |
|---|---|
| Purpose | Translates the strategy and creative into the actual live configuration |
| Inputs | Campaign structure, targeting, creative |
| Procedure | 1) Build the campaign with the correct objective. 2) Build ad sets with the defined targeting, placements, and budget/bidding settings. 3) Build ads using the prepared creative and copy. 4) Set the destination link with UTM parameters for tracking. |
| Tools | Meta Ads Manager |
| Deliverable | Fully built, unpublished campaign structure |
| Owner | Advertising specialist |
| Dependency | Tasks 4.1, 5.1 |
| Frequency | Per campaign cycle |
| KPI | Structure built matching the approved plan exactly |
| Quality check | Reviewed by a second team member before publishing, given the direct budget risk of a misconfiguration |
| Common mistake | A targeting or budget-setting error (e.g. wrong currency, wrong daily vs. lifetime budget) going unnoticed until spend has already occurred |
| Estimated complexity | Medium |

### 7. Testing

**Task: Launch a small-budget test phase and verify tracking**
| Field | Detail |
|---|---|
| Purpose | Confirms the campaign, creative, and tracking all function correctly before committing the full budget |
| Inputs | Built campaign |
| Procedure | 1) Launch with a small initial budget. 2) Verify ads are delivering and displaying correctly across placements. 3) Verify Pixel/Conversions API events are firing and attributing correctly. 4) Confirm the destination page loads correctly from the ad link. |
| Tools | Meta Ads Manager, Meta Pixel Helper |
| Deliverable | Verified, functioning test-phase campaign |
| Owner | Advertising specialist |
| Dependency | Task 6.1 |
| Frequency | Per campaign launch |
| KPI | Zero tracking or delivery issues found before scaling budget |
| Quality check | Tested by actually clicking through a live ad, not just reviewing the Ads Manager preview |
| Common mistake | Scaling budget immediately without a verified test phase, risking wasted spend on a broken tracking setup or landing page mismatch |
| Estimated complexity | Medium |

### 8. Launch

**Task: Scale budget on validated campaigns**
| Field | Detail |
|---|---|
| Purpose | Moves from cautious testing to full delivery once the setup is confirmed sound |
| Inputs | Verified test-phase results |
| Procedure | 1) Confirm test-phase delivery and tracking were clean. 2) Increase budget to the full planned level, in reasonable increments rather than a single large jump (which can disrupt Meta's delivery algorithm). |
| Tools | Meta Ads Manager |
| Deliverable | Fully scaled, live campaign |
| Owner | Advertising specialist |
| Dependency | Task 7.1 |
| Frequency | Per campaign cycle |
| KPI | Budget scaled without a delivery disruption |
| Quality check | Scaling paced gradually, per Meta's own guidance on budget-change stability |
| Common mistake | Jumping the budget from a small test amount to the full amount in one step, which can reset the ad set's learning phase and temporarily hurt performance |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor spend, delivery, and key performance metrics**
| Field | Detail |
|---|---|
| Purpose | Catches an underperforming or misconfigured campaign quickly, before significant budget is wasted |
| Inputs | Live campaign |
| Procedure | 1) Review spend pacing, CPM, CTR, cost per result, and frequency at least every few days. 2) Watch for ad fatigue (rising frequency alongside falling performance) signaling a need for creative refresh. |
| Tools | Meta Ads Manager |
| Deliverable | Ongoing performance monitoring log |
| Owner | Advertising specialist |
| Dependency | Task 8.1 |
| Frequency | At least every 2–3 days while campaigns are live |
| KPI | No campaign left unreviewed for more than a few days |
| Quality check | Metrics compared against the campaign's own benchmark and objective, not a generic industry number |
| Common mistake | Letting a clearly underperforming or overspending campaign run unattended for an extended period between reviews |
| Estimated complexity | Low |

### 10. Optimization

**Task: Pause underperformers and reallocate budget to winners**
| Field | Detail |
|---|---|
| Purpose | Concentrates budget on what's actually working, based on evidence rather than assumption |
| Inputs | Monitoring log |
| Procedure | 1) Identify ad sets/ads clearly underperforming relative to others, with enough data to be confident (not too early in the learning phase). 2) Pause or adjust them. 3) Reallocate budget toward validated winners. 4) Introduce new creative or audience tests to keep improving. |
| Tools | Meta Ads Manager |
| Deliverable | Optimized, reallocated campaign |
| Owner | Advertising specialist |
| Dependency | Task 9.1 |
| Frequency | Weekly, or as clear evidence emerges |
| KPI | Budget increasingly concentrated on demonstrated top performers over time |
| Quality check | Decisions based on statistically meaningful data volume, not a handful of early results |
| Common mistake | Pausing an ad too early, before it has exited the learning phase and had a fair chance to perform |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly advertising performance report**
| Field | Detail |
|---|---|
| Purpose | Connects ad spend to real, honestly framed business outcomes |
| Inputs | Monitoring and optimization logs |
| Procedure | 1) Summarize spend, key metrics, and results (leads/sales/traffic per the objective). 2) Calculate cost per result and, where reliable data exists, return on ad spend. 3) Present attribution honestly, noting the limits of last-click and platform-reported attribution (see [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md)). |
| Tools | Report template, Meta Ads Manager reporting |
| Deliverable | Monthly advertising performance report |
| Owner | Advertising specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Report distinguishes platform-reported results from independently verified outcomes (e.g. actual CRM-logged leads) |
| Common mistake | Presenting platform-reported conversions as unquestionably accurate without noting known attribution limitations |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Maintain account health and resolve policy issues**
| Field | Detail |
|---|---|
| Purpose | Ad accounts can face disapproved ads or, in serious cases, restrictions — proactive management minimizes disruption |
| Inputs | Ad account status |
| Procedure | 1) Monitor for disapproved ads and resolve the underlying policy issue promptly. 2) Stay current on Meta's advertising policy changes relevant to the client's sector, especially ⚠️-flagged ones. 3) Refresh creative periodically to avoid ad fatigue even on continuously running campaigns. |
| Tools | Meta Ads Manager, Meta's advertising policy documentation |
| Deliverable | Healthy, compliant, continuously fresh ad account |
| Owner | Advertising specialist |
| Dependency | Ongoing |
| Frequency | Ongoing, reviewed weekly |
| KPI | Zero unresolved disapproved ads outstanding for more than a few days |
| Quality check | Root cause of any disapproval identified and fixed, not just resubmitted unchanged |
| Common mistake | Resubmitting a disapproved ad without changing what caused the disapproval, resulting in repeated rejection |
| Estimated complexity | Medium |

## E. Deliverables

**Initial deliverables**
- Confirmed client-owned ad account with delegated access
- Audience targeting options and competitor ad research
- Campaign structure and testing plan
- Verified Pixel/Conversions API and built audiences
- Ad-ready creative and copy variants
- Launched, tested, and scaled campaign

**Monthly deliverables**
- Ongoing campaign management and optimization
- Monthly advertising performance report

**Optional add-ons**
- Expanded creative testing volume
- Dedicated retargeting campaign structure
- Seasonal/campaign-specific advertising pushes

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Tracking verified before scaling spend | Leading | Directly attributable |
| Creative variants tested per ad set | Leading | Directly attributable |
| Cost per result (per lead/sale/click, per objective) | Lagging | Directly attributable to campaign management quality |
| Return on ad spend | Lagging | Depends on accurate downstream conversion tracking (24) and honest margin data from the client — flag when either is uncertain |
| Reach, impressions, CTR | Lagging | Useful diagnostic metrics, not themselves the business outcome — always connect back to the actual objective |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Meta Ads Manager, Meta Ad Library, Meta Pixel Helper, Meta Events Manager | Covers the entire core of this service at no direct tool cost beyond ad spend itself |
| Low-cost | Basic creative-adaptation tools (Canva) | Sufficient for most SME ad creative needs |
| Professional | Third-party ad-management and reporting platforms | Justified for managing many campaigns/clients at scale, not required for a single SME account |
| Low-bandwidth / mobile-first consideration | Ad creative and landing pages built and tested for fast loading on mobile data, since most Ethiopian Meta users will see and click ads on mobile | Directly affects both ad relevance/delivery cost and actual conversion once clicked |

## H. Risks and Common Failure Modes

- **Technical risk:** a broken Pixel or Conversions API silently producing inaccurate optimization and reporting data.
- **Platform risk:** Meta's ad policies, targeting options, and algorithm behavior change over time — verify current rules before launching a new campaign type.
- **Client-related risk:** an unrealistic budget-to-objective expectation, or a client wanting to bypass the test phase to "just launch big."
- **Data and access risk:** running campaigns through an agency-owned ad account instead of the client's, creating a billing and data-ownership entanglement.
- **Reputation risk:** an ad using an exaggerated or unverifiable claim damages trust and may violate policy — see the same claim discipline as copywriting.
- **Security risk:** ad account access should follow the same role-based, minimum-necessary principle as other platform access.
- **Legal or compliance risk:** ⚠️-flagged sectors (healthcare, financial services) face specific Meta advertising restrictions that must be checked before any campaign in those categories — see [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md).
- **Measurement and attribution risk:** platform-reported conversions can differ from independently verified outcomes (CRM-logged sales); report the gap honestly rather than presenting platform numbers as unquestionable fact.

## I. Standard Operating Procedure

- [ ] Ad account confirmed client-owned with delegated agency access, and a client-controlled payment method attached
- [ ] Objective and budget confirmed as realistic for each other
- [ ] Personas translated into specific, justified audience targeting
- [ ] Competitor ad research completed for messaging/creative context
- [ ] Campaign structure and testing plan defined within realistic budget limits
- [ ] Pixel/Conversions API verified firing correctly; custom/lookalike audiences built
- [ ] Creative and copy variants prepared and checked against current ad policy
- [ ] Campaign built and peer-reviewed before publishing
- [ ] Small-budget test phase run and tracking verified before scaling
- [ ] Budget scaled gradually once the test phase is clean
- [ ] Spend, delivery, and key metrics monitored at least every 2–3 days
- [ ] Underperformers paused and budget reallocated to validated winners, based on sufficient data
- [ ] Monthly report delivered with honest attribution framing
- [ ] Disapproved ads resolved at the root cause, not just resubmitted; creative refreshed to avoid fatigue
