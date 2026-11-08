# Dashboard Chat Builder · start here

This file-based kit helps an AI coding workspace create a fictional local dashboard preview, then plan an adaptation for a real project. It is not a finished app, AI chatbot or hosted service.

## Choose one path

### A. Make the fictional sample preview

1. Copy this kit into a disposable folder. Do not use the website source checkout or a real application repository as the sample destination.
2. Open that disposable folder in a coding workspace that can read the kit files and create a local preview.
3. Ask it to read `START.md`, `PROMPT.md`, `CHECKS.md` and `sample.csv`, and build the fictional sample only in this disposable folder.
4. The intended artifact is one self-contained `dashboard.html` that opens directly in a browser without installing packages or starting a server. It should offer only **Total orders** and **Total revenue** as rule-based questions. Review the generated file and record which checks actually ran. The expected all-row totals are 20 orders and USD 270 revenue; North alone is 12 orders and USD 160.

No model API, real dataset, external service or deployment is needed for the intended non-AI sample. A first sample matching this one-file/two-question contract passed Node logic checks but had document-level overflow at 320 CSS px (522px document width); this review manually fixed the grid panel's minimum width. An isolated browser review of that corrected sample at 320, 390 and 1440 CSS px confirmed no document-level overflow; the wide table scrolled only inside its focusable wrapper. Keyboard focus and the sample CSV picker were also checked; a malformed CSV showed a row-specific error and preserved valid prior data. A separate fresh Codex output from the revised prompt now passes Node logic and static responsive-CSS checks and includes the grid min-width guard; that new output has not received browser/runtime checks. Available browser tools reject direct `file://` navigation, so opening either output directly from disk remains unverified. Physical devices, screen readers and other coding workspaces remain unverified. If the workspace proposes a package, CDN or server, stop and explain why before adding it.

### B. Plan an adaptation for an existing project

1. Open the user's target application as the working project. Attach or copy the DropKit kit files as reference context; do not choose the DropKit product repository as the working target for the app.
2. Fill `PROJECT-BRIEF.md` with synthetic or otherwise approved information. Follow `DESIGN-RESEARCH.md` only for the specific user task.
3. Request a read-only plan with exact paths/actions, existing edits to preserve, data assumptions, dependencies/costs, checks, risks and recovery.
4. Verify the coding workspace is in a genuine read-only planning mode. A prompt saying “do not edit” is not a technical lock. If the mode cannot be confirmed or existing edits cannot be protected, use a disposable clone or stop before adaptation.
5. Approve only a specific proposal. Recheck the target state, apply only that scope, then review the diff and actual results.

This adaptation process is proposed guidance and has not been validated across coding workspaces. Never put API keys in kit files or browser code. Model access, databases, authentication, paid services, real data and deployment need separate decisions.

## What is and is not verified

The checklist is a guide for recording actual results, not evidence that every check passed. Direct `file://` opening, browser/runtime checks for the fresh generation, physical-device use, screen-reader behavior, other workspaces, model-backed answers, the existing-project plan path and deployment have not been verified.
