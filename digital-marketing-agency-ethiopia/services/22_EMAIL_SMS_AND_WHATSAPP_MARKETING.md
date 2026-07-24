# Service: Email, SMS, and WhatsApp Marketing

## A. Service Definition

**What it is.** Planning and executing direct messaging campaigns — email, SMS, and WhatsApp — to existing customers and captured leads, for promotions, updates, appointment/booking reminders, re-engagement, and relationship-building, always built on documented, genuine consent.

**What business problem it solves.** Most SME businesses have no systematic way of staying in touch with past customers or nurturing a captured lead who wasn't ready to buy immediately. Marketing spend keeps chasing new customers while a cheaper, often higher-converting opportunity — repeat business from people who already know the business — goes untapped.

**Why a customer would pay for it.** Direct messaging is one of the lowest-cost, highest-return channels available, but it requires disciplined list management, real consent, sensible timing and frequency, and channel-appropriate writing to avoid annoying recipients — or, on WhatsApp specifically, risking the business number being blocked or restricted for unsolicited messaging.

**Business types that benefit most.** Any business with meaningful repeat-purchase potential or a longer consideration cycle needing nurturing — see the "Repeat-purchase potential" dimension in [../market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md](../market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md). Especially relevant for retail, hospitality, healthcare (appointment reminders), education, and B2B relationship-building.

**What this does not include.** Initial lead capture ([20_LEAD_GENERATION.md](20_LEAD_GENERATION.md) — this service messages people already captured there). Deep CRM/automation platform configuration ([23_CRM_AND_MARKETING_AUTOMATION.md](23_CRM_AND_MARKETING_AUTOMATION.md) owns the underlying system; this service defines campaign content and strategy running on top of it). Social media direct messages, which fall under [13_SOCIAL_MEDIA_MANAGEMENT.md](13_SOCIAL_MEDIA_MANAGEMENT.md)'s community management.

**How it connects to other services.** Consumes captured leads/customers and consent status from 20/23. Follows the copy/tone discipline from [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md). Review-request messages specifically are owned by [11_REVIEW_AND_REPUTATION_MANAGEMENT.md](11_REVIEW_AND_REPUTATION_MANAGEMENT.md), not duplicated here. Reports through [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | List segmentation, campaign planning, message creation, sending, performance tracking |
| Output | Segmented, consent-documented contact lists, a campaign calendar, sent campaigns, performance reports |
| Outcome | Repeat purchases, re-engaged dormant customers, and leads nurtured toward a sale |
| Financial impact | Low-cost incremental revenue from the existing customer/lead base, at a lower cost than acquiring an equivalent new customer |

## C. Inputs Required From the Client

- The existing customer/lead database from 20/23, with consent status documented per contact
- Access to the email platform, SMS gateway, and WhatsApp Business account (from 12)
- Brand voice and tone guidance
- Offers, promotions, and updates to communicate
- The business's realistic messaging-frequency tolerance for its customers
- Awareness of any regulatory consent requirements relevant to the client's sector

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Audit the existing contact list and consent status**
| Field | Detail |
|---|---|
| Purpose | Messaging anyone without genuine consent is both an ethical problem and, particularly on WhatsApp, a real risk to the business number's standing on the platform |
| Inputs | Existing customer/lead data |
| Procedure | 1) Review the current contact list for how each contact was acquired and whether real consent to be messaged exists. 2) Separate contacts into consented (eligible to message), unclear (needs a fresh opt-in before messaging), and do-not-contact. |
| Tools | CRM/contact list, shared spreadsheet |
| Deliverable | Consent-audited contact list |
| Owner | Messaging specialist |
| Dependency | 20/23's captured contact data |
| Frequency | One-time initial audit, repeated quarterly |
| KPI | Every contact classified by consent status before any campaign is sent |
| Quality check | "Unclear" contacts never moved to "consented" without an actual fresh opt-in action |
| Common mistake | Assuming everyone who ever submitted a form or made a purchase has consented to ongoing marketing messages, when they may have only consented to a single transaction-related contact |
| Estimated complexity | Medium |

### 2. Research

