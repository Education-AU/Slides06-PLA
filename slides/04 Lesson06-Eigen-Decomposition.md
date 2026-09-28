---
title: Eigen Decomposition
footerVariant: dark
template: theorem
theoremTitle: Spectral theorem
---

Let $V$ be a **real** finite-dimensional **inner product** space and
$L : V \to V$ a linear map. We refer to such a linear map as an operator.

<!-- theorem -->

For any symmetric operator

$$\forall \mathbf{x}, \mathbf{y} \in V : \langle L\mathbf{x}, \mathbf{y}\rangle = \langle \mathbf{x}, L\mathbf{y}\rangle$$

there exists an orthonormal basis $\{\mathbf{v}_1, \mathbf{v}_2, \dots, \mathbf{v}_n\}$ of $V$ such that

$$L (\mathbf{v}_i) = \lambda_i \mathbf{v}_i, \quad i = 1, \dots, n$$

The scalars $\lambda_i \in \mathbb{R}$ are called the eigenvalues of $L$, and the
vectors $\mathbf{v}_i$ are called the associated eigenvectors.

The eigenvalues are counted with multiplicity. If an eigenvalue has an
eigenspace of dimension greater than one, the orthonormal eigenvectors
are chosen within that eigenspace are not unique.
<!-- /theorem -->


