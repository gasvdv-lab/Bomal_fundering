# Bomal Fundering v0.7.2.6 — Anchored Axis Test

Gebaseerd op de fysiek geslaagde dual-anchor v0.7.2.5.1.

Nieuw:
- P00 en P03 blijven twee echte, onafhankelijke WebXR anchors.
- Iedere frame worden beide actuele anchorposes gelezen.
- De lijn P00 → P03 vormt de lokale Y-as.
- Door P00 wordt een horizontaal loodrechte X-as getekend.
- Geen opgeslagen P03-worldmatrix, geen ProjectRoot en nog geen 3×5 raster.

Doel: bewijzen dat een geometrische constructie die rechtstreeks uit de twee actuele anchors
wordt afgeleid stabiel op het terrein blijft.