**Task: Segment the audience and assess channel preference**
| Field | Detail |
|---|---|
| Purpose | A single generic message to everyone performs worse than a relevant message to the right segment on the right channel |
| Inputs | Consent-audited list, purchase/engagement history |
| Procedure | 1) Segment contacts by relevant criteria (purchase history, lead stage, engagement level, location if relevant). 2) Where known, note each segment's likely channel preference (e.g. WhatsApp for immediate, conversational contact; email for longer-form or B2B content). |
| Tools | CRM segmentation tools |
| Deliverable | Segmented audience with channel-preference notes |
| Owner | Messaging specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | At least the most useful segments (e.g. past customers vs. uncontacted leads) defined |
| Quality check | Segments reviewed for whether they actually change what message/channel would be used |
| Common mistake | Building overly granular segments that don't meaningfully change the campaign approach, adding complexity without benefit |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Define campaign types, cadence, and consent process per channel**
| Field | Detail |
|---|---|
| Purpose | Sets clear rules for what gets sent, how often, and how consent is obtained and honored on each channel |
| Inputs | Segments, business messaging-frequency tolerance |
| Procedure | 1) Define the campaign types per channel: promotional, transactional/reminder (e.g. appointment confirmations), re-engagement (dormant customers), and nurture sequences (leads not yet ready to buy). 2) Define a sensible sending cadence per channel that avoids over-messaging. 3) Define the explicit opt-in process for each channel and how an easy opt-out/unsubscribe is provided. |
| Tools | Shared document |
| Deliverable | Documented campaign types, cadence, and consent process per channel |
| Owner | Messaging specialist, account lead |
| Dependency | Task 2.1 |
| Frequency | One-time, revisited quarterly |
| KPI | Every channel has an explicit opt-in mechanism and opt-out method documented |
| Quality check | Cadence reviewed against WhatsApp Business policy and general anti-spam good practice specifically, given the higher risk of account restriction on that channel |
| Common mistake | Messaging too frequently on WhatsApp in particular, risking the business account being reported and restricted by recipients |
| Estimated complexity | Medium |

### 4. Setup

**Task: Connect messaging platforms and configure segmentation**
| Field | Detail |
|---|---|
| Purpose | Establishes the technical infrastructure needed to actually send and track campaigns |
| Inputs | Email platform, SMS gateway, WhatsApp Business account |
| Procedure | 1) Connect/configure the email platform, SMS gateway, and WhatsApp Business account (or WhatsApp Business API for higher-volume needs) to the CRM. 2) Set up the defined segments as usable lists within each platform. 3) Configure unsubscribe/opt-out handling to update the CRM automatically. |
| Tools | Email marketing platform, SMS gateway, WhatsApp Business app/API, CRM |
| Deliverable | Connected platforms with working segmentation and opt-out handling |
| Owner | Messaging specialist |
| Dependency | Task 3.1 |
| Frequency | One-time setup |
| KPI | Opt-out from any channel confirmed to update the contact's status across the system |
| Quality check | Tested with a real opt-out action to confirm it's honored correctly and doesn't require manual intervention |
| Common mistake | An opt-out request on one channel not being reflected in the CRM, so the contact continues receiving messages on another channel |
| Estimated complexity | Medium |

### 5. Production

**Task: Write campaign content per channel**
| Field | Detail |
|---|---|
| Purpose | Each channel has a different format, tone expectation, and constraint — content should be written for the specific channel, not copy-pasted across all three |
| Inputs | Campaign type, segment, brand voice |
| Procedure | 1) Write email content appropriate for longer-form messaging with a clear subject line and call-to-action. 2) Write SMS content within character limits, front-loading the key message. 3) Write WhatsApp content in a natural, conversational tone appropriate to a messaging app, not a broadcast-style announcement. |
| Tools | Email platform editor, shared document |
| Deliverable | Channel-appropriate campaign content |
| Owner | Messaging specialist, with copywriting support |
| Dependency | Task 3.1 |
| Frequency | Per campaign |
| KPI | Content format and tone appropriate to each specific channel |
| Quality check | Reviewed against the brand voice guide and each platform's current content policy |
| Common mistake | Writing one message and sending the identical text across email, SMS, and WhatsApp regardless of each channel's different norms and constraints |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Schedule campaigns and set up automated trigger-based sequences**
| Field | Detail |
|---|---|
| Purpose | Some messages should be sent as one-off campaigns; others work better as automated sequences triggered by a specific action (a welcome message after signup, an appointment reminder, a follow-up after an inquiry) |
| Inputs | Campaign content, defined cadence |
| Procedure | 1) Schedule one-off campaigns for the appropriate send time per segment. 2) Build automated sequences for recurring, trigger-based messages (welcome, reminder, re-engagement after a period of inactivity). |
| Tools | Email/SMS/WhatsApp platform automation features |
| Deliverable | Scheduled campaigns and active automated sequences |
| Owner | Messaging specialist |
| Dependency | Task 5.1 |
| Frequency | Per campaign; automated sequences set up once and run ongoing |
| KPI | Every planned automated sequence tested and confirmed triggering correctly |
| Quality check | Trigger conditions tested with a real test action |
| Common mistake | Building an automated sequence but never testing that its trigger condition actually fires correctly, discovering the gap only when a real customer never received it |
| Estimated complexity | Medium |

