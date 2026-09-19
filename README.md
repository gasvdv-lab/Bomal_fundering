# Bomal Fundering v0.7.7.0 — Undo + Tile Detection Test

Deze release combineert de geplande v0.7.6.1 en v0.7.7.0.

## AR Undo
- P00 geplaatst: UNDO verwijdert P00.
- P00 + P03 geplaatst: eerste UNDO verwijdert alleen P03.
- Tweede UNDO verwijdert daarna P00.
- Het theoretische raster wordt nooit gewijzigd door UNDO.

## Tegelherkenning test
Buiten de immersive AR-modus staat `TEGELHERKENNING TEST`.
De achtercamera zoekt een tegelkandidaat rond het midden van het camerabeeld, tekent een contourkader en toont een kruis/cirkel op het berekende centrum.

Dit is bewust nog een geïsoleerde herkenningstest:
- detectie maakt nog GEEN WebXR-anchor;
- P00/P03-anchorlogica is niet gewijzigd;
- gebruiker moet eerst buiten testen of echte tegels op het terrein betrouwbaar worden herkend.

De bestaande cirkels, kruisen, P00–P14 labels en schakelbare hoogtehulp blijven behouden.
Geen afbeeldingen of mediabestanden in de ZIP.
