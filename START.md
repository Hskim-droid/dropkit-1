# Dashboard + Chat Kit · Start here

This is a file-based kit for an AI coding workspace. Pick one path and keep it separate from the other.

## A. Build the fictional local preview

1. Copy or clone this kit into a disposable folder. Do not use a real application repository as the sample destination.
2. Open that folder in an AI coding workspace that can read the kit and create files.
3. Ask it to read `START.md`, `PROMPT.md`, `CHECKS.md`, and `sample.csv`, then follow path A in `PROMPT.md`.
4. Review the generated `dashboard.html` against `CHECKS.md`. Record the exact run, environment, evidence, and limits in `RESULTS-TEMPLATE.md`.

The expected totals are 20 orders and USD 270 revenue. North alone has 12 orders and USD 160 revenue. The local sample supports only the “Total orders” and “Total revenue” question intents. Other questions should be identified as unsupported. No model, API, server, package, or real data is required.

A fresh sample generated from this kit was opened directly from disk and tested in Chrome 147 headless on a Mac mini. The generated preview passed 29 dashboard checks, including CSV recovery, calculations, filters, keyboard behavior, and 320px / 390px / 1440px viewport checks. See `TEST-REPORT.md` for exact scope. This result describes that one sample run only.

## B. Plan a dashboard for an existing project

1. Open the intended application as the target project. Attach this kit as reference material; do not select the kit repository as the application.
2. Fill `PROJECT-BRIEF.md` with approved information. Follow `DESIGN-RESEARCH.md` for the specific user task.
3. Ask for a read-only proposal listing exact paths, current edits to preserve, data and access assumptions, dependencies, checks, risks, and recovery.
4. Confirm that the workspace enforces read-only planning. Prompt wording alone is not a technical lock. If it cannot be confirmed, stop before adapting files.
5. Review and approve a specific plan, then implement only that scope in an isolated, reviewable change.

This planning path has not been validated across coding workspaces. It does not grant access to a repository, dataset, model, database, account, paid service, or deployment. Never put API keys in kit files or browser code.

## Limits

The example is a local, deterministic preview, not an AI chatbot or production-ready app. Real data handling, authentication, authorization, isolation, model-backed answers, databases, deployment, physical-device behavior, screen readers, and other coding workspaces require separate checks.
