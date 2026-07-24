# Service: Conversion Rate Optimization

## A. Service Definition

**What it is.** A systematic, evidence-based process for increasing the percentage of visitors or inquiries that take the desired action — a call, message, form submission, booking, or purchase — through hypothesis-driven testing and refinement of the website, landing pages, and capture points built under [20_LEAD_GENERATION.md](20_LEAD_GENERATION.md).

**What business problem it solves.** Much of the value created by traffic-generating services (SEO, advertising, social, GBP) is capped by how well the destination page actually converts a visitor. A small improvement in conversion rate compounds across every traffic source without requiring any additional spend on traffic itself.

**Why a customer would pay for it.** Proper CRO requires a disciplined methodology — a clear hypothesis, changing one variable at a time, and enough patience to reach a statistically meaningful conclusion — that most businesses don't have the time or expertise to run themselves. It also requires being honest about when a full statistical test isn't realistic at a given traffic volume (see Task 1.2) rather than presenting an unreliable result as a confident finding.

**Business types that benefit most.** Any business with a website, landing page, or capture point already receiving meaningful traffic — this service pairs naturally with clients already using 03/07/17/18/20. Lower priority for very low-traffic businesses, where testing conclusions would be statistically unreliable regardless of methodology (see Task 1.2).

**What this does not include.** Driving traffic itself (06–09, 10, 17–19). Building the initial capture system ([20_LEAD_GENERATION.md](20_LEAD_GENERATION.md) — this service improves what 20 built, it doesn't replace it). Analytics platform installation ([24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md) installs the tracking; this service consumes the data). Major redesigns — this service recommends targeted, testable changes; a full redesign decision feeds back into [02_WEBSITE_DESIGN.md](02_WEBSITE_DESIGN.md)/[03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) as its own project.

**How it connects to other services.** Consumes traffic and capture-point setup from 20 and data from 24. Coordinates with [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md) and 02/03 to implement copy, layout, or design changes. Informs [14_CONTENT_STRATEGY.md](14_CONTENT_STRATEGY.md)/[15_CONTENT_PRODUCTION.md](15_CONTENT_PRODUCTION.md) on which landing-page approaches convert best.

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Conversion funnel audit, hypothesis generation, test design and execution, results analysis |
| Output | Conversion audit report, prioritized hypothesis backlog, test results log, implemented winning changes |
| Outcome | A higher percentage of the same traffic converts into a lead or sale |
| Financial impact | More revenue or leads from the same traffic and ad spend, effectively lowering the blended cost per acquisition across every channel feeding that page |

## C. Inputs Required From the Client

- Analytics/tracking access from 24, confirmed accurate and complete
- Current conversion-rate baseline
- The capture points and funnel design from 20
- Access to implement changes to the website/landing pages (03/04)
- Realistic traffic-volume expectations, to set the right testing methodology
- Understanding of the business's actual offer/pricing — CRO can't fix a fundamentally weak offer, only how clearly and persuasively it's presented
- Any qualitative customer feedback already available

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Confirm tracking accuracy before any optimization work begins**
| Field | Detail |
|---|---|
| Purpose | CRO built on inaccurate conversion data produces confidently wrong conclusions — this must be verified first, not assumed |
| Inputs | 24's tracking setup |
| Procedure | 1) Verify conversion tracking is firing correctly and completely for every conversion action in scope. 2) Cross-check reported conversions against a real, independent source (e.g. actual CRM-logged leads) for a sanity check. |
| Tools | Google Analytics, CRM, tag-verification tools |
| Deliverable | Confirmed, verified tracking accuracy |
| Owner | CRO specialist |
| Dependency | 24's tracking installed |
| Frequency | One-time before starting, re-verified periodically |
| KPI | Tracking discrepancy between platform-reported and independently verified conversions understood and, if significant, resolved before proceeding |
| Quality check | Sanity-checked against a real, independent number, not just the platform's own report |
| Common mistake | Running a CRO program for months on top of broken or incomplete tracking, drawing conclusions from data that was never accurate to begin with |
| Estimated complexity | Medium |

