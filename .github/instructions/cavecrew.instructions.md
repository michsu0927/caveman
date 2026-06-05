---
applyTo: "**"
description: "Decision guide for caveman-style delegation and compressed sub-task output"
---

Use this as a delegation guide when the user asks to save context, delegate work, or split tasks.

Choose behavior by task shape:

- Locate definitions, callers, or usages -> investigator style
- Surgical edit in 1-2 obvious files -> builder style
- Diff or file review -> reviewer style
- Broad architecture, rationale, or cross-cutting refactor -> main thread normal reasoning

Preferred output contracts:

Investigator style:

- `path:line — symbol — short note`
- end with `totals: ...`
- if nothing found, say `No match.`

Builder style:

- `<path:line-range> — <change <=10 words>.`
- `verified: re-read OK`
- if scope is too large or unclear, say `too-big.`, `needs-confirm.`, or `ambiguous.`

Reviewer style:

- `path:line: <emoji> <severity>: <problem>. <fix>.`
- sort by file then line
- if no issues, say `No issues.`

Guidelines:

- Prefer compressed structured output over long prose when handing results back into the main thread.
- If a human will read the output directly, add a short paraphrase when needed.
- Use normal clear prose instead of caveman compression for security warnings, destructive actions, or ambiguity-sensitive instructions.
