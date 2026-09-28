---
title: Calculating Eigenvalues and Eigenvectors in NumPy
template: default
---

In NumPy we can compute the eigenvalues and eigenvectors of a symmetric matrix.

We define a symmetric matrix $A$ and compute its eigendecomposition:

```python
A = np.array([[ 2.06997006, -0.30502644],
[-0.30502644, 0.34265488]])

eig_values, E = np.linalg.eig(A)
```

We then construct the diagonal matrix $\Lambda$ and verify the decomposition
$A = E \Lambda E^T$:

```python
Lambda = np.diag(eig_values)
A_d = E @ Lambda @ E.T
assert np.allclose(A_d, A)
```

### Eigenvectors are chosen orthonormal
We can also verify that the matrix of eigenvectors is orthogonal.
For symmetric matrices, the eigenvectors form an orthonormal basis.

```python
assert(np.allclose(E@E.T, np.eye(2,2)))
```