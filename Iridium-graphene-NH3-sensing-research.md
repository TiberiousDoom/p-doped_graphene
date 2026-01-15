# Iridium and Graphene for NH₃ Gas Sensing: A Research Summary

## Document Notes

**This document synthesizes findings from web searches conducted on January 15, 2026. Where information is directly supported by sources, it is noted. Sections marked with [INFERENCE], [KNOWLEDGE GAP], or [RESEARCH OPPORTUNITY] indicate where I have extrapolated beyond the direct source material.**

### Version History

| Version | Date | Changes |
|---------|------|---------|
| v1 | 2026-01-15 | Initial literature synthesis from web searches |

---

## 1. Overview

This document explores the use of **iridium-based materials** (iridium black, iridium oxide) as catalysts for **ammonia (NH₃) sensing**, with particular focus on combinations with **graphene and carbon nanomaterials**.

### Key Findings Summary

- Iridium oxide (IrOx) decorated carbon nanotubes show **6-fold improvement** in NH₃ response vs bare CNTs
- Iridium-graphene composites are well-studied for **electrocatalysis** but underexplored for **gas sensing**
- The IrOx sensing mechanism involves **redox interaction**: Ir(IV) ↔ Ir(III) with NH₃/NO₂
- **Research gap identified**: Direct iridium-graphene composites for NH₃ gas sensing

---

## 2. Iridium Black

### 2.1 Definition and Properties

**Iridium black** is a high specific surface area form of iridium metal, typically produced by chemical reduction of iridium salts. Key properties:

| Property | Value/Description |
|----------|-------------------|
| Appearance | Black powder |
| Surface area | High (exact values vary by preparation) |
| Conductivity | Metallic |
| Stability | Excellent chemical and thermal stability |

### 2.2 Applications (From Johnson Matthey)

According to Johnson Matthey, iridium black is specifically suitable for:
- Electrocatalyst in gas diffusion electrodes
- Electrochemical gas sensors
- Electrolysers

**[INFERENCE]**: The high surface area and catalytic activity of iridium black make it potentially suitable for chemiresistive gas sensors, though most literature focuses on electrochemical applications.

---

## 3. Iridium Oxide for NH₃ Sensing

### 3.1 IrOx-Carbon Nanotube Composite (Key Study)

The most directly relevant research combines iridium oxide nanoparticles with multi-walled carbon nanotubes (MWCNTs).

**Source**: MDPI Sensors, 2019 - "Gas Sensing with Iridium Oxide Nanoparticle Decorated Carbon Nanotubes"

| Parameter | Finding |
|-----------|---------|
| NH₃ response improvement | **6-fold increase** vs bare MWCNTs |
| Optimal temperature | 100°C |
| Humidity dependence | Stable at 50% RH |
| Dual-gas capability | Also detects NO₂ |
| Mechanism | Redox: Ir(IV) + NH₃ → Ir(III) |

**Sensing Mechanism:**
- NH₃ exposure: Ir(IV) is **reduced** to Ir(III)
- NO₂ exposure: Ir(III) is **oxidized** back to Ir(IV)
- This redox cycling provides selectivity and reversibility

**Advantages over bare CNTs:**
- Higher sensitivity
- Better reproducibility
- Improved stability
- Lower noise

### 3.2 Wearable Electrochemical NH₃ Sensor

**Source**: MDPI Sensors, 2021 - "A Wearable Electrochemical Gas Sensor for Ammonia Detection"

| Component | Material |
|-----------|----------|
| Semiconductor | PEDOT (organic) |
| Catalyst | Electrochemically deposited IrOx particles |
| Membrane | Self-healing hydrogel film |
| Operation | Room temperature |

**Key features:**
- Reversible response
- Selective detection
- Optimized hydrogel for humidity stability

---

## 4. Iridium-Graphene Composites

### 4.1 Current Research Focus

Iridium-graphene composites have been studied primarily for **electrocatalysis**, not gas sensing:

| Application | Material | Performance | Source |
|-------------|----------|-------------|--------|
| Nitrogen Reduction (NRR) | Ir nanoparticles on rGO | NH₃ yield: 55.6 μg h⁻¹ mg⁻¹; FE: 15.3% | RSC New J. Chem, 2022 |
| Oxygen Evolution (OER) | rGO/IrO₂/TiO₂ | 240 mV overpotential @ 10 mA/cm²; 50 hr stable | MDPI Molecules, 2025 |
| NH₃ Oxidation | Ir overlayer on Fe-Cr-Al | TOF >70x greater than Ir/γ-Al₂O₃ | ACS Omega, 2020 |

