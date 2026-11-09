# Prompt

First identify the selected path: (A) fictional sample preview or (B) planning an existing project. If unclear, ask one concise question. Keep the paths separate.

## A. Fictional sample preview

- Work only in a disposable copy of this kit; do not edit the publisher's website checkout or a real project.
- Read `START.md`, `CHECKS.md`, `RESULTS-TEMPLATE.md` and `sample.csv`.
- Create a single self-contained `dashboard.html` with inline CSS and JavaScript. Embed the four fictional sample rows so it opens directly from a local file in a browser. Do not require an installed package, CDN, local server, model API, real data, external service, database, authentication or deployment.
- Show the data source, fictional-data notice, units, metric definitions, active filter and last-updated state. Make totals derive from the visible rows.
- Provide a CSV file picker for a user-selected local file; parse it in the browser without transmitting its contents. Keep the required columns/order from `sample.csv` and show useful errors for malformed or empty files.
- Show exactly two supported question examples: `Total orders` and `Total revenue`. Calculate both from the currently visible rows, show the source row IDs or aggregation, and return an honest unknown for other questions. Do not use a model.
- At 320 CSS px and 390 CSS px, keep the document itself free of horizontal overflow. A wide data table may scroll only inside its labeled, keyboard-focusable wrapper. When that wrapper has focus, ArrowLeft and ArrowRight move it horizontally by a useful step; Home and End move to its left and right edges. Do not capture these keys when focus is elsewhere. Give the wrapper an accessible name and a short visible or programmatically available hint for these keys. Keep a visible keyboard focus indicator.
- If direct local-file use cannot be supported by the available browser, explain the blocker instead of silently introducing a package, CDN or server.
- Report generated paths and the actual acceptance checks that ran. Do not claim model-backed chat.
- Record the run in `RESULTS-TEMPLATE.md`; label every check passed, failed, or not run with concise evidence and limits.

## B. Existing-project plan

- Confirm the exact project and current state first. Inspect only relevant instructions, structure and existing changes.
- Use the intended target application repository as the working project and the DropKit files as reference context. Do not make the product-kit repository the working target for the user's application. If the current tool cannot separate reference files from the writable target, stop and report the constraint.
- Use a tool-enforced read-only Plan mode if available and verify its active state. Instructions in this prompt alone do not prevent writes.
- Do not edit or create project files, install packages, run migrations, call external services, transfer real data or deploy during planning.
- Return exact proposed paths/actions, pre-existing changes to preserve, data/access assumptions, dependencies/costs, checks, risks and selective recovery.
- Stop for approval of the exact proposal. If the active mode or existing user work cannot be verified, stop before editing and report the limitation.

## After approval

- Reconfirm the target and compare its current state with the proposal. Re-plan if anything changed.
- Implement only approved paths/actions in an isolated reviewable change set when possible. Never erase, reset or overwrite existing work.
- Keep model/API access, databases, authentication, paid services, real-data use and deployment outside scope unless separately approved.
- Show the diff, generated paths and exact check results. Explain recovery for only this change set.

For every statement, distinguish observed facts, assumptions and untested items. Do not claim a tool run, model call, source review, test or deployment that did not actually happen.
