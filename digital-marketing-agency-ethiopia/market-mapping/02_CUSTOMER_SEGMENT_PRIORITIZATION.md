# Customer Segment Prioritization Model

## Purpose

[01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md](01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md) lists nearly every business type that could theoretically buy a service. A new agency cannot sell to all of them at once — it has limited staff, cash, reputation, and case studies. This file provides a scoring model to decide which segments to pursue first (Tier A), which to pursue selectively (Tier B), and which to deprioritize for now (Tier C).

This is a decision-support tool, not a market-research report. The scores in Part 3 are illustrative first-pass estimates based on generally observed patterns for these business types — **they are judgment calls to be recalibrated with real field research, sales-call outcomes, and this agency's own delivery experience**, not fixed facts. Re-score a segment whenever real evidence contradicts the initial estimate.

Related files: [04_BUYER_PERSONAS.md](04_BUYER_PERSONAS.md) and [05_CUSTOMER_PAIN_POINTS.md](05_CUSTOMER_PAIN_POINTS.md) carry the deeper per-segment detail (typical customer, decision-maker, objections, sales angle) that sits alongside this prioritization; [06_SERVICE_TO_SEGMENT_MATCHING.md](06_SERVICE_TO_SEGMENT_MATCHING.md) turns a prioritized segment into a specific service recommendation.

---

## Part 1 — Scoring Factors (score every segment 1–5 on each)

For each factor, 1 = weakest/lowest, 5 = strongest/highest, using the anchors below for consistency across whoever does the scoring.

| Factor | 1 (low) | 5 (high) |
|---|---|---|
| Dependence on local discovery | Customers rarely search or ask around locally to find this business (e.g. pre-arranged B2B supply contracts) | Customers routinely search "near me" or ask locally before choosing (e.g. restaurants, salons) |
| Dependence on Google Maps | Location/proximity is irrelevant to the purchase decision | Physical proximity strongly drives the choice of provider |
| Dependence on customer reviews | Reviews have little influence (e.g. sole regional supplier, contract-based B2B) | Reviews are a primary trust signal before purchase (e.g. clinics, hotels, restaurants) |
| Search demand | Almost nobody actively searches for this type of business online | High, consistent search volume for this type of business/service |
| Lead value | A single new customer/deal is worth very little | A single new customer/deal is worth a great deal to the business |
| Customer lifetime value | Customers are typically one-time or very infrequent | Customers return repeatedly or the relationship is long-term/contractual |
| Repeat-purchase frequency | Purchased rarely (years apart) | Purchased frequently (weekly/monthly) |
| Visual-content suitability | Hard to make visually compelling (e.g. back-office B2B services) | Naturally photogenic/video-friendly (e.g. food, fashion, venues) |
| Current digital maturity (opportunity gap) | Segment is typically already well set up digitally — little visible gap to fix | Segment is typically weak or absent online — large, demonstrable gap to fix |
| Competitive pressure | Little local competition; visibility matters less | Many competing options; standing out matters a lot |
| Urgency of the problem | Business isn't losing much by staying as-is | Business is visibly and immediately losing customers/revenue by staying as-is |
| Ability to pay | Very limited, unpredictable budget | Consistent, meaningful marketing budget available |
| Ease of reaching the owner | Decision-maker is layered behind procurement/gatekeepers | Owner/decision-maker is a single person, easy to reach directly (walk-in, phone, WhatsApp) |
| Speed of the sales cycle | Typically weeks to months of approvals (tenders, committees) | Can decide and sign within days |
| Potential for a monthly retainer | Naturally a one-off, single-project need | Naturally an ongoing, continuous need |
| Potential for cross-selling | Needs are narrow and unlikely to expand | Likely to need multiple additional services over time |
| Number of businesses in the segment | Very few such businesses exist to sell to | Very many such businesses exist to sell to |
| Ease of demonstrating return on investment | Hard to connect marketing activity to a business result the owner will recognize | Easy to show a clear, credible link (e.g. more calls, more bookings) |

## Part 2 — Weighting Model

