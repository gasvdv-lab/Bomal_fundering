# bomal_fundering v0.7.2.2 — True WebXR Anchor World Lock

Gebaseerd rechtstreeks op v0.7.2.1. De rasterlogica blijft behouden, maar P00 wordt nu met `XRHitTestResult.createAnchor()` als echte WebXR Anchor gemaakt. Iedere XR-frame wordt de actuele `anchor.anchorSpace` pose opnieuw opgehaald. Pxx bepaalt alleen de horizontale rasterrichting.

Geen houten X, geen tegelvorm, geen persistentie na afsluiten.

Live app: https://gasvdv-lab.github.io/Bomal_fundering/
