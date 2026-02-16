# Processing Log

## Files Read

### Extraction Inputs
- `inputs/hypotheses.yaml` — 6 hypotheses from 3 source documents (S1: exec summary, S2: pitch deck, S3: angel teaser)

### Research Results (Round 1)
- `research/problem/round-01/prevalence.md` — 60 citations, SOV framework gaps, payment delay statistics, fraud prevalence, abandonment data
- `research/problem/round-01/severity.md` — 60 citations, 60hr/month admin burden, 83-day collection, 8% bid inflation, carrying costs, dispute timelines
- `research/problem/round-01/customer-voice.md` — 46 citations, homeowner quotes, contractor anxiety, renovation stress studies, forum posts
- `research/problem/round-01/current-solutions.md` — 60 citations, platform capability gaps, escrow costs, regulatory barriers, commercial vs residential comparison
- `research/problem/round-01/prevalence.json` — 60 structured citations with URLs
- `research/problem/round-01/severity.json` — 60 structured citations with URLs
- `research/problem/round-01/customer-voice.json` — 46 structured citations with URLs
- `research/problem/round-01/current-solutions.json` — 60 structured citations with URLs

### Research State
- `research/problem/research-state.yaml` — gap analysis showing all 6 hypotheses validated in Round 1

## Hypothesis Validation

### H1: Residential renovation payments are structurally disconnected from verified work completion
- **Outcome:** Validated
- **Evidence:** SOV frameworks concentrated in "large-scale commercial projects" (ProjectManager.com / NAHB). No standardized completion criteria in residential renovation. CoConstruct, Houzz Pro, Buildertrend, Jobber generate invoices but do NOT enforce SOV verification or independent progress checks. Singapore CAS data — S$728K in prepayment losses. Mr. Lim case — S$90K contract, work barely started.
- **Notes:** Strongest structural gap identified. Every other hypothesis connects back to this — absence of verification-linked payments is the root cause.

### H2: Homeowners routinely prepay for unverified work, exposing them to significant financial loss
- **Outcome:** Validated
- **Evidence:** FTC: 109K+ scams 2007-2021, $206.9M total. 81,900 reports in 2024 alone. 1 in 10 Americans victimized. Project abandonments at record highs (66.5% increase). Multiple catastrophic case studies: Colorado homeowner lost retirement savings ($350K), 75 homeowners mass-emailed by bankrupt roofer, "I told my husband I was done."
- **Notes:** Most emotionally documented hypothesis. Customer voice evidence is overwhelming.

### H3: Contractors experience chronic cash flow strain from slow payment cycles
- **Outcome:** Validated
- **Evidence:** 70% face delayed payments (Built, n=250). 82% wait 30+ days, up from 49% in two years (Rabbet 2024). Average 83-day collection vs 30-day terms (CFMA). 60 hrs/month on payment admin. 8% bid inflation. $280B annual payment delay costs. Texas GC on personal credit cards. 100% of subs evaluate GC payment reputation.
- **Notes:** Most quantitatively documented hypothesis. Multiple independent sources with converging data. Two-sided problem: homeowners harmed by absence of controls, contractors harmed by absence of controls.

### H4: Lenders and insurers lack real-time visibility into fund utilization
- **Outcome:** Validated
- **Evidence:** Manual draw process averages 11 days. Costs $200-$500/inspection residential. "Inspections provide snapshots, not real-time visibility" (Built). Built Technologies and Land Gorilla solve for commercial but not residential. AI-generated fraudulent photos as emerging risk (Truepic). $9.3B annual post-disaster fraud (NICB).
- **Notes:** Clearest current-solutions gap. Commercial lending platforms exist but haven't moved to residential — validates the market gap claim.

### H5: Residential renovation operates without independent third-party financial controls
- **Outcome:** Validated
- **Evidence:** Commercial has SOV, inspections, surety bonds, AIA contracts, escrow. Residential has none as standard. NY requires escrow/bonding but compliance uneven. Escrow costs $400-$725/draw, doesn't scale. Niche providers (Build Safe, La Mesa) market custody as novel. Money transmitter licenses needed in 50 states.
- **Notes:** This is the umbrella hypothesis — H1-H4 are specific manifestations of this structural gap. The thesis leads with this framing.

