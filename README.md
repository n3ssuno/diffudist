
<!-- README.md is generated from README.Rmd. Please edit that file -->

# diffudist <img src="man/figures/diffudist.png" align="right" alt="" width="120"/>

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

## Overview

The `diffudist` package provides the functions for the evaluation of the
diffusion distance between nodes of a complex network.

## Installation

``` r
# Or the development version from GitHub
# install.packages("devtools")
devtools::install_github("gbertagnolli/diffudist")
```

## Usage

`library(diffudist)` will load the functions of the package.

You will also need to load igraph `library(igraph)`, because the main
arguments of the functions in `diffudist` are networks, in the igraph
format.