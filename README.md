# bomal_fundering v0.7.2.1 — Rotation Direction Fix

Gerichte hotfix op v0.7.2.

De tweede fysieke referentie (bv. P03) werd correct geregistreerd, maar de yaw-rotatie werd met het verkeerde teken toegepast voor de gebruikte WebXR X/Z-matrixconventie.

Fix:
- oud: `yaw = aWorld - aLocal`
- nieuw: `yaw = aLocal - aWorld`

Werkwijze:
1. Kies bv. P03 als richtingspunt.
2. Plaats P00.
3. Richt het vizier op het echte middelpunt van P03.
4. Tik.
5. P00 blijft vast en het volledige raster roteert rigide zodat de theoretische P03 naar de aangewezen richting draait.

Laser blijft de definitieve maatcontrole.

Live:
https://gasvdv-lab.github.io/Bomal_fundering/
