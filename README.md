# 💎 Crystalline — Comprehensive Crystal Structures Database

> A scientifically rigorous, artist-friendly database of crystalline mineral structures
> for AI art generation, shader development, game/VFX pipelines, generative design,
> and scientific visualization.

[![entries](https://img.shields.io/badge/crystal_entries-120%2B-blueviolet)]()
[![systems](https://img.shields.io/badge/crystal_systems-7-blue)]()
[![license](https://img.shields.io/badge/license-MIT-green)]()

---

## 📖 What Is This?

**Crystalline** is a comprehensive reference database of mineral crystal structures,
combining crystallographic precision with creative and engineering utility:

- **Accurate crystallographic parameters** — space groups, lattice constants, symmetry operations
- **Physical properties** — density, Mohs hardness, optical constants, phonon frequencies
- **Visual and artistic descriptors** — curated for generative AI, shaders, and game art
- **120+ mineral entries** spanning all 7 crystal systems and all 230 space groups

---

## 🗂 Directory Structure

```
crystalline/
├── README.md                        # This file
├── CRYSTAL_SYSTEMS.md               # Overview of all 7 crystal systems
├── core/
│   ├── crystals_database.json       # Master database (120+ entries)
│   └── crystal_systems/
│       ├── master_index.md          # Cross-system comparison table
│       ├── 01_cubic.md              # Cubic system — full documentation
│       ├── 02_hexagonal.md          # Hexagonal system
│       ├── 03_tetragonal.md         # Tetragonal system
│       ├── 04_trigonal.md           # Trigonal/Rhombohedral system
│       ├── 05_orthorhombic.md       # Orthorhombic system
│       ├── 06_monoclinic.md         # Monoclinic system
│       └── 07_triclinic.md          # Triclinic system
├── data/                            # Supplementary data files
├── visual/
│   └── palettes/                    # Color palettes by crystal type
├── math/                            # Mathematical reference formulas
├── physics/                         # Physical properties references
├── shaders/                         # GLSL shader references and stubs
├── creative/                        # AI art prompts and descriptors
├── analysis/                        # Analysis scripts and tools
└── metadata/                        # Provenance and versioning info
```

---

## 🎯 Use Cases

### 🤖 AI Art & Generative Design
Each entry includes `ai_art_tags`, `visual_profile`, and `color` descriptors optimized for:
- Stable Diffusion / FLUX prompt engineering
- Midjourney style descriptors
- ComfyUI node workflows

**Example — Diamond entry tags:**
```
["adamantine luster", "octahedral crystal", "brilliant dispersion",
 "colorless transparent", "cubic geometry", "rainbow caustics"]
```

### 🎮 Game Development & VFX
- `shader_ref` maps each mineral to a `.glsl` file for PBR pipelines
- Optical constants (refractive index, birefringence) drive material shaders
- Lattice constants as procedural noise seeds
- `phonon_freq_cm1` arrays → audio/haptic material feedback

### 🔬 Scientific Visualization
- Accurate space groups in Hermann-Mauguin notation
- Lattice constants in Ångströms (Å), angles in degrees
- Density (g/cm³), Mohs hardness, optical class
- Phonon vibrational modes in wavenumbers (cm⁻¹)

### 🎵 Music & Sound Design
- Convert phonon frequencies: `f_Hz = freq_cm⁻¹ × 2.998 × 10¹⁰`
- Crystal "fingerprint spectra" as synthesizer harmonic series
- Birefringence values as frequency ratios for FM synthesis
- Mineral lattice ratios as rhythmic subdivisions

### 📐 Procedural Architecture & Design
- Unit-cell ratios (c/a, b/a) as architectural proportion systems
- Symmetry operations as Islamic geometric tiling rules
- Point group orders as subdivision counts
- Packing fractions as fill densities

---

## ⚡ Quick Start

```python
import json

with open("core/crystals_database.json") as f:
    db = json.load(f)

# Find all cubic minerals
cubic = [c for c in db if c["system"] == "Cubic"]

# Find gems harder than Mohs 7
gems = [c for c in db
        if isinstance(c["hardness_mohs"], (int, float))
        and c["hardness_mohs"] >= 7]

# Piezoelectric crystals only
piezo = [c for c in db if c["piezoelectric"]]

# Convert phonon frequencies to Hz for audio synthesis
quartz = next(c for c in db if c["name"] == "Quartz")
freqs_hz = [f * 2.998e10 for f in quartz["phonon_freq_cm1"]]

# Build AI art prompt from tags
gold = next(c for c in db if c["name"] == "Gold")
prompt = ", ".join(gold["ai_art_tags"]) + ", macro photography, 8k"
```

---

## 📋 Data Format

Every entry in `core/crystals_database.json`:

| Field | Type | Description |
|-------|------|-------------|
| `id` | string | Unique ID, format `CRYST-NNN-ABR` |
| `name` | string | Mineral/material name |
| `formula` | string | Chemical formula |
| `system` | string | Crystal system (one of 7) |
| `space_group` | string | Hermann-Mauguin space-group symbol |
| `lattice_a/b/c` | number\|null | Unit-cell lengths in Å (null if = a) |
| `alpha/beta/gamma` | number | Inter-axial angles in degrees |
| `density` | number | Density in g/cm³ |
| `hardness_mohs` | number\|string | Mohs hardness (string for ranges) |
| `refractive_index` | number\|string\|null | RI or "opaque" |
| `color` | string | Characteristic color description |
| `transparency` | string | Transparent / Translucent / Opaque |
| `luster` | string | Luster type |
| `cleavage` | string | Cleavage description |
| `fracture` | string | Fracture type |
| `phonon_freq_cm1` | array | Characteristic IR/Raman peaks (cm⁻¹) |
| `birefringence` | number\|null | |δ| = |ne − no| or nz − nx |
| `optical_class` | string | Isotropic / Uniaxial / Biaxial |
| `piezoelectric` | boolean | True if non-centrosymmetric SG |
| `visual_profile` | string | Artist-friendly visual description |
| `ai_art_tags` | array[5] | Prompt engineering tags |
| `shader_ref` | string | Suggested GLSL shader filename |
| `uses` | array | Industrial/artistic applications |
| `formation` | string | Geological/synthetic origin |

---

## 📚 Data Sources

- American Mineralogist Crystal Structure Database (AMCSD)
- Inorganic Crystal Structure Database (ICSD)
- Mineralogical Society of America — *Reviews in Mineralogy & Geochemistry*
- *Dana's New Mineralogy*, 8th Edition
- RRUFF Project (rruff.info) — Raman/IR spectra
- WebMineral.com — supplementary physical properties

## 📄 License

MIT — free for commercial, academic, and creative use. Attribution appreciated.
