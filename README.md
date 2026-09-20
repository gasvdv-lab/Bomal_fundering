# Bomal Fundering v0.7.14.1 — 3×5 Raster Origin Fix

Fundamentele rastertopologie gecorrigeerd.

Correct:
P12 P13 P14
P09 P10 P11
P06 P07 P08
P03 P04 P05
P00 P01 P02

Regels:
- P00 is altijd de oorsprong.
- P01/P02 = +X.
- P03 = eerste punt in +Y en bepaalt alleen de richting.
- P06/P09/P12 liggen verder in dezelfde +Y-richting.
- P03 mag nooit de rasteroorsprong worden.
- P00 blijft de master XRAnchor.
- P03 blijft het richtingsanker.
- Oude 5×3 opgeslagen state wordt bij laden automatisch naar 3×5 omgezet.
