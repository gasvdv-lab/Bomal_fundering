# Bomal Fundering v0.7.13.1 — AR Start Runtime Fix

v0.7.13.0 bevatte één harde runtimefout:
`checkedPoints.clear()` werd uitgevoerd vóór `checkedPoints` was aangemaakt.
Daardoor stopte het volledige JavaScript bij het laden en reageerden Controleer AR / Start AR niet.

Fix:
- correcte initialisatievolgorde;
- controlemodus behouden;
- blauwe punten-status behouden;
- PRECISIE/DIRECT behouden;
- groene fullscreen-fix behouden;
- alle inline JavaScript opnieuw met `node --check` gecontroleerd.
