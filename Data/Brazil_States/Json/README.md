# Brazil_States

This folder contains simplified GeoJSON boundary files for major peanut-producing Brazilian states, used to power the interactive maps in the Peanut Dashboard (US/BR).

## Files

- `shiny_map_mato_grosso_simplified.geojson` — Mato Grosso state boundaries
- `shiny_map_mato_grosso_do_sul_simplified.geojson` — Mato Grosso do Sul state boundaries
- `shiny_map_minas_gerais_simplified.geojson` — Minas Gerais state boundaries
- `shiny_map_parana_simplified.geojson` — Paraná state boundaries
- `shiny_map_sao_paulo_simplified.geojson` — São Paulo state boundaries

Each file has been simplified (reduced geometry complexity) to improve loading performance in the Shiny dashboard while preserving state-level spatial accuracy.

