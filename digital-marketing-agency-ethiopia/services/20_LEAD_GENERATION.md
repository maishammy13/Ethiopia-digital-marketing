# Service: Lead Generation

## A. Service Definition

**What it is.** The end-to-end system that captures inbound inquiries from every channel — website forms, phone calls, WhatsApp, social DMs, Google Business Profile messages — and routes them into a usable, trackable pipeline, ensuring no lead is lost and every lead is properly captured, tagged by source, and handed to the right next step.

**What business problem it solves.** Businesses often generate real traffic and visibility through SEO, advertising, social media, and their Google Business Profile, but leak much of that potential value because forms are clunky, phone calls aren't tracked, WhatsApp messages get missed, or there's no consistent process for what happens the moment an inquiry arrives.

**Why a customer would pay for it.** A well-designed capture-and-routing system directly increases the yield from marketing spend that's already happening elsewhere — the same traffic converts into more actual, actionable leads, and those leads get followed up faster.

**Business types that benefit most.** Any business already investing in traffic-generating services (06–09, 10, 17–19) that needs the capture and routing side built properly to actually realize that investment's value — especially higher lead-value segments such as real estate, clinics, hotels, and B2B, per [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md).

**What this does not include.** The traffic-generation services themselves (06–09, 10, 17–19) — this service captures and routes the traffic those services produce, it doesn't generate it. The technical website form build ([03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) builds the form; this service defines what it should capture and how routing works). Deep CRM system configuration ([23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md) owns the CRM itself; this service defines what happens at the moment of capture and feeds the CRM).

**How it connects to other services.** Consumes traffic from 06–09, 10, and 17–19. Uses the forms and integrations built under 03 and the WhatsApp setup from [22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md). Routes captured leads into 23. Reports through [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md). Informs and is informed by [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md), which improves the conversion rate at each capture point this service designs.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Lead-capture audit, funnel/form design, multi-channel capture setup, lead routing and tagging, qualification-process design |
| Output | Optimized capture points (forms, call tracking, WhatsApp, booking), a lead-routing system, a lead-qualification framework, a source-tagged pipeline |
| Outcome | More of the traffic already being generated converts into a captured, actionable lead; no lead falls through the cracks |
| Financial impact | Increased lead volume from the same underlying traffic/spend; faster follow-up leading to a higher lead-to-sale conversion rate |

## C. Inputs Required From the Client

- Current traffic sources in place or planned (which services are active)
- Current forms and contact methods
- A phone number (or agreement to set one up) usable for call tracking
- WhatsApp Business setup from 12/22
- The CRM system from 23, or agreement to set one up alongside this service
- Staff responsible for following up on leads, and their availability
- Expected response-time standards for the business

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Audit current lead-capture points across every channel**
| Field | Detail |
|---|---|
| Purpose | Establishes exactly what exists today and where the obvious gaps are before designing anything new |
| Inputs | Website, phone, WhatsApp, social accounts, GBP |
| Procedure | 1) Inventory every current way a customer could try to contact or inquire with the business. 2) Test each one as a real customer would (submit a form, call the number, send a WhatsApp message). 3) Note what works, what's broken, and what's missing entirely. |
| Tools | Manual testing across every channel |
| Deliverable | Lead-capture audit report |
| Owner | Lead-generation specialist |
| Dependency | Onboarding complete |
| Frequency | One-time initial audit, repeated quarterly |
| KPI | Every channel tested as a real customer would experience it |
| Quality check | Findings based on actual test interactions, not assumed from looking at the settings alone |
| Common mistake | Assuming a contact form works because it appears correctly configured, without ever actually submitting a real test entry |
| Estimated complexity | Medium |

### 2. Research

