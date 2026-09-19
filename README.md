# Bomal Fundering v0.7.3.0 — Anchored Full Raster

Gebaseerd op de fysiek geslaagde P00/P03 dual-anchor en de v0.7.2.6 assentest.

## Nieuw
- Volledig 3 × 5 raster P00–P14 in AR.
- Nummering:
  P12 P13 P14
  P09 P10 P11
  P06 P07 P08
  P03 P04 P05
  P00 P01 P02
- P00 en P03 blijven de twee echte WebXR anchors.
- P00→P03 bepaalt de positieve Y-richting.
- X staat loodrecht op Y.
- De exacte rasterafstanden blijven afkomstig uit de bestaande ingevoerde ontwerpgeometrie (`coords()`).
- Alle rasterpunten vormen één rigide geometrie; er is geen individuele puntcorrectie aan het terrein.

De laser blijft de definitieve maatcontrole.
