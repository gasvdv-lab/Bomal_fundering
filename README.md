# bomal_fundering v0.6.3 — Persistent 3D Markers

## Live app
https://gasvdv-lab.github.io/Bomal_fundering/

Nieuw:
- P00 en P01 worden als echte WebGL-objecten in de WebXR-wereld gerenderd.
- P00 = groen, P01 = geel.
- verbindingslijn zodra beide punten geplaatst zijn.
- keuze uit: Doelwit, Kruis, Cirkel, Pin, Paaltje, Vlak/tegel, Kubus.
- instelbare grootte.
- markerkeuze verandert uitsluitend de visualisatie; de geometrische positie blijft identiek.
- geen externe 3D-library/CDN.

Test:
1. kies objecttype vóór Start AR;
2. Start AR en zoek vloer;
3. plaats P00;
4. P00 moet zichtbaar blijven wanneer de camera beweegt;
5. plaats P01;
6. beide markers + verbindingslijn moeten zichtbaar blijven;
7. loop weg en terug om world-lock/drift visueel te beoordelen.

De laser blijft de definitieve maatvoering.
