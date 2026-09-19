# Female cyberpunk hairstyles

Hyper-minimal thick glossy near-black plastic plates — same visual language as the Cliphost bobcut / male set.
Fits unit sphere head r=1.0. OBJ Y-up, face +Z (export from Blender −Y face).

| Style | Description | Verts |
|-------|-------------|-------|
| `long_aline/` | Long elegant A-line — shoulder front, short nape, trapezoid HL | 1442 |
| `pixie/` | Short polished pixie — cropped nape, fuller crown, angular bangs | 898 |
| `twin_buns/` | Twin disc buns above temples + short shell base | 966 |

## Generate
```bash
blender -b -P scripts/generate_all_female.py
```

Each style folder has `{name}.obj` / `.mtl` / `.blend` (hair only), `previews/`, and `scripts/`.
