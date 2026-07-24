# Service: Review and Reputation Management

## A. Service Definition

**What it is.** The end-to-end system for generating genuine customer reviews across platforms, monitoring incoming reviews, responding to them, and handling negative feedback and real complaints through a defined internal service-recovery process.

**A non-negotiable ethical boundary, stated upfront:** this service never buys reviews, never writes or facilitates fake reviews, and never uses **review gating** — the practice of privately asking customers if they're satisfied first and only inviting the satisfied ones to leave a public review while diverting dissatisfied customers elsewhere. Review gating is explicitly prohibited by Google's and Meta's platform policies, and it is dishonest regardless of policy. Every eligible customer is invited to review through the same consistent process, regardless of how the interaction seemed to go.

**What business problem it solves.** Most businesses have too few reviews, no systematic way of asking, no process for responding, and no way to catch and fix a real service problem before it becomes public, permanent, negative feedback.

**Why a customer would pay for it.** A disciplined, ethical review system compounds over time — more reviews, a stronger average rating, and higher trust from prospective customers comparing options. It also functions as an early-warning system: a well-run service-recovery process turns a real complaint into a retained customer instead of a lost one and a bad review.

**Business types that benefit most.** Virtually every consumer-facing business, especially the "Very High" review-importance segments in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md) — restaurants, hotels, clinics, salons, auto repair, event venues, and most other experience-based services.

**What this does not include.** The technical execution of responding to reviews *specifically on the Google Business Profile platform* — that mechanical step is performed under [10_GOOGLE_BUSINESS_PROFILE.md](10_GOOGLE_BUSINESS_PROFILE.md) Task 10.2, using the templates, tone, and escalation rules this service defines. This service is the policy, process, and multi-platform system; 10 executes it on one specific platform.

**How it connects to other services.** Defines the response templates and escalation rules used by [10_GOOGLE_BUSINESS_PROFILE.md](10_GOOGLE_BUSINESS_PROFILE.md). Uses [22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md) channels for digital review requests. Feeds testimonial content (with permission) into [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md) and review volume/rating KPIs into [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md). One of the three local-visibility pillars alongside 09 and 10.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Sending review requests, monitoring incoming reviews, responding to reviews, escalating and resolving real complaints |
| Output | Review-request materials (QR codes, links, scripts), a review-response log, a service-recovery log |
| Outcome | Higher review volume and average rating; real service problems surfaced and resolved before they compound; stronger trust signal for prospective customers |
| Financial impact | Reviews directly influence purchase decisions in high review-importance segments; a working service-recovery process improves retention by converting an unhappy customer into a resolved, retained one |

## C. Inputs Required From the Client

- Access to the business's review platforms (Google Business Profile via 10, Facebook Page, and any relevant industry-specific review platform)
- A list of realistic customer touchpoints where a review request could naturally occur (after a meal, after an appointment, after delivery, on a receipt)
- Staff willing to be briefly trained on how to ask for a review in person
- Brand assets for printed materials (table cards, signage, receipt footers)
- Any existing negative reviews needing a response as part of onboarding
- The name of whoever internally owns real complaint resolution (owner, manager) for the service-recovery escalation path

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Audit current review presence and confirm the ethical policy**
| Field | Detail |
|---|---|
| Purpose | Establishes a starting baseline and ensures the client explicitly understands and agrees to the no-buying/no-fake/no-gating policy before any request activity begins |
| Inputs | Client's known review platforms |
| Procedure | 1) Record current review count, average rating, and platform coverage across Google, Facebook, and any relevant industry platform. 2) Explicitly walk the client through the ethical policy in Section A and get their agreement in writing. |
| Tools | Manual platform review, shared document |
| Deliverable | Baseline review audit and signed ethical-policy agreement |
| Owner | Reputation specialist |
| Dependency | Onboarding complete |
| Frequency | One-time per client |
| KPI | Baseline recorded and policy agreement signed before any request activity |
| Quality check | Baseline figures verified directly on each platform |
| Common mistake | Skipping the explicit policy conversation and assuming the client already understands why review gating is prohibited, only to have them ask for it later |
| Estimated complexity | Low |

