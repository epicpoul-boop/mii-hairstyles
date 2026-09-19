# Long A-line — elegant cyberpunk shell

Longer, sleeker A-line than the bobcut: **chin→shoulder** front length, **short nape**, sharp trapezoid hairline. Single continuous thick plate.

## Design
- Dramatic A-line hem front **−1.32** / nape **+0.40** (stronger slant than bob)
- Trapezoid hairline: Z_BROW=0.62 → Z_TEMPLE=0.36; face open ±50°; brow kinks ±18°
- Dense meridian grid (n_v=18) + Solidify **0.18** — clean silhouette, no ledges
- Pitch **−14°** open-brow; unit sphere r=1; OBJ Y-up; glossy near-black

```bash
blender -b -P scripts/generate_long_aline.py
```
