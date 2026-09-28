---
title: Inverse of a Symmetric Operator
template: default
---

Let $A$ be a symmetric matrix. Then by the spectral theorem,
$$
A = Q \Lambda Q^T,
$$
where $Q$ is orthogonal and $\Lambda = \mathrm{diag}(\lambda_1,\dots,\lambda_n)$.


If $A$ is invertible (i.e. $\lambda_i \neq 0$ for all $i$), then
$$
A^{-1} = Q \Lambda^{-1} Q^T,
\quad \text{where } \Lambda^{-1} = \mathrm{diag}\left(\frac{1}{\lambda_1}, \dots, \frac{1}{\lambda_n}\right).
$$


#### Key observation:
Small eigenvalues of $A$ become large eigenvalues of $A^{-1}$.



#### Consequence:
If $|\lambda_i| \ll 1$, then $\frac{1}{\lambda_i}$ is large, so small perturbations in the data can be strongly amplified.



This is the source of numerical instability and ill-conditioning in matrix inversion.
