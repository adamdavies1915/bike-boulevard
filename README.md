# Uptown–Downtown bike boulevard

An interactive New Orleans corridor study connecting Lafayette Square and Camellia Grill.

**Live report:** https://adamdavies.dev/bike-boulevard/

The map compares eight route options with directional stop and all-way-stop markers, traffic lights, and pavement measurements. Pavement colors are on by default. The report includes the personal ride-time model, methodology, route tradeoffs, a PDF, and full street sequences.

## Files

- `index.html`: interactive report and route comparison
- `map.html`: standalone map with embedded street and route data
- `report.html` and `report.pdf`: full write-up
- `selected-route-cues.txt`: all shortlisted street sequences
- Five PNG maps: printable overview, controls and pavement

## Publishing

This is a buildless static site. GitHub Pages publishes the `main` branch from the repository root. `.nojekyll` disables Jekyll processing. The account’s existing GitHub Pages custom domain supplies the `/bike-boulevard/` URL; this repository does not need a separate `CNAME`.

Keep the HTML, PDF, text and PNG files together when updating the export, then commit and push to `main`. All internal asset links are relative, and the parent report and map run on the same origin.

## Evidence and attribution

Prepared 7 October 2026. Route recommendations, timing scenarios, source dates and limitations are explained in the report and map. Stop markers represent encounters in the plotted riding direction; they are not a census of all signs.

Street geometry © OpenStreetMap contributors (ODbL). Pavement: Bumpy Roads. Traffic-control evidence: OpenStreetMap, Mapillary and Google Street View review, and scoped rider observations. No raw personal ride histories or API credentials are included.
