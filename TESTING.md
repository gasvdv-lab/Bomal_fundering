# TESTING — v0.7.12.0

Automatisch PASS:
- JavaScript node --check
- PRECISIE-knop aanwezig
- DIRECT-knop aanwezig
- geen `best.hit`
- geen opgeslagen XRHitTestResult in stabiliteit
- Undo reset rasterstate
- groene fullscreen-overlayfix behouden
- ZIP-integriteit en 5-file structuur

Fysiek:
1. Start AR — geen groene fullscreen laag.
2. Test P00 DIRECT.
3. Undo.
4. Test P00 PRECISIE.
5. Plaats P03 DIRECT of PRECISIE.
6. Controleer `MASTER RASTER GEANKERD`.
7. Loop weg en terug naar P00/P03/P14.
8. Controleer dat P00–P14 als één geheel blijven.