### 7. Testing

**Task: Send test messages and verify opt-out functionality**
| Field | Detail |
|---|---|
| Purpose | Catches formatting, link, or personalization errors before they reach the full list, and confirms opt-out actually works |
| Inputs | Scheduled campaign |
| Procedure | 1) Send a test message to an internal recipient on each channel. 2) Check formatting, personalization (e.g. name fields), and that all links work. 3) Test the opt-out/unsubscribe mechanism to confirm it functions correctly. |
| Tools | Test recipient accounts |
| Deliverable | Verified, ready-to-send campaign |
| Owner | Messaging specialist |
| Dependency | Task 6.1 |
| Frequency | Per campaign |
| KPI | Zero formatting/link errors in the test send |
| Quality check | Test reviewed on an actual mobile device for SMS/WhatsApp/email |
| Common mistake | Sending to the full list without a test send first, only discovering a broken personalization field ("Hi {{first_name}}") after it's already gone to every recipient |
| Estimated complexity | Low |

### 8. Launch

**Task: Send the campaign or activate the automated sequence**
| Field | Detail |
|---|---|
| Purpose | Executes the verified campaign to the real audience |
| Inputs | Verified campaign |
| Procedure | 1) Send the campaign to the intended segment at the scheduled time. 2) For automated sequences, formally activate and confirm it's live. |
| Tools | Email/SMS/WhatsApp platform |
| Deliverable | Sent campaign or activated sequence |
| Owner | Messaging specialist |
| Dependency | Task 7.1 |
| Frequency | Per campaign |
| KPI | Sent to the correct, intended segment only |
| Quality check | Recipient list double-checked against the intended segment before sending, given how difficult a mass-send is to undo |
| Common mistake | Sending to the entire contact list instead of the intended segment due to a list-selection error |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Monitor delivery, open/click rates, and unsubscribe/block signals**
| Field | Detail |
|---|---|
| Purpose | Confirms the campaign is actually reaching and engaging recipients, and catches an early sign of over-messaging before it escalates |
| Inputs | Sent campaign data |
| Procedure | 1) Review delivery, open, and click rates per channel. 2) Watch unsubscribe and, on WhatsApp specifically, block/report rates closely — these are early warning signs of frequency or relevance problems. |
| Tools | Platform analytics |
| Deliverable | Ongoing performance monitoring log |
| Owner | Messaging specialist |
| Dependency | Task 8.1 |
| Frequency | Within 24–48 hours of each send, and weekly overall |
| KPI | Unsubscribe/block rate tracked against a sensible threshold |
| Quality check | A rising unsubscribe/block trend investigated immediately, not allowed to continue unaddressed |
| Common mistake | Continuing a messaging cadence unchanged despite a clearly rising unsubscribe or block rate signaling recipient fatigue |
| Estimated complexity | Low |

### 10. Optimization

**Task: Refine timing, frequency, and content based on evidence**
| Field | Detail |
|---|---|
| Purpose | Keeps the program improving and prevents recipient fatigue from an unchanging approach |
| Inputs | Monitoring log |
| Procedure | 1) Adjust send timing or frequency where data suggests a problem. 2) Test subject line or message-opening variants where volume supports it. 3) Prune consistently bounced or unengaged contacts from active lists. |
| Tools | Platform analytics, CRM |
| Deliverable | Refined campaign approach and cleaner contact list |
| Owner | Messaging specialist |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| KPI | At least one evidence-based refinement per month where warranted |
| Quality check | Refinement tied to a specific, observed metric |
| Common mistake | Continuing to message a long-unengaged or repeatedly bounced contact indefinitely instead of pruning the list, which drags down deliverability metrics for everyone |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly messaging performance report**
| Field | Detail |
|---|---|
| Purpose | Connects messaging activity to real outcomes, honestly including any warning signs |
| Inputs | Monitoring log |
| Procedure | 1) Summarize campaigns sent, delivery/open/click rates, and unsubscribe/block rates per channel. 2) Summarize any resulting revenue/bookings where trackable. |
| Tools | Report template |
| Deliverable | Monthly messaging performance report |
| Owner | Messaging specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly |
| QA | Report includes unsubscribe/block trends honestly, not just positive engagement metrics |
| Quality check | Figures cross-checked against the platform's own reporting directly |
| Common mistake | Reporting only open/click rates while omitting a concerning unsubscribe or block trend that the client needs to know about |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Maintain list hygiene and consent records**
| Field | Detail |
|---|---|
| Purpose | An unmaintained list accumulates bounced addresses, unengaged contacts, and stale consent records that hurt deliverability and compliance over time |
| Inputs | Ongoing campaign data |
| Procedure | 1) Regularly remove hard-bounced addresses and confirmed unsubscribes/opt-outs from active sending lists. 2) Keep consent records current and easily auditable. 3) Stay current on WhatsApp Business policy and general anti-spam requirements relevant to the client's jurisdiction. |
| Tools | CRM, platform list-management tools |
| Deliverable | A clean, compliant, currently maintained contact list |
| Owner | Messaging specialist |
| Dependency | Ongoing |
| Frequency | Monthly |
| KPI | Zero hard-bounced addresses still actively targeted |
| Quality check | Consent records spot-checked for completeness and accuracy |
| Common mistake | Letting a growing number of bounced or disengaged contacts remain in active campaigns, quietly damaging overall deliverability for the whole list |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Consent-audited contact list
- Segmented audience with channel-preference notes
- Documented campaign types, cadence, and consent process per channel
- Connected platforms with working segmentation and opt-out handling
- First campaign(s) sent and/or automated sequences activated

