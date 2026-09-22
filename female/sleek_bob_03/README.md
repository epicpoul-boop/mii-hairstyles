# Style 03 — Sleek Bob with Arched Bangs

Cute chibi sleek bob. Source screened from Mii Maker `hair.000`–`hair.040`; **chose `hair.004`** for soft arched bangs + V-notch.

## Facing
- Blender **Z-up**, face **−Y** (camera from −Y)

## Fit
- Head sphere r=0.5, outer half-width → 0.53 (~0.02–0.03 clearance)
- Bang tips pulled toward z≈0.16 (just above eyebrow/eye line)
- Mild side-notch fill so front silhouette isn't ear-C dominated
- Solidify **0.08** inward → watertight; Subsurf L1 on blend/GLB

## Material
Base **#231815**, Roughness **0.7**

## Stats
verts=1242 faces=1382 tris=284 quads=1098 nonmanifold=0 boundary=0 glb=yes

```bash
blender -b -P scripts/generate_sleek_bob_03.py
```
