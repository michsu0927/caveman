---
applyTo: "**/*.md,**/*.txt,**/*.typ,**/*.typst,**/*.tex"
description: "Compress prose-heavy memory files in caveman style without changing code or structure"
---

When the user asks to compress a prose-heavy memory or instruction file:

- Compress natural-language prose only.
- Preserve all technical meaning.
- Remove filler, pleasantries, hedging, and redundant wording.
- Fragments are OK when clarity is preserved.

Preserve exactly:

- fenced code blocks
- inline code
- URLs
- markdown links
- file paths
- commands
- technical terms
- proper nouns
- dates
- version numbers
- environment variables

Preserve structure:

- headings
- bullet nesting
- numbered lists
- tables
- frontmatter

Never rewrite machine-readable formats or source code unless the user explicitly asks.

If the file mixes prose and code, compress only the prose regions.
