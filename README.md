HDOT Harbors Division — Pavement & Substructure Repairs Dashboard

Interactive portfolio dashboard for the Hawaii Department of Transportation, Harbors Division construction program: 23 pavement and substructure repair contracts across Oahu, Maui, Hawaiʻi Island, Kauaʻi, Molokaʻi, and Lānaʻi.

Live dashboard: https://ctamashiro.github.io/HDOT_Harbors_Dashboard/


What's inside


Portfolio overview — KPIs, priority flags, activity by island, program split, awarded value, and schedule performance across all contracts
CM Process Timeline — each contract's progress through the 8-phase Construction Management procedure (Plans & Specs Review → RCA/Award → Contract & NTP → Pre-Con Meeting → Mobilization → Construction → Final Inspections → Close Out), with a gradient progress bar that darkens as phases complete
Per-project views — click any contract for its full timeline, contract-value-by-phase pie chart, document status, field activity history, QA/QC ratings, and location map
Needs Attention — in-progress contracts ranked by days since last field activity
Map — contract locations from geotagged field observations


Data sources

HeadLight field documentation (daily reports, observations, photos), contract transmittal letters, and payment records. Data snapshot: June 30, 2026.

Notes & caveats


CM phase statuses are inferred from available dates (contract transmittal, NTP, first/latest field activity, Final Acceptance Letter). Close-out is assumed complete ~90 days after final acceptance.
The contract-value-by-phase pie chart is an illustrative allocation — no payment/billing records are in the source data, so slice dollars are estimates, not invoiced amounts.
Some duration comparisons mix working days and calendar days; caveats are shown next to the affected charts.


Tech

Single self-contained HTML file (index.html) — no build step, no server required. Uses Chart.js for charts and Leaflet with OpenStreetMap tiles for the map, both embedded/loaded in-page.
