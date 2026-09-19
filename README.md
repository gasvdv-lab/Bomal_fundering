# Bomal Fundering v0.7.4.0 — Active Physical Relock

Deze release stopt met vertrouwen op een niet-beschikbare WebXR Anchor API.

## Werking
1. P00 vastleggen op de fysieke X.
2. P03 vastleggen voor de richting.
3. Raster verschijnt als één rigide object.
4. Als het raster zichtbaar verschuift:
   - richt opnieuw exact op P00;
   - druk `P00 positie corrigeren`.
   Het hele raster verschuift terug zonder de richting te wijzigen.
5. Als de richting fout loopt:
   - richt op P03;
   - druk `P03 richting corrigeren`.
   P00 blijft vast en het hele raster roteert opnieuw correct.

## Raster
3 kolommen × 5 rijen:
P12 P13 P14
P09 P10 P11
P06 P07 P08
P03 P04 P05
P00 P01 P02

Elk AR-doel is 300 × 300 mm met centrumkruis.

Dit is een actieve fysieke relock: de fysieke referenties corrigeren de WebXR-wereld tijdens dezelfde sessie. Laser/controlemetingen blijven definitief.

Live: https://gasvdv-lab.github.io/Bomal_fundering/
