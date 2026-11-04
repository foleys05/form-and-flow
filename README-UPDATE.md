# Form & Flow — Life Tools update

Adds weekly workout planner, suggested workout, express option, categorized exercise swaps, optional measurements, strength milestones, glute/core progression path, daily energy check-in, rest timer and enhanced home dashboard.

## Install
Upload `index.html`, `flow-tools.js`, and the existing `exercise-gifs/` directory to the same GitHub Pages repository. Preserve other files (if present). Before updating, export a JSON backup in Settings.

## Data
The original localStorage key `form-flow-local-v1` is unchanged. Existing sessions, drafts, enabled programs, and settings remain intact. New optional preferences are stored in `state.flowTools`. No account or cloud sync is added.

## Important behavior
Express mode visually shows only the first four exercises in the current draft; it does not delete the others. Exercise swaps reset that exercise's sets, with a confirmation when any sets are marked completed. Recovery suggestions are informational. The app uses local device time.

## Demonstrations
Existing stylized GIFs remain in this package; no new third-party footage is included.
