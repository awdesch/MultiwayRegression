# MultiwayClassification

This is an R package to perform linear classification for data with multi-way structure.  The distance-weighted discrimination (DWD) or support vector machine (SVM) classification objectives are optimized under the assumption that the multi-way coefficients have low rank. 
This package depends on the packages `DWD` (for DWD) and `kernlab` (for SVM). `DWD` is not currently available on CRAN, and so will need to be installed via its url:
```
install.packages("https://cran.r-project.org/src/contrib/Archive/DWD/DWD_0.11.tar.gz",repos = NULL, type = "source")
```
The `MultiwayClassification` package can then be installed, directly from GitHub, using the devtools library:

```
install.packages(devtools)
library(devtools)
install_github("lockEF/MultiwayClassification")
``` 

This methodolgy was developed in collaboration with Tianmeng Lyu and Lynn E. Eberly. Code for this package was primarily written by Tianmeng Lyu.     