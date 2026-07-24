# Service: CRM and Marketing Automation

## A. Service Definition

**What it is.** Selection, setup, and ongoing management of a customer relationship management (CRM) system that stores every lead and customer record, tracks their stage in the sales pipeline, and automates routine follow-up tasks and reminders so nothing falls through the cracks.

**What business problem it solves.** Without a CRM, leads live in someone's head, a notebook, or scattered chat threads. Leads get forgotten, follow-up is inconsistent from one staff member to the next, and there's no visibility into the overall pipeline or a customer's history with the business.

**Why a customer would pay for it.** Choosing the right CRM for the business's actual scale and budget, structuring it around the real sales process, and building genuinely useful automation all require setup expertise. A badly configured or overly complex CRM gets abandoned by staff within weeks — the setup quality determines whether the tool is actually used.

**Business types that benefit most.** Any business with more than a handful of leads or customers to track at once, especially higher lead-value or longer-sales-cycle segments (real estate, B2B, clinics, education) — see [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md). A very small business the owner can track personally may not need this immediately — recommend the smallest workable solution per [../01_AGENCY_STRATEGY_AND_POSITIONING.md](../01_AGENCY_STRATEGY_AND_POSITIONING.md) §10.

**What this does not include.** The capture-point setup itself ([20_LEAD_GENERATION.md](20_LEAD_GENERATION.md) builds the forms/tracking that feed data in; this service stores and manages what's captured). Messaging campaign content ([22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md) uses this system's data and segmentation but owns its own campaign content). The human sales process itself ([../operations/03_SALES_PROCESS.md](../operations/03_SALES_PROCESS.md) — this system supports and structures the process, it doesn't replace human selling).

**How it connects to other services.** Receives captured leads from 20. Feeds segments to 22. Supports [../operations/09_QUALITY_ASSURANCE.md](../operations/09_QUALITY_ASSURANCE.md) and [../operations/12_CLIENT_RETENTION_AND_UPSELLING.md](../operations/12_CLIENT_RETENTION_AND_UPSELLING.md) with pipeline and history visibility. Reports through [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Platform selection, pipeline/data structure setup, automation-rule building, staff training, ongoing management |
| Output | A configured CRM, defined pipeline stages, automated follow-up sequences and reminders, adopted by staff |
| Outcome | Every lead is tracked and followed up consistently, with full visibility into the pipeline and each customer's history |
| Financial impact | Fewer lost sales from missed follow-up, more efficient staff time, better retention from consistent visibility into customer history |

## C. Inputs Required From the Client

- The current (even if informal) method of tracking leads/customers
- The real sales process steps from [../operations/03_SALES_PROCESS.md](../operations/03_SALES_PROCESS.md)
- Staff who will use the CRM, and their general comfort level with software tools
- A realistic budget for CRM software
- Integration needs — which capture points (20) and messaging platforms (22) need to connect
- What follow-up work should be automated versus handled manually by staff

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Assess business complexity to determine the appropriate CRM tier**
| Field | Detail |
|---|---|
| Purpose | Prevents both under-tooling a business that genuinely needs a fuller system and over-tooling a small business that will abandon a complex one |
| Inputs | Lead/customer volume, sales-process complexity, staff count |
| Procedure | 1) Assess current and expected lead/customer volume. 2) Assess how many people need to use the system and how complex the sales process actually is. 3) Recommend a CRM tier matched to this reality — a simple, free/low-cost tool for a small, single-person sales process; a fuller platform for a multi-stage, multi-person process. |
| Tools | Discovery conversation |
| Deliverable | Documented CRM-tier recommendation |
| Owner | CRM specialist |
| Dependency | Onboarding complete |
| Frequency | One-time per client |
| KPI | Recommendation matched to actual complexity, not the most feature-rich option by default |
| Quality check | Recommendation checked against the client's realistic staff capacity to actually use it |
| Common mistake | Recommending an enterprise-grade CRM to a business with one person handling all sales, guaranteeing it gets abandoned as too complex |
| Estimated complexity | Low |