**Task: Identify where leads are currently being lost**
| Field | Detail |
|---|---|
| Purpose | Pinpoints the specific, fixable leaks rather than redesigning the whole system based on assumption |
| Inputs | Audit findings, available analytics data |
| Procedure | 1) Review analytics for drop-off points (e.g. visitors reaching a contact page but not completing the form). 2) Cross-reference with the audit for known broken or missing capture points. |
| Tools | Google Analytics, audit report |
| Deliverable | Documented leak/drop-off points |
| Owner | Lead-generation specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | At least the most significant leak points identified with supporting evidence |
| Quality check | Each identified leak backed by a specific data point or test finding |
| Common mistake | Guessing at where leads are lost without checking actual analytics drop-off data |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Design the lead-capture funnel and source-tagging taxonomy**
| Field | Detail |
|---|---|
| Purpose | Defines exactly how a lead moves from arrival to captured, qualified, routed record — and how it's tracked back to its source |
| Inputs | Audit findings, traffic sources in place |
| Procedure | 1) Map the funnel: traffic source → capture point → qualification → routing → follow-up. 2) Define a consistent lead-source tagging taxonomy (e.g. "Google Ads – Search," "Organic – GBP," "Instagram – DM") so every lead can be traced to what generated it. 3) Define minimum qualification criteria appropriate to the business (e.g. genuine contact detail provided, matches the service area). |
| Tools | Shared document |
| Deliverable | Lead-capture funnel design and source-tagging taxonomy |
| Owner | Lead-generation specialist |
| Dependency | Task 2.1 |
| Frequency | One-time, revisited as new traffic sources are added |
| KPI | Every current and planned traffic source has an assigned tag in the taxonomy |
| Quality check | Taxonomy reviewed against what [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md) can actually capture and report |
| Common mistake | Designing a source-tagging taxonomy too granular to realistically maintain, or too broad to be useful for reporting |
| Estimated complexity | Medium |

### 4. Setup

**Task: Set up call tracking and optimize capture points**
| Field | Detail |
|---|---|
| Purpose | Call tracking reveals which channels actually drive phone inquiries, which are otherwise invisible to standard web analytics |
| Inputs | Current phone number(s), traffic sources |
| Procedure | 1) Set up call tracking numbers per major channel where budget and setup allow (or a single tracked number with source-level web-to-call tracking as a lighter alternative). 2) Optimize existing forms per capture-point best practice (short, only necessary fields, clear submit confirmation). 3) Confirm WhatsApp Business quick replies and catalog are configured to support fast response. |
| Tools | Call-tracking service, CMS form settings, WhatsApp Business app |
| Deliverable | Configured call tracking and optimized capture points |
| Owner | Lead-generation specialist |
| Dependency | Task 3.1 |
| Frequency | One-time setup, refreshed as channels change |
| KPI | Call tracking active on at least the highest-traffic channels |
| Quality check | Tested with a real test call/submission to confirm tracking captures correctly |
| Common mistake | Building a long, multi-field form when a short one would convert meaningfully better, out of a desire to collect more information upfront |
| Estimated complexity | Medium |

**Task: Connect capture points to the CRM**
| Field | Detail |
|---|---|
| Purpose | Ensures every captured lead actually lands somewhere trackable and actionable, not scattered across disconnected inboxes |
| Inputs | CRM from 23 |
| Procedure | 1) Connect each form, call-tracking system, and messaging channel to route into the CRM. 2) Apply the source-tagging taxonomy automatically where possible. |
| Tools | CRM integrations, form/webhook connections |
| Deliverable | CRM-connected capture points |
| Owner | Lead-generation specialist, coordinating with [23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md) |
| Dependency | 23's CRM setup |
| Frequency | One-time setup |
| KPI | Every capture point routes into the CRM automatically, without manual re-entry |
| Quality check | Tested end to end with a real test lead |
| Common mistake | Leaving a capture point (e.g. WhatsApp) manually logged rather than connected, causing leads to be forgotten or entered late |
| Estimated complexity | Medium |

### 5. Production

**Task: Refine capture-point copy and confirmation messaging**
| Field | Detail |
|---|---|
| Purpose | The words on a form and the confirmation a customer receives affect both completion rate and the customer's confidence that their inquiry was received |
| Inputs | Brand voice guide |
| Procedure | 1) Write clear, specific form labels and a compelling, low-friction call-to-action. 2) Write a confirmation message/page confirming receipt and setting a response-time expectation. |
| Tools | CMS, shared document |
| Deliverable | Finalized capture-point copy and confirmation messaging |
| Owner | Lead-generation specialist, with copywriting support |
| Dependency | Task 4.1 |
| Frequency | One-time, revisited as evidence suggests |
| KPI | Every capture point has a clear confirmation message |
| Quality check | Confirmation message tested to actually display/send correctly |
| Common mistake | Leaving a generic or absent confirmation message, leaving the customer unsure whether their inquiry actually went through |
| Estimated complexity | Low |

### 6. Implementation

**Task: Build lead-routing rules and notification alerts**
| Field | Detail |
|---|---|
| Purpose | Ensures the right person is notified immediately when a lead arrives, matched appropriately if multiple staff or locations are involved |
| Inputs | Staff responsibilities, CRM |
| Procedure | 1) Define routing rules (e.g. by service type, location, or source) if more than one person/team handles leads. 2) Set up immediate notification alerts (email, SMS, or app notification) to the responsible person. |
| Tools | CRM automation, notification settings |
| Deliverable | Configured routing rules and active notifications |
| Owner | Lead-generation specialist |
| Dependency | Task 4.2 |
| Frequency | One-time setup, updated as staff/structure change |
| KPI | Every lead triggers an immediate notification to the correct responsible person |
| Quality check | Tested with a real test lead per routing rule |
| Common mistake | Setting up a single generic notification address that isn't actually monitored promptly by anyone in particular |
| Estimated complexity | Medium |

