# 05 — Orthorhombic Crystal System

## Overview

The **orthorhombic** system has three mutually perpendicular axes of **all different lengths**.
It is the lowest-symmetry system with all right angles. The unit cell is a rectangular
parallelepiped (box) with unequal edges. By convention: a < b < c.

---

## Lattice Parameters

| Parameter | Constraint |
|-----------|-----------|
| a | free |
| b | free (≠ a) |
| c | free (≠ a, ≠ b) |
| α | = 90° |
| β | = 90° |
| γ | = 90° |

**Degrees of freedom:** 3 (a, b, c all independent)

---

## Bravais Lattices

| Symbol | Name | Points/Cell | Notes |
|--------|------|------------|-------|
| oP | Primitive orthorhombic | 1 | |
| oC | C-centered orthorhombic | 2 | Also A or B centered (same lattice) |
| oI | Body-centered orthorhombic | 2 | |
| oF | Face-centered orthorhombic | 4 | |

---

## Point Groups

| H-M Symbol | Schönflies | Order | Type | Piezoelectric |
|-----------|-----------|-------|------|--------------|
| 222 | D₂ | 4 | Three 2-fold axes | Yes |
| mm2 | C₂v | 4 | Two mirrors + 2-fold axis | Yes |
| mmm | D₂h | 8 | Three mirrors + inversion (holohedric) | No |

---

## Space Groups (16–74)

**16–24: Point group 222**
P222 (16), P222₁ (17), P2₁2₁2 (18), P2₁2₁2₁ (19), C222₁ (20), C222 (21),
F222 (22), I222 (23), I2₁2₁2₁ (24)

**25–46: Point group mm2**
Pmm2 (25), Pmc2₁ (26), Pcc2 (27), Pma2 (28), **Fdd2 (43)** — natrolite type,
Imm2 (44), Ima2 (46)

**47–74: Point group mmm**
Pmmm (47), Pnnn (48), Pccm (49), **Pnma (62)** — olivine/forsterite (most common oP SG),
**Cmca (64)** — many minerals, Cmmm (65), Cccm (66), Cmme (67), Ccce (68),
**Fddd (70)** — sulfur, **Immm (71)**, Ibam (72), Ibca (73), Imma (74)

---

## Crystal Examples

| Mineral | Formula | a (Å) | b (Å) | c (Å) | Space Group | Density | Hardness |
|---------|---------|-------|-------|-------|------------|---------|---------|
| Sulfur | S₈ | 10.468 | 12.870 | 24.860 | Fddd | 2.07 | 2.0 |
| Aragonite | CaCO₃ | 4.959 | 7.968 | 5.741 | Pmcn | 2.93 | 3.5 |
| Topaz | Al₂SiO₄F₂ | 4.650 | 8.800 | 8.394 | Pbnm | 3.55 | 8.0 |
| Forsterite | Mg₂SiO₄ | 4.756 | 10.207 | 5.980 | Pnma | 3.21 | 7.0 |
| Barite | BaSO₄ | 7.157 | 8.878 | 5.457 | Pnma | 4.48 | 3.0 |
| Marcasite | FeS₂ | 4.436 | 5.414 | 3.381 | Pnnm | 4.89 | 6.5 |
| Staurolite | Fe₂Al₉Si₄O₂₃(OH) | 7.869 | 16.620 | 5.652 | C2/m* | 3.74 | 7.5 |
| Brookite | TiO₂ | 9.166 | 5.456 | 5.135 | Pbca | 4.13 | 5.5 |
| Enstatite | MgSiO₃ | 18.228 | 8.819 | 5.179 | Pbca | 3.20 | 5.5 |
| Natrolite | Na₂Al₂Si₃O₁₀·2H₂O | 18.320 | 18.630 | 6.600 | Fdd2 | 2.23 | 5.5 |
| Chrysoberyl | BeAl₂O₄ | 5.479 | 9.404 | 4.427 | Pnma | 3.75 | 8.5 |
| Celestite | SrSO₄ | 8.360 | 5.352 | 6.866 | Pnma | 3.96 | 3.0 |
| Anhydrite | CaSO₄ | 6.993 | 6.995 | 6.245 | Amma | 2.96 | 3.5 |
| Sillimanite | Al₂SiO₅ | 7.488 | 7.680 | 5.777 | Pbnm | 3.24 | 7.5 |
| Andalusite | Al₂SiO₅ | 7.800 | 7.898 | 5.557 | Pnnm | 3.15 | 7.5 |

*Staurolite: pseudo-orthorhombic, true symmetry monoclinic C2/m

---

## Al₂SiO₅ Polymorphs (Orthorhombic + Triclinic)

The three aluminum silicate polymorphs — kyanite, andalusite, sillimanite — have
the same composition but different structures reflecting pressure-temperature stability:

| Phase | System | P (kbar) | T (°C) | Density |
|-------|--------|---------|-------|---------|
| Kyanite | Triclinic | >6 | Low | 3.68 g/cm³ |
| Andalusite | Orthorhombic | low P | 400-600 | 3.15 g/cm³ |
| Sillimanite | Orthorhombic | low P | >600 | 3.24 g/cm³ |

---

## Mathematical Formulas

### d-Spacing
```
1/d²_hkl = h²/a² + k²/b² + l²/c²
```

### Unit Cell Volume
```
V = a · b · c
```

### Biaxial Optics (2V angle)
```
cos²(Vz) = (ny² - nx²)(nz² + nx²) / (nz² - nx²)(ny² + nx²)
```
where nx < ny < nz are principal refractive indices (nα < nβ < nγ).

---

## Visual Characteristics

- **Crystal habit:** Tabular, prismatic, acicular, blade-like, platy
- **Orthorhombic bipyramids** have distinct faces at different angles
- **Cleavage:** Defined by specific hkl planes, often prismatic {110} or {010}
- **Optical:** Biaxial — two optic axes (2V), orientation varies by mineral
- **Topaz:** Very good {001} cleavage (basal), prismatic habit
- **Olivine/Forsterite:** Glassy green grains, sugary texture in rock sections
- **Barite:** Heavy tabular crystals, "desert rose" aggregates in clay

---

## AI Art Descriptors

**Sulfur:**
`bright yellow sulfur crystals, dipyramidal habit, resinous to adamantine luster,
volcanic fumarole deposit, sulfurous yellow gem`

**Topaz:**
`imperial topaz crystal, amber-yellow prismatic gem, vitreous luster, orthorhombic prism,
perfect basal cleavage, gem faceting`

**Aragonite:**
`white aragonite sputnik aggregate, acicular crystals radiating, stalactite banding,
blue cave pearl, iridescent nacre`

**Olivine (Forsterite):**
`olive-green peridot crystal, gem olivine, glassy luster, mantle mineral,
green vitreous nodule in basalt`
