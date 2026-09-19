# Bomal Fundering v0.7.2.3 — P00 Anchor Isolation Test

Doel: één echte WebXR Anchor isoleren en vergelijken met de officiële WebXR anchor-demo die op het toestel stabiel bleef.

Bewust NIET aanwezig in AR: P03, raster, ProjectRoot, yaw/rotatie, tegelvorm of houten marker.

Werkwijze: start AR, zoek oppervlak, tik één keer voor P00, loop 1 m / 3 m / 5 m weg en terug. Het groene kruis wordt elke frame rechtstreeks uit `frame.getPose(p00Anchor.anchorSpace, xrRef)` gerenderd.