### 7. Testing

**Task: Test every capture point end to end**
| Field | Detail |
|---|---|
| Purpose | Confirms the entire system — from a customer's action to a staff member's notification — actually works before relying on it |
| Inputs | Fully configured system |
| Procedure | 1) Submit a real test form. 2) Place a real test call to the tracked number. 3) Send a real test WhatsApp message. 4) Confirm each generates a correctly tagged, routed CRM record and a prompt notification. |
| Tools | Real device/channel testing |
| Deliverable | Verified, fully functioning end-to-end system |
| Owner | Lead-generation specialist |
| Dependency | Task 6.1 |
| Frequency | One-time at launch, repeated at each quarterly audit |
| KPI | Every channel confirmed functional end to end |
| Quality check | Tested as a real customer would, not just checked in the admin dashboards |
| Common mistake | Confirming each piece works in isolation (form submits, CRM has a record) without confirming the full chain including the actual notification reaching a person |
| Estimated complexity | Low |

### 8. Launch

**Task: Activate the system and brief staff on the new process**
| Field | Detail |
|---|---|
| Purpose | Ensures staff actually know and follow the new process from day one |
| Inputs | Verified system |
| Procedure | 1) Confirm the system is fully live. 2) Brief every staff member involved in lead follow-up on the new routing, notification, and response-time expectations. |
| Tools | Training session, quick-reference document |
| Deliverable | Live system with briefed staff |
| Owner | Lead-generation specialist, account lead |
| Dependency | Task 7.1 |
| Frequency | One-time per client |
| KPI | All relevant staff briefed before go-live |
| Quality check | Staff can correctly describe the response-time expectation when asked |
| Common mistake | Launching the technical system without ensuring staff actually understand and adopt the new process, so leads still get handled inconsistently |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor lead volume by source and response-time adherence**
| Field | Detail |
|---|---|
| Purpose | Confirms the system is working and that leads are actually being followed up promptly |
| Inputs | CRM data |
| Procedure | 1) Review lead volume broken down by source tag. 2) Review response-time adherence against the agreed standard. 3) Watch for any capture point that suddenly stops producing leads, which often signals a silent technical failure. |
| Tools | CRM reporting |
| Deliverable | Ongoing lead-volume and response-time monitoring log |
| Owner | Lead-generation specialist |
| Dependency | Task 8.1 |
| Frequency | Weekly |
| KPI | Log updated weekly without gaps |
| Quality check | A sudden drop in leads from any single source investigated promptly, not dismissed as normal variation |
| Common mistake | Not noticing a form has silently broken because overall lead volume from other channels masked the drop from that one source |
| Estimated complexity | Low |

### 10. Optimization

**Task: Fix leaks and test capture-point improvements**
| Field | Detail |
|---|---|
| Purpose | Continuously improves the percentage of traffic that actually converts into a captured lead |
| Inputs | Monitoring log, leak points from Task 2.1 |
| Procedure | 1) Address identified drop-off points (e.g. shortening a form, clarifying a call-to-action). 2) Test one meaningful change at a time and measure the effect. 3) Refine qualification criteria if too many or too few inquiries are being treated as qualified leads. |
| Tools | CRM data, CMS |
| Deliverable | Improved capture-point performance |
| Owner | Lead-generation specialist, coordinating with [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md) |
| Dependency | Task 9.1 |
| Frequency | Monthly, or as evidence warrants |
| KPI | Measurable improvement in the capture rate for the targeted leak point |
| Quality check | One variable changed at a time where practical, so the cause of any improvement is identifiable |
| Common mistake | Changing multiple elements of a capture point simultaneously, making it impossible to know which change actually helped |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly lead-generation report**
| Field | Detail |
|---|---|
| Purpose | Connects the capture-and-routing system's performance to real business outcomes the client cares about |
| Inputs | Monitoring log |
| Procedure | 1) Summarize total leads by source, response-time adherence, and qualification rate. 2) Highlight any leak points fixed and their measured impact. |
| Tools | Report template, CRM reporting |
| Deliverable | Monthly lead-generation report |
| Owner | Lead-generation specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Figures cross-checked against the CRM directly |
| Common mistake | Reporting raw lead counts without any source breakdown, leaving the client unable to see which channels are actually working |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Periodic capture-point health check**
| Field | Detail |
|---|---|
| Purpose | Capture points can silently break (a form integration fails after a CMS update, a tracked number gets disconnected) without any obvious warning sign |
| Inputs | Live capture points |
| Procedure | 1) Re-test every capture point end to end on a quarterly basis, using the same method as Task 7.1. 2) Update routing rules whenever staff or business structure changes. |
| Tools | Real channel testing |
| Deliverable | Confirmed, currently functioning capture system |
| Owner | Lead-generation specialist |
| Dependency | Ongoing |
| Frequency | Quarterly, or immediately if a lead-volume anomaly is noticed |
| KPI | Zero broken capture points found during the quarterly check |
| Quality check | Tested exactly as a real customer would use it |
| Common mistake | Assuming a system that worked at launch still works months later without ever re-testing it |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Lead-capture audit report
- Documented leak/drop-off points
- Lead-capture funnel design and source-tagging taxonomy
- Configured call tracking, optimized forms, and CRM-connected capture points
- Configured routing rules and notification alerts
- Verified, fully functioning end-to-end system

