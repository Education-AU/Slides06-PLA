---
title: Complex Roots of the Characteristic Polynomial
template: default
---

Recall that a real linear operator may not have a full set of eigenvalues in $\mathbb{R}$.

The characteristic polynomial can have complex roots. These correspond to eigenvalues when the operator is extended to a
complex vector space $\mathbb{C}^n$.

### Important:

1. Over $\mathbb{R}$, complex roots do not correspond to real eigenvectors.
2. Over $\mathbb{C}$, every root of the characteristic polynomial is an eigenvalue.

In numerical computations (e.g. NumPy), eigenvalues are computed in a such a way that it allows complex values, even for real
matrices.

