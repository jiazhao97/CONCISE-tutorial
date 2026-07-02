---
layout: full
homepage: true
disable_anchors: true
description: Spatial co-expression and cell-cell communication inference from spatially resolved transcriptomics
---
## CONCISE Overview
![method\_pipeline](overview.jpg)

We developed `CONCISE` for spatial co-expression and cell-cell communication inference from spatially resolved transcriptomics.

CONCISE models intrinsic features of ST count data, including spatial autocorrelation, heterogeneous total molecular counts and measurement errors, all of which can lead to spurious results if ignored. By jointly accounting for these sources of confounding, CONCISE enables reliable inference with calibrated false-positive control and higher detection power. With efficient moment-based parameter estimation and analytically derived hypothesis testing, CONCISE avoids computationally intensive permutation procedures and restrictive distributional assumptions, achieving rigorous inference while maintaining high robustness and computational efficiency.

Extensive real-data permutation and biologically motivated negative-control studies have demonstrated its reliablility. Applications of CONCISE have uncovered distinct communication patterns between inflammation-associated fibroblasts and normal fibroblasts during intestinal inflammation, and elucidated complex tumor-immune and tumor-stromal signaling networks within the tumor microenvironment.

Installation
------------
You can install CONCISE from Github with the following code ([link](https://jiazhao97.github.io/CONCISE-tutorial/documentation/02_installation.html):

``` r
# install devtools if necessary
install.packages('devtools')

# install the CONCISE package
install_github("jiazhao97/CONCISE")

# load package
library(CONCISE)

```

Use `CONCISE`
-------------------
Example Analysis with CONCISE: [here](https://jiazhao97.github.io/CONCISE-tutorial/documentation/03_Experiments.html).
