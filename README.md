# Bomal Fundering v0.7.11.2 — Green Screen Removal Test

Deze release doet bewust maar één hoofdzaak:
- het WebXR-canvas wordt NIET meer als fullscreen DOM-laag getoond;
- `#arCanvas` staat offscreen/onzichtbaar en dient alleen als WebGL-context voor `XRWebGLLayer`;
- de AR-HUD blijft via DOM overlay zichtbaar;
- achtergebleven hoogtehulp-restcode is verwijderd.

De Master Anchor-logica is verder niet gewijzigd.
