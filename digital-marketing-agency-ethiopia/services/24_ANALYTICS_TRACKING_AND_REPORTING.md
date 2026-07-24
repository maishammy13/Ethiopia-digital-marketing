# Service: Analytics, Tracking, and Reporting

## A. Service Definition

**What it is.** Installs, verifies, and maintains the full measurement stack across a client's digital presence — Google Analytics, Google Search Console, Google Business Profile insights, Meta/TikTok pixels, call/form/WhatsApp/booking tracking, and CRM integration — and produces honest, regular reporting connecting marketing activity to real business outcomes.

**What business problem it solves.** Without proper measurement, neither the business nor the agency can reliably tell what's actually working. Just as damaging, sloppy or overstated measurement actively misleads a client into bad decisions — cutting a channel that's genuinely working, or continuing to fund one that isn't, because the reported numbers weren't trustworthy.

**Why a customer would pay for it.** Correct tracking setup and honest, careful interpretation require real technical skill and integrity. This service is the foundation every other service's reporting depends on — every single service file in this system cross-references it for its own KPIs.

**Business types that benefit most.** Every client, universally. This is measurement infrastructure, not a segment-specific service — its value scales with how much marketing activity is happening across other services, not with any particular business type.

**What this does not include.** The advertising platforms' own campaign management (17/18/19 run the campaigns; this service measures and reports on them). CRM pipeline management itself ([23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md) owns the system; this service instruments it and reports on its data). The initial technical tag installation performed during a website build ([03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) does the initial install; this service owns ongoing verification, health monitoring, and the reporting layer built on top).

**How it connects to other services.** This is the measurement layer underneath the entire system — nearly every other service file in `services/` references this one for its own KPI attribution caveats. It depends on tags installed under 03, data from 10's Google Business Profile insights, pixels from 17/19, conversion data from 18, lead data from 20/23, and messaging performance from 22.

### What can and cannot be reliably measured

This distinction must be understood before any dashboard or report is built, and explained honestly to every client — see the Writing and Formatting philosophy in [../00_README.md](../00_README.md).

| Can be measured with reasonable confidence | Cannot be measured reliably, or requires caution |
|---|---|
| Website sessions, pageviews, and on-site behavior (Google Analytics) | The precise causal impact of one specific piece of content or one specific post — behavior is influenced by many simultaneous factors |
| Search impressions, clicks, and average position (Search Console) | Exact organic ranking-position causality for any single SEO change, given constant algorithm and competitor movement |
| Ad platform-reported clicks, impressions, and platform-attributed conversions | Whether a platform-attributed conversion would have happened anyway without the ad (true incrementality) — platforms tend to over-credit themselves |
| Form submissions, tracked call volume, tracked WhatsApp-link clicks | The exact identity/path of every single visitor across devices — cross-device journeys are frequently undercounted |
| Google Business Profile-reported calls, clicks, direction requests, and views | The precise revenue value of a GBP view versus a competitor's, without further offline confirmation |
| Email/SMS/WhatsApp campaign delivery, open, and click rates (platform-reported) | True open rates on some channels (e.g. Apple Mail privacy features inflate reported email opens) |
| Revenue when a sale can be directly, systematically logged back to a specific lead source (CRM-linked) | Revenue attribution when sales happen offline/in person with no consistent system for asking or recording "how did you hear about us" |

**On attribution models:** last-click attribution (crediting the final click before a conversion) is the simplest and most common model, but it systematically over-credits the last touchpoint (often paid search or direct) and under-credits earlier touchpoints (social, content, word of mouth) that contributed to the decision. Where a client's tools support it, note when a data-driven or position-based model would give a more balanced picture, and explain the difference plainly rather than presenting last-click numbers as the full story.

**On correlation versus causation:** a metric moving after a marketing action does not prove that action caused the movement — seasonality, competitor activity, word of mouth, and simple random variation all move numbers too. State findings using cautious language ("traffic increased following the campaign, though other factors may have contributed") rather than definitive causal claims, unless a genuine controlled test (see [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md)) actually supports a causal claim.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Tracking installation and verification, dashboard building, monthly/quarterly reporting, attribution analysis |
| Output | A verified, complete tracking stack, a live dashboard, monthly reports, quarterly strategy reviews |
| Outcome | The business and the agency both have an accurate, honest picture of what's actually producing results |
| Financial impact | Better-informed budget allocation across channels; avoided wasted spend continuing an underperforming channel that looked good only due to measurement error |

