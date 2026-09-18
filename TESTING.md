# TESTING — v0.5.0

Automatische/static controles:
- PASS: v0.5.0 Interactive Raster marker aanwezig.
- PASS: flat release met exact 5 bestanden.
- PASS: geen externe JS/CSS en geen ES modules.
- PASS: puntselectie A/B aanwezig.
- PASS: afstand = Math.hypot(dx,dy).
- PASS: fullscreen-achtige rastermodus aanwezig.
- PASS: pan via Pointer Events.
- PASS: pinch zoom-logica aanwezig.
- PASS: actief/leeg is aparte knop.
- PASS: labels en maatlijnen blijven toggles.

Rekencontrole:
5×3, horizontaal 1200 mm, verticaal 1500 mm:
P00 -> P14 = sqrt(4800² + 3000²) = 5660.4 mm.

Handmatig Android:
1. Open v0.5.0 en Raster.
2. Raster moet het scherm domineren.
3. Tik P00, daarna P14.
4. Verwacht 5660.4 mm bij 1200/1500.
5. Test ander punt als nieuwe A.
6. Test Wis selectie.
7. Test Actief/leeg.
8. Test slepen en pinch-zoom.
9. Test Labels en Maten.
