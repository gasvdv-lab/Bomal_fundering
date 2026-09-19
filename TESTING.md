# TESTING — v0.6.2

Static gecontroleerd:
- PASS v0.6.2 marker.
- PASS body krijgt `ar-mode` bij succesvolle AR-start.
- PASS header wordt tijdens AR verborgen.
- PASS volledige normale main-interface wordt tijdens AR verborgen.
- PASS AR HUD blijft zichtbaar.
- PASS Stop-knop blijft klikbaar.
- PASS `ar-mode` wordt na Stop verwijderd.
- PASS rood/groen hit-testvizier behouden.
- PASS P00/P01 workflow behouden.
- PASS flat ZIP met 5 bestanden.

Fysiek testen op Android:
1. AR Test > Controleer AR > Start AR.
2. Alleen camera + compacte HUD mogen zichtbaar zijn.
3. Geen gewone menu's of kaarten mogen in beeld staan.
4. Beweeg rustig over de vloer.
5. Vizier moet bij een gevonden oppervlak rood -> groen gaan.
6. Tik groen vizier voor P00.
7. Richt op P01 en tik.
8. Stop: normale app moet volledig terugkomen.