## C. Inputs Required From the Client

- Access to every platform in the client's marketing stack (GA4, Search Console, GBP, Meta/TikTok business accounts, CRM)
- Website/tag-management access
- Phone system access for call tracking, if in scope
- WhatsApp Business account from 12
- Clearly defined business goals and the specific actions that count as a conversion
- A reporting cadence preference, within the standard monthly/quarterly structure

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Inventory every channel and platform needing tracking**
| Field | Detail |
|---|---|
| Purpose | A complete inventory prevents a measurement blind spot in any active marketing channel |
| Inputs | List of active/planned services from the client's package |
| Procedure | 1) List every active marketing channel (website, GBP, social, paid ad platforms, email/SMS/WhatsApp). 2) For each, confirm what tracking should exist. |
| Tools | Shared checklist |
| Deliverable | Complete channel/tracking inventory |
| Owner | Analytics specialist |
| Dependency | Onboarding complete, package scope known |
| Frequency | One-time, updated whenever a new service/channel is added |
| KPI | Every active channel represented in the inventory |
| Quality check | Cross-checked against the client's actual active services in [../02_SERVICE_CATALOGUE.md](../02_SERVICE_CATALOGUE.md) |
| Common mistake | Building a tracking plan around only the most obvious channel (usually the website) and missing GBP, social, or messaging tracking entirely |
| Estimated complexity | Low |

**Task: Confirm the business's real conversion goals**
| Field | Detail |
|---|---|
| Purpose | Tracking should measure what the business actually cares about, not a generic default list of metrics |
| Inputs | Conversion goals from [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md) |
| Procedure | 1) Confirm the specific actions that count as a meaningful conversion for this business (a call, a form, a WhatsApp message, a booking, a sale). 2) Confirm relative priority if there are multiple. |
| Tools | Shared document |
| Deliverable | Confirmed conversion-goal list |
| Owner | Analytics specialist |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited if business goals change |
| KPI | Every conversion goal specific and named, not generic |
| Quality check | Reviewed against 01's original conversion-goal definition for consistency |
| Common mistake | Tracking generic engagement metrics (pageviews, session duration) as if they were the actual business goal, rather than tracking real conversion actions |
| Estimated complexity | Low |

### 2. Research

**Task: Audit existing tracking for gaps and errors**
| Field | Detail |
|---|---|
| Purpose | Many clients already have some tracking installed that is broken, incomplete, or duplicated — this must be found before building anything new on top of it |
| Inputs | Existing platform access |
| Procedure | 1) Review each existing tag/pixel/tracking installation for whether it's actually firing correctly. 2) Check for duplicate tracking (e.g. GA installed twice, inflating numbers) or missing tracking on key pages. |
| Tools | Tag-verification browser extensions (Google Tag Assistant, Meta Pixel Helper), GA4 real-time reports |
| Deliverable | Existing-tracking audit report |
| Owner | Analytics specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial audit, repeated at each quarterly review |
| KPI | Every existing tracking installation checked and its status documented |
| Quality check | Verified live, not assumed working from installation code being present |
| Common mistake | Assuming a previously installed pixel or tag is working correctly just because the installation code is present in the page source |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Design the full measurement plan**
| Field | Detail |
|---|---|
| Purpose | Provides a single blueprint for what's tracked where, avoiding an ad hoc, inconsistent buildup of tracking over time |
| Inputs | Channel inventory, conversion goals, audit findings |
| Procedure | 1) Map each conversion goal to the specific tracking mechanism that will capture it. 2) Design a consistent UTM parameter taxonomy for all campaign links across every channel. 3) Decide the attribution approach appropriate to the client's tools and data volume. |
| Tools | Shared document |
| Deliverable | Documented measurement plan and UTM taxonomy |
| Owner | Analytics specialist |
| Dependency | Task 2.1 |
| Frequency | One-time, revisited annually or when a major new channel is added |
| KPI | Every conversion goal mapped to a specific tracking mechanism |
| Quality check | UTM taxonomy reviewed for consistency (e.g. always lowercase, consistent source/medium naming) so future reports aren't fragmented by inconsistent tagging |
| Common mistake | Allowing inconsistent UTM tagging across different campaigns/services, which fragments reporting into many small, hard-to-analyze source variants |
| Estimated complexity | Medium |

### 4. Setup

