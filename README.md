# Bomal Fundering v0.7.9.6 — Unified Raster Offset

P00 en P03 zijn de twee fysieke WebXR-referenties. Zodra beide staan, wordt één rigide 3D-rasterframe vastgelegd.

Belangrijk:
- P00–P14 zijn één raster.
- Alle 15 punten gebruiken exact dezelfde `visualHeightOffset`.
- OFFSET 0 mm = nul offset voor het volledige raster.
- +2 mm of -2 mm verplaatst het volledige raster samen langs dezelfde raster-normaal.
- Geen individuele puntcorrectie.
- Geen automatische terreincorrectie.
- Geen herberekening van de rasterrichting na vergrendeling.
