# Service: Additional Services

## About This File

[02_SERVICE_CATALOGUE.md](../02_SERVICE_CATALOGUE.md) Section G lists ten emerging/secondary service ideas that don't yet have their own numbered file. This file writes each one up with the same A–I structure as the numbered services, so none of them get sold on a handshake — but at a **condensed depth** rather than the full 12-phase task breakdown used in services 01–25.

**Why condensed, not full depth:** these are lower-priority, validated-on-demand services (see [../01_AGENCY_STRATEGY_AND_POSITIONING.md](../01_AGENCY_STRATEGY_AND_POSITIONING.md) §10 — smaller, credible additions rather than the agency's core offer). Writing all ten at the same exhaustive length as, say, [10_GOOGLE_BUSINESS_PROFILE.md](10_GOOGLE_BUSINESS_PROFILE.md) would make this the largest file in the system for the services least likely to be sold in the first year. Each item below still has a full Definition, Outcomes, Inputs, a lifecycle task table (Preparation through Maintenance collapsed into fewer, still-specific tasks), Deliverables, KPIs, Tools, Risks, and an SOP checklist — nothing here is vague or unusable, it's simply scoped to match the item's actual current priority.

**When to expand an item to full depth:** once a specific item here proves to have real, repeatable client demand, promote it to its own numbered `services/` file with the full 12-phase structure, and update [02_SERVICE_CATALOGUE.md](../02_SERVICE_CATALOGUE.md) accordingly.

---

## 1. WhatsApp Business API / Chatbot Setup

### A. Service Definition
**What it is:** Setup of the WhatsApp Business API (beyond the free WhatsApp Business app covered in [12_SOCIAL_MEDIA_ACCOUNT_SETUP.md](12_SOCIAL_MEDIA_ACCOUNT_SETUP.md)) — product catalog, automated quick replies, and basic chatbot flows for common questions and order-taking. **Why it matters:** WhatsApp is a primary inquiry and ordering channel for many Ethiopian SMEs; the free app hits volume and automation limits quickly once a business gets busy. **Who benefits:** higher-volume retail, food/delivery, and service businesses already getting substantial WhatsApp inquiry volume through 20/22. **Not included:** general WhatsApp marketing campaigns (22), the basic WhatsApp Business app setup itself (12). **Connects to:** 20 (lead capture), 22 (messaging), 23 (CRM routing).

### B. Outcomes
| Level | Example |
|---|---|
| Output | Configured API access, product catalog, automated quick-reply/chatbot flows |
| Outcome | Faster response to routine inquiries, orders captured without a staff member manually typing every reply |
| Financial impact | Reduced staff time per inquiry; fewer missed messages during high-volume periods |

### C. Inputs Required From the Client
- Existing WhatsApp Business account and phone number (from 12) — the API requires giving up the free app on that number, which must be explained clearly
- Product/service catalog details
- Common customer questions and desired automated answers
- A business solution provider relationship (required to access the official API)

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Assess genuine need for the API vs. the free app | Prevents an unnecessary, more complex migration for a business the free app already serves fine | Review actual WhatsApp inquiry volume and current pain points against API benefits and costs | Documented go/no-go recommendation | One-time | Recommendation grounded in real volume data, not assumption |
| Select a business solution provider and migrate the number | The API requires an approved provider relationship | Compare provider options against cost/features; execute the migration from the free app | Active API access under the client's account | One-time | Migration completed with zero message-history loss where avoidable |
| Build the product catalog | Lets customers browse and order directly in-chat | Enter products/services with accurate names, prices, and images | Live, accurate WhatsApp catalog | One-time, updated as offerings change | Catalog matches current real pricing |
| Build automated quick-reply/chatbot flows | Handles routine questions without staff typing the same answer repeatedly | Script flows for the most common questions (hours, location, pricing, order status); always include an easy path to a real human | Working automated flows | One-time, refined ongoing | Chatbot correctly resolves routine queries; always offers human handoff |
| Test and launch | Confirms the flows work correctly before customers rely on them | Run real test conversations through every flow path | Verified, live system | One-time | Zero broken flow paths at launch |
| Monitor and maintain | Catches a broken flow or an outdated catalog entry | Periodically test flows and review catalog accuracy | Ongoing health log | Monthly | No stale catalog entries found at review |

### E. Deliverables
Initial: API access, product catalog, chatbot flows, tested and live. Monthly: health monitoring, catalog updates as needed.

### F. KPIs
Response time to routine inquiries; catalog accuracy; successful human-handoff rate when a chatbot can't resolve a query (never let a customer get stuck in an automated loop).

### G. Tools
A WhatsApp Business Solution Provider (required for API access); free WhatsApp Business app remains the right tool below the volume threshold that justifies this service.

### H. Risks and Common Failure Modes
Migrating to the API when the free app would have sufficed, adding cost and complexity without real benefit. A chatbot flow with no human-handoff path frustrating customers. Catalog prices going stale after a business update. ⚠️ WhatsApp Business API policies and provider terms change — verify current requirements before recommending.

### I. SOP
- [ ] Genuine need assessed against real inquiry volume before recommending
- [ ] Provider selected, migration executed without avoidable message-history loss
- [ ] Catalog built and kept accurate
- [ ] Every automated flow has a clear human-handoff path
- [ ] Flows tested end to end before launch; monitored monthly thereafter

---

## 2. E-Commerce Enablement

### A. Service Definition
**What it is:** Building online ordering/purchasing capability — product catalog, cart, checkout, payment integration, and order/delivery management — distinct from a general marketing website. **Why it matters:** retail, food, and product-based segments increasingly need to sell online, not just be found online. **Who benefits:** retail, food/beverage, and product-based businesses ready to accept online orders/payment, per [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md). **Not included:** the general marketing website ([03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) builds the base site this extends), ongoing content/social selling (13/15). **Connects to:** 03 (technical foundation), 20 (order capture/routing), 23 (customer/order data).

### B. Outcomes
| Level | Example |
|---|---|
| Output | A working online store: catalog, cart, checkout, payment integration, order management |
| Outcome | Customers can complete a purchase online without a manual back-and-forth |
| Financial impact | New sales channel; reduced staff time per order; captured orders outside business hours |

### C. Inputs Required From the Client
- Full product catalog with accurate pricing and inventory
- A confirmed, currently available local payment gateway option
- Delivery/fulfillment process the store needs to reflect
- Return/refund policy

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Confirm payment and fulfillment feasibility | Prevents building a store around a payment or delivery method that isn't actually workable | Verify current payment-gateway availability and confirm the client's real fulfillment capacity | Confirmed technical/operational plan | One-time | Plan checked against currently available options, not assumed |
| Build the product catalog and store structure | Produces the actual browsable, purchasable store | Enter products, categories, images, pricing, and inventory levels | Live product catalog | One-time, updated ongoing | Catalog matches real current stock and pricing |
| Integrate payment and order management | Makes checkout actually work and orders trackable | Configure the payment gateway; connect order data to 20/23 | Working checkout and order routing | One-time | Test purchase completes successfully end to end |
| Test the full purchase flow | Confirms a real customer can complete a purchase without friction | Run multiple real test purchases across devices | Verified, working store | One-time | Zero broken steps in the test purchase flow |
| Launch and monitor | Activates the store and catches early issues | Go live; monitor first orders closely | Live store with early monitoring | One-time then ongoing | Zero unresolved order-processing errors in the first weeks |
| Maintain inventory and payment health | Keeps the store trustworthy over time | Periodically verify inventory accuracy and payment-gateway health | Ongoing accurate, working store | Monthly | No stale inventory or payment failures found at review |

### E. Deliverables
Initial: live store with tested purchase flow. Monthly: inventory accuracy checks, payment-health monitoring, order-volume reporting.

### F. KPIs
Cart abandonment rate; checkout completion rate; order-processing error rate; average order value.

### G. Tools
E-commerce plugins/platforms compatible with the client's CMS; a currently available, locally viable payment gateway — confirm this before quoting the project, since availability changes.

### H. Risks and Common Failure Modes
Promising a payment or delivery integration that turns out to be unavailable or unreliable after the project has started. Stale inventory causing a customer to order something out of stock. ⚠️ Payment processing carries real financial-compliance considerations — verify current requirements before launch.

### I. SOP
- [ ] Payment and fulfillment feasibility confirmed before committing scope
- [ ] Catalog built accurately and kept current
- [ ] Checkout and order routing tested end to end
- [ ] Full purchase flow tested across real devices before launch
- [ ] Inventory and payment health monitored monthly

---

## 3. Marketplace and Delivery-Platform Listing Management

### A. Service Definition
**What it is:** Setting up and optimizing a business's presence on third-party marketplace, classifieds, or delivery/ordering platforms distinct from the business's own website or Google Business Profile. **Why it matters:** many customers discover and order directly through these platforms without ever visiting the business's own site. **Who benefits:** food-delivery-eligible restaurants, retail sellers active on marketplace platforms. **Not included:** the business's own GBP (10) or website store (Item 2 above). **Connects to:** 16 (photos for listings), 24 (reporting on this channel's contribution).

### B. Outcomes
| Level | Example |
|---|---|
| Output | Complete, accurate, optimized listings on relevant third-party platforms |
| Outcome | Increased discoverability and orders through channels the business doesn't own |
| Financial impact | Incremental revenue from a channel outside the business's own website/social presence |

### C. Inputs Required From the Client
- Which third-party platforms are relevant and already in use, if any
- Product/menu/service details and pricing
- Photos (from 16)
- Awareness of each platform's commission structure

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Audit current listings | Establishes what exists and its accuracy | Search for and review any existing listing on relevant platforms | Listing audit | One-time | All findable listings documented |
| Claim/create and complete listings | Establishes accurate, complete presence | Claim or create listings; complete every available field with accurate, consistent information | Complete listings | One-time per platform | 100% of relevant fields completed accurately |
| Optimize with photos and descriptions | Improves conversion within the platform | Upload strong photos from 16; write clear, accurate descriptions | Optimized listings | One-time, refreshed periodically | Listings visually competitive with category leaders |
| Monitor and respond to platform-specific reviews/ratings | Some platforms carry their own review system separate from Google | Monitor and respond per the principles in [11_REVIEW_AND_REPUTATION_MANAGEMENT.md](11_REVIEW_AND_REPUTATION_MANAGEMENT.md) | Managed platform reputation | Ongoing | Response-time target met |
| Reconcile pricing/menu consistency | Prevents customer confusion from mismatched pricing across channels | Cross-check platform pricing against the business's actual current pricing | Consistent pricing across channels | Monthly | Zero pricing discrepancies found |

### E. Deliverables
Initial: complete, optimized listings. Monthly: pricing/menu consistency check, review monitoring.

### F. KPIs
Listing completeness; orders/inquiries attributable to the platform (where the platform provides this data); review rating trend on the platform.

### G. Tools
Each platform's own merchant/partner dashboard — no separate agency tool typically required.

### H. Risks and Common Failure Modes
Pricing drifting out of sync between the platform and the business's own channels. Commission structures eating into margin in ways the client didn't fully budget for — make sure this is understood before recommending the channel. Platform-specific policy compliance requirements changing over time.

### I. SOP
- [ ] Existing listings audited before creating new ones
- [ ] Listings completed accurately on every relevant platform
- [ ] Photos and descriptions optimized
- [ ] Platform reviews monitored and responded to
- [ ] Pricing/menu consistency checked monthly

---

## 4. Translation and Localization

### A. Service Definition
**What it is:** Professional translation and cultural localization of website, social, and marketing content across Amharic, English, and other locally relevant languages — distinct from the basic bilingual consistency check already embedded in [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md)'s style guide. **Why it matters:** in a genuinely multilingual market, a business serving multiple language communities needs content that reads naturally in each, not machine-translated or awkwardly adapted. **Who benefits:** any business needing formal, larger-scale multi-language content beyond what copywriting's own bilingual style guide covers — tourism, hospitality, exporters, diaspora-facing businesses. **Not included:** the base content-writing work itself (04/15 write the source content; this service translates and localizes it). **Connects to:** 04, 14/15.

### B. Outcomes
| Level | Example |
|---|---|
| Output | Professionally translated, culturally localized content across required languages |
| Outcome | Content that reads naturally and persuasively to each language audience, not just literally translated |
| Financial impact | Access to a broader customer base without a credibility-damaging translation quality gap |

### C. Inputs Required From the Client
- Source content requiring translation
- Confirmed target languages
- Any existing glossary of preferred terms (especially technical/industry terms)

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Build/confirm a glossary of key terms | Ensures consistent translation of business-critical terms | Identify recurring key terms and confirm the preferred translation for each | Approved glossary | One-time, updated as needed | Glossary covers all recurring business-critical terms |
| Translate content with a qualified native translator | Produces natural, accurate translated content — never relying on machine translation alone for client-facing material | Assign to a qualified native-language translator/editor; translate against the glossary | Translated content | Per content batch | Zero unnatural or awkward machine-translation artifacts |
| Localize (not just translate) culturally sensitive content | Literal translation can miss cultural context, idiom, or tone appropriateness | Review translated content specifically for cultural fit, not just linguistic accuracy | Culturally localized content | Per content batch | Reviewed by a native speaker familiar with the target audience |
| Quality-review against the source | Catches errors before publishing | A second reviewer checks the translation against source meaning and the glossary | Quality-reviewed content | Per content batch | Peer-reviewed before delivery |
| Deliver and coordinate implementation | Gets the finished translation into the right place | Hand off to whichever service (04/03/13/15) will implement it | Implemented multi-language content | Per content batch | Delivered in the format the receiving service needs |

### E. Deliverables
Per content batch: translated, localized, peer-reviewed content in the target language(s), ready for implementation.

### F. KPIs
Translation quality (peer-reviewed, glossary-consistent); turnaround time; zero client-reported translation errors post-publication.

### G. Tools
A qualified native-language translator/editor (not machine translation alone for client-facing content); a shared glossary document; translation-memory tools for consistency at scale if volume justifies it.

### H. Risks and Common Failure Modes
Relying on machine translation alone for client-facing content, producing an unnatural or embarrassing result. Inconsistent terminology across different content pieces without a maintained glossary. Cultural tone-deafness from literal translation without genuine localization review.

### I. SOP
- [ ] Glossary built and approved before large-scale translation begins
- [ ] Translation done by a qualified native speaker, not machine translation alone
- [ ] Content reviewed specifically for cultural localization, not just linguistic accuracy
- [ ] Peer-reviewed against source and glossary before delivery
- [ ] Delivered in the format the implementing service needs

---

## 5. Print and Offline Collateral Tied to Digital Campaigns

### A. Service Definition
**What it is:** Menus, table cards, flyers, signage, and other printed materials that carry QR codes, review links, or social handles — connecting offline foot traffic to digital assets. **Why it matters:** most Ethiopian SME customer interaction still happens significantly offline (in-store, in-person); print collateral is the bridge from that physical moment to a digital action (review, follow, revisit). **Who benefits:** any physical-location business, especially restaurants, retail, and service businesses with in-person customer moments. **Not included:** the digital assets/links themselves (10, 11, 12 create the actual QR/review links this collateral displays). **Connects to:** 11 (review QR codes), 12 (social handles), 25 (brand template).

### B. Outcomes
| Level | Example |
|---|---|
| Output | Printed materials incorporating working, on-brand digital touchpoints |
| Outcome | Offline foot traffic converted into digital follows, reviews, or repeat visits |
| Financial impact | Low-cost conversion of existing foot traffic into digital assets that compound over time |

### C. Inputs Required From the Client
- The specific digital links/QR codes to incorporate (from 10/11/12)
- Brand template from 25
- Print quantities, locations, and budget

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Confirm the specific digital destination per material | Ensures every printed piece drives to a working, purposeful link | Confirm and test each QR code/link before it goes to print | Verified digital destinations | Per print run | Every code tested working before print |
| Design on-brand collateral | Produces materials consistent with the established identity | Apply the brand template from 25 to each piece | Design-ready print files | Per print run | Consistent with the brand style guide |
| Coordinate print production | Gets physical materials produced to spec | Source a print vendor and confirm quality/specs before full-quantity printing | Printed materials | Per print run | Proof approved before full print run |
| Deploy and verify placement | Ensures materials are actually where they're supposed to be | Confirm physical placement in person, not just by instruction | Deployed collateral | Per print run | Placement confirmed in person |
| Monitor QR/link engagement | Confirms the print investment is actually driving digital action | Track scans/clicks where the platform provides this data | Engagement data | Ongoing | Engagement tracked, not assumed |

### E. Deliverables
Per print run: on-brand printed collateral with verified, working digital touchpoints, deployed and confirmed in place.

### F. KPIs
QR code/link scan rate where trackable; review or follow growth attributable to the campaign period.

### G. Tools
Design software (25's brand templates), a reliable local print vendor, a QR code generator/tracker.

### H. Risks and Common Failure Modes
Printing a QR code that was never actually tested, discovered broken only after a large print run is already produced. Materials printed but never actually placed or replaced once worn. Outdated pricing or offers left in circulation on old printed material.

### I. SOP
- [ ] Every digital destination tested working before print
- [ ] Design consistent with the brand style guide
- [ ] Print proof approved before full production run
- [ ] Placement confirmed in person after deployment
- [ ] QR/link engagement tracked where possible

---

## 6. Influencer and Creator Partnerships

### A. Service Definition
**What it is:** Sourcing, vetting, briefing, negotiating, and managing compliance for paid or gifted partnerships with social media influencers/creators — a distinct process from organic content (15) or paid advertising (17/19). **Why it matters:** an influencer's existing trusted audience can reach potential customers more credibly than brand-owned content alone. **Who benefits:** visually strong consumer segments with budget beyond the core packages — hospitality, beauty, fashion, food. **Not included:** the agency's own organic content production (15) or ad campaigns (17/19), though this service may hand off strong influencer content for paid amplification via those services. **Connects to:** 13 (coordinating publish timing), 15 (content style consistency), 17/19 (amplification).

### B. Outcomes
| Level | Example |
|---|---|
| Output | Vetted influencer partnerships, signed agreements, published sponsored content, disclosed per platform policy |
| Outcome | Credible third-party reach into an audience the business's own channels don't reach as effectively |
| Financial impact | Reach and conversions from an influencer's audience relative to the partnership cost |

### C. Inputs Required From the Client
- Budget and objective for the partnership program
- Brand guidelines and any messaging restrictions
- Target audience/persona to match influencer selection against

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Source and vet candidates | Finds influencers with a genuine, relevant, real (not bought) audience | Identify candidates matching the target persona; review for audience authenticity and past brand-safety issues | Vetted candidate shortlist | Per campaign | Candidates checked for authentic engagement, not just follower count |
| Negotiate terms and secure a written agreement | Protects both parties and clarifies deliverables | Agree deliverables, timeline, compensation, and usage rights in writing | Signed agreement | Per partnership | Written agreement in place before any content is produced |
| Brief the creator | Ensures the content stays on-brand while preserving the creator's authentic voice | Provide a clear brief covering key messages and required disclosures, without over-scripting | Creator brief | Per partnership | Brief balances brand needs with creator authenticity |
| Confirm proper sponsored-content disclosure | A legal and platform-policy requirement, not optional | Confirm the creator discloses the partnership per platform rules (e.g. paid partnership labels) | Compliant disclosure | Per post | 100% disclosure compliance |
| Track performance and manage the relationship | Measures the partnership's value and informs future decisions | Track reach/engagement where available; maintain the relationship for potential future collaboration | Performance summary | Per campaign | Performance reviewed against the original objective |

### E. Deliverables
Per campaign: vetted partnerships, signed agreements, published and properly disclosed sponsored content, a performance summary.

### F. KPIs
Reach/engagement from partnership content; follower/inquiry growth attributable to the campaign period; disclosure compliance rate (must be 100%).

### G. Tools
Manual vetting and outreach; a written agreement template; platform-native disclosure tools (e.g. Meta's branded content tag).

### H. Risks and Common Failure Modes
Partnering with an influencer whose audience is largely inauthentic (bought followers/engagement). No written agreement, leading to a dispute over deliverables or usage rights. Missing required sponsored-content disclosure, which is both a platform-policy and, in some jurisdictions, a legal requirement. ⚠️ Verify current disclosure requirements — platform and regulatory rules evolve.

### I. SOP
- [ ] Candidates vetted for authentic audience engagement, not follower count alone
- [ ] Written agreement in place before content production begins
- [ ] Creator briefed with a balance of brand needs and authentic voice
- [ ] Sponsored-content disclosure confirmed compliant on every post
- [ ] Performance tracked and reviewed against the original objective

---

## 7. Crisis Communication and Reputation-Incident Response

### A. Service Definition
**What it is:** A defined escalation and response process for reputation emergencies — a health/safety incident, a viral complaint, a public relations crisis — that goes beyond [11_REVIEW_AND_REPUTATION_MANAGEMENT.md](11_REVIEW_AND_REPUTATION_MANAGEMENT.md)'s routine review-response process. **Why it matters:** a mishandled crisis moment can cause damage far beyond what routine reputation management addresses; having a plan ready before a crisis happens is the difference between a controlled response and a panicked one. **Who benefits:** any business, but especially those with higher public visibility or safety-sensitive operations (food service, healthcare, hospitality). **Not included:** routine review response (11 handles day-to-day reputation management; this activates only for genuine crisis-level incidents). **Connects to:** 11, 13 (social response), operations/15 (legal/compliance coordination).

### B. Outcomes
| Level | Example |
|---|---|
| Output | A documented crisis-response plan, ready to activate; managed response during an actual incident |
| Outcome | A controlled, appropriate, timely response that limits reputational damage during a genuine crisis |
| Financial impact | Avoided compounding damage (lost customers, prolonged negative press) from a mishandled response |

### C. Inputs Required From the Client
- Internal escalation contact(s) and their availability
- Any past incidents worth learning from
- Legal/compliance contact for guidance during a real incident

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Define what qualifies as a crisis | Distinguishes a genuine crisis from a routine negative review already handled under 11 | Set clear criteria (e.g. safety incident, viral spread, media inquiry) | Documented crisis criteria | One-time, revisited annually | Criteria clear enough to avoid both over- and under-escalation |
| Build the response protocol | Provides a ready-to-use plan rather than improvising under pressure | Define the escalation chain, response-time targets, and approval process for public statements | Documented response protocol | One-time, revisited annually | Protocol includes a clear approval chain for public statements |
| Prepare holding-statement templates | Enables a fast, appropriate initial response while facts are still being gathered | Draft general holding-statement templates adaptable to different incident types | Template set | One-time, revisited annually | Templates avoid admitting fault or making promises before facts are confirmed |
| Activate the protocol during an actual incident | Executes the plan when genuinely needed | Follow the defined escalation chain; coordinate the response across affected channels (11, 13) | Managed incident response | As needed | Response initiated within the defined time target |
| Conduct a post-incident review | Captures lessons for the next time | Review what happened and how the response performed; update the protocol if needed | Post-incident review notes | After each activation | Protocol updated based on real lessons learned |

### E. Deliverables
Initial: documented crisis criteria, response protocol, and holding-statement templates. As-needed: managed incident response and post-incident review.

### F. KPIs
Time to initial response during an actual incident; protocol activation appropriateness (correctly distinguishing a real crisis from a routine issue); post-incident review completion.

### G. Tools
A documented protocol (shared document); the same channels used in 11/13 for actual response execution.

### H. Risks and Common Failure Modes
No plan existing before a real crisis hits, forcing an improvised and often poorly judged response. Escalating a routine negative review as a "crisis" and overreacting. A public statement made without legal/compliance input on a sensitive matter. This service's value is almost entirely in preparation — an unused, ready plan is a success, not a wasted cost.

### I. SOP
- [ ] Crisis criteria clearly defined and distinct from routine review-response scope
- [ ] Response protocol documented with a clear escalation and approval chain
- [ ] Holding-statement templates prepared in advance
- [ ] Protocol actually activated and followed during any genuine incident
- [ ] Post-incident review conducted and protocol updated with real lessons

---

## 8. Employer Branding and Recruitment Marketing

### A. Service Definition
**What it is:** Applying the same digital-marketing skillset (content, social, targeted advertising) to attracting job candidates rather than customers — for clients who need to market to a labor market, not just a customer market. **Why it matters:** the same tools (LinkedIn presence, targeted content, employer-brand storytelling) that attract customers can attract better job applicants, an adjacent but distinct use case. **Who benefits:** growing businesses with active hiring needs, particularly in competitive-talent sectors (tech, healthcare, hospitality management). **Not included:** the recruitment/hiring process itself (this markets the opportunity; it doesn't screen or hire candidates), the business's core customer-facing marketing (12–19, which remain distinct and separately scoped). **Connects to:** 12/13 (LinkedIn presence), 15 (employer-brand content), 25 (consistent brand identity applied to a talent audience).

### B. Outcomes
| Level | Example |
|---|---|
| Output | Employer-brand content, targeted recruitment posts/campaigns, a consistent careers presence |
| Outcome | A stronger, more visible employer brand attracting more and better-fit job applicants |
| Financial impact | Reduced cost and time to fill open roles; improved candidate quality |

### C. Inputs Required From the Client
- Current hiring needs and the roles being recruited for
- What makes the business a good place to work (for authentic content, not generic claims)
- A careers page or application process to direct candidates to

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Confirm hiring needs and target candidate profile | Focuses the effort on real, current roles | Identify current/upcoming roles and the profile of candidate needed | Documented hiring needs | Per hiring cycle | Needs confirmed directly with the client's hiring manager |
| Develop authentic employer-brand content | Builds genuine candidate interest, not generic recruitment-ad language | Produce content showcasing real team, culture, and work (coordinate with 15/16) | Employer-brand content | Per hiring cycle | Content reflects real, specific aspects of the workplace, not generic claims |
| Set up/optimize a LinkedIn or careers presence | Provides a credible destination for interested candidates | Configure or refine the relevant presence, consistent with 12's account-setup discipline | Live, complete careers presence | One-time, updated per hiring cycle | Presence complete and consistent with brand identity |
| Run targeted recruitment content/ads | Reaches candidates who fit the target profile | Publish organic content and, if in scope, run targeted ads aimed at the candidate profile | Published recruitment content/campaigns | Per hiring cycle | Reach/engagement among the target candidate profile |
| Track applicant quality and source | Confirms which efforts are producing genuinely good candidates | Track application volume and quality by source, coordinating with the client's hiring process | Source-tracked applicant data | Per hiring cycle | Source-of-hire data captured and reviewed |

### E. Deliverables
Per hiring cycle: employer-brand content, a live careers presence, recruitment content/campaigns, and source-tracked applicant data.

### F. KPIs
Applications received; applicant quality/fit as assessed by the client; cost and time to fill a role; source-of-hire breakdown.

### G. Tools
LinkedIn (primary platform for most professional-role recruitment), the same content-production tools used elsewhere (15/16), targeted advertising tools (17/18) if paid recruitment campaigns are in scope.

### H. Risks and Common Failure Modes
Generic, inauthentic "great place to work" messaging that doesn't reflect the real workplace, damaging credibility with candidates who later discover the gap. Recruiting for a role that gets filled or cancelled mid-campaign without pausing the campaign. Mixing customer-facing and candidate-facing messaging in a way that confuses either audience.

### I. SOP
- [ ] Hiring needs confirmed directly with the hiring manager before starting
- [ ] Employer-brand content grounded in real, specific workplace detail
- [ ] Careers/LinkedIn presence complete and brand-consistent
- [ ] Recruitment content/campaigns targeted at the actual candidate profile
- [ ] Applicant source and quality tracked and reviewed each hiring cycle

---

## 9. Digital-Skills Training for Client Staff

### A. Service Definition
**What it is:** Structured training for a client's own staff to handle basic ongoing digital tasks themselves (posting to social media, responding to reviews, updating a website page) rather than fully outsourcing every task to the agency. **Why it matters:** some clients want partial independence, either for cost reasons or because certain tasks (like immediate customer replies) are better handled in-house; training done well builds a longer-term, trust-based relationship rather than losing the client entirely to full self-sufficiency. **Who benefits:** clients wanting to bring specific tasks in-house while retaining the agency for strategy and higher-skill work. **Not included:** ongoing execution of the tasks being trained (that becomes the client's own responsibility post-training). **Connects to:** touches nearly every service as the subject matter of what's being taught.

### B. Outcomes
| Level | Example |
|---|---|
| Output | Trained staff able to competently perform specific, defined digital tasks |
| Outcome | The client's team can handle certain ongoing tasks confidently and correctly, freeing agency capacity for higher-value work |
| Financial impact | A revenue stream from training itself, plus a stronger long-term relationship that reduces full-churn risk when a client wants more independence |

### C. Inputs Required From the Client
- Which specific tasks the client wants their staff trained on
- Staff availability for training sessions
- Staff technical comfort level, to pitch training appropriately

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Scope the specific tasks to train | Prevents an unfocused, overly broad training engagement | Confirm exactly which tasks the client wants their team to handle independently | Documented training scope | Per engagement | Scope specific and limited, not "teach us everything" |
| Develop training materials | Provides a lasting reference beyond the live session | Build clear, task-specific guides/checklists matched to the client's actual tools and accounts | Training materials | Per engagement | Materials specific to the client's actual setup, not generic |
| Deliver the training session(s) | Transfers the actual skill | Run hands-on training with real practice on the client's real accounts | Completed training session(s) | Per engagement | Staff complete a real task successfully during the session |
| Confirm competency before handoff | Ensures the task is actually being handed off successfully, not prematurely | Observe or review the staff member completing the task independently before fully stepping back | Confirmed competency | Per engagement | Task completed correctly without agency assistance |
| Provide a support window after handoff | Catches early mistakes before they become habits | Offer a defined period of light support/check-ins after training | Post-training support | Per engagement (defined period) | Issues caught and corrected within the support window |

### E. Deliverables
Per engagement: task-specific training materials, delivered training session(s), confirmed staff competency, a defined post-training support window.

### F. KPIs
Staff competency confirmed (task completed correctly and independently); client satisfaction with the training; task quality maintained after handoff (spot-checked during the support window).

### G. Tools
The client's own actual accounts/tools (never a generic demo environment); simple written guides/checklists.

### H. Risks and Common Failure Modes
Training that's too generic to be immediately useful on the client's actual accounts. Handing a task off before staff have genuinely demonstrated competency, leading to quality problems the agency then gets blamed for. No support window after training, leaving staff to struggle alone with early mistakes.

### I. SOP
- [ ] Training scope specific and confirmed with the client, not open-ended
- [ ] Materials built around the client's actual accounts and tools
- [ ] Training delivered hands-on with real practice, not a passive presentation
- [ ] Staff competency confirmed before considering the handoff complete
- [ ] Post-training support window provided and issues addressed promptly

---

## 10. Voice Search and Structured-Data Readiness

### A. Service Definition
**What it is:** An emerging extension of [06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md)/[09_LOCAL_SEO.md](09_LOCAL_SEO.md), preparing a site's structured data and content format for voice-assistant search patterns (conversational, question-based queries) as adoption grows. **Why it matters:** voice search usage is an evolving pattern worth tracking, though its current practical impact for a given SME should be assessed honestly rather than assumed. **Who benefits:** currently a lower-priority, forward-looking add-on rather than a standalone core offer — bundle it into the FAQ/schema work already done in 06/09 rather than selling it as a separate major engagement. **Not included:** the base technical/local SEO work itself (06/09 do the core work this extends). **Connects to:** 06, 07, 09.

### B. Outcomes
| Level | Example |
|---|---|
| Output | FAQ-style content and structured data formatted for conversational query matching |
| Outcome | Better readiness for voice-search-driven discovery as/if it becomes more relevant to the client's audience |
| Financial impact | Currently modest and hard to isolate — position honestly as a forward-looking readiness measure, not a guaranteed traffic driver |

### C. Inputs Required From the Client
- Existing FAQ content (from 04/09)
- Confirmation this is being added onto existing technical/local SEO work, not sold as a standalone major project

### D. Task Breakdown
| Task | Purpose | Procedure | Deliverable | Frequency | KPI |
|---|---|---|---|---|---|
| Assess realistic relevance for this client | Avoids overselling an emerging, hard-to-measure tactic | Honestly assess whether this client's audience and query types make voice-readiness meaningfully relevant right now | Documented relevance assessment | One-time | Assessment stated honestly, including if relevance is currently low |
| Expand FAQ content into conversational, question-based format | Matches how voice queries are typically phrased | Write/expand FAQ answers as natural, direct answers to full conversational questions | Conversational FAQ content | One-time, revisited with regular FAQ updates | Content phrased as natural question-and-answer, not keyword fragments |
| Ensure structured data supports FAQ/Q&A formats | Gives search engines a structured way to surface this content | Verify/add FAQ-type structured data alongside the LocalBusiness schema already in 09 | Validated structured data | One-time, part of 06's regular audit | Passes structured-data validation alongside existing schema |
| Monitor for any measurable change | Confirms whether this is producing any detectable effect | Watch for any relevant Search Console signal, with appropriately cautious interpretation | Monitoring notes | Quarterly, alongside 06's cadence | Findings reported with honest uncertainty, not overstated |

### E. Deliverables
One-time: relevance assessment, conversational FAQ content, validated structured data. Quarterly: folded into 06's regular technical SEO monitoring.

### F. KPIs
FAQ content coverage of common conversational queries; structured-data validation status. Direct voice-search traffic is not reliably isolatable in most current analytics setups — do not promise a specific measurable outcome here.

### G. Tools
The same tools as 06/09 (Schema.org markup, Google's Rich Results Test) — no separate dedicated tool needed.

### H. Risks and Common Failure Modes
Overselling this as a distinct, high-value service when its current measurable impact for most SME clients is genuinely uncertain — the honest, correct approach is to fold it into existing FAQ/schema work at low incremental cost, not sell it as a major standalone project. Presenting any traffic change as attributable to voice-search readiness specifically, when it can't be reliably isolated from the rest of the site's SEO work.

### I. SOP
- [ ] Relevance honestly assessed for this specific client before doing any work
- [ ] FAQ content expanded into natural conversational format
- [ ] Structured data validated alongside existing schema work
- [ ] Positioned to the client as a low-cost readiness measure, never a guaranteed traffic driver
- [ ] Folded into 06's regular quarterly monitoring rather than tracked as a separate program

---

## Standard Operating Procedure — Maintaining This File

- [ ] Do not sell any item above until its section here is complete — this file exists specifically so nothing gets sold on a handshake.
- [ ] When an item proves to have real, repeatable demand, promote it to its own full-depth `services/` file and remove it from this catalogue, updating [02_SERVICE_CATALOGUE.md](../02_SERVICE_CATALOGUE.md).
- [ ] When a genuinely new service idea emerges that doesn't fit an existing numbered service, add it here first, at this same condensed depth, before ever selling it.
- [ ] Keep the "why condensed" framing in the About section honest — if this file starts being sold from heavily, that itself is the signal to promote items to full depth.