### 2. Research

**Task: Identify optimal request timing and channel per touchpoint**
| Field | Detail |
|---|---|
| Purpose | Review requests work best when timed to a genuine, fresh moment of positive engagement — a generic, poorly timed request is far less effective |
| Inputs | Client's real customer journey (from [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md) if available) |
| Procedure | 1) Map the realistic touchpoints where a request could occur (e.g. immediately after a meal is finished, right after an appointment, on delivery completion). 2) For each, identify the most natural channel (in-person ask, receipt QR code, WhatsApp follow-up, SMS, email). |
| Tools | Shared document, client interview |
| Deliverable | Touchpoint and channel map |
| Owner | Reputation specialist |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited if the customer journey changes |
| KPI | At least one realistic touchpoint identified per major customer interaction type |
| Quality check | Each touchpoint checked for genuine naturalness — would a real customer find this timing reasonable, not intrusive |
| Common mistake | Requesting a review at a moment disconnected from the actual service experience (e.g. days later, with no reminder of what the experience even was) |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Define the review-request policy — who is asked, and how**
| Field | Detail |
|---|---|
| Purpose | This is where the ethical boundary from Section A becomes an operational rule, not just a stated principle |
| Inputs | Touchpoint map |
| Procedure | 1) Define the rule explicitly: every customer at the identified touchpoint is invited to leave a review through the same consistent process — never filtered by a private satisfaction check first. 2) Define response-time targets for review replies. 3) Define what qualifies as a complaint requiring service-recovery escalation versus a routine review response. |
| Tools | Shared document |
| Deliverable | Documented request policy, response-time targets, and escalation criteria |
| Owner | Reputation specialist, account lead |
| Dependency | Task 2.1 |
| Frequency | One-time, revisited if the touchpoint map changes |
| KPI | Policy explicitly states the no-gating rule in writing |
| Quality check | Policy reviewed against current platform guidelines for review solicitation |
| Common mistake | Designing a "ask happy customers to review, ask unhappy customers to contact us directly instead" flow — this is textbook review gating and is prohibited |
| Estimated complexity | Low |

### 4. Setup

**Task: Create direct review links and QR codes**
| Field | Detail |
|---|---|
| Purpose | Removes friction — a customer is far more likely to leave a review if given a single tap/scan than if asked to search for the business themselves |
| Inputs | Verified Google Business Profile (10), Facebook Page |
| Procedure | 1) Generate the direct review link for Google (via the GBP dashboard) and any other relevant platform. 2) Generate a QR code encoding that link. 3) Test both before distribution. |
| Tools | Google Business Profile short-link generator, a QR code generator |
| Deliverable | Working direct review link(s) and QR code(s) |
| Owner | Reputation specialist |
| Dependency | 10, Task 4.1 (verified profile) |
| Frequency | One-time, regenerated if the platform URL changes |
| KPI | Link and QR code tested and confirmed working before distribution |
| Quality check | QR code scanned on a real phone to confirm it lands on the correct review page |
| Common mistake | Distributing a QR code that was never actually tested and turns out to link to the wrong page or an expired URL |
| Estimated complexity | Low |

**Task: Set up review monitoring across platforms**
| Field | Detail |
|---|---|
| Purpose | Ensures new reviews are noticed promptly enough to respond within the agreed target |
| Inputs | Access to all relevant review platforms |
| Procedure | 1) Enable notification alerts on each platform. 2) Where useful, set up a consolidated monitoring view or tool. |
| Tools | Native platform notifications, a review-monitoring tool for multi-platform consolidation if in scope |
| Deliverable | Active review monitoring |
| Owner | Reputation specialist |
| Dependency | Task 1.1 |
| Frequency | One-time setup |
| KPI | Test review/notification confirmed to arrive correctly |
| Quality check | Alerts tested, not assumed to work |
| Common mistake | Relying on manually checking each platform periodically instead of setting up actual alerts, causing slow response times |
| Estimated complexity | Low |

### 5. Production

