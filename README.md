# Bomal Fundering v0.7.11.1 — No Green Camera Layer

Gerichte renderer-fix:
- de app wist de WebXR COLOR_BUFFER niet meer;
- de app tekent geen achtergrondkleur/tint over het camerabeeld;
- alleen de DEPTH_BUFFER wordt per XR-frame gewist;
- globale alpha blending voor de AR-overlay is uitgeschakeld;
- groen wordt uitsluitend gebruikt voor echte GL_LINES van raster/cirkels/kruisen;
- Master Anchor-logica van v0.7.11.0 blijft behouden.
