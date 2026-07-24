# Service: Website Development

## A. Service Definition

**What it is.** Builds the actual, live, working website from the approved [02_WEBSITE_DESIGN.md](02_WEBSITE_DESIGN.md) files: the CMS or codebase, responsive front-end, all required integrations (forms, WhatsApp, maps, booking, payment where relevant), tracking installation, security, and initial performance optimization — through testing and launch.

**What business problem it solves.** A beautiful design is not a website. Development is where the site becomes real, fast, secure, trackable, and usable on the actual devices and connections target customers use. Poor development work (slow pages, broken forms, no tracking, no security) silently destroys the value of everything done in strategy and design.

**Why a customer would pay for it.** A professionally built site works correctly the first time, loads acceptably on a mid-range mobile phone over a mobile connection, is secure, and gives the business owner real evidence (via tracking) of what it is producing.

**Business types that benefit most.** Any business proceeding past strategy and design; complexity and cost scale with the segment's real needs (see [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md)) — a laundromat may need a single-page site while a hotel needs booking integration and a real-estate agency needs a searchable listings system.

**What this service does not include.** Strategy and research (01), visual design (02), copywriting (04 — development implements approved copy, it does not write it), ongoing domain renewal/hosting/backup/update management after launch (05 — development performs the *initial* domain/hosting/SSL setup required to launch; ongoing maintenance is a distinct, separately delivered service), original photography (16).

**How it connects to other services.** Consumes the design files from 02 and the copy from 04. Its initial setup work (domain, hosting, SSL, CMS) hands off into the ongoing responsibilities of [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md). Its tracking installation work is the technical foundation for [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md). Its technical build choices directly enable or constrain [06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Coding/configuring the CMS, building integrations, testing, deploying |
| Output | A live, working, secure, trackable website matching the approved design |
| Outcome | A site visitors can actually use successfully on their own device/connection to take the intended action |
| Financial impact | Fewer lost inquiries from broken forms/links/slow pages; a technical foundation that doesn't cap the return on later SEO or advertising spend |

## C. Inputs Required From the Client

- Approved design files and handoff package from 02
- Approved final copy from 04 (or an agreed placeholder/phased-content plan)
- Domain name decision (new registration vs. existing domain access)
- Access to any existing domain registrar and hosting account, if applicable (see [../operations/07_ACCESS_AND_ASSET_COLLECTION.md](../operations/07_ACCESS_AND_ASSET_COLLECTION.md))
- Business contact details for forms/integrations (phone, WhatsApp number, email, address, map location)
- Decision on payment integration, if e-commerce or online payment is in scope, and confirmation of available local payment options
- Google account for Analytics/Search Console setup, and Meta/TikTok business accounts if pixels are required
- A named technical/content approver for launch sign-off

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm handoff package and finalize platform selection**
| Field | Detail |
|---|---|
| Purpose | Development cannot start reliably on an incomplete handoff or an unconfirmed platform choice |
| Inputs | Design handoff package (02, Task 8.1), platform recommendation (01, Task 4.1) |
| Procedure | 1) Confirm all design files, assets, and the style guide are present. 2) Confirm or revise the platform recommendation against final scope (e.g. e-commerce needs). 3) Document the final technical stack decision. |
| Tools | Checklist, shared drive |
| Deliverable | Confirmed technical stack decision |
| Owner | Development lead |
| Dependency | Design sign-off (02, Task 8.1) |
| Frequency | One-time per project |
| KPI | Stack decision documented before setup begins |
| Quality check | Decision checked against budget and required integrations from strategy |
| Common mistake | Starting build on a platform that can't actually support a feature promised in strategy (e.g. local payment gateway not supported) |
| Estimated complexity | Low |

### 2. Research

