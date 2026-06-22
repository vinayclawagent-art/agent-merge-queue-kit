# Merge Queue Post-Trial Debrief Template

Source: [[DeployBot as Agent Merge Queue]]  
Package: [[Agent Merge Queue Kit]]  
Prerequisites: [[Merge Queue Trial Packet]] and [[Merge Queue Trial Evidence Index]]

## Purpose
Turn a completed two-agent-PR merge-queue dry run into explicit README, prototype, infographic, and package-local skill decisions. This is a template-ready gate only; do not fill it with guessed outcomes.

## Before filling this debrief
- [ ] The trial packet identifies at least two agent PRs, owners, risk levels, and intended queue order.
- [ ] CI URLs/log excerpts, rebase/conflict notes, and human review/deploy decisions are linked in the evidence index.
- [ ] Failing or blocked PRs remain visible in the evidence, not scrubbed from the story.
- [ ] No public claim has been strengthened before the rows below are complete.

## Trial summary
- Trial date:
- Operator:
- Repo / branch set tested:
- PRs in queue:
- CI suite / proof commands:
- Evidence folder / issue / repo path:

## What happened
| Question | Answer | Evidence link/path |
|---|---|---|
| Were two or more agent PRs sequenced before merge? |  |  |
| Did CI proof hold or advance each PR? |  |  |
| Did rebasing expose conflicts, stale assumptions, or hidden dependencies? |  |  |
| Did a human retain the final merge/deploy decision? |  |  |
| What queue rule changed after the dry run? |  |  |

## Claim-to-patch decisions
| Proposed claim or change | Evidence row supporting it | Allowed wording | Patch target | Decision |
|---|---|---|---|---|
| The queue safely sequenced multiple agent PRs. |  | Say only "sequenced in one dry run" unless merged PR links and CI proof are attached. | Package README / root README |  |
| The workflow improved human release control. |  | Mention human control only when review/deploy timestamp is attached. | Prototype README / infographic |  |
| The skill draft is ready to promote. |  | Promote only after the queue sequence repeats with clear verification steps. | Skill draft / installed skill decision |  |
| A queue rule should become mandatory. |  | Tie each rule to CI/rebase/review proof. | Prototype packet / backlog |  |

## Decision
Choose exactly one after evidence is attached:
- [ ] Promote: patch README/prototype wording and prepare the package-local skill for installed-skill review.
- [ ] Pilot-only: keep the package active and run one more two-PR dry run before public claims change.
- [ ] Iterate: patch the trial packet, evidence index, or queue rules because the proof slots were insufficient.
- [ ] Hold: evidence is too thin or the workflow is not worth repeating.

## Follow-up patch queue
- Package README:
- Prototype README:
- Infographic/spec:
- Skill draft:
- GitHub issue or repo README:

## Notes
Template-ready only. This debrief becomes evidence only after the prerequisite packet and evidence index contain real CI/rebase/review/merge links.
