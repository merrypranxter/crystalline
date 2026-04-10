# 07 — Triclinic Crystal System

## Overview

The **triclinic** system is the least symmetric of all seven crystal systems.
All three axes have different lengths, and none of the three interaxial angles
are equal to 90°. There are no required angular relationships whatsoever.

Despite having minimal symmetry, triclinic minerals include the
**plagioclase feldspars** — the most abundant minerals in the Earth's crust.

---

## Lattice Parameters

| Parameter | Constraint |
|-----------|-----------|
| a | free |
| b | free (≠ a) |
| c | free (≠ a, ≠ b) |
| α | free (≠ 90°) |
| β | free (≠ 90°) |
| γ | free (≠ 90°) |

**Degrees of freedom:** 6 (all six parameters independent)

---

## Bravais Lattice

Only **one** Bravais lattice exists for triclinic:
**aP** — Primitive triclinic (also written tric)

There can be no centering in the triclinic system — any centered lattice can always be
reduced to a primitive triclinic lattice by choosing a different unit cell.

---

## Point Groups

| H-M Symbol | Schönflies | Order | Type | Piezoelectric |
|-----------|-----------|-------|------|--------------|
| 1 | C₁ | 1 | Pedial (no symmetry) | Yes |
| 1̄ | Cᵢ | 2 | Pinacoidal (inversion only) | No |

**P1 (No. 1):** Chiral, only a 1-fold rotation (trivial identity). Very rare for minerals.
**P1̄ (No. 2):** Contains only an inversion center. By far the most common triclinic SG.

---

## Space Groups

Only **2** space groups exist for triclinic:
| No. | Symbol | Description |
|-----|--------|-------------|
| 1 | P1 | Primitive, no symmetry |
| 2 | P1̄ | Primitive with inversion center |

Despite having only 2 space groups, the triclinic system encompasses an enormous range of
structures because the 6 independent lattice parameters allow vast geometric flexibility.

---

## Crystal Examples

| Mineral | Formula | a | b | c | α (°) | β (°) | γ (°) | Density |
|---------|---------|---|---|---|-------|-------|-------|---------|
| Albite | NaAlSi₃O₈ | 8.144 | 12.787 | 7.160 | 94.33 | 116.57 | 87.65 | 2.63 |
| Anorthite | CaAl₂Si₂O₈ | 8.177 | 12.877 | 14.169 | 93.17 | 115.85 | 91.22 | 2.76 |
| Kyanite | Al₂SiO₅ | 7.122 | 7.848 | 5.574 | 89.99 | 101.11 | 106.03 | 3.68 |
| Turquoise | CuAl₆(PO₄)₄(OH)₈·4H₂O | 7.424 | 7.629 | 9.910 | 68.61 | 69.71 | 65.06 | 2.84 |
| Rhodonite | MnSiO₃ | 7.682 | 11.818 | 6.707 | 111.97 | 86.53 | 94.28 | 3.57 |
| Axinite | Ca₂(Fe,Mn)Al₂BSi₄O₁₅(OH) | 7.145 | 9.204 | 8.958 | 88.08 | 84.42 | 77.31 | 3.31 |
| Amblygonite | LiAlPO₄F | 5.187 | 7.119 | 5.047 | 112.03 | 97.82 | 68.13 | 3.11 |
| Wollastonite | CaSiO₃ | 7.926 | 7.320 | 7.065 | 90.03 | 95.37 | 103.43 | 2.91 |
| Chalcanthite | CuSO₄·5H₂O | 6.109 | 10.674 | 5.983 | 97.57 | 107.28 | 77.55 | 2.28 |
| Microcline | KAlSi₃O₈ | 8.590 | 12.964 | 7.222 | 90.65 | 115.93 | 87.68 | 2.56 |

All above in space group P1̄ (No. 2) unless otherwise noted. Lattice constants in Ångströms.

---

## The Feldspar Group

Feldspars constitute ~60% of Earth's crust and include both monoclinic and triclinic members:

| Feldspar | System | Composition | Note |
|----------|--------|-------------|------|
| Sanidine | Monoclinic C2/m | K-rich | High-T form |
| Orthoclase | Monoclinic C2/m | KAlSi₃O₈ | Common K-feldspar |
| Microcline | Triclinic P1̄ | KAlSi₃O₈ | Low-T K-feldspar |
| Albite | Triclinic P1̄ | NaAlSi₃O₈ | Na end-member |
| Oligoclase | Triclinic P1̄ | Ab70An30 | Plagioclase |
| Andesine | Triclinic P1̄ | Ab50An50 | Plagioclase |
| Labradorite | Triclinic P1̄ | Ab30An70 | Labradorescence |
| Bytownite | Triclinic P1̄ | Ab10An90 | Plagioclase |
| Anorthite | Triclinic P1̄ | CaAl₂Si₂O₈ | Ca end-member |

---

## Mathematical Formulas

### Unit Cell Volume (general triclinic)
```
V = a·b·c · sqrt(1 − cos²α − cos²β − cos²γ + 2·cosα·cosβ·cosγ)
```

### d-Spacing (triclinic — general metric tensor)
```
1/d²_hkl = (1/V²) · [S₁₁h² + S₂₂k² + S₃₃l²
             + 2S₁₂hk + 2S₂₃kl + 2S₁₃hl]
```
where:
```
S₁₁ = b²c²sin²α
S₂₂ = a²c²sin²β
S₃₃ = a²b²sin²γ
S₁₂ = abc²(cosα·cosβ − cosγ)
S₂₃ = a²bc(cosβ·cosγ − cosα)
S₁₃ = ab²c(cosγ·cosα − cosβ)
```

### Metric Tensor
```
G = | a²     ab·cosγ  ac·cosβ |
    | ab·cosγ  b²     bc·cosα |
    | ac·cosβ  bc·cosα   c²   |
```

### Reciprocal Cell Parameters
```
a* = bc·sinα / V
b* = ac·sinβ / V
c* = ab·sinγ / V
cosα* = (cosβ·cosγ − cosα)/(sinβ·sinγ)
cosβ* = (cosα·cosγ − cosβ)/(sinα·sinγ)
cosγ* = (cosα·cosβ − cosγ)/(sinα·sinβ)
```

---

## Reduced Cell

The **Niggli cell** (reduced cell) provides a canonical, unique description of any
triclinic lattice. Reduction algorithms (Niggli, Delaunay/selling) transform any
arbitrary triclinic cell to a standardized form for comparison and database searching.

Three conditions for Niggli reduction:
1. |A| ≤ |B| ≤ |C|  (A = a², B = b², C = c²)
2. |ξ| ≤ B, |η| ≤ A, |ζ| ≤ A  (ξ = 2bc·cosα, etc.)
3. All off-diagonal elements same sign, or all negative

---

## Visual Characteristics

- **Crystal habit:** Tabular, prismatic, no required morphological symmetry
- **Plagioclase:** Polysynthetic twins (albite law) visible as striations on {010}
- **Kyanite:** Distinctive blade-like crystals with hardness anisotropy (H=4.5 // to c; H=7 ⊥ to c)
- **Turquoise:** Massive, nodular, rarely well-formed crystals; waxy luster
- **Rhodonite:** Rose-pink to red with black manganese oxide veinlets
- **Microcline:** Perthitic texture (alternating K and Na feldspar lamellae)

---

## AI Art Descriptors

**Feldspar/Labradorite:**
`labradorite schiller effect, peacock blue-green iridescence, spectrolite flash,
polysynthetic twinning, dark base stone, supernatural glow`

**Kyanite:**
`blue kyanite blade crystal, anisotropic mineral, sapphire-blue elongated crystal,
fibrous bladed habit, Swiss Alps mineral`

**Turquoise:**
`sky-blue turquoise matrix, waxy luster, copper mineral, Native American gem,
blue-green veining, desert mineral`

**Rhodonite:**
`rose-pink rhodonite, black manganese veins, manganese silicate gem,
raspberry-pink mineral, carved gemstone cabochon`

**Chalcanthite:**
`vivid electric blue chalcanthite crystals, copper sulfate pentahydrate,
triclinic tabular crystals, brilliant blue color, water-soluble mineral`