**Task: Assess traffic volume to determine an appropriate testing methodology**
| Field | Detail |
|---|---|
| Purpose | True split (A/B) testing needs a meaningful volume of traffic and conversions to reach a statistically reliable conclusion; below that volume, a different, more honest approach is needed |
| Inputs | Current traffic and conversion volume |
| Procedure | 1) Assess whether current traffic/conversion volume can realistically support a split test reaching significance in a reasonable timeframe. 2) Where volume is too low, plan to use a sequential before/after approach with a longer observation window and appropriately cautious conclusions, or focus on qualitative/heuristic-based improvements instead. |
| Tools | Traffic/conversion data, a sample-size calculator |
| Deliverable | Documented testing-methodology decision |
| Owner | CRO specialist |
| Dependency | Task 1.1 |
| Frequency | One-time, revisited if traffic volume changes materially |
| KPI | Methodology matched honestly to actual traffic volume |
| Quality check | Decision explained to the client in plain terms, including the limits of what conclusions the current traffic volume can support |
| Common mistake | Running a split test on very low traffic and presenting an inconclusive or noise-driven result as a confident, statistically significant finding |
| Estimated complexity | Low |

### 2. Research

**Task: Conduct a conversion funnel audit**
| Field | Detail |
|---|---|
| Purpose | Identifies exactly where visitors are dropping off before generating any hypotheses |
| Inputs | Analytics data, capture points from 20 |
| Procedure | 1) Map the funnel from landing to conversion for each key page/flow. 2) Identify the steps with the highest drop-off rate. 3) Review the actual page/flow at each high-drop-off step for obvious friction. |
| Tools | Google Analytics funnel/path reports |
| Deliverable | Conversion funnel audit report |
| Owner | CRO specialist |
| Dependency | Task 1.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | The highest-drop-off step(s) clearly identified with supporting data |
| Quality check | Findings backed by actual funnel data, not assumption |
| Common mistake | Assuming the homepage is the biggest problem without checking the data, when the real drop-off is often deeper in the flow (e.g. at the form itself) |
| Estimated complexity | Medium |

**Task: Gather qualitative insight**
| Field | Detail |
|---|---|
| Purpose | Quantitative data shows *where* visitors drop off; qualitative insight helps explain *why* |
| Inputs | Heatmap/session-recording tools if in scope, direct customer/staff feedback |
| Procedure | 1) Review heatmaps or session recordings if available and in scope, looking for confusion signals (rage clicks, hovering without acting). 2) Gather direct feedback from staff who talk to customers, or from the reviews/complaints already being tracked in [11_REVIEW_AND_REPUTATION_MANAGEMENT.md](11_REVIEW_AND_REPUTATION_MANAGEMENT.md), about points of confusion or hesitation. |
| Tools | Heatmap/session-recording tool (if in scope), staff interviews |
| Deliverable | Qualitative insight notes |
| Owner | CRO specialist |
| Dependency | Task 2.1 |
| Frequency | One-time initial pass, revisited quarterly |
| KPI | At least one qualitative insight source consulted, not quantitative data alone |
| Quality check | Insight cross-checked against the quantitative drop-off data for consistency |
| Common mistake | Relying purely on quantitative drop-off data without ever asking why, missing the actual reason behind a friction point |
| Estimated complexity | Medium |

### 3. Strategy

**Task: Build a prioritized hypothesis backlog**
| Field | Detail |
|---|---|
| Purpose | Prevents random, unfocused testing by ranking ideas on likely impact, ease of implementation, and confidence in the underlying evidence |
| Inputs | Funnel audit, qualitative insight |
| Procedure | 1) Generate specific, testable hypotheses for each identified friction point (e.g. "shortening the form from 8 fields to 4 will increase submission rate"). 2) Score each by potential impact, ease of implementation, and confidence in the supporting evidence. 3) Sequence the backlog highest-priority first. |
| Tools | Shared spreadsheet |
| Deliverable | Prioritized hypothesis backlog |
| Owner | CRO specialist |
| Dependency | Tasks 2.1–2.2 |
| Frequency | One-time initial backlog, replenished ongoing (Task 12.1) |
| KPI | Every hypothesis is specific and testable, not vague ("improve the page") |
| Quality check | Each hypothesis traces back to a specific piece of evidence from Task 2 |
| Common mistake | Testing changes based on personal aesthetic preference or generic "best practice" claims rather than evidence specific to this business's actual funnel |
| Estimated complexity | Medium |

