# BayesMVP

<!-- badges: start --

[![CRAN](http://www.r-pkg.org/badges/version/BayesMVP)](https://cran.r-project.org/package=BayesMVP)
[![r-universe](https://zhizuio.r-universe.dev/badges/BayesMVP)](https://zhizuio.r-universe.dev/BayesMVP)
[![DOI](https://img.shields.io/badge/doi-10.32614%2FCRAN.package.BayesMVP-brightgreen)](https://doi.org/10.32614/CRAN.package.BayesMVP)

-- badges: end -->

[![R-CMD-check](https://github.com/zhizuio/BayesMVP/workflows/R-CMD-check/badge.svg)](https://github.com/zhizuio/BayesMVP/actions)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


This R package is for high-dimensional Bayesian multivariate probit (BayesMVP) models with general variable selection and dense/sparse covariance matrix, including extended methods from [Bottolo et al. (2021)](https://doi.org/10.1111/rssc.12490), [Zhao et al. (2021)](https://doi.org/10.18637/jss.v100.i11) and [Zhao et al. (2024)](https://doi.org/10.1093/jrsssc/qlad102). 

## Installation

Install the latest development version from [GitHub](https://github.com/zhizuio/BayesMVP_test)

```r
#install.packages("remotes")
remotes::install_github("zhizuio/BayesMVP_test")
```

## Examples

TBA...


## References

> Leonardo Bottolo, Marco Banterle, Sylvia Richardson, Mika Ala-Korpela, Marjo-Riitta Järvelin, Alex Lewin (2021).
> A computationally efficient Bayesian seemingly unrelated regressions model for high-dimensional quantitative trait loci discovery.
> _Journal of the Royal Statistical Society: Series C (Applied Statistics)_, 70(4):886-908. DOI: [10.1111/rssc.12490](https://doi.org/10.1111/rssc.12490).

> Zhi Zhao, Marco Banterle, Leonardo Bottolo, Sylvia Richardson, Alex Lewin, Manuela Zucknick (2021).
> BayesMVP: An R package for high-dimensional multivariate Bayesian variable and covariance selection in linear regression.
> _Journal of Statistical Software_, 100(11):1-32. DOI: [10.18637/jss.v100.i11](https://doi.org/10.18637/jss.v100.i11).

> Zhi Zhao, Marco Banterle, Alex Lewin, Manuela Zucknick (2023).
> Multivariate Bayesian structured variable selection for pharmacogenomic studies.
> _Journal of the Royal Statistical Society: Series C (Applied Statistics)_, 73(2):420-443 qlad102. DOI: [10.1093/jrsssc/qlad102](https://doi.org/10.1093/jrsssc/qlad102).
