# SoC GWP Summary — Santam Specialist (Tableau extension)

Live-reading Tableau dashboard extension for the **GWP SoC Summary** dashboard.
Santam Specialist branded; A4 print; PDF + PowerPoint export; filter panel; insights.

**Data:** the numbers in this repo are DECOY samples for the standalone preview only.
Inside Tableau the extension reads the dashboard's own worksheets live, so real
figures never leave your environment.

## Hosting (GitHub Pages)
Served at: `https://jpny82.github.io/soc-gwp-summary/index.html`
(Settings → Pages → Deploy from branch → `main` / root.)

## Use in Tableau
Add an Extension object to the GWP SoC Summary dashboard → Access Local Extensions →
pick `soc-gwp-summary.trex` (which points at the Pages URL above) → Allow full data.