**Task: Confirm the real sales process to model**
| Field | Detail |
|---|---|
| Purpose | The CRM should reflect how the business actually sells, not a generic template |
| Inputs | [../operations/03_SALES_PROCESS.md](../operations/03_SALES_PROCESS.md), client interview |
| Procedure | 1) Walk through the client's actual steps from first contact to closed sale (or lost). 2) Document each real stage, including any that a generic CRM template wouldn't anticipate. |
| Tools | Shared document |
| Deliverable | Documented real sales-process steps |
| Owner | CRM specialist |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited if the sales process changes |
| KPI | Process documented directly from the client's real practice, not assumed |
| Quality check | Reviewed with whoever actually handles sales day to day, not just the owner's idealized version of the process |
| Common mistake | Modeling the CRM on a generic textbook sales funnel that doesn't match how this specific business actually operates |
| Estimated complexity | Medium |

### 2. Research

**Task: Evaluate CRM platform options**
| Field | Detail |
|---|---|
| Purpose | Different CRM platforms fit different budgets, technical comfort levels, and integration needs |
| Inputs | Tier recommendation, integration needs |
| Procedure | 1) Compare a shortlist of CRM platforms appropriate to the recommended tier against budget, ease of use, and required integrations (capture points, messaging platforms). 2) Confirm the shortlist against what's actually usable and supported in Ethiopia (billing, currency, local payment options for the subscription). |
| Tools | CRM platform comparison, vendor documentation |
| Deliverable | Shortlisted, evaluated CRM options |
| Owner | CRM specialist |
| Dependency | Task 1.1 |
| Frequency | One-time per client, revisited if needs change materially |
| KPI | Shortlist narrowed to 2–3 realistic options with a clear recommendation |
| Quality check | Each option checked for the specific integrations this client actually needs, not assumed compatible |
| Common mistake | Recommending a platform based on general popularity without confirming it actually supports the client's required integrations or billing situation |
| Estimated complexity | Medium |

**Task: Audit existing (informal) lead/customer data for import**
| Field | Detail |
|---|---|
| Purpose | Most clients have some existing record (a spreadsheet, a notebook, scattered contacts) worth preserving rather than starting from zero |
| Inputs | Client's existing records |
| Procedure | 1) Review existing lead/customer records for quality and completeness. 2) Identify what can be cleanly imported versus what needs to be manually re-entered or discarded as unreliable. |
| Tools | Existing spreadsheets/records |
| Deliverable | Data-import assessment |
| Owner | CRM specialist |
| Dependency | Task 1.2 |
| Frequency | One-time |
| KPI | Existing usable data identified before setup, not discovered mid-import |
| Quality check | Data reviewed for consent status consistent with [22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md) Task 1.1 before being imported for marketing use |
| Common mistake | Importing an old, unmaintained contact list wholesale without checking data quality or consent status first |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Design pipeline stages and data fields**
| Field | Detail |
|---|---|
| Purpose | Converts the real sales process into the actual structure the CRM will use |
| Inputs | Documented sales-process steps |
| Procedure | 1) Define pipeline stages matching each real step in the sales process. 2) Define the data fields to track per contact (only what's actually useful — avoid collecting data with no clear purpose). 3) Define what "won" and "lost" mean and how a lost reason gets recorded. |
| Tools | Shared document |
| Deliverable | Pipeline stage and data-field design |
| Owner | CRM specialist |
| Dependency | Task 1.2 |
| Frequency | One-time, revisited if the sales process changes |
| KPI | Every real sales-process step has a corresponding pipeline stage |
| Quality check | Reviewed for unnecessary fields that add data-entry burden without real analytical or follow-up value |
| Common mistake | Adding too many required fields, making data entry so tedious that staff stop updating records consistently |
| Estimated complexity | Medium |

**Task: Define automation rules**
| Field | Detail |
|---|---|
| Purpose | Specifies exactly what should happen automatically versus what needs a human decision |
| Inputs | Pipeline design, follow-up expectations from Task C |
| Procedure | 1) Define trigger-based automations (e.g. a new lead gets an automatic acknowledgment and a task assigned to a staff member; a lead untouched for X days triggers a reminder). 2) Confirm which follow-ups should remain manual/human-judgment-based rather than automated. |
| Tools | Shared document |
| Deliverable | Defined automation rules |
| Owner | CRM specialist |
| Dependency | Task 3.1 |
| Frequency | One-time, revisited quarterly |
| KPI | Every pipeline stage has a defined follow-up expectation, automated or manual |
| Quality check | Automation rules checked to avoid producing generic, obviously automated messages where a human touch matters more |
| Common mistake | Automating every single touchpoint, producing an impersonal experience for what should be a relationship-driven, human sales process |
| Estimated complexity | Medium |

