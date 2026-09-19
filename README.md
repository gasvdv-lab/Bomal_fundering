# Bomal Fundering v0.7.10.2 — AR Green Overlay Fix

Hotfix op v0.7.10.1.

Correcties:
- expliciete transparante WebXR framebuffer-compositie;
- alpha blending wordt voor de AR-overlay expliciet ingesteld;
- raster wordt pas getekend wanneer P00 én P03 én het master-rasterframe geldig zijn;
- geen geometrie tekenen vanuit een gedeeltelijk geïnitialiseerde rasterstate;
- master-anchorarchitectuur en vaste P00 → P03 workflow blijven behouden.
