---
name: debug-and-verify
description: Diagnose a reproducible bug, failing test, crash, or unexpected behavior and verify the root-cause fix. Use when symptoms or failures are present; do not activate for ordinary feature work.
license: MIT
compatibility: codex, opencode
---

# Debug and verify

1. Capture the exact symptom, environment, inputs, expected result, and first known failure.
2. Reproduce with the smallest command or test; preserve the original error output.
3. Trace data and control flow to form one falsifiable hypothesis at a time.
4. Add a regression test that fails for the observed reason.
5. Fix the root cause without weakening validation or suppressing errors.
6. Re-run the reproduction, regression test, neighboring tests, and static checks.
7. Distinguish confirmed cause from inference in the final report.

If reproduction is impossible, stop after evidence collection and describe the missing condition.
