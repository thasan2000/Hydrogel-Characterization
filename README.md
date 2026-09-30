# Biomaterials Laboratory Coursework (BMES 460)

Lab reports from Drexel University's Biomaterials Laboratory course, focused on 
characterizing material properties relevant to drug delivery and implant design.

---

## Lab 1: Solubility of Biomaterials

Investigated the solubility behavior of three biomedically relevant solutes — dextrose, 
bovine serum albumin (BSA), and poly(lactic-co-glycolic acid) (PLGA) — across three 
solvents (deionized water, DMSO, and DCM) to characterize the intermolecular forces 
governing dissolution.

- Designed and executed a controlled solubility matrix experiment, systematically 
  testing 3 solutes × 3 solvents at fixed concentration (3.33 mg/cm³).
- Analyzed results through the lens of intermolecular forces (hydrogen bonding, 
  dipole-dipole interactions, van der Waals forces) to explain observed solubility 
  and insolubility patterns.
- Investigated an exothermic DI water–DMSO reaction and its effect on PLGA 
  precipitation, relevant to controlled drug-release formulation design.
- **Relevance:** Solubility behavior directly informs drug delivery kinetics and 
  polymer-solvent compatibility in biomaterials design.

---

## Lab 2: Modeling to Quantify Hydrogel Viscoelastic Properties

Characterized the viscoelastic behavior of gelatin hydrogels using stress relaxation 
testing and mathematical modeling, to evaluate material behavior relevant to implant 
durability and fatigue resistance.

- Conducted stress relaxation tests on 2% gelatin hydrogels (control vs. 
  glutaraldehyde-crosslinked) using a Bose ElectroForce 3200 mechanical testing instrument.
- Applied and compared two viscoelastic models — the **Maxwell model** and the 
  **Standard Linear Solid (SLS) model** — to quantify time-dependent stress relaxation behavior.
- Performed curve fitting in **MATLAB** to extract model coefficients (spring/dashpot 
  parameters E₁, E₂, η) and evaluated goodness of fit via adjusted R².
- Found the SLS model provided a superior fit for glutaraldehyde-treated hydrogels 
  (Adj. R² = 0.968), while the Maxwell model performed better for untreated controls, 
  demonstrating how crosslinking density alters viscoelastic relaxation behavior.
- **Relevance:** Viscoelastic characterization is critical to predicting the mechanical 
  integrity and long-term performance of implantable hydrogel-based biomaterials.

---

### Tools & Techniques
`MATLAB (curve fitting)` `Mechanical testing (Bose ElectroForce 3200)` 
`Stress relaxation analysis` `Viscoelastic modeling (Maxwell, SLS)` 
`Solubility characterization` `Intermolecular force analysis`
