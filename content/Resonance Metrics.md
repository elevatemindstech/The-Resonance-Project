---
title: Resonance Signals and Metrics
description: Lightweight mixed‑methods sensing—qualitative signals, quantitative proxies, and boundary metrics to keep resonance visible without letting metrics lead.
tags:
  - metrics
  - signals
  - monitoring
  - pilots
  - governance
draft: false
updated: 2025-08-20
---

# Resonance Signals and Metrics

A practical, humane approach to sensing alignment: use small, mixed‑methods dashboards that pair lived narrative with simple quantitative proxies and safety/boundary metrics. Metrics are mirrors, not masters—always interpret numbers alongside participant stories and steward reflection.

This page describes the 3‑3‑2 pattern, how to choose signals and proxies, cadence and synthesis practices, templates you can copy, cautions and anti‑patterns, and examples for pilots, nodes, and roadmap items.

---

## Why this matters

- Maintain coherence as projects move from idea → pilot → scale.  
- Detect drift early (loss of consent, declining feedback density, hidden labor).  
- Make learning public and accountable without weaponizing data.  
- Support decisions with both evidence and narrative.

Related: [Pilot Playbook](./pilot-playbook.md) • [Harmonic Scaling](./harmonic-scaling.md) • [Roadmap](./roadmap.md)

---

## Core pattern: 3‑3‑2

A small, intentional dashboard pattern.

- Signals (3 qualitative) — felt & behavioral indicators (stories, ease, invitations).  
- Proxies (3 quantitative) — simple counts or latencies that stand in for alignment (retention, decision time, rework).  
- Boundary metrics (2) — safety & harm indicators (opt‑outs, incidents, burnout proxies).

Keep dashboards small. Choose measures that are meaningful to your stakeholders and feasible to collect with consent.

---

## Definitions & examples

Signals (qualitative)
- Felt ease / friction: participants describe how manageable the experience felt.  
- Clarity voiced: participants reference resonance statement or express clear next steps.  
- Emergent stories of value: short anecdotes of change or application.  
Example collection methods: one‑sentence exit prompts, resonance circles, short interviews.

Proxies (quantitative)
- Retention / completion rate: percent of participants who finish a timebox or activity.  
- Decision latency: time between identifying an action and it being owned/closed.  
- Rework rate: proportion of artifacts or sessions that required significant revision.  
Example: retention = participants completed ÷ participants started.

Boundary metrics (do‑no‑harm)
- Opt‑out / drop rate: people leaving or declining participation (with reasons).  
- Incident count & resolution time: number of safety/privacy incidents and time to remediate.  
Also consider compensation gaps or recurring accommodation denials as boundary alerts.

---

## How to choose metrics (practical)

1. Link to purpose: start from your resonance statement → which outcomes matter?  
2. Prioritize signals first: pick the 3 qualitative indicators you will listen for.  
3. Select low‑friction proxies: choose measures you can collect with consent and minimal overhead.  
4. Choose boundary metrics that will pause expansion if triggered.  
5. Keep it feasible: opt for measures you can review weekly or biweekly.

Quick checklist:
- Does each metric relate to Why/What/How?  
- Can we collect this without harming participants?  
- Will this metric help a steward decide keep/change/stop?

---

## Collection methods & instruments

Weekly signal check (15 min)
- Quick round in a team standup or asynchronous doc: each steward answers 1–2 signal prompts (ease, story).

Micro‑survey (end of session, 1–3 minutes)
- 3 items: Clarity (1–5), Ease (1–5), Value (1–5) + one open field for a short story.

Resonance circle (20–30 min)
- Structured rounds: aligned / drifted / request — capture verbatim quotes (with consent) and synthesize.

Short interviews (10–15 min)
- Ask for examples, pain points, suggestions; prioritize diverse voices and those closest to impact.

Automated proxies
- Retention/completion from sign‑up lists (with opt‑out consent).  
- Decision latency from issue tracker timestamps.  
- Rework measured via number of significant revisions or iterations documented.

Data governance
- Collect only what you need; store minimally; anonymize before publishing syntheses unless explicit consent exists for attribution. See Pilot Playbook for consent templates.

---

## Cadence & synthesis

- Weekly (15 min): signal check — capture quick qualitative flags and any red boundary hits.  
- Monthly (synthesis, 60–90 min): combine micro‑surveys, resonance circles, and proxy trends; create an anonymized summary.  
- Quarterly (pattern review): look across pilots/nodes for systemic patterns (energy economics, recurring access gaps).

Synthesis template (use in pilot/library entries)
```yaml
period: "YYYY-MM"
item: ""
signals:
  - name: "Felt ease"
    evidence: "quotes or summary"
proxies:
  - name: "Retention"
    value: "85%"
boundary:
  - name: "Opt-outs"
    value: "2 (reasons: X,Y)"
insights:
  - ""
decision:
  - option: "keep|change|stop|scale-with-guards"
    rationale: ""
next_steps:
  - owner: ""
    by: "YYYY-MM-DD"
```
---
## Dashboard examples (compact)

