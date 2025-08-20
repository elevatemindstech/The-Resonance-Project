---
title: Roadmap
description: A living, time‑boxed plan for the Resonance Project—priorities, milestones, owners, dependencies, and gates for the next 0–36+ months.
tags:
  - roadmap
  - planning
  - governance
draft: false
updated: 2025-08-20
---

# Roadmap — Resonance Project

Purpose
- Provide a clear, living plan that connects strategy → experiments → scale while preserving resonance (coherence, consent, feedback density).
- Make priorities, owners, and dependencies explicit so contributors can plug in with clarity.

How to use this page
- Read the time horizons below and find the project rows that match your interests.
- Use the Roadmap Item YAML template to propose or update initiatives (submit as an issue or PR).
- Roadmap is a coordination tool, not a prescriptive plan—expect iteration, reprioritization, and gated decisions.

---

## Time horizons & guiding priorities

- Now (0–3 months)
  - Stabilize core docs (Start Here, About, Core Frameworks, Unified Dimensions, Pilot Playbook, Glossary, Collaboration).
  - Run 3 short pilots (2–4 weeks) to test the Pilot Playbook and signal flow.
  - Harden contribution and review flows (CONTRIBUTING.md, decision log).
  - Priority: clarity, reproducibility, humane templates.

- Near (3–12 months)
  - Build pilot library and searchable synthesis archive.
  - Create Implementation Spec templates and partner intake automation.
  - Run 3–5 partner micro‑pilots (local nodes) using Harmonic Scaling checklist.
  - Priority: repeatability, interoperability, compensated facilitation.

- Mid (12–24 months)
  - Standardize protocols (consent templates, data rules, accessibility baseline).
  - Develop lightweight tooling (templates, issue/PR automation, dashboard for 3‑3‑2 signals).
  - Expand steward network and formalize partner criteria.
  - Priority: robustness, safety, distributed stewardship.

- Long (24+ months)
  - Publish field‑level guides and shareable standards (one‑page specs, policy touchpoints).
  - Cultivate an ecosystem of independent nodes using fractal specs.
  - Explore funding models and institutional partnerships to sustainably compensate core roles.
  - Priority: field resonance, sustainability, systemic partnerships.

---

## Roadmap items (high level)

Note: owners indicated as roles (Steward / Decision Owner). Use Roadmap Item Template below to propose changes.

1) Core Docs Stabilization
- Timeline: Now (0–6 weeks)
- Owner: Documentation Steward
- Dependencies: existing drafts (index.md, about.md, frameworks.md, UD, pilot-playbook.md)
- Outputs: stable, versioned docs; CONTRIBUTING.md; decision log
- Success criteria: All core pages marked stable or in‑review; CONTRIBUTING.md published; one public decision recorded.
- Gate: peer review + ethics/access review passed.

2) Pilot Suite — Run & Synthesize
- Timeline: Now → Near (0–12 weeks)
- Owner: Pilot Steward / Decision Owner per pilot
- Dependencies: Pilot Playbook, Metrics template, Inclusion checklist
- Outputs: 3 pilot syntheses (anonymized), signals dashboard, lessons-for-templates
- Success criteria: 3 pilots completed; each has synthesis with signals + decision; documented adjustments to Pilot Playbook.
- Gate: each pilot must pass consent & ethics check before launch.

3) Pilot Library & Search
- Timeline: Near (3–6 months)
- Owner: Documenter / Editor + Tooling Steward
- Dependencies: Syntheses from Pilot Suite
- Outputs: searchable library (tags, UD links, partner metadata)
- Success criteria: library with 10+ tagged syntheses; basic UI for search/filter.
- Gate: privacy check; anonymization confirmed.

4) Implementation Spec & Fractal Templates
- Timeline: Near → Mid (3–9 months)
- Owner: Frameworks Steward
- Dependencies: Pilot learnings, Harmonic Scaling patterns
- Outputs: one‑page Implementation Spec template, facilitator one‑pagers, consent bundle
- Success criteria: 3 local hosts successfully run dry runs using spec without heavy rework.
- Gate: documented local adaptations and approval by Steward.

5) Partner Program (intake → pilot → scale)
- Timeline: Mid (6–18 months)
- Owner: Partnerships Steward / Partner Liaison
- Dependencies: Implementation Spec, Partner Intake YAML, Resource map
- Outputs: partner intake flow, onboarding packet, compensation model grid
- Success criteria: 3 funded partner pilots; partner satisfaction ≥ baseline; compensation plan agreed.
- Gate: partner resonance check passed; resource commitments confirmed.

