# Bomal Fundering v0.7.7.1 — Stability Assisted Anchoring

Basis: v0.7.7.0.1.

## Verwijderd
De experimentele tegelherkenning is volledig verwijderd. Er wordt buiten WebXR geen aparte camera meer gestart.

## Nieuw: stabiliteitsmeting P00/P03
Bij `PRECISIE VASTZETTEN`:
- de app verzamelt ongeveer 0,85 seconde geldige hit-testposities;
- horizontale spreiding van de metingen wordt berekend;
- bij meer dan 18 mm spreiding wordt de plaatsing geweigerd met `TE VEEL BEWEGING`;
- bij voldoende stabiliteit kiest de app de echte hit-testmeting die het dichtst bij de mediaan ligt;
- op precies die `XRHitTestResult` wordt de echte WebXR-anchor aangemaakt.

Dit vermijdt het verzinnen van een anchorpositie: `createAnchor()` blijft op een echte gemeten hit-test gebeuren.

Behouden: P00/P03 anchorarchitectuur, Undo, 3×5 raster, labels, cirkel+kruis en schakelbare hoogtehulp.
