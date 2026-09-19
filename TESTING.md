# TESTING — v0.6.7

## Automatisch/static
- PASS: één P00
- PASS: `anchors` als optionele WebXR feature aangevraagd
- PASS: native anchor wordt vanaf XRHitTestResult aangemaakt
- PASS: rendering gebruikt actuele `anchorSpace` pose
- PASS: geen coordinate-fallback bij verloren anchor tracking
- PASS: marker wordt verborgen bij verloren anchor-pose
- PASS: bestaande AR Stop/start-flow behouden
- PASS: flat 5-file ZIP

## Fysieke test
1. Open AR.
2. Plaats P00 op een duidelijke fysieke markering.
3. Controleer dat `P00 VASTGEPIND · TRACKING OK` verschijnt.
4. Beweeg links/rechts en vooruit/achteruit.
5. Loop rond P00.
6. Breng P00 uit beeld.
7. Kijk terug naar dezelfde fysieke markering.
8. Noteer: stabiel / springt / tracking verloren / keert correct terug.
9. Indien `NATIVE ANCHOR NIET BESCHIKBAAR` verschijnt: meld dit exact; de app plaatst dan bewust geen nep-fallback.