**Task: Design printed and digital request materials**
| Field | Detail |
|---|---|
| Purpose | Makes the review link/QR code physically and digitally present at the exact moment a customer might act on it |
| Inputs | Brand assets, QR code/link, touchpoint map |
| Procedure | 1) Design in-store signage, table cards, and/or a receipt footer incorporating the QR code and a brief, honest prompt (not a plea or an incentive offer). 2) Draft WhatsApp, SMS, and email request message templates for each relevant touchpoint. |
| Tools | Design tool (see [25_BRANDING_AND_GRAPHIC_DESIGN.md](25_BRANDING_AND_GRAPHIC_DESIGN.md)), messaging templates |
| Deliverable | Printed material designs and digital message templates |
| Owner | Reputation specialist, with design support |
| Dependency | Task 4.1 |
| Frequency | One-time initial set, refreshed periodically |
| KPI | Materials cover every touchpoint identified in Task 2.1 |
| Quality check | Language reviewed to ensure it never offers an incentive (discount, entry into a prize draw) in exchange for a review, which violates platform policy |
| Common mistake | Offering a discount "for leaving a review," which is a policy violation regardless of whether the review itself is genuine |
| Estimated complexity | Medium |

**Task: Write review-response templates**
| Field | Detail |
|---|---|
| Purpose | Prepared, adaptable templates ensure fast, consistent, appropriate responses instead of improvised replies under time pressure |
| Inputs | Business tone/voice guide from [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md) |
| Procedure | 1) Draft a positive-review response template (genuine thanks, specific where possible, no generic copy-paste feel). 2) Draft a neutral-review response template (acknowledge, invite further feedback or an offline conversation). 3) Draft a negative-review response template (acknowledge without being defensive, apologize for the experience, move the resolution offline, avoid arguing publicly). 4) Draft a separate internal procedure for identifying and reporting fake or abusive reviews, distinct from responding to legitimate negative ones. |
| Tools | Shared document |
| Deliverable | Response-template set for positive, neutral, negative, and fake/abusive review scenarios |
| Owner | Reputation specialist |
| Dependency | Task 3.1 |
| Frequency | One-time, refreshed periodically |
| KPI | Templates reviewed and approved by the client before use |
| Quality check | Negative-review template specifically checked to ensure it never argues publicly or discloses private customer details in the response |
| Common mistake | Responding to a negative review by publicly disputing the customer's account of events or revealing private details of their transaction, which damages trust with every other reader |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Train staff on how to ask for a review**
| Field | Detail |
|---|---|
| Purpose | The in-person ask is often the single most effective channel, but only if staff can do it naturally and consistently |
| Inputs | Touchpoint map, request policy |
| Procedure | 1) Brief staff on when and how to ask (a short, natural, non-pressuring script). 2) Explain the no-gating rule clearly — every customer is asked, not just ones staff perceive as happy. 3) Role-play the ask if useful. |
| Tools | Short training session, printed quick-reference card |
| Deliverable | Trained staff, consistently able to make the ask |
| Owner | Reputation specialist, client's manager |
| Dependency | Task 3.1 |
| Frequency | One-time initial training, refreshed periodically (Task 12.2) |
| KPI | All customer-facing staff briefed before launch |
| Quality check | A sample interaction observed or reviewed to confirm the ask sounds natural, not scripted or pressuring |
| Common mistake | Training staff to "size up" a customer's mood before deciding whether to ask, which reintroduces selection bias equivalent to gating |
| Estimated complexity | Medium |

**Task: Deploy printed materials and digital request messages**
| Field | Detail |
|---|---|
| Purpose | Puts the system into actual daily operation |
| Inputs | Printed materials, digital templates |
| Procedure | 1) Place signage/table cards/receipt QR codes at the physical touchpoints. 2) Configure digital request messages to send at the appropriate post-interaction timing (see Task 2.1). |
| Tools | Physical placement, messaging platform (see [22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md)) |
| Deliverable | Live, deployed request system |
| Owner | Reputation specialist |
| Dependency | Tasks 5.1–6.1 |
| Frequency | One-time deployment, refreshed as needed |
| KPI | All identified touchpoints have an active request mechanism |
| Quality check | Physical placement checked in person, not just confirmed by description |
| Common mistake | Printing materials but never actually confirming they were placed and are still present and visible on a follow-up visit |
| Estimated complexity | Low |

