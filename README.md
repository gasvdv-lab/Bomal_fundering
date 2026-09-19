# Bomal Fundering v0.7.9.2 — Anchor Recovery

Deze release is opnieuw opgebouwd vanaf de bewezen v0.7.7.1.1 technische baseline.

Doel: eerst de echte WebXR-verankering herstellen en niet verder bouwen op de gewijzigde v0.7.9.x anchorcode.

Behouden uit de bewezen baseline:
- echte P00 WebXR-anchor;
- echte P03 WebXR-anchor;
- poses via `frame.getPose(anchor.anchorSpace, xrRef)`;
- bestaande stabiliteitsmeting;
- exact 3×5 raster;
- OFFSET;
- HOOGTEHULP;
- labels en puntmarkeringen.

Gerichte toevoegingen:
- UNDO: eerst P03, daarna P00;
- cirkels/kruisjes hebben een andere kleur dan de rasterlijnen.

Niet meegenomen:
- rigid orientation lock uit v0.7.9.0;
- nieuwe wijzigingen aan de stabiliteits-/anchorarchitectuur.

Laser blijft de definitieve maatcontrole.
