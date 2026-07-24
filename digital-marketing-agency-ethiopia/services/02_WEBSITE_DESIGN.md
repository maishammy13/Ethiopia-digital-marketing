# Service: Website Design

## A. Service Definition

**What it is.** Translates the signed-off [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md) into a detailed information architecture, wireframes, and full visual design (layout, brand application, imagery direction, typography) that [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md) builds from. Covers everything the customer will see and interact with before a single line of production code is written.

**What business problem it solves.** A site with the right strategy can still fail if it is confusing to navigate, slow-loading due to poor image/layout choices, inconsistent across pages, unwelcoming on a small mobile screen, or simply doesn't look credible enough for a visitor to trust the business.

**Why a customer would pay for it.** First impressions are formed in seconds; a professional, easy-to-use, trustworthy design measurably affects whether a visitor stays, believes the business is legitimate, and takes the action the business wants (call, message, book).

**Business types that benefit most.** Any business where the website plays a real role in the buying decision — see the "Website" column in [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md). Visual-heavy segments (hospitality, food, beauty, real estate, events) benefit especially from strong imagery-led design; trust-sensitive segments (healthcare, law, finance) benefit especially from credibility-signal design (certifications, clear contact information, professional tone).

**What this service does not include.** Website strategy/research (01), actual coding and CMS build (03), final copywriting (04 — design works with approved or placeholder copy), original photography/video production (16 — design specifies what's needed and works with supplied or produced assets), brand identity creation from scratch (25 — design applies an existing or concurrently-developed brand, it does not invent one unprompted).

**How it connects to other services.** Consumes the Website Strategy Document from 01. Feeds 03 directly (developers build the approved design). Coordinates with 04 (copy must fit the designed layout and vice versa) and with 16/25 (imagery and brand assets are inputs to design, not outputs of it).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Wireframing, visual design, prototyping, design review cycles |
| Output | Approved wireframes, approved visual designs for all key page templates (desktop and mobile), a short style guide |
| Outcome | A professional, easy-to-use, trustworthy site that developers can build accurately and that supports the conversion goals defined in strategy |
| Financial impact | Higher on-site conversion rate from better usability and trust signals; lower development cost from fewer build revisions caused by unclear design |

## C. Inputs Required From the Client

- Signed-off Website Strategy Document (sitemap, personas, conversion goals) from [01_WEBSITE_STRATEGY.md](01_WEBSITE_STRATEGY.md)
- Brand assets (logo, color palette, fonts) — or a referral to [25_BRANDING_AND_GRAPHIC_DESIGN.md](25_BRANDING_AND_GRAPHIC_DESIGN.md) if none exist yet
- Photographs and video, or agreement to use stock imagery/commission [16_PHOTOGRAPHY_AND_VIDEO.md](16_PHOTOGRAPHY_AND_VIDEO.md)
- Draft copy or explicit agreement to design against placeholder text pending [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md)
- Examples of websites the client likes or dislikes, and why
- A named approver and a realistic feedback-turnaround commitment for review rounds

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Review strategy document and confirm design-ready inputs**
| Field | Detail |
|---|---|
| Purpose | Prevents starting design work on an unclear or missing foundation |
| Inputs | Website Strategy Document, brand assets, image/copy status |
| Procedure | 1) Confirm the strategy document is signed off. 2) Check brand assets, images, and copy status against C. 3) Flag any missing input and agree a placeholder plan (e.g. "design with brand-colors-only until logo is finalized") rather than stalling. |
| Tools | Checklist, shared drive |
| Deliverable | Design-readiness checklist, signed |
| Owner | Design lead |
| Dependency | Strategy sign-off (01, Task 6.1) |
| Frequency | One-time per project |
| KPI | Checklist completed before wireframing starts |
| Quality check | Every "missing input" has an explicit placeholder decision, not silence |
| Common mistake | Starting full visual design before brand assets exist, causing a redo once the logo/colors are finalized |
| Estimated complexity | Low |

### 2. Research

