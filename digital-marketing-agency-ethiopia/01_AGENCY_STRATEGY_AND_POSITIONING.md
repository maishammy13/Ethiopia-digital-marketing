# Agency Strategy and Positioning

## Purpose of this file

Before selling any service, the agency needs to decide what it is, who it serves first, how it wins against alternatives, and how it will grow without collapsing under its own scope. This file is the strategic foundation that every other file in this system assumes. If a decision here changes (for example, which segments to target first), update this file and note the change in `../../claude.md` or the project's own working-notes file so the change is visible before it causes inconsistency elsewhere.

Related files: [02_SERVICE_CATALOGUE.md](02_SERVICE_CATALOGUE.md), [market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md](market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md), [commercial/01_SERVICE_PACKAGES.md](commercial/01_SERVICE_PACKAGES.md), [implementation/01_FIRST_30_DAYS.md](implementation/01_FIRST_30_DAYS.md).

---

## 1. Market Context (assumptions — verify before relying on them commercially)

The following statements describe general, widely-observed conditions in emerging digital-marketing markets and are **not** sourced statistics about Ethiopia specifically. Each must be checked against current data (e.g. Ethiopian Communications Authority reports, GSMA Mobile Economy reports, HDI/World Bank data, or direct field research) before being used in a pitch deck or public claim.

| Assumption | Why it matters to strategy | Verification needed |
|---|---|---|
| Smartphone and mobile-internet use is growing faster than fixed broadband use among Ethiopian consumers and businesses | Justifies a mobile-first, WhatsApp-centric, low-bandwidth-friendly service design | Current mobile penetration and mobile-data-cost figures for Ethiopia |
| Most small and medium Ethiopian businesses have little or no professional digital presence (no website, an inactive or unclaimed Google Business Profile, inconsistent social accounts) | Creates the core "digital foundation" opportunity — see [Package 1](commercial/01_SERVICE_PACKAGES.md) | Field audits per target segment/city, not assumed |
| Google Search and Google Maps are the dominant local-discovery tools where internet access exists; Telegram, Facebook, Instagram, and TikTok are the dominant social platforms; LinkedIn matters mainly for B2B and professional services | Determines which services are "default" vs. "situational" per segment | Platform-usage patterns shift quickly; re-check yearly and per segment |
| Trust and word-of-mouth strongly influence Ethiopian consumer buying decisions, meaning reviews and referrals carry outsized weight relative to paid advertising alone | Justifies prioritizing [Review and Reputation Management](services/11_REVIEW_AND_REPUTATION_MANAGEMENT.md) early in most packages | Qualitative — confirm per segment during discovery calls, not assumed universal |
| Price sensitivity is high for most SME segments; ability to pay varies enormously by sector (e.g. hospitality/exporters vs. small retail) | Justifies tiered packaging instead of one flagship offer | See [market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md](market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md) "Ability to pay" scoring |
| Regulatory and payment infrastructure (online payments, ad-account billing, platform verification) can be harder to access than in mature markets | Affects which deliverables are realistic (e.g. in-platform payment integration) and timelines | Confirm current banking/payment-gateway and ad-platform billing options available in Ethiopia at time of delivery |

**Rule:** any number that looks like a market statistic in future files (market size, number of businesses, percentage of internet users, etc.) must either cite a real, checkable source or be explicitly labeled as an assumption requiring field verification. Never state invented figures as fact.

---

## 2. What This Agency Is

A digital-marketing agency that helps Ethiopian businesses become findable, trustworthy, and reachable online, and converts that visibility into calls, messages, bookings, and sales — using the smallest solution that produces a measurable result, then expanding as the client's budget and readiness grow.

**What this agency is not:**
- Not a pure website-development shop (websites are one service among many, not the default first sale).
- Not a "guaranteed #1 on Google" operation — no ranking, follower, or sales guarantees are made (see §4 and [operations/15_LEGAL_COMPLIANCE_AND_RISK.md](operations/15_LEGAL_COMPLIANCE_AND_RISK.md)).
- Not a one-size-fits-all retainer seller — service recommendations are matched to segment and business maturity, per [market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md).
- Not, at launch, a full-service creative/branding house competing with established ad agencies for large corporate branding budgets — that is a later-stage expansion, not a foundation.

## 3. Mission

Give Ethiopian businesses of any size a professional, trustworthy digital presence and a repeatable way to turn that presence into paying customers, delivered honestly, measured transparently, and priced for the realities of the local market.

## 4. Positioning Statement

Use this as the master statement; adapt tone per segment but keep the substance consistent across sales scripts, proposals, and the agency's own website.

