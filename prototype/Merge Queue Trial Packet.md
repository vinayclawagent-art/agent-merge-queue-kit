# Merge Queue Trial Packet

Source: [[DeployBot as Agent Merge Queue]]  
Package: [[Agent Merge Queue Kit]]

## Trial setup
- Date:
- Operator:
- Real/sanitized workflow:
- User/customer being simulated:
- Input files/links:
- Agent/tool being tested:
- Baseline manual process:

## Workflow sequence
1. Inventory open agent PRs and owners.
2. Tag each PR with risk, dependency, CI status, and required human review.
3. Rebase in queue order and rerun the proof suite.
4. Hold merges on failing CI, unclear ownership, or missing trust signals.
5. Let a human issue the final deploy/merge decision.

## Evidence capture
| Claim to test | Evidence link/path | Pass / partial / fail | Notes |
|---|---|---|---|
| The workflow can be scoped clearly before the run. |  |  |  |
| The agent output is inspectable by a human. |  |  |  |
| The proof is strong enough to change package wording. |  |  |  |
| The workflow is repeatable with another source/task. |  |  |  |

## Decision gate
Choose exactly one after evidence is attached:
- [ ] Promote into a stronger reusable workflow.
- [ ] Pilot-only: useful, but needs one more trial.
- [ ] Iterate: keep package active and patch the prototype.
- [ ] Hold: evidence too thin or workflow not worth repeating.

## Patch queue
- README changes:
- Prototype changes:
- Skill draft changes:
- GitHub issue/backlog changes:

## Notes
Template-ready only. Do not use this packet as proof until the evidence table is filled with real links or files.
