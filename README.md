# Bomal Fundering v0.7.11.4 — Green Overlay Root Cause Fix

Werkelijke oorzaak:
`#arVisual` is fullscreen en krijgt tijdens AR de class `on`.
Er stond óók een generieke CSS-regel `.on{background:rgba(74,222,128,.92);...}`.
Daardoor werd de volledige AR-HUD groen.

Fix:
- generieke groene `.on`-regel verwijderd;
- `#arVisual` en `#arVisual.on` expliciet transparant;
- START/STOP/UNDO behouden;
- WebXR/P00/P03-logica behouden;
- alle inline JavaScript gecontroleerd met `node --check`.
