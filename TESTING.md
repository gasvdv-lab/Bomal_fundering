# TESTING — v0.4.0

Automatische controles:
- PASS: index.html vermeldt v0.4.0 Geometry Check.
- PASS: Geometrie-tab aanwezig.
- PASS: maatlijnen aanwezig.
- PASS: diagonale controlelijn aanwezig.
- PASS: afstand gebruikt Math.hypot(dx,dy).
- PASS: geen externe JS/CSS.
- PASS: 5 flat bestanden.

Rekencontrole 5 × 3 met X=1200 mm en Y=1500 mm:
P00 -> P14:
ΔX = 4800 mm
ΔY = 3000 mm
afstand = 5660.3887 mm, dus weergegeven 5660.4 mm.

Handmatig Android:
1. Controleer versie v0.4.0.
2. Open Geometrie.
3. Kies P00 en P14.
4. Bij 1200/1500 verwacht 5660.4 mm.
5. Toon controlelijn.
6. Zet Maten aan/uit in Raster.
