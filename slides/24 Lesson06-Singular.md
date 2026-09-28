---
title: Eigenvalues of a Singular Operator
template: default
---




A linear operator $L$ (or matrix $A$) is singular if its null space is non-trivial:
$$
\exists\, \mathbf{v} \neq \mathbf{0} \quad \text{such that} \quad L\mathbf{v} = \mathbf{0}.
$$


But this can be rewritten as
$$
L\mathbf{v} = 0 \cdot \mathbf{v},
$$
which shows that $\mathbf{v}$ is an eigenvector with eigenvalue $0$.


#### Conclusion:
A matrix is singular if and only if it has at least one zero eigenvalue.


We can verify this numerically in NumPy:
```python
A = np.array([[1,4,7],[2,5,8],[3,6,9]])
print(np.linalg.det(A))
eig, E = np.linalg.eig(A)
print(eig)
0.0
[ 1.61168440e+01 -1.11684397e+00 -5.70069119e-16]
```