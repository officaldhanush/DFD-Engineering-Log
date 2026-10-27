# DFD Study Log 11: Google Pixel 7a (Internal Battery Replacement)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** Google Pixel 7a | Internal Battery Replacement
> * **DFD Grade:** D+ (Score: 5/10) | **Est. Time:** ~35–45 minutes (Moderate-High)
> * **Core Failure:** Strong battery adhesive pull tabs prone to snapping, requiring thermal back panel removal.
> * **Reference:** [Teardown Visual Reference (iFixit)](./Screenshot_20261027-071743_iFixit.png)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **Minimum Variety:** Pass — Standard T3 Torx screws throughout internal midframe.
* [x] **Standard Drives:** Pass — Standard Torx drive heads.
* [ ] **Fastener Elimination:** Fail — Relies on perimeter adhesive for thermoformed plastic rear panel.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Battery cell heavily secured using dense PSA.
* [ ] **Thermal / Mechanical Release:** Partial Pass — Includes pull tabs, but high failure rates require IPA solvent.
* [x] **Material Separation:** Pass — Clear separation between plastic rear cover, aluminum frame, and circuits.

### 3. High-Wear Component Access
* [ ] **First-Layer Access:** Fail — Requires back panel removal, midframe unfastening, and wireless coil unseating.
* [ ] **Tool-Free Removal:** Fail — Requires heat pads, opening picks, suction tools, and Torx drivers.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — Detachable board-to-board press connector.
* [ ] **Cable Management:** Partial Pass — Screen flex cable routes across battery well under protective tape.

---

## 4. Manufacturer Intent & Business Context
* **Why Designed It This Way:** Cost-effective IP67 water/dust resistance and structural integrity on a budget build.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** Stretch-release pull tabs frequently tear, forcing technicians to use prying or chemical solvents.
* **DFD Redesign Recommendation:** Implement full-width stretch-release adhesive pull tabs or a reusable metal bracket enclosure.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** Perimeter adhesive seal and hidden midframe fasteners protect internal components from fluid intrusion.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Partial Pass — Battery and logic board can be isolated, but strong adhesives risk component damage.
* **Material Identification & Sorting:** Pass — Plastic back panel and internal composite elements carry clear resin stamps.
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Structural battery PSA tapes and perimeter sealing glues act as recycling contaminants.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PC-GF< (thermoformed back panel), >PA66< internal support frames.
* **Thermal Response & Disassembly Friction:** Tg ~90°C; back cover adhesive softens at 75–80°C via heat pad.
* **Elastomers & Waterproofing Seals:** Silicone perimeter gasket for IP67 water and dust resistance.
* **Eco-Compliance & Circularity:** RoHS and REACH compliant, significant post-consumer recycled plastic content.
