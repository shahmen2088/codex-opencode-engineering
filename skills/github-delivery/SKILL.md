---
name: github-delivery
description: Prepare and publish a verified Git branch, pull request, or release to GitHub after explicit user authorization. Use for GitHub delivery; do not use merely because a repository has a remote.
license: MIT
compatibility: codex, opencode
---

# GitHub delivery

1. Confirm the target repository, visibility, branch, base branch, and requested artifact.
2. Verify a clean or intentionally scoped working tree and review the diff for secrets and generated noise.
3. Run the required tests and capture their current output.
4. Use a focused commit message and push only the intended branch.
5. Create the requested PR or release with summary, verification, and known risks.
6. Read back the remote URL and status before claiming success.

Creating repositories, changing visibility, merging, force-pushing, or publishing releases requires explicit authorization.