### 7. Testing

**Task: Test the full request-to-response flow**
| Field | Detail |
|---|---|
| Purpose | Confirms every part of the system actually works together before relying on it |
| Inputs | Deployed system |
| Procedure | 1) Have a real person (e.g. a team member, with disclosure) test the QR code/link end to end. 2) Confirm a test message sent via each digital channel arrives correctly. 3) Confirm monitoring correctly flags a test/incoming review. |
| Tools | Real device testing |
| Deliverable | Confirmed working end-to-end system |
| Owner | Reputation specialist |
| Dependency | Task 6.1 |
| Frequency | One-time at launch |
| KPI | Every channel tested and confirmed functional |
| Quality check | Tested on the actual devices/platforms customers will use, not just in the admin dashboard |
| Common mistake | Assuming the system works because each individual piece was set up correctly, without testing the full flow together |
| Estimated complexity | Low |

### 8. Launch

**Task: Activate the review system**
| Field | Detail |
|---|---|
| Purpose | Formal activation marks when ongoing monitoring, response, and reporting begin |
| Inputs | Tested system |
| Procedure | 1) Confirm all touchpoints are live. 2) Confirm the client understands the ongoing cadence and their own role (e.g. staff continuing to ask consistently). |
| Tools | Confirmation document |
| Deliverable | Activated review system, confirmed with the client |
| Owner | Account lead |
| Dependency | Task 7.1 |
| Frequency | One-time per client |
| KPI | Activation confirmed within the agreed launch timeline |
| Quality check | Client explicitly confirms understanding of the no-gating policy's operational implications |
| Common mistake | Launching without the client's staff genuinely on board with the consistent-ask policy, causing silent non-compliance later |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor incoming reviews and response-time adherence**
| Field | Detail |
|---|---|
| Purpose | Confirms the system is running as designed and catches any new review promptly |
| Inputs | Active monitoring (Task 4.2) |
| Procedure | 1) Check for new reviews at least as often as the agreed response-time target requires. 2) Track whether responses are being posted within that target. |
| Tools | Platform notifications, tracking sheet |
| Deliverable | Ongoing review and response-time log |
| Owner | Reputation specialist |
| Dependency | Task 4.2 |
| Frequency | At least weekly, more often per the agreed response-time target |
| KPI | 100% of reviews checked within the target window |
| Quality check | Log reviewed for any missed response before it becomes overdue |
| Common mistake | Checking reviews only when producing the monthly report, allowing responses to sit far longer than the agreed target |
| Estimated complexity | Low |

**Task: Identify reviews requiring service-recovery escalation**
| Field | Detail |
|---|---|
| Purpose | A negative review is sometimes a symptom of a real, fixable problem — catching this internally prevents recurrence and can turn the reviewer into a retained customer |
| Inputs | Incoming reviews, escalation criteria from Task 3.1 |
| Procedure | 1) Assess each negative review against the escalation criteria. 2) For anything meeting the bar, notify the internal owner named in onboarding immediately, separate from the routine public response. |
| Tools | Escalation criteria checklist |
| Deliverable | Escalation notifications sent |
| Owner | Reputation specialist |
| Dependency | Task 3.1 |
| Frequency | As reviews arrive |
| KPI | 100% of qualifying reviews escalated within 24 hours |
| Quality check | Escalation notification includes enough detail for the internal owner to act, not just "you got a bad review" |
| Common mistake | Treating a negative review only as a public-relations problem to manage with a good response, missing the underlying operational issue it points to |
| Estimated complexity | Medium |

### 10. Optimization

