# Sample workflow test report

Run date: 2026-11-10. Host: user-authorized Mac mini. Browser: Google Chrome 147.0.7727.15, headless mode. Test input: fictional rows only. The local `dashboard.html` was opened directly with a `file://` URL; no server or network resources were required.

## Result

**29/29 Dashboard + Chat Kit checks passed.** A single browser run also tested five separate Development Research Kit dialog-probe checks; all 34 checks in the shared run passed. The dashboard report came from a fresh disposable output following this kit's sample workflow, not from an existing production application.

- Data: four fictional records; 20 total orders and USD 270.00 revenue.
- Filter: North shows 12 orders and USD 160.00 across two records; clearing the filter restores the all-row totals.
- Answers: `Total orders` and `Total revenue` show aggregation formulas and source row IDs. An unsupported question returns a bounded unknown. No model was invoked.
- File handling: the valid sample loads; malformed and empty CSV files show useful errors and leave the last valid data intact; selecting the valid file again recovers.
- Responsive layout: no document overflow at 320px, 390px or 1440px CSS viewport widths. At 320px and 390px, the wide table scrolls inside its own focusable region.
- Keyboard: ArrowLeft/ArrowRight and Home/End move the focused table region. Those keys are not intercepted when focus is in the question field. Tab navigation reaches the region, question and Ask control in order.
- Network: the page reported zero network resource requests.

The CSV files were assigned to the file input through Chrome DevTools Protocol; the operating system's native file chooser was not opened.

## Not tested

No physical mobile device, screen reader, other browser, second AI coding workspace, model/API, database, authentication, real project, real data or production deployment was used. The report does not prove production readiness or universal workspace compatibility.

The bundled example code uses the MIT license. This report and the fictional CSV use CC BY 4.0 under the notices in `LICENSE` and `LICENSE-DOCUMENTATION.md`.