**Task: Design and usability audit of comparable sites**
| Field | Detail |
|---|---|
| Purpose | Grounds design decisions in what actually works for credible sites in this segment, building on the competitor list from strategy |
| Inputs | Competitor list from 01, target-customer device/behavior assumptions |
| Procedure | 1) Review the layout, navigation, and calls-to-action of the competitor sites identified in strategy. 2) Note specific patterns worth adopting or specifically avoiding. 3) Check how each performs on a mobile device, not just desktop. |
| Tools | Google Chrome mobile device emulator (free), manual mobile testing on an actual phone |
| Deliverable | Short design-research note | 
| Owner | Designer |
| Dependency | Task 1.1 |
| Frequency | One-time per project |
| KPI | At least 3 patterns to adopt and 2 to avoid documented |
| Quality check | Findings are specific ("use a sticky WhatsApp button," not "make it modern") |
| Common mistake | Copying a competitor's design directly instead of learning from its usability patterns |
| Estimated complexity | Low |

### 3. Strategy

**Task: Define detailed information architecture and navigation**
| Field | Detail |
|---|---|
| Purpose | Turns the strategy's page list into an actual navigable structure a visitor can move through easily |
| Inputs | Sitemap from 01 |
| Procedure | 1) Group pages into a primary navigation menu (kept short — most SME sites need 5–7 top-level items). 2) Decide secondary navigation (footer links, in-page anchors). 3) Confirm every required page (homepage, about, services/products, locations if multi-site, FAQ, testimonials, gallery, booking, contact, privacy/policy pages, blog/resources if applicable) has a place in the structure. |
| Tools | Whiteboard/diagramming tool, shared document |
| Deliverable | Navigation structure diagram |
| Owner | Designer |
| Dependency | Task 1.1 |
| Frequency | One-time per project |
| KPI | Every sitemap page placed in the navigation without duplication or dead ends |
| Quality check | A person unfamiliar with the business can find "contact" and the core service within 2 clicks |
| Common mistake | Overloading the main navigation menu with every page instead of grouping logically |
| Estimated complexity | Medium |

**Task: Define visual design direction**
| Field | Detail |
|---|---|
| Purpose | Sets a consistent visual language before individual pages are designed, avoiding a patchwork result |
| Inputs | Brand assets, design research note, target-customer personas from 01 |
| Procedure | 1) Confirm color palette, typography, and imagery style against the brand assets. 2) Define the visual tone (e.g. warm and traditional vs. clean and modern) matched to the persona. 3) Document spacing, button, and component style basics. |
| Tools | Figma, Coolors (palette checking), Google Fonts | 
| Deliverable | Visual design direction / mini style guide draft |
| Owner | Designer |
| Dependency | Task 2.1 |
| Frequency | One-time per project |
| KPI | Direction approved before high-fidelity design begins |
| Quality check | Direction is traceable to brand assets and persona, not the designer's personal preference alone |
| Common mistake | Choosing a generic "corporate" look that doesn't match how the target customer actually relates to the business |
| Estimated complexity | Medium |

### 4. Setup

**Task: Set up the design project and system basics**
| Field | Detail |
|---|---|
| Purpose | Establishes a shared, organized workspace and a basic design system (grid, breakpoints, spacing units) so pages stay consistent |
| Inputs | Visual design direction |
| Procedure | 1) Create the design file in the chosen tool. 2) Set up a grid and mobile/tablet/desktop breakpoints. 3) Build a small component library (buttons, form fields, cards) to reuse across pages. |
| Tools | Figma (free tier sufficient for most SME projects) |
| Deliverable | Design system starter file |
| Owner | Designer |
| Dependency | Task 3.2 |
| Frequency | One-time per project |
| KPI | Component library covers all recurring elements before page design starts |
| Quality check | Components are reused, not redrawn per page |
| Common mistake | Designing each page from scratch without reusable components, causing visual inconsistency and slower development |
| Estimated complexity | Low |

### 5. Production