**Task: Refine timing, channel mix, and templates based on results**
| Field | Detail |
|---|---|
| Purpose | Request effectiveness varies by touchpoint and channel — real response-rate data should guide what to keep doing and what to change |
| Inputs | Review volume trend, request-channel performance if trackable |
| Procedure | 1) Review which touchpoints/channels are producing the most reviews. 2) Adjust timing or wording where a channel is underperforming. 3) Update response templates based on what has resonated or fallen flat. |
| Tools | Tracking sheet, review-volume data |
| Deliverable | Refined request approach and templates |
| Owner | Reputation specialist |
| Dependency | Task 9.1 |
| Frequency | Quarterly |
| KPI | Measurable improvement in review-request response rate over time |
| Quality check | Refinements checked against the ethical policy in Section A before implementation — never "optimize" toward gating |
| Common mistake | Interpreting a low response rate as a signal to start filtering who gets asked, rather than improving the timing or wording of the ask itself |
| Estimated complexity | Medium |

**Task: Follow up on resolved service-recovery cases**
| Field | Detail |
|---|---|
| Purpose | Confirms the internal fix actually happened and, where appropriate, invites the customer to reconsider or update their experience |
| Inputs | Escalation log |
| Procedure | 1) Confirm with the internal owner that the underlying issue was addressed. 2) Where appropriate and only if genuine, the business may reach out directly to the customer to make things right — never to pressure a review change. |
| Tools | Escalation log |
| Deliverable | Closed-out, confirmed service-recovery cases |
| Owner | Reputation specialist, client's internal owner |
| Dependency | Task 9.2 |
| Frequency | As cases are escalated |
| KPI | 100% of escalated cases have a confirmed resolution or explicit decision logged |
| Quality check | Follow-up confirmed genuine, not a pretext to ask for a review edit or removal |
| Common mistake | Contacting a customer after a fix specifically to ask them to change or remove their negative review, which is a form of manipulation the client must be firmly advised against |
| Estimated complexity | Low |

### 11. Reporting

**Task: Deliver the monthly review report**
| Field | Detail |
|---|---|
| Purpose | Makes review-system performance and its connection to real business outcomes visible to the client |
| Inputs | Monitoring log, escalation log |
| Procedure | 1) Summarize review volume, average rating trend, and response rate/time for the month. 2) Summarize common themes appearing in reviews (useful operational feedback, not just a PR metric). 3) Summarize any service-recovery cases and their resolution status. |
| Tools | Report template |
| Deliverable | Monthly review report |
| Owner | Reputation specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Themes in reviews cross-checked for accuracy before being presented as operational feedback |
| Common mistake | Reporting only the star-rating number without surfacing the qualitative themes that actually help the business improve |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Keep request materials and links current**
| Field | Detail |
|---|---|
| Purpose | A broken QR code or an outdated printed card silently stops producing reviews without anyone noticing until a periodic check |
| Inputs | Deployed materials |
| Procedure | 1) Periodically re-test links and QR codes. 2) Replace worn or outdated physical materials. 3) Regenerate links if the underlying platform URL structure changes. |
| Tools | Manual testing |
| Deliverable | Consistently working, current request materials |
| Owner | Reputation specialist |
| Dependency | Ongoing |
| Frequency | Quarterly, or immediately if a platform change is known |
| KPI | Zero broken links/QR codes found during the quarterly check |
| Quality check | Tested on a real device, matching the original Task 7.1 standard |
| Common mistake | Assuming a QR code printed months ago still works without ever re-testing it |
| Estimated complexity | Low |

**Task: Refresh staff training periodically**
| Field | Detail |
|---|---|
| Purpose | Staff turnover and habit drift both erode a consistent request practice over time |
| Inputs | Original training materials |
| Procedure | 1) Re-brief staff periodically, and immediately for any new hire in a customer-facing role. 2) Reinforce the no-gating policy each time. |
| Tools | Quick-reference training card |
| Deliverable | Consistently trained current staff |
| Owner | Reputation specialist, client's manager |
| Dependency | Task 6.1 |
| Frequency | Quarterly refresh, plus for every new hire |
| KPI | No customer-facing staff member goes untrained for more than one quarter |
| Quality check | Spot-checked during site visits or manager conversations |
| Common mistake | Training staff once at launch and never refreshing it, so the practice quietly fades as original staff leave |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Baseline review audit
- Touchpoint and channel map
- Documented request policy, response-time targets, and escalation criteria
- Direct review links and QR codes
- Printed material designs and digital message templates
- Response-template set (positive, neutral, negative, fake/abusive)
- Trained staff

