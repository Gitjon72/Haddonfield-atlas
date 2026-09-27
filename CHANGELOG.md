# Changelog

Notable public changes to Haddonfield Atlas will be documented here.

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
