# Bomal Fundering v0.7.2.5.1 — Dual Anchor Fix

Gerichte hotfix op v0.7.2.5.

## Gecorrigeerd
- `p03Anchor` wordt nu expliciet gedeclareerd.
- Na P00 schakelt de onderste knop naar `P03 HIER VASTZETTEN`.
- P03 wordt met dezelfde `XRHitTestResult.createAnchor()`-methode als P00 gemaakt.
- P00 en P03 worden iedere frame rechtstreeks vanuit hun eigen `anchorSpace` opgehaald.
- Beide anchorposes worden nu werkelijk gerenderd.
- Beide anchors worden bij afsluiten verwijderd.

Nog bewust afwezig: raster, ProjectRoot en yawberekening.
