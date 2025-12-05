# Homo sapiens malate dehydrogenase 1 (MDH1)

# Uniprot number: P40925
# Variation: Phosphorylated Tyr277 (pY277) and phosphomimetic substitution Y277D


## Description
This repository contains structural models, visualizations, and molecular-dynamics output for unmodified MDH1, phosphorylated Tyr277 (pY277), and the Y277D phosphomimetic variant. The goal is to compare how authentic phosphorylation reshapes the local environment around residue 277 and whether the Y277D substitution reproduces those structural or dynamic effects. Data include interaction maps, structural overlays, RMSF analysis, and pKa calculations.


# Comparison of MDH1 models and phospho modified MDH1

1. **Unmodified Tyr277**  
![Tyr277 forms contacts with Asn275, Trp183, Val299, and Arg309, stabilizing the loop at the entrance of the active-site channel.](images/site_unmodified_y277.png)

   **Wide view:**  
   ![Shows the position of Tyr277 within the MDH1 dimer and how the loop fits into the larger fold.](images/site_unmodified_y277_wide.png)

2. **Phosphorylated Tyr277 (pY277)**  
![Phosphorylation shifts the pocket by drawing in Gly301 and Arg309 while retaining contact with Asn275. Several unmodified interactions disappear, and the loop geometry tightens around the phosphate.](images/site_modified_pY277.png)

   **Wide view:**  
   ![The phosphate produces noticeable repositioning of residues in the nearby β-strand and short helix (300–304), slightly narrowing the entry to the active-site channel.](images/site_modified_pY277_wide.png)

3. **Y277D Mimic**  
![Asp277 is shorter and lacks the aromatic ring. Only Asn275 and Arg309 remain as contacts, leaving the loop more open and less organized.](images/site_mimic_y277d.png)

   **Wide view:**  
   ![The loop around 275–280 appears looser, reflecting the absence of the bulky Tyr side chain and the lack of phosphate-driven electrostatic organization.](images/site_mimic_y277d_wide.png)

4. **Overlay of all three variants**  
![Tyr277, Asp277, and pTyr277 are outlined in red. Phosphotyrosine extends outward and engages new contacts; Asp277 sits lower in the pocket and cannot reach the same residues. This reinforces that Y277D does not reproduce the structure created by phosphorylation.](images/site_compare_p277.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1. **Aligned PDB site comparison (no solvent)**  
![Direct comparison of residue placement highlights differences in sterics and electrostatics across the three states.](images/site_compare_p277.png)

2. **RMSF (line plot)**  
![RMSF values show increased flexibility around residues 270–310 in the Y277D variant. This region includes the substituted site and the helix interacting with Arg309 and Gly301.](images/rmsf_plot_mdh1_pY277.png)

3. **RMSF scatter plot**  
![The mimic displays a wider spread of fluctuations in the same region, supporting that the loop becomes more mobile when Tyr277 is replaced with Asp.](images/rmsf_scatter_plot_mdh1_pY277.png)

4. **pKa plot (titratable residues)**  
![The mimic does not substantially alter pKa values of active-site histidines or other catalytic residues. The effect of Y277D is therefore structural rather than electrostatic.](images/pKa_scatter_plot_mdh1_pY277.png)


**Description of the data and changes**  
Phosphorylation introduces a large negative charge that reorganizes contacts at residue 277 and shifts nearby backbone positions. Y277D cannot reproduce these effects and instead increases loop mobility. MD data confirm this: RMSF values rise specifically around the substituted loop, and pKa values remain unchanged, consistent with a mimic that disrupts packing but does not generate phosphorylation-like electrostatics.


## Comparison of the mimic and the authentic PTM

Structural comparisons show that pY277 and Y277D diverge both in residue contacts and in spatial orientation. Phosphorylation creates a coordinated electrostatic pocket involving Gly301, Arg309, and Asn275, while the mimic collapses to a two-residue contact network. The overlay visualization demonstrates that Asp277 cannot physically reach the same positions as pTyr277. MD results reinforce this: the mimic increases flexibility where phosphorylation appears to stabilize the loop. These differences indicate that Y277D is not an adequate substitute for studying the functional role of Tyr277 phosphorylation.


### Colab notebook links

`Y277D_MD_simulation.ipynb`


## Authors
Noah Canter  
Course: BIOCHEMISTRY 361 – Project 4  


## Deposition Date
December 2025  


## License

Shield:  
[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a  
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/  
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png  
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg  


## References

1. Harms, M. J.; Schlessman, J. L.; Sue, G. R.; Garcia-Moreno, B. E. *PNAS* **2011**, 108, 18954–18959. https://doi.org/10.1073/pnas.1104808108  

2. Dephoure, N.; Gygi, S. P. *Methods* **2011**, 54, 379–386. https://doi.org/10.1016/j.ymeth.2011.03.008  

3. Hammes-Schiffer, S.; Benkovic, S. J. *Annu. Rev. Biochem.* **2006**, 75, 519–541.  

4. Hunter, T.; Sefton, B. M. *PNAS* **1980**, 77, 1311–1315. https://doi.org/10.1073/pnas.77.3.1311  

5. LaNoue, K. F.; Schoolwerth, A. C. *Annu. Rev. Biochem.* **1979**, 48, 871–922.  

6. Minárik, P.; Tomásková, N.; Kollárová, M.; Antalík, M. *Gen. Physiol. Biophys.* **2002**, 21, 257–265.  

7. Navo, C. D.; Jiménez-Osés, G. *ACS Med. Chem. Lett.* **2021**, 12, 1624–1628. https://doi.org/10.1021/acsmedchemlett.1c00435  

8. UniProt: P40925. https://www.uniprot.org/uniprotkb/P40925/entry  

9. Tokuriki, N.; Tawfik, D. S. *Science* **2009**, 324, 203–207. https://doi.org/10.1126/science.1169375  

10. Whittier, S. K.; Hengge, A. C.; Loria, J. P. *Science* **2013**, 341, 899–903. https://doi.org/10.1126/science.1241735  
