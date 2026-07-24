# Pricing Architecture

## Purpose

Pricing based only on the agency's own cost is a common and expensive mistake — it caps revenue at whatever the cheapest competitor charges, ignores how much value the work actually creates for the customer, and gives no method for pricing genuinely differentiated work higher. This file defines four distinct pricing perspectives, explains how they interact, and introduces the general pricing formula structure that [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md) turns into working calculators per service category.

**Ground rule:** as throughout `commercial/`, no invented Ethiopian birr figures are stated as fact here — every number below is a formula, a placeholder, or an adjustable assumption to be filled in with the agency's real costs and real market observations at the time of use.

---

## The Four Pricing Perspectives

No single perspective should set a price alone. Each answers a different question, and a defensible price sits at the intersection of all four.

### A. Cost Floor — "What is the minimum this can sustainably cost?"

The cost floor is the price below which the agency loses money or takes on unsustainable risk on a given engagement. It is a **floor**, not a target — it tells you what you must never go below, not what you should charge.

**Cost components to include:**

| Category | What to include |
|---|---|
| Labor | Employee or contractor hours across every service phase (see each `services/` file's Task Breakdown for the real phases involved), at a fully loaded hourly cost (salary/fee, benefits, taxes where applicable) |
| Software and tools | Any paid tool specifically required to deliver the service (see the "Tools" section of the relevant `services/` file) |
| Hosting and domain | Where the agency fronts or manages these costs |
| Advertising-management time | The staff time spent managing a client's ad account, separate from the ad spend itself (see [13. Advertising Pricing](#cross-reference-advertising-pricing) below) |
| Photography and travel | Equipment use/depreciation, travel time and cost for on-location work (see [../services/16_PHOTOGRAPHY_AND_VIDEO.md](../services/16_PHOTOGRAPHY_AND_VIDEO.md)) |
| Payment-processing costs | Fees charged by payment processors on the client's payment to the agency |
| Communication costs | Time spent in calls, messages, and meetings beyond core production work |
| Revision time | A realistic allowance for the agreed number of revision rounds — not zero |
| Project-management/account-management time | Coordination, scheduling, and client communication overhead |
| Administrative overhead | A proportional share of the agency's fixed costs (rent if any, general admin, insurance) |
| Tax obligations | Where applicable to the agency's structure |
| Risk allowance | A buffer for scope creep, non-payment risk, or unexpected complexity |
| Required profit margin | The minimum margin the agency needs to reinvest and sustain itself — a real number, not an afterthought |

**Formula:**

```
Cost Floor = Σ(all cost components above) + Required Minimum Margin
```

Any quoted price below this number is, by definition, a loss or an unsustainable bet — acceptable only as a deliberate, time-limited, approved exception per the discount rules in [Discounts and Negotiation](#discounts-and-negotiation) below — never as the default.

### B. Market Reference — "What does the market already charge, and does it matter?"

Competitor pricing is useful context, not an anchor to copy. Two services can carry the identical label — "social media management," "SEO," "a website" — and differ enormously underneath it.

**Before comparing to a competitor's price, compare:**

- Scope — exactly what's included and excluded
- Quality — production values, technical depth, actual expertise behind the work
- Service depth — how many of the 12 lifecycle phases (per the `services/` files' Task Breakdowns) are actually covered, versus a bare minimum
- Client effort required — does the competitor's cheaper price come with the client doing most of the work?
- Response times and support level
- Deliverables — precisely what's handed over, and in what format/ownership terms
- Reporting — honest, regular, and clear versus minimal or absent
- Account ownership — does the client actually own their own assets (see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)), or does the competitor retain control as a lock-in tactic?
- Maintenance and ongoing support included versus billed separately
- Strategic support — is there a real strategist behind the work, or just execution?

**Rule:** never quote a price primarily because "a competitor charges X." Use competitor pricing only to sanity-check that the agency's price is not wildly disconnected from the market it's competing in, after first controlling for the differences above.

### C. Customer Economic Value — "What is this actually worth to them?"

This is where [01_VALUE_ARCHITECTURE.md](01_VALUE_ARCHITECTURE.md)'s value equation and segment value-driver table become a pricing input, not just a sales narrative. The value created can include:

- Additional bookings, appointments, or occupancy
- More qualified inquiries at a lower cost than the client's current acquisition method
- Reduced dependency on commission-charging intermediaries (booking platforms, delivery apps, referral agents)
- Reduced customer-acquisition cost relative to what the client was previously spending (word of mouth alone, ineffective past marketing, expensive intermediaries)
- Increased customer retention and repeat-purchase rate
- Reduced staff time spent managing marketing tasks internally, freeing that time for revenue-generating work
- Reduced risk of a costly failure (a hacked website, a suspended Google Business Profile, a compliance violation)

**How to use this perspective without inventing numbers:** work from the segment's value-driver ratings in [01_VALUE_ARCHITECTURE.md](01_VALUE_ARCHITECTURE.md) Section 6, and from any real figures the client is willing to share (their own average transaction value, their own estimate of a new customer's worth). Never present an invented ROI projection as fact — see the Ethical Requirements cross-reference at the end of this file.

### D. Willingness and Ability to Pay — "What can and will they actually pay?"

A service can create substantial real value and still be unsuitable for a given customer, because value created, value understood, and ability to pay are three separate things:

| Factor | What it means | Why it matters to pricing |
|---|---|---|
| Value created | The objective economic value per Perspective C | Sets a theoretical ceiling |
| Customer's understanding of that value | Whether the client actually perceives the value (see [01_VALUE_ARCHITECTURE.md](01_VALUE_ARCHITECTURE.md)'s Perceived Likelihood of Success) | A client who doesn't believe the outcome is achievable won't pay for it regardless of its real value |
| Available cash / cash flow | The client's actual liquidity, independent of long-term business value | Determines what payment structure (see [12. One-Time Fees and Monthly Retainers, cross-referenced below]) is realistic |
| Willingness to invest in marketing specifically | Some businesses with real cash prefer to reinvest it elsewhere | Even a wealthy client may not be a good-fit customer for a premium package |
| Urgency of the problem | A business losing customers right now to a visible gap is more willing to pay quickly | Urgency can justify a faster sales cycle and less price resistance, not a higher price on its own |
| Authority of the decision-maker | Whether the person in the conversation can actually approve the spend | A compelling pitch to someone without budget authority doesn't convert regardless of price |

