# 01 — Cubic Crystal System

## Overview

The **cubic** (isometric) crystal system is the most symmetric of the seven systems.
It is characterized by three mutually perpendicular axes of **equal length**,
giving a perfect cube as the unit cell.

---

## Lattice Parameters

| Parameter | Constraint | Physical Meaning |
|-----------|-----------|-----------------|
| a | free | Cube edge length |
| b | = a | Equal to a |
| c | = a | Equal to a |
| α (alpha) | = 90° | Angle between b and c |
| β (beta) | = 90° | Angle between a and c |
| γ (gamma) | = 90° | Angle between a and b |

**Degrees of freedom:** 1 (only a is free)

---

## Bravais Lattices

| Symbol | Name | Points/Cell | Description |
|--------|------|------------|-------------|
| cP | Primitive cubic | 1 | Lattice points at cube corners only |
| cI | Body-centered cubic (BCC) | 2 | Corner + body-center points |
| cF | Face-centered cubic (FCC) | 4 | Corner + face-center points |

---

## Point Groups

| H-M Symbol | Schönflies | Order | Type | Piezoelectric |
|-----------|-----------|-------|------|--------------|
| 23 | T | 12 | Chiral tetrahedral | Yes |
| m3̄ | Th | 24 | Pyritohedral | No |
| 432 | O | 24 | Chiral octahedral | No |
| 4̄3m | Td | 24 | Tetrahedral | Yes |
| m3̄m | Oh | 48 | Full octahedral | No |

---

## Space Groups (195–230)

**195–199: Point group 23 (T)**
Pm3̄ (195), Pn3̄ (201), Fm3̄ (202), Fd3̄ (203), Im3̄ (204), Pa3̄ (205), Ia3̄ (206)

**200–206: Point group m3̄ (Th)**

**207–214: Point group 432 (O)**
P432 (207), P4₂32 (208), F432 (209), F4₁32 (210), I432 (211), P4₃32 (212), P4₁32 (213), I4₁32 (214)

**215–220: Point group 4̄3m (Td)**
P4̄3m (215), F4̄3m (216), I4̄3m (217), P4̄3n (218), F4̄3c (219), I4̄3d (220)

**221–230: Point group m3̄m (Oh)** — most mineral structures
Pm3̄m (221), Pn3̄n (222), Pm3̄n (223), Pn3̄m (224),
**Fm3̄m (225)** — rock salt, close-packed metals,
**Fm3̄c (226)**, **Fd3̄m (227)** — diamond, spinel, magnetite,
Fd3̄c (228), **Im3̄m (229)** — BCC metals,
**Ia3̄d (230)** — garnet

---

## Packing Fractions and Coordination Numbers

| Structure | Space Group | η (packing) | CN | Nearest-neighbor distance |
|-----------|------------|-------------|-----|--------------------------|
| Simple cubic | Pm3̄m | 52.36% | 6 | d = a |
| Body-centered cubic | Im3̄m | 68.02% | 8 | d = a√3/2 |
| Face-centered cubic | Fm3̄m | 74.05% | 12 | d = a/√2 |
| Diamond cubic | Fd3̄m | 34.01% | 4 | d = a√3/4 |
| NaCl structure | Fm3̄m | ~79% (ionic) | 6+6 | d = a/2 |
| CsCl structure | Pm3̄m | ~73% (ionic) | 8+8 | d = a√3/2 |
| Fluorite (CaF₂) | Fm3̄m | — | 8+4 | Ca-F: a√3/4 |
| Spinel (AB₂O₄) | Fd3̄m | — | 4+6 | complex |

---

## Crystal Examples

| Mineral | Formula | a (Å) | Space Group | Density (g/cm³) | Hardness |
|---------|---------|-------|------------|----------------|---------|
| Halite | NaCl | 5.640 | Fm3̄m | 2.16 | 2.5 |
| Diamond | C | 3.567 | Fd3̄m | 3.515 | 10 |
| Gold | Au | 4.078 | Fm3̄m | 19.30 | 2.5 |
| Copper | Cu | 3.615 | Fm3̄m | 8.96 | 3.0 |
| Iron (α) | Fe | 2.866 | Im3̄m | 7.874 | 4.0 |
| Fluorite | CaF₂ | 5.463 | Fm3̄m | 3.18 | 4.0 |
| Pyrite | FeS₂ | 5.417 | Pa3̄ | 5.01 | 6.5 |
| Galena | PbS | 5.936 | Fm3̄m | 7.58 | 2.5 |
| Magnetite | Fe₃O₄ | 8.397 | Fd3̄m | 5.17 | 5.5 |
| Spinel | MgAl₂O₄ | 8.086 | Fd3̄m | 3.58 | 7.5 |
| Almandine | Fe₃Al₂Si₃O₁₂ | 11.526 | Ia3̄d | 4.32 | 7.5 |
| Sphalerite | ZnS | 5.406 | F4̄3m | 4.09 | 3.5 |
| Periclase | MgO | 4.211 | Fm3̄m | 3.58 | 5.5 |

