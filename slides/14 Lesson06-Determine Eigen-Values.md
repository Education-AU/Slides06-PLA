---
title: Determine Eigenvalues
template: default

---


The next step is to determine the eigenvalues of $L$.

A scalar $\lambda$ is an eigenvalue if and only if there exists a non-zero vector $\mathbf{x}$ such that
$$
(L - \lambda I)\mathbf{x} = 0.
$$

This is a homogeneous linear system with a non-trivial solution, which holds if and only if the operator is not
invertible:

$$
\det (L - \lambda I) = 0.
$$

Let $A$ be a matrix representation of $L$. Since determinant is invariant under change of basis, we obtain the
characteristic equation:
$$
\det (A - \lambda I) = 0.
$$

In matrix terms
$$
\operatorname{det} (A - \lambda I) =
\begin{vmatrix}
a_{11}-\lambda & a_{12} & \dots & a_{1n}\\
a_{21} & a_{22}-\lambda & \dots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{n1} & a_{n2} & \dots & a_{nn}-\lambda
\end{vmatrix}
$$
Expanding this determinant produces a polynomial in $\lambda$ of degree $n$, called the **characteristic polynomial**
of $A$ (or of $L$). 

#### Characteristic Polynomial
$$
P(\lambda) = \det(A - \lambda I)
$$