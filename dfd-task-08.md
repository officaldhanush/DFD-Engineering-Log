# DFD Study Log 08: iPad Pro 11" 4th Gen (M2) (Display & Battery Assembly Teardown)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** iPad Pro 11" 4th Gen (M2) | Display & Battery Assembly Teardown
> * **DFD Grade:** D (Score: 4/10) | **Est. Time:** ~50–60 minutes (High)
> * **Core Failure:** Heavy perimeter display adhesive and high glass fracture risk during lifting.
> * **Reference:** [Teardown Visual Reference (iFixit)](./Screenshot_iFixit_iPadPro11.png)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **MinimumVariety:** Pass — Standard internal Torx fasteners.
* [x] **Standard Drives:** Pass — Standard precision tool bits.
* [ ] **Fastener Elimination:** Fail — Relies entirely on perimeter display adhesive.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Heavy industrial display adhesive.
* [ ] **Thermal / Mechanical Release:** Partial Pass — Requires high thermal blanket application.
* [x] **Material Separation:** Pass — Clean metal enclosure post-unbonding.

### 3. High-Wear Component Access
* [ ] **First-Layer Access:** Fail — Screen removal requires prolonged thermal softening.
* [ ] **Tool-Free Removal:** Fail — Requires thermal heating pads and prying shims.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — Modular board connectors.
* [ ] **Cable Management:** Partial Pass — Delicate FaceID sensor cabling across edges.

---

## 4. Manufacturer Intent & Business Context
* **Why Designed It This Way:** Ultra-thin profile targets sleek aesthetics and rigid structural integrity.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** Glued glass display panel creates extreme breakage risk during routine repair.
* **DFD Redesign Recommendation:** Implement a frame-screwed bezel design to secure the screen assembly.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** Heavy adhesive bonding provides exceptional rigidity and environmental seal protection.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Partial Pass — Display glass and battery extraction carry high fracture risks.
* **Material Identification & Sorting:** Pass — Metal housing and glass elements sort well.
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Extensive perimeter display adhesive introduces high bonding contamination.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PC-GF< internal stiffeners, PET display enhancement films.
* **Thermal Response & Disassembly Friction:** Tg ~90°C; requires perimeter thermal blanket application (80–90°C).
* **Elastomers & Waterproofing Seals:** Silicone perimeter edge gasket.
* **Eco-Compliance & Circularity:** RoHS and REACH aligned, 100% recycled aluminum enclosure.
