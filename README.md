# **Enhancing motivation to learn about the ocean through VR underwater field skills in a Higher Education setting**

**This repository contains code and data presented in the article**:
  
Keith, S.A., Jeannot, L.-L., McKinley, E., Fauville, G. & Woolsey, E.S. Enhancing motivation to learn about the ocean through VR underwater field skills in a Higher Education setting.


## 1. How to download this project?

On the project main page on Anonymous GitHub, click on the button `Download Repository` and then extract the ZIP folder.



## 2. Description of the project

### 2.1 Project organization

This project is organized in 2 folders:
  
* :file_folder:	`data` folder contains 1 dataset (see **2.2 Datasets description**).
* :file_folder:	`figures` folder contains 4 figures.


### 2.2 Dataset description

The dataset correspond to responses collected from a questionnaire filled out by Lancaster University undergraduate students. 
The dataset contains the following variables:
- `Participant` Participant ID (anonymous)
- `Group` Group ID 
- `Q1` - `Q8` Response on a scale of 1-10

### 2.3 Code description

The _VR_HE.Rmd_ code is formatted in Rmarkdown and contains all R-based analyses and code to reproduce data and figures from the paper. It is divided into five sections:

* Data exploration
* 1. Positive effect
* 2. Treatment effect
* 3. Predictors
* 4. CGI acceptance

### 2.4 Figures

All figures are available in PNG and PDF format in the `figures` folder and can be reproduced by running the script. 

## 3. Reproducibility parameters

R version 4.3.2 (2023-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default

locale:
[1] LC_COLLATE=English_United Kingdom.utf8  LC_CTYPE=English_United Kingdom.utf8    LC_MONETARY=English_United Kingdom.utf8 LC_NUMERIC=C                            LC_TIME=English_United Kingdom.utf8    

time zone: Europe/London
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] ggpattern_1.1.4 ggpubr_0.6.0    ggridges_0.5.6  brms_2.22.0     Rcpp_1.0.12     lubridate_1.9.3 forcats_1.0.0   stringr_1.5.1   dplyr_1.1.3     purrr_1.0.2     readr_2.1.5     tidyr_1.3.0    
[13] tibble_3.2.1    ggplot2_3.5.1   tidyverse_2.0.0 modelr_0.1.11   tidybayes_3.0.6

loaded via a namespace (and not attached):
  [1] DBI_1.2.2            gridExtra_2.3        inline_0.3.19        sandwich_3.1-0       rlang_1.1.5          magrittr_2.0.3       multcomp_1.4-25      e1071_1.7-14         matrixStats_1.3.0   
 [10] compiler_4.3.2       loo_2.8.0            systemfonts_1.1.0    vctrs_0.6.4          reshape2_1.4.4       pkgconfig_2.0.3      arrayhelpers_1.1-0   fastmap_1.1.1        backports_1.4.1     
 [19] labeling_0.4.3       utf8_1.2.4           rmarkdown_2.26       tzdb_0.4.0           ragg_1.3.0           xfun_0.43            cachem_1.0.8         jsonlite_1.8.8       broom_1.0.5         
 [28] parallel_4.3.2       R6_2.5.1             stringi_1.7.12       StanHeaders_2.32.7   car_3.1-2            estimability_1.5     rstan_2.32.6         knitr_1.46           zoo_1.8-12          
 [37] bayesplot_1.11.1     Matrix_1.6-1.1       splines_4.3.2        timechange_0.3.0     tidyselect_1.2.1     rstudioapi_0.16.0    abind_1.4-5          yaml_2.3.8           codetools_0.2-20    
 [46] curl_5.1.0           pkgbuild_1.4.4       lattice_0.22-6       plyr_1.8.9           withr_3.0.0          bridgesampling_1.1-2 posterior_1.6.0      coda_0.19-4.1        evaluate_0.23       
 [55] sf_1.0-19            survival_3.6-4       units_0.8-5          proxy_0.4-27         RcppParallel_5.1.7   ggdist_3.3.2         pillar_1.9.0         carData_3.0-5        tensorA_0.36.2.1    
 [64] KernSmooth_2.23-22   checkmate_2.3.1      stats4_4.3.2         distributional_0.4.0 generics_0.1.3       hms_1.1.3            rstantools_2.4.0     munsell_0.5.1        scales_1.3.0        
 [73] xtable_1.8-4         class_7.3-22         glue_1.6.2           emmeans_1.10.1       tools_4.3.2          gridpattern_1.3.1    ggsignif_0.6.4       mvtnorm_1.2-4        cowplot_1.1.3       
 [82] grid_4.3.2           QuickJSR_1.1.3       colorspace_2.1-0     nlme_3.1-164         cli_3.6.1            textshaping_0.4.0    fansi_1.0.5          svUnit_1.0.6         viridisLite_0.4.2   
 [91] Brobdingnag_1.2-9    V8_4.4.2             gtable_0.3.5         rstatix_0.7.2        digest_0.6.33        classInt_0.4-10      TH.data_1.1-2        farver_2.1.1         memoise_2.0.1       
[100] htmltools_0.5.8.1    lifecycle_1.0.4      MASS_7.3-60         

