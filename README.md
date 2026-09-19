# Bomal Fundering v0.7.7.0.1 — Camera Hotfix

Gerichte hotfix op v0.7.7.0.

Probleem:
`Cannot set properties of null (setting 'srcObject')`

Oorzaak:
de JavaScript-code bewaarde verwijzingen naar de video/canvas-interface voordat die elementen beschikbaar waren.

Fix:
- camera-elementen worden pas opgezocht wanneer de tegelherkenning daadwerkelijk start;
- er is een expliciete controle toegevoegd dat video, canvas en overlay bestaan;
- de achtercamera-stream wordt daarna pas aan `video.srcObject` gekoppeld;
- camera-stream wordt netjes gestopt bij sluiten of een startfout.

Niet gewijzigd:
- P00/P03 WebXR anchors;
- 3×5 raster;
- Undo;
- labels/cirkels/kruisen;
- hoogtehulp;
- rastergeometrie.

Geen afbeeldingen in de ZIP.
