# Universal Editor — Product Brief 0.2

## Product thesis
A cross-disciplinary editor that makes specialist notation and structured documents easier to create. Initial wedge: fast scientific notation entry. Long-term scope: humanities and sciences, education, research, and general-purpose documents.

## Initial audience
- Students
- Teachers and tutors
- Researchers

## Positioning
Initially complements Word, Google Docs and other editors through fast input and export. Later expands into a standalone document workspace.

## Current prototype (0.2)
- Rich-text editing, headings, lists, quotes and tables
- Superscript/subscript
- Lightweight chemistry notation helper and symbol palette
- Local autosave with document title
- Character count
- HTML/TXT import
- JSON backup export/import
- HTML export and print/PDF workflow

## Explicitly out of scope
- Accounts and cloud sync
- Collaboration
- AI generation
- Handwriting recognition
- Full DOCX import/export
- Native iOS/Android packages

## Technical direction
- Web-first, responsive, PWA-ready
- Next maintainable implementation: TypeScript + React
- Structured document model with typed nodes for text, chemistry, math, tables, images and citations
- Keep conversion/export adapters separate from the editor core
- Treat chemistry and math as structured editable content, not flattened screenshots

## Validation metrics
- Activation: user creates and exports a document
- Repeat use: weekly active users and 7/30-day retention
- Utility: documents created and specialist insertions
- Quality: export fidelity and editing errors
- Business: conversion, churn, gross margin and support burden

## Next milestone
Move from the single-file prototype to a modular React/TypeScript implementation, add automated tests for notation conversion, and validate workflows with students and teachers.
