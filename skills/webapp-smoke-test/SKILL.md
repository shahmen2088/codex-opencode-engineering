---
name: webapp-smoke-test
description: Validate a local web application after UI or integration changes using browser interactions, screenshots, console inspection, and a short critical-path checklist. Use when a runnable local web UI exists.
license: MIT
compatibility: codex, opencode
---

# Web-app smoke test

1. Identify the supported start command, base URL, test account constraints, and critical user path.
2. Start or reuse the local app without altering production data.
3. Exercise navigation, primary action, empty/error states, and one responsive viewport.
4. Inspect browser console and failed network requests.
5. Capture screenshots only when they prove layout or state.
6. Record exact steps and classify failures as product, environment, or test-data issues.

Never infer that a page works solely because it renders; verify the requested interaction and resulting state.
