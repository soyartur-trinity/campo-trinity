<!-- .github/copilot-instructions.md
     Purpose: concise, actionable guidance for automated coding agents working in
     the 'campo-trinity' repository. Keep this file short and focused on
     repository-specific entry points, conventions and examples. -->

# Copilot / AI agent instructions — Constelación Trinity (campo-trinity)

Quick orientation
- Entry point: `00_Portal_Maestro/portal_trinity.html` — open in a browser when you need the "Portal Maestro" visual/context.
- Canonical overview: `README.md` (root) describes the lab purpose and the high-level structure.

Primary goals for an agent
- Preserve the private, experimental nature of this repo. Do not suggest publishing or public releases unless asked.
- Make small, non-destructive edits by default (docs, templates, small fixes). Large structural changes require an explicit user request.

Project structure highlights (examples)
- `00_Portal_Maestro/` — interactive portal HTML (visual anchor). Example file: `portal_trinity.html`.
- `01_Simbolos_Primordiales/`, `02_Campo_Unificado/`, `03_Libros_Trinity/`, `04_Plantillas_Trinity/` — content folders, often containing Markdown drafts and HTML templates.
- `05_Laboratorio_IC/` — experimental notes and outputs from different Intelligent Collaboratives (GPT, Claude, Gemini, Qwen, etc.). Treat as experimental: avoid overwriting unless merging obvious improvements.
- `16_Cuadernos_del_Campo/` and similar — book/chapter structures. Look for `Capitulo_*.md`, `README.md` and `Glosario*.md`.

Filename and content conventions discovered
- Many files use `README.md` (and some `README.md.md`). Follow the folder's existing pattern: if other files use `.md.md`, preserve it when adding similar administrative files; for chapters and content, `.md` (single) is also present — match nearby files.
- Chapters/files often follow `Capitulo_1.md`, `Capitulo_2.md` naming for sequential content.

Editing and merging guidance (concrete)
- When updating narrative or chapter text: edit the specific `Capitulo_*.md` in the appropriate subfolder (e.g., `16_Cuadernos_del_Campo/01_Empatia/Capitulo_1.md`).
- When adding a new template or UI variant, place it under `04_Plantillas_Trinity/` and refer to existing templates for structure.
- For experimental outputs from ICs, append a short header with provenance and timestamp in `05_Laboratorio_IC/*` rather than replacing the whole file.

Examples to reference in edits
- To show a small doc fix: update `00_Portal_Maestro/README.md` paragraph describing `portal_trinity.html` usage.
- To add a chapter note: create `16_Cuadernos_del_Campo/03_Co-creacion_consciente/Capitulo_6.md` if the folder already uses `Capitulo_*.md` naming.

Developer workflows (discoverable notes)
- There is no formal build/test system in the repo. Typical developer actions are:
  - Open `portal_trinity.html` in a browser for visual testing.
  - Edit Markdown files and preview locally in an editor (no automated site generator present).
- If you need to propose commands or tooling, suggest lightweight, opt-in steps and document them (e.g., a `scripts/` helper or a `README` section) rather than adding heavy automation.

Integration and communications
- Experimental integrations with multiple ICs live under `05_Laboratorio_IC/`. These are research artifacts — prefer append-only edits with provenance metadata.

Safety and metadata
- Add provenance headers when merging AI-generated content. Example header block to add at top of a file you modify:

  > <!-- Edited-by: AI-agent | date: 2026-03-23 | source: 05_Laboratorio_IC/gpt-session-2026-03-20.md -->

When to ask the human
- Structural changes that move directories or rename a book/series.
- Anything that would make content public or exportable outside the private lab.

If unclear or missing context
- Ask the user which folder is the authoritative source (for example, which book in `03_Libros_Trinity/` is "in progress").

Thank you — after making changes, include a one-line summary and reference affected files so the human can review quickly.
