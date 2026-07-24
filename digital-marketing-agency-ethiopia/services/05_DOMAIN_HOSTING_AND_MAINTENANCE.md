# Service: Domain, Hosting, and Maintenance

## A. Service Definition

**What it is.** The ongoing service that keeps a live website online, secure, backed up, updated, and performing correctly after [03_WEBSITE_DEVELOPMENT.md](03_WEBSITE_DEVELOPMENT.md)'s initial build and launch are complete: uptime monitoring, backups, software updates, security scanning, domain/SSL/hosting renewal, broken-link and form checks, and monthly reporting.

**What business problem it solves.** An unmaintained website quietly decays: CMS and plugin software goes out of date and becomes a security target, backups stop being current, domains or SSL certificates lapse and take the site offline entirely, and small breakages (a dead link, a broken form) go unnoticed until a customer complains — or simply gives up and doesn't.

**Why a customer would pay for it.** Prevention is far cheaper than recovery. A hacked, defaced, or offline site costs far more in emergency recovery work, lost leads, and reputational damage than the cost of ongoing maintenance. A lapsed domain can, in the worst case, be lost entirely to another registrant.

**Business types that benefit most.** Any business with a live website, in direct proportion to how much the business actually depends on that site for leads or sales — see [../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md](../market-mapping/06_SERVICE_TO_SEGMENT_MATCHING.md). E-commerce and higher-traffic sites need this most urgently; a simple brochure site for a low-digital-dependence business still needs at minimum domain/SSL renewal and basic security patching to avoid going dark.

**What this service does not include.** The initial website build (03), new visual design work (02), new page development, or major feature additions — these are treated as new scope, priced and delivered separately, not folded into routine maintenance. Ongoing copy edits beyond minor factual corrections are coordinated with [04_WEBSITE_COPYWRITING.md](04_WEBSITE_COPYWRITING.md) Task 12.1, not duplicated here.

**How it connects to other services.** Directly continues from 03's setup work. The site's technical health here is a precondition for [06_TECHNICAL_SEO.md](06_TECHNICAL_SEO.md) performing well, and uptime/speed data feeds [24_ANALYTICS_TRACKING_AND_REPORTING.md](24_ANALYTICS_TRACKING_AND_REPORTING.md).

## B. Desired Business Outcomes

| Level | Example |
|---|---|
| Activity | Monitoring uptime, running backups, applying updates, scanning for security issues, renewing domain/hosting/SSL, checking links and forms |
| Output | Uptime logs, backup logs, update logs, monthly maintenance report |
| Outcome | The site stays online, secure, and fully functional continuously, without the business owner needing technical knowledge to notice or fix problems |
| Financial impact | Avoided cost of emergency recovery from a hacked or offline site; avoided lead loss from broken forms/links going unnoticed; avoided (in the worst case) permanent loss of the domain itself |

## C. Inputs Required From the Client

- Access to hosting, domain registrar, and CMS admin (or a clear delegation of renewal authority if the agency manages these on the client's behalf — ownership stays with the client per [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md))
- A valid payment method/authorization for domain, hosting, and SSL renewals, and clarity on who is billed
- Confirmation of the maintenance package scope and cadence
- An agreed process for urgent/emergency issue escalation (who to contact, how fast a response is expected)
- Advance notice if the client or client's staff makes direct changes to the site outside the agency's process, so maintenance records stay accurate

## D. Detailed Task Breakdown

### 1. Preparation

**Task: Onboard the site into the maintenance program**
| Field | Detail |
|---|---|
| Purpose | Ensures a clean, documented handoff from the one-time build to ongoing care, with nothing assumed or missed |
| Inputs | Completed website build (03, Task 12.1) |
| Procedure | 1) Confirm access to hosting, domain registrar, and CMS admin. 2) Record all current account details, renewal dates, and current software versions in the agency's maintenance tracker. 3) Confirm the agreed maintenance package and cadence with the client in writing. |
| Tools | Maintenance-tracking spreadsheet or CRM, password manager |
| Deliverable | Completed onboarding record |
| Owner | Maintenance lead |
| Dependency | 03, Task 12.1 |
| Frequency | One-time per client |
| KPI | Onboarding record completed within 5 business days of build handoff |
| Quality check | All renewal dates (domain, SSL, hosting) verified directly in the relevant account, not assumed from memory |
| Common mistake | Failing to record an upcoming renewal date, discovering the lapse only when the site goes offline |
| Estimated complexity | Low |

