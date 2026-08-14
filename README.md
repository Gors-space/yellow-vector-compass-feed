# Yellow Vector — Compass Feed

The public, published output of the Investment Compass — nothing else.

## What this repo is

- Holds `compass_data.json`, the file the site's Compass widget
  (`investment_compass.html`) fetches directly at page load via
  `raw.githubusercontent.com`.
- This repo is intentionally minimal and public. All pipeline code, model
  internals, and historical working data live in the **private**
  `yellow-vector-compass-data` repo — this repo only ever receives an
  already-approved JSON file, copied over after a PR is merged there.
- No PR gate here — the approval already happened upstream, in the private
  repo. A push here just publishes what was already signed off.

## Status

Scaffolding only as of 2026.08.14 — no `compass_data.json` published yet.

See `cl_project_yellow_vector/YELLOW_VECTOR_LOG.md` in the main project
folder for full project context and decision history.
