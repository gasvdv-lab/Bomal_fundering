# bomal_fundering v0.6.4 — Anchor & Recalibration

## Live app
https://gasvdv-lab.github.io/Bomal_fundering/

Doel: het probleem aanpakken waarbij een marker goed blijft staan zolang hij zichtbaar is, maar na uit beeld gaan en terugkeren verschoven kan zijn.

Nieuw:
- vraagt WebXR `anchors` als optionele feature;
- toont of native WebXR Anchors werkelijk beschikbaar zijn;
- probeert P00/P01 aan een native anchor te koppelen;
- gebruikt tijdens rendering de actuele anchor-pose wanneer die beschikbaar is;
- nieuwe `Herijk`-knop;
- herijking: richt opnieuw exact op de fysieke P00 en tik;
- de correctie wordt als één translatie op ALLE geplaatste punten toegepast;
- de onderlinge rastergeometrie wordt dus niet vervormd;
- fallback blijft bruikbaar als browser/toestel geen WebXR Anchors ondersteunt.

Belangrijk:
Anchors zijn geen garantie voor millimeterprecisie. De laser blijft de definitieve maatvoering. Deze release test of anchors + expliciete herijking de relokalisatie praktisch bruikbaar maken.
