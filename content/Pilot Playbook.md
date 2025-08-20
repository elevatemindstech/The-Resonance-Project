---
title: Pilot Playbook
description: Design, run, and learn from small tests with integrity—clear scope, consent, access, and feedback.
tags:
  - pilots
  - practice
  - integration
  - ethics
  - access
draft: false
updated: 2025-08-20
---

# Pilot Playbook

Turn ideas into learning with humane scope, clear ethics, and strong feedback. Pilots are timeboxed, reversible experiments that validate value, refine design, and protect participant energy.

## When to use

- You have a promising concept and need real‑world signals before investing more.  
- You want to de‑risk scaling by validating coherence, access, and governance.  
- You’re comparing alternative approaches on a small, safe scale.

## Principles

- **Small & humane** — Minimal scope, reversible decisions, clear boundaries.  
- **Consent & care** — Plain language, opt‑in/out, inclusion and access by default.  
- **Learning over winning** — Publish lessons, not just successes.  
- **Coherence** — Trace Why → What → How back to the resonance statement at every gate.

Related: [Unified Dimensions](Unified%20Dimensions.md) • [Resonance Metrics](./resonance-metrics.md) • [Inclusion & Access](./inclusion-and-access.md)

---

## Roles (lightweight)

- **Decision Owner** — accountable for scope, gates, and final decisions.  
- **Facilitator** — holds process, timeboxes sessions, and attends to pacing.  
- **Ethics / Access Reviewer** — validates consent, inclusion, and do‑no‑harm practices.  
- **Documenter** — captures run logs, signals, and synthesis.  
- **Partner Liaison** (optional) — coordinates hosts and collaborators.

> Tip: In very small pilots one person may hold multiple roles.

---

## Pilot brief (YAML template)

Copy this block into an issue, note, or repo file to define the pilot formally.

~~~yaml
pilot_title: ""
steward: ""            # Decision Owner
facilitator: ""
ethics_access_reviewer: ""
documenter: ""
partners: []

purpose: ""            # 1-2 sentences linking to resonance statement
hypothesis: "We believe that [change] for [people] will result in [outcome]."
beneficiaries: []      # Primary groups impacted/benefiting

scope:
  timebox_weeks: 2     # recommended 2–4
  participants: "8-15" # small, humane group
  boundaries:          # explicit "what we will NOT do"
    - ""
  artifacts:           # expected outputs
    - ""

success_criteria:      # 2–3 observable signals/proxies
  - ""

consent_and_ethics:
  consent_mode: "plain-language form | verbal with recording"
  data_minimization: true
  opt_out_path: "email/contact or button/link"
  risk_mitigations:
    - ""

inclusion_access:
  accommodations_offered:
    - "captions/transcript"
    - "screen-reader friendly docs"
    - "breaks/quiet mode"
  contact_for_access: "name@email"

feedback_plan:
  methods: ["short survey", "resonance circle", "brief interviews"]
  cadence: "end of each session + final synthesis"
  steward: ""

metrics_3_3_2:
  signals: ["felt ease/clarity", "story of value", "self-initiated invites"]
  proxies: ["retention %", "decision cycle time", "rework rate"]
  boundary: ["opt-outs honored", "incident count/resolution time"]

risks_assumptions:
  risks:
    - ""
  assumptions:
    - ""

schedule:
  start: "YYYY-MM-DD"
  mid_check: "YYYY-MM-DD"
  end_synthesis: "YYYY-MM-DD"

decision_gate:
  options: ["keep", "change", "stop", "scale-with-guards"]
  criteria_notes: ""
~~~

---

## Consent & ethics (practical guidance)

- Use plain language: state purpose, activities, time commitment, benefits/risks, data handling, and opt‑in/out options.  
- Make participation voluntary: ensure easy exit without penalty.  
- Minimize data collection: only keep what you need and define retention and deletion.  
- Offer trauma‑informed options: pauses, breaks, off‑camera or non‑verbal participation modes.  
- Default to privacy: anonymize reports; obtain explicit permission for names/quotes.

Consent snippet (copy/paste):

~~~text
Purpose: [one sentence].
What you’ll do: [bullets].
Time: [X minutes / sessions].
Risks/benefits: [short].
Data: [what is collected, storage, retention].
Participation is voluntary. You can opt out at any time by [how].
Questions or accommodations: [contact details].

I consent to participate: Yes / No   Name (optional): ____   Date: ____
~~~

More detail: [Inclusion & Access](./inclusion-and-access.md)

---

## Access & inclusion checklist

