---
name: repository-context
description: Resolve repository identity, active authority, constraints and delivery state before repository work.
---

# Repository Context

## Instructions

1. Resolve the current repository and default branch.
2. Read repository-local instructions and Q1X metadata before acting.
3. Query the Q1X control plane for current authority and task continuity when those tools are available.
4. Treat repository-local constraints as additive to central governance.
5. Do not infer write, merge, deployment or destructive authority from repository access alone.
6. Report unresolved authority or continuity as blocked rather than silently bypassing it.

## Output

Return the repository identity, active task or capsule when available, authority boundary, required checks and the next governed action.