---

## Mathematical Formulas

### d-Spacing (interplanar spacing for Miller indices hkl)
```
d_hkl = a / sqrt(h² + k² + l²)
```

### Unit Cell Volume
```
V = a³
```

### Reciprocal Lattice Vector Magnitude
```
|G_hkl|² = (2π/a)² (h² + k² + l²)
```

### Structure Factor (general)
```
F_hkl = Σⱼ fⱼ · exp[2πi(h·xⱼ + k·yⱼ + l·zⱼ)]
```

### Structure Factor — FCC (Fm3̄m, 4 atoms/cell at 0,0,0; ½,½,0; ½,0,½; 0,½,½)
```
F_hkl = f × {1 + exp[πi(h+k)] + exp[πi(h+l)] + exp[πi(k+l)]}
= 4f  if h,k,l all even or all odd
= 0   if h,k,l mixed parity (systematic absence)
```

### Structure Factor — BCC (Im3̄m, 2 atoms at 0,0,0 and ½,½,½)
```
F_hkl = f × {1 + exp[πi(h+k+l)]}
= 2f  if h+k+l even
= 0   if h+k+l odd (systematic absence)
```

### Structure Factor — Diamond (Fd3̄m, 8 atoms/cell)
```
F_hkl = F_FCC × {1 + exp[πi(h+k+l)/2]}
= 8f    if h+k+l = 4n
= (4±4i)f  if h+k+l = 4n±1 (all same parity)
= 0     if mixed parity
```

---

## Miller Indices — Key Planes

| Plane family | Multiplicity | d_hkl | Example reflections |
|-------------|-------------|-------|-------------------|
| {100} | 6 | a | (100),(010),(001),(1̄00),... |
| {110} | 12 | a/√2 | (110),(101),(011),(1̄10),... |
| {111} | 8 | a/√3 | (111),(1̄11),(11̄1),(111̄),... |
| {200} | 6 | a/2 | (200),(020),(002),... |
| {210} | 24 | a/√5 | (210),(201),(012),... |
| {211} | 24 | a/√6 | (211),(121),(112),... |
| {220} | 12 | a/√8 | (220),(202),(022),... |
| {221} | 24 | a/3 | (221),(212),(122),... |
| {311} | 24 | a/√11 | (311),(131),(113),... |

---

## Visual Characteristics

- **Crystal habit:** Cube {001}, octahedron {111}, dodecahedron {110}, combinations
- **Cleavage:** Cubic {001} (galena, halite), octahedral {111} (fluorite, diamond), dodecahedral {110} (garnet)
- **Optical appearance:** Isotropic — unchanged under rotating polarizers; no birefringence
- **Face angles:** Cube edges all 90°; octahedra have 70.53° and 109.47° face angles
- **Twinning:** Spinel law (rotation about [111]), iron cross (pyrite), penetration twins (fluorite)

---

## AI Art Descriptors

**General cubic:**
`perfect geometric cube, equal-sided crystal, isometric symmetry, geometric perfection`

**Octahedral habit (diamond, fluorite, spinel):**
`adamantine octahedral gem, double pyramid crystal, brilliant facets, prismatic light dispersion`

**Cubic metal (gold, copper):**
`metallic crystalline grain, cubic close-packed lattice, warm metallic luster, atom sphere packing`

**Garnet (dodecahedral):**
`deep red dodecahedral garnet, rhombic faces, vitreous luster, wine-dark gemstone`

**Pyrite (cubic/pyritohedron):**
`fool's gold cubic crystals, metallic yellow cubes, striated faces, brassy luster`

**Spinel (octahedral):**
`deep red or blue spinel octahedra, gem-quality transparent crystal, brilliant luster`
