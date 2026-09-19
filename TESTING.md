# TESTING — v0.7.7.0

## Undo
1. Start AR en plaats P00.
2. Druk UNDO: P00 moet verdwijnen en opnieuw plaatsbaar zijn.
3. Plaats P00 en P03.
4. Druk UNDO: alleen P03 moet verdwijnen; P00 blijft staan.
5. Plaats P03 opnieuw.
6. Controleer dat raster/labels/hoogtehulp weer normaal werken.

## Tegelherkenning
1. Stop AR.
2. Start `TEGELHERKENNING TEST`.
3. Richt de achtercamera ongeveer op één echte tegel.
4. Controleer of een tegelkandidaat wordt omlijnd.
5. Controleer of kruis + cirkel ongeveer op het echte geometrische middelpunt liggen.
6. Test met verschillende kijkhoeken, licht, gras/modder en afstand.
7. Noteer situaties waarin de herkenning fout zit.

Deze versie gebruikt de herkenning nog niet om P00/P03 te verankeren.
