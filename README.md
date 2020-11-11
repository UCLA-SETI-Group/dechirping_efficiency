# Dechirping Efficiency
This repository contains code to compute the dechirping efficiency ([Margot et al. (2020)](https://arxiv.org/abs/2011.05265)) of radio technosignature data-processing pipelines such as those used by the Breakthrough Listen team in [Enriquez et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...849..104E/abstract) and [Price et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020AJ....159...86P/abstract).  The dechirping implemented in this notebook comes from the [turboSETI package](https://github.com/UCBerkeleySETI/turbo_seti).



## dechirping_efficiency.ipynb

In this notebook, we provide the code to replicate the Breakthrough Listen (BL) portion of Figure 7 of [Margot et al. (2020)](https://arxiv.org/abs/2011.05265):

![Dechirp_efficiency_compariosn](/images/dechirp_efficiency_comparison.png)

Additionally, we provide the code to generate Table 4, which lists the dechirping efficiency statistics of the tree algorithm for various array dimensions:

|  Rows |  Min (%) |  Max (%) | Mean (%) |Median (%)|  STD (%) |
|-------|----------|----------|----------|----------|----------|
|     2 |   100.00 |   100.00 |   100.00 |   100.00 |     0.00 |
|     4 |   100.00 |   100.00 |   100.00 |   100.00 |     0.00 |
|     8 |    75.00 |   100.00 |    93.75 |   100.00 |    11.57 |
|    16 |    75.00 |   100.00 |    90.62 |    93.75 |    10.70 |
|    32 |    68.75 |   100.00 |    85.16 |    81.25 |    11.20 |
|    64 |    68.75 |   100.00 |    81.64 |    78.12 |     9.83 |
|   128 |    64.06 |   100.00 |    77.93 |    75.00 |     8.88 |
|   256 |    64.06 |   100.00 |    75.17 |    73.44 |     7.68 |
|   512 |    60.16 |   100.00 |    72.42 |    71.09 |     6.84 |
|  1024 |    60.16 |   100.00 |    70.08 |    69.14 |     6.10 |
|  2048 |    56.84 |   100.00 |    67.92 |    66.60 |     5.53 |
|  4096 |    56.84 |   100.00 |    66.01 |    64.94 |     5.06 |

<br>
Notebook author: UCLA graduate student Paul Pinchuk

