
<!-- README.md is generated from README.Rmd. Please edit that file -->

# networkdata

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/networkdata)](https://cran.r-project.org/package=networkdata)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Downloads](https://cranlogs.r-pkg.org/badges/networkdata)](https://CRAN.R-project.org/package=networkdata)
<!-- badges: end -->

The package contains a large variety of different network datasets (all
in `igraph` format). So far, it includes datsets from the following
repositories:

  - Freeman’s datasets from <http://moreno.ss.uci.edu/data>
  - Movie networks from
    <https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/T4HBA3>
  - Covert networks from
    <https://sites.google.com/site/ucinetsoftware/datasets/covert-networks>
  - Animal networks from <https://bansallab.github.io/asnr/>
  - Shakespeare’s plays networks build with data from
    <https://github.com/mallaham/Shakespeare-Plays>

A list of all datasets can be obtained with

``` r
data(package = "networkdata")
```

So far, the package contains 954 datasets.

**Feel free to add your own datset via a pull request**

## Installation

You can install the developers version of networkdata with:

``` r
#install.packages("remotes")
remotes::install_github("schochastics/networkdata")
```
