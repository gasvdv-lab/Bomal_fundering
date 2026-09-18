# TESTING — bomal_fundering

## v0.1.0
Foundation smoke tests uitgevoerd.

## v0.2.0
Orthogonale puntgeometrie getest.

## v0.2.1 automatische tests
- cumulatieve X/Y-afstanden
- P00/P14 nummering bij 5 × 3
- 15 rasterposities bij 5 × 3
- eindcoördinaat bij bekende afstanden

Verwacht: `PASS: v0.2.1 grid table geometry tests`

## Handmatig testen op Android/Chrome
1. Open de vaste testlink.
2. Maak 5 horizontaal × 3 verticaal.
3. Zet horizontaal `1200` en kies `Op alle`.
4. Zet verticaal `1500` en kies `Op alle`.
5. Open tab Raster: er moeten 15 punten P00 t/m P14 zichtbaar zijn.
6. Tik een punt: status moet wisselen tussen ACTIEF en LEEG.
7. Herlaad de pagina: raster moet lokaal bewaard blijven.


## v0.2.2 — Mobile Fix
- [x] JavaScript syntax check (`node --check js/app.js`)
- [x] Geometry/unit tests
- [ ] Fysiek testen op Android/Chrome: Raster maken
- [ ] Fysiek testen: Op alle horizontaal/verticaal
- [ ] Fysiek testen: tab Raster en punt ACTIEF/LEEG


## v0.2.3
- Controle: index.html bevat inline CSS en inline JavaScript.
- Geen externe lokale css/js afhankelijkheden.
- Handmatig op Android testen: Raster maken, Op alle, Invoer/Raster tabs, Nieuw.
