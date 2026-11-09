# Acceptance checks

Record each item as passed, failed, or not run, with actual evidence.

1. The fictional sample loads; its source and fictional-data status are visible.
2. Each total equals the sum of visible rows, with source IDs or formula. All rows: 20 orders and USD 270 revenue. North only: 12 orders and USD 160 revenue.
3. Changing the region filter changes both metrics and available source rows. Clearing it restores the all-row totals.
4. An unsupported question receives an honest response. Missing, malformed, or empty data is identified rather than silently treated as zero. The non-AI status is visible.
5. Answers show relevant source rows or aggregation and distinguish calculated facts from generated explanations.
6. Test a valid file, malformed file, and empty file. Errors should be useful and must not expose secrets. Verify recovery after an invalid selection.
7. At 320px and 390px CSS widths, verify no document-level horizontal overflow. A wide table may scroll inside a labeled, keyboard-focusable wrapper. With it focused, ArrowLeft/ArrowRight should scroll in both directions and Home/End should reach both edges. Verify unrelated fields keep their usual key behavior. Test keyboard order through the filter, file input, table, question field, and Ask control. Record browser and viewport.
8. For real users, test authentication, authorization, isolation, logging, and data handling in the intended environment. A synthetic preview does not establish production readiness.
9. For model-backed chat, test natural-language questions, evidence accuracy, filter enforcement, and unsupported answers with the configured provider. Record whether a model was invoked; a rule-based example cannot pass this check.
10. For UI research, verify pages were opened, links and access dates recorded, reuse terms distinguished from assumptions, and design decisions linked to user tasks. If browsing was unavailable, label research incomplete. Check the mockup narrowly and by keyboard.
11. Before adapting a project, confirm the exact target and active tool-enforced read-only planning mode. Record the proposal, pre-existing Git status, and protected file hashes. Pass only if planning creates or modifies no files and proposes exact paths, dependencies, checks, and recovery. If the mode cannot be confirmed, mark not run and stop before adaptation.
12. Open the generated `dashboard.html` directly from disk with no local server, package, or network. Confirm embedded rows load, supported question intents calculate correctly, and an unsupported question is identified. Record browser and actual result. If direct opening fails, report the blocker instead of adding an unapproved dependency.

List generated files, exact steps, untested items, and any services or costs. Request review before deploying an adapted application.