**Task: Install and verify the core tracking stack**
| Field | Detail |
|---|---|
| Purpose | Establishes the actual technical foundation everything else depends on |
| Inputs | Measurement plan |
| Procedure | 1) Install/verify Google Analytics (GA4) and Search Console, in the client's own account. 2) Link Google Business Profile insights. 3) Install/verify Meta Pixel and TikTok Pixel where those advertising services are active. 4) Set up call tracking, form-submission tracking, WhatsApp-click tracking, and booking tracking as applicable. 5) Connect tracking data into the CRM from 23. |
| Tools | Google Tag Manager (recommended for centralized tag management), GA4, Search Console, Meta Events Manager, TikTok Events Manager |
| Deliverable | Installed, verified core tracking stack |
| Owner | Analytics specialist |
| Dependency | Task 3.1 |
| Frequency | One-time setup, re-verified at each quarterly review |
| KPI | Every planned tracking mechanism confirmed firing correctly |
| Quality check | Verified with each platform's own live testing tool, not assumed from installation alone |
| Common mistake | Installing tracking codes without testing that they actually fire on the intended action, discovering the gap only when the first report comes up empty |
| Estimated complexity | High |

### 5. Production

**Task: Build the reporting dashboard**
| Field | Detail |
|---|---|
| Purpose | Consolidates data from multiple sources into one place the client can actually understand at a glance |
| Inputs | Verified tracking stack |
| Procedure | 1) Build a dashboard pulling together the key metrics per conversion goal, across channels. 2) Design it for clarity — the client's actual priority metrics prominent, secondary detail available but not cluttering the main view. |
| Tools | Google Looker Studio (free) or equivalent, connected to GA4/Search Console/ad platforms |
| Deliverable | Live reporting dashboard |
| Owner | Analytics specialist |
| Dependency | Task 4.1 |
| Frequency | One-time build, refined ongoing |
| KPI | Dashboard reflects every confirmed conversion goal |
| Quality check | Reviewed with a non-technical team member for clarity before presenting to the client |
| Common mistake | Building a dashboard crammed with every available metric instead of prioritizing the handful that actually matter to this specific business |
| Estimated complexity | High |

### 6. Implementation

**Task: Document what's tracked and how, for internal and client reference**
| Field | Detail |
|---|---|
| Purpose | Prevents tracking knowledge from living only in one person's head, and gives the client a clear reference for what their numbers actually mean |
| Inputs | Completed setup |
| Procedure | 1) Document every tracked conversion action, its source, and any known limitation. 2) Document the UTM taxonomy for consistent future use by every team working on the account. |
| Tools | Shared document |
| Deliverable | Tracking documentation |
| Owner | Analytics specialist |
| Dependency | Task 5.1 |
| Frequency | One-time, kept updated |
| KPI | Documentation complete and accessible to every team member who might add a new campaign |
| Quality check | Reviewed by another team member for completeness |
| Common mistake | Keeping tracking knowledge undocumented, so a new team member unknowingly breaks the UTM taxonomy or misunderstands what a metric represents |
| Estimated complexity | Low |

### 7. Testing

**Task: Test every tracked conversion action end to end**
| Field | Detail |
|---|---|
| Purpose | Confirms the entire measurement system works correctly before the client starts making decisions based on it |
| Inputs | Fully built tracking stack and dashboard |
| Procedure | 1) Trigger each tracked conversion action as a real user would (submit a form, make a test call, click a WhatsApp link, complete a test booking). 2) Confirm each appears correctly in the relevant platform and flows through to the dashboard. |
| Tools | Real device/channel testing |
| Deliverable | Verified, fully functioning measurement system |
| Owner | Analytics specialist |
| Dependency | Task 6.1 |
| Frequency | One-time before launch, repeated at each quarterly review |
| KPI | Every conversion action confirmed tracked end to end, from action to dashboard |
| Quality check | Tested as a real user would interact, not verified only in a platform's technical debug view |
| Common mistake | Confirming a pixel fires in a debug tool without confirming the resulting conversion actually appears correctly in reporting and the dashboard |
| Estimated complexity | Medium |

### 8. Launch

