# Agent Merge Queue Kit Prototype

Source: [[DeployBot as Agent Merge Queue]]

## Current artifact
Use [[Merge Queue Trial Packet]] as the next-run packet. It is designed to gather proof, not claim validation.

## What it demonstrates
A fillable trial packet for routing two or more agent PRs through trust rules, CI proof, rebase handling, and a final human `deploy` gate.

## How to use
1. Pick one real or sanitized workflow.
2. Fill the packet before the agent run.
3. Attach evidence during the run.
4. Complete the decision section before patching README, repo, or skill claims.

## Latest improvement
- 2026-06-22: Created the first trial packet and GitHub mirror. Status: template-ready, evidence-pending.