**Task: Confirm integration and hosting technical requirements**
| Field | Detail |
|---|---|
| Purpose | Some integrations (payment gateways, booking systems, SMS/WhatsApp APIs) have specific, sometimes-changing technical and eligibility requirements in Ethiopia that must be confirmed before committing to a build approach |
| Inputs | Required integrations list from strategy/design |
| Procedure | 1) For each required integration, confirm current availability, cost, and setup requirements. 2) Confirm hosting requirements (server location/latency, storage, bandwidth) needed to run the chosen platform acceptably for the target audience. 3) Document any integration that is not currently feasible and propose an alternative (e.g. a WhatsApp click-to-chat link instead of a full API integration for a small-budget client). |
| Tools | Vendor documentation, direct inquiries to payment/API providers |
| Deliverable | Confirmed integration and hosting requirements list |
| Owner | Development lead |
| Dependency | Task 1.1 |
| Frequency | One-time per project (re-verify for each new project — availability changes) |
| KPI | Every planned integration confirmed feasible before build starts |
| Quality check | No integration promised to the client without being technically confirmed first |
| Common mistake | Promising a payment or booking integration in the proposal stage without confirming it is currently available and affordable |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Define the technical build and tracking plan**
| Field | Detail |
|---|---|
| Purpose | Gives the build a concrete task list and ensures tracking is planned in from the start rather than bolted on afterward |
| Inputs | Confirmed stack, confirmed integrations, conversion goals from 01 |
| Procedure | 1) List every page template, integration, and tracked conversion event to be built. 2) Define what each tracked event should be (e.g. "WhatsApp button click," "form submit," "call link tap"). 3) Sequence the build order (foundation pages first, integrations, then tracking, then optimization). |
| Tools | Project-management tool |
| Deliverable | Technical build plan and tracking-event list |
| Owner | Development lead |
| Dependency | Task 2.1 |
| Frequency | One-time per project |
| KPI | Every conversion goal from strategy has a corresponding named tracked event |
| Quality check | Plan reviewed against the strategy document's conversion goals for completeness |
| Common mistake | Leaving tracking as an afterthought added right before launch instead of designed in from the start |
| Estimated complexity | Medium |

### 4. Setup

**Task: Register/configure domain, hosting, SSL, and CMS**
| Field | Detail |
|---|---|
| Purpose | Establishes the technical foundation the site will be built on and eventually launched from |
| Inputs | Domain decision, hosting requirements |
| Procedure | 1) Register the domain in the client's own name/account wherever possible (see ownership rules in [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)) or confirm access to an existing domain. 2) Set up hosting. 3) Install and configure the SSL certificate so the site loads securely (https). 4) Install and configure the CMS or framework. 5) Set up a staging environment separate from the eventual live site. |
| Tools | Domain registrar, hosting provider control panel, SSL provisioning (often free via Let's Encrypt or included with hosting) |
| Deliverable | Working domain, hosting, SSL, CMS, and staging environment |
| Owner | Developer |
| Dependency | Task 3.1 |
| Frequency | One-time per project |
| KPI | Staging site accessible over https with no certificate warnings |
| Quality check | Domain and hosting account ownership confirmed to be in the client's name/control per agency policy |
| Common mistake | Registering the domain under the agency's own account "for convenience," creating an ownership dispute later |
| Estimated complexity | Medium |

### 5. Production

**Task: Build responsive page templates and implement content**
| Field | Detail |
|---|---|
| Purpose | Converts the approved design into a real, working, responsive site with the approved content in place |
| Inputs | Design files, approved copy and images |
| Procedure | 1) Build each page template to match the design at all required breakpoints (mobile, tablet, desktop). 2) Enter or import the approved copy and optimized images. 3) Build internal linking between pages consistent with the navigation structure. |
| Tools | CMS/framework, image-compression tool |
| Deliverable | Fully built, content-populated staging site |
| Owner | Developer |
| Dependency | Task 4.1, content available |
| Frequency | One-time per project |
| KPI | All page templates built and matching design within acceptable tolerance |
| Quality check | Compared side-by-side against design files (see also 02, Task 9.1 design QA) |
| Common mistake | Uploading uncompressed, oversized images that slow the site significantly |
| Estimated complexity | High |

**Task: Build required integrations**
| Field | Detail |
|---|---|
| Purpose | Delivers the actual functionality the strategy promised — the reason visitors convert into inquiries |
| Inputs | Confirmed integration list from Task 2.1 |
| Procedure | 1) Implement lead-capture forms with spam protection. 2) Implement WhatsApp click-to-chat linking to the correct business number. 3) Implement a map embed pointing to the verified correct location. 4) Implement booking functionality if in scope. 5) Implement payment integration if in scope, using a currently available local-compatible option. |
| Tools | Form plugin/builder, WhatsApp click-to-chat link generator, Google Maps embed, booking/payment plugin as applicable |
| Deliverable | Working integrations on the staging site |
| Owner | Developer |
| Dependency | Task 5.1 |
| Frequency | One-time per project |
| KPI | Every planned integration functions correctly on staging |
| Quality check | Each integration tested with a real test submission/click, not just visually reviewed |
| Common mistake | Linking a WhatsApp button to the developer's or agency's test number instead of the client's real business number |
| Estimated complexity | High |

