# A shared meaning for every answer

Before generating an application, define the metric, unit, period, filters, data revision, source rows and caller scope. The dashboard and chat must call the same query/calculation function. Treat frontend filters as untrusted; enforce authorization at the actual data boundary.

Ask for clarification when a period or metric is ambiguous. Reject missing numeric inputs rather than silently converting them to zero. If data changes during a request, return the captured revision or restart the request; never silently mix revisions. Distinguish received, generated, checked and delivered. A generated answer is not a verified answer.

Record reference answers independently before testing. Include wrong-scope requests, missing values, source corrections, changed filters and unsupported questions. Report time to a verified usable answer separately from time to first text. Do not claim reduced human effort without a user study.

The query-contract example demonstrates shared deterministic calculations and a simulated scope restriction. It is not secure production authorization and makes no model call. A real application needs authenticated server-side enforcement. Provider selection remains optional; a language model may explain a computed result but must not establish access rights or invent numeric values.