### 4. Setup

**Task: Set up testing and behavior-analysis tools**
| Field | Detail |
|---|---|
| Purpose | Provides the infrastructure needed to actually run and measure a test |
| Inputs | Testing methodology decision from Task 1.2 |
| Procedure | 1) Set up a split-testing tool if traffic supports it, or a before/after tracking framework if not. 2) Set up a heatmap/session-recording tool if in scope and not already active. |
| Tools | An A/B testing tool (e.g. Google Optimize successor tools, or CMS-native split testing), heatmap/session-recording tool |
| Deliverable | Active testing infrastructure |
| Owner | CRO specialist |
| Dependency | Task 1.2 |
| Frequency | One-time setup |
| KPI | Testing tool confirmed working with a test run before relying on it |
| Quality check | Verified with a test event, not assumed functional from installation alone |
| Common mistake | Installing a testing tool but never confirming it accurately splits traffic and reports data before relying on its results |
| Estimated complexity | Medium |

### 5. Production

**Task: Build the test variant**
| Field | Detail |
|---|---|
| Purpose | Produces the actual alternative version to be tested against the current page/flow |
| Inputs | Prioritized hypothesis |
| Procedure | 1) Build the variant reflecting the single hypothesis being tested (e.g. a shorter form, a different headline, a repositioned call-to-action). 2) Change only the one variable the hypothesis addresses, keeping everything else identical. |
| Tools | CMS, coordination with 02/04 for design/copy changes |
| Deliverable | Built test variant |
| Owner | CRO specialist, with design/copywriting support |
| Dependency | Task 4.1 |
| Frequency | Per test |
| KPI | Variant differs from the control by exactly the one variable under test |
| Quality check | Reviewed by a second team member to confirm no unintended additional differences crept in |
| Common mistake | Changing multiple elements at once (new headline and new image and new button color), making it impossible to know which change drove any resulting difference |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Launch the test**
| Field | Detail |
|---|---|
| Purpose | Puts the test live and collecting real data |
| Inputs | Built variant, testing infrastructure |
| Procedure | 1) Launch the split test (or begin the before period of a sequential test). 2) Confirm both variants (or before/after periods) are being measured correctly. |
| Tools | Testing tool |
| Deliverable | Live, correctly measured test |
| Owner | CRO specialist |
| Dependency | Task 5.1 |
| Frequency | Per test |
| KPI | Test confirmed live and measuring correctly within the first day |
| Quality check | Spot-checked shortly after launch to confirm traffic is actually being split/measured as intended |
| Common mistake | Launching a test and not checking back until the end, missing an early technical problem that invalidates the whole test |
| Estimated complexity | Low |

### 7. Testing

**Task: Monitor for statistical validity before concluding**
| Field | Detail |
|---|---|
| Purpose | Ending a test too early, before reaching a meaningful sample size, is the single most common cause of a false conclusion in CRO work |
| Inputs | Live test data |
| Procedure | 1) Track sample size and, where running a true split test, statistical significance as data accumulates. 2) Do not conclude the test until a pre-defined minimum sample size or duration is reached. 3) For a before/after test, ensure the observation period is long enough to account for normal variation (day-of-week, seasonal effects). |
| Tools | Testing tool's statistical reporting, sample-size calculator |
| Deliverable | Validated test result |
| Owner | CRO specialist |
| Dependency | Task 6.1 |
| Frequency | Per test, checked regularly until concluded |
| KPI | No test concluded before its pre-defined minimum sample size/duration |
| Quality check | Result checked against the pre-defined threshold set before the test began, not decided after seeing early promising data |
| Common mistake | Stopping a test as soon as the variant appears to be winning, before reaching real statistical confidence — a well-documented source of false positives |
| Estimated complexity | Medium |

