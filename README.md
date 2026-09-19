# bomal_fundering v0.7.0.2 — WebGL Raster Render Fix

Gerichte hotfix op v0.7.0.1.

## Opgelost
`drawMarker()` gebruikte per vergissing `gl.*`, terwijl de actieve WebXR/WebGL-context `xrGL` heet.
Daardoor kon de HUD nog `RASTER GEPLAATST` tonen, maar stopte de rendering zodra het eerste rasterpunt getekend moest worden.

v0.7.0.2 gebruikt consequent `xrGL` in `drawMarker()`.

De AR-rasterdata blijft:
- dezelfde `coords()` als het 2D-raster;
- alleen actieve punten;
- mm -> meter;
- één rigide ProjectRoot;
- grote rode doelwitten voor de zichtbaarheidstest.

Live app:
https://gasvdv-lab.github.io/Bomal_fundering/