**Rule:** perspectives A–C set the range within which a price is commercially and ethically defensible. Perspective D determines what price, within that range, is actually achievable with a specific customer — and sometimes correctly rules a prospect out entirely rather than forcing a package they can't sustain (see the segment-fit discipline already established in [../market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md](../market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md)).

---

## Synthesizing the Four Perspectives

1. **Cost Floor (A)** sets the absolute minimum — never price below this except as a deliberate, approved, time-limited exception.
2. **Market Reference (B)** is a sanity check, not a target — use it to catch a price that's disconnected from reality in either direction, after adjusting for real scope differences.
3. **Customer Economic Value (C)** sets the ceiling of what's commercially justifiable to propose.
4. **Willingness and Ability to Pay (D)** determines where, between the floor and the ceiling, the actual quoted price and payment structure should land for this specific customer.

A price that satisfies A but ignores C leaves money on the table with high-value clients. A price that chases C while ignoring D loses winnable deals. A price that only references B produces a commodity race to the bottom. All four must be checked, in that order, for every non-trivial engagement.

---

## The General Pricing Formula

This is the shared structure behind every calculator built out in [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md). Each line item is explained conceptually here; the per-category scoring rules and worked structures live in that file.

```
Base delivery cost
+ Overhead allocation
+ Complexity premium
+ Urgency premium
+ Travel and production costs
+ Risk allowance
+ Revision allowance
+ Strategic-value premium
+ Account-management cost
+ Required profit margin
= Recommended price
```

| Line item | What it represents | Driven by |
|---|---|---|
| Base delivery cost | The core labor/production cost to deliver the defined scope | The specific service's task breakdown (see the relevant `services/` file) |
| Overhead allocation | A proportional share of the agency's fixed running costs | Agency-wide, allocated per engagement or per revenue |
| Complexity premium | Extra cost for scope that's harder than the baseline (more locations, more languages, more integrations, a regulated industry) | The complexity scoring factors in [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md) |
| Urgency premium | Extra cost for compressed timelines requiring reprioritized capacity | Client-requested turnaround versus standard turnaround |
| Travel and production costs | Real out-of-pocket and time costs for on-location work | Photography/video shoots, in-person meetings outside the base city |
| Risk allowance | A buffer against scope creep, payment risk, or the specific engagement's higher-than-average uncertainty | Client payment history, scope-definition clarity, industry volatility |
| Revision allowance | Cost of the agreed number of revision rounds | The package's stated revision-round limit (see [03_OFFER_TIERS.md](03_OFFER_TIERS.md)) |
| Strategic-value premium | The portion of price justified by Perspective C (customer economic value) beyond raw delivery cost | The segment's value-driver rating from [01_VALUE_ARCHITECTURE.md](01_VALUE_ARCHITECTURE.md) |
| Account-management cost | Ongoing coordination, communication, and relationship-management time, especially for retainer work | Reporting frequency, meeting cadence, and support-level commitments in the package |
| Required profit margin | The agency's necessary margin, applied last so it isn't eroded by the items above | Agency-wide financial target, not negotiated away per deal |