**Task: Install analytics, Search Console, pixels, and schema markup**
| Field | Detail |
|---|---|
| Purpose | Without this, the business has no way to measure what the site produces, and search engines have a harder time understanding the content |
| Inputs | Google account, Meta/TikTok business accounts (if applicable), tracking-event list from Task 3.1 |
| Procedure | 1) Install Google Analytics (in the client's own account). 2) Install and verify Google Search Console. 3) Install the Meta Pixel and/or TikTok Pixel if paid advertising is in scope. 4) Configure the tracked conversion events defined in Task 3.1. 5) Add structured data (schema markup) for the business type, address, and, where applicable, products/services. |
| Tools | Google Analytics, Google Search Console, Google Tag Manager (recommended, to manage tags without repeated code edits), Meta Events Manager, Schema.org markup / structured-data testing tools |
| Deliverable | Verified analytics, Search Console, pixel installation, and schema markup |
| Owner | Developer, with analytics specialist review |
| Dependency | Task 5.1 |
| Frequency | One-time per project |
| KPI | Every tracked event fires correctly when tested |
| Quality check | Verified using each platform's own live testing tool (e.g. Google Tag Assistant, Meta Pixel Helper) before launch |
| Common mistake | Installing tracking codes but never testing that events actually fire, discovering the gap only during monthly reporting |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Configure speed, caching, security, and backups**
| Field | Detail |
|---|---|
| Purpose | A slow, insecure, or unbacked-up site creates ongoing risk and directly hurts both user experience and SEO |
| Inputs | Built staging site |
| Procedure | 1) Compress and properly size all images. 2) Configure browser/server caching. 3) Enable a web application firewall or equivalent security hardening available on the hosting platform. 4) Configure automated backups. 5) Configure custom 404 and error pages. 6) Set up any required redirects (e.g. for a redesign replacing an old site's URLs). |
| Tools | Image-compression tools, hosting-level caching, hosting/plugin-level firewall, backup plugin/service |
| Deliverable | Optimized, secured, backed-up staging site with error pages and redirects configured |
| Owner | Developer |
| Dependency | Task 5.1 |
| Frequency | One-time per project (baseline; ongoing management moves to 05) |
| KPI | Page-speed test results meet an agreed acceptable threshold; backups run successfully on first test |
| Quality check | Redirects tested individually, not assumed to work from configuration alone |
| Common mistake | Launching a redesign without redirecting old URLs, losing existing search rankings and breaking bookmarked links |
| Estimated complexity | Medium |

### 7. Testing

**Task: Full pre-launch testing pass**
| Field | Detail |
|---|---|
| Purpose | Catches errors while they are still cheap and low-risk to fix, before real customers encounter them |
| Inputs | Fully built, optimized staging site |
| Procedure | 1) Test on multiple browsers. 2) Test on multiple real mobile devices, not just emulators. 3) Test every form with a real submission. 4) Test the WhatsApp and telephone links tap-to-action on an actual phone. 5) Run a page-speed test. 6) Check for broken links sitewide. 7) Proofread all live copy for spelling and grammar. 8) Verify every tracking event fires correctly. 9) Take a full backup of the staging site immediately before launch. |
| Tools | Multiple real devices/browsers, Google PageSpeed Insights, a broken-link checker, tag-verification tools |
| Deliverable | Completed pre-launch testing checklist |
| Owner | Developer, with QA support from account lead |
| Dependency | Task 6.1 |
| Frequency | One-time per project |
| KPI | Zero open critical issues at launch sign-off |
| Quality check | Checklist signed off by someone other than the developer who built the site |
| Common mistake | Testing only on the developer's own device/browser/connection, missing issues that appear on the client's actual customers' typical devices |
| Estimated complexity | Medium |

### 8. Launch

**Task: Go live and confirm post-launch health**
| Field | Detail |
|---|---|
| Purpose | The moment of highest risk in the whole build — a rushed or unconfirmed launch can undo all prior QA work |
| Inputs | Signed-off testing checklist, client final approval |
| Procedure | 1) Obtain final written client approval to go live. 2) Point the domain to the live hosting environment. 3) Confirm the site loads correctly over https at the live domain. 4) Submit the XML sitemap to Google Search Console. 5) Re-verify tracking fires correctly on the live (not staging) URL. 6) Monitor closely for the first 24–48 hours for any errors. |
| Tools | DNS management, Google Search Console, tag-verification tools |
| Deliverable | Live, verified, indexed-and-submitted website |
| Owner | Developer, account lead |
| Dependency | Task 7.1 |
| Frequency | One-time per project |
| KPI | Site live with zero critical post-launch errors in the first 48 hours |
| Quality check | Tracking re-verified specifically on the live URL, since staging verification does not guarantee live behavior |
| Common mistake | Assuming staging-environment testing automatically applies to the live environment without re-checking |
| Estimated complexity | Medium |

