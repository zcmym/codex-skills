---
name: markdown
description: Create, edit, structure, lint, and explain Markdown documents. Use when writing README files, technical notes, reports, specifications, tables, checklists, documentation, GitHub issues, or Markdown-based knowledge bases; also use when fixing Markdown rendering or portability problems.
---

# Markdown Authoring

## Workflow
1. Identify the target renderer (GitHub Flavored Markdown, CommonMark, MkDocs, Quarto, Obsidian, or another documented dialect). If unspecified, use conservative GitHub-compatible Markdown.
2. Preserve the author's intent and existing structure. For edits, inspect surrounding headings, links, tables, and code fences before changing anything.
3. Use semantic structure: one H1 title, logically nested headings, short paragraphs, and lists only when they improve scanning.
4. Keep code examples in fenced blocks with explicit language identifiers. Use inline code for filenames, commands, paths, keys, and short literals.
5. Use descriptive link text. Prefer relative links for files in the same repository; verify target paths and anchors when tools are available.
6. Keep tables compact; avoid them for long prose, mobile-first content, or complex nested structures.
7. Use blank lines around headings, lists, blockquotes, tables, and fenced code blocks.
8. Escape characters only when necessary. Avoid raw HTML unless the target renderer requires it.
9. Add a table of contents only when navigation materially helps; keep anchors consistent with the target renderer.
10. Never invent facts, citations, links, command output, or file paths.

## GitHub-compatible conventions
- Use `- ` for unordered lists and `1. ` for ordered steps.
- Use `- [ ]` / `- [x]` for task checklists.
- Use fenced code blocks with language tags; use `text` when no language is appropriate.
- Use blockquotes for callouts only when no renderer-independent callout exists.
- Use Mermaid only when the target platform supports it.
- Do not use heading levels merely to change font size.

## Review checklist
- Heading hierarchy is sequential and meaningful.
- Lists are parallel in grammar and punctuation.
- Code fences are closed and tagged appropriately.
- Tables have headers and are not excessively wide.
- Links and image references point to real targets.
- Pipes in tables, special characters, and nested code fences are escaped correctly.
- The document renders without accidental paragraph joins, broken lists, or malformed HTML.

## Editing existing Markdown
Make the smallest change that solves the problem. Preserve front matter, reference-style links, HTML blocks, comments, and project conventions unless asked to change them. When converting formats, distinguish semantic content from renderer-specific presentation and note unsupported constructs.
