# pyMatrixEQTL
to understand what's going on inside Matrix eQTL, use Python to write the functions


# Matrix eQTL: Ultra Fast eQTL Analysis via Large Matrix Operations

Matrix eQTL is designed for fast eQTL analysis on large datasets.
Matrix eQTL can test for association between genotype
and gene expression using linear regression
with either additive or ANOVA genotype effects.
The models can include covariates to account for factors
as population stratification, gender, and clinical variables.
It also supports models with heteroscedastic and/or correlated errors,
false discovery rate estimation and
separate treatment of local (cis) and distant (trans) eQTLs.
For more details see
[Shabalin (2012)](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/bts163).

## Installation

### Install CRAN Version

To install the
[CRAN version](https://CRAN.R-project.org/package=MatrixEQTL)
of `MatrixEQTL`, run

```
install.packages("MatrixEQTL")
```

### Install GitHub Version

To install `MatrixEQTL` directly from GitHub, run

```
if(!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")
devtools::install_github("andreyshabalin/MatrixEQTL")
```