### 2. Research

**Task: Audit the current technical baseline**
| Field | Detail |
|---|---|
| Purpose | Establishes a starting point (software versions, current speed, current security posture) to measure future maintenance work against |
| Inputs | Live site access |
| Procedure | 1) Record current CMS, theme, and plugin versions. 2) Run a baseline speed test. 3) Run a baseline security scan. 4) Note any pre-existing issues found. |
| Tools | CMS admin panel, Google PageSpeed Insights, a security-scanning plugin/service |
| Deliverable | Baseline technical audit report |
| Owner | Maintenance lead |
| Dependency | Task 1.1 |
| Frequency | One-time per client (repeated after any major platform migration) |
| KPI | Baseline report completed and stored before the first maintenance cycle begins |
| Quality check | Any pre-existing issue found is flagged to the client immediately, not silently absorbed into "maintenance" |
| Common mistake | Skipping the baseline and later being unable to tell whether an issue is new or pre-existing |
| Estimated complexity | Low |

### 3. Strategy

**Task: Define the maintenance cadence and escalation process**
| Field | Detail |
|---|---|
| Purpose | Sets clear expectations for what happens on what schedule, and what happens when something urgent breaks |
| Inputs | Agreed maintenance package |
| Procedure | 1) Document the routine cadence (e.g. weekly backup checks, monthly updates, monthly report). 2) Define what counts as an emergency (site down, hacked, forms broken) versus routine. 3) Document the escalation path and expected response time for emergencies. |
| Tools | Shared document |
| Deliverable | Maintenance cadence and escalation document |
| Owner | Maintenance lead, account lead |
| Dependency | Task 2.1 |
| Frequency | One-time per client (revisited if the package changes) |
| KPI | Document shared with and acknowledged by the client |
| Quality check | Escalation response time is realistic and actually deliverable by the agency's staffing |
| Common mistake | Promising a faster emergency response time than the agency can consistently deliver |
| Estimated complexity | Low |

### 4. Setup

**Task: Configure monitoring, backup automation, and renewal reminders**
| Field | Detail |
|---|---|
| Purpose | Automates the routine detection work so problems are caught by a system, not by hoping someone remembers to check |
| Inputs | Baseline audit, cadence document |
| Procedure | 1) Set up automated uptime monitoring with alerting. 2) Configure automated, scheduled backups with off-site storage. 3) Set up security-scan automation where available. 4) Set calendar reminders well ahead of every domain, hosting, and SSL renewal date. |
| Tools | UptimeRobot (free tier) or equivalent, hosting/CMS backup automation, security-scan plugin/service, shared calendar |
| Deliverable | Active monitoring, backup, and renewal-reminder setup |
| Owner | Maintenance lead |
| Dependency | Task 3.1 |
| Frequency | One-time per client |
| KPI | Monitoring and backups confirmed active with a successful first test run |
| Quality check | Renewal reminders set at least 30 days ahead of expiry, not on the expiry date itself |
| Common mistake | Setting a renewal reminder for the exact expiry date, leaving no buffer if a payment issue arises |
| Estimated complexity | Medium |

### 5. Production

**Task: Document the backup-restore procedure**
| Field | Detail |
|---|---|
| Purpose | A backup that has never been tested for restoration is not a reliable backup |
| Inputs | Backup system configuration |
| Procedure | 1) Perform a test restore of a backup to a staging environment. 2) Document the exact steps required to restore in an emergency. 3) Confirm the restored version matches the live site. |
| Tools | Staging environment, backup system |
| Deliverable | Tested, documented backup-restore procedure |
| Owner | Maintenance lead |
| Dependency | Task 4.1 |
| Frequency | One-time per client, then re-verified quarterly |
| KPI | Successful test restore completed |
| Quality check | Restore tested on staging, never on the live site |
| Common mistake | Assuming backups work without ever actually testing a restore, discovering a failure only during a real emergency |
| Estimated complexity | Medium |

### 6. Implementation

