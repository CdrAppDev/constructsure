# Problem Thesis: ConstructSure

## Problem Statement

Residential renovation and restoration in the United States operates without the independent financial controls — fund custody, milestone verification, and audit trails — that are standard in commercial construction, exposing homeowners, contractors, subcontractors, and lenders to preventable losses that reach hundreds of billions of dollars annually.

## Who Suffers

Four distinct stakeholder groups bear the consequences of absent financial controls in residential renovation:

**Homeowners** fund renovation projects averaging tens of thousands of dollars with no mechanism ensuring payments align with verified work completion. One in ten Americans report being victimized by contractor fraud, with average losses exceeding $2,400 per incident (Metal Construction News / consumer watchdog estimates). The FTC received more than 81,900 home improvement scam reports in 2024 alone, with homeowners losing an average of $1,800 per incident (Uken Report / FTC, 2024). More than 82% of homeowners have at least one issue needing repair, but 60% cannot afford it (YouTube / homeowner survey), and 71% have postponed renovations due to economic uncertainty (PA Realtors, 2025), making those who do proceed more vulnerable to unfavorable payment terms.

**Contractors** experience chronic cash flow strain: 70% regularly face delayed payments (Built, 2025, n=250), with 82% waiting 30+ days — up from 49% just two years ago (Rabbet 2024 Construction Payments Report). The average collection time is 83 days against 30-day contract terms (CFMA). Contractors waste over 60 hours per month — nearly two full work weeks — on payment administration alone (Construction Cost Accounting). To compensate, contractors inflate bids by an average of 8% (Built, 2025), and over one-third have seen projects canceled or delayed due to financing gaps.

**Subcontractors and suppliers** sit at the bottom of the payment chain. By end of 2023, 71% reported delayed payments from general contractors, up from 60% in 2022, and 77% cover materials expenses out-of-pocket before reimbursement (PYMNTS/American Express, 2025). Every surveyed subcontractor now evaluates a general contractor's payment reputation before bidding, and 88% have rejected projects over payment reliability concerns (PYMNTS/American Express, 2025).

**Lenders and insurers** funding residential renovation lack real-time visibility into fund utilization. Manual draw inspection processes average 11 days from work completion to payment (Sekady), with inspections providing "snapshots, not real-time visibility" (Built, construction loan monitoring). Draw inspection costs of $200-$500 per residential inspection do not scale to $10K-$100K renovation projects (Sekady). AI-generated fraudulent progress photos now represent a distinct fraud category (Truepic).

## How They Suffer

The suffering is measurable across time, trust, and cascading financial harm:

**Time lost to broken payment processes.** Contractors spend 60+ hours monthly managing payments: invoice creation (~15 hrs), follow-up and collections (~20 hrs), dispute resolution (~12 hrs), and reconciliation (~13 hrs) (Construction Cost Accounting). A single invoice for a complex project can require 2-3 hours of preparation across 5-8 disparate systems. Manual draw processes take 3x longer than automated alternatives (Land Gorilla). The average dispute takes 16.7 months to resolve (Arcadis, 2022).

**Trust erosion across the payment chain.** Homeowners face a 1-in-10 chance of contractor fraud. Contractors inflate bids 8% as a trust tax. Subcontractors add 5-10% markups for slow-paying GCs. Lenders cannot distinguish genuine progress from fabricated claims between episodic inspections. The result is a market where every party prices in mistrust, inflating costs industry-wide.

**Cascading financial harm.** When a homeowner delays payment, the contractor delays subcontractor payment, who delays supplier payment. Each tier incurs carrying costs of approximately 6.17% per month (CFMA analysis). A $50K invoice unpaid for 60 days generates roughly $6,200 in cumulative carrying costs across the chain. Project abandonments have climbed 66.5% since end of 2024, reaching the highest level since tracking began (ConstructConnect).

**Emotional and psychological toll.** 85% of homeowners undergoing remodeling report significant stress; 57% experience "renovation fatigue" (Block Renovation, 2025). Millennials feel it most acutely: 67% report moderate-to-high stress and 40% say renovations strained personal relationships. Among contractors, "anxiety becomes a constant companion, sleepless nights follow, and over time, stress can lead to burnout" (Contractor Foreman).

## Why It Persists

**Historical fragmentation.** Residential renovation developed as a relationship-based industry dominated by small contractors and individual homeowners, without the institutional intermediaries that commercial construction evolved. At $603 billion in 2024 residential remodeling spending (NARI/Harvard JCHS), informal trust-based controls are inadequate for the capital flows they govern.

**Economic barriers to adopting controls.** Escrow services cost $400-$725 per draw (California escrow fee survey, 2024), representing 5-15% of small project costs. Draw inspections cost $200-$500 per residential inspection. These per-draw costs don't scale to $10K-$100K residential projects the way they scale to multi-million dollar commercial loans.

**Regulatory fragmentation.** Escrow, bonding, and lien requirements vary across 50 states. New York requires escrow or bonding for residential contractors, but compliance is uneven. Building a compliant custody offering across all states requires navigating 50 separate regulatory regimes. Money transmitter or escrow licenses would be needed in each state.

