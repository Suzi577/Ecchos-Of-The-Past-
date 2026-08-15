# Echoes of the Past — Theme Engine Step 1

This build establishes the first complete data-driven theme definition for **Haunted Hotel**.

## What changed
- Added `THEME_DESIGNS`, a structured visual-theme registry.
- Added a reusable `getThemeDesign()` fallback for the remaining themes.
- Extended `applyTheme()` to apply typography, geometry, surfaces, button behaviour, effects, and tool treatments.
- Haunted Hotel now uses its existing photo assets as themed surfaces and exposes tool-specific treatments.
- The theme state remains persisted through the existing app storage.
- Existing 50-theme presets and selector remain intact.

## Haunted Hotel theme contract
The first complete theme defines:
- Victorian serif display typography
- brass/gold accent and bevelled button treatment
- 8px geometry
- candlelit hallway surface treatment
- dust ambient effect
- Haunted Hotel assets for Spirit Box, EMF, Radar, Camera, EVP and navigation icons
- loading text: "Ringing the front desk..."

## Next step
The same `THEME_DESIGNS[id]` structure can now be filled out for the remaining themes using the Theme Design Bible, without changing the app's components.
