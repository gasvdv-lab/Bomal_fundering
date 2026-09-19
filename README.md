# bomal_fundering v0.6.6.1 — Button Fix

Deze release is bewust teruggebracht tot één AR-doel: P00 correct world-locked krijgen.

## AR-diagnose
- één P00;
- geen P01;
- geen native anchors;
- geen herijking;
- geen tweepuntskalibratie;
- één vast doelwit;
- P00 wordt één keer uit de hit-testpose opgeslagen;
- opgeslagen P00-coördinaten worden daarna niet meer aangepast;
- HUD toont de bevroren local X/Y/Z-coördinaten.

## Test
Plaats P00 op een herkenbare fysieke markering. Beweeg daarna de telefoon ongeveer 1 meter links/rechts, vooruit/achteruit en rond P00 terwijl het punt zichtbaar blijft. P00 moet fysiek op dezelfde plaats blijven.

Breng P00 daarna uit beeld en kijk opnieuw naar dezelfde fysieke plaats. Noteer afzonderlijk of:
1. het punt tijdens zichtbare camerabeweging meeschuift;
2. het pas na uit beeld gaan verspringt;
3. het na een sprong vanzelf terugkeert.

De laser blijft de definitieve maatvoering.

## Live app
De eerder gebruikte Pages-link was door de gebruiker als onjuist gemeld. Vul de correcte GitHub Pages-URL in zodra die bevestigd is.

## Hotfix
Herstelt een JavaScript-syntaxfout in v0.6.6 waardoor de knoppen niet reageerden. De AR-diagnose blijft één P00 zonder anchors of herijking.