Pilot node mini‑dashboard (weekly)

- Signals: 3 one‑line notes (ease, clarity, story)
- Proxies: retention %, avg. session rating (1–5), # of follow‑ups requested
- Boundary: opt‑outs this week, incident flagged (Y/N)

Aggregate scaling dashboard (monthly)

- Node retention distribution chart
- Median decision latency (days) across nodes
- Count of documented adaptations (proxy for local autonomy)
- Boundary alerts: nodes with opt‑out > threshold

Visualization placeholders (for designers)

- Small multiples for node-level retention.
- Sparkline for weekly avg signal scores.
- Incident heatmap by node/time.

---

## Templates (copyable)

Signals capture (inline text)

```text

textCopy block
Date: YYYY-MM-DD
Node/Pilot: ""
Signal - Felt ease (one sentence): ""
Signal - Clarity (one sentence): ""
Signal - Story (one short anecdote): ""
Any boundary alerts? (opt-out/incident): ""
```

Micro‑survey (copy)

```text

textCopy block
1. I understood the purpose. (1–5)
2. This felt humane / manageable. (1–5)
3. I experienced concrete value or can imagine it. (1–5)
4. If you can, share one short example or friction point:
```

Proxy calculation note (example)

```text

textCopy block
Retention % = (participants_completed / participants_started) * 100
Decision latency (days) = median(days_between_issue_created_and_closed)
Rework rate = significant_revisions / total_artifacts
```

Boundary alert rule (example)

```text

textCopy block
If opt_out_rate > 10% OR incident_count > 0 in current week => flag "pause and review"
```

---

## Interpreting metrics: pairing numbers with narrative

- Always ask: what story does this number suggest? Seek corroborating voices.
- Probe contradictions: high retention but low qualitative value suggests inertia or lack of alternatives.
- Use boundary metrics as hard gates: do not scale while boundary metrics are amber/red.

Example interrogation flow

1. Retention ↓ — ask: who is leaving and why? (interview, opt‑out reasons)
2. If reasons point to access or timing → run a micro‑pilot addressing that bridge (see Barriers & Bridges).
3. Reassess with 3‑3‑2 after 2–4 weeks.

---

## Integration with pilots, roadmap, and governance

- Pilots: include 3‑3‑2 block in every Pilot brief. Review signals weekly during pilot and synthesize monthly.
- Roadmap items: add a mini‑dashboard as part of the Roadmap item page so stewards can triage.
- Governance: require Ethics/Access signoff for metrics that collect personal or sensitive data. Include a steward responsible for monitoring boundary metrics.

---

## Cautions & anti‑patterns

- Metric worship: treating proxies as sole decision drivers. Always pair with signals.
- Data hoarding: collecting more than needed or retaining identifiable raw data unnecessarily.
- Perverse incentives: designing proxies that encourage gaming or reduce participant dignity.
- Over‑measurement: dashboards that impose heavy reporting burden and reduce feedback density.
- Ignoring context: comparing nodes without accounting for local adaptation and resource differences.

Remedy: favor small, high‑value metrics and prioritize qualitative sensemaking.

---

## Accessibility & ethics reminders

- Explain what will be collected and why; secure consent.
- Offer opt‑out and alternative reporting routes for people who prefer not to provide metrics.
- Provide accessible formats for surveys and syntheses.
- Publish anonymized summaries by default. See Pilot Playbook for consent language.

---

## Example scenarios (compact)

1. Short pilot (3 weeks)

- Signals: weekly resonance circle notes.
- Proxies: retention %, avg micro‑survey score.
- Boundaries: opt‑out count; zero incidents target.  
    Outcome: pilot synthesis shows high clarity but low follow‑through → adjust success criteria and run follow‑up 2‑week micro‑pilot.

2. Scaling across 5 nodes

- Node dashboards aggregated monthly.
- Watch for nodes with low feedback density (fewer than 1 signal report/week) — treat as amber; assign Steward support.

---

## Next steps & practices for stewards

- Require 3‑3‑2 block in pilot briefs and roadmap items.
- Set default weekly cadence for signal capture and monthly syntheses.
- Train stewards on pairing narratives with proxies and on boundary escalation protocols.
- Publish a lightweight how‑to for contributors on collecting consented metrics (sample consent snippets are in Pilot Playbook).

---

## Related pages

- Pilot Playbook → [Pilot Playbook](./pilot-playbook.md)
- Harmonic Scaling → [Harmonic Scaling](./harmonic-scaling.md)
- Barriers & Bridges → [Barriers and Bridges](./barriers-and-bridges.md)
- Roadmap → [Roadmap](./roadmap.md)
- Engagement & Collaboration → [Engagement & Collaboration](./collaboration.md)
- Glossary → [Glossary](./glossary.md)