# Agent Merge Queue Loop

Source: [[DeployBot as Agent Merge Queue]]  
Package: [[Agent Merge Queue Kit]]

```text
Source signal
   ↓
Workflow inputs
   ↓
Agent execution
   ↓
Evidence packet
   ↓
Human decision gate
   ↓
README / prototype / skill patch
```

## Why the loop matters
DeployBot turns the agent-code bottleneck from “can it write code?” into “can we safely sequence, rebase, verify, and land many PRs without losing human release control?”

## Guardrail
This artifact explains the intended workflow. It is not validation proof until a real trial packet is completed.
