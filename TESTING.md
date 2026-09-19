# TESTING — v0.6.3
Static checks:
- PASS v0.6.3 marker
- PASS raw WebGL shader/program
- PASS per-XR-view projection/view matrix
- PASS P00/P01 persistent coordinates in local reference space
- PASS 7 marker/object choices
- PASS marker size control
- PASS P00/P01 connection line
- PASS clean AR mode retained
- PASS no external JS/3D library
- PASS flat 5-file ZIP

Physical Android checks required:
- camera + clean HUD
- hit-test red -> green
- P00 appears green after first tap
- P01 appears yellow after second tap
- line appears between P00/P01
- markers remain at physical references while moving
- assess drift after walking away and returning
