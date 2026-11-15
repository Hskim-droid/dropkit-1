# Shared sales query reference

Open index.html directly. No installation, network, database or model is needed. Ask `net sales`; dashboard and answer use the same deterministic query function. Synthetic January 2026 data: North gross 150, refunds 15, net 135; South gross 70, refunds 0, net 70. Correction changes North refunds to 25 and net to 125.

Test region, unspecified period, simulated North-only scope, missing numeric input, correction, reset and unsupported questions. Every context change invalidates the previous answer. Expected source rows for North are a and c; South is b.

Scope restriction is deliberately simulated in a fully visible local file and can be bypassed by editing it. This is not a security boundary or a production access-control test. Independent spreadsheet calculation establishes baseline arithmetic only. No human usability benefit, live model integration or real business-data result is claimed.