### 9. Monitoring

**Task: Monitor early indexation and technical health**
| Field | Detail |
|---|---|
| Purpose | Confirms the site is being properly crawled and indexed, and catches any issue that only appears once real traffic arrives |
| Inputs | Live site, Search Console, uptime-monitoring tool |
| Procedure | 1) Check Search Console indexation status over the first weeks. 2) Monitor for crawl errors. 3) Monitor uptime (coordinate with [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md) for the ongoing version of this task). 4) Watch analytics for unexpected drop-offs suggesting a broken page or link real users are hitting. |
| Tools | Google Search Console, uptime-monitoring service, Google Analytics |
| Deliverable | Post-launch technical health note |
| Owner | Developer |
| Dependency | Task 8.1 |
| Frequency | Daily for the first 2 weeks post-launch, then handed to the cadence in 05 |
| KPI | Core pages indexed within the expected timeframe; zero unresolved crawl errors |
| Quality check | Indexation status checked against the sitemap submitted at launch |
| Common mistake | Assuming "it's live" means "it's indexed" — these are not the same and indexation should be actively confirmed |
| Estimated complexity | Low |

### 10. Optimization

**Task: Address post-launch performance and Core Web Vitals findings**
| Field | Detail |
|---|---|
| Purpose | Real-world performance data after launch often reveals optimization opportunities that weren't visible in staging testing alone |
| Inputs | Core Web Vitals data (Search Console/PageSpeed Insights), analytics |
| Procedure | 1) Review Core Web Vitals scores once sufficient real-user data exists. 2) Identify and fix the highest-impact performance issues (typically large images, unoptimized third-party scripts, or render-blocking resources). 3) Re-test after each fix. |
| Tools | Google PageSpeed Insights, Search Console Core Web Vitals report |
| Deliverable | Performance-optimization note and applied fixes |
| Owner | Developer |
| Dependency | Task 9.1, sufficient real-user data accumulated |
| Frequency | Quarterly, or immediately if a critical performance regression is found |
| KPI | Core Web Vitals scores meet Google's "Good" thresholds for the majority of tracked page views |
| Quality check | Improvement verified with a second measurement after the fix, not assumed |
| Common mistake | Chasing a perfect lab-test score while ignoring real-user field data, which better reflects actual visitor experience |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver a technical launch report and access handover**
| Field | Detail |
|---|---|
| Purpose | The client should have a clear record of what was built, what tracking exists, and full access to their own assets |
| Inputs | Completed build, all account access details |
| Procedure | 1) Summarize what was built, which integrations are live, and what is tracked. 2) Confirm the client has (or has granted the agency access to) ownership-level access to domain, hosting, and any connected accounts per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md). 3) Deliver login/access documentation securely, not over plain chat messages. |
| Tools | Report document, password manager/secure-sharing tool |
| Deliverable | Technical launch report and secure access handover |
| Owner | Account lead |
| Dependency | Task 8.1 |
| Frequency | One-time per project |
| KPI | Report delivered within 5 business days of launch |
| Quality check | Client confirms receipt and understanding of what they now own and control |
| Common mistake | Sending passwords in plain WhatsApp/email text instead of a secure method |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Transition to ongoing hosting and maintenance service**
| Field | Detail |
|---|---|
| Purpose | Development is a one-time build; the site still needs ongoing updates, security monitoring, and backups indefinitely afterward |
| Inputs | Completed build |
| Procedure | 1) Formally transition the site to the cadence and responsibilities defined in [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md). 2) Confirm the client understands whether ongoing maintenance is included in their package or requires a separate agreement. |
| Tools | Handoff document |
| Deliverable | Confirmed maintenance arrangement |
| Owner | Account lead |
| Dependency | Task 11.1 |
| Frequency | One-time per project |
| KPI | Maintenance responsibility explicitly agreed upon, with no ambiguity about who patches, backs up, and renews what |
| Quality check | Written into the contract or a signed addendum, not assumed |
| Common mistake | Leaving maintenance responsibility unstated, so a site quietly goes unpatched, unbacked-up, or expires without renewal |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Live, responsive, tested website matching the approved design
- Working forms, WhatsApp, map, and (where in scope) booking/payment integrations
- Installed and verified Analytics, Search Console, and relevant advertising pixels
- Schema markup for the business
- SSL-secured domain and hosting, with baseline security, caching, and backups configured
- Technical launch report and secure access handover