> For [Ethiopian small and medium businesses] who [are hard to find online, have no or weak Google/Maps presence, and cannot verify whether past marketing spend produced results], [Agency Name] is the [digital-marketing partner] that [builds and manages the specific digital presence a business needs — website, Google Business Profile, social media, advertising, or all of these — and reports honestly on what it produced], unlike [freelancers who disappear after delivery, agencies that oversell services the client doesn't need, or DIY attempts that stall from lack of time and skill].

Test every packaging, pricing, or messaging decision against this statement. If it doesn't reinforce "the right-sized solution, delivered reliably, measured honestly," reconsider it.

## 5. Differentiation

| Differentiator | What it means in practice | Where it shows up |
|---|---|---|
| Right-sized selling | Never recommend a full website + paid ads package to a business that would get more value from a Google Business Profile fix and a review system | [market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md), [commercial/01_SERVICE_PACKAGES.md](commercial/01_SERVICE_PACKAGES.md) |
| Ownership transparency | Client owns their domain, hosting, Google Business Profile, social accounts, and ad accounts from day one; agency works via granted access, not accounts it controls | [operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md) |
| Honest measurement | Reports separate what is directly attributable (e.g. ad-platform conversions) from what is directional (e.g. organic ranking movement); no vanity metrics presented as business results | [services/24_ANALYTICS_TRACKING_AND_REPORTING.md](services/24_ANALYTICS_TRACKING_AND_REPORTING.md) |
| Mobile-first, low-bandwidth-aware delivery | Websites, ads, and content are built and tested for the connection speeds and devices target customers actually use, not assumed high-end setups | [services/03_WEBSITE_DEVELOPMENT.md](services/03_WEBSITE_DEVELOPMENT.md) |
| Segment fluency | Sales and delivery staff understand the specific dynamics of the segments they serve (e.g. a restaurant's needs differ fundamentally from a law firm's) rather than applying one generic playbook | [market-mapping/](market-mapping/) |

## 6. Target Market Summary

Full detail lives in `market-mapping/`. Summary for strategic purposes:

- **Level 1 (customer types):** nearly every organized business sector in Ethiopia is a theoretical customer — see [market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md](market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md).
- **Level 2 (who to actually pursue first):** a new agency with limited staff, cash, and case studies cannot serve everyone at once. Initial focus should go to segments that score highest on the prioritization model in [market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md](market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md) — segments with high dependence on local discovery and reviews, reachable decision-makers, a fast sales cycle, and a realistic ability to pay (e.g. hospitality, food and beverage, healthcare/clinics, beauty and personal care, and professional services tend to score well on these dimensions, subject to the scoring model, not assumed here).
- **Geography:** initial delivery capacity should concentrate where in-person selling and support are feasible (typically Addis Ababa first), expanding to regional cities per [market-mapping/03_CITY_AND_GEOGRAPHIC_PRIORITIZATION.md](market-mapping/03_CITY_AND_GEOGRAPHIC_PRIORITIZATION.md).
- **Segments to defer, not ignore:** government/public-sector (long procurement cycles), heavily regulated financial and healthcare advertising (compliance overhead), and large enterprise/manufacturing B2B (long sales cycles, needs case studies the agency won't have yet) are lower priority for a new agency, not permanently excluded. See Tier C reasoning in the prioritization file.

## 7. Business Model

| Model | Description | When to use | Risk |
|---|---|---|---|
| One-time project | Client pays for a defined deliverable (e.g. website build, GBP setup) with no ongoing commitment | Digital Foundation-type engagements, budget-constrained clients, first engagement with a new client to build trust | No recurring revenue; client may not maintain the asset afterward |
| Monthly retainer | Client pays a recurring fee for ongoing management (social media, SEO, ads, reporting) | Once a client has an initial asset in place and wants sustained results | Requires consistent delivery capacity and clear scope to avoid scope creep |
| Hybrid (setup fee + retainer) | Upfront project fee for setup, then a smaller recurring fee for management and optimization | Most services that have both a build phase and an ongoing phase (websites, GBP, social, ads) | Needs clear contract language distinguishing the two phases — see [operations/05_PROPOSALS_AND_CONTRACTING.md](operations/05_PROPOSALS_AND_CONTRACTING.md) |
| Performance/ad-spend-linked | Fee tied partly to advertising budget managed or leads generated | Lead-generation and paid-advertising engagements with clients who have budget and trust already established | Should never be the only pricing model early on — attribution is imperfect and disputes are more likely without a trust foundation |

**Recommendation for launch:** lead with the hybrid model (setup fee + retainer) as the default, with pure one-time projects available as a lower-commitment entry point for first-time or budget-constrained clients. Avoid performance-only pricing until the agency has case studies and mature tracking (see [services/24_ANALYTICS_TRACKING_AND_REPORTING.md](services/24_ANALYTICS_TRACKING_AND_REPORTING.md)). Full pricing mechanics are in [commercial/02_PRICING_MODEL.md](commercial/02_PRICING_MODEL.md).

## 8. Growth Model

Three phases, detailed operationally in `implementation/`:

1. **Foundation (roughly first 30 days):** agency's own positioning, tools, sales materials, and Google Business Profile/social presence are set up; first prospecting begins. See [implementation/01_FIRST_30_DAYS.md](implementation/01_FIRST_30_DAYS.md).
2. **Traction (roughly days 31–90):** first paying clients delivered well enough to produce case studies and referrals; delivery processes get stress-tested and fixed. See [implementation/02_FIRST_90_DAYS.md](implementation/02_FIRST_90_DAYS.md).
3. **Scale (beyond day 90):** segment specialization, pricing refinement, hiring/outsourcing, partnerships, and a real KPI dashboard replace ad hoc decision-making. See [implementation/06_AGENCY_KPI_DASHBOARD.md](implementation/06_AGENCY_KPI_DASHBOARD.md).

Growth should be funded primarily by retained clients and referrals before the agency invests heavily in its own paid acquisition — see [operations/01_LEAD_GENERATION_FOR_THE_AGENCY.md](operations/01_LEAD_GENERATION_FOR_THE_AGENCY.md).

## 9. Brand and Naming Guidance

No agency name is assumed by this system. When one is chosen, it should be checked for:

- Availability as a `.com` or relevant local domain, and as consistent handles across Google Business Profile, Instagram, Facebook, TikTok, and LinkedIn.
- Pronounceability and spelling simplicity in both Amharic and English contexts, since the agency will operate in a multilingual market.
- No unintended meaning in major Ethiopian languages relevant to the target cities.
- Room to grow beyond one city or one service category (avoid overly narrow names like "AddisWebDesign" if the intent is to expand services or geography).

Once named, the agency's own website and social profiles should be treated as the first client delivery — see the cross-references in §6 of [00_README.md](00_README.md) and the website services in `services/`. A digital-marketing agency with a weak or absent digital presence is a credibility risk in every sales conversation.

## 10. Service Selection Philosophy

The full catalogue is in [02_SERVICE_CATALOGUE.md](02_SERVICE_CATALOGUE.md). The philosophy governing which services to build out first and recommend most:

- Prioritize services that are foundational to nearly every segment (Google Business Profile, reviews, basic website or landing page presence) before specialized or platform-specific services (e.g. TikTok advertising).
- Recommend the smallest package that produces a measurable outcome before upselling a larger one — never lead with the largest package by default (see [commercial/01_SERVICE_PACKAGES.md](commercial/01_SERVICE_PACKAGES.md)).
- Only recommend a service if there is a credible mechanism connecting it to a business outcome the client cares about (visibility → inquiries → bookings/sales), not because it is trendy.
- Regulated or sensitive service areas (healthcare advertising, financial-services advertising, before/after imagery, testimonials) require the compliance flags in [operations/15_LEGAL_COMPLIANCE_AND_RISK.md](operations/15_LEGAL_COMPLIANCE_AND_RISK.md) to be checked before being sold.

## 11. Risks to the Strategy Itself

| Risk | Description | Mitigation |
|---|---|---|
| Scope creep across too many segments at once | Trying to serve every sector in `market-mapping/01_ETHIOPIA_CUSTOMER_SEGMENT_MAP.md` simultaneously dilutes expertise and case studies | Follow Tier A segments first per the prioritization model; expand deliberately |
| Overpromising results | Claiming specific ranking positions, follower counts, or revenue outcomes damages trust and may violate platform or advertising norms | Standardize language in [commercial/05_SALES_SCRIPTS.md](commercial/05_SALES_SCRIPTS.md) and [operations/15_LEGAL_COMPLIANCE_AND_RISK.md](operations/15_LEGAL_COMPLIANCE_AND_RISK.md) |
| Underpricing to win first clients | Sets unsustainable expectations and anchors future pricing conversations too low | Use the unit-economics model in [commercial/03_UNIT_ECONOMICS.md](commercial/03_UNIT_ECONOMICS.md) before discounting |
| Treating assumptions in §1 as facts | Using unverified market claims in a client-facing pitch undermines the "honest measurement" differentiator | Verify before citing; prefer field-audit evidence per prospect over generalized claims |

## 12. Standard Operating Procedure — Reviewing This Strategy

- [ ] Revisit this file at the end of each phase in §8 (30/90 day marks) and whenever a major market signal changes (e.g. a target segment turns out to be unreachable or unprofitable).
- [ ] Before any public claim referencing market size, adoption rates, or platform usage in Ethiopia, confirm it is sourced or explicitly labeled as an assumption.
- [ ] Before adding a new service to the catalogue, confirm it satisfies the service-selection philosophy in §10.
- [ ] Before entering a new geography or segment, confirm it against `market-mapping/02_CUSTOMER_SEGMENT_PRIORITIZATION.md` and `03_CITY_AND_GEOGRAPHIC_PRIORITIZATION.md` rather than ad hoc opportunity.