---
title: Application to Linear Normal Models
template: default
---


In the linear normal regression model the fitted values are
$$
\hat{\mu} = D \hat{\beta} = D (D^T D)^{-1} D^T y.
$$

The covariance matrix of the estimator is
$$
\mathrm{Var} (\hat{\beta}) = \sigma^2 (D^T D)^{-1}.
$$

#### Key observation:

The matrix $D^T D$ is symmetric positive semidefinite and plays a central role in inference.

Its eigenvalues determine stability:

1. Large eigenvalues $\Rightarrow$ small variance (stable estimates)
2. Small eigenvalues $\Rightarrow$ large variance (unstable estimates)

Thus, near-singularity of $D^T D$ leads to high-variance, ill-conditioned estimation.
