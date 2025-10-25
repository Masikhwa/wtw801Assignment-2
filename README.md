# WTW 801 Assignment 2
## Assignment Summary
This assignment has two parts. `Part 1` requires simulation of 1{,}500 observations of a trivariate normal $(x,y,z)$ with the given mean vector and covariance, implement PCA from `first principles` and then report the three eigenvectors and eigenvalues, verify orthogonality via pointwise products, and compare $v_1 \cdot v_3$ with $x \cdot z$. 

`Part 2` uses at least five years of daily prices for six U.S.\ companies: compute returns; set the last three months aside as `Data Set 2` (out-of-sample), with the remainder as `Data Set 1`. On `Data Set 1`, we build a three-factor model using the sample covariance and present factor loadings and factor series that will help us interpret factors, and report the variance share of the first component. Furthermore, we need to assess whether any factor's returns in 2025 differ from prior years (e.g., tariffs). Then redo the model with covariance shrinkage toward $\mu I$ with weight $\gamma\in\bigl(0,\tfrac12\bigr)$, and compare out-of-sample performance on `Data Set 2`.

#### NB: For Part 2, we used the yfinance library to dowload data from yahoo finance. This library can be installed using the command: pipinstall yfinance