### 4.2 Synergistic Effects

**From Ir/rGO NRR study:**
- rGO provides **electron enrichment** to Ir nanoparticles
- Causes **upshift of d-band center**
- Results in **enhanced N₂ adsorption**
- Outperforms most reported NRR catalysts

**[INFERENCE]**: Similar electron-donating effects from graphene could enhance iridium's sensing properties for NH₃.

### 4.3 IrO₂/rGO for OER

**From MDPI Molecules, 2025:**
- rGO retains intact sp² carbon framework
- Minor oxygen-containing functional groups enhance:
  - Electrical conductivity
  - Hydrophilicity
- Synergistic effect between rGO, IrO₂, and TiO₂ matrix

---

## 5. Graphene-Based NH₃ Sensors (Context)

### 5.1 Why Graphene for Gas Sensing?

| Property | Benefit for Sensing |
|----------|---------------------|
| Large surface area | More adsorption sites |
| High carrier mobility | Fast response |
| 2D structure | Every atom is surface atom |
| Tunable properties | Can be functionalized |

### 5.2 Limitations of Pristine Graphene

- **Non-selective**: Responds to many gases
- **Weak NH₃ binding** at room temperature
- Requires functionalization for practical sensors

### 5.3 Noble Metal Decoration Comparison

| Metal | Graphene Composite | NH₃ Sensing Performance | Source |
|-------|-------------------|------------------------|--------|
| Pt | Pt NPs + GO | 10.2 pm/ppm sensitivity (3x vs pure GO) | ScienceDirect |
| Ag | Ag NPs + rGO | Room temp wireless sensor; synergistic enhancement | Nature Sci. Rep. |
| Pd | Pd + graphene | Enhanced selectivity | Multiple sources |
| **Ir** | IrOx + MWCNTs | 6-fold response increase | MDPI Sensors |
| **Ir** | Ir + graphene | **Not yet studied for NH₃ sensing** | - |

---

## 6. Research Gap and Opportunity

### 6.1 Gap Identified

**Direct iridium-graphene composites for NH₃ gas sensing appear to be unexplored.**

| Material Combination | NH₃ Gas Sensing | Electrocatalysis |
|---------------------|-----------------|------------------|
| IrOx + Carbon Nanotubes | Yes (demonstrated) | - |
| Ir/IrOx + Graphene | **Not found** | Yes (NRR, OER) |
| Other noble metals + Graphene | Yes (Pt, Ag, Pd) | Yes |

### 6.2 Rationale for Ir-Graphene NH₃ Sensors

**[RESEARCH OPPORTUNITY]**: Combining iridium oxide with graphene for NH₃ sensing could leverage:

1. **Proven IrOx sensing mechanism** (Ir(IV)/Ir(III) redox with NH₃)
2. **Graphene's superior properties** vs CNTs:
   - Higher surface area
   - Better conductivity
   - More uniform 2D structure
   - Easier functionalization
3. **Demonstrated synergy** in electrocatalysis applications
4. **Electron donation from graphene** could enhance Ir activity

### 6.3 Potential Synthesis Approaches

Based on related literature:

| Approach | Basis | Potential Method |
|----------|-------|------------------|
| Electrochemical deposition | Wearable sensor work | Deposit IrOx on graphene electrode |
| Sputtering/PVD | IrOx-CNT work | Sputter Ir onto graphene substrate |
| Chemical reduction | Ir/rGO NRR catalyst | Reduce Ir precursor on GO, then reduce GO |
| Microwave-assisted | P-doped graphene methods | Rapid Ir incorporation via microwave |

---

## 7. Iridium in Ammonia Catalysis (Related Context)

### 7.1 NH₃ Oxidation

| Catalyst | Key Finding | Source |
|----------|-------------|--------|
| Ir sponge | More active and selective to N₂ than Pt | ScienceDirect |
| Ir overlayer (12 nm) | <5% N₂O selectivity vs ~70% for Pt at 225°C | ACS Omega, 2020 |
| Ir-W dual-atom | Cascade catalysis: NH₃ → NO → N₂ | Nature Comm., 2025 |

**Mechanism**: Stepwise dehydrogenation of NH₃; rate-determining step is NH + OH → N + H₂O

### 7.2 NH₃ Decomposition

