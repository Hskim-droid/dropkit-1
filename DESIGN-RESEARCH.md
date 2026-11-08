# Research a dashboard and chat UI

This is a repeatable research method, not a collection of preapproved templates. Use it after the sample preview and before adapting the interface to the user's actual task. Keep research, design choices and tested behavior distinguishable.

## 1. Define the job

Identify the intended users, the decisions they need to make, 3–5 frequent questions, the type and freshness of data, and the primary device. Ask only about unknowns that change the UI. When answers are unavailable, state assumptions and use fictional data.

## 2. Find and compare references

When the workspace can browse, search current official documentation, design systems and public examples for dashboard layouts, charts and chat patterns relevant to that job. Open the actual pages and check that the reference contains the claimed pattern. Record the access date and source URL. Compare at least three suitable references when available; do not treat search snippets as reviewed pages.

For each reference, record: provider/title, exact link, pattern observed, task it helps, accessibility or responsive evidence if actually checked, stack/dependencies, price and license/reuse conditions if verified, unknowns, and whether it will be used for inspiration or code. A project's main license does not establish the rights for every embedded asset, example or dependency. Do not copy code, images, logos or templates without checking their applicable terms. Do not present paid or unverified resources as free.

Starting points to check for relevance, not mandatory dependencies:

- [shadcn/ui dashboard blocks](https://ui.shadcn.com/blocks?category=dashboard): sidebar, charts and table examples for React.
- [shadcn/ui AI Elements](https://ui.shadcn.com/docs/ai-elements): chat and message UI patterns. Check stack and component terms before reuse. The older AI Elements site announced a move and planned deprecation; check its current status if using older examples.
- [W3C complex images](https://www.w3.org/WAI/tutorials/images/complex/): text alternatives for charts and complex visualizations.
- [MDN form structure and accessibility](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_forms): labels, controls and keyboard behavior.

If browsing is unavailable, say so. Ask the user for links or use the workspace's already available materials. Do not fabricate links, visits, prices, licenses, screenshots or a current-source comparison.

## 3. Translate findings into options

Describe two or three distinct layouts tied to the job, rather than a generic list of styles. For each: identify information hierarchy, dashboard regions, location and behavior of chat, mobile arrangement, source/metric visibility, strengths and tradeoffs. Examples include a data-first dashboard with a collapsible chat panel, a conversation-first workspace with evidence cards, or a compact single-screen report. These are hypotheses, not claims about a referenced site's design.

Recommend one option with reasons and show a lightweight wireframe or local mockup when the workspace can render one. If an important preference is missing, ask the user; otherwise proceed with a clearly stated sample assumption. Do not claim the user approved a layout unless they did.

## 4. Prototype and report

Adapt only what was chosen, using the sample dataset first. Do not install a new dependency, connect a service, send data to a provider or incur a charge without explaining it and obtaining the user's direction. Show source, units, loading, empty and error states; keep unsupported questions honest. Test the chosen viewport and keyboard path; inspect overflow and ensure charts have a readable data alternative. Record what actually ran, what did not, sources used, and unresolved rights or compatibility questions. Do not call a rule-based demo an AI chatbot.
