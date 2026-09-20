# TESTING — v0.7.14.1
Automatisch PASS:
- default 3×5
- 2 X-overgangen
- 4 Y-overgangen
- horizontale AR-neighbour +1
- verticale AR-neighbour +3
- P00 master anchor behouden
- P03 richtingsanker behouden
- legacy 5×3 state-migratie
- alle inline JavaScript via node --check
- ZIP-integriteit

Fysiek:
1. Start AR.
2. Plaats P00.
3. Plaats P03.
4. Onderste rij moet P00-P01-P02 zijn.
5. P03 moet recht boven P00 liggen.
6. P06/P09/P12 moeten verder in dezelfde Y-richting liggen.
7. Loop weg en terug; raster moet één rigide geheel blijven.
