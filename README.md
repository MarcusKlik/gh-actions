
<img src="fstcore.png" align="right" height="196" width="196" />

[![License: AGPL
v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![R-CMD-check](https://github.com/MarcusKlik/gh-actions/workflows/R-CMD-check/badge.svg)](https://github.com/MarcusKlik/gh-actions/actions)

## Overview

R package `fstcore` contains R bindings to the C++ `fstlib` library which allows interfacing with _fst_ files.
It also contains the `LZ4` and `ZSTD` sources used for compression. `fstcore` exists as a package separate from the
`fst` package to facilitate independent updates to the `fstlib`, `LZ4` and `ZSTD` libraries and is used as a
backend to `fst`.


## Installation

Package `fstcore` is automatically installed as a dependency when you install the `fst` package from CRAN.
If you need to install it directly, you can use:

``` r
install.packages("fstcore")
```

You can also use the development version from GitHub:

``` r
# install.packages("devtools")
devtools::install_github("fstpackage/fstcore", ref = "develop")
```

## Basic usage

Please refer to http://www.fstpackage.org/fst to get an introduction to using the `fst` package.


## Contact

Questions, ideas and issues can be best reported in the [fst package repository](https://github.com/fstpackage/fst).