- At 580°C, N-H bond scission is rate-limiting on Ir (also Rh, Pd, Pt, Cu)
- Relevant for hydrogen production from ammonia

### 7.3 Electrochemical NH₃ Synthesis (NRR)

| Catalyst | NH₃ Yield | Faradaic Efficiency | Source |
|----------|-----------|---------------------|--------|
| Ir single-atom | High activity | - | Nano Research, 2023 |
| Ir/rGO | 55.6 μg h⁻¹ mg⁻¹ | 15.3% | RSC, 2022 |

---

## 8. Sources Consulted

### Primary Sources (with links)

| # | Citation | Access | Link |
|---|----------|--------|------|
| 1 | MDPI Sensors, 2019 - "Gas Sensing with Iridium Oxide Nanoparticle Decorated Carbon Nanotubes" | Open Access | [MDPI](https://www.mdpi.com/1424-8220/19/1/113) / [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC6339137/) |
| 2 | MDPI Sensors, 2021 - "A Wearable Electrochemical Gas Sensor for Ammonia Detection" | Open Access | [MDPI](https://www.mdpi.com/1424-8220/21/23/7905) |
| 3 | RSC New J. Chem, 2022 - "Ultrasmall iridium nanoparticles on graphene for efficient nitrogen reduction reaction" | Paywalled | [RSC](https://pubs.rsc.org/en/content/articlelanding/2022/nj/d1nj05843f) |
| 4 | MDPI Molecules, 2025 - "Reduced Graphene Oxide-Coated Iridium Oxide as a Catalyst for OER" | Open Access | [MDPI](https://www.mdpi.com/1420-3049/30/9/2069) |
| 5 | ACS Omega, 2020 - "Nanometric Iridium Overlayer Catalysts for High-Turnover NH₃ Oxidation" | Open Access | [ACS](https://pubs.acs.org/doi/10.1021/acsomega.0c05443) / [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC7758949/) |
| 6 | Nature Communications, 2025 - "Cascade catalysis on dual-atom iridium-tungsten catalysts for enhanced ammonia selective oxidation" | Open Access | [Nature](https://www.nature.com/articles/s41467-025-66144-6) |

### Review Articles on Graphene NH₃ Sensors

| # | Citation | Access | Link |
|---|----------|--------|------|
| 7 | MDPI Sensors, 2021 - "A Review on Functionalized Graphene Sensors for Detection of Ammonia" | Open Access | [MDPI](https://www.mdpi.com/1424-8220/21/4/1443) |
| 8 | PMC, 2022 - "Recent Advances in Graphene-Based Nanocomposites for Ammonia Detection" | Open Access | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9739373/) |
| 9 | Beilstein J. Nanotechnol. - "Graphene-enhanced metal oxide gas sensors at room temperature: a review" | Open Access | [Beilstein](https://www.beilstein-journals.org/bjnano/articles/9/264) |

### Other Noble Metal-Graphene NH₃ Sensors

| # | Citation | Access | Link |
|---|----------|--------|------|
| 10 | ScienceDirect - "Pt nanoparticle decorated GO NH₃ sensor" | Paywalled | [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0925400516320974) |
| 11 | Nature Scientific Reports, 2019 - "Ag-rGO room temperature wireless NH₃ sensor" | Open Access | [Nature](https://www.nature.com/articles/s41598-019-46213-9) |

---

## Summary

### What the literature clearly supports:
- IrOx on carbon nanotubes provides 6x improvement in NH₃ sensing
- The sensing mechanism is Ir(IV)/Ir(III) redox interaction with NH₃
- Ir-graphene composites show excellent performance in electrocatalysis (NRR, OER)
- Graphene enhances Ir activity through electron donation
- Other noble metals (Pt, Ag, Pd) on graphene are effective NH₃ sensors

### Research gap identified:
- **No studies found** on direct Ir/IrOx-graphene composites for NH₃ gas sensing
- This represents a potential research opportunity combining:
  - Proven IrOx NH₃ sensing mechanism
  - Superior properties of graphene vs CNTs
  - Demonstrated Ir-graphene synergy in catalysis

### Recommended next steps:
1. Review IrOx-MWCNT paper in detail for synthesis parameters
2. Explore electrochemical deposition of IrOx on graphene electrodes
3. Consider microwave-assisted synthesis for rapid Ir-graphene composite formation
4. Compare chemiresistive vs electrochemical sensing modes