**Task: Apply routine CMS, plugin, and theme updates**
| Field | Detail |
|---|---|
| Purpose | Outdated software is the most common way sites get compromised; routine updates close known vulnerabilities |
| Inputs | Update notifications from the CMS/plugin vendors |
| Procedure | 1) Review available updates. 2) Apply updates on a staging copy first. 3) Test the staging site for breakage. 4) Apply to the live site once confirmed safe. 5) Log the update. |
| Tools | Staging environment, CMS admin panel |
| Deliverable | Updated, tested live site |
| Owner | Maintenance lead |
| Dependency | Task 4.1 |
| Frequency | Monthly, or immediately for a critical security patch |
| KPI | No update applied directly to the live site without a staging test first, except for a confirmed critical security emergency |
| Quality check | Site functionality spot-checked after every update (forms, key pages, integrations) |
| Common mistake | Applying an update directly to the live site to save time, then discovering it broke a plugin or integration |
| Estimated complexity | Medium |

### 7. Testing

**Task: Monthly form, link, and speed test pass**
| Field | Detail |
|---|---|
| Purpose | Confirms the site's key functions still work correctly, since integrations and links can silently break over time (e.g. an API changes, a linked page is deleted elsewhere) |
| Inputs | Live site |
| Procedure | 1) Submit a real test entry through every lead-capture form. 2) Click every WhatsApp/telephone link on a real device. 3) Run a sitewide broken-link check. 4) Run a page-speed test and compare against the baseline. |
| Tools | Broken-link checker tool, Google PageSpeed Insights, real device testing |
| Deliverable | Monthly functional-test log |
| Owner | Maintenance lead |
| Dependency | Task 6.1 |
| Frequency | Monthly |
| KPI | All forms and links confirmed working every month |
| Quality check | Test performed with a real submission/click, not just a visual check |
| Common mistake | Assuming a form still works because it "looks fine," missing a silent backend failure that stopped submissions from arriving |
| Estimated complexity | Low |

### 8. Launch

**Task: Activate the maintenance program and confirm with the client**
| Field | Detail |
|---|---|
| Purpose | Formally starts the ongoing service so both sides know exactly when responsibility began and what is covered |
| Inputs | Completed setup (Tasks 4–5) |
| Procedure | 1) Confirm all monitoring, backups, and renewal reminders are active. 2) Send the client written confirmation that the maintenance program has started, what it covers, and the escalation contact. |
| Tools | Confirmation document/email |
| Deliverable | Signed-off maintenance activation confirmation |
| Owner | Account lead |
| Dependency | Tasks 4.1–5.1 |
| Frequency | One-time per client |
| KPI | Confirmation sent and acknowledged before the first invoice for maintenance |
| Quality check | Confirmation explicitly states what is and is not covered, to prevent scope disputes later |
| Common mistake | Starting to bill for maintenance before monitoring/backups are actually active |
| Estimated complexity | Low |

### 9. Monitoring

**Task: Continuous uptime and security monitoring**
| Field | Detail |
|---|---|
| Purpose | Detects an outage or intrusion as early as possible, minimizing downtime and damage |
| Inputs | Active monitoring tools |
| Procedure | 1) Monitoring tools check the site automatically at short intervals. 2) Any alert triggers immediate review against the escalation process from Task 3.1. 3) Confirm resolution and log the incident. |
| Tools | UptimeRobot or equivalent, security-scan alerts |
| Deliverable | Uptime and security log |
| Owner | Maintenance lead |
| Dependency | Task 4.1 |
| Frequency | Continuous/automated, reviewed daily |
| KPI | Alerts acknowledged within the agreed escalation response time |
| Quality check | Every alert has a logged resolution, not left open indefinitely |
| Common mistake | Configuring alerts but not actually routing them to someone who checks regularly |
| Estimated complexity | Low |

**Task: Monitor site speed trends**
| Field | Detail |
|---|---|
| Purpose | Sites tend to slow down gradually as content, plugins, and media accumulate — catching this early prevents a slow decline into a poor user experience |
| Inputs | Baseline speed data, ongoing PageSpeed/Core Web Vitals data |
| Procedure | 1) Re-run a speed test on a regular cadence. 2) Compare against the baseline and the previous check. 3) Flag any material decline for the optimization task below. |
| Tools | Google PageSpeed Insights, Search Console Core Web Vitals report |
| Deliverable | Speed-trend log |
| Owner | Maintenance lead |
| Dependency | Task 2.1 |
| Frequency | Monthly |
| KPI | Any decline beyond an agreed threshold flagged within the same monthly cycle |
| Quality check | Compared against the same testing conditions each time for a fair comparison |
| Common mistake | Not noticing a slow, steady speed decline because each individual monthly check looks only marginally worse than the last |
| Estimated complexity | Low |

