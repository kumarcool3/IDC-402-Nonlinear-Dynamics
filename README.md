# IDC-402-Nonlinear-Dynamics
This repository includes the supporting code for the term paper "Laser Dynamics as a Nonlinear Dynamical System"
# Laser Dynamics as a Nonlinear Dynamical System

## Overview

This project investigates laser dynamics from the perspective of nonlinear dynamical systems. Using the Lorenz–Haken model, the study explores how deterministic equations governing laser behavior can lead to complex phenomena such as oscillations and chaos.

The work combines theoretical analysis with numerical simulations to understand stability, bifurcations, and the emergence of chaotic dynamics in single-mode lasers.

---

## Model

The system is described using a set of coupled nonlinear differential equations:

[
\dot{E} = \sigma (P - E), \quad
\dot{P} = ED - P, \quad
\dot{D} = -EP - b(D - r)
]

where:

* (E): electric field amplitude
* (P): polarization
* (D): population inversion
* (r): pump parameter (control parameter)
* (\sigma, b): system parameters

This formulation is mathematically equivalent to the Lorenz system and captures the essential physics of laser dynamics.

---

## Objectives

* Analyze fixed points and their stability
* Identify thresholds for lasing and instability
* Study bifurcations and transition to chaos
* Perform numerical simulations of the system
* Visualize dynamical behavior using plots

---

## Results

The system exhibits a rich range of dynamical behaviors:

* **Non-lasing regime** for (r < 1)
* **Steady-state lasing** for (r > 1)
* **Oscillatory dynamics** at intermediate values of (r)
* **Chaotic behavior** at higher pump values

The following analyses were performed:

* Time series of intensity (E^2(t))
* Phase space trajectories (2D and 3D attractors)
* Sensitivity to initial conditions
* Bifurcation diagram
* Threshold analysis

---

## Applications

Chaotic laser dynamics have practical applications in:

* Secure optical communication (chaos-based encryption)
* Random number generation
* Optical signal processing

A demonstration of chaos-based signal masking is included to illustrate how information can be hidden within a chaotic carrier.

---

## Tools and Methods

* Python (NumPy, SciPy, Matplotlib)
* Numerical integration using `solve_ivp` (Runge–Kutta method)
* Visualization of nonlinear dynamics


---

## Key Insight

This project demonstrates how simple deterministic equations can produce highly complex and unpredictable behavior, highlighting the fundamental role of nonlinear dynamics in physical systems such as lasers.


---

## Author

Amarnath (MS22070)
BS-MS Physics, IISER Mohali