**Monthly deliverables**
- Reviews monitored and responded to within the agreed target
- Service-recovery escalations actioned
- Monthly review report

**Quarterly deliverables**
- Request-approach and template refinement based on results
- Materials/links health check
- Staff training refresh

**Optional add-ons**
- Multi-platform review-monitoring tool subscription for larger or multi-location clients
- Expanded printed material sets for multi-location businesses

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Review requests made per period (via trackable channels) | Leading | Directly attributable |
| Response-time adherence | Leading | Directly attributable |
| Review volume growth | Lagging | Directly attributable to the request system, though also affected by overall business volume |
| Average rating trend | Lagging | Reflects real service quality as much as the review system itself — this service surfaces and responds to feedback, it does not manufacture a rating |
| Service-recovery case resolution rate | Lagging | Directly attributable to the internal escalation process working as designed |
| Review-driven local ranking contribution | Lagging | Shared outcome across the three local-visibility pillars (09, 10, 11) — do not attribute solely to this service |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Business Profile's native review link generator, a free QR code generator, native platform notifications | Sufficient for most single-location SME clients |
| Low-cost | Basic review-monitoring/alert tools | Useful once monitoring multiple platforms manually becomes time-consuming |
| Professional | Multi-platform reputation-management software | Justified for multi-location businesses or those with high review volume across many platforms |
| Low-bandwidth / mobile-first consideration | QR codes and short links that work reliably on a basic smartphone camera and a slower mobile connection | Reflects how most customers will actually scan and follow through |

## H. Risks and Common Failure Modes

- **Technical risk:** a broken or outdated QR code/link silently stops producing reviews.
- **Platform risk:** Google's and Meta's review-solicitation and content policies change over time — verify current rules before deploying any new request tactic.
- **Client-related risk:** a client or staff member reverting to gating behavior under pressure to improve the rating quickly — this must be firmly and consistently declined, with the reasoning explained (policy violation risk, and it undermines the very trust reviews are meant to build).
- **Data and access risk:** losing access to review-monitoring or response tools if platform account access isn't properly documented (see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)).
- **Reputation risk:** an unanswered or poorly handled negative review is more damaging than the review itself — every reader sees how the business responded, not just what happened.
- **Security risk:** not typically applicable directly to this service.
- **Legal or compliance risk:** never offer an incentive for a review, never write or facilitate a fake review, and never dispute a review by disclosing private customer information — all can violate platform policy and, in some cases, broader consumer-protection principles.
- **Measurement and attribution risk:** an improving average rating reflects real service quality as much as this service's process — avoid claiming sole credit for a rating change that is substantially driven by the business's own operational improvements (or decline).

## I. Standard Operating Procedure

- [ ] Baseline review audit completed; ethical no-buying/no-fake/no-gating policy explicitly agreed with the client in writing
- [ ] Realistic touchpoint and channel map built
- [ ] Request policy, response-time targets, and escalation criteria documented — explicitly stating that every eligible customer is asked, without pre-filtering by sentiment
- [ ] Direct review links and QR codes created and tested
- [ ] Review monitoring active and tested across all relevant platforms
- [ ] Printed materials and digital templates designed, with no incentive-for-review language
- [ ] Response templates drafted for positive, neutral, negative, and fake/abusive scenarios and approved by the client
- [ ] Staff trained on the consistent, non-filtering ask
- [ ] Materials deployed at all identified touchpoints and verified in person
- [ ] Full request-to-response flow tested end to end before launch
- [ ] System activated with client confirmation of the ongoing policy
- [ ] Reviews monitored and responded to within the agreed target every period
- [ ] Qualifying negative reviews escalated internally within 24 hours, separate from the public response
- [ ] Service-recovery cases followed up and closed out, never used as a pretext to request a review change
- [ ] Monthly report delivered, including qualitative themes, not just the rating number
- [ ] Materials/links health-checked and staff training refreshed quarterly
