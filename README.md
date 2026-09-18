# bomal_fundering v0.2.2 — Mobile Fix

## Live app / vaste testlink
https://gasvdv-lab.github.io/Bomal_fundering/index.html

## Doel
Eenvoudige funderingshulp: een exact orthogonaal raster van tegelmiddelpunten voorbereiden en later in AR op het terrein gebruiken voor visuele verificatie. De lasermeter blijft het definitieve meettoestel.

## Deze release
- Herstelt de niet-reagerende knoppen van v0.2.1 op mobiel.
- Geen ES-module imports meer: de browser laadt één klassiek JavaScript-bestand.
- Raster maken, Invoer/Raster tabs, Op alle, Nieuw en punt actief/leeg zijn functioneel.
- Excel-achtige rasteropbouw via aantal punten horizontaal × verticaal.
- P00 ligt links onderaan op (0,0).
- Horizontale en verticale afstanden worden intern in mm verwerkt.
- Bestaande lokale v0.2.1-data wordt automatisch ingelezen indien aanwezig.
- Cache-busting toegevoegd aan CSS/JS zodat GitHub Pages sneller de nieuwe release gebruikt.

## Installeren via GitHub
Upload de inhoud van deze ZIP naar de root van de `main` branch en vervang de bestaande bestanden. GitHub Pages blijft ingesteld op `main` + `/(root)`.

## Snelle test op smartphone
1. Open de vaste testlink hierboven.
2. Controleer dat bovenaan `v0.2.2 · Mobile Fix` staat.
3. Kies 5 horizontaal en 3 verticaal.
4. Tik `Raster maken` — de invoervelden moeten verschijnen.
5. Vul bij horizontaal `1200` in en tik `Op alle`.
6. Vul bij verticaal `1500` in en tik `Op alle`.
7. Tik `Raster` — er moeten 15 punten P00 t/m P14 verschijnen.
8. Tik een punt — de status wisselt tussen ACTIEF en LEEG.

## Bekende beperking
Dit is nog geen AR-release. v0.2.2 focust uitsluitend op een betrouwbare mobiele rastereditor.