**Quarterly deliverables**
- Core Web Vitals / performance review and applied fixes (Task 10.1)

**Optional add-ons**
- Payment gateway integration
- Booking/reservation system integration
- Multi-language site build
- Custom functionality beyond a standard CMS build (e.g. a searchable property/product database)

**Monthly deliverables:** none by default from development itself — ongoing monthly technical work (updates, backups, uptime monitoring) is delivered under [05_DOMAIN_HOSTING_AND_MAINTENANCE.md](05_DOMAIN_HOSTING_AND_MAINTENANCE.md), not this service.

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Pre-launch testing checklist completed with zero open critical issues | Leading | Directly attributable |
| Tracked conversion events firing correctly | Leading | Directly attributable |
| Page-load speed / Core Web Vitals scores | Leading/Lagging | Directly attributable to development quality, though also affected by hosting tier and third-party scripts added later by other services |
| Site uptime | Lagging | Shared responsibility with hosting provider reliability |
| Search Console indexation rate | Lagging | Influenced by technical SEO quality (06) as well as development |
| Post-launch critical error count | Lagging | Directly attributable in the first weeks; later issues may stem from subsequent content or plugin changes outside this service's scope |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Analytics, Google Search Console, Google Tag Manager, Let's Encrypt (free SSL), Google PageSpeed Insights, browser developer tools | Covers the technical core of most SME builds at no direct tool cost |
| Low-cost | Shared/entry-level hosting plans, CMS page-builder plugins, image-compression plugins | Appropriate for most single-location SME sites |
| Professional | Managed/cloud hosting with higher performance and support SLAs, premium CMS themes/plugins with dedicated support | Justified for higher-traffic, multi-location, or e-commerce builds |
| Low-bandwidth / mobile-first delivery | Aggressive image compression, minimal render-blocking scripts, lightweight page-builder choices | Directly affects real-world load time for visitors on slower mobile connections, which is the majority use case |

## H. Risks and Common Failure Modes

- **Technical risk:** unoptimized images and excessive third-party scripts producing slow load times, especially damaging on mobile connections.
- **Platform risk:** committing to an integration or platform feature that turns out to be unavailable, unreliable, or prohibitively expensive to maintain in the Ethiopian context after the build has already started.
- **Client-related risk:** delayed final copy or asset delivery stalling the production phase; unclear client sign-off leading to launch disputes.
- **Data and access risk:** domain/hosting registered under the agency's account rather than the client's, creating an ownership dispute at offboarding (see [../operations/13_OFFBOARDING.md](../operations/13_OFFBOARDING.md) and [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)).
- **Reputation risk:** a broken form, dead WhatsApp link, or wrong phone number silently losing every inquiry until discovered — test every contact method with a real submission, never assume.
- **Security risk:** missing SSL, weak admin passwords, no two-factor authentication, or no backup strategy leaving the site vulnerable to defacement or data loss.
- **Legal or compliance risk:** payment integrations must meet applicable local financial-service requirements; any data collected via forms must be handled per the guidance in [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md).
- **Measurement and attribution risk:** launching without verified tracking means the client's very first weeks of performance data — often used as the baseline for future comparison — are silently lost.

## I. Standard Operating Procedure

- [ ] Design handoff package confirmed complete; final platform decision documented
- [ ] Integration and hosting technical requirements confirmed feasible before build starts
- [ ] Technical build plan and tracking-event list defined
- [ ] Domain, hosting, SSL, CMS, and staging environment set up, with domain/hosting ownership in the client's control
- [ ] Responsive page templates built and populated with approved content
- [ ] Required integrations (forms, WhatsApp, map, booking, payment) built and functionally tested
- [ ] Analytics, Search Console, pixels, and schema markup installed and verified firing correctly
- [ ] Speed, caching, security, backups, error pages, and redirects configured
- [ ] Full pre-launch testing checklist completed with zero open critical issues
- [ ] Client final approval obtained; site launched; tracking re-verified on the live URL
- [ ] Sitemap submitted to Search Console; indexation monitored for the first two weeks
- [ ] Technical launch report delivered and access securely handed over
- [ ] Ongoing maintenance arrangement explicitly confirmed and documented