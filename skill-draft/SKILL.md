---
name: agent-merge-queue-operations
description: "Draft package-local workflow from X-Intel: Agent Merge Queue Operations. Promote only after evidence-backed trials."
version: 0.1.0-draft
---

# Agent Merge Queue Operations (Draft)

## Trigger
Use when a captured X-Intel item or active project needs this repeatable workflow:

1. Inventory open agent PRs and owners.
2. Tag each PR with risk, dependency, CI status, and required human review.
3. Rebase in queue order and rerun the proof suite.
4. Hold merges on failing CI, unclear ownership, or missing trust signals.
5. Let a human issue the final deploy/merge decision.

## Procedure
1. Start from the package trial packet, not from a blank prompt.
2. Record inputs, outputs, blockers, and human review criteria.
3. Attach evidence links before changing public claims.
4. Decide promote / pilot-only / iterate / hold.
5. Patch the package and repo only with evidence-backed wording.

## Pitfalls
- Do not treat a template as validation proof.
- Do not skip human decision gates for business-critical outputs.
- Keep source-specific claims in the package until at least one repeat trial succeeds.

## Verification
- Trial packet filled.
- Evidence table links to real files/logs/screenshots.
- README/skill claims map to evidence.
