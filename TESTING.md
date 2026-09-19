# TESTING — v0.7.2
- PASS JavaScript syntax
- PASS richtingspunt selector
- PASS P00 eerste fysieke referentie
- PASS tweede tik is gekozen Pxx
- PASS yaw uit theoretische en fysieke P00→Pxx vector
- PASS P00-translatie blijft behouden
- PASS volledig raster roteert rigide
- PASS AR-labels blijven gekoppeld aan punten
- PASS HUD heeft afzonderlijke P00/richtings/aligned states

Fysiek:
1. Kies P03.
2. Plaats P00.
3. Controleer HUD `P00 VAST · PLAATS NU P03`.
4. Richt op echte P03 en tik.
5. Controleer `RASTER UITGELIJND VIA P00 → P03`.
6. Controleer P00 en P03 met laser/markeringen.
