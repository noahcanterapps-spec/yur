# README_human_mdh1_pY277

# Species and enzyme  
**Homo sapiens malate dehydrogenase 1 (MDH1)**  

# Uniprot number  
**P40925**

# Variation  
**Phosphorylated Tyr277 (pY277) and phosphomimetic substitution Y277D**

---

## Description  
This project analyzes how post-translational phosphorylation at Tyr277 and the Y277D phosphomimetic substitution affect the structure and predicted function of human MDH1. MDH1 plays a central role in the malate–aspartate shuttle, where subtle loop motions near the active-site cleft regulate substrate access and catalytic timing. Tyr277 sits on a short loop adjacent to this region, making it a plausible regulatory position even though it is not a documented PTM site. Structural modeling, weak-interaction mapping, and MD simulations were used to compare the unmodified, phosphorylated, and mimic states.

---

## Summary of structures and how structures were generated  
All models were generated in **IntelliFold** with the **homodimer assembly** enabled.  

- **Unmodified model:** Direct IntelliFold prediction of the MDH1 dimer.  
- **Phosphorylated model:** Tyr277 modified to phosphotyrosine (PTR277) using the PTM editor.  
- **Mimic model:** Tyr277 mutated to Asp277 (Y277D).  

Weak-interaction maps were used to identify residue contacts for each model.  
The Y277D mimic was further analyzed using MD simulations (Project 2 Colab), generating RMSF and pKa profiles.

---

## Summary of findings  

### Structural outcomes  
- **Unmodified Tyr277** interacts with Asn275, Trp183, Val299, and Arg309.  
- **Phosphorylation (pY277)** adds bulk and negative charge, pulling Gly301 and Arg309 into the pocket and shifting local loop geometry.  
- **Y277D** cannot reproduce these effects. The smaller side chain removes aromatic packing and loosens the loop.

### Functional implications  
- **pY277** likely stabilizes a shifted loop conformation that could regulate substrate access.  
- **Y277D** increases flexibility instead of creating a structured electrostatic environment, meaning it does not function as a true mimic.

### MD simulation outcomes  
- RMSF shows **elevated motion** between residues 270–310.  
- pKa values show **no meaningful changes** in catalytic histidines.  
- The mimic’s effects are primarily structural and dynamic rather than altering protonation equilibria.

---

## Mutation and PTM in context  
Tyr277 sits near the entrance of the active-site cleft where loop movements gate substrate access. Disrupting packing or altering charge distribution at this position is predicted to influence catalytic timing and oxaloacetate positioning.

---

## Comparison with wild-type  
Relative to WT:  
- **pY277** reorganizes the loop and surrounding residues without disturbing global folding.  
- **Y277D** destabilizes the region by removing aromatic bulk and shortening the side chain.  
The mimic diverges from both WT and phosphorylated forms.

---

## Local structure changes  

### Unmodified  
**Figure 1.** `site_unmodified_y277.png`  
**Figure 2.** `site_unmodified_y277_wide.png`

### Phosphorylated  
**Figure 3.** `site_modified_pY277.png`  
**Figure 4.** `site_modified_pY277_wide.png`

### Mimic  
**Figure 5.** `site_mimic_y277d.png`  
**Figure 6.** `site_mimic_y277d_wide.png`

### Structural overlay  
**Figure 7.** `site_compare_p277.png`

---

## Change in dynamics (MD results)

### RMSF  
**Figure 8.** `rmsf_plot_mdh1_pY277.png`  
**Figure 9.** `rmsf_scatter_plot_mdh1_pY277.png`

### pKa  
**Figure 10.** `pKa_scatter_plot_mdh1_pY277.png`

MD simulations show increased flexibility around the 270–310 region in the mimic variant.  
pKa values remain stable across frames, indicating no major electrostatic disruption at catalytic residues.

---

## Substrate-specific parameters or results  
No substrate docking was performed; interpretation focuses on structural elements that influence oxaloacetate access and catalytic loop closure. Changes observed near Tyr277 are consistent with modified catalytic timing or destabilized substrate positioning.

---

## Any other important results  
- Y277D is **not** a reliable approximation of phosphotyrosine at this position.  
- Phosphorylation produces targeted electrostatic remodeling; the mimic produces general destabilization.  
- Loop dynamics increase in the mimic, contrasting with the organized structural changes in the phosphorylated model.

---

## Supporting material  

All figures included:

