---
layout: page
permalink: /research/
title: Research
description: Statistical methodology for inverse problems, differential equations, and uncertainty quantification.
nav: true
nav_order: 2
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

My research develops statistical methods for recovering complex, often infinite-dimensional objects from indirect and noisy observations. A recurring theme is to understand what remains statistically reliable when the forward model, the noise distribution, or parts of the observation mechanism are only approximately known.

<div class="research-grid">
  <section class="research-card">
    <div class="research-number">01</div>
    <h2>Robust Bayesian inverse problems</h2>
    <p>I study posterior contraction and uncertainty quantification for nonlinear inverse problems under heteroscedasticity and model misspecification. The aim is to connect rigorous Bayesian theory with the surrogate forward models used in computation.</p>
    <p class="research-keywords">Bayesian nonparametrics · misspecification · posterior contraction · UQ</p>
  </section>

  <section class="research-card">
    <div class="research-number">02</div>
    <h2>Inference for differential equations</h2>
    <p>I investigate parameter and function estimation in models governed by ODEs and PDEs, including the Darcy problem, reaction–diffusion equations, and the two-dimensional Navier–Stokes equations. My work covers upper bounds, stability, and minimax lower bounds.</p>
    <p class="research-keywords">PDE-constrained regression · dynamical systems · minimax theory</p>
  </section>

  <section class="research-card">
    <div class="research-number">03</div>
    <h2>Inverse problems with unknown structure</h2>
    <p>I develop spectral methods for multiplicative measurement error models in which the error distribution—and hence the inverse operator—is unknown. I am particularly interested in adaptive procedures for densities, distribution functions, and other local functionals.</p>
    <p class="research-keywords">multiplicative deconvolution · unknown operators · adaptation</p>
  </section>
</div>

## Current directions

- Bernstein–von Mises theory and uncertainty quantification under misspecification
- Statistical guarantees for numerical and surrogate forward models
- Inference for Gaussian random fields from local measurements
- Minimax theory for nonlinear dynamical systems

My work is currently connected to the [SFB 1294 “Data Assimilation”](https://sfb1294.math.uni-potsdam.de/) and builds on collaborations and research stays in Berlin, Cambridge, Heidelberg, Aarhus, and Potsdam.