- Content: plain‑language summary at the top; slides/docs with alt text; captions/transcripts.  
- Timing: humane scheduling; predictable breaks; time‑boxed sessions.  
- Tech: low‑bandwidth alternatives; clear instructions for tools; screen‑reader friendly docs.  
- Environment: offer multiple participation modes (chat, voice, async); provide a quiet channel.  
- Ask participants: "What would support your participation?" and honor reasonable requests.

---

## Risk & safety

- Identify foreseeable risks (confusion, privacy concerns, emotional triggers) and mitigation steps.  
- Create an escalation path (who to contact; how to pause/stop).  
- Run a pre‑mortem: "If this pilot failed, why?" and add mitigations before launch.

---

## Data & privacy

- Collect the minimum necessary data; avoid sensitive data where possible.  
- Secure storage and role‑based access controls.  
- Delete data according to the retention policy agreed in the pilot brief.  
- Publish aggregated, anonymized learnings by default; surface raw data only with explicit consent.

---

## Run plan (example cadence)

- **Week 0 (Design)** — finalize brief, consent language, access checks, dry run.  
- **Week 1 (Run)** — session 1; capture signals; adjust small scope items.  
- **Week 2 (Run)** — session 2; mid‑check for coherence, risks, access.  
- **Week 3 (Run)** — session 3; gather feedback; draft learnings.  
- **Week 4 (Synthesize)** — final session; synthesis; decide; publish report.

Shorter pilots (2 weeks) compress to kickoff → mid‑check → synthesis.

---

## Feedback instruments

### Micro‑survey (3–5 items)

1. Clarity: I understood the purpose and what was being asked. (1–5)  
2. Ease: This felt humane and manageable. (1–5)  
3. Value: I experienced or can imagine concrete value. (1–5)  
4. Inclusion: My participation needs were met. (1–5)  
5. Open: What worked? What could be improved?

### Interview guide (10–15 min)

- What did you hope to get? What actually happened?  
- Where did you feel ease or friction? Any moment that stood out?  
- What would make this more inclusive or accessible?  
- If we kept one thing and changed one thing, what should they be?

### Resonance circle (20–30 min)

- Round 1: One sentence — what felt aligned?  
- Round 2: One sentence — what drifted?  
- Round 3: One request or offer.

Facilitator: synthesize themes, capture 3 insights, name one next step.

---

## Selecting metrics (3‑3‑2 pattern)

- **Signals (qualitative)** — felt ease/clarity; story of value; self‑initiated invites.  
- **Proxies (quantitative)** — retention/completion; decision cycle time; rework rate.  
- **Boundary (safety/harm)** — opt‑outs honored; incident count and resolution time.

See: [Resonance Metrics](./resonance-metrics.md)

---

## Synthesis & decision template

Use this to conclude and publish the pilot findings.

~~~markdown
# Pilot Synthesis

**Purpose & Hypothesis**
- Purpose (link): …
- Hypothesis: …

**What Happened**
- Activities: …
- Participation: …

**Signals & Metrics**
- Signals (qualitative): …
- Proxies (quantitative): …
- Boundary metrics: …

**Insights (Top 3)**
1. …
2. …
3. …

**Decision**
- Chosen option: Keep | Change | Stop | Scale-with-guards
- Rationale: …
- If scaling: partner criteria, coherence checks, additional mitigations.

**Next Steps**
- Owner: …
- Timeline: …
- Updated docs/links: …
~~~

Publish the synthesis with anonymized data by default.

---

## Anti‑patterns (to avoid)

- Big‑bang pilots with too many variables and unclear learning goals.  
- Hidden governance — no decision owner or fuzzy success criteria.  
- Collecting excess data without clear use or retention policy.  
- Ignoring access requests or consent boundaries.  
- Treating pilots as one‑off events rather than iterative learning loops.

---

## Compact example

- **Purpose:** Test a weekly "resonance standup" to reduce meeting fatigue.  
- **Hypothesis:** A 20‑minute ritual will reduce decision latency and increase clarity.  
- **Scope:** 3 weeks, 10 participants, Zoom + shared doc; no recording.  
- **Success criteria:** Decision latency drops by 20%; participant clarity ≥ 4/5.  
- **Consent & access:** Plain‑language consent; captions; camera‑optional.  
- **Feedback:** Micro‑survey + final resonance circle.  
- **Decision:** Keep with a shorter agenda; publish one‑pager template.

---

## Related pages

- Context mapping → [Unified Dimensions](Unified%20Dimensions.md)  
- Pathway → [Idea‑to‑Field Workflow](./workflow.md)  
- Phases → [Five Phases](./phases.md)  
- Metrics → [Resonance Metrics](./resonance-metrics.md)  
- Inclusion → [Inclusion & Access](./inclusion-and-access.md)

---
