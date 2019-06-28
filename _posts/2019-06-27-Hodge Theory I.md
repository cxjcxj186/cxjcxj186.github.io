---
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

layout:     post
title:      Review on Hodge Theory I
subtitle:   VHS, monodromy, and topology
date:       2019-06-27
author:     无敌小呆呆
header-img: img/Brookings Hall.jpg
catalog: true
tags:
    - Geometry
---



## 前言

略略略

K\"{a}hler manifolds, in particular projective manifolds, are excellent objects whose geometry has more algebraic structures. The interplay between differential geometry and algebra leads to the Hodge theory of k\"{a}hler manifolds which states the algebraic structures on the cohomology groups: Hodge decomposition and Hodge diamonds, the natural $\mathfrak{sl}_2$-action and Lefschetz decomposition, Riemann-Hodge bilinear relations. These algebraic structures are Hodge structures, and morphism of k\"{a}hler manifolds induces morphism of Hodge structures. Explicit computations need more techniques, but the general story for a single k\"{a}hler manifold comes to the end.



The more interesting problem is to study the Hodge theory of morphisms of complex manifolds. Though we do have decomposition theory for relative manifolds, the simplest two cases are submanifolds, and families of manifolds.

We want to compare the cohomology of a k\"{a}hler manifold $X$ and its codimension $1$-submanifold $Y$. Their cohomologies are related by a long exact sequence
$$\cdots H^k(X,\mathbb{Z})\to H^k(U,\mathbb{Z})\to H^{k-1}(Y,\mathbb{Z})\to H^{k+1}(X,\mathbb{Z})\cdots.$$

\begin{remark}
There are two interpretations of this long exact sequence:
\begin{enumerate}
\item[(1).]\textit{Topological Interpretation}The long exact sequence associated to the pair $(X,U)$, where $U=X-Y$. Thom isomorphism.
\item[(2).]\textit{de Rham interpretation}$H^k(U,\mathbb{C})$ can be computed as the \textit{hypercohomology} of $\Omega^\cdot(\log Y)$. Residue map and Gysin morphism.

    The residue map is defined as a sheaf complex map: $\Omega_X^\cdot(\log Y)\to\Omega^{\cdot-1}_Y$. This map induces a morphism of \textit{hypercohomology} of the sheaves, i,e,. $H^\cdot(U,\mathbb{C})\to H^{\cdot-1}(Y,\mathbb{C})$.
\end{enumerate}
\end{remark}

The typical case are:
\begin{enumerate}
\item[1.]$X$ is projective, and $Y$ is a hyperplane intersection (Lefschetz theorem on hyperplane sections). The interesting point is that, in this case, we can always put $Y$ in a Lefschetz pencil(a family of hyperplane sections parameterized by $\mathbb{P}^1$ with only finitely many singular fiber whose only singular point is ODP). Lefschetz pencils are easy enough to study the local degeneration and local monodromy, and is general enough to give information for more general monodromy. (The monodromy of a Lefschetz is a representation of $\pi_1(\mathbb{P}^1-\{0_1,...,0_M\},0)$).
\item[2.]$X$ is the projective space $\mathbb{P}^N$, $Y$ is a hypersurface of degree $d$. Part of its cohomology can be deduced from the Lefschetz theorem on hyperplane sections (P.35). The nontrivial term can be computed as residues of homogeneous quotient (P.166. Corollary 6.12).
\end{enumerate}
\begin{remark}
The study of codimension $1$ geometry is roughly the study of line bundles. Classical line bundles are: the canonical bundle $K_X$; the line bundle $\mathcal{O}_{X}(D)$ associated to a divisor $D$; the twisted bundle $\mathcal{O}_X(k)$ for a projective manifold.
\end{remark}

The simplest examples of deformations are: projective morphism (projective bundles); Legendre family of elliptic curves; universal hyperplane sections (hypersurfaces) associated to a projective variety $X$ (line bundle over $X$). The interesting point is that: let  $\phi:X\to Y$ be a deformation with k\"{a}hler fibers, then the algebraic objects on fibers becomes analytic objects over $Y$, therefore, infinitesimal study is possible. Examples are Kadaira-Spencer map; Hodge bundles, Griffiths transversality, and infinitesimal variation of Hodge structure (which should, at least, be linear); Jacobian filtration and normal functions; Hodge loci.

Leray spectral sequence plays an important role in this case because it decomposes the study of $X$ into the base part $Y$ and the relative part (fiber part) $X/Y$. Actually, Hodge bundles and Griffiths transversality have pure algebraic interpretation. This interpretation makes it possible to study deformation theory algebraically.
