# DFD Study Log 07: MacBook Air 13" Late 2020 (M1) (Logic Board & Battery Replacement)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** MacBook Air 13" Late 2020 (M1) | Logic Board & Battery Replacement
> * **DFD Grade:** B (Score: 7.5/10) | **Est. Time:** ~25–35 minutes (Low-Moderate)
> * **Core Failure:** Glued-in battery cells require thermal solvent release agents.
> * **Reference:** [Teardown Visual Reference (iFixit)](Screenshot_20261023-073157_iFixit~2.jpg)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **Minimum Variety:** Pass — Standard Pentalobe P5 and Torx T3 screws.
* [x] **Standard Drives:** Pass — Standard precision tool bits.
* [x] **Fastener Elimination:** Pass — Unibody clip-and-screw architecture.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Battery cells use strong structural adhesive strips.
* [x] **Thermal / Mechanical Release:** Pass — Accessible screw layout for internal shielding.
* [x] **Material Separation:** Pass — Exceptionally clean aluminum unibody separation.

### 3. High-Wear Component Access
* [x] **First-Layer Access:** Pass — Bottom case removes immediately upon unfastening.
* [x] **Tool-Free Removal:** Fail — Requires Pentalobe and Torx drivers.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — Modular IO and logic board planes.
* [x] **Cable Management:** Pass — Well-routed display and keyboard ribbon cables.

---

## 4. Manufacturer Intent & Business Context
* **Why Designed It This Way:** Premium unibody rigidity combined with efficient factory automated assembly.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** Glued battery cells complicate safe removal without chemical solvents.
* **DFD Redesign Recommendation:** Implement mechanical drop-in battery trays with screw retention.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** Clean screw-based internal architecture balances moderate serviceability with structural durability.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Pass — Unibody screw assembly allows systematic removal of core parts.
* **Material Identification & Sorting:** Pass — Aluminum unibody shell sorts easily.
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Glued-in battery cells require thermal release agents.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PC/ABS< (hinge covers), PET insulating sheets.
* **Thermal Response & Disassembly Friction:** Glued battery removal requires controlled thermal pad softening (~60–70°C).
* **Elastomers & Waterproofing Seals:** Low elastomer usage; relies on unibody metal tolerances.
* **Eco-Compliance & Circularity:** RoHS and REACH compliant, 100% recycled aluminum unibody.
