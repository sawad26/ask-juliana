# Juliana Knowledge Base
*Last updated: Sep 15, 2026 — from Sep 8 Les 1:1, Sep 8 Davis Quick Sync, Sep 8 Juliana Weekly, Sep 9 Michael & Shadi Touchbase, and Gmail (Sep 6–12)*

---

## What Is Juliana

Juliana is an embedded care delivery model that deploys a multidisciplinary pod inside hospitals to manage polychronic, high-utilizer inpatients. It is built on the VICP (Vanderbilt Interdisciplinary Care Program) and is not a SaaS product. It is a B2B clinical operating model sold as a service to health systems.

Positioning: partner, not vendor. The pod operates inside the hospital but is directed by Juliana. The health system provides the unit; Juliana provides the operating model, the operator, and the governance structure.

---

## The Clinical Model

The pod is deployed inside a hospital on a dedicated unit. It is non-negotiable on Day 1 — all roles must be present at launch.

**Juliana standard pod (Michael-approved, all new sites):**
- Physician (one designated as local site medical director)
- Advanced practice provider (NP or PA)
- Pharmacist
- Behavioral health / psych (PMH-APRN)
- Registered nurses (RNs)
- Charge nurse
- Social worker
- Case manager
- Clinical Implementation Director (Juliana-employed)
- Program Manager (Juliana-employed)

Note: The VICP pod at Vanderbilt is the proof-of-concept model only — not the deployment template. Role mix at any given site may vary; this list is the canonical starting point for new sites.

Operating structure:
- Shared workroom on patient unit (Command Center)
- Near 100% bedside rounds
- Daily discharge huddle
- A team: 10–12 patients, handles admissions
- B team: 6–8 patients, afternoon clinic
- Night float covers after 7pm; nocturnist follows care plan; 7am huddle handoff
- Team is the continuity vehicle, not individual providers

---

## Patient Cohort

Standard cohort criteria (starting point, not a mandate — health systems can modify):
- HCC 2–2.999 + 2 or more unscheduled admissions per year, OR
- HCC 3+ + 1 or more unscheduled admission per year
- Minimum 60 patients at go-live

Exclusion criteria are site-specific. The VICP exclusion list is Vanderbilt-infrastructure-specific and does not automatically apply elsewhere. Behavioral health diagnoses including schizophrenia and substance abuse are NOT categorically excluded. Evaluate specialty service coverage at each new site before applying any exclusions.

Two enrollment pathways: monthly team referral review + proactive SW screening of admitted patients.

---

## Proven Outcomes (VICP)

### Published / External-Safe Figures
- 21% reduction in length of stay
- 23% reduction in recurrent admissions
- 6,300+ bed-days recovered
- 900 patients enrolled

### Per Michael's Sep 9 Suggestions (Michael & Shadi Touchbase)

**Unadjusted LOS:** 0.83-day reduction (no crossing of confidence intervals). Sourced from Epic Slicer Dicer; in forthcoming manuscript. Michael suggests using this for bed-day calculations — NOT the dashboard RLOS, which carries an unexplainable hospital-applied cofactor that cannot be unadjusted. Davis does not distinguish between the two; Michael is the sole authority on LOS methodology.

**Hazard ratio for recurrent hospitalizations:** 0.77 (post-enrollment VICP population, adjusted).

**Hospitalization volume for calculations:** Two options: (1) EBM benchmark — 3.29 total hospitalizations × 0.77 hazard ratio; (2) actual admission numbers from Davis's operational metrics PowerPoint. Michael prefers whole population since program inception.

**Bed-day formula per Michael:** 3.29 admissions × 6.66 avg LOS × 18% LOS reduction = bed days saved per patient per year. 18% replaces prior 20%.

**Hospitalization framing for external use:** Michael's peer-reviewed manuscript (now accepted) shows 23% improvement vs. expected baseline — without VICP, hospitalizations would be ~40% higher. Two options on any external doc: (1) cite the 23% peer-reviewed figure, or (2) drop the metric entirely. A one-pager is too tight to explain without the benchmark context.

**Total cost of care:** Confirmed unreliable for external use. VUMC's total cost figure is billed charges (Epic-based), not payer collections. Excluded from all external documents.

**External language standard:** "patients cared for on the VICP unit" — not "VICP enrollees." ~80% of unit patients are enrollees; the distinction is conservative by ~20%.

### Internal Metrics (NOT for external use — full dataset ~2,500 patients)
- 20% decrease in admissions vs. expected baseline
- 65% drop in ED visits post-enrollment
- ~40% decrease in 7-day readmission rate (26.5% to 11%)
- Significant LOS reduction
- 30% drop in total cost of care per patient
- Deceased patients excluded; numbers confirmed not artificially inflated
- 12-month numbers stronger than 36-month (expected for elderly, high-acuity population)

