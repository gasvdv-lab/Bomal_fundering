# TESTING — v0.7.0.2

Automatisch/static:
- PASS JavaScript syntax
- PASS drawMarker gebruikt uitsluitend xrGL
- PASS geen ongedefinieerde gl.* calls in drawMarker
- PASS AR-raster gebruikt coords()
- PASS AR-raster gebruikt s.active
- PASS één ProjectRoot
- PASS flat 5-file ZIP

Fysieke test:
1. Open AR.
2. Zoek vloer tot vizier groen is.
3. Tik P00.
4. HUD moet `RASTER GEPLAATST · 15 PUNTEN` tonen bij een 3×5-raster.
5. Rode rasterdoelwitten moeten zichtbaar zijn.
