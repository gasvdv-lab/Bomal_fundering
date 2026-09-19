# Bomal Fundering v0.7.8.2 — AR Controls Fix

Opnieuw opgebouwd vanaf de door de gebruiker aangeleverde v0.7.7.1.1.

Belangrijkste oorzaak gevonden: `#arVisual` gebruikt `pointer-events:none`. De bestaande werkende AR-knoppen hadden expliciet `pointer-events:auto`, maar de OFFSET-bediening niet. Daardoor was ze zichtbaar zonder betrouwbare touch-input.

Reparaties:
- OFFSET-bediening expliciet touch/click-actief.
- `beforexrselect` wordt op interactieve HUD-elementen tegengehouden.
- OFFSET gebruikt ±2 mm en verandert alleen `visualHeightOffset`.
- alle rastervisualisatie gebruikt dezelfde P00 + OFFSET-basis.
- Plaatsmodus gebruikt geen native select maar een expliciet P00–P14 knoppenpaneel voor betrouwbaardere WebXR DOM-overlay bediening.
- gekozen punt wordt groter; overige labels worden teruggenomen.
- P00/P03 anchor- en stabiliteitslogica uit v0.7.7.1.1 blijft onaangeroerd.