### DRG-Risk Value Stream (CFO-ready for FFS hospitals)
Medicare pays a fixed amount per DRG. If a hospital's average LOS for a DRG exceeds the Medicare benchmark, they lose money per case. Plan: pull top 20 DRGs for VICP cohort, identify DRGs where LOS exceeds benchmark, cross-reference with VICP's LOS impact = direct, bottom-line FFS savings attributable to VICP. Davis and Derrick Anderson's team working on this.

### Cohorted Analysis
Enrolled vs. eligible-but-unenrolled analysis still pending. Needed to fully validate admission reduction claim. Pursuing via CJ Stimpson's analytics org at VUMC.

---

## Commercial Model

### Standard Structure (all non-MacNeal clients)
- Two-tier PMPM: enrolled rate (FTE cost + thin margin) + ~20% activation step-up when patient has active care plan
- Plus 25% of validated savings above baseline
- 90-day ramp option available
- Shared savings split: 75/25 (hospital/Juliana) for all fee-bearing clients

### MacNeal Exception (50/50 IFV split, fully deferred fees)
- MacNeal provides all clinical resources; Juliana provides PM + Analyst + IP + operating model
- 100% of fees at risk (deferred); 50/50 split on Incremental Financial Value
- Five contractually confirmed value streams: total cost of care, LOS, readmissions, ED visits, falls/HAIs, site-specific payer contract bonus pools
- 36-month term; LOI non-binding

### PMPM Trigger
$400 PMPM = first Juliana provider clinical note (consult or H&P). Active status persists once care plan is built.

### Physician Lease Mechanism
Retired entirely. Do not reference or suggest this structure.

### Three-Tier FTE Staffing Scenarios
- **Tier 1:** Juliana employs PM + Analyst; hospital provides physician, APP, SW, CM (MacNeal model)
- **Tier 2:** Juliana employs PM + Analyst + SW + CM; hospital provides physician and APP
- **Tier 3:** Juliana employs everything except physician + APRN (~40% of pod cost); proposed 75/25 shared savings split

Notes: PMH-APRN is NOT in any tier (clinical role). Pharmacist is NOT in Tier 2. Staffing is fixed to unit capacity from Day 1, not patient volume. Bed count is the limiting constraint. ICP focus: clients who can supply their own physician and APP.

### Commercial Language Blocker
Do NOT finalize PMPM language in the playbook or investor materials until Patrick's CFO no-risk model notes are received. This is an active blocker.

---

## Governance Model (agreed Aug 25, 2026)

Three tiers:
1. **Working group** — day-to-day clinical self-arbitration
2. **Clinical steering committee** — joint Juliana + health system; outcomes, outlier cases, operational friction; weekly or biweekly; finance (both sides) + clinical program lead + VBC contracting lead
3. **Executive committee** — CFOs + contracting leads; monthly; results review + transparency

Open question (tabled for Michael + Patrick): if Juliana fills a clinical role the health system can't staff, how does accountability/escalation change?

---

## Repeatable Engagement Workflow

10 phases:
- Phase 0: NDA
- Phase 1: Engagement Call + Cohort Agreed
- Phase 2A: Stage 1 Data Request
- Phase 2B: Stage 1 Analysis
- Phase 3: Cohort Selection Gate
- Phase 4A: Stage 2 Data Request (DUA fully executed gate)
- Phase 4B: Stage 2 Analysis
- Phase 5: Baseline Lock
- Phase 6: Pilot Launch
- Phase 7: Post-Launch Review (30/60/90-day)

Document architecture: Workflow = process map only. Data Request Template = inputs. Internal Analysis Guide = method. Client-facing memo/heatmap = output.

---

## Market Size

