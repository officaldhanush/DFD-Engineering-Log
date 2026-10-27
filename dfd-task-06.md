# DFD Study Log 06: iPhone 13 Pro Max (Display & Battery Subassembly Replacement)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** iPhone 13 Pro Max | Display & Battery Subassembly Replacement
> * **DFD Grade:** C+ (Score: 6/10) | **Est. Time:** ~35–45 minutes (Moderate-High)
> * **Core Failure:** Dense perimeter display adhesive and multi-bracket cable shields.
> * **Reference:** [Teardown Visual Reference (iFixit)](./Screenshot_iFixit_iPhone13ProMax.png)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **Minimum Variety:** Pass — Standard Tri-point and micro-Torx screws.
* [x] **Standard Drives:** Pass — Precision driver bits.
* [ ] **Fastener Elimination:** Fail — Continuous perimeter adhesive for display glass.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Heavy adhesive seals.
* [ ] **Thermal / Mechanical Release:** Partial Pass — Requires thermal heating.
* [x] **Material Separation:** Pass — Clean component separation post-unbonding.

### 3. High-Wear Component Access
* [x] **First-Layer Access:** Pass — Screen opens outward first.
* [ ] **Tool-Free Removal:** Fail — Requires heating and opening tools.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — Modular ZIF connectors.
* [ ] **Cable Management:** Partial Pass — Tight sensor ribbon paths.

---

## 4. Manufacturer Intent & Business Context
* **Why Designed It This Way:** Maximum structural strength and IP68 water resistance.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** FaceID sensor array tightly bound to display assembly complicates screen swaps.
* **DFD Redesign Recommendation:** Decouple biometric sensors from the main display module.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** High structural sealing secures data and hardware integrity against intrusion.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Partial Pass — High-value components recoverable, stuck batteries risk puncture.
* **Material Identification & Sorting:** Pass — Separable aluminum and glass elements.
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Continuous perimeter adhesive hinders automated sorting.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PA66< internal brackets, PET shielding films.
* **Thermal Response & Disassembly Friction:** Tg ~85°C; perimeter display adhesive softens at ~80°C.
* **Elastomers & Waterproofing Seals:** Silicone perimeter gasket and port seals.
* **Eco-Compliance & Circularity:** RoHS and REACH compliant, recycled rare earth elements.
