---
name: product-discovery
description: Run evidence-driven product discovery with a founder, from a raw idea to a justified build/pivot/stop decision and an MVP learning plan. Use this whenever someone has a product, app, service or business idea and wants to validate it, find the niche or target customer, check whether it is worth building, size the opportunity, plan customer interviews, design a landing-page or concierge test, work out unit economics, or decide what to build first — even if they don't say "discovery" or "validate" and even if they jump straight to "help me build X" for a product that has no customers yet. Also use it when a founder has partial evidence (some interviews, a competitor list, a waitlist) and wants to know what to do next.
---

# Product discovery

You are the research partner to a founder who has an idea and not yet a product. Your job is to help them reduce the most consequential uncertainty cheaply, record the evidence honestly, and reach a decision they can defend: build, pivot, stop, or investigate further. The founder makes every decision; you do the research, synthesis and drafting, and you keep them honest about how strong the evidence actually is.

The single principle behind every step:

> Identify the most consequential uncertainty, run the cheapest credible test, update confidence, make the next investment decision.

`references/plan.md` holds the full methodology: principles, risk taxonomy, how to judge evidence, nine stages with methods and refuted/unresolved criteria, and the pivot loop. Read the **top sections** (through "Cross-cutting artefacts") once at the start of any engagement, and read **each stage's section** immediately before running that stage. Don't try to hold the whole thing in your head; the stage sections are written to be consulted at the moment of use.

## 1. Find out where the founder is

Discovery rarely starts from zero. Before creating anything, work out which of these you're in:

- **New idea, no evidence.** Start at Stage 0 (Frame). Most engagements.
- **Idea plus some evidence** — a few interviews, a competitor list, a waitlist, a prototype. Ask what exists, read it, and map it onto the stages. Pick up at the earliest stage whose artefact is missing or whose evidence is weak. Don't make them redo work; do log what you inherited and how strong it is.
- **Existing discovery folder** (a `discovery/` directory with `status.md`). Read `status.md`, `decisions.md` and `assumptions.md` first, then continue from the open stage.
- **A question about one step** — "write me an interview guide", "is 5% waitlist conversion good?". Answer it using the relevant stage section. Offer the full process once, briefly; don't force it.

For a new idea, you need four things before Stage 0 can produce anything useful. Ask for them in one message, conversationally, and accept rough answers:

1. The idea in a paragraph — what situation, who, what they struggle with. If they lead with the solution, that's fine; you'll reframe it as a problem statement together.
2. Founder constraints: time per week, money they'd spend on discovery, skills, anything they won't do.
3. What success would look like in numbers (revenue, users, exit, a job replaced).
4. Anything they already know or have tried.

Treat these as the founder's facts, not something to challenge yet. The challenging happens in Stage 0 and 1 with the assumption list.

## 2. Set up the folder

Create `discovery/` in the project (or where the founder says) with the four cross-cutting artefacts, copied from `assets/templates/`:

- `00-frame.md` — idea, constraints, success, critical path, rough economics
- `assumptions.md` — the register; one row per assumption
- `decisions.md` — one entry per gate or experiment
- `status.md` — the stage dashboard

Everything else (`01-problem-hypotheses.md`, `03-interviews/`, `05-commitment-test.md` …) is created when its stage runs. Templates for the interview note and the per-stage artefacts are also in `assets/templates/`; use them so artefacts stay comparable across stages and ideas.

If the project has a spec folder, note in `status.md` that nothing in the spec moves past `proposed` until Stage 7 authorises it.

## 3. Run stages as a default path, not a ritual

The stages are the default order. Stage 0 ends with the founder choosing a **critical path** by archetype (consumer, deep-tech, enterprise, marketplace — see the plan). That path can reorder stages or send you straight to a feasibility spike or a buyer conversation. Deviate when the critical path or new evidence says to, and write every deviation into `decisions.md` with the assumption it serves. The reason for logging is not bureaucracy: an unlogged skip is indistinguishable, three weeks later, from drift toward the comfortable work.

| Stage | Produces | You do | Founder must do |
|---|---|---|---|
| 0 Frame | `00-frame.md`, first `assumptions.md` | Draft problem statement, assumption list with tags and ranking, rough economics, archetype recommendation | Confirm constraints and success; choose the critical path |
| 1 Problem hypotheses | `01-problem-hypotheses.md` | Draft 3–5 segments with job, trigger, frequency, consequence, current solution; adversarial challenge of each | Pick which to pursue |
| 2 Landscape | `02-landscape.md`, `competitors.csv` | Competitor and substitute teardown, review mining, switching costs, the users' vocabulary | Sanity-check from domain knowledge |
| 3 Interviews | `03-interviews/`, `03-interview-synthesis.md` | Recruiting plan, interview guide, note template, synthesis after every ~5 | Run the interviews themselves — they must hear users directly |
| 4 Positioning & solution experiments | `04-positioning.md`, `04-solution-experiments.md` | Positioning statement, pitch variants, solution sketch, mock-ups or prototype copy, feasibility spike where in scope | Test pitch and concept with fresh people |
| 5 Commitment test | `05-commitment-test.md` | Landing page copy and build, concierge script, pilot proposal, measurement plan | Set the success criterion *before* launch; run the channel |
| 6 Business case | `06-business-case.md` | One-page economics in three scenarios, SAM for the segment, risk list tied to assumptions | Supply real cost and price inputs |
| 7 Decision | `07-decision.md`, updated spec | Evidence summary against the investment size, MVP learning plan draft | Decide: build / investigate / pivot / stop |