**Task: Produce low-fidelity wireframes**
| Field | Detail |
|---|---|
| Purpose | Confirms layout and content priority per page before investing in full visual polish |
| Inputs | Navigation structure, conversion goals per page from 01 |
| Procedure | 1) Sketch or wireframe the layout of each key page template (homepage, service/product page, location page, contact page, etc.) in low fidelity. 2) Place the primary call-to-action prominently per the conversion goal for that page. 3) Design mobile layout first, then adapt to desktop. |
| Tools | Figma, pen and paper for initial sketches |
| Deliverable | Wireframe set covering all key page templates |
| Owner | Designer |
| Dependency | Task 4.1 |
| Frequency | One-time per project |
| KPI | Wireframes cover 100% of pages in the sitemap |
| Quality check | Every page's primary call-to-action is visible without scrolling on mobile ("above the fold") |
| Common mistake | Designing desktop-first and treating mobile as an afterthought, when most Ethiopian visitors will arrive on mobile |
| Estimated complexity | Medium |

**Task: Produce high-fidelity visual designs**
| Field | Detail |
|---|---|
| Purpose | Applies the approved visual direction to the approved wireframes to produce the final look of the site |
| Inputs | Approved wireframes, visual design direction, brand assets, images/copy (or placeholders) |
| Procedure | 1) Apply typography, color, and imagery to each wireframed page. 2) Design both mobile and desktop versions of every key template. 3) Ensure calls-to-action, trust signals (reviews, certifications, contact info), and navigation are visually prominent and consistent. |
| Tools | Figma |
| Deliverable | Full visual design set (desktop + mobile) for every key page template |
| Owner | Designer |
| Dependency | Wireframes approved |
| Frequency | One-time per project |
| KPI | All key templates designed in both device sizes |
| Quality check | Contrast and text size checked against accessibility minimums (see H) |
| Common mistake | Designing beautiful but low-contrast text that is hard to read outdoors on a mobile screen — a common real-world usage condition |
| Estimated complexity | High |

### 6. Implementation

**Task: Incorporate approved copy and final imagery into designs**
| Field | Detail |
|---|---|
| Purpose | Placeholder text and stock images rarely fit the same way real copy and real photos do — designs need a final pass once real content is available |
| Inputs | Final or near-final copy from 04, final images/video from 16 or client-supplied assets |
| Procedure | 1) Replace placeholder text with approved copy. 2) Replace placeholder/stock imagery with final photos. 3) Adjust layout where real content length or image proportions differ materially from placeholders. |
| Tools | Figma |
| Deliverable | Content-accurate final design files |
| Owner | Designer, coordinating with copywriter and photographer |
| Dependency | Copy and imagery delivered | 
| Frequency | One-time per project |
| KPI | Zero placeholder ("lorem ipsum" or stock-photo) content remaining in final design files |
| Quality check | Design reviewed once more after content swap, since layouts can break with real content length |
| Common mistake | Sending designs to development still containing placeholder text, leaving developers to guess final wording and spacing |
| Estimated complexity | Medium |

### 7. Testing

**Task: Internal design QA against usability and accessibility standards**
| Field | Detail |
|---|---|
| Purpose | Catches usability and accessibility problems while they are still cheap to fix, before development builds them into code |
| Inputs | Final design files |
| Procedure | 1) Check color-contrast ratios against WCAG AA minimums. 2) Check that tap targets (buttons, links) are large enough for mobile use. 3) Check that the design works with realistic content lengths, not just ideal-case text. 4) Have someone unfamiliar with the project try to complete the primary conversion action using only the designs. |
| Tools | WebAIM Contrast Checker (free), peer walkthrough |
| Deliverable | Design QA checklist, signed |
| Owner | Second designer or account lead (peer review) |
| Dependency | Task 6.1 |
| Frequency | One-time per project |
| KPI | Zero failed accessibility contrast checks on primary text/buttons |
| Quality check | QA checklist completed and issues resolved before client presentation |
| Common mistake | Skipping accessibility checks because the design "looks fine" visually to the designer |
| Estimated complexity | Medium |

### 8. Launch

