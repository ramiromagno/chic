
<!-- README.md is generated from README.Rmd. Please edit that file -->

# chic <img src="man/figures/logo.svg" align="right" height=140/>

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/chic)](https://CRAN.R-project.org/package=chic)
[![R-CMD-check](https://github.com/patterninstitute/chic/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/patterninstitute/chic/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

A pkgdown template for Pattern Institute R packages.

## Installation

``` r
# install.packages("devtools")
devtools::install_github("patterninstitute/chic")
```

## Usage

Add to `DESCRIPTION`:

    Config/Needs/website: patterninstitute/chic

And in `_pkgdown.yml`:

``` yml
template:
  package: chic
  bootstrap: 5
```