**Task: Activate the reporting cadence and present the baseline**
| Field | Detail |
|---|---|
| Purpose | Establishes the starting point everything else will be measured against, and formally begins the reporting relationship |
| Inputs | Verified system |
| Procedure | 1) Record baseline figures for every tracked metric. 2) Present the dashboard and reporting cadence to the client, explaining what can and cannot be reliably measured per the framework in Section A. |
| Tools | Dashboard, presentation |
| Deliverable | Recorded baseline and client-briefed reporting cadence |
| Owner | Analytics specialist, account lead |
| Dependency | Task 7.1 |
| Frequency | One-time per client |
| KPI | Baseline recorded and cadence confirmed before the first monthly report is due |
| Quality check | Client explicitly walked through the measurement-limitations framework, not just shown the dashboard |
| Common mistake | Presenting the dashboard without explaining its limitations, setting the client up to misinterpret a future number |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor tracking health continuously**
| Field | Detail |
|---|---|
| Purpose | Tags and integrations break silently — a CMS update, a platform API change, or a code edit elsewhere can quietly stop data flowing |
| Inputs | Live tracking stack |
| Procedure | 1) Periodically check that all tags/integrations are still firing correctly. 2) Watch for a sudden, unexplained drop in any tracked metric, which often signals a broken tag rather than a real change in activity. |
| Tools | GA4 real-time reports, tag-verification tools |
| Deliverable | Tracking-health monitoring log |
| Owner | Analytics specialist |
| Dependency | Task 8.1 |
| Frequency | Weekly light check, full re-verification quarterly |
| KPI | Any tracking gap identified within the same week it occurs |
| Quality check | A sudden metric drop always investigated as a possible tracking failure before being reported as a real performance change |
| Common mistake | Reporting a sharp drop in leads as a real business problem when the actual cause was a broken form-tracking tag after an unrelated website update |
| Estimated complexity | Low |

### 10. Optimization

**Task: Fix tracking gaps and refine the dashboard**
| Field | Detail |
|---|---|
| Purpose | Keeps the measurement system accurate and genuinely useful as the business and its channels evolve |
| Inputs | Monitoring log, client feedback on the dashboard |
| Procedure | 1) Fix any identified tracking gap promptly. 2) Refine the dashboard based on what the client actually finds useful versus what goes unused. |
| Tools | Same as setup tasks |
| Deliverable | Corrected tracking and refined dashboard |
| Owner | Analytics specialist |
| Dependency | Task 9.1 |
| Frequency | As needed, reviewed quarterly |
| KPI | Zero unresolved tracking gaps carried past one reporting cycle |
| Quality check | Dashboard changes checked with the client before finalizing, since usefulness is ultimately their judgment |
| Common mistake | Never revisiting the original dashboard design even after the client indicates certain metrics aren't useful to them |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver monthly reports and quarterly strategy reviews**
| Field | Detail |
|---|---|
| Purpose | This is the direct output the client experiences most regularly, and where the honesty standard from Section A must be applied consistently |
| Inputs | Dashboard data |
| Procedure | 1) Each month, summarize performance against the confirmed conversion goals, per channel, using the attribution caveats appropriate to each metric. 2) Each quarter, provide a deeper strategic review connecting trends across channels and recommending resource-allocation changes based on the evidence. |
| Tools | Dashboard, report template ([../templates/07_MONTHLY_REPORT_TEMPLATE.md](../templates/07_MONTHLY_REPORT_TEMPLATE.md)) |
| Deliverable | Monthly report and quarterly strategy review |
| Owner | Analytics specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly reports; quarterly strategy reviews |
| KPI | Delivered on a consistent schedule |
| Quality check | Every claim in the report checked against the "what can/cannot be measured" framework before it goes to the client |
| Common mistake | Presenting a platform-reported number as an unqualified fact when it actually carries a known attribution limitation that should be disclosed |
| Estimated complexity | Medium |

### 12. Maintenance

**Task: Adapt to platform changes and enforce ongoing tagging discipline**
| Field | Detail |
|---|---|
| Purpose | Tracking platforms and their policies change; without active maintenance, the measurement system gradually degrades |
| Inputs | Platform update notices |
| Procedure | 1) Stay current on major changes to GA4, Search Console, and ad-platform tracking/privacy policy that could affect data accuracy. 2) Enforce the UTM taxonomy across every team adding new campaigns, correcting any drift. |
| Tools | Platform documentation, UTM taxonomy documentation |
| Deliverable | An up-to-date, consistently tagged measurement system |
| Owner | Analytics specialist |
| Dependency | Ongoing |
| Frequency | Ongoing, reviewed quarterly |
| KPI | Zero UTM taxonomy drift found during the quarterly review |
| Quality check | Spot-checked against the documented taxonomy each quarter |
| Common mistake | Letting a new campaign use inconsistent, ad hoc UTM parameters "just this once," gradually fragmenting the whole reporting system's source data |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Complete channel/tracking inventory and confirmed conversion goals
- Existing-tracking audit report
- Documented measurement plan and UTM taxonomy
- Installed, verified core tracking stack
- Live reporting dashboard
- Tracking documentation
- Recorded baseline, with the client briefed on measurement limitations