**Task: Present designs and secure client sign-off, then hand off to development**
| Field | Detail |
|---|---|
| Purpose | Formal sign-off prevents disputes later about what was approved; a clean handoff prevents development from guessing at unclear details |
| Inputs | QA-approved final designs |
| Procedure | 1) Present designs to the client, explaining how they reflect the approved strategy and personas. 2) Capture and incorporate feedback within the agreed number of revision rounds. 3) Obtain written sign-off. 4) Hand off design files, assets, and the style guide to the development team with a live walkthrough. |
| Tools | Meeting, Figma share link, shared drive |
| Deliverable | Signed-off final designs, development handoff package |
| Owner | Account lead and designer |
| Dependency | Task 7.1 |
| Frequency | One-time per project |
| KPI | Sign-off obtained within the agreed revision-round limit |
| Quality check | Development lead confirms the handoff package is complete before design work is considered finished |
| Common mistake | Allowing unlimited informal revision rounds without reference to the contracted scope |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Support development with design QA during the build**
| Field | Detail |
|---|---|
| Purpose | Ensures the live site actually matches the approved design, not an approximation of it |
| Inputs | Development staging site |
| Procedure | 1) Review the staging build against the final design files. 2) Flag visual or spacing discrepancies for correction before launch. |
| Tools | Staging site, design files side by side |
| Deliverable | Design-QA sign-off on the staging build |
| Owner | Designer |
| Dependency | Staging site available (see [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md)) |
| Frequency | One-time per project, before launch |
| KPI | Staging build matches design files with no unresolved discrepancies |
| Quality check | Checked on both mobile and desktop staging views |
| Common mistake | Skipping this step and discovering visual bugs only after the site is already live |
| Estimated complexity | Medium |

### 10. Optimization

**Task: Propose design iterations based on real post-launch behavior**
| Field | Detail |
|---|---|
| Purpose | Design decisions made pre-launch are informed guesses; real visitor behavior after launch shows what actually works |
| Inputs | Analytics/behavior data (see [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md)), CRO findings from [21_CONVERSION_RATE_OPTIMIZATION.md](21_CONVERSION_RATE_OPTIMIZATION.md) |
| Procedure | 1) Review pages with high drop-off or low conversion against their design. 2) Propose specific, testable design changes (not a full redesign) tied to the observed problem. 3) Coordinate implementation with development. |
| Tools | Analytics dashboard, Figma |
| Deliverable | Design-change proposal, tied to evidence |
| Owner | Designer, with CRO/analytics input |
| Dependency | Sufficient post-launch traffic data |
| Frequency | Quarterly, or as CRO findings warrant |
| KPI | Each proposed change ties to a specific, named data point |
| Quality check | Proposal distinguishes a genuine pattern from normal random variation in a small data sample |
| Common mistake | Redesigning based on personal taste rather than actual visitor behavior |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Present design rationale in plain language**
| Field | Detail |
|---|---|
| Purpose | Helps the client understand and defend design decisions (e.g. to staff or partners) rather than treating the design as a black box |
| Inputs | Final design files, research notes |
| Procedure | 1) Summarize why key decisions were made (layout, imagery direction, navigation) in non-technical language. 2) Present alongside the design at Task 8.1 and again with any Task 10.1 proposals. |
| Tools | Summary document or slide |
| Deliverable | Plain-language design rationale summary |
| Owner | Account lead |
| Dependency | Task 8.1 |
| Frequency | At initial delivery and with each significant design update |
| QA | Client can explain back why the primary call-to-action is placed where it is |
| Common mistake | Presenting design purely on aesthetic terms without connecting it to the business goal |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Maintain the style guide and page-template library**
| Field | Detail |
|---|---|
| Purpose | Keeps future pages, campaigns, and content additions visually consistent with the original design without starting from scratch each time |
| Inputs | Final design files, style guide |
| Procedure | 1) Store the style guide and component library in a shared, version-controlled location. 2) Update it whenever the brand or design direction changes. 3) Reuse it for any new page or landing-page request rather than freehand design. |
| Tools | Figma with shared library, shared drive |
| Deliverable | Current style guide and template library |
| Owner | Designer |
| Dependency | Ongoing |
| Frequency | Ongoing / as-needed |
| KPI | New pages/campaigns built without introducing an off-brand inconsistency |
| Quality check | Spot-check new deliverables against the style guide |
| Common mistake | Letting each new landing page or promotional page drift stylistically from the core site |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Detailed information architecture / navigation structure
- Low-fidelity wireframes for all key page templates
- High-fidelity visual designs (desktop and mobile) for all key page templates
- Mini style guide / design system reference

