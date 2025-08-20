---
title: Contribute
description: How to plug into the Resonance Project — pathways, expectations, templates, review flow, licensing, and practices for humane contribution.
tags:
  - contribute
  - community
  - governance
draft: false
updated: 2025-08-20
---

# Contribute — Resonance Project

Thank you for offering your time, craft, and care. This page explains how to contribute content, code, facilitation templates, or run pilots in ways that preserve consent, accessibility, and coherence. We value clarity, small reversible steps, and explicit recognition of labor.

Contents
- Contribution pathways
- How to propose an idea (issues & UD map)
- Contribution workflow (branches, PRs, reviews)
- Required reviewers & steward consent
- Templates (issue, roadmaps, PR checklist)
- Licensing, IP, and attribution
- Compensation & hidden labor
- Onboarding & mentorship
- Communication channels & response expectations
- Recognition & gratitude
- Quick start checklist

---

## Contribution pathways

- Reader / Learner — use materials; file issues for typos, errors, or clarifications.  
- Micro‑contributor — fix a typo, add alt text, small doc edit (<30 min).  
- Contributor (content) — author guides, templates, or case studies.  
- Contributor (code) — add tooling, automation, or website fixes.  
- Practitioner / Piloteer — run pilots, publish syntheses, submit templates from real runs.  
- Steward / Maintainer — hold editorial, governance, or tooling responsibilities (requires nomination/consent).

Choose the smallest meaningful action that advances quality or clarity.

---

## How to propose an idea (issue + Unified Dimensions)

Before drafting large changes, open an issue with:
- A short title and one‑line summary.
- A brief Unified Dimensions (UD) snapshot: purpose, what changes, who benefits, and one smallest next step.
- Links to related pages or pilots.

This creates shared semantics early and shortens review cycles.

Quick UD snippet to paste in issue:

~~~yaml
resonance_statement: ""
why: ""
what: ""
who: ""
smallest_next_step: ""
links: []
~~~

---

## Contribution workflow (practical)

1. Open an issue describing the change (or pick an existing issue). Attach UD snippet if relevant.  
2. Discuss scope in the issue; iterate until owner and reviewers are identified.  
3. Create a branch or fork for changes. Title branches as: contrib/<type-short-name (e.g., contrib/content-plain-language).  
4. Draft changes; include tests or acceptance criteria for operational artifacts. For content, include accessibility checks (alt text, captions, plain language).  
5. Submit a Pull Request (PR) referencing the issue. Include:
   - A short summary of changes
   - UD map (if scope affects strategy or people)
   - Reviewer requests
   - Checklist of acceptance criteria (see PR checklist below)  
6. Request reviews: at minimum one Steward and (if participant-facing) an Ethics/Access reviewer.  
7. Address feedback, squash or rebase as appropriate, and merge once approvals and any required consent are recorded.  
8. Publish a brief changelog entry and, if relevant, announce in the project's update channel.

--- 


## Required reviewers & steward consent

Who to request for review depends on the change:

- Minor content fixes (typos, formatting): one Editor or Steward.  
- New or revised templates (pilot, consent, partner intake): Steward + Ethics/Access reviewer.  
- Participant‑facing workflows, pilots, or events: Steward + Ethics/Access reviewer (explicit signoff required).  
- Governance, policy, or licensing changes: affected Stewards + Consent process (see Engagement & Collaboration).  
- Code changes affecting infrastructure or security: Tooling Steward + at least one developer reviewer.

Steward consent: for changes that alter shared norms or policies, consent from affected Stewards is required before merge.

Response expectations (target):
- Issue triage acknowledgement: 3 business days
- Initial review of PR: 7 business days
- Ethics/Access signoff: 7–10 business days (may vary with complexity)

If timelines are urgent for safety/privacy, flag as high priority and notify Steward.

---

## PR checklist (copyable)

Use this checklist in every PR description.

~~~yaml
title: ""
issue_link: ""
type: "typo|content|template|code|policy|other"
owner: ""
steward_requested: ""
ethics_access_requested: true|false
summary: ""
ud_map: ""   # short UD snippet if relevant
acceptance_criteria:
  - ""
accessibility_checks:
  - alt_text_included: true|false
  - plain_language_summary: true|false
  - captions_or_transcript_included: true|false
tests:
  - unit_or_linked_test: true|false
license_headers: true|false
steward_approval: ""
ethics_access_approval: ""
notes: ""
~~~

---

## Issue templates & Roadmap proposals

- Content or code change: open a standard issue with UD snippet.  
- Roadmap proposals: use the Roadmap item YAML template from the Roadmap page and tag "roadmap". Assign a Steward for triage.

Roadmap item quick copy (see Roadmap page):
~~~yaml
title: ""
owner: ""
timeline: "Now | Near | Mid | Long"
purpose: ""
outputs:
  - ""
