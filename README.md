# Bomal Fundering v0.7.9.0 — Manual Stability + Rigid Lock

Gebouwd vanaf v0.7.8.2.

- Nieuwe schakelaar `STABILISATIE: AAN/UIT`.
- AAN: bestaande circa 0,85 s precisie/stabiliteitsmeting.
- UIT: onmiddellijk het actuele WebXR hit-testpunt ankeren.
- Na P00 en P03 wordt de horizontale rasterrichting éénmalig vastgezet. Daardoor kunnen kleine onafhankelijke P03-correcties niet langer ieder frame het hele raster verdraaien.
- Undo/reset wist deze rigid lock zodat opnieuw kalibreren mogelijk is.
- Plaatsmodus P00–P14, OFFSET, HOOGTEHULP en laserworkflow blijven behouden.
