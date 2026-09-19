# Male cyberpunk hairstyles

Hyper-minimal thick glossy near-black plastic plates — same visual language as the Cliphost bobcut.
Fits unit sphere head r=1.0. OBJ Y-up, face +Z (export from Blender −Y face).

| Style | Description | Verts |
|-------|-------------|-------|
| `crew/` | Short military/crew cut — low hemispheric cap, even hem | 722 |
| `undercut/` | Flat-top undercut — thick top plate, bare sides | 522 |
| `slick/` | Asymmetric slicked side — +X volume plate | 722 |
| `spike/` | Short base + 5 geometric wedge spikes | 522 |

## Generate
```bash
blender -b -P scripts/generate_all_male.py
```

Each style folder has `{name}.obj` / `.mtl` / `.blend` (hair only), `previews/`, and `scripts/`.
