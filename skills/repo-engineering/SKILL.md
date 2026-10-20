---
name: repo-engineering
description: Implement or refactor a feature in an existing repository with scoped discovery, explicit interfaces, minimal patches, tests, and a concise handoff. Use for coding requests; do not use for read-only reviews.
license: MIT
compatibility: codex, opencode
---

# Repository engineering

1. Read repository instructions and inspect Git status before editing.
2. Locate the existing implementation, callers, tests, and configuration using targeted search.
3. State the behavioral contract and the smallest file set that can satisfy it.
4. Add or update a focused test before the implementation when behavior is testable.
5. Apply the smallest coherent patch; preserve unrelated user changes.
6. Run the narrow test first, then the relevant broader suite.
7. Report changed files, verification evidence, compatibility notes, and remaining risk.

Do not push, deploy, delete data, rotate credentials, or change external systems without explicit authorization.
