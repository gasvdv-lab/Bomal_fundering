# Bomal Fundering v0.7.12.0 — Precision + Direct Anchor Placement

Nieuw:
- P00 en P03 kunnen nu op twee manieren geplaatst worden:
  - PRECISIE VASTZETTEN: korte stabiliteitscontrole, daarna echte WebXR anchor.
  - DIRECT VASTZETTEN: het huidige geldige hit-testpunt wordt onmiddellijk gebruikt.
- Beide methodes maken dezelfde echte XRAnchor.
- P00 blijft master anchor; P03 bepaalt alleen de rasterrichting.
- P00–P14 blijven één rigide raster.

Fixes:
- foutieve `best.hit`-logica verwijderd;
- stabiliteitscontrole bewaart geen XRHitTestResult-objecten;
- Undo wist `rigidRasterFrame` en pending placement state;
- P03 wordt na master-rasterlock niet meer dubbel als aparte marker gerenderd;
- groene fullscreen-overlayfix van v0.7.11.4 blijft behouden;
- alle inline JavaScript gecontroleerd met `node --check`.