### 10. Optimization

**Task: Periodic performance and housekeeping cleanup**
| Field | Detail |
|---|---|
| Purpose | Removes accumulated bloat (unused plugins, oversized media, orphaned pages) that gradually degrades speed and increases security surface area |
| Inputs | Speed-trend log, plugin/media inventory |
| Procedure | 1) Review installed plugins/themes and remove any that are unused or unmaintained by their developer. 2) Re-compress or replace oversized media. 3) Re-test speed after cleanup. |
| Tools | CMS admin panel, image-compression tools |
| Deliverable | Cleaned-up, re-tested site |
| Owner | Maintenance lead |
| Dependency | Task 9.1 (speed monitoring) |
| Frequency | Quarterly |
| KPI | Measurable speed improvement or confirmed no further easy gains available |
| Quality check | Site functionality re-tested after removing any plugin, in case of a hidden dependency |
| Common mistake | Removing a plugin without checking whether another feature silently depends on it |
| Estimated complexity | Medium |

### 11. Reporting

**Task: Deliver the monthly maintenance report**
| Field | Detail |
|---|---|
| Purpose | Gives the client visibility into work that is otherwise invisible — maintenance is easy to undervalue if the client never sees evidence of it |
| Inputs | Update log, backup log, uptime/security log, functional-test log, speed-trend log |
| Procedure | 1) Compile the month's uptime percentage, updates applied, backup status, security scan results, and functional test results. 2) Present in plain language with any issues found and resolved highlighted. 3) Send on a consistent monthly date. |
| Tools | Report template (see [../templates/07_MONTHLY_REPORT_TEMPLATE.md](../templates/07_MONTHLY_REPORT_TEMPLATE.md)) |
| Deliverable | Monthly maintenance report |
| Owner | Account lead |
| Dependency | Tasks 6–10 for that month |
| Frequency | Monthly |
| KPI | Report delivered on the same date each month without exception |
| Quality check | Report reviewed for accuracy against the underlying logs before sending |
| Common mistake | Sending a generic report that doesn't reflect what actually happened that specific month |
| Estimated complexity | Low |

### 12. Maintenance

**Task: Renew domain, hosting, and SSL before expiry**
| Field | Detail |
|---|---|
| Purpose | The single most damaging and most avoidable failure in this service — a lapsed domain or SSL certificate can take the site fully offline or, worse, allow the domain to be lost to another registrant |
| Inputs | Renewal reminders from Task 4.1 |
| Procedure | 1) Confirm renewal cost and payment authorization with the client well ahead of the deadline. 2) Process the renewal. 3) Confirm the renewal was successful by checking the account directly. 4) Update the renewal date record. |
| Tools | Domain registrar, hosting provider, SSL provisioning |
| Deliverable | Confirmed, successful renewal |
| Owner | Maintenance lead |
| Dependency | Task 4.1 reminder trigger |
| Frequency | Per each renewal cycle (varies by domain/hosting/SSL term) |
| KPI | Zero lapsed domains, hosting accounts, or SSL certificates |
| Quality check | Renewal confirmed directly in the account, not assumed from a payment receipt alone |
| Common mistake | Waiting until the renewal deadline to contact the client for payment authorization, risking a lapse if they are unreachable |
| Estimated complexity | Low |

**Task: Apply minor content updates within scope**
| Field | Detail |
|---|---|
| Purpose | Small factual corrections (a changed phone number, a corrected typo, an updated opening hour) should not require a separate project engagement |
| Inputs | Client-submitted change requests |
| Procedure | 1) Confirm the request is a minor factual update within the maintenance package's scope, not a new feature or design change. 2) Apply the update. 3) Verify it displays correctly. |
| Tools | CMS admin panel |
| Deliverable | Applied, verified content update |
| Owner | Maintenance lead |
| Dependency | Ongoing |
| Frequency | As-needed |
| KPI | Minor updates applied within the agreed turnaround time (e.g. 2 business days) |
| Quality check | Update verified live, not just saved in the CMS |
| Common mistake | Scope creep — treating a request for a new page or redesign as a "minor update" instead of a separately scoped project |
| Estimated complexity | Low |

## E. Deliverables

**Initial deliverables**
- Baseline technical audit report
- Maintenance cadence and escalation document
- Active monitoring, backup, and renewal-reminder setup
- Tested, documented backup-restore procedure

