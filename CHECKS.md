# Acceptance checks

Record each item as passed, failed or not run, with evidence.

1. The fictional sample loads; show its source and indicate it is fictional.
2. A total equals the sum of the visible rows; report the row IDs and formula. With all sample rows, `orders` totals **20** and `revenue_usd` totals **270**. North alone has **12** orders and **160 USD** revenue.
3. Changing the region filter changes both metrics and the data available to chat. Clear the filter and verify totals return.
4. An unsupported question receives an honest unknown response. Missing values and malformed data are identified rather than silently treated as zero. If no model is configured, supported demo questions and the non-AI status are visible.
5. Confirm each answer gives its relevant source rows or aggregation and distinguishes calculated facts from model-generated explanation.
6. Test empty data and an invalid file. Show a useful error without revealing secrets.
7. At 320 CSS px and 390 CSS px, check that the document itself has no horizontal overflow; wide tables may scroll only inside their labeled, keyboard-focusable table wrapper. With that wrapper focused, verify ArrowLeft/ArrowRight scroll it in both directions and Home/End reach both edges; verify those keys are not intercepted when focus is elsewhere. Check keyboard navigation through the filter, file input, question buttons and form. Report the actual browser, viewport and results.
8. For real users, test authentication, authorization, isolation, logging and data handling in the intended environment. A synthetic preview does not establish production readiness.

9. For model-backed chat, separately test natural-language questions, evidence accuracy, filter enforcement and unsupported answers with the actual configured provider. Report whether a model was invoked; a rule-based demo cannot pass this check.
10. For UI research, verify referenced pages were actually opened, links and access dates recorded, reuse conditions distinguished from assumptions, and chosen design decisions linked to user tasks. If browsing was unavailable, label the research incomplete. Check the chosen mockup on a narrow viewport and by keyboard; report actual observations.

11. Before adapting an existing project, confirm the exact target and active tool-enforced read-only planning mode. Record the proposal, pre-existing Git status and protected file hashes. Pass only if planning completes without file creation/modification or an unauthorized command, and the exact proposed paths, dependencies, checks and recovery are reviewable. If the mode cannot be confirmed, record **not run** and do not open the target for adaptation. Do not infer protection from the prompt wording alone.

12. Open the generated `dashboard.html` directly from disk in a browser with no local server, installed package or network connection. Confirm the embedded fictional rows load and exactly the two supported question buttons work. Record the browser and actual result; if the agent-generated file requires a server, dependency or network access, mark this requirement failed and explain why.

List the generated files, exact steps used, untested items and any services or costs required. Ask the user to review before deployment.