Not all factors matter equally for a **new** agency without an established reputation, large team, or case-study library. Weights below emphasize factors that make a segment easy to win and easy to prove value in quickly, over factors that matter more once the agency is established.

| Factor | Weight (of 100) | Why this weight |
|---|---:|---|
| Ability to pay | 10 | Without this, nothing else matters — no budget means no engagement regardless of fit |
| Ease of reaching the owner | 9 | A new agency has no inbound brand pull; it depends on being able to get in front of the actual decision-maker directly |
| Ease of demonstrating return on investment | 9 | Early case studies are the agency's most valuable asset; segments where results are easy to show build the proof needed to sell the next client |
| Speed of the sales cycle | 8 | Cash flow and momentum in the first 90 days depend on closing deals quickly, not waiting out long approval chains |
| Urgency of the problem | 7 | Urgent, visible problems sell themselves; low-urgency segments require expensive education-heavy selling |
| Dependence on local discovery | 7 | Directly predicts whether Google Business Profile/local SEO/reviews work — the agency's fastest, cheapest-to-deliver wins |
| Potential for a monthly retainer | 6 | Recurring revenue is what makes the agency sustainable, not just individual projects |
| Dependence on Google Maps | 5 | A specific, high-leverage subset of local discovery |
| Dependence on customer reviews | 5 | Reviews are one of the fastest, cheapest levers the agency can pull for a visible early win |
| Lead value | 5 | Higher-value leads justify higher fees and more attention per client |
| Customer lifetime value | 5 | Segments with high LTV per customer justify a client investing in a bigger, ongoing engagement |
| Number of businesses in the segment | 5 | A larger pool of prospects means the sales pipeline is easier to fill even with a low conversion rate |
| Search demand | 4 | Matters for SEO/ads viability, but a business can still be sold local/social services without high search demand |
| Current digital maturity (opportunity gap) | 4 | A visible gap makes the pitch easier, but too large a gap (zero digital literacy) can also slow delivery — moderate weight |
| Visual-content suitability | 3 | Helps social/content services perform, but is not decisive for local-SEO or lead-gen-first engagements |
| Competitive pressure | 3 | A useful sales angle ("your competitor is ahead of you") but secondary to the harder constraints above |
| Repeat-purchase frequency | 3 | Correlates with retainer potential (already weighted) but adds less independently |
| Potential for cross-selling | 2 | A real bonus, but a first-client decision should not hinge mainly on hypothetical future upsells |

**Weighted score formula:**

```
Weighted Score = Σ (factor score 1–5 × factor weight) ÷ 5
```

Because weights sum to 100 and the maximum factor score is 5, this produces a score from 0–100 (all factors scored 5 → 100×5÷5 = 100; all scored 1 → 100×1÷5 = 20).

## Part 3 — Tiers

| Tier | Score range | Meaning | Action |
|---|---|---|---|
| **A** | 70–100 | Strong fit for a new agency on nearly every dimension that matters right now | Target immediately; build the first prospecting lists, packages, and sales scripts around these segments first |
| **B** | 50–69 | Decent fit but weaker on one or more critical factors (pay, reach, sales-cycle speed, or provable ROI) | Target selectively — pursue via referral, opportunistic contact, or once Tier A delivery capacity is stable |
| **C** | Below 50 | Weak fit for a new agency today, usually due to long sales cycles, regulatory complexity, low reachability, or low near-term ability to pay | Lower priority for now; revisit once the agency has case studies, staff capacity, and reputation to support the longer or more complex sales process |

Low tier does **not** mean "never sell to this segment" — it means "don't build the agency's early pipeline around it." Sections J, M, and Q of the segment map (regulated professional/financial services, government) are structurally Tier B/C for a new agency specifically because of sales-cycle length and compliance overhead, not because the segments lack value.

## Part 4 — Illustrative Application

