# Agent Merge Queue Kit Prototype

Source: [[DeployBot as Agent Merge Queue]]

## Current artifact
Use [[Merge Queue Trial Evidence Index]] after the trial packet to route proof into safe public wording and patch targets.

Use [[Merge Queue Trial Packet]] as the next-run packet. It is designed to gather proof, not claim validation.

## What it demonstrates
A fillable trial packet for routing two or more agent PRs through trust rules, CI proof, rebase handling, and a final human `deploy` gate.

## How to use
1. Pick one real or sanitized workflow.
2. Fill the packet before the agent run.
3. Attach evidence during the run.
4. Complete the decision section before patching README, repo, or skill claims.

## Latest improvement
- 2026-06-22: Added [[Merge Queue Trial Evidence Index]] so future proof is mapped to README/prototype/skill patch decisions before claims change. Status: template-ready, evidence-pending.

## Trial evidence index
- [[Merge Queue Trial Evidence Index]] — after the dry run, map each CI log, rebase note, review decision, and merge outcome to safe README/prototype/skill wording before patching public claims. Template-ready; evidence pending.
