# 04 — Trigonal (Rhombohedral) Crystal System

## Overview

The **trigonal** system is characterized by a single 3-fold (or 3̄-fold) rotation axis.
It is often considered a subset of the hexagonal system because trigonal crystals
frequently use hexagonal axes for description. However, it has its own distinct Bravais
lattice — the **rhombohedral** (R) lattice.

---

## Lattice Parameters

### Hexagonal Setting (most common)
| Parameter | Constraint |
|-----------|-----------|
| a = b | free |
| c | free (≠ a) |
| α = β | = 90° |
| γ | = 120° |

### Rhombohedral Setting
| Parameter | Constraint |
|-----------|-----------|
| a = b = c | free |
| α = β = γ | free (≠ 90°, typically 50–65°) |

**Conversion (hex → rhomb):**
```
a_R = (1/3)√(3a_H² + c_H²)
cos(α_R) = (2c_H² − 3a_H²)/(2c_H² + 6a_H²) · (using obverse setting)
```

---

## Bravais Lattices

| Symbol | Name | Notes |
|--------|------|-------|
| hP | Primitive hexagonal | P-lattice trigonal SG 143–146, 149–155, 157–159, 162–163 |
| hR | Rhombohedral | R-lattice SG 146, 148, 155, 160–161, 166–167 |

The R lattice has the transformation matrix between hexagonal and rhombohedral settings:
```
Obverse:  a_H = a_R - b_R;  b_H = b_R - c_R;  c_H = a_R + b_R + c_R
Reverse:  a_H = -a_R + b_R;  b_H = -b_R + c_R;  c_H = a_R + b_R + c_R
```

---

## Point Groups

| H-M Symbol | Schönflies | Order | Type | Piezoelectric |
|-----------|-----------|-------|------|--------------|
| 3 | C₃ | 3 | Trigonal pyramidal | Yes |
| 3̄ | C₃ᵢ (S₆) | 6 | Rhombohedral | No |
| 32 | D₃ | 6 | Trigonal trapezoidal | Yes |
| 3m | C₃v | 6 | Ditrigonal pyramidal | Yes |
| 3̄m | D₃d | 12 | Ditrigonal scalenohedral (holohedric) | No |

---

## Space Groups (143–167)

**143–146: Point group 3**
P3 (143), P3₁ (144), P3₂ (145), R3 (146)

**147–148: Point group 3̄**
P3̄ (147), **R3̄ (148)** — dolomite, ilmenite, bismuth, antimony

**149–155: Point group 32**
P312 (149), P321 (150), **P3₁12 (151)**, **P3₁21 (152)** — left-quartz,
P3₂12 (153), **P3₂21 (154)** — right-quartz, R32 (155) — cinnabar

**156–161: Point group 3m**
P3m1 (156), P31m (157), P3c1 (158), P31c (159), **R3m (160)** — proustite,
**R3c (161)**

**162–167: Point group 3̄m**
P3̄1m (162), P3̄1c (163), **P3̄m1 (164)** — brucite,
P3̄c1 (165), **R3̄m (166)** — antimony, bismuth, dioptase,
**R3̄c (167)** — calcite, corundum, hematite, tourmaline (schorl is R3m)

---

## Crystal Examples

| Mineral | Formula | a (Å) | c (Å) | Space Group | Density | Hardness |
|---------|---------|-------|-------|------------|---------|---------|
| Calcite | CaCO₃ | 4.989 | 17.062 | R3̄c | 2.71 | 3.0 |
| Corundum | Al₂O₃ | 4.759 | 12.991 | R3̄c | 3.99 | 9.0 |
| Hematite | Fe₂O₃ | 5.038 | 13.772 | R3̄c | 5.26 | 6.0 |
| Tourmaline | NaFe₃Al₆(BO₃)₃Si₆O₁₈(OH)₄ | 15.98 | 7.19 | R3m | 3.25 | 7.0 |
| Dolomite | CaMg(CO₃)₂ | 4.807 | 16.010 | R3̄ | 2.85 | 3.5 |
| Ilmenite | FeTiO₃ | 5.088 | 14.093 | R3̄ | 4.72 | 5.5 |
| Bismuth | Bi | 4.547 | 11.862 | R3̄m | 9.79 | 2.25 |
| Siderite | FeCO₃ | 4.688 | 15.373 | R3̄c | 3.96 | 3.75 |
| Rhodochrosite | MnCO₃ | 4.777 | 15.673 | R3̄c | 3.70 | 3.75 |
| Smithsonite | ZnCO₃ | 4.653 | 15.025 | R3̄c | 4.43 | 4.0 |
| Magnesite | MgCO₃ | 4.633 | 15.016 | R3̄c | 3.01 | 4.0 |
| Antimony | Sb | 4.307 | 11.273 | R3̄m | 6.69 | 3.0 |
| Cinnabar | HgS | 4.149 | 9.495 | P3₁21 | 8.18 | 2.5 |
| Proustite | Ag₃AsS₃ | 10.816 | 8.696 | R3c | 5.57 | 2.5 |
| Quartz (α) | SiO₂ | 4.913 | 5.405 | P3₁21/P3₂21 | 2.65 | 7.0 |

---

## Calcite vs Aragonite Polymorphism

Calcite (trigonal R3̄c) and aragonite (orthorhombic Pmcn) are both CaCO₃ but:
- Calcite stable at ambient P/T; aragonite stable at higher pressure
- Calcite has extreme birefringence (δ = 0.172, one of highest known)
- Double-refraction effect visible with naked eye through calcite cleavage rhombs
- Transformation: calcite → aragonite at ~3 kbar at room temperature

---

## Mathematical Formulas

### Birefringence (calcite example)
```
δ = |ne - no| = |1.486 - 1.658| = 0.172
Retardation = δ · t  (t = thickness)
Interference color from Michel-Levy chart
```

### d-Spacing (hexagonal setting, trigonal)
```
1/d²_hkl = (4/3)(h² + hk + k²)/a² + l²/c²
```
(Same as hexagonal — same metric)

### Rhombohedral d-Spacing
```
1/d²_hkl = [(h²+k²+l²)sin²α + 2(hk+hl+kl)(cos²α-cosα)] / [a²(1-3cos²α+2cos³α)]
```

---

## Visual Characteristics

- **Crystal habit:** Rhombohedra, scalenohedra, prisms, bipyramids
- **Calcite habits:** Dogtooth spar (scalenohedral), nail-head spar (rhombohedral), Iceland spar (cleavage rhombs)
- **Corundum habit:** Barrel-shaped prismatic crystals, tablular, flat rhombohedral
- **Tourmaline habit:** Elongated trigonal prisms with striated faces, hemimorphic (pyroelectric)
- **Quartz habit:** Six-sided prism capped by rhombohedral faces; handedness visible from etch figures
- **Cleavage:** Calcite — perfect rhombohedral {101̄4}; corundum — none; hematite — none, parting on {0001}

---

## AI Art Descriptors

**Calcite/Iceland Spar:**
`calcite rhombohedron, perfect cleavage faces, double refraction, birefringent crystal,
ghost image visible through clear mineral, optical illusion`

**Corundum/Ruby/Sapphire:**
`deep red ruby hexagonal barrel crystal, asterism star effect, corundum prism,
silk inclusions, precious gem, brilliant cut`

**Hematite:**
`silver-grey metallic hematite, kidney ore botryoidal, red streak, steely luster,
specular metallic sheen, iron oxide`

**Tourmaline:**
`black schorl tourmaline prism, trigonal cross-section, striated faces,
color zoning, watermelon pink-green tourmaline, gem crystal`