6) Signals & Dashboard Tooling
- Timeline: Mid (9–18 months)
- Owner: Metrics Steward / Tooling
- Dependencies: 3‑3‑2 metrics templates, pilot data
- Outputs: lightweight dashboard (node + aggregate view), alerting for boundary metrics
- Success criteria: dashboard ingest for pilot syntheses; weekly signal checks visible.
- Gate: privacy/data minimization audit passed.

7) Governance & Steward Network
- Timeline: Mid → Long (12–36 months)
- Owner: Governance Steward
- Dependencies: Decision log, CONTRIBUTING.md, active Stewards
- Outputs: Steward registry, consented governance norms, escalation paths
- Success criteria: named stewards for core domains; documented consent process for policy changes.
- Gate: Consent-based approval from affected stewards.

8) Field Convenings & Standards Packaging
- Timeline: Long (24+ months)
- Owner: Field Steward / Partnerships
- Dependencies: partner network, published protocols
- Outputs: field guides, policy briefs, shared protocols adopted by partner organizations
- Success criteria: at least two external organizations adopt core protocols; published case studies.
- Gate: coherence review and external peer feedback.

---

## Roadmap item template (copy into an issue)

~~~yaml
title: ""                # short name
owner: ""                # Steward or Decision Owner
timeline: "Now | Near | Mid | Long"
start_date: "YYYY-MM-DD"
end_date: "YYYY-MM-DD"
purpose: ""              # 1-2 sentences linking to resonance statement
outputs:
  - ""
dependencies:
  - ""
risks:
  - ""
success_criteria:
  - ""
gate: ""                 # what must be true to move forward (coherence, consent, resources)
status: "proposed | in-progress | in-review | blocked | complete"
links:
  - ""
~~~

---

## Prioritization & decision rules

- Safety & consent first: items that affect access, privacy, or safety require an Ethics/Access review before approval.  
- Lean experiments: prefer small, reversible pilots to validate assumptions before heavy investment.  
- Capacity-aware planning: require a resource map for any item that expands commitments across volunteers or partners.  
- Triaged prioritization: Stewards meet monthly to reprioritize based on signals, capacity, and partner interest.

---

## Cadence & coordination

- Weekly: Resonance standup (45m) — immediate signals, blockers, micro-decisions.  
- Biweekly: Roadmap & design review (60m) — review item progress, unblock, assign owners.  
- Monthly: Synthesis (90m) — publish updates, re-assess priorities, update roadmap items.  
- Quarterly: Partner resonance review & metrics synthesis — aggregated review of 3‑3‑2 across initiatives.  
- Annual: Roadmap refresh & steward consent process for major pivots.

Record minutes and decisions in the Decision Log and link them from item pages.

---

## Monitoring & signals

Use the 3‑3‑2 pattern across the roadmap to sense health and risk.

- Example mini-dashboard per major item
  - Signals: qualitative notes from participants/stewards (ease, clarity, stories)  
  - Proxies: participation rate, retention, time‑to‑decision, number of documented adaptations  
  - Boundary: opt‑out rate, incidents, unresolved access requests

Escalation: any amber/red boundary metric pauses expansion until mitigations are enacted and reviewed.

---

## Contribution & update process

- Propose: open a Roadmap Issue using the template. Attach a brief Unified Dimensions map where helpful.  
- Review: assign a Steward and an Ethics/Access reviewer for items affecting participants.  
- Approve: owner and Steward agree on timeline and resource map; item status moves to in‑progress.  
- Update: owners publish fortnightly updates to the roadmap issue.  
- Close: publish synthesis and link artifacts; change status to complete.

---

## Versioning & release notes

- Docs and templates: semantic versioning for major releases (v1.0, v1.1). Use changelog entries for each update.  
- Pilot syntheses and templates: date‑stamped; syntheses archived in Pilot Library with tags.  
- Roadmap snapshots: publish quarterly snapshots as a public changelog.

---

## Risks & mitigations

- Risk: value drift during rapid scale — Mitigation: coherence gates + partner resonance checks.  
- Risk: uncompensated hidden labor — Mitigation: require resource maps and prefer funded partners.  
- Risk: metric distortion — Mitigation: pair proxies with narrative signals; limit dashboard to 3‑3‑2.  
- Risk: accessibility failures — Mitigation: Inclusion & Access reviewer signoff for public activities.

---

## Related pages

- Start Here → [Start Here](./index.md)  
- Core Frameworks → [Core Frameworks](Frameworks%20draft.md)  
- Unified Dimensions → [Unified Dimensions](./unified-dimensions.md)  
- Pilot Playbook → [Pilot Playbook](./pilot-playbook.md)  
- Harmonic Scaling → [Harmonic Scaling](./harmonic-scaling.md)  
- Engagement & Collaboration → [Engagement & Collaboration](./collaboration.md)  
- Resonance Metrics → [Resonance Metrics](./resonance-metrics.md)  
- Glossary → [Glossary](./glossary.md)

---
