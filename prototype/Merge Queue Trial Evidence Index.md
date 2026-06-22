# Merge Queue Trial Evidence Index

Source: [[DeployBot as Agent Merge Queue]]  
Package: [[Agent Merge Queue Kit]]  
Companion packet: [[Merge Queue Trial Packet]]

## Purpose
A fillable evidence index for a two-agent-PR merge-queue dry run. It maps each proof item to the claim it can support, the wording it permits, and the exact package/prototype/skill patch target. Keep this template evidence-pending until real links/files are attached.

## Trial metadata
- Date:
- Operator:
- Repo/doc/workflow under test:
- Baseline comparison:
- Evidence folder or issue:

## Evidence-to-claim map
| Proof item to attach | Claim it may support | Patch target | Allowed wording guardrail | Evidence link/path |
|---|---|---|---|---|
| Queue setup screenshot or issue list | Two or more agent PRs were scoped before sequencing. | README current status, package why-it-matters | Only say “tested on queued PRs” if both PR identifiers and owners are attached. |  |
| CI run URLs/log excerpts | CI proof was sufficient to hold or advance each PR. | Prototype README, skill draft verification step | Allowed wording must name pass/partial/fail; no blanket “safe merge” claim. |  |
| Rebase/conflict transcript | The queue exposed blockers that normal parallel agent work hides. | Infographic loop, package backlog | Use “identified blockers” unless the conflict was fully resolved and verified. |  |
| Human review/deploy decision | A human kept final release control. | README next step, skill draft decision gate | Promotion requires timestamped human decision plus merge/deploy outcome. |  |

## Claim safety checks
- [ ] Every stronger claim has a concrete evidence link/path.
- [ ] Partial/failing proof is preserved instead of hidden.
- [ ] README/prototype/skill wording is narrowed when proof is thin.
- [ ] Promotion/pilot-only/iterate/hold decision is made only after this index and the trial packet are complete.

## Patch queue after evidence exists
| Target | Proposed patch | Evidence row | Decision |
|---|---|---|---|
| Package README |  |  |  |
| Prototype README/template |  |  |  |
| Infographic/spec |  |  |  |
| Skill draft or no-skill note |  |  |  |

## Notes
Template-ready only. Do not treat this index as validation proof until the table contains real screenshots, logs, exported docs, or repo links.