### 4. Setup

**Task: Set up the CRM account and configure the pipeline**
| Field | Detail |
|---|---|
| Purpose | Establishes the actual working system under client ownership |
| Inputs | Platform selection, pipeline/field design |
| Procedure | 1) Set up the CRM account under the client's own ownership, per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md). 2) Configure the pipeline stages and data fields as designed. 3) Import the assessed, cleaned existing data. |
| Tools | Selected CRM platform |
| Deliverable | Configured CRM with imported data |
| Owner | CRM specialist |
| Dependency | Tasks 2.1, 3.1 |
| Frequency | One-time setup |
| KPI | Pipeline and fields match the approved design exactly |
| Quality check | Imported data spot-checked for accuracy after import |
| Common mistake | Setting up the CRM under the agency's own account, creating an ownership dispute later |
| Estimated complexity | Medium |

### 5. Production

**Task: Build automation workflows**
| Field | Detail |
|---|---|
| Purpose | Turns the defined automation rules into working, active workflows |
| Inputs | Automation rules from Task 3.2 |
| Procedure | 1) Build each defined trigger-based workflow (acknowledgment messages, task assignments, stale-lead reminders). 2) Write any templated messages the automation sends, keeping them genuinely helpful rather than generic. |
| Tools | CRM automation builder |
| Deliverable | Built automation workflows |
| Owner | CRM specialist |
| Dependency | Task 3.2 |
| Frequency | One-time initial build, refined ongoing |
| KPI | Every defined automation rule has a corresponding built workflow |
| Quality check | Workflow logic reviewed for edge cases (e.g. what happens if a lead is marked won before the automated reminder fires) |
| Common mistake | Building a workflow that doesn't account for a lead moving stages faster than expected, causing an awkward, out-of-context automated message |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Connect integrations and set up staff accounts**
| Field | Detail |
|---|---|
| Purpose | Makes the CRM the actual central hub receiving leads and enabling staff to work in it |
| Inputs | 20's capture points, 22's messaging platforms, staff list |
| Procedure | 1) Connect capture points from 20 so new leads flow in automatically. 2) Connect messaging platforms from 22 for segment syncing. 3) Set up individual staff accounts with role-appropriate access levels. |
| Tools | CRM integration settings |
| Deliverable | Connected integrations and configured staff accounts |
| Owner | CRM specialist |
| Dependency | Task 4.1 |
| Frequency | One-time setup |
| KPI | Every planned integration confirmed connected |
| Quality check | Each staff account tested to confirm correct access level, not over- or under-permissioned |
| Common mistake | Granting every staff member full administrative access rather than the minimum needed for their role |
| Estimated complexity | Medium |

### 7. Testing

**Task: Test automations and integrations end to end**
| Field | Detail |
|---|---|
| Purpose | Confirms the whole system actually works together before staff start relying on it |
| Inputs | Configured CRM |
| Procedure | 1) Submit a real test lead through a connected capture point and confirm it arrives correctly in the CRM with the right stage/fields. 2) Move a test record through the full pipeline, confirming each automation fires as designed. 3) Confirm messaging-platform segment syncing works correctly. |
| Tools | Real test submissions |
| Deliverable | Verified, fully functioning system |
| Owner | CRM specialist |
| Dependency | Task 6.1 |
| Frequency | One-time before launch |
| KPI | Every integration and automation confirmed working via a real test |
| Quality check | Tested as a real lead/customer record would move through the system, not just checked in isolation |
| Common mistake | Testing each integration individually but never testing the full end-to-end flow of a single record through the whole pipeline |
| Estimated complexity | Medium |

### 8. Launch