### H6: The U.S. residential renovation industry loses tens of billions annually
- **Outcome:** Validated
- **Evidence:** $280B payment delays (Rabbet 2024). $9.3B post-disaster fraud (NICB). 8% bid inflation on $400B+ spending = $32B+. Fraud median $250K per incident, 25% of firms victimized. Founder's $40B claim is actually conservative when aggregating all sources.
- **Notes:** "Tens of billions" is well-supported as a floor. The precise number depends on what's included — payment delays alone dwarf the founder's $40B figure.

## Emergent Findings

1. **E1: Administrative burden as standalone problem.** 60 hours/month wasted on payment management per firm — nearly two full work weeks. This strengthens H3 but also reveals a standalone automation opportunity beyond fund custody.

2. **E2: Generational divide in renovation stress.** Millennials report 67% moderate-high stress, 40% strained relationships, compared to 15% of Boomers. Millennials are more likely to adopt digital platforms. Potential market entry angle for adoption strategy.

3. **E3: State regulatory fragmentation as structural barrier.** Escrow/bonding requirements vary across 50 states. Money transmitter or escrow licenses needed in each. This is why no one has built a national residential fund custody platform — regulatory complexity is the moat.

4. **E4: AI-generated fraud as escalating risk.** Fraudsters now use AI to create fake invoices and progress photos. Truepic documenting this as a distinct category. Increases urgency for verification controls.

5. **E5: Economic headwinds amplifying vulnerability.** 71% postponing renovations, tariffs adding material cost unpredictability, 82% have repair needs but 60% can't afford them. Those who do proceed are more financially vulnerable to fraud and payment issues.

## Thesis Direction

