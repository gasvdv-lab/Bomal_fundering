# bomal_fundering v0.6.7.1 — Native Anchor Startup Fix

Deze release test één enkele P00 als echte native WebXR Anchor.

## Werking
1. ARCore/WebXR zoekt een geldig oppervlak via hit-test.
2. Tik om P00 te plaatsen.
3. De app roept `XRHitTestResult.createAnchor()` aan op exact die hit.
4. Na plaatsing wordt P00 niet meer uit de oorspronkelijke losse x/y/z gerenderd.
5. Iedere frame wordt de actuele pose uit `anchor.anchorSpace` opgevraagd.
6. Als de anchor-pose tijdelijk niet beschikbaar is, wordt P00 verborgen en verschijnt `P00 TRACKING VERLOREN`.
7. Er is bewust géén losse-coordinate fallback die een mogelijk fout punt kan tonen.
8. Zodra de native anchor opnieuw traceerbaar is, verschijnt P00 opnieuw.

## Doel
Test of één fysiek punt robuuster vastgepind blijft wanneer je:
- links/rechts beweegt;
- rond P00 loopt;
- P00 tijdelijk uit beeld brengt;
- daarna terug naar dezelfde fysieke plaats kijkt.

Native AR-anchors zijn geen garantie voor landmeetkundige nauwkeurigheid. De laser blijft de definitieve maatvoering.

## Live app
https://gasvdv-lab.github.io/Bomal_fundering/

## Hotfix 0.6.7.1
Herstelt de startupfout `lastHitResult is not defined`. De native-anchor test zelf blijft ongewijzigd.