**Task: Train staff and activate the live system**
| Field | Detail |
|---|---|
| Purpose | A CRM only works if staff actually use it correctly and consistently — this is the single biggest determinant of whether the investment pays off |
| Inputs | Verified system |
| Procedure | 1) Train every staff member who will use the CRM on the pipeline, data-entry expectations, and what's automated versus manual. 2) Confirm each staff member can complete a basic task (move a lead, log an interaction) unassisted. 3) Formally activate the live system. |
| Tools | Training session, quick-reference guide |
| Deliverable | Trained staff and a live, activated CRM |
| Owner | CRM specialist, account lead |
| Dependency | Task 7.1 |
| Frequency | One-time per client, refreshed for new hires |
| KPI | Every relevant staff member confirmed able to complete basic tasks before go-live |
| Quality check | Training confirmed with a real, observed task completion, not just a presentation |
| Common mistake | Setting up a technically excellent CRM but skipping proper staff training, so it gets used inconsistently or abandoned within weeks |
| Estimated complexity | Medium |

### 9. Monitoring

**Task: Monitor staff adoption and stalled leads**
| Field | Detail |
|---|---|
| Purpose | Confirms the system is actually being used as intended and catches leads sitting untouched before they're lost |
| Inputs | CRM usage data |
| Procedure | 1) Review whether staff are updating records consistently. 2) Review the pipeline for leads sitting untouched beyond the expected follow-up window. |
| Tools | CRM reporting |
| Deliverable | Adoption and stalled-lead monitoring log |
| Owner | CRM specialist, account lead |
| Dependency | Task 8.1 |
| Frequency | Weekly for the first month, then monthly |
| KPI | No lead left untouched beyond its expected follow-up window without being flagged |
| Quality check | Adoption gaps addressed directly with the relevant staff member, not just noted passively |
| Common mistake | Noticing low staff adoption in the data but never actually following up with the team about why, letting the problem persist |
| Estimated complexity | Low |

### 10. Optimization

**Task: Refine pipeline and automation based on real usage**
| Field | Detail |
|---|---|
| Purpose | The initial design is a first attempt — real usage patterns reveal what actually needs adjusting |
| Inputs | Monitoring log, staff feedback |
| Procedure | 1) Gather staff feedback on what's working and what's friction. 2) Adjust pipeline stages, fields, or automation rules based on real evidence. 3) Address any adoption gap with additional training or a simplified process. |
| Tools | Staff feedback, CRM configuration |
| Deliverable | Refined pipeline and automation |
| Owner | CRM specialist |
| Dependency | Task 9.1 |
| Frequency | Monthly for the first quarter, then quarterly |
| KPI | At least one evidence-based refinement made in the first quarter if adoption data suggests friction |
| Quality check | Refinement tied to specific staff feedback or usage data, not assumption |
| Common mistake | Never revisiting the initial CRM configuration even after clear evidence that a particular field or stage isn't being used as intended |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly CRM health and pipeline report**
| Field | Detail |
|---|---|
| Purpose | Gives the client visibility into the pipeline's overall health, not just individual campaign results |
| Inputs | CRM data |
| Procedure | 1) Summarize leads by stage, follow-up compliance, and conversion rate by stage. 2) Highlight any stalled or at-risk leads. |
| Tools | Report template, CRM reporting |
| Deliverable | Monthly CRM health and pipeline report |
| Owner | CRM specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | Report delivered on a consistent monthly date |
| Quality check | Figures cross-checked directly against the CRM |
| Common mistake | Reporting only total lead count without a stage breakdown, hiding where in the pipeline leads are actually getting stuck |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Maintain data hygiene and user access**
| Field | Detail |
|---|---|
| Purpose | An unmaintained CRM accumulates duplicate and stale records over time, undermining its usefulness |
| Inputs | Ongoing CRM data |
| Procedure | 1) Periodically identify and merge duplicate records. 2) Archive or clean up long-stale records per an agreed policy. 3) Update user access as staff join or leave, following the same discipline as [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md). |
| Tools | CRM data-management tools |
| Deliverable | A clean, currently accurate CRM with correct user access |
| Owner | CRM specialist |
| Dependency | Ongoing |
| Frequency | Quarterly |
| KPI | Zero duplicate records found during the quarterly review; no departed staff member retaining active access |
| Quality check | Access list cross-checked against actual current staff |
| Common mistake | Leaving a departed staff member's CRM access active long after they've left, particularly a risk given the sensitive customer data involved |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Documented CRM-tier recommendation and real sales-process mapping
- Evaluated CRM platform shortlist and recommendation
- Configured pipeline, data fields, and imported existing data
- Built and tested automation workflows
- Connected integrations (capture points, messaging platforms) and configured staff accounts
- Trained staff and a live, activated system