**TAM:** ~$10.2B (VUMC ratio 6.92 eligible pts/staffed bed × 307,611 beds across 687 qualifying hospitals × $400 PMPM × 12). Unresolved numerator discrepancy (Michael cited 2,200 vs. Davis 3,700 vs. model's 4,333) — TAM range $7.8B–$11.5B until confirmed. Shared savings and $150 enrolled PMPM excluded from headline.

**SAM:** Development paused pending Les and Patrick input on three open questions: (1) does Juliana target hospitals directly or health system relationships? (2) do early commercial conversations validate/invalidate ICP filters? (3) should near-term geography shrink SAM to regional deployable universe?

**SOM:** 1-2-4-7-11 client ramp, ~$7M yr1 / ~$78M yr5 PMPM only.

---

## BD Pipeline (Current as of Sep 15, 2026)

**MacNeal (Trinity Health, Berwyn IL)** — LOI sent Aug 24; in-person with Chuck Aug 26. Sep 11 update: Patrick sent directional capacity assessment to Charles Bareis (chuck, trinity-health.org) — LOS/capacity only, 500-patient cohort, Phase 1 framing. Based on public Medicare/cost report data + Vanderbilt results. Phase 2 will layer quality incentives, contracts, TCC. Shared internally Sep 12; Les and Mark responded positively. Chuck's response still pending. Cohort list (7–10 from Chuck) still pending. Conflict flag: Endeavor Health (MacNeal parent) co-led Lumeris's April 2024 $100M equity raise — Patrick to ask Chuck about the Endeavor–Lumeris relationship.

**Franciscan Alliance** — Confirmed Sep 21, 3–4 PM ET with Michael Englehart and Brandy Bukowski. Deb and Michael both on the call. Previously last-minute canceled; now rescheduled. Lumeris co-pitch being explored (Patrick has deep relationship with Rick). NDA status not confirmed resolved — confirm before meeting. 13 hospitals via Millennium Physicians/Evolent is the opportunity.

**Vanderbilt (VUMC)** — MSA signed Jul 24. Engagement framework ~95% complete (Olivia signed off). Preferred structure: Juliana manages entire expanded unit (~1,000 patients, phased ~200/month). Unit currently at capacity (24 patients for 16 beds); referrals temporarily shut down. Associate chief of staff independently raising expansion with adult hospital CEO. Davis and Olivia pursuing meetings with adult hospital CEO, Warren Sandberg (Chief of Staff), and chief of staff. Warren Sandberg alignment still needed before C-suite return. DRG risk analysis in progress (Davis/Derrick Anderson). Deb drafting 1–2 pager for C-suite. Contract undrafted. Hospital Medicine becoming its own division July 1, 2027.

**Mercy Health Virginia** — Call held Aug 13; CFO in room. Follow-up window closed ~Aug 27; status needs confirming.

**Rush** — Patrick has Garcia's cell; dinner planned. No meeting yet. Lead, not yet active pipeline.

**Lumeris** — Meeting held Aug 28. VBC enabler, Evolent investor; channel partner opportunity. Same Endeavor Health investor as MacNeal — flag before deepening.

**LEK Group** — Patrick met solo Sep 2 night. Outcome not yet reported back.

**UCSF / Amy Liu** — Chief Quality Officer; was on vacation; waiting for return and reply. Virtual call being scheduled. Michael to loop in Shadi when conversation advances.

**Angelo Pirrozi (BDO partner) / NYP** — Patrick had lunch Sep 8 Palm Beach. Thursday deck walk-through confirmed. Ready to tee up to NYP and potentially others.

**Sandbox / Jeff Carrol** — Meeting confirmed Sep 11. Les intro. Leah to update team.

**AdvisoryTrust (Jeff and Merle)** — Merle met Dave Rayford (retired VUMC chief of staff) for intros to Cookville Regional and Murray. Lunch scheduled September 20. ~20 health system pipeline. Equity vs. rev-share counter still pending.

**Advocate Health** — NDA not yet signed; Patrick assessing value vs. time.

**BayCare, Powers Health, Paul Butler (Spartanburg Regional), Carrie Mueller (OhioHealth)** — Still in pipeline.

**Blue Venture Fund** (BCBS-affiliated LP network) — Expressed interest; relationship-building, not a formal investor pitch.

---

## Investor-Facing Positioning

**Pro forma scope (strategy set Sep 2, 2026):** ONE investor-facing version, anchored only to LOS + readmission data. Lead with bed days saved. National LOS benchmarks, conservative 1-day reduction assumption. Falls, HAIs, VBC/MSSP/TCC held as Tier 2 placeholders until Juliana has its own outcome data. Shared savings 75/25 standard (Juliana/hospital); MacNeal 50/50 confirmed exception. Do NOT finalize commercial language until Patrick's CFO no-risk notes received.

**PitchBook profile** — Jebesty Selvaraj (analyst) responded Sep 10 with template constraints. Next pass with Leah. Nothing submitted until reviewed with Patrick.

**TAM/SAM/SOM:** See Market Size section. SAM paused. Do not use investor-facing until Les/Patrick input received.

---

## Key Team

- Patrick Sorrentino — CEO/Co-Founder. Former Market President VillageMD, former CEO Chicago Health System Tenet.
- Michael McCann MD MBA — Founding Director Clinical Model, Medical Director VICP, Asst Prof Clinical Medicine VUMC.
- Les Wilkinson JD — Strategic Advisor, COO Hashed Health.
- Mark Montoney MD MBA — Senior Clinical Advisor, former CMO Wellvana/Contessa/Tenet.
- Deb Sasmal — VP Product, Hashed Health (joined Aug 17, 2026). 7 years at UPMC Enterprises. Background: investment strategy, enterprise implementation, deal structuring.
- Davis Rand — VUMC analytics and financial modeling lead. Out until ~Sep 20.
- Olivia C. Bryant — Enterprise analytics, VUMC.
- Leah Callahan — BD/marketing and pipeline outreach.
- Tommy Gallon — PR/Media Advisor. Agreement finalized.
- Lynn Simon — Clinical Advisor.
- Rob Moskowitz — Advisor, former president/CMO of Contessa. Meeting with Patrick weekly (Thursdays).
- Frank Coliano — Advisor. ACO/VBC background.
- Shadi Awad — Venture Architect, Hashed Health. Owns investor infrastructure, implementation playbook, data strategy, tracker/SOP operations.

---

## Implementation Playbook Status

Final v2: 7 Parts, 18 sections, 13 appendices. Internal only.

- Locked: Section 1.1
- Drafted: 2.1–2.3, 3.1–3.3, 4.1–4.4, 5.1–5.2, 5.6, 6.1–6.3
- Pending Michael: 5.3, 5.4, 5.5, 5.2 activation confirm, family refusal protocol
- Pending Patrick + Michael: 6.4
- Pending Patrick: ICP criteria, operator JD, re-benchmarking protection, Appendices H+I
- Pending demos: 6.1 + App K
- Jun 24 + Jul 2 edits still not executed in document
- Three-tier governance model agreed Aug 25; Deb writing section

---

## Open Blockers (Sep 15, 2026)

- **Commercial language** — Do not lock pricing language until Patrick's CFO no-risk notes received. Active blocker, no movement
- **VICP outcomes one-pager** — per Michael's Sep 9 suggestions: unadjusted LOS 0.83 days, hazard ratio 0.77, 18% LOS for bed-day calc, 23% vs. baseline or drop hospitalization framing. Sent to Michael EOD Sep 9; confirm receipt. Michael out next week
- **Follow up with Davis on hospitalization admission numbers** — needed for bed-day calc; Davis out until ~Sep 20
- **MacNeal cohort list** — pending from Chuck; directional capacity doc sent Sep 11, awaiting response
- **Franciscan NDA** — status not confirmed; meeting Sep 21 — confirm before that date
- **Franciscan prep** — Sep 21 3–4 PM ET with Michael Englehart; Deb and Michael on call
- **PitchBook second pass** — Jebesty template constraints noted; Leah + Shadi next pass before submission
- **Pro forma rebuild** — blocked on commercial language AND Davis cohorted analysis
- **Playbook edits** — Jun 24 + Jul 2 edits unexecuted; governance section pending Deb
- **Warren Sandberg alignment** — VUMC Chief of Staff; needed before C-suite return
- **Cohorted analysis (enrolled vs. eligible-but-unenrolled)** — pursuing CJ Stimpson's org; timeline unclear
- **DRG risk analysis** — Davis + Derrick Anderson's team; top 20 DRGs for VICP cohort
- **Shared savings dashboard + methodology** — not locked
- **Vanderbilt contract** — undrafted
- **Vanderbilt business terms + governance outline** — Patrick + Michael for Davis
- **Juliana webinar** — Vanderbilt permission still needed
- **HCC coding variables** — Patrick + Chris to identify essential fields for Davis
- **AdvisoryTrust equity vs. rev-share counter** — pending
- **TAM/SAM/SOM** — SAM paused pending Les/Patrick input on three questions
- **Mission statement** — individual responses still being collected; Shadi consolidates
- **PMH-APRN credentialing lift for Tier 2** — Patrick to confirm
- **Free assessment concept** — tabled
- **CFO hire** — fractional/advisory; Les flagged higher priority than CMO at this stage

---

## Key Decisions and Principles

- VICP pod at Vanderbilt is proof-of-concept only — not replicated at other sites. Juliana standard pod is canonical for all new deployments
- Cohort exclusions are VICP-specific infrastructure rules; evaluate separately at each new site
- $400 PMPM trigger = first Juliana provider clinical note
- Night float = nocturnist follows care plan; 7am huddle handoff
- Shared savings = 5 contractually defined streams agreed before go-live; freed bed-day = site-specific negotiated contribution margin
- Operator = Day 1, one per site, Juliana-employed. All pod roles non-negotiable Day 1
- Physician lease mechanism is retired — do not reference
- Patrick's CFO no-risk model notes must be received before commercial language is finalized anywhere
- Dashboard RLOS not usable for bed-day math — use Michael's unadjusted figures only
- TCC excluded from all external use until confirmed reliable
- External language locked to "patients cared for on the VICP unit"
