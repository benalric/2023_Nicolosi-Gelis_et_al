
<!-- README.md is generated from README.Rmd. Please edit that file -->

# 2023_Nicolosi-Gelis_STOTEN

## Overview

In this repository, you will find two tutorials explaining how we processed metabarcoding data (rRNA 16S and 23S) to report on the genetic diversity of phytoplankton in four French peri-alpine lakes used in a study aiming to test the relevance of DNA metabarcoding data for biomonitoring.

Data analysis was done using R version 4.2.1. This document was compiled with the rmarkdown package version 2.8. This tutorial is licensed under CC BY-NC-ND 4.0, which means you are free to share, copy and redistribute this tutorial in any medium or format under the terms of attribution of appropriate credit, non-commercial purposes and no derivatives.

The data were produced as part of the article:

>Nicolosi Gelis M.M., A. Canino, A. Bouchez, I. Domaizon, C. Laplace-Treyture, F. Rimet, B. Alric. Assessing the relevance of DNA metabarcoding compared to morphological identification for lake phytoplankton monitoring, submitted to the journal *Science of the Total Environment*.

## Utilization

We can access the script for 16S rRNA analyzes [here](https://raw.githack.com/benalric/2023_Nicolosi-Gelis_STOTEN/main/DADA2_pipeline_phytoplankton_16S.html)
We can access the script for 23S rRNA analyzes [here](https://raw.githack.com/benalric/2023_Nicolosi-Gelis_STOTEN/main/DADA2_pipeline_phytoplankton_23S.html)

## Version of packages used to create the web application
```r
sessionInfo()

R version 4.2.1 (2022-06-23 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19044)

Matrix products: default

locale:
[1] LC_COLLATE=French_France.utf8  LC_CTYPE=French_France.utf8   
[3] LC_MONETARY=French_France.utf8 LC_NUMERIC=C                  
[5] LC_TIME=French_France.utf8    

attached base packages:
[1] stats4    stats     graphics  grDevices utils     datasets  methods  
[8] base     

other attached packages:
 [1] ggplot2_3.4.0               tidyr_1.2.1                
 [3] dplyr_1.0.10                ShortRead_1.56.1           
 [5] GenomicAlignments_1.34.0    SummarizedExperiment_1.28.0
 [7] Biobase_2.58.0              MatrixGenerics_1.10.0      
 [9] matrixStats_0.63.0          Rsamtools_2.14.0           
[11] GenomicRanges_1.50.1        Biostrings_2.66.0          
[13] GenomeInfoDb_1.34.3         XVector_0.38.0             
[15] IRanges_2.32.0              S4Vectors_0.36.0           
[17] BiocParallel_1.32.3         BiocGenerics_0.44.0        
[19] dada2_1.26.0                Rcpp_1.0.9                 
[21] DiagrammeR_1.0.9           

loaded via a namespace (and not attached):
 [1] sass_0.4.4             jsonlite_1.8.3         bslib_0.4.1           
 [4] RcppParallel_5.1.5     latticeExtra_0.6-30    GenomeInfoDbData_1.2.9
 [7] yaml_2.3.6             pillar_1.8.1           lattice_0.20-45       
[10] glue_1.6.2             digest_0.6.30          RColorBrewer_1.1-3    
[13] colorspace_2.0-3       htmltools_0.5.3        Matrix_1.5-3          
[16] plyr_1.8.8             pkgconfig_2.0.3        bookdown_0.30         
[19] zlibbioc_1.44.0        purrr_0.3.5            scales_1.2.1          
[22] jpeg_0.1-10            tibble_3.1.8           generics_0.1.3        
[25] withr_2.5.0            cachem_1.0.6           cli_3.4.1             
[28] magrittr_2.0.3         crayon_1.5.2           deldir_1.0-6          
[31] evaluate_0.18          fansi_1.0.3            hwriter_1.3.2.1       
[34] tools_4.2.1            formatR_1.12           lifecycle_1.0.3       
[37] stringr_1.4.1          interp_1.1-3           munsell_0.5.0         
[40] DelayedArray_0.24.0    compiler_4.2.1         jquerylib_0.1.4       
[43] rlang_1.0.6            grid_4.2.1             RCurl_1.98-1.9        
[46] rstudioapi_0.14        htmlwidgets_1.5.4      visNetwork_2.1.2      
[49] bitops_1.0-7           rmarkdown_2.18         gtable_0.3.1          
[52] codetools_0.2-18       DBI_1.1.3              reshape2_1.4.4        
[55] R6_2.5.1               knitr_1.41             fastmap_1.1.0         
[58] utf8_1.2.2             stringi_1.7.8          parallel_4.2.1        
[61] rmdformats_1.0.4       vctrs_0.5.1            png_0.1-8             
[64] tidyselect_1.2.0       xfun_0.35  
```
