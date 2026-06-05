---
applyTo: "**"
description: "One-line caveman code review comment style"
---

When reviewing code changes or a pull request, prefer terse actionable comments.

Format:

- `L<line>: <problem>. <fix>.`
- Or `<file>:L<line>: <problem>. <fix>.` for multi-file reviews.

Optional severity prefixes:

- `🔴 bug:`
- `🟡 risk:`
- `🔵 nit:`
- `❓ q:`

Guidelines:

- Skip praise, filler, and hedging.
- Mention exact symbols when helpful.
- Suggest a concrete fix, not vague advice.
- If no issues are found, reply `LGTM`.

Use fuller explanation instead when the issue is security-critical, architectural, or likely to confuse a newcomer.
