# 02 — Hexagonal Crystal System

## Overview

The **hexagonal** system is characterized by a single 6-fold (or 6̄-fold) rotation axis
perpendicular to a plane containing two equal axes at 120°. The unit cell is a hexagonal
prism — a right prism with a regular hexagonal cross-section.

---

## Lattice Parameters

| Parameter | Constraint | Notes |
|-----------|-----------|-------|
| a | free | Basal plane axis |
| b | = a | Equivalent by hexagonal symmetry |
| c | free (≠ a) | Height of prism (unique axis) |
| α (alpha) | = 90° | |
| β (beta) | = 90° | |
| γ (gamma) | = 120° | Hexagonal basal angle |

**Degrees of freedom:** 2 (a and c are independent)

---

## Bravais Lattice

Only **one** Bravais lattice exists in the hexagonal system:
**hP** — Hexagonal Primitive

The primitive hexagonal cell contains 2 lattice points when compared to a conventional
rectangular description, but just 1 in the standard hexagonal setting.

*(Note: The rhombohedral lattice hR, sometimes grouped here, belongs to the trigonal system.)*

---

## Point Groups

| H-M Symbol | Schönflies | Order | Type | Piezoelectric |
|-----------|-----------|-------|------|--------------|
| 6 | C₆ | 6 | Hexagonal pyramidal | Yes |
| 6̄ | C₃h | 6 | Trigonal dipyramidal | No |
| 6/m | C₆h | 12 | Hexagonal dipyramidal | No |
| 622 | D₆ | 12 | Hexagonal trapezoidal | No |
| 6mm | C₆v | 12 | Dihexagonal pyramidal | Yes |
| 6̄m2 | D₃h | 12 | Ditrigonal dipyramidal | No |
| 6/mmm | D₆h | 24 | Dihexagonal dipyramidal (holohedric) | No |

---

## Space Groups (168–194)

**168–173: Point group 6**
P6 (168), P6₁ (169), P6₅ (170), P6₂ (171), P6₄ (172), P6₃ (173)

**174: Point group 6̄**
P6̄ (174)

**175–176: Point group 6/m**
P6/m (175), P6₃/m (176) — apatite, pyromorphite, molybdenite

**177–182: Point group 622**
P622 (177), P6₁22 (178), P6₅22 (179), P6₂22 (180), P6₄22 (181), P6₃22 (182)

**183–186: Point group 6mm**
P6mm (183), P6cc (184), P6₃cm (185), **P6₃mc (186)** — wurtzite structure

**187–190: Point group 6̄m2**
P6̄m2 (187), P6̄c2 (188), P6̄2m (189), **P6̄2c (190)**

**191–194: Point group 6/mmm**
**P6/mmm (191)**, P6/mcc (192), P6₃/mcm (193), **P6₃/mmc (194)** — graphite, ice, HCP metals

---

## c/a Ratio and HCP Significance

The **ideal HCP c/a ratio** for equal-sphere close-packing is:
```
c/a = sqrt(8/3) ≈ 1.6330
```

| Mineral/Metal | a (Å) | c (Å) | c/a | Notes |
|--------------|-------|-------|-----|-------|
| Magnesium | 3.209 | 5.211 | 1.624 | Near ideal |
| Titanium | 2.951 | 4.686 | 1.587 | Compressed |
| Zinc | 2.665 | 4.947 | 1.856 | Elongated |
| Beryllium | 2.287 | 3.584 | 1.567 | Compressed |
| Cadmium | 2.979 | 5.618 | 1.886 | Very elongated |
| Ice Ih | 4.523 | 7.367 | 1.629 | Near ideal |
| Graphite | 2.461 | 6.708 | 2.725 | Layered structure |
| Beryl | 9.215 | 9.192 | 0.997 | Ring silicate |

---

## HCP vs FCC Comparison

Both HCP (hexagonal close-packed) and FCC (face-centered cubic/CCP) achieve
74.05% packing efficiency with CN=12, but differ in stacking sequence:

| Property | HCP | FCC/CCP |
|----------|-----|---------|
| Stacking | ABABAB... | ABCABC... |
| Space group | P6₃/mmc (194) | Fm3̄m (225) |
| Close-packed planes | (0001) basal | {111} planes |
| Stacking fault energy | lower | higher |
| Slip systems | 3 basal | 12 {111}⟨110⟩ |
| Example metals | Mg, Ti, Zn, Co | Cu, Al, Au, Ag, Ni |

