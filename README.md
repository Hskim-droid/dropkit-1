# DropKit 1 · Dashboard Chat Builder

A file-based kit for asking an AI coding workspace to build a local dashboard preview from fictional CSV data.

This download is the kit, not a finished dashboard, AI chatbot, model connection, database or hosted service. Its sample asks the generated preview to support exactly two deterministic questions: **Total orders** and **Total revenue**.

## Quick start

1. Copy this folder into a disposable workspace. Keep the sample away from a real application repository.
2. Open the folder in a coding workspace that can read its files. If it does not load project instructions automatically, ask it to read `START.md`, `PROMPT.md`, `CHECKS.md` and `sample.csv`, then confirm it has done so before it edits.
3. Ask it to create the fictional sample preview described in `START.md` and `PROMPT.md`.
4. Review the result against `CHECKS.md`. Keep any real-project adaptation on its separate planning path.

## Files

- `README.md` — purpose, quick start, file guide and current verification limits.
- `START.md` — the sample and existing-project paths.
- `PROMPT.md` — the bounded build request and project-planning rules.
- `PROJECT-BRIEF.md` — questions to resolve before adapting a real project.
- `sample.csv` — four fictional records.
- `CHECKS.md` — expected totals and checks for filters, errors, evidence and access.
- `DESIGN-RESEARCH.md` — a method for researching a specific dashboard task; it is not a completed research result or a preapproved design.
- `CHANGELOG.md` — dated draft changes and verification scope.
- `LICENSE` — MIT terms for code files in this kit and code examples separated from prose.
- `LICENSE-DOCUMENTATION.md` — CC BY 4.0 terms for original prose, prompts, research notes and fictional sample data.

## Current verification

A first fictional preview matching the one-file, two-question contract passed Node logic checks but overflowed at 320 CSS px (522px document width); this review manually fixed the grid panel's minimum width. The corrected preview passed isolated browser checks at 320, 390 and 1440 CSS px, keyboard focus checks, CSV sample loading, and a malformed-CSV error check. A separate fresh Codex output passed Node logic and static responsive-CSS checks before this draft added the table keyboard contract. Source inspection shows that output does not implement the new table-key behavior; it must not be treated as passing the current checks. Available browser tools reject direct `file://` navigation, so opening the output directly from disk remains unverified. Physical-device and screen-reader use, other coding workspaces, model-backed chat, real-project planning and production deployment have not been verified. Documentation support in a tool does not establish that this kit is compatible with it.

## License

Code files and code examples are licensed under the MIT License in `LICENSE`. Original prose, prompts, research notes and the fictional `sample.csv` are licensed under CC BY 4.0 as described in `LICENSE-DOCUMENTATION.md`. Third-party names, marks, linked sources and materials are not relicensed by these notices. The generated dashboard is an output of a user's coding workspace and is not bundled here; its authorship and license must be decided for that output separately.
