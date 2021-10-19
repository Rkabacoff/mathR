
# mathR

The goal of mathR is to ...

## Installation

You can install the development version of mathR using 

``` r
if (!require(remotes)){
  install.package("remotes")
  library(remotes)
}
remotes::install_github("rkabacoff/mathR")
```

## Basic Example

This is a basic example which shows you how to add two vectors:

``` r
library(mathR)
x <- c(1, 2, 3)
y <- c(10, 15, 20)
add(x, y)
```

