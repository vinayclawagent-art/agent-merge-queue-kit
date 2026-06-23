# Merge Queue Trial Operator Handoff Checklist

Status: operator-ready, evidence-pending. This checklist sequences the existing packet, evidence index, and debrief template for the next two-agent-PR dry run. It does not claim validation.

Source package: [[Agent Merge Queue Kit]]  
Loop: [[Agent Merge Queue Kit Loop]]

## 1. Scope the dry run

- Trial repo / branch:
- Agent PR #1 goal:
- Agent PR #2 goal:
- Human release owner:
- Allowed automation actions:
- Explicit stop conditions:

## 2. Pre-run artifact sequence

| Step | Artifact | Operator action | Done |
|---|---|---|---|
| 1 | [[Merge Queue Trial Packet]] | Fill trust rules, PR inputs, CI expectations, rebase policy, and final human deploy gate before starting. | [ ] |
| 2 | [[Merge Queue Trial Evidence Index]] | Pre-create rows for CI logs, rebase events, review comments, queue ordering, and final merge/hold decision. | [ ] |
| 3 | [[Merge Queue Post-Trial Debrief Template]] | Leave blank until packet and index have real links; do not complete from memory. | [ ] |

## 3. Evidence routing during run

| Evidence item | Where to capture it | Claim it can support later | Current allowed wording |
|---|---|---|---|
| CI run links for each PR | Trial evidence index | Whether the queue catches failures before merge | "designed to collect CI proof" |
| Rebase/conflict notes | Trial packet + evidence index | Whether the operator can resolve sequencing issues safely | "includes rebase handling fields" |
| Human review decision | Trial packet final gate | Whether release control stayed human-owned | "requires a final human deploy gate" |
| Merge/hold outcome | Debrief template | Whether to promote, pilot-only, iterate, or hold | "evidence pending" |

## 4. Post-run decision order

1. Attach all links/files to [[Merge Queue Trial Evidence Index]].
2. Complete [[Merge Queue Post-Trial Debrief Template]] using only captured evidence.
3. Choose one outcome: promote / pilot-only / iterate / hold.
4. Patch README, prototype, infographic, or skill draft claims only where the evidence index and debrief name an exact target.

## 5. Handoff notes

- Missing evidence:
- Surprising queue behavior:
- Human-control risk observed:
- Recommended next patch:

## Safety rule

Do not strengthen public claims until the evidence index and debrief are filled with real/sanitized trial proof.
