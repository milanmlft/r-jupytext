
# jupytext

<!-- badges: start -->
<!-- badges: end -->

The goal of the *jupytext* R package is to provide an R wrapper for the
[jupytext](https://github.com/mwouts/jupytext) Python library.

## Installation

You can install the development version of jupytext from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("milanmlft/r-jupytext")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(jupytext)

## Converting from Rmd to ipynb
jupytext("path/to/file.Rmd", to = "ipynb")

## Converting from ipynb to Rmd
jupytext("path/to/file.ipynb", to = "Rmd")
```