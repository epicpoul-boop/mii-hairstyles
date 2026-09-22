# Style 03 — Sleek Bob with Arched Bangs

Cute chibi bob for head sphere **r=0.5m** at origin. Sleek, polished, soft arched bangs.

## Fit notes
- Object `Hair_03_SleekBob` at origin, ~**0.02m** clearance over head r=0.5
- Base: UV-sphere recipe r=**0.55**, scale **(1.05, 0.95, 1.05)**, keep top **62%**
- Thickness **0.08m** Solidify applied; bottom rim pulled **inward**
- Bangs: soft inverted U — **lowest center** z≈0.22, **highest temples** z≈0.43; extrude **0.14m**; **8** edge loops across bangs
- Bevel bottom 3 segments; Subdivision Surface Level **2** (modifier on .blend; applied on GLB export)
- Shade Smooth + Auto Smooth 45°
- Side silhouette: smooth dome, no sharp points

## Mesh stats (OBJ control cage)
- verts=957 faces=988
- tris=70 quads=914 ngons=4
- bang-region tris=6
- nonmanifold=0 boundary=0
- GLB: yes

## Material
Principled BSDF Base **#231815**, Roughness **0.7**, Specular **0.25**, Subsurface **0.05**

```bash
blender -b -P scripts/generate_sleek_bob_03.py
```
