# TESTING — v0.7.2.2

1. Start AR in Android Chrome.
2. Plaats P00 op een exact herkenbaar fysiek punt. Controleer melding `P00 ECHT VERANKERD`.
3. Plaats P03 (of gekozen referentiepunt) op zijn fysieke positie.
4. Controleer dat het volledige raster verschijnt en correct draait.
5. Loop 1 m, 3 m en 5 m weg en terug.
6. Controleer P00 en meerdere verre rasterpunten tegen dezelfde fysieke grondposities.
7. Beweeg rond het raster en keer terug.
8. Bij tijdelijk anchor-trackingverlies moet het raster verborgen worden, niet op een oude pose blijven staan.

Belangrijkste regressietest: P00 mag niet meer als een eenmalig opgeslagen hit-testmatrix worden behandeld.