### 8. Launch

**Task: Implement the winning variant permanently**
| Field | Detail |
|---|---|
| Purpose | Converts a validated test result into a permanent improvement |
| Inputs | Validated test result |
| Procedure | 1) Once a test concludes with a valid result, implement the winning variant as the permanent version. 2) If the test was inconclusive, document that honestly rather than picking a "preferred" version arbitrarily. |
| Tools | CMS |
| Deliverable | Permanently implemented winning variant, or an honestly documented inconclusive result |
| Owner | CRO specialist |
| Dependency | Task 7.1 |
| Frequency | Per test |
| KPI | Every concluded test results in either an implementation or a documented inconclusive finding — never silently dropped |
| Quality check | Implementation double-checked to match exactly what was validated in the test |
| Common mistake | Declaring an inconclusive test a "win" for whichever variant looked slightly better, rather than honestly reporting no clear result |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Confirm the improvement holds post-implementation**
| Field | Detail |
|---|---|
| Purpose | A test result can occasionally fail to replicate once implemented at full traffic — checking confirms the real-world impact |
| Inputs | Post-implementation conversion data |
| Procedure | 1) Monitor conversion rate for a defined period after implementing a winning variant. 2) Confirm the improvement is holding at the expected magnitude. |
| Tools | Google Analytics |
| Deliverable | Post-implementation confirmation |
| Owner | CRO specialist |
| Dependency | Task 8.1 |
| Frequency | For 2–4 weeks following each implementation |
| KPI | Improvement confirmed to hold, or flagged for investigation if it doesn't |
| Quality check | Compared against the pre-test baseline, not just the test-period result |
| Common mistake | Assuming a test's measured lift automatically persists indefinitely without ever checking back afterward |
| Estimated complexity | Low |

### 10. Optimization

**Task: Move to the next hypothesis in the backlog**
| Field | Detail |
|---|---|
| Purpose | CRO is a continuous, compounding process — each validated improvement should be followed by the next highest-priority test |
| Inputs | Prioritized hypothesis backlog |
| Procedure | 1) Select the next highest-priority hypothesis. 2) Repeat the build-test-validate-implement cycle. |
| Tools | Hypothesis backlog |
| Deliverable | Next test cycle initiated |
| Owner | CRO specialist |
| Dependency | Task 9.1 |
| Frequency | Ongoing, one test cycle at a time per page/flow |
| KPI | A new test cycle begins promptly after each previous one concludes |
| Quality check | Only one active test per page/flow at a time to keep results attributable |
| Common mistake | Running multiple overlapping tests on the same page simultaneously, making it impossible to attribute results cleanly |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the CRO report**
| Field | Detail |
|---|---|
| Purpose | Shows the client the cumulative, compounding value of the testing program |
| Inputs | Test results log |
| Procedure | 1) Summarize tests run, results (including inconclusive ones, reported honestly), and implemented changes. 2) Show the cumulative conversion-rate improvement over time where multiple tests have been implemented. |
| Tools | Report template |
| Deliverable | CRO report |
| Owner | CRO specialist / account lead |
| Dependency | Task 9.1 |
| Frequency | Monthly, with a fuller quarterly cumulative view |
| KPI | Report delivered on schedule |
| Quality check | Inconclusive or losing tests reported alongside wins, not omitted |
| Common mistake | Only reporting successful tests, hiding inconclusive or negative results and giving a distorted picture of the program's actual learnings |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Replenish the hypothesis backlog and re-audit the funnel periodically**
| Field | Detail |
|---|---|
| Purpose | Keeps the testing program fed with fresh, evidence-based ideas rather than running out of things to test |
| Inputs | Ongoing monitoring, qualitative feedback |
| Procedure | 1) Add new hypotheses as new evidence emerges from ongoing monitoring or feedback. 2) Repeat the full funnel audit (Task 2.1) periodically to catch new friction points as the business, site, or traffic composition changes. |
| Tools | Hypothesis backlog, analytics |
| Deliverable | Continuously replenished backlog and periodically refreshed funnel audit |
| Owner | CRO specialist |
| Dependency | Ongoing |
| Frequency | Backlog reviewed monthly; full funnel re-audit quarterly |
| KPI | Backlog never runs empty between test cycles |
| Quality check | Re-audit compared against the original audit to confirm real, cumulative progress |
| Common mistake | Running the same handful of tests repeatedly without periodically stepping back to re-audit the whole funnel for new opportunities |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Verified tracking accuracy and a documented testing-methodology decision
- Conversion funnel audit and qualitative insight notes
- Prioritized hypothesis backlog
- Active testing infrastructure

