# Bomal Fundering v0.7.9.3 — Anchor Fix

Herbouwd vanaf v0.7.7.1.1. De bestaande stabiliteitscontrole blijft behouden, maar `createAnchor()` wordt nu uitgevoerd op een hit-testresultaat uit de actuele XR-frame. P00 en P03 blijven echte WebXR XRAnchor-objecten en worden gevolgd via `frame.getPose(anchor.anchorSpace, xrRef)`. De bestaande tweestaps Undo blijft: eerst P03, daarna P00.