**Quarterly deliverables**
- None by default; design-change proposals occur as evidence warrants (see Task 10.1), not on a fixed calendar

**Optional add-ons**
- Clickable prototype for stakeholder walkthroughs before development
- Additional page templates beyond the original scope (e.g. new location pages, campaign landing pages)
- Seasonal/promotional design refreshes

**Monthly deliverables:** none by default — design work concentrates upfront, with the design system maintained on an as-needed basis afterward (see Task 12.1).

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Wireframes/designs approved within the agreed revision-round limit | Leading | Directly attributable — internal process metric |
| Accessibility contrast checks passed | Leading | Directly attributable |
| Staging build matches design with no unresolved discrepancies | Leading | Directly attributable |
| Bounce rate on key pages post-launch | Lagging | Influenced by traffic quality/source, not design alone |
| Conversion rate on primary call-to-action post-launch | Lagging | Shared influence with copywriting, offer, and development execution — do not attribute solely to design |
| Mobile vs. desktop conversion gap | Lagging | Useful diagnostic, but confirm it reflects design/usability rather than a traffic-source difference before acting on it |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | Figma (free tier), Google Fonts, WebAIM Contrast Checker, Coolors (free tier) | Sufficient for the large majority of SME website designs |
| Low-cost | Figma paid tier (for larger teams/version history needs), Canva Pro | Useful once the agency runs multiple concurrent projects |
| Professional | Adobe Creative Cloud (Photoshop, Illustrator, XD) | Justified for heavier custom-illustration or advanced brand work, not required for standard SME sites |
| Low-bandwidth / mobile-first delivery | Exported PNG/PDF design previews shareable over WhatsApp/email for clients who cannot comfortably review an interactive Figma file on a slow connection | Matches how many Ethiopian SME decision-makers will actually review the work |

## H. Risks and Common Failure Modes

- **Technical risk:** designing without accounting for real content length (long service names, long Amharic text strings) causes layouts to break once real content is inserted.
- **Platform risk:** designing a feature or interaction that the platform recommended in strategy cannot actually support, discovered only during development.
- **Client-related risk:** slow, unclear, or unlimited-round feedback cycles stall the project — manage this with the revision-round limit stated in the contract (see [../operations/05_PROPOSALS_AND_CONTRACTING.md](../operations/05_PROPOSALS_AND_CONTRACTING.md)).
- **Data and access risk:** using images or fonts without proper licensing exposes the client to legal risk; confirm licensing on every non-original asset used.
- **Reputation risk:** a generic, templated-looking design that doesn't differentiate the business, or an inaccessible design that excludes visitors with visual impairments.
- **Security risk:** minimal at the design stage, but shared design files should still be access-controlled (see [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md)) to protect unreleased brand work.
- **Legal or compliance risk:** image usage rights, model releases for any people shown, and — for ⚠️-flagged segments (healthcare, finance) — avoiding misleading visual claims (e.g. unverifiable before/after imagery).
- **Measurement and attribution risk:** crediting or blaming design alone for post-launch conversion results without accounting for copywriting, traffic quality, and offer strength.

## I. Standard Operating Procedure

- [ ] Strategy document confirmed signed off; design-readiness checklist completed
- [ ] Design/usability research on comparable sites completed
- [ ] Navigation structure and information architecture defined and mapped to the full sitemap
- [ ] Visual design direction approved before high-fidelity work begins
- [ ] Design system / component basics set up
- [ ] Wireframes produced for every key page template, mobile-first
- [ ] High-fidelity visual designs produced for every key page template (desktop and mobile)
- [ ] Placeholder copy and images replaced with final or near-final content
- [ ] Internal accessibility and usability QA completed and issues resolved
- [ ] Client sign-off obtained within the agreed revision-round limit
- [ ] Development handoff package delivered with a live walkthrough
- [ ] Staging build QA'd against final design files before launch
- [ ] Style guide and template library stored in a shared, version-controlled location