**Monthly deliverables**
- Test cycles run and results (including inconclusive ones)
- CRO report

**Quarterly deliverables**
- Cumulative conversion-rate improvement summary
- Full funnel re-audit

**Optional add-ons**
- Heatmap/session-recording tool subscription
- Dedicated landing-page variant production for high-value campaigns

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Tests run per period, with valid methodology | Leading | Directly attributable |
| Percentage of tests reaching a valid (not premature) conclusion | Leading | Directly attributable |
| Conversion rate at each tested step | Lagging | Directly attributable for the specific tested change; broader page conversion rate is also affected by traffic quality and offer strength |
| Cumulative conversion-rate improvement | Lagging | Represents the compounding effect of validated implementations; report alongside a caveat about traffic-composition changes over the same period |
| Cost per acquisition (blended, across paired traffic services) | Lagging | Improved by this service alongside traffic-cost efficiency from 17/18/19 — a shared outcome, not attributable to CRO alone |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Google Analytics, a free sample-size calculator | Sufficient for funnel analysis and methodology decisions |
| Low-cost | Entry-tier heatmap/session-recording tools, CMS-native split-testing features | Useful once traffic supports meaningful behavioral analysis |
| Professional | Dedicated A/B testing and experimentation platforms | Justified for higher-traffic clients running frequent, more sophisticated tests |
| Low-bandwidth / mobile-first consideration | Testing variants evaluated on real mobile performance, not just desktop preview, since most conversion attempts will happen on mobile | Ensures test conclusions reflect the real majority-use environment |

## H. Risks and Common Failure Modes

- **Technical risk:** a testing tool incorrectly splitting traffic or misreporting results.
- **Platform risk:** third-party testing/analytics tools changing features or being deprecated over time.
- **Client-related risk:** pressure to implement a "preferred" variant before a test has reached statistical validity.
- **Data and access risk:** running CRO on top of inaccurate or incomplete conversion tracking, invalidating every conclusion drawn from it.
- **Reputation risk:** presenting an inconclusive or statistically weak result as a confident win damages the agency's credibility once the client or the numbers later contradict it.
- **Security risk:** not typically applicable directly to this service.
- **Legal or compliance risk:** test variants for ⚠️-flagged sectors must respect the same claim restrictions as copywriting.
- **Measurement and attribution risk:** at low traffic volumes, true statistical testing may not be feasible — this must be communicated honestly rather than overstating the reliability of a result (see Task 1.2).

## I. Standard Operating Procedure

- [ ] Tracking accuracy verified and sanity-checked against an independent data source before starting
- [ ] Testing methodology (split test vs. sequential before/after) honestly matched to actual traffic volume
- [ ] Conversion funnel audit completed with the highest-drop-off steps identified
- [ ] Qualitative insight gathered to explain the "why" behind the drop-off
- [ ] Hypothesis backlog built, prioritized, and every hypothesis specific and testable
- [ ] Testing infrastructure set up and confirmed working before relying on it
- [ ] Test variants change exactly one variable each, peer-reviewed before launch
- [ ] Tests launched and spot-checked shortly after going live
- [ ] No test concluded before its pre-defined minimum sample size/duration
- [ ] Winning variants implemented permanently; inconclusive results documented honestly, never forced into a "win"
- [ ] Post-implementation performance confirmed to hold for 2–4 weeks
- [ ] Next hypothesis cycle initiated promptly, one active test per page/flow at a time
- [ ] Monthly report includes losing/inconclusive tests, not only wins
- [ ] Hypothesis backlog replenished monthly; full funnel re-audited quarterly