**Monthly deliverables**
- Lead-volume and response-time monitoring
- Capture-point optimization based on evidence
- Monthly lead-generation report

**Quarterly deliverables**
- Full capture-point health check and re-audit

**Optional add-ons**
- Expanded call-tracking coverage across more channels/numbers
- Lead-scoring model development (coordinated with [23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md))

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Capture points functioning correctly (health check pass rate) | Leading | Directly attributable |
| Response-time adherence | Leading | Directly attributable |
| Leads captured per traffic source | Leading | Directly attributable to this service's routing/tagging, though volume also depends on the traffic-generating services |
| Form/capture-point conversion rate | Lagging | Shared with [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md) and page design quality |
| Lead-to-sale conversion rate | Lagging | Influenced heavily by sales process and follow-up quality, not just capture — report as a shared outcome |
| Cost per lead (where paired with paid traffic) | Lagging | Combines this service's capture efficiency with the traffic service's cost — attribute to both, not this service alone |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Native CMS form tools, Google Analytics for drop-off analysis, WhatsApp Business app | Sufficient for a single-location SME's basic capture needs |
| Low-cost | Entry-tier call-tracking services | Useful once tracking phone-source attribution becomes valuable enough to justify the cost |
| Professional | Multi-channel call-tracking and attribution platforms | Justified for larger, multi-channel, higher lead-volume clients |
| Low-bandwidth / mobile-first consideration | Short, fast-loading forms and WhatsApp-first capture options, since many customers will inquire from a mobile device on a constrained connection | Directly affects completion rate for the majority of real inquiries |

## H. Risks and Common Failure Modes

- **Technical risk:** a form or integration silently breaking after an unrelated CMS or platform update.
- **Platform risk:** a messaging or call-tracking platform changing its API or feature availability over time.
- **Client-related risk:** staff not adopting the new routing/response-time process, leaving leads to sit unanswered despite the technical system working correctly.
- **Data and access risk:** a capture point not properly connected to the CRM, causing leads to be lost or duplicated.
- **Reputation risk:** a slow or absent response to a captured lead undoes the value of the entire system — the capture is only half the job.
- **Security risk:** lead data (customer contact details) should be handled per [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md) and access-controlled per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md).
- **Legal or compliance risk:** consent and data-handling requirements for captured customer information must be respected, especially for ⚠️-flagged sectors.
- **Measurement and attribution risk:** lead-to-sale outcomes depend heavily on sales process quality, not capture alone — avoid overstating this service's sole contribution to final sales results.

## I. Standard Operating Procedure

- [ ] Every current capture point audited by real test interaction, not assumption
- [ ] Analytics drop-off points identified and documented
- [ ] Lead-capture funnel and source-tagging taxonomy designed
- [ ] Call tracking configured; forms optimized for length and clarity
- [ ] Capture points connected to the CRM with automatic source tagging
- [ ] Capture-point copy and confirmation messaging finalized
- [ ] Routing rules and immediate notification alerts configured and tested
- [ ] Full end-to-end test completed across every channel before launch
- [ ] Staff briefed on the new process and response-time expectations
- [ ] Lead volume by source and response-time adherence monitored weekly
- [ ] Leak points addressed with one-variable-at-a-time evidence-based changes
- [ ] Monthly report delivered with a clear source breakdown
- [ ] Full capture-point health check repeated quarterly; routing rules kept current as staff change