This formula structure is deliberately the same across every service category so that a proposal combining multiple services (e.g. a website plus ongoing SEO plus social management) can be priced consistently rather than each line being priced by an unrelated, ad hoc method. See [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md) for the specific scoring rules and separate calculators for one-time projects, monthly retainers, advertising management, website development, content production, Google Business Profile management, SEO, and consulting/strategy work.

---

## Cross-Reference: Advertising Pricing

Paid-advertising engagements require a specific pricing structure because ad spend paid to a platform is never agency revenue and must never be presented as though it were. This is developed in full in [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md)'s advertising-management calculator, applying this file's general formula with ad spend explicitly excluded from every agency-fee line item.

## Cross-Reference: One-Time Fees and Retainers

The choice between a one-time setup fee, a monthly retainer, a hybrid structure, deposits, and milestone billing is a cash-flow and risk decision layered on top of the pricing formula above, not a separate pricing philosophy — see [06_PRICING_CALCULATOR.md](06_PRICING_CALCULATOR.md) for the one-time-project and monthly-retainer calculators, and [../01_AGENCY_STRATEGY_AND_POSITIONING.md](../01_AGENCY_STRATEGY_AND_POSITIONING.md) §7 for the agency's default business-model recommendation (hybrid setup fee + retainer).

## Discounts and Negotiation

A discount that reduces price without reducing anything else erodes the Cost Floor (A) established above and teaches every future negotiation that the listed price was never real. The governing principle:

> **Change the scope, terms, speed, responsibility, or payment conditions before changing the price.**

### Acceptable reasons to adjust price or terms

- Genuinely reduced scope (fewer platforms, lower content volume, fewer revisions)
- A longer contractual commitment (justifies a lower effective monthly rate in exchange for reduced client-acquisition-cost risk to the agency)
- Advance or upfront payment (justifies a discount in exchange for improved agency cash flow)
- Multiple locations bundled into a single, more efficient engagement
- Bundled services that reduce the agency's total coordination overhead versus selling them separately
- Reduced reporting detail/frequency
- Client-supplied content (photography, copy) reducing the agency's production cost
- A genuine strategic partnership (e.g. a referral-generating relationship, not just a request for a lower price)
- Charitable or portfolio-building work, explicitly approved in advance by agency leadership, treated as a deliberate exception rather than a precedent

### Negotiation alternatives to offer instead of a straight discount

When a prospect pushes back on price, offer one or more of these rather than simply lowering the number:

- Remove a platform or channel from scope
- Reduce posting/content frequency
- Reduce the number of revision rounds
- Extend the delivery deadline
- Replace agency-produced photography/video with client-supplied material
- Reduce reporting detail or frequency
- Move from a Managed Growth (done-for-you) scope to a Guided Growth (done-with-you) scope — see [03_OFFER_TIERS.md](03_OFFER_TIERS.md)
- Split implementation into phases, spreading cost over a longer period
- Require full or partial advance payment in exchange for a lower rate
- Extend the minimum contract period in exchange for a lower monthly rate

### What discounting must never do

- Reduce price below the Cost Floor (A) without an explicit, approved exception
- Use a fabricated "original price" to make a discount look larger than it is
- Create false urgency or scarcity to pressure a decision
- Be offered inconsistently in a way that penalizes a client who didn't think to ask

## Cross-Reference: Ethical Requirements

Every price produced by this architecture must still satisfy the ethical rules in [01_VALUE_ARCHITECTURE.md](01_VALUE_ARCHITECTURE.md) Section 16: no fake discounts, no inflated reference prices used to make a real price look like a bargain, no hidden fees, and no guaranteed outcomes used to justify a premium price.
