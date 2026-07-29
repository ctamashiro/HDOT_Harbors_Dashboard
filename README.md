HDOT Harbors Division — Pavement & Substructure Repairs Dashboard

Interactive portfolio dashboard for the Hawaii Department of Transportation, Harbors Division construction program: 26 pavement and substructure repair contracts across Oahu, Maui, Hawaiʻi Island, Kauaʻi, Molokaʻi, and Lānaʻi.

Live dashboard: https://YOUR-USERNAME.github.io/hdot-harbors-dashboard/ (replace with your GitHub Pages URL)

What's inside
Portfolio overview — KPIs, priority flags, activity by island, program split, awarded value, and schedule performance across all contracts
CM Process Timeline — each contract's progress through the 8-phase Construction Management procedure (Plans & Specs Review → RCA/Award → Contract & NTP → Pre-Con Meeting → Mobilization → Construction → Final Inspections → Close Out), with a gradient progress bar that darkens as phases complete
Per-project views — click any contract for its full timeline, contract-value-by-phase pie chart, document status, field activity history, QA/QC ratings, and location map
Closeout Readiness — for every contract, which of the three required closeout records (as-built drawings, final acceptance letter, final payment / retention release) are on file, drafted, or not yet due
Map — contract locations from geotagged field observations
Data sources

HeadLight field documentation (daily reports, observations, photos), contract transmittal letters, HIePRO award summary reports, payment records, and the Harbors Division Closeout Audit (2026-07-06). Data snapshot: June 30, 2026.

Notes & caveats
The portfolio covers 26 contracts. The HeadLight export supplies field data for 23 of them (24 project records — S50194 has a separate record for its CO-2 emergency waterline repair). Three contracts — Q10945, Q70175, and S50223 — are awarded and under Notice to Proceed but have no HeadLight field records yet. They appear as Pre-Construction: included in contract counts, contract value, the CM timeline, and closeout tracking, but contributing zero to activity-based charts.
CM phase statuses are inferred from available dates (contract transmittal, NTP, first/latest field activity, Final Acceptance Letter). Close-out is assumed complete ~90 days after final acceptance.
The contract-value-by-phase pie chart is an illustrative allocation — no payment/billing records are in the source data, so slice dollars are estimates, not invoiced amounts.
Some duration comparisons mix working days and calendar days; caveats are shown next to the affected charts.
Tech

Single self-contained HTML file (index.html) — no build step, no server required. Uses Chart.js for charts and Leaflet with OpenStreetMap tiles for the map, both embedded/loaded in-page.

Updating

Re-upload index.html (Add file → Upload files) with the same name — GitHub Pages refreshes within a couple of minutes.
