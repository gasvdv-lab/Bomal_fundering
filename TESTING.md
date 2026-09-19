# TESTING — v0.7.7.1.1

1. Start AR en plaats P00/P03 zoals in v0.7.7.1.
2. Controleer dat de beginwaarde `HOOGTE 0 mm` is.
3. Controleer dat raster/cirkels/kruisen niet meer bewust +14 mm boven P00 worden getekend.
4. Druk `+`: waarde moet per druk 2 mm stijgen.
5. Druk `−`: waarde moet per druk 2 mm dalen.
6. Controleer minimum −20 mm en maximum +50 mm.
7. Controleer dat alleen de visuele overlay omhoog/omlaag gaat.
8. Controleer dat P00/P03 anchors niet opnieuw worden aangemaakt of verplaatst.
9. Test UNDO.
10. Test HOOGTEHULP en labels.
11. Loop weg en terug naar P00/P03 en controleer de anchorstabiliteit.

Laser blijft de definitieve maatcontrole.
