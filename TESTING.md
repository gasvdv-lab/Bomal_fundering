# TESTING — v0.7.7.1

1. Controleer dat `TEGELHERKENNING TEST` verdwenen is.
2. Start AR en richt op P00.
3. Druk `P00 PRECISIE VASTZETTEN`.
4. Houd de telefoon ongeveer 0,85 s stil.
5. Bij grote beweging moet `TE VEEL BEWEGING` verschijnen en mag P00 niet vastgelegd zijn.
6. Bij voldoende stabiliteit moet P00 een echte anchor krijgen.
7. Herhaal voor P03.
8. Test UNDO: eerst P03 verwijderen, daarna eventueel P00.
9. Controleer raster, labels, cirkels/kruisen en hoogtehulp.
10. Loop 1 m, 3 m en 5 m weg en terug en controleer stabiliteit.

Drempel huidige testrelease: maximaal 18 mm horizontale spreiding tijdens de meetperiode.