**Monthly deliverables**
- Updates applied (with staging-tested verification)
- Functional test log (forms, links, speed)
- Monthly maintenance report

**Quarterly deliverables**
- Performance and housekeeping cleanup
- Backup-restore procedure re-verification

**Optional add-ons**
- Emergency incident response / hacked-site recovery (typically priced separately from routine maintenance given its urgency and variable scope)
- Major platform/version migrations
- Expanded backup retention or additional staging environments

## F. KPIs

| KPI | Type | Attribution caution |
|---|---|---|
| Updates applied on schedule, staging-tested first | Leading | Directly attributable |
| Backups completed successfully each cycle | Leading | Directly attributable |
| Monitoring alerts acknowledged within the agreed response time | Leading | Directly attributable |
| Renewals processed with zero lapses | Leading | Directly attributable |
| Actual uptime percentage | Lagging | Partly dependent on the hosting provider's own reliability, not solely the agency's actions |
| Site speed / Core Web Vitals trend | Lagging | Also affected by content and media added by the client or other services over time |
| Time-to-resolution for reported issues | Lagging | Directly attributable within the agency's control once an issue is reported |

## G. Tools

| Category | Tools | Notes |
|---|---|---|
| Free | UptimeRobot (free tier), Google Search Console (crawl-error alerts), Google PageSpeed Insights, built-in CMS update notifications | Sufficient baseline monitoring for most SME sites |
| Low-cost | Paid uptime-monitoring tiers with more frequent checks, backup plugins with off-site storage | Worth the upgrade once a site has meaningful traffic or revenue dependence |
| Professional | Managed hosting with built-in security/backup/update handling, dedicated malware-scanning services | Justified for higher-traffic, e-commerce, or higher-risk sites |
| Low-bandwidth / mobile-first consideration | Schedule non-urgent updates during low-traffic periods to avoid disrupting visitors, and keep the live site's own resource weight low so maintenance work doesn't itself degrade the mobile experience | Directly protects the real-world visitor experience the whole system is meant to serve |

## H. Risks and Common Failure Modes

- **Technical risk:** an update breaking site functionality if applied directly to the live site without a staging test first.
- **Platform risk:** hosting-provider outages or policy changes outside the agency's direct control — mitigate with a reliable provider and clear client communication when this occurs.
- **Client-related risk:** a client not authorizing a renewal payment in time, or a client's staff making direct, unrecorded changes to the site that maintenance logs then don't reflect.
- **Data and access risk:** losing access if the client changes a password without informing the agency — reinforce the access-management process in [../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md](../operations/14_SECURITY_AND_ACCESS_MANAGEMENT.md).
- **Reputation risk:** a hacked, defaced, or offline site reflects on the agency regardless of the specific root cause, since the client's expectation is that maintenance prevents exactly this.
- **Security risk:** outdated plugins/themes remain the most common real-world vulnerability vector — this is the single highest-priority routine task in this service.
- **Legal or compliance risk:** if the site collects customer data and a security incident occurs, applicable data-handling and breach-notification obligations must be checked (see [../operations/15_LEGAL_COMPLIANCE_AND_RISK.md](../operations/15_LEGAL_COMPLIANCE_AND_RISK.md)).
- **Measurement and attribution risk:** third-party monitoring tools measure uptime from their own checkpoints, which can differ slightly from what a real visitor in Ethiopia actually experiences — treat monitoring data as a strong indicator, not an infallible one.

## I. Standard Operating Procedure

- [ ] Site onboarded into the maintenance program with access and renewal dates confirmed
- [ ] Baseline technical audit completed (versions, speed, security)
- [ ] Maintenance cadence and escalation process documented and shared with the client
- [ ] Uptime monitoring, automated backups, security scanning, and renewal reminders active
- [ ] Backup-restore procedure tested and documented
- [ ] Maintenance program activation confirmed in writing with the client
- [ ] Updates applied monthly, staging-tested before going live
- [ ] Monthly functional test (forms, links, speed) completed
- [ ] Speed trend monitored monthly; quarterly housekeeping cleanup performed
- [ ] Monthly maintenance report delivered on a consistent date
- [ ] Domain, hosting, and SSL renewals processed with zero lapses
- [ ] Minor content updates applied within the agreed turnaround time, with scope creep redirected to a new project