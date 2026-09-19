# Bobcut (hair only)

Preview head removed. Single continuous mesh `bobcut`.

# Bobcut — longer cyberpunk A-line (sharp polygonal hairline)

Single continuous thick shell — seamless crown→sides (meridian grid + Solidify).

## Design
- **Dramatic A-line** (t106-style longer sides) — unpitched hem front **-1.05** / nape **+0.22** → after **-16°** pitch ≈ front tip **~-0.6**, nape **~-0.25** (strong slant)
- **Hairline** — flat planar strips with **hard temple corners** (Z_BROW=0.60 → Z_TEMPLE=0.38); not soft curves; not a soft coplanar brow bar
- Face opening sides at ±48°; brow kinks at ±20°
- Thick plates via Solidify (**0.18**), wraparound nape, glossy near-black
- Pitch **-16°** open-brow; unit sphere r=1; OBJ Y-up
- Manifold (0 non-manifold / 0 boundary); no GLB (numpy missing)

```bash
blender -b -P scripts/generate_bobcut.py
```
