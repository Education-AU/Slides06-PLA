---
title: Eigenvectors for symmetric operators
template: theorem
theoremTitle: Symmetric operators have orthogonal eigenvectors
---


Let $L: V \to V$ be a **symmetric** linear operator on a real vector space $V$.

<!-- theorem -->

Let $\lambda$ and $\mu$ be distinct eigenvalues with eigenvectors $\mathbf{v}$ and $\mathbf{w}$. Then
$$
\begin{aligned}
\lambda\langle \mathbf{v}, \mathbf{w} \rangle
=\langle \lambda \mathbf{v}, \mathbf{w} \rangle
= \langle L\mathbf{v}, \mathbf{w} \rangle
= \langle \mathbf{v}, L\mathbf{w} \rangle
= \langle \mathbf{v}, \mu \mathbf{w} \rangle
= \mu \langle \mathbf{v}, \mathbf{w} \rangle
\end{aligned}
$$

Implying,
$$
(\lambda - \mu)\langle \mathbf{v}, \mathbf{w} \rangle = 0
$$

Since $\lambda \neq \mu$ we have $\langle \mathbf{v}, \mathbf{w} \rangle =0$

<!-- /theorem -->


