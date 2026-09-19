# Bomal Fundering v0.7.10.0 — Master Anchor Raster

Architectuurcorrectie:
- P00 en P03 worden als echte WebXR anchors geplaatst.
- P03 bepaalt éénmalig de lokale rasteroriëntatie.
- Daarna wordt géén absolute wereldpositie als rasterlock opgeslagen.
- Iedere XR-frame gebruikt het raster de actuele pose van P00's `anchorSpace` als mastertransformatie.
- P01–P14 zijn vaste lokale punten van hetzelfde rigide raster.
- P03 wordt na de lock niet gebruikt om de geometrie opnieuw te berekenen.
- Rasterlijnen, cirkels, kruisen en labels gebruiken dezelfde mastertransformatie.
- OFFSET is één gemeenschappelijke lokale offset voor P00–P14.
- Hoogtehulp is volledig verwijderd.
