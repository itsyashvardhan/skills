---
name: docx-automation
description: Create, edit, inspect, transform, and automate Microsoft Word DOCX documents. Use when working with .docx files, templates, mail merges, formatting preservation, headings, tables, comments, tracked-change review, document metadata, or batch document generation.
---

# DOCX Automation

Work with DOCX files as structured Office Open XML packages. Prefer reliable libraries and document-level validation over ad hoc text replacement.

## Workflow

1. Inspect the task goal and source files before editing.
2. Preserve formatting, styles, sections, headers, footers, tables, images, numbering, and document properties unless the user asks to change them.
3. Use an appropriate library when possible:
   - Python: `python-docx` for creation and common edits.
   - JavaScript: `docx` for generated documents.
   - XML/package edits for advanced features not exposed by libraries.
4. For template replacement, replace placeholders at the run level without losing surrounding formatting.
5. For batch generation, keep input data separate from document templates and emit deterministic filenames.
6. Validate by reopening or parsing the generated DOCX package and checking expected content.

## Guardrails

- Do not silently flatten complex formatting into plain text.
- Do not overwrite source documents unless explicitly requested.
- For legal, financial, or client-facing documents, report any fields or placeholders that could not be resolved.
