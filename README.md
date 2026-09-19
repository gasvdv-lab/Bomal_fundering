# bomal_fundering v0.7.0.1 — Raster Visibility Fix

Hotfix voor v0.7.0: de AR-renderer verwees naar niet-bestaande globale `rows/cols/active/xs/ys`, terwijl het raster in deze app in `s` en `coords()` zit. Daardoor verscheen wel `RASTER GEPLAATST`, maar werd het raster niet correct opgebouwd.

Fix:
- AR gebruikt nu exact dezelfde `coords()` als de werkende 2D-rasterweergave;
- actieve punten komen uit `s.active`;
- mm -> meter in AR;
- markers tijdelijk groter en rood voor zichtbaarheid;
- HUD toont hoeveel rasterpunten geplaatst zijn.

Live: https://gasvdv-lab.github.io/Bomal_fundering/
