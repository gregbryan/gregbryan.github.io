---
layout: page
title: Grackle
description: A chemistry and radiative cooling library for astrophysical simulations
img: assets/img/research/grackle_cooling.png
importance: 8
category: software
related_publications: true
---

[Grackle](https://github.com/grackle-project/grackle) is an open-source chemistry and radiative cooling/heating library for astrophysical simulations and models {% cite 2017MNRAS.466.2217S %}. It provides a non-equilibrium primordial chemistry network for atomic and molecular hydrogen, helium, and deuterium species, tabulated cooling and photoheating rates from the Cloudy code for metals, and a treatment of the UV background and its self-shielding.

Originally spun out of the chemistry machinery in Enzo, Grackle is deliberately code-agnostic: it presents a simple C/Fortran/Python interface and is used as the cooling solver by many of the major simulation codes in the community. The image above shows a classic application — the radiative cooling rate of gas as a function of temperature.

Documentation is at [grackle.readthedocs.io](https://grackle.readthedocs.io/), and development happens openly on [GitHub](https://github.com/grackle-project/grackle).
