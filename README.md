# diet_guthealth

Project Description: This repository contains code and scripts for analysis on USDA Nutritional Phenotyping Study associations between diet and markers of gastrointestinal inflammation. 
Author = Yasmine Y. Bouzid

## Please CITE
Bouzid YY, Wilson SMG, Alkan Z, Stephensen CB, Lemay DG. Lower Diet Quality Associated with Subclinical Gastrointestinal Inflammation in Healthy U.S. Adults. 

Publication Status: under review

## Table of Contents: 

- Scripts
- Tables
- Figures

**Scripts**

- dfs_here_datawrangle_dietguthealth: descriptions for GI inflammation marker distribution transformations and code to create dataframes
- *0_covariate_checks*: analysis to determinate associations between alcohol intake and physical activity with GI health markers (calprotectin, myeloperoxidase, neopterin, LPS-binding protein) considering inclusion as covariates in regression models (no associations).
- *1a_table1*: table1_perkcal_fiber_dietguthealth.Rmd = regression analysis to determine associations between recent total fiber, habiutal total fiber, and habitual soluble fiber intake with GI inflammation markers. table1_perkcal_fiber_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method.
- *1b_table2*: table2_perkcal_vegfruitsfat_dietguthealth.Rmd = regression analysis to determine associations between vegetable (excluding legumes), legume, total vegetables, total fruit, and saturated fat intake both recently (ASA24) and habitually (FFQ) with GI inflammation markers. table2_perkcal_vegfruitsfat_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method.
- *1c_table3*: table3_indices_dietguthealth.Rmd = regression analysis to determine associations between dietary indices (2015 Healthy Eating Index and Dietary Inflammatory Index) with GI inflammation markers. table3_indices_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method.
- *1d_table4*: table4_perkcal_fiber_dietguthealth.Rmd = regression analysis to determine associations between recent total fiber, habiutal total fiber, and habitual soluble fiber intake with GI inflammation markers in subclinical calprotectin and myeloperoxidase subsets. table4_perkcal_vegfruitsfat_dietguthealth.Rmd = regression analysis to determine associations between vegetable (excluding legumes), legume, total vegetables, total fruit, and saturated fat intake both recently (ASA24) and habitually (FFQ) with GI inflammation markers in subclinical calprotectin and myeloperoxidase subsets. table4_indices_dietguthealth.Rmd = regression analysis to determine associations between dietary indices (2015 Healthy Eating Index and Dietary Inflammatory Index) with GI inflammation markers in subclinical calprotectin and myeloperoxidase subsets. table4_perkcal_fiber_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method in subclinical subset. table4_perkcal_vegfruitsfat_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method in subclinical subset. table4_indices_mtestcorr_dietguthealth.Rmd = extracting p-values from analysis for multiple hypothesis testing correction using Benjamini Hochberg method in subclinical subset.
- *2c_figure3*: figure3_partial_cn_hei_dii_dietguthealth.Rmd = code to create figure showing partial regression plots for significant association between calprotectin and HEI + neopterin and DII 
- *2d_figure4*: figure4_partial_subc_dietguthealth = code to create figure showing partial regression for significant associations between subclincial calprotectin and habitual fiber, legume, and total vegetable intake and recent HEI score
- *3d_multiplehypothcorrection*: multipletestingcorrection_perkcal.Rmd = Benjamini Hochberg false discovery rate p-value correction for multiple hypothesis testing (all dietary compenents). multipletestingcorrection_perkcal_subclinical.Rmd = Benjamini Hochberg false discovery rate p-value correction for multiple hypothesis testing (all dietary compenents for subclinical calprotectin and myeloperoxidase subsets).
- *plots*: plots generated from all analyses

**Tables**

- *Table 1*: Associations between fiber intake and GI health markers
- *Table 2*: Associations between vegetable, legume, fruit, and saturated fat intake and GI health markers
- *Table 3*: Associations between Healthy Eating Index, Dietary Inflammatory Index and GI health markers
- *Table 4*: Associations between all dietary components from tables above and subclinical GI inflammation markers

**Figures**

- *Figure 1*: CONSORT diagram of each GI health marker distribution
- *Figure 2*: Density plots for each GI health marker with red dashes for clinical thresholds of calprotectin and myeloperoxidase
- *Figure 3*: Partial regression plots for significant associations between calprotectin and recent HEI score + neopterin and recent DII score
- *Figure 4*: Partial regression plots for significant associations between subclinical calprotectin and habitual fiber, legume, and total vegetable intake and recent HEI score