The thesis addresses H5 as the root cause — absent financial controls in residential renovation — with H1-H4 as specific manifestations and H6 as the aggregate impact. The problem statement frames the gap between commercial (which has controls) and residential (which doesn't).

The thesis does NOT address market sizing, business model viability, or solution design — those belong to downstream workspaces.

## Evidence Included

### Prevalence (13 entries in evidence.yaml)
- Payment delay rates from Built 2025, Rabbet 2024, CFMA
- SOV framework gap from ProjectManager.com
- Fraud statistics from FTC, ACFE, Metal Construction News
- Subcontractor payment data from PYMNTS/AmEx 2025
- Project abandonment data from ConstructConnect
- Homeowner postponement data from PA Realtors

### Severity (12 entries in evidence.yaml)
- Administrative burden from Construction Cost Accounting
- Bid inflation from Built 2025
- Draw inspection costs/timeline from Sekady, Larson
- Dispute resolution timeline from Arcadis
- Fraud median loss from ACFE/Veryfi
- Carrying costs from Billd/CFMA
- Aggregate impact from PYMNTS/AmEx, NICB
- Escrow costs from Secured Trust
- Mechanics lien risk from Illinois Legal Aid

### Customer Voice (9 entries in evidence.yaml)
- Homeowner loss quotes from Channel News Asia, BBB, Bogleheads, Uken Report
- Contractor anxiety from Contractor Foreman
- Renovation stress from Block Renovation
- Willingness to adopt from Built 2025

### Current Solutions (7 entries in evidence.yaml)
- Platform gaps from CoConstruct, Houzz Pro, Buildertrend, Jobber documentation
- Commercial alternatives from Built Technologies, Land Gorilla
- Lien waiver management from Levelset, Procore
- Escrow providers from Build Safe, La Mesa
- Escrow cost barriers from Secured Trust
- Regulatory barriers from Procore construction escrow analysis
- Drone inspection from EagleView

## Evidence Excluded

- **Riviera Finance / 1st Commercial Credit** — Invoice factoring companies cited in prevalence research. Factoring is a workaround for slow payments, not a control mechanism. Excluded from thesis as solution evidence but noted as proof that contractors seek workarounds.
- **Plooto** — General cash flow management article. Generic advice, not specific enough for evidence claims.
- **EisnerAmper** — Private equity fund accounting. Commercial focus, not relevant to residential thesis.
- **Insurance Journal / Cotality** — $308.6B total insurance fraud estimate. Too broad (all insurance, not construction-specific). NICB's $9.3B is more targeted.
- **Warren Averett** — Custody audit guidance for RIAs. Financial services analogy but not construction-specific.
- **KPMG Canada** — Technology adoption in Canadian construction. Different market, not directly applicable.
- **Singapore Consumer Association / theconsumer.org.sg** — Prepayment danger data from Singapore. Included as customer voice context but not used for U.S. prevalence claims.
- **Various law firms** (Kaplin Stewart, Chicago Mechanics Lien Attorney, Dallas Construction Law, etc.) — General mechanics lien legal guidance. Referenced for context but not primary evidence sources.

## Conflicts Found

- **Draw inspection cost ranges:** Sekady reports $200-$500 residential, $500-$1,500 commercial. Larson reports $100-$150 residential, $250-$350 commercial. Resolution: Both are cited. Ranges vary by geography and project complexity. Used Sekady's higher range in thesis as it represents the more typical national figure.

- **Payment delay cost figures:** Construction Dive reported $208B in 2022. Rabbet/PYMNTS/AmEx report $280B in 2024. Resolution: Both cited. The increase from $208B to $280B over two years is internally consistent and shows worsening trend.

- **Homeowner repair affordability:** YouTube survey says 82% have issues, 60% can't afford repairs. PA Realtors says 71% postponing due to economic uncertainty. Resolution: Different surveys measuring different things (ability to pay vs. willingness to proceed). Both included as they show complementary demand-side constraints.

## Gaps Identified

- **Residential-specific fraud loss data:** Most fraud statistics cover all construction, not residential specifically. The thesis infers residential share from total figures and market size ratios but doesn't have a residential-only fraud survey.
- **International comparison data:** Strong evidence that commercial construction has controls, but limited quantitative comparison of loss rates between commercial and residential per dollar spent.
- **Contractor demographic data:** Limited data on firm size distribution in residential renovation. The 60 hrs/month burden may affect small firms differently than large ones.
- **Lender-specific loss data:** FDIC construction loan loss paper is from 2021 and covers all construction loans. No residential-specific lender loss rate data found.

## Decisions Made

### Connective Claims

1. **"Absent controls cause the losses" (P5 derivation):** Connected commercial construction's lower loss rates to its mandatory controls, and residential's higher losses to its absent controls. This is a correlation-to-causation inference. Logged because the causal mechanism is plausible (commercial has controls AND lower losses) but not proven by RCT. The denial test strengthens this: if controls didn't matter, commercial and residential would have similar loss rates.

2. **"$280B annual cost" scope:** The Rabbet/PYMNTS figure covers all construction, not just residential. The thesis cites it as "across construction" not "residential specifically." Residential's share would be proportional to its ~40% of total construction spending.

3. **"~100:1 ratio" of losses to control costs:** Derived by comparing $280B annual losses to escrow costs ($400-$725/draw × estimated draws). This is an order-of-magnitude estimate, not a precise calculation. Stated as "orders of magnitude" in the thesis.

4. **Trust → bid inflation → cost increase chain:** Connected 8% bid inflation (Built) to trust deficit (100% of subs evaluate GC reputation, 88% reject projects). The causal chain is: trust deficit → risk pricing → bid inflation → cost increase. Each link is independently evidenced but the full chain is an inference.

### Structural Choices

- Organized first principles around the payment verification gap (P1-P6) rather than by stakeholder group. This reflects the root cause structure better than a stakeholder-by-stakeholder analysis.
- JTBD organized functionally (J1-J5) covering all stakeholder groups rather than one job per stakeholder. This prevents siloed thinking about what are interconnected payment chain problems.
- Customer voice organized by theme (7 themes) rather than by stakeholder. Themes map to JTBD and validated problems.
- Thesis "Why It Persists" section traces to structural causes rather than individual failures. This is a deliberate framing choice to match P4 (trust-based controls fail at market scale).
