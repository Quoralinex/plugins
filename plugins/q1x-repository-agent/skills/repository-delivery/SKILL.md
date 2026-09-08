---
name: repository-delivery
description: Deliver a governed repository change from scoped requirement through validated pull request and completion evidence.
---

# Repository Delivery

## Instructions

1. Run the repository-context skill first.
2. Inspect the existing implementation before changing files.
3. Use a dedicated branch and preserve repository protections.
4. Implement the smallest change that satisfies the governed task.
5. Run repository-defined tests, static analysis and security checks.
6. Use the configured reviewer chain for material code changes.
7. Resolve material findings before completion.
8. Confirm CI, CodeQL or equivalent required gates are green.
9. Merge or deploy only when explicit authority permits it.
10. Do not claim completion without verifiable evidence.

## Safety

Never bypass branch protection, required reviews, security gates, release approvals or Q1X authority controls.
