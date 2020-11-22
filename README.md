
# dublinbikes

<!-- badges: start -->
<!-- badges: end -->

The goal of dublinbikes package is to provide R user access to quarterly rollups of historic bike data. Static data provides information like bike station position, number of bike stands, payment terminal availability. It is formatted to be convenient for data analysis with R.

## Installation

``` r
install.packages("devtools")
devtools::install_github("mryap/dublinbikes")
```
Once the package is installed, load the library every time to access it.

``` r
library(dublinbikes)
dplyr::glimpse(dublinbikes)
```

## License

This package is licensed under MIT license.

