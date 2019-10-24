---
layout:     post
title:      Physics Notes II
subtitle:   Quantum Mechanics
date:       2019-10-15
author:     无敌小呆呆
header-img: img/TheGreatDome.jpg
catalog: true
tags:
    - Physics
---

In classical mechanics, the position and velocity totally determine the state of an object. But in quantum mechanics, these two cannot be measured simultaneously. Therefore, an object does not have an explicit orbit.

The position and other physical quantity are expressed by a wave function, its integration determines the probability. Although we cannot determine the motion (or even the state) of an object, the wave function can be explicitly determined by the wave equation

$$i\hbar \frac{\partial \psi}{\partial t}=\hat{H}\psi$$

where $\hat{H}$ is the Hamiltonian, which is an Hermitian operator. An Hermitian operator is, in some sense, a real operator. We can see this by its behavior under conjugation, or its spectrum decomposition.


A physical quantity is represented by an Hermitian operator $f$. Its eigenvalues $f_n$ are the possible values , while the corresponding eigenvectors $\phi_n$ are the corresponding wave functions. By superposition principle, the wave function for any state is a linear combination of eigen-wave functions.


## Philosophy
Observable and observation: Observable is not the same as observation. An observable is an Hermitian operator. Its eigenvalues form a complete set of possible values of a certain physical quantity. Its eigenstatetes spans all the states. When we apply an observable to an eigenstate, the eigenvalue appears, but usually, a state is not an eigenstate. An observable change the state. but the result is not necessarily an eigenstate. Observation is a physical experiment, it collapses the state to one eigenstate. Observable is an definite operator, while observation is essentially a probability 

Observables are operators, but not all operators are observables. At least, given an observable, we can decompose the state space into eigentates of the observable. We can decompose the state space with respect to any observable.

The particle and wave properties are intrinsically inconsistant. That is the origin of quantum mechanics. In quantum mechanics, we replace the physical quantity by observables, therefore, certain physical quantities become quantized. 

Neither a state nor an operator gives a concrete real number. To get a real number, we must use the pairing of two states. For example, the expectation of an observation. Therefore, Schrodinger picture or Hisenburg picture (operators evolves with time) give the same evolution picture. Once we are trying to get any real number, anything that we can detect.

In nonrelativistic quantum mechanics, time $t$ is an independent parameter, while the position is an operator. This is an intrinsic inconsistence with relativity. The Schrodinger is first order with respect to time, while second order with respect to spatial coordinates.


## Operator Methods
Abstract theory of Hilbert spaces and operators become concrete in Schrodinger picture. A wave function is the decomposition with reapect to the position observable. The inner product is the usual $L^2$-inner product. Position and momentum operators are multiplication of differential operators on functions. These two basic operators induces other canonical operators, energy operator for example.

The position and momentum share the same position. Their wave functions are related by Fourier transform. This is reflected by the fact that momentum is essentially frequency. Multiplication and differential exchanges after a Foruier transform.

The Schrodinger equation: the evoluation of state is determined by energy operator, or Hamiltonian. The commutator relation $[\hat{x},\hat{p}]=i\hbar$ implies that these operators are essentially infinite dimensional. For the case of one-dimensional equation, especially when the potential operator is even, refer to MIT open course, by Barton Zwiebach.


## Angular Momentum & Spins
