---
layout: page
title: Machine Learning & AI
description: Connecting simulations to observations with machine learning and simulation-based inference
img: assets/img/research/camels_maps.png
importance: 5
category: research
related_publications: true
---

Modern cosmology and galaxy formation share a problem: the models are too complex for analytic likelihoods, and the simulations are too expensive to run everywhere we need them. Machine learning offers a way through — emulators that learn the mapping from physical parameters to observables, neural networks that extract cosmological information directly from field-level data, and simulation-based (implicit likelihood) inference that turns suites of simulations into rigorous posteriors on the parameters of cosmology and galaxy formation.

Much of this work builds on the CAMELS project — thousands of cosmological simulations with varied cosmology and feedback physics, designed from the start as a machine-learning training set {% cite 2021ApJ...915...71V 2023ApJS..265...54V %}. The image above shows gas surface-density maps from a sample of these simulations. With suites like these we can perform robust field-level inference of cosmological parameters {% cite 2023ApJ...944...27S %} and, conversely, use observations to calibrate the subgrid physics of the simulations themselves {% cite 2023ApJ...944...67J %}.

On the methods side, we develop tools and generative models for the community: the LtU-ILI framework packages the full simulation-based inference pipeline for astrophysical applications {% cite 2024OJAp....7E..54H %}, autoregressive networks generate halo catalogs directly {% cite 2025PhRvD.112j3503P %}, and hybrid physics-informed approaches like sapphire aim to combine the interpretability of analytic models with the flexibility of machine learning {% cite 2026arXiv260406318P %}.
