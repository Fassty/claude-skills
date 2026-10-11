# Product discovery — from idea to a product worth building

## Contents
- The one idea underneath everything
- Principles
- Risk taxonomy
- Judging evidence
- Cross-cutting artefacts
- Three phases, nine stages
  - Stage 0 — Frame the opportunity and its risks
  - Stage 1 — Problem hypotheses
  - Stage 2 — Landscape
  - Stage 3 — Customer interviews and observation
  - Stage 4 — Positioning and solution experiments
  - Stage 5 — Commitment and value tests
  - Stage 6 — Business case and risk review
  - Stage 7 — Investment decision and MVP learning plan
  - Stage 8 — Build, release, measure, iterate
- Pivot loop
- What we deliberately skip
- Roles

A general framework for evidence-driven early product discovery, with example methods that must be adapted to the opportunity's market, constraints and business model. It covers the phase *before* the spec: the spec says what we build; discovery records why anyone would want it, whether we can deliver it, and the evidence for both. The investment decision at Stage 7 is the gate that authorises implementation; nothing in the spec moves past `proposed` before it.

The principles are domain-agnostic. The methods are not: marketplaces test liquidity on both sides, regulated products need safety and regulatory evidence, network-effect products cannot be validated with five isolated users. The critical-path archetypes in Stage 0 are the first adaptation; the founder makes the rest.

## The one idea underneath everything

> Identify the most consequential uncertainty, run the cheapest credible test, update confidence, make the next investment decision.

The stages below are the default path through that loop. They are a reference map, not a ritual: evidence can send you back a stage or straight to a different test. But any deviation from the default path is written down with the assumption it tests, so that "we skipped interviews" is a decision, not a drift.

## Principles

- **Evidence over frameworks.** SWOT, Porter, Lean Canvas, TAM/SAM/SOM are summaries of evidence. Fill them after you have evidence, as a check for holes, never as a starting point.
- **Riskiest, cheapest-to-test assumption first.** Rank by impact × uncertainty, then prefer what is cheapest to resolve or blocks everything else.
- **Talk to relevant people early.** Use the cheapest evidence-producing method for the risk in front of you — usually a conversation, sometimes a prototype or a technical spike.
- **Past behaviour, not opinions.** What people did, paid for, and quit tells the truth; what they say they would do does not.
- **An experiment passing does not validate an assumption.** An assumption is supported only to the extent the evidence reduces uncertainty about *that* assumption. Failing to establish an assumption is not the same as refuting it.
- **Evidence sufficient for the next investment.** Discovery does not aim to eliminate uncertainty; it aims to reduce the most consequential risks enough to justify the next commitment. Required evidence strength rises with the size and irreversibility of that commitment:
  - *A day of prototyping* — a plausible problem and a clearly testable assumption is enough.
  - *A month on an MVP* — credible problem evidence, some real commitment from customers, no unresolved feasibility blocker.
  - *Hiring or committing capital* — behavioural, financial, delivery and distribution evidence, each from a test that directly addressed it.
- **Every experiment ends in a documented decision**: stop, pivot, proceed, or investigate further — with confidence and remaining uncertainty stated.
- **Optimise learning per unit of time and money**, not artefacts or interview counts. Sample sizes and stage lists are planning heuristics, not completion requirements. If one well-designed experiment answers two questions, run one.
- **Budget, then review.** Set a discovery budget (default 4–6 weeks part-time for a simple, accessible market; longer for enterprise or complex domains) and a review date. Extend only when a specific unresolved risk justifies it, named in writing.
- **Keep the artefacts small.** One page of arithmetic beats a business plan.

## Risk taxonomy

Every assumption gets a primary tag and optionally a secondary one (distribution + viability, feasibility + constraints). If a category has no assumptions, you have probably missed some.

| Tag | Question |
|---|---|
| Desirability | Do people need this, badly enough to change behaviour? |
| Viability | Can the economics work for this founder? |
| Feasibility | Can we deliver the promised outcome with the resources we have? |
| Usability | Can the target customer successfully perform the core task with it? |
| Distribution | Can we reach, convince and acquire customers repeatedly at an affordable cost? |
| Constraints | Legal, regulatory, trust, data, platform or operational blockers |

## Judging evidence

Evidence is strong when it **directly tests the assumption**, comes from the **target customer in realistic circumstances**, was **observed rather than reported**, and has **few alternative explanations**. Judge on those four, not on the type of action alone. Payment is strong for willingness-to-pay and weak for usability; observed task completion is strong for usability and says nothing about demand; ten uses of a free concierge service is strong for value delivered and silent on price.