**Monthly deliverables**
- Adoption and stalled-lead monitoring
- Monthly CRM health and pipeline report

**Quarterly deliverables**
- Pipeline/automation refinement based on real usage
- Data hygiene and user-access review

**Optional add-ons**
- Advanced lead-scoring model development
- Expanded automation for more complex, multi-branch follow-up sequences
- Additional staff training sessions for new hires or a platform migration

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Staff adoption (records updated consistently) | Leading | Directly attributable to training quality and system usability |
| Automations firing correctly | Leading | Directly attributable |
| Leads followed up within the expected window | Leading | Directly attributable to the system and staff discipline together |
| Stalled-lead count | Lagging | A useful diagnostic signal, directly actionable |
| Conversion rate by pipeline stage | Lagging | Reflects sales-process and staff performance as much as the CRM system itself |
| Lead-to-sale conversion overall | Lagging | Shared outcome across lead-generation quality (20), sales skill, and CRM discipline — not attributable to this service alone |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Free-tier CRM platforms (e.g. HubSpot's free tier or equivalent), a simple spreadsheet-based system for a very small business | Sufficient for a small business's first structured system |
| Low-cost | Paid-tier small-business CRM platforms | Useful once volume or automation needs exceed free-tier limits |
| Professional | Enterprise CRM platforms with advanced automation and reporting | Justified only for larger, multi-team, higher-volume businesses — avoid recommending by default |
| Low-bandwidth / mobile-first consideration | A CRM with a functional, lightweight mobile app or mobile-friendly web interface, since staff (especially in field-based or walk-in businesses) will often need to log activity away from a desktop | Directly affects whether staff actually keep records updated in real time |

## H. Risks and Common Failure Modes

- **Technical risk:** an automation workflow misfiring due to an unanticipated edge case (e.g. a lead skipping a stage).
- **Platform risk:** CRM platforms change pricing tiers, features, or integration support over time — verify current terms before recommending.
- **Client-related risk:** low staff adoption undermining the entire investment, regardless of how well the system itself is configured.
- **Data and access risk:** CRM set up under the agency's account instead of the client's, or departed staff retaining access — see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md).
- **Reputation risk:** an over-automated system that feels impersonal to leads/customers in what should be a relationship-driven sales process.
- **Security risk:** the CRM holds sensitive customer contact and, potentially, financial data — access must be role-based and tightly controlled.
- **Legal or compliance risk:** customer data stored in the CRM must be handled per [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md), including consent records feeding [22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md](22_EMAIL_SMS_AND_WHATSAPP_MARKETING.md).
- **Measurement and attribution risk:** pipeline conversion metrics reflect sales skill and process quality as much as the CRM tool itself — avoid presenting CRM adoption alone as the cause of a sales-conversion change.

## I. Standard Operating Procedure

- [ ] Business complexity assessed and CRM tier matched realistically, not over- or under-specified
- [ ] Real sales-process steps documented directly from whoever handles sales day to day
- [ ] CRM platform evaluated and selected against budget, usability, and required integrations
- [ ] Existing lead/customer data assessed for import quality and consent status
- [ ] Pipeline stages and data fields designed to match the real process, avoiding unnecessary fields
- [ ] Automation rules defined, balancing automation with genuine human touch where it matters
- [ ] CRM account set up under client ownership; pipeline configured; data imported and spot-checked
- [ ] Automation workflows built and reviewed for edge cases
- [ ] Integrations connected and staff accounts configured at appropriate access levels
- [ ] Full end-to-end test completed with a real test record moving through the pipeline
- [ ] Staff trained and confirmed able to complete basic tasks before go-live
- [ ] Adoption and stalled leads monitored weekly for the first month, then monthly
- [ ] Pipeline/automation refined based on real usage evidence and staff feedback
- [ ] Monthly report delivered with a full stage breakdown, not just totals
- [ ] Data hygiene and user access reviewed quarterly