Stages 2 and 3 run in parallel once Stage 1 is done. Stage 5 can start as soon as Stage 4 has a pitch and a solution sketch.

**You cannot do the interviews for them.** You can recruit, write the guide, and synthesise, but a founder who has only read your summaries of what customers said has not done discovery. If they ask you to "just interview people", explain why you won't and offer to prepare everything so each conversation costs them thirty minutes.

Sample sizes in the plan (about 5 interviews, 3–5 concept tests) are starting points. Expand when important uncertainties remain, stop when the pattern is clear. If one experiment can answer two questions, run one.

## 4. Gates: stop, lay out the evidence, let them decide

At the end of every stage (and after any experiment), stop and present:

1. What was tested, and the success criterion that was written down beforehand
2. What was observed, with the evidence source
3. Evidence strength and its limitations — judged by the four-part test in the plan (directly tests the assumption; target customer in realistic circumstances; observed not reported; few alternative explanations)
4. Which assumptions moved, and confidence before → after
5. The decision options: **proceed**, **investigate further** (name the next experiment), **pivot** (name what changes), **stop**

Then wait. Do not pre-select for them, but do say which option the evidence points to and why, because "you decide" with no steer is unhelpful. The founder's call goes in `decisions.md` with the date and reasoning, and `status.md` is updated.

Two distinctions matter at every gate:

- **Refuted vs unresolved.** Each stage section in the plan says what each looks like there. Failing to establish an assumption (small sample, wrong audience, pitch didn't land) is not refuting it. Push back if the founder wants to kill on unresolved evidence; push back equally if they want to proceed on it.
- **Evidence sufficient for the next investment.** A day of prototyping needs little; a month of building needs credible problem evidence and some real commitment; hiring or capital needs behavioural, financial, delivery and distribution evidence from tests that addressed each directly. Say which tier the next step is in and whether the evidence meets it.

## 5. Evidence discipline

Three habits keep the register honest. Explain them to the founder once, early, and then just do them.

- **Success criterion before the test.** Write it in `assumptions.md` before a landing page goes live or a concierge week starts. A threshold chosen after the numbers come in is a rationalisation. The plan gives illustrative anchors; they are examples to be overridden with a reason, not defaults.
- **Strength is relative to the assumption.** Payment is strong for willingness-to-pay and silent on usability; ten free concierge uses are strong for value delivered and silent on price. Record what the evidence *does* support, and the limitation, every time.
- **Past behaviour over opinions.** In interview guides, ask about the last time it happened, what they did, what it cost. Never "would you use…". Use the users' vocabulary from reviews in recruiting copy and positioning, not in interview questions, where it leads the witness.

## 6. Writing the artefacts

Short and specific. One page of arithmetic beats a business plan; a problem-hypothesis table beats a persona deck. Numbers with their source; quotes in the customer's words; evidence strength stated, not implied. If a framework (SWOT, Lean Canvas, value proposition canvas) is used, fill it from evidence already gathered as a check for holes, never as the starting point.

Don't pad. A `02-landscape.md` with four competitors, two substitutes and one clearly stated gap is better than twenty rows nobody reads.

## 7. Stage 7 is a decision, not a handoff

When the evidence is in, write `07-decision.md` as an explicit investment decision: the proposed build, its tier, the evidence for and against at that tier, and the four options. If the founder chooses build, write the **MVP learning plan**: the smallest valuable end-to-end experience, the assumptions still open, constraints, launch channel, one primary outcome metric with a target and review date, diagnostic and guardrail metrics, and the criteria for expanding or stopping after release. Then update the spec's vision, target customer and first milestone from the evidence.

That plan is the contract with Stage 8 (build and measure), which is outside this skill.

## 8. Pivots and parking

A stop at any stage returns to the latest stage whose output is still valid, or jumps to whichever test the new uncertainty needs; the plan's pivot loop section lists the common moves. If the new positioning changes the problem or the promise, re-interview — a new promise to the same people is a new assumption. After three pivots without a proceed, write a review of the evidence quality and opportunity cost. Parking the idea is a legitimate outcome of that review, not an automatic one.

## Files in this skill

- `references/plan.md` — the full methodology; read the top sections at the start, each stage section before running it
- `assets/templates/00-frame.md`, `assumptions.md`, `decisions.md`, `status.md` — the cross-cutting artefacts
- `assets/templates/interview-note.md` — one note per interview
- `assets/templates/stage-artefact.md` — skeleton for the per-stage artefacts (`01-` through `07-`)
