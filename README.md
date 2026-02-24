
<!-- README.md is generated from README.Rmd. Please edit that file -->

# fishr

<!-- badges: start -->

[![R-CMD-check](https://github.com/SemraYalcin/fishr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/SemraYalcin/fishr/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of fishr is to provide functions for calculating Catch Per Unit
Effort (CPUE), a fundamental metric in fisheries science.

## Installation

You can install the development version of fishr from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("SemraYalcin/fishr")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(fishr)
cpue(100, 5)
#> [1] 20
```
