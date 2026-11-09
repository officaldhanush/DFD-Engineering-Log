# DFD Study Log 19: Motorola Moto G 5G (2025) (LCD Screen Replacement)

> **Executive Overview & Audit Snapshot**
> * **Device & Goal:** Motorola Moto G 5G (2025) | LCD Screen & Digitizer Assembly Extraction
> * **DFD Grade:** C- (Score: 5.5/10) | **Est. Time:** ~35–45 minutes (Moderate to High Friction)
> * **Core Failure:** Accessing and extracting the front display assembly requires removing the bonded perimeter rear plastic cover, unseating numerous midframe screws, disconnecting the battery flex cable, and applying continuous uniform thermal energy to break down the strong screen frame adhesive.
> * **Reference:** [Teardown Visual Reference (iFixit)](./Screenshot_MotoG5G_Screen.png)

---

## 3. DFD Audit Checklist

### 1. Fasteners & Hardware
* [x] **Minimum Variety:** Pass — Uses uniform standard Phillips #00 screws across the internal midframe and motherboard protection plates.
* [x] **Standard Drives:** Pass — Complete avoidance of proprietary security drives; standard cross-head precision bits suffice.
* [ ] **Fastener Elimination:** Fail — Reliance on heavy peripheral thermal-activated pressure adhesive to retain both the rear plastic cover and the front LCD panel.

### 2. Bonding & Materials
* [ ] **Zero Permanent Glue:** Fail — Dual adhesive layers (outer rear cover gasket tape and perimeter display frame tape) gate internal electronic access.
* [x] **Thermal / Mechanical Release:** Pass — Perimeter acrylic screen adhesive softens predictably at controlled temperatures (~75–80°C) using heat guns or thermal pads.
* [x] **Material Separation:** Pass — Polycarbonate back cover, aluminum internal frame, glass/LCD stack, and Li-ion battery cell can be isolated once unbonded.

### 3. High-Wear Component Access
* [ ] **First-Layer Access:** Fail — Replacing the front screen requires a complete rear-entry teardown: removing the back cover, unfastening the midframe bracket, disconnecting the battery, and routing the display flex ribbon through the chassis mid-chassis slot.
* [ ] **Tool-Free Removal:** Fail — Requires a thermal heat source, suction cup, thin pry picks, plastic spudger, Phillips screwdriver, and isopropyl alcohol for adhesive clean-up.

### 4. Modular Architecture
* [x] **Sub-Assemblies:** Pass — The display assembly connects to the main logic board via a dedicated flex ribbon cable with a standard ZIF flip-lock connector.
* [ ] **Cable Management:** Warning — Display flex cable routes directly underneath the battery well; improper battery extraction poses a tearing hazard to the display ribbon.

---

## 4. Manufacturer Intent & Business Context
* **Why Motorola Designed It This Way:**
  1. **Budget-Conscious Durability:** Utilizing an LCD panel paired with a polycarbonate chassis frame keeps bill-of-materials (BOM) costs low while offering structural drop resistance.
  2. **Basic Environmental Resistance:** Continuous perimeter adhesive strips provide splash and dust resistance without requiring expensive rubberized gasket rings or O-rings.

---

## 5. Engineering Critique & DFD Redesign
* **Main Design Flaw:** Display ribbon routing requires full disassembly of the back cover, midframe, and battery disconnect before replacing the front screen, unnecessarily multiplying labor time and component risk for a frequent repair item.
* **DFD Redesign Recommendation:** Standardize a front-accessible screen module secured by concealed frame micro-screws or quick-release latch channels, allowing screen replacement without disrupting the rear battery compartment.

---

## 6. Product Design & Physical Security Trade-offs
* **Tamper Resistance vs. Disassembly:** Perimeter structural adhesive prevents dust intrusion and provides structural stiffness for the plastic housing, but drastically increases display replacement difficulty and risks thermal deformation of the plastic midframe during removal.

---

## 7. Regulatory & Eco-Compliance Audit
* **WEEE Target Separation:** Partial Pass — LCD matrix and glass sort cleanly from plastic housing once thermal release is achieved, though residual adhesive strips hinder high-speed automated recycling sorting.
* **Material Identification & Sorting:** Pass — Polycarbonate outer shell and internal frame carry clear molded ISO resin indicators (>PC+ABS<).
* **RoHS/REACH Chemical & Bonding Risk:** Warning — Adhesives securing the display frame and battery call for isopropyl alcohol chemical solvents during field servicing.

---

## 8. Material Breakdown & Polymer Selection
* **Primary Resins:** >PC+ABS< (back cover and internal midframe matrix), Aluminosilicate glass (front display cover glass), PET (display flex substrate).
* **Thermal Response & Disassembly Friction:** Glass transition temperature Tg ~110–125°C for PC+ABS chassis; perimeter acrylic adhesive softens at 75–80°C.
* **Elastomers & Waterproofing Seals:** Polyurethane perimeter adhesive foam tape acting as primary liquid splash protection.
* **Eco-Compliance & Circularity:** Compliant with RoHS and REACH standards; high recycling yield for plastics and glass upon manual chemical/thermal separation.
