---
title: Complex Eigenvalues in Practice
template: default
---



We generate a random real matrix and compute its eigenvalues:

```python
A = np.random.randn(3,3)
eig, E = np.linalg.eig(A)
print("Eigenvalues");  print(eig)
print("Eigenvectors"); print(E);
```

This can produce results such as:

```python
Eigenvalues
[-1.60067843+0.22089685j -1.60067843-0.22089685j  2.33690063+0.j]

Eigenvectors
[[-0.3027998 +0.10719447j -0.3027998 -0.10719447j  0.37385239+0.j]
[ 0.91941024+0.j          0.91941024-0.j          0.49420961+0.j]
[-0.2257535 -0.02327633j -0.2257535 +0.02327633j  0.7848511 +0.j]]
```