**Technology gap.** No dominant residential construction management platform integrates end-to-end financial controls. Buildertrend, CoConstruct, Houzz Pro, and Jobber each address isolated components — invoicing, scheduling, payment tracking — but none offers fund custody, independent verification, or SOV enforcement. Built Technologies and Land Gorilla solve draw management for commercial lending but have not adapted for residential projects at scale. Levelset and Procore offer lien waiver management designed for commercial workflows.

**Market failure.** The benefits of standardized controls are distributed industry-wide (lower fraud, faster payments, fewer disputes) but the costs of implementing them fall on individual actors who capture only a fraction of those benefits. No single party has sufficient incentive to build the infrastructure that would benefit all parties.

## First Principles

**P1: Payment without independent verification is payment without accountability.**
- Evidence: SOV frameworks concentrated in commercial, not residential; no standardized completion criteria in residential renovation (ProjectManager.com / NAHB)
- Implication: Every disbursement must be conditioned on independently verified work completion

**P2: Information asymmetry between parties determines who bears financial risk.**
- Evidence: Homeowners lack expertise; subcontractors can't see upstream status; lenders get episodic snapshots (Levelset 2022, Built, severity research)
- Implication: Solution must provide symmetric, real-time visibility to all stakeholders

**P3: Payment chain delays compound through tiers.**
- Evidence: 82% of contractors wait 30+ days; 71% of subs report delayed GC payments; carrying costs of 6.17%/month cumulative (Rabbet 2024, PYMNTS/AmEx 2025, CFMA)
- Implication: Solution must accelerate the entire chain, not just one tier

**P4: Trust-based controls fail at market scale.**
- Evidence: $603B market with relationship-based controls; fraud cases up 60%; abandonments up 66.5% (NARI, ACFE 2024, ConstructConnect)
- Implication: Controls must be institutional and structural, not dependent on individual trust

**P5: Financial controls are a prerequisite for, not a consequence of, project completion.**
- Evidence: Commercial construction has controls and lower loss rates; residential lacks controls at $603B scale (cross-research comparison)
- Implication: Controls must be designed into the payment structure from project inception

**P6: The cost of absent controls exceeds the cost of implementing controls by orders of magnitude.**
- Evidence: $280B payment delay costs vs. $400-$725/draw for escrow; ~100:1 ratio (Rabbet 2024, California escrow survey)
- Implication: Even partial loss reduction generates compelling economics

## Jobs to Be Done

**Functional:**
- J1: Ensure money only moves when work is verified complete -> Done when: every payment tied to independently verified milestone
- J2: Receive payment within days of completing milestones -> Done when: verified work triggers payment in 1-2 business days
- J3: Real-time visibility into fund utilization and work progress -> Done when: dashboard shows verified vs. claimed progress for all projects
- J4: Documented evidence for rapid dispute resolution -> Done when: complete audit trail resolves disputes in days, not months
- J5: Automatic lien waiver satisfaction at milestones -> Done when: lien waivers collected and matched to payments; clean title at completion

**Emotional:**
- E1: Feel confident that renovation funds are protected
- E2: Feel relieved from cash flow anxiety and payment chasing
- E3: Feel in control of the renovation process

**Social:**
- S1: Be seen as a reliable business partner by subcontractors
- S2: Be seen as a responsible fiduciary by regulators and borrowers

## Evidence Summary

| Category | Finding | Source |
|----------|---------|--------|
| Prevalence | 70% of contractors regularly face delayed payments | Built, 2025 (n=250) |
| Prevalence | 82% of contractors wait 30+ days, up from 49% two years ago | Rabbet 2024 |
| Prevalence | 1 in 10 Americans victimized by contractor fraud | Metal Construction News / watchdog estimates |
| Prevalence | SOV frameworks concentrated in commercial, not residential | ProjectManager.com / NAHB |
| Prevalence | Project abandonments up 66.5% since end of 2024 | ConstructConnect |
| Severity | 60 hours/month lost to payment administration per firm | Construction Cost Accounting |
| Severity | Average 83-day collection time vs. 30-day terms | CFMA |
| Severity | 8% bid inflation to compensate for payment risk | Built, 2025 |
| Severity | Manual draw process averages 11 days | Sekady |
| Severity | Dispute resolution averages 16.7 months | Arcadis, 2022 |
| Customer Voice | 85% of remodeling homeowners report significant stress | Block Renovation, 2025 |
| Customer Voice | "Anxiety becomes a constant companion, sleepless nights follow" | Contractor Foreman |
| Customer Voice | 82% of contractors open to digital payment systems | Built, 2025 |
| Current Solutions | Buildertrend/CoConstruct/Houzz Pro/Jobber: no fund custody | Current-solutions research |
| Current Solutions | Built/Land Gorilla: commercial lending only, not residential | Current-solutions research |
| Current Solutions | Escrow exists but costs $400-$725/draw, fragmented by state | California escrow survey, 2024 |