---

## Crystal Examples

| Mineral | Formula | a (Å) | c (Å) | c/a | Space Group | Density | Hardness |
|---------|---------|-------|-------|-----|------------|---------|---------|
| Quartz (α) | SiO₂ | 4.913 | 5.405 | 1.100 | P3₁21 | 2.65 | 7 |
| Ice Ih | H₂O | 4.523 | 7.367 | 1.629 | P6₃/mmc | 0.917 | 1.5 |
| Graphite | C | 2.461 | 6.708 | 2.725 | P6₃/mmc | 2.23 | 1.5 |
| Zinc | Zn | 2.665 | 4.947 | 1.856 | P6₃/mmc | 7.133 | 2.5 |
| Beryl | Be₃Al₂Si₆O₁₈ | 9.215 | 9.192 | 0.997 | P6/mcc | 2.76 | 7.5 |
| Apatite | Ca₅(PO₄)₃F | 9.432 | 6.881 | 0.730 | P6₃/m | 3.20 | 5.0 |
| Molybdenite | MoS₂ | 3.160 | 12.295 | 3.891 | P6₃/mmc | 4.73 | 1.5 |
| Wurtzite | ZnS | 3.820 | 6.257 | 1.638 | P6₃mc | 4.09 | 3.5 |
| Greenockite | CdS | 4.135 | 6.713 | 1.623 | P6₃mc | 4.82 | 3.0 |
| Titanium | Ti | 2.951 | 4.686 | 1.587 | P6₃/mmc | 4.507 | 6.0 |
| Magnesium | Mg | 3.209 | 5.211 | 1.624 | P6₃/mmc | 1.738 | 2.5 |
| Vanadinite | Pb₅(VO₄)₃Cl | 10.331 | 7.347 | 0.711 | P6₃/m | 6.88 | 3.0 |
| Pyromorphite | Pb₅(PO₄)₃Cl | 9.973 | 7.327 | 0.735 | P6₃/m | 7.04 | 3.5 |
| Mimetite | Pb₅(AsO₄)₃Cl | 10.260 | 7.440 | 0.725 | P6₃/m | 7.24 | 3.5 |
| Tridymite | SiO₂ | 5.052 | 8.270 | 1.637 | P6₃/mmc | 2.27 | 7.0 |

---

## Mathematical Formulas

### Unit Cell Volume
```
V = a² · c · sin(60°) = a² · c · (√3/2)
```

### d-Spacing (hexagonal)
```
1/d²_hkl = (4/3) · (h² + hk + k²)/a² + l²/c²
```

### Structure Factor for Hexagonal Close-Packed (P6₃/mmc)
Atoms at (1/3, 2/3, 1/4) and (2/3, 1/3, 3/4):
```
F_hkl = f · [exp(2πi(h/3 + 2k/3 + l/4)) + exp(2πi(2h/3 + k/3 + 3l/4))]
```

### Bragg's Law
```
2 · d_hkl · sin(θ) = n · λ
```

### Miller-Bravais Indices (4-index notation)
For hexagonal: (hkil) where i = -(h+k)
- Basal plane: (0001)
- Prism face: (101̄0) or (1̄010)
- Pyramidal face: (101̄1) or (112̄2)

---

## Visual Characteristics

- **Crystal habit:** Hexagonal prisms, bipyramids, plates, columns
- **Basal sections:** Regular hexagons
- **Prismatic sections:** Rectangles
- **Optical appearance:** Uniaxial — shows interference figure with single optic axis
- **Color in crossed polars:** Varies from extinction (viewing down c-axis) to maximum birefringence colors
- **Common forms:** {0001} basal pinacoid, {101̄0} hexagonal prism, {101̄1} pyramids

---

## AI Art Descriptors

**General hexagonal:**
`hexagonal prism crystal, six-sided column, prismatic habit, geometric natural form`

**Beryl/Emerald:**
`emerald green hexagonal prism, vitreous luster, gem quality crystal, deep forest green`

**Apatite:**
`blue-green hexagonal apatite crystal, translucent prismatic form, pastel mineral`

**Graphite:**
`layered hexagonal graphite, metallic grey sheets, hexagonal close-packed layers, 2D material`

**Ice crystals:**
`snowflake hexagonal symmetry, ice crystal, six-fold branching, frost pattern, winter macro`

**Vanadinite:**
`bright orange-red vanadinite hexagonal crystals, small barrel-shaped prisms, metallic matrix`
