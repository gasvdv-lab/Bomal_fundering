# TESTING — v0.3.0

Automatische/static checks:
- PASS: index.html aanwezig.
- PASS: v0.3.0 versiemarker aanwezig.
- PASS: geen externe CSS/JS afhankelijkheden.
- PASS: rastercoördinaten zijn cumulatief uit horizontale/verticale mm-afstanden.
- PASS: P00 is geometrische oorsprong.
- PASS: lokale opslag aanwezig.

Handmatig op Android:
1. Maak 5 × 3 raster.
2. Horizontaal 1200 mm -> Op alle.
3. Verticaal 1500 mm -> Op alle.
4. Open Raster.
5. Controleer 15 punten P00-P14.
6. Test Centreer, +, -, slepen en Labels.
7. Tik een punt: actief/leeg moet wisselen.
8. Herlaad pagina: invoer moet lokaal behouden blijven.
