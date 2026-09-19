# TESTING — v0.6.4

Static gecontroleerd:
- PASS v0.6.4 marker
- PASS `anchors` optioneel aangevraagd
- PASS anchor-capability status
- PASS native anchor create attempt
- PASS anchor pose wordt per frame gelezen
- PASS Herijk-knop
- PASS herijking verschuift alle geplaatste punten met exact dezelfde delta
- PASS bestaande 3D markers/objectselector behouden
- PASS flat 5-file ZIP

Fysieke test:
1. Start AR en controleer anchorstatus.
2. Plaats P00 op een fysieke markering.
3. Plaats P01.
4. Beweeg P00 uit beeld en kom terug.
5. Controleer drift.
6. Bij drift: druk Herijk.
7. Richt groen vizier exact op fysieke P00 en tik.
8. P00 moet terug op de referentie liggen.
9. P01 moet met exact dezelfde correctie mee verplaatsen.
10. Herhaal weg/terug-test.

Let op: deze versie corrigeert bij handmatige herijking translatie. Een tweede referentie voor expliciete oriëntatiecorrectie volgt pas als deze test slaagt.
