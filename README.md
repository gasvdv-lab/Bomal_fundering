# Bomal Fundering v0.7.8.1.1 — Correctness Fix

Gerichte reparatie van v0.7.8.1.

## Gecorrigeerd
- Raster, cirkels/kruisen, rasterassen, labels en hoogtehulp gebruiken nu dezelfde visuele Y-basis: `P00 Y + OFFSET`.
- De oude afzonderlijke +35 mm labelhoogte en +8 mm ashoogte zijn verwijderd.
- `OFFSET 0 mm` betekent nu voor alle rastergerelateerde visualisatie dezelfde basis.
- Stabiliteitsmeting controleert naast horizontale beweging ook verticale spreiding.
- Huidige limieten: 18 mm horizontaal en 12 mm verticaal gedurende circa 0,85 s.
- Na P00/P03 wordt H/V-spreiding gemeld.
- Plaatsmodus houdt het gekozen punt nadrukkelijk zichtbaar en probeert de algemene rasterlijnen visueel terug te nemen.

## Bewust niet gewijzigd
De bewezen P00/P03 WebXR `createAnchor()`-werkwijze is niet herschreven. De exacte 3×5 geometrie blijft rigide en de laser blijft de definitieve controle.
