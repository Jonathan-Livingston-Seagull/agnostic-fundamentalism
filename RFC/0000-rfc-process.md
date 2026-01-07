# AF-RFC Process (0000)
**Status:** Active
**Purpose:** Evolve AF documents and modules safely, transparently, and without capture.

## What is an RFC?
An RFC is a proposed change to:
- the AF-0 kernel (CHARTER/AF-0.md)
- BIOS services (BIOS/*)
- modules (MODULES/*)
- metrics (MVP/METRICS.md and related specs)
- conduct/sanctions (MVP/CONDUCT.md, MODULES/justice/*)
- the Kudos Ledger spec (LEDGER/AF-KL-0.1.md)

If it affects high-stakes governance or sentience protections, it must be an RFC.

## Principles
- Forkable: disagreement is allowed; peaceful divergence is a feature.
- Evidence-bound: high-stakes changes require provenance and uncertainty.
- Anti-Goodhart: anything that becomes a metric needs a gaming plan and a kill-switch.
- No epistemic monopoly: dissent is protected; critique is not disloyalty.
- No cruelty license: kernel constraints override all plugins.

## RFC States
1) Draft
2) Under Review
3) Provisional (Trial)
4) Accepted
5) Rolled Back
6) Deprecated (replaced by a newer RFC)

## When is an RFC required?
Required when a change:
- touches AF-0 constraints, justice, consent, sentience, or fork rights
- introduces/changes a metric
- changes sanctions or dispute processes
- changes governance power flows (roles, audits, decision rules)
- is hard to reverse or likely to be gamed

Optional for: spelling fixes, formatting, clarifications that do not change meaning.

## Decision Rules (minimal)
- Default: prefer rough consensus + documented dissent.
- If consensus fails: either (a) run a bounded trial, or (b) fork.
- No forced unity: forks are safer than coercion.

## Review Requirements (minimum)
Every RFC must include:
- a kernel compatibility check (sentience, forkability, no monopoly, superposition)
- risks & failure modes (including gaming vectors)
- evaluation plan (how we’ll know)
- rollback plan + sunset date (for high-stakes changes)

## Red Teaming
High-stakes RFCs require a red-team section:
- strongest objections
- how an adversary would exploit it
- mitigations and remaining vulnerabilities

## Trial / Sandbox
Whenever feasible:
- run as Provisional for a fixed period
- measure pre-defined outcomes
- publish a postmortem
- accept or rollback based on evidence (not vibes)

## Recording Decisions
- Accepted RFCs move to `RFC/accepted/`
- Rollbacks remain in history with a short “why”
- Significant outcomes go in the Kudos Ledger changelog

## Conduct During Process
- Critique ideas, not identities.
- Steelman opponents before disagreeing.
- No humiliation rituals.
- If conflict escalates, route to mediation before escalation.

## Fast Path (urgent safety fixes)
For urgent harm prevention:
- temporary patch may be applied
- must be followed by a full RFC within 14 days
- auto-sunsets unless ratified
