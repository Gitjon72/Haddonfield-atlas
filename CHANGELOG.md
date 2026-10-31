# Changelog

Notable public changes to Haddonfield Atlas will be documented here.

## v1.1.0 - Tower Farm Update - 2026-10-31

### New
- **Tower Farm**, the fifth map: farmhouses, the trailer park, Ridgeline Rd. and Clover Way, with building numbers 300–309 and trailers L01–L10.
- Tower Farm escape locations as separate categories: 7 possible storm cellars (hatches), 9 possible sewers / storm drains and 6 possible civilian escape car spawns.
- **Illustrated view**: an optional illustrated style for all five maps, toggled from Filters. It uses the same coordinates, markers, grid and building outlines as the dark view. The dark view stays the default.
- **Grid search**: type a square such as `C6` and press Enter to jump to it and highlight it.
- Hovering a marker or building label shows its name and grid square.

### Changed
- The map grid now matches the in-game paper map on all five maps: A–G across the top, 1–8 down the left number column. It replaces the old A–J / 1–10 grid. Grid lines are straight and registered to each map.
- Grid headers (A–G and 1–8) sit along the edges instead of a label in every square.
- Sewers / storm drains are now green and kept separate from storm cellars.
- Building labels stay anchored to their buildings at every zoom level. When space is tight they shrink, then hide, and they come back as you zoom in. They no longer slide away from their buildings.

### Compatibility
- Personal discoveries, notes, settings and backups from v1.0.0 carry over automatically. Storage keys are unchanged.
- Map-selection photographs are unchanged.

## v1.0.0 - 2026-09-27

First formal GitHub release of Haddonfield Atlas.

### Included

- Interactive maps for Haddonfield Heights, Haddonfield Town Center, Orange Grove Estates, and East Haddonfield.
- Pan and zoom with anchored map markers.
- Search and marker filtering.
- Optional A–J / 1–10 map grid.
- Personal discoveries with editable names, categories, notes, and positions.
- Local browser storage for personal Atlas data.
- Backup export and import for saved personal data.
- Match Mode for fast temporary in-match tracking.
- One-tap temporary match markers.
- Temporary cross-out and restore states for existing markers.
- Temporary marker editing and promotion to permanent personal discoveries.
- Match reset that clears temporary match information without affecting permanent discoveries, notes, or settings.
- Mobile-friendly Match Mode controls and touch targets.

### Production cleanup

- Removed public-facing Match Mode test labeling from the production build.
- Changed the temporary Match Mode session-storage key to its production name while preserving existing permanent personal-data storage keys for compatibility.
