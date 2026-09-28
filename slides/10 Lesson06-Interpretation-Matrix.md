---
title: Interpretation of Matrix Diagonalization
template: default
---

1. Eigenvectors constitute a **basis**
2. We can change coordinates to that **basis**
3. Change of coordinates is some matrix $Q$ having columns of the initial **basis** expressed in the target **basis**

Assume that $A$ is expressed in standard coordinates.

Define $Q$ as the matrix containing columns of eigenvectors $\mathbf{v}_i$ expressed in standard coordinates. That is
$$
\begin{aligned}
Q &: \text{eigen-coordinates} \;\rightarrow\; \text{standard coordinates} \\
Q^{-1} &: \text{standard coordinates} \;\rightarrow\; \text{eigen-coordinates}
\end{aligned}
$$

Now, as we saw in the previous lesson, we can change coordinates of a Linear operator by using the formula

$$
A'=\left (P_{e\rightarrow e'}AP_{e\rightarrow e'}^{-1}\right) \text{ or } A'=\left (P_{e'\rightarrow e}^{-1}AP_{e'\rightarrow e}\right)
$$

Using the matrix $Q$ instead we get

$$
A'=\Lambda=Q^{-1}AQ
$$

Since in those coordinates the matrix is diagonal with the eigenvalues on the diagonal.

Which is the same as

$$
A = Q\Lambda Q^{-1}
$$

If the eigenvectors are orthonormal, then $Q^{-1}=Q^T$ and we have

$$
A = Q\Lambda Q^T
$$
