# Homo sapiens malate dehydrogenase 1 (MDH1)

# Uniprot number: P40925
# Variation: Phosphorylated Tyr277 (pY277) and phosphomimetic substitution Y277D


## Description
This repository contains modeled structures, molecular dynamics output, and analysis for unmodified MDH1, phosphorylated Tyr277, and the Y277D phosphomimetic variant. Data include weak-interaction maps, structural overlays, RMSF analyses, and pKa predictions that together evaluate whether Y277D accurately mimics phosphotyrosine at this position.


# Models of human-modified MDH proteins

1. **Image of the unmodified site**  
![Unmodified site](images/site_unmodified_y277.png)

   **Wide view:**  
   ![Unmodified wide](images/site_unmodified_y277_wide.png)

2. **Image of modification site**  
![Modified site](images/site_modified_pY277.png)

   **Wide view:**  
   ![Modified wide](images/site_modified_pY277_wide.png)

3. **Image of mimic site**  
![Mimic site](images/site_mimic_y277d.png)

   **Wide view:**  
   ![Mimic wide](images/site_mimic_y277d_wide.png)

4. **Superimposed comparison of all three variants**  
![Superimposed structures](images/site_compare_p277.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1. **Image of aligned PDB files (no solvent)**  
*(Provided as superimposed variants)*  
![Aligned variants](images/site_compare_p277.png)

2. **Image of the site with the aligned PDB files (no solvent)**  
*(Close-up of the same overlay)*  
![Aligned site view](images/site_compare_p277.png)

3. **Annotated RMSF plot showing differences between simulations**  
![RMSF line plot](images/rmsf_plot_mdh1_pY277.png)

4. **Annotated RMSF scatter plot**  
![RMSF scatter](images/rmsf_scatter_plot_mdh1_pY277.png)

5. **Annotated pKa plot for titratable residues**  
![pKa plot](images/pKa_scatter_plot_mdh1_pY277.png)


**Description of the data and changes**  
(See full written report for integrated structural and MD interpretation.)


## Comparison of the mimic and the authentic PTM

Part 4 from the Project 4 report outline

The comparison uses:

- Unmodified Tyr277  
  ![Unmodified](images/site_unmodified_y277.png)

- Phosphorylated Tyr277  
  ![Modified](images/site_modified_pY277.png)

- Y277D mimic  
  ![Mimic](images/site_mimic_y277d.png)

- Structural overlay  
  ![Overlay](images/site_compare_p277.png)

See main report text for full structural and functional comparison.


### Colab notebook links

`MDH1_Y277D_MD_simulation.ipynb`  
`MDH1_Y277D_pKa_analysis.ipynb`  


## Authors
Noah Canter  
Course: BIOCHEMISTRY 452 – Project 4  


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