Heuristic ladder, useful as a reminder and never as a ranking: stated opinion < reported past behaviour < observed behaviour < costless commitment < costly commitment (time, data, reputation) < payment < repeat payment or repeat use.

**Decision guidance for any experiment:**

| Evidence outcome | Decision |
|---|---|
| Critical assumption credibly refuted | Stop or pivot |
| Evidence supports proceeding at the required strength | Proceed |
| Weak, inconclusive, or sample too biased | Test again, or choose a different experiment |
| Problem sound, solution or positioning fails | Change the solution or the positioning, not the segment |

Each stage below states what *refuted* looks like there (stop/pivot) and what *unresolved* looks like (investigate further).

## Cross-cutting artefacts (maintained through every stage)

| Artefact | What it holds |
|---|---|
| `00-frame.md` | The idea in one paragraph, founder constraints, success definition, chosen critical path, rough economics |
| `assumptions.md` | One row per assumption (fields below) |
| `decisions.md` | One entry per gate or experiment: date, decision (stop / pivot / proceed / investigate), evidence, confidence, what changed |
| `status.md` | Stage, status, started, decision — the dashboard |

**`assumptions.md` fields:** assumption (falsifiable) · risk tag (primary, secondary) · impact if false · confidence before · test cost · experiment · success criterion (written before running) · observation · evidence source (link to interview, data, experiment) · evidence strength and limitations · confidence after · decision · next uncertainty.

## Three phases, nine stages (0–8)

| Phase | Core question | Stages |
|---|---|---|
| Opportunity discovery | Is there a real problem and an attractive opportunity worth pursuing? | 0–3 |
| Solution discovery and validation | Can we deliver a solution customers value, adopt and will pay for? | 4–6 |
| Investment decision and delivery | Should we build, what must the first release prove, and what does real usage teach? | 7–8 |

A pre-spec discovery skill covers 0–7. Stage 8 is the handoff.

### Stage 0 — Frame the opportunity and its risks
**Question:** What is the idea, what do we need from it, what would have to be true, and what is the critical path?
**Method:**
- Write the idea in one paragraph without naming a solution ("people in situation X struggle to do Y; today they Z").
- Founder constraints: time, money, skills, what you will not do. Define success numerically.
- List assumptions, tag each, rank by impact × uncertainty, note test cost. Distinguish *proven impossible* from *not currently feasible* — a licence or partner requirement changes the model, it doesn't necessarily kill the idea.
- Rough economics on the back of an envelope: plausible price, obvious variable cost per customer, obvious acquisition cost. These are guesses; their job is to surface which of them to test early, not to decide.
- Name at least one acquisition channel you could plausibly use repeatedly.
- **Choose the critical path** by archetype and record it:

| Archetype | Dominant uncertainty | Default path |
|---|---|---|
| Consumer habit or utility | Enough people care and keep returning | Problem → demand → retention |
| Deep-tech / novel capability | The core capability is possible | Feasibility spike → problem → demand |
| Enterprise / B2B | Someone can authorise, adopt and pay | Buyer & budget → integration/feasibility → paid pilot |
| Marketplace / two-sided | Supply and demand can be seeded together | Scarce side first → other side → liquidity |

**Artefact:** `00-frame.md`, `assumptions.md` (first version).
**Refuted when:** a constraint is proven impossible for this founder with no plausible model or partner that removes it.
**Unresolved when:** the back-of-envelope economics look negative — that makes price or delivery cost the first assumption to test, not a reason to stop.

### Stage 1 — Problem hypotheses
**Question:** Which 3–5 specific segments might have a painful, unsolved problem this idea addresses?
**Method:** For each candidate segment record the job to be done (functional, emotional, social), the trigger that makes it urgent, frequency, consequences of not solving it, current solution and its pain, and the segment's willingness and ability to change behaviour. Prefer segments you can describe in one line. Challenge each adversarially: why would this group *not* care?
**Artefact:** `01-problem-hypotheses.md` — table: segment · job · trigger · frequency · consequence · current solution · pain · ability to change · where found · reachability.
**Refuted when:** you cannot get conversations with the segment at all inside the discovery budget, or the economics of reaching them can never work (small segments are fine if each customer is worth it).
**Unresolved when:** you don't yet know a repeatable channel. Finding channels is discovery work; log it as a distribution assumption and carry the segment forward.

### Stage 2 — Landscape
**Question:** Who already serves each segment's job, how, at what price, and where is the opening?
**Method:** Competitor teardown — listings, pricing, onboarding, 1★ and 5★ reviews, forums, support threads. Include *adjacent substitutes* (spreadsheets, paper, a general-purpose tool, a human service, doing nothing). Record switching costs, why people churn, and the users' own vocabulary for the problem (for recruiting copy and positioning — not for interview questions, where it biases answers). Treat review data as a biased sample of the motivated.
**Artefact:** `02-landscape.md` + `competitors.csv` (name · segment served · price · job coverage · top praise · top complaint · switching cost · gap).
**Refuted when:** after honest effort you cannot write down any credible reason a reachable segment would choose your offering over its best current alternative — cost, convenience, integration, distribution, a new capability, or an unmet need.
**Unresolved when:** you have a candidate reason but no evidence yet that customers weigh it. Absence of complaints is not absence of opportunity.

Runs in parallel with Stage 3 once Stage 1 is done.

### Stage 3 — Customer interviews and observation
**Question:** Do real people in the top segments have the problem, how do they handle it today, what have they tried, what made them quit?
**Method:** Start with about 5 problem-focused interviews in the highest-priority segment, 30 min, recorded with consent. Synthesise, then recruit more or open a second segment only where important uncertainties remain. Mom Test rules: past behaviour, specifics, money; never pitch; never ask "would you use…". Write the recruiting plan before the first interview. Where possible, *observe* someone doing the task — friction people don't articulate shows up on screen. Tag notes by assumption.
**Adaptation:** B2B — interview the user *and* the buyer; who signs, which budget line, current vendor, procurement path. Consumer — "tell me about the last time this happened," step by step.
**Artefact:** `03-interviews/` (one note per interview, same template) + `03-interview-synthesis.md` (patterns, quotes in users' words, assumption status).
**Refuted when:** people in the segment, asked about the relevant situation concretely, do not describe the problem as recurring or consequential, and nothing in their behaviour suggests it costs them.
**Unresolved when:** the sample is small or skewed, or the problem appears only when named. Signals that raise confidence: it comes up unprompted; people have paid, hacked or spent effort on it. Signals that lower it: nobody has changed anything to deal with it. Small samples show patterns and disconfirm; they do not establish prevalence — say so in the evidence field.

### Stage 4 — Positioning and solution experiments
**Question:** For the surviving segment: who exactly, what they use today, what we do differently, why they'd believe it — and does our proposed solution actually work for them?
**Method:**
- Positioning statement (Dunford format: competitive alternative → unique attributes → value → target customer → category). Value proposition canvas. A buyer/user map and the observed workflow; persona sketches only if they add something the map doesn't.
- A one-sentence pitch in the customer's words (a sentence of context is fine for B2B). This is a *comprehension* test — can the listener say who it's for and what changes? — not a desirability test.
- A solution sketch: one paragraph on the smallest offering that delivers the promise.
- **Solution experiments**, scaled to the risk: concept test with a mocked screen or document, clickable prototype, walkthrough of a mocked workflow, demo, or a technical spike for the hardest feasibility assumption. Where one experiment can test both comprehension and desirability, run one. Use *fresh* participants for first impressions, comprehension and usability; Stage 3 interviewees are biased by familiarity and are better for depth.
- Answer four questions: Do they understand the approach? Do they believe it would improve their situation? Can they perform the core task with it? Can we realistically deliver the outcome?
**Artefact:** `04-positioning.md` + `04-solution-experiments.md`.
**Refuted when:** target customers understand the approach and do not believe it helps them; or the feasibility spike shows the core outcome cannot be delivered with the founder's resources.
**Unresolved when:** they cannot say who it is for — that is a positioning failure; rewrite and retest before concluding anything about the opportunity.

### Stage 5 — Commitment and value tests
**Question:** Will people in the segment give something up for the promise before the product exists — and once they get the value, do they come back or pay?
**Method:** Pick the experiment that tests the highest-risk behaviour on the critical path. Measure three things separately where relevant: **initial commitment**, **value actually received**, **willingness to repeat or pay**. Match the time horizon to natural usage frequency (daily tool: a week or two; annual service: one cycle, so use a stronger proxy). Write the success criterion in `assumptions.md` *before* launching, specific to segment, channel and model. Record the channel used and what it cost. This gives evidence of **channel reachability** — you found and reached these people — but not of **scalable acquisition economics**, which stays an open distribution assumption until tested at volume.

| Experiment | What it shows | What it doesn't |
|---|---|---|
| Landing page + waitlist (with a qualifying question) | Interest among reached visitors | Purchase, use, retention |
| Pricing page click-through | Engagement with an offer | Willingness to pay |
| Pre-order / deposit | Purchasing commitment | Satisfaction, retention |
| Concierge / Wizard-of-Oz (deliver by hand to ~5 people) | Value can be delivered and experienced; repeat behaviour | Scalable economics |
| Letter of intent (B2B) | Organisational interest | Often non-binding |
| Paid pilot (B2B) | Purchase and initial usage | Generalisation beyond the pilot |
| Paid discovery call | Buyer budget and seriousness | Product fit |

Illustrative only, not defaults: a consumer waitlist might be set at ≥5% of ≥200 targeted visitors; a concierge test at users returning unprompted in the second week; a B2B test at one of five qualified buyers agreeing to pay something. The founder sets the real criterion from the segment and the economics, and writes it down first.
**Artefact:** `05-commitment-test.md` — criterion set in advance, channel, cost, the three measurements, evidence strength, limitations.
**Refuted when:** on the measurement that matters for the critical path, the target customers you reached did not commit, did not receive value, or would not repeat.
**Unresolved when:** traffic was too small or the wrong audience, the horizon was too short for the usage pattern, or only interest (signups) was measured. Email signups alone never count as validated demand.

Can start as soon as Stage 4 has a pitch and a solution sketch.

### Stage 6 — Business case and risk review
**Question:** Can this make money at realistic numbers, for this founder, in the time allowed?
**Method:** Consolidate the economics refined since Stage 0 into one page: price, variable cost to serve, acquisition cost and channel, sales/onboarding effort, fixed build/maintain/support cost, retention and lifetime value, payback, contribution margin, break-even in customers and months. Three scenarios (pessimistic / expected / optimistic) so uncertainty is visible. Rough SAM for the *segment*. SWOT and risk list as a holes check, each risk tied to an assumption and a mitigation. Compare against the Stage 0 success definition.
**Artefact:** `06-business-case.md`.
**Refuted when:** contribution margin is negative in the expected scenario *after* investigating plausible levers — a higher price customers signalled they'd bear, a narrower richer segment, a cheaper delivery model — or break-even is beyond the founder's runway with no credible lever.
**Unresolved when:** the negative result rests on an untested price or cost; that sends you back to a Stage 5 pricing test.

### Stage 7 — Investment decision and MVP learning plan
**Question:** Build, pivot, stop, or investigate — and if build, what must the first release prove?
**Method:** Apply the evidence-sufficiency principle: is the evidence strong enough for *this* size of commitment? Decide explicitly among **build**, **investigate further** (name the experiment), **pivot** (name what changes), or **stop**. If build: rewrite the spec's vision, target customer and first milestone from the evidence, and write the **MVP learning plan** — the smallest valuable end-to-end experience; assumptions still open (usually usability, retention, distribution at scale); operational and technical constraints; launch channel; one primary outcome metric with target and review date, plus diagnostic and guardrail metrics; the criteria for expanding, iterating or stopping after release.
**Artefact:** `07-decision.md`, updated spec.
**This is the authorisation gate.** It is a decision, not a handoff that happens because the earlier artefacts exist.

### Stage 8 — Build, release, measure, iterate (outside the discovery skill)
Some assumptions only resolve when real people use a working product in real conditions. The MVP learning plan is the contract: ship the smallest thing that tests it, instrument the primary metric, review on the date set, feed results back into `assumptions.md` and `decisions.md`. Discovery doesn't end at approval; it changes instruments.

## Pivot loop
A stop at any stage returns to the latest stage whose output is still valid, or jumps to whichever test the new uncertainty needs:
- Segment refuted in Stage 3 → back to Stage 1 with the next hypothesis (Stage 2 work on it is often done).
- Pitch or solution fails in Stage 4 → reposition. If the new positioning changes the problem or the promised value, re-interview; a new promise to the same people is a new assumption.
- Commitment test fails in Stage 5 → ask the non-converters before deciding whether the pitch, the channel or the segment failed.
- Economics fail in Stage 6 → test a price or segment lever before stopping.
After three pivots without a proceed, write a review: quality of the new evidence, opportunity cost, and whether the next experiment has a real chance of changing the decision. Parking the idea is a legitimate outcome of that review; it is not automatic.

## What we deliberately skip
- Full market-sizing reports, formal business plans, pitch decks.
- Brand, name, visual identity, domain shopping.
- Implementation beyond what a solution experiment, concierge test or feasibility spike needs. Minimal prototypes and technical spikes that resolve a critical uncertainty are discovery work, not building.

## Roles
- **Founder:** picks hypotheses and the critical path, runs interviews (they must hear users directly), writes success criteria before tests, makes every stop/pivot/proceed/investigate call.
- **Assistant:** desk research, competitor teardown, review mining, interview guide and recruiting copy, synthesis, prototype and landing-page copy and build, feasibility spikes where in scope, unit-economics model, framework fill-ins, drafting every artefact, keeping `assumptions.md`, `decisions.md` and `status.md` current.