**Monthly deliverables**
- Campaigns sent per the agreed cadence
- Monthly messaging performance report
- List hygiene and consent-record maintenance

**Optional add-ons**
- WhatsApp Business API integration for higher-volume, more automated messaging needs
- Advanced segmentation/personalization at scale
- Dedicated nurture-sequence development for longer B2B sales cycles

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Every contact's consent status documented before messaging | Leading | Directly attributable |
| Delivery rate | Leading | Directly attributable to list hygiene and platform health |
| Open/click rate | Lagging | Influenced by subject line/content quality and list relevance |
| Unsubscribe/block rate | Lagging | An early warning signal — rising trend should trigger investigation, not just be tracked passively |
| Revenue/bookings attributable to a campaign | Lagging | Attribution depends on the tracking quality in 24; report honestly where attribution is uncertain |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | WhatsApp Business app (for lower-volume needs), free-tier email marketing platforms | Sufficient for many single-location SME clients |
| Low-cost | Paid-tier email platforms, SMS gateway services, entry-tier CRM messaging features | Useful once list size or automation needs exceed free-tier limits |
| Professional | WhatsApp Business API with a business solution provider, enterprise marketing-automation platforms | Justified for higher-volume, multi-segment, or highly automated messaging programs |
| Low-bandwidth / mobile-first consideration | Concise, mobile-optimized email design and WhatsApp-first strategy for segments most comfortable with that channel | Reflects the primary way most Ethiopian customers will actually receive and read these messages |

## H. Risks and Common Failure Modes

- **Technical risk:** a broken personalization field or link going out to the full list without a test send catching it first.
- **Platform risk:** WhatsApp Business policy, email deliverability standards, and SMS regulations change over time — verify current requirements periodically.
- **Client-related risk:** a client wanting to message an unconsented list "just this once," which must be firmly declined.
- **Data and access risk:** an opt-out on one channel not propagating to the CRM, causing continued unwanted contact on another channel.
- **Reputation risk:** over-messaging, especially on WhatsApp, risking the business number being blocked or restricted, which can be difficult to recover from.
- **Security risk:** contact data should be access-controlled per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md).
- **Legal or compliance risk:** consent, data-handling, and marketing-communication rules apply to every channel here — verify against [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md), especially for ⚠️-flagged sectors.
- **Measurement and attribution risk:** revenue attributed to a messaging campaign should be treated with the same attribution caution as other channels — a purchase following a message isn't automatically fully caused by it.

## I. Standard Operating Procedure

- [ ] Existing contact list audited and classified by real consent status before any campaign
- [ ] Audience segmented with channel-preference notes
- [ ] Campaign types, cadence, and per-channel consent/opt-out process documented
- [ ] Platforms connected with working segmentation and CRM-synced opt-out handling, tested end to end
- [ ] Campaign content written specifically for each channel's format and tone, not copy-pasted across channels
- [ ] Automated sequences built and their trigger conditions tested with a real action
- [ ] Test send completed and reviewed before every full send
- [ ] Recipient segment double-checked before sending
- [ ] Delivery, open/click, and unsubscribe/block rates monitored within 48 hours of each send
- [ ] Rising unsubscribe/block trends investigated immediately
- [ ] Timing, frequency, and content refined monthly based on evidence
- [ ] Monthly report includes unsubscribe/block trends honestly alongside positive metrics
- [ ] List hygiene and consent records maintained monthly; bounced/disengaged contacts pruned
