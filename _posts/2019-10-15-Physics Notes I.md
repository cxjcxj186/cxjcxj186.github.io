---
layout:     post
title:      Physics Notes I
subtitle:   Mechanics and electrodynamics
date:       2019-10-15
author:     无敌小呆呆
header-img: img/TheGreatDome.jpg
catalog: true
tags:
    - Physics
---



## Mechanics

The mechanics statue of a particle is determined by its position and velocity. Thus a function $L(q,\dot{q},t)$ is enough to derive mechanics principles. The actual mechanics happens when the action $S[L]$ takes its extreme. This derives the Euler-Lagrange equation. In certain cases, it is the motion equation for a particle or a system. It is a system of $s$ second-order equations.

To derive the Lagrangian for a system, we use the symmetry of the space-time. In practice, just apply the canonical Lagrangian and make a change of variable. Note that for a system, $L=\sum \frac{1}{2}m_\alpha v_\alpha^2-U$, while the energy is $E=\sum \frac{1}{2}m_\alpha v_\alpha^2 +U$.

Another way to study mechanics is, instead of considering $L$, we consider a function of momentum and speed
$$H=\sum p_i\dot{q}_i-L$$
Then we have the canonical equations, which is a system of $2s$ first-order equations.

## Relativity

The principle of relativity and finiteness of transition speed. Since the speed is finite, the space and time are there related. Time flows in different speed in different frames. The form $ds^2=\sum dx_i^2-c^2dt^2$ will be an invariant in this setting.


Physical laws are suitable for any inertia frame. All inertia frames are equivalent. But special relativity tells how to compare physical quantities in different inertia frame (one is moving with a constant sppe $v$). The Lorentz transform tells you how to compare time, space, and thus velocity. The Lorentz  transformation is a purely geometric setting. Therefore, all physical laws, classical mechanics nor electrodynamics are not changed under special relativity, but the trivial comparison between inertia frames (Galileo's transformation) does not hold anymore. So you have to specify an inertia frame before talking about physics. 

Mechanics: The rest mass is an invariant quantity (same value in all inertia frames). The relativistic momentum becomes a 4-vector. 

### Minkowski geometry:

The "spheres" in Minkowski are hyperboloids (one-sheeted, two sheeted or a cone). 


## Electrodynamics
### Maxwell's Equations

Gradient, curl, divergence, are usual exterier differential operators. $d^2=0$ gives two fundamental equations. However, in physics, we identify one forms and two forms since they are both $3$-vectors. The Helmholtz theorem asserts that, under certain decaying conditions, div and curl of a field determine the field itself. The Maxwell's equations telly you the div and curl of electric and magnetic fields:

$$\nabla\cdot E=\frac{1}{\epsilon_0}\rho;$$

$$\nabla \cdot B=0;$$


$$\nabla\times E=-\frac{\partial B}{\partial t};$$

$$\nabla\times B=\mu_0 J+\mu_0\epsilon_0\frac{\partial E}{\partial t}.$$

where $\rho$ and $J$ are external conditions (sources  of the fields) satisfying the continuity equation

$$\frac{\partial \rho}{\partial t}=-\nabla\cdot J.$$

What does the Maxwell's equation tell you?

The essence of electrodynamics is the symmetry and asymmetry between electric and magnetic fields.

A static electric field is a div field, it has no curl. The curl part of a electric field in induced from the variation of a magnetic field. While a magnetic field has no div (the field are enclosed loops). The magnetic comes partly from the electric flow, partly from the variation of electric field.

Another asymmetry is that, we have electrons, it creates electric fields, while the magnetic field comes essentially from the motion of electric objects, charges or fields.

### Relativistic Electrodynamics

Electrodynamics is inherently consistent with special relativity.
 
Electric and magnetic fields become a antisymmetric $2$-tensor $F^{\mu\nu}$ and its dual $G^{\mu\nu}$. $(\pho,J)$ becomes the current density $4$-vector. Maxwell's equations become

$$\frac{\partial F^{\mu\nu}}{\partial x^{\nu}}=\mu_0J^{\mu};\frac{\partial G^{\mu\nu}}{\partial x^{\nu}}=0.$$

The potential fields $A^{\mu}$ satisfies
$$F^{\mu\nu}=\frac{\partial A^{\nu}}{\partial x^{\mu}}-\frac{\partial A^{\mu}}{\partial A^{\nu}}.$$

In potential form, the Maxwell's equations become d'Alembert equation
$$\Box^2A^{\mu}=-\mu_0J^{\mu}.$$
### EM waves



