---
applyTo: "**"
description: "Commit message style for caveman commit generation"
---

When generating commit messages:

- Use Conventional Commits when appropriate.
- Format subject as `<type>(<scope>): <imperative summary>`.
- Prefer `<= 50` characters; hard cap `72`.
- Use imperative mood.
- No trailing period.
- Add a body only when the why is not obvious, for breaking changes, migrations, or security-sensitive changes.
- Explain why over what.
- Do not include AI attribution.

If the user asks for multiple options, keep each option terse.