dependencies:
  - ""
success_criteria:
  - ""
gate: ""
status: "proposed"
~~~

---

## Licensing, IP, and attribution

- Content: default license CC BY 4.0. Contributors retain authorship and grant the project the right to relicense derivatives under the project defaults if mutually agreed.  
- Templates & code: default license MIT or Apache‑2.0 (state chosen license in repo headers).  
- By submitting a PR you affirm you have the right to contribute the content/code and license it under the project defaults.  
- Attribution: add an authorship line in the header of longer contributions (e.g., "Author: Name — Role") where appropriate.

If external IP or third‑party content is included, add provenance and explicit permission notes to the PR.

---

## Compensation & hidden labor

We acknowledge many contributions require unpaid labor. Where possible:
- Prioritize funded work for facilitation, accessibility services (captioning, translation), and heavy documentation.  
- Request resource maps for any scaling commitments that assume volunteer labor.  
- Stewards should track and publish hidden labor estimates for projects (coordination, editing, facilitation), and advocate for compensation models in partner agreements.

If you need compensation to contribute, open an issue labeled "compensation-request" and the Partnerships Steward will advise on available options.

---

## Accessibility & ethics requirements

- Include accessible alt text for images, plain‑language summaries, and captions/transcripts for multimedia.  
- If the contribution affects participants (pilots, consent forms, facilitation scripts), an Ethics/Access reviewer must sign off before launch.  
- Use inclusive language; avoid jargon or culturally narrow metaphors when possible.

See: Inclusion & Access / Pilot Playbook / Harmonic Scaling for operational templates.

---

## Onboarding & mentorship

New contributors can:
- Pick a microtask labeled "good first issue" or "micro-contribute".  
- Request a mentor: Stewards can pair new contributors with an experienced contributor for a single iteration. Mentorship requests are handled through the issue tracker or the project's onboarding channel.

Suggested first tasks:
- Fix a typo or broken link.
- Add alt text to an image.
- Submit a plain‑language summary for a page lacking one.
- Convert a checklist into a YAML template.

---

## Communication channels & expectations

- Public repo issues & PRs are the default record for asynchronous collaboration.  
- Announcement channel / mailing list — for major releases and roadmap snapshots.  
- Working groups / discussion channels — for active design work (use meeting notes and PRs to record decisions).  
- If a private or sensitive issue arises (privacy, legal, safety), tag it and contact a Steward for a private coordination path.

Keep threads focused: convert long conversations into issues or PRs with clear next steps.

---

## Recognition & gratitude

We honor contributors by:
- Adding names to a CONTRIBUTORS.md with short bios.  
- Granting contributor badges or levels (micro‑contributor, contributor, steward) in the project README or site.  
- Spotlighting community case studies in the Pilot Library and roadmaps.  
- Offering letters of recommendation or references for sustained, high‑impact contributions when requested.

If you prefer anonymity, indicate that in your PR and we will honor it while preserving attribution where required by license.

---

## Conflict & escalation for contributions

- If a dispute arises about content, process, or attribution:
  1. Try to resolve in the issue/PR thread with curiosity and evidence.  
  2. If unresolved, request Steward mediation.  
  3. If mediation fails, follow the escalation path in Engagement & Collaboration (documented process with restorative focus).

Keep records of decisions and rationales in the Decision Log.

---

## Quick start checklist (copy & paste)

~~~text
- [ ] Read Start Here, Core Frameworks, and CONTRIBUTING.md
- [ ] Open an issue with a UD snippet for proposed changes
- [ ] Request a Steward and (if participant-facing) Ethics/Access reviewer
- [ ] Create branch contrib/<type>-short-name
- [ ] Draft changes with accessibility in mind (alt text, captions, plain language)
- [ ] Submit PR with PR checklist filled
- [ ] Address reviews and obtain required approvals
- [ ] Merge, publish changelog entry, and link from Decision Log if policy-relevant
~~~

---

## Related pages & templates

- Start Here → [Start Here](./index.md)  
- Engagement & Collaboration → [Engagement & Collaboration](./collaboration.md)  
- Pilot Playbook → [Pilot Playbook](./pilot-playbook.md)  
- Unified Dimensions → [Unified Dimensions](./unified-dimensions.md)  
- Roadmap → [Roadmap](./roadmap.md)  
- Harmonic Scaling → [Harmonic Scaling](./harmonic-scaling.md)  
- Inclusion & Access → [Inclusion and Access](./inclusion-and-access.md)

---

## Final note

We hold contribution as an act of care. Aim for small, testable changes that reduce friction and increase clarity. If you're unsure how to start, open an issue with a UD map and a one‑sentence request: someone will help you convert it into a microtask.

Thank you for contributing with presence and care.