The table below applies the model to a representative cross-section of segments from [01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md](01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md). Scores are illustrative first-pass estimates, not measured data — see the Purpose note above. Maintain the full 18-factor breakdown per segment in a spreadsheet or CRM (see [implementation/03_TOOL_STACK.md](../implementation/03_TOOL_STACK.md)) rather than in this file; only the outcome is shown here for readability.

| Segment | Illustrative weighted score | Tier | Key drivers | Main caution |
|---|---:|---|---|---|
| Restaurants (casual/full-service) | ~82 | A | High local-discovery and review dependence, visually strong, fast sales cycle, owner easy to reach | Ability to pay varies widely by establishment size |
| Hotels and guesthouses | ~80 | A | Very high review/Maps dependence, strong ROI story (direct bookings), good retainer potential | Higher production/content expectations to compete credibly |
| Cafés and coffee shops | ~78 | A | High local discovery/visual suitability, fast, low-friction sales cycle | Lower average lead value than hospitality/healthcare |
| Beauty salons and barbershops | ~77 | A | High review/local dependence, owner directly reachable, fast cycle | Ability to pay often limited at smaller shops |
| Dental and private clinics | ~75 | A | Very high review dependence, high lead value, strong retainer potential | ⚠️ Healthcare advertising compliance overhead |
| Gyms and fitness studios | ~73 | A | Strong retainer/repeat-purchase fit, good visual-content suitability | Search demand varies by city |
| Wedding/event venues and planners | ~72 | A | High visual suitability, high lead value, urgent seasonal demand | More seasonal/lumpy sales cycle than daily-use segments |
| Auto repair and garages | ~68 | B | High local/review dependence, fast cycle | Lower visual-content suitability, moderate lead value |
| Real estate agents | ~66 | B | High lead value, strong ROI story | Longer sales cycle per transaction; competitive market |
| Private schools and training centres | ~64 | B | High LTV (repeat enrollment/referral), strong urgency around enrollment periods | Decision often involves a small committee, not one owner; educational-claims compliance |
| E-commerce / social-commerce sellers | ~63 | B | High digital-maturity gap turned into opportunity, fast cycle | Ability to pay and lead value vary enormously by seller size |
| Retail (clothing, electronics, homeware) | ~60 | B | Reasonable local/review dependence, large number of prospects | Lower LTV per customer than services segments |
| Coffee/honey exporters and B2B manufacturers | ~55 | B | High lead value, strong cross-sell potential once engaged | Long B2B sales cycle, low local-discovery dependence, harder ROI story short-term |
| Law firms, accounting firms | ~52 | B | High lead value, high ROI potential once trust is established | ⚠️ Advertising-restriction compliance; slower-to-reach decision-makers; trust-building sales cycle |
| Banks, insurance, microfinance | ~38 | C | Large potential lead value | ⚠️ Heavy regulatory/compliance overhead, long procurement-like sales cycle, hard for a new agency to access decision-makers |
| Government and public-sector bodies | ~30 | C | Very high potential engagement value if won | Tender/procurement process, long timelines, formal registration requirements |
| NGOs and large nonprofits | ~48 | C | Meaningful budgets exist in some cases, high visual/storytelling suitability | Committee-based, donor-driven decisions slow the sales cycle considerably |

## Standard Operating Procedure — Applying and Maintaining This Model

- [ ] Before prospecting a new segment not listed in Part 4, score it against Part 1's 18 factors and compute its tier using the Part 2 formula before committing agency resources.
- [ ] Store the full per-segment, per-factor scores in the CRM/spreadsheet, not in this file — this file holds only the summarized outcome and reasoning.
- [ ] Recalibrate a segment's score after every 3–5 real sales attempts in that segment if actual results (response rate, ability to pay, sales-cycle length) diverge from the illustrative estimate.
- [ ] Do not let Tier C status become a permanent exclusion — revisit tiering at each phase boundary in [../01_AGENCY_STRATEGY_AND_POSITIONING.md](../01_AGENCY_STRATEGY_AND_POSITIONING.md) §8 as the agency's capacity and reputation grow.
- [ ] Cross-check any ⚠️-flagged segment against [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md) before it moves from "scored" to "actively prospected."