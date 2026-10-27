# DFD Study Log 09: Nintendo Switch 2 (Console Shell & Battery Extraction)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** Nintendo Switch 2 | Console Shell & Battery Extraction
> * **DFD Grade:** B (Score: 7.5/10) | **Est. Time:** ~35–45 minutes (Moderate)
> * **Core Failure:** Mixed-drive fastener matrix combined with adhesive-anchored internal battery cells.
> * **Reference:** [Teardown Visual Reference (iFixit)](Screenshot_20261025-072216_iFixit.png)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **Minimum Variety:** Pass — Standardized internal screw layout.
* [x] **Standard Drives:** Pass — Standard Y-wing and Phillips driver compatibility.
* [ ] **Fastener Elimination:** Fail — Housing shells rely on snap-clips and perimeter screws.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Battery secured with strong PSA strips.
* [ ] **Thermal / Mechanical Release:** Partial Pass — Screws ease entry, but battery requires solvent.
* [x] **Material Separation:** Pass — Clean separation of housing shells and internal frame.

### 3. High-Wear Component Access
* [x] **First-Layer Access:** Pass — Rear shell unfastens easily.
* [ ] **Tool-Free Removal:** Fail — Requires specialized screwdriver bits.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — Modular rail connectors and card readers.
* [x] **Cable Management:** Pass — Clean internal ribbon routing.

---

## 4. Manufacturer Intent & Business Context
* **Why Designed It This Way:** Balances handheld drop durability with modular serviceability for high-wear components.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** Battery adhesive lacks easy pull tabs, risking puncture during extraction.
* **DFD Redesign Recommendation:** Integrate stretch-release pull tabs for tool-free battery removal.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** Standard screw drives offer moderate accessibility while maintaining secure casing interlocks.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Partial Pass — Mainboard and shell separate cleanly, battery requires solvent release.
* **Material Identification & Sorting:** Pass — Plastic housing features molded ISO resin codes.
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Structural battery PSA adhesive increases recycling contamination risk.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PC+ABS< (console housing), >PA66< (rail brackets), POM (sliders).
* **Thermal Response & Disassembly Friction:** Tg ~110°C; snap-fit primary assembly with localized thermal release.
* **Elastomers & Waterproofing Seals:** Silicone port gaskets and dust seals.
* **Eco-Compliance & Circularity:** RoHS and REACH compliant, molded ISO recycling codes.