**Monthly deliverables**
- Tracking-health monitoring
- Monthly performance report

**Quarterly deliverables**
- Full tracking re-verification
- Quarterly strategy review

**Optional add-ons**
- Offline conversion tracking integration (e.g. importing in-store sales data to close the loop with online activity)
- Advanced multi-touch attribution modeling for larger, more complex accounts

**Monthly deliverables note:** this service's reports are consumed by nearly every other active service — coordinate timing so the analytics report can inform, not duplicate, other services' own monthly reports.

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Every confirmed conversion goal has working tracking | Leading | Directly attributable |
| Tracking-health checks completed on schedule | Leading | Directly attributable |
| Reports delivered on a consistent schedule | Leading | Directly attributable |
| Dashboard usage/engagement by the client | Leading | A useful signal of whether the dashboard is genuinely useful, not just built |
| Accuracy of attribution disclosed in reporting | N/A — a quality standard, not a numeric KPI | Every report should be checked against Section A's framework, not just produced on schedule |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Analytics (GA4), Google Search Console, Google Tag Manager, Google Looker Studio, Meta Events Manager, TikTok Events Manager | Covers the entire core measurement stack at no direct tool cost |
| Low-cost | Call-tracking services, entry-tier CRM reporting features | Useful once phone-based conversions are a meaningful share of activity |
| Professional | Dedicated multi-touch attribution or business-intelligence platforms | Justified for larger, multi-channel accounts with enough volume to benefit from more sophisticated modeling |
| Low-bandwidth / mobile-first consideration | A dashboard that loads quickly and is genuinely readable on a phone, since many client decision-makers will check it from mobile | Matches how the report will actually be consumed |

## H. Risks and Common Failure Modes

- **Technical risk:** a silently broken tag or integration producing an inaccurate, unnoticed data gap.
- **Platform risk:** privacy-policy and tracking-technology changes (e.g. browser cookie restrictions, platform privacy features) progressively reducing measurement precision over time — communicate this evolving limitation honestly rather than pretending precision hasn't changed.
- **Client-related risk:** a client wanting a single, simple number ("just tell me if it's working") when the honest answer requires nuance — resist oversimplifying to the point of being misleading.
- **Data and access risk:** tracking accounts set up under the agency's own credentials instead of the client's — see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md).
- **Reputation risk:** presenting an inflated or overstated result that later doesn't hold up damages trust far more than an honest, more modest report would have.
- **Security risk:** analytics and CRM platforms contain customer and business data requiring the same access discipline as other sensitive systems.
- **Legal or compliance risk:** tracking technologies (cookies, pixels) are subject to consent and data-protection considerations — flag for verification against current requirements in [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md).
- **Measurement and attribution risk:** this entire service exists to manage this risk — see Section A. The single most damaging failure mode for the whole agency is a report that misleads a client into a bad decision.

## I. Standard Operating Procedure

- [ ] Complete channel inventory built and confirmed conversion goals documented
- [ ] Existing tracking audited and its actual status (not assumed status) documented
- [ ] Measurement plan and consistent UTM taxonomy designed
- [ ] Core tracking stack installed and verified firing correctly, in the client's own accounts
- [ ] Reporting dashboard built, prioritizing the client's actual priority metrics
- [ ] Tracking setup and taxonomy documented for internal and client reference
- [ ] Every conversion action tested end to end, from real action to dashboard display
- [ ] Baseline recorded and client explicitly briefed on the measurement-limitations framework
- [ ] Tracking health monitored weekly; a sudden metric drop always checked as a possible tracking failure first
- [ ] Tracking gaps fixed promptly; dashboard refined based on client usefulness feedback
- [ ] Monthly reports and quarterly strategy reviews delivered on schedule, every claim checked against the can/cannot-measure framework
- [ ] Platform changes tracked and UTM taxonomy discipline enforced across every team quarterly
