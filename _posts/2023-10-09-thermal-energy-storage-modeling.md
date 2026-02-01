---
title: 'Modelling and optimization of thermal energy storage'
date: 2023-10-09
permalink: /posts/2023/10/thermal-energy-storage-modeling/
tags:
  - papers
  - geothermal
  - reservoir simulation
  - optimization
  - thermal storage
---

Shallow geothermal reservoirs are excellent candidates for heat batteries, providing constant discharge of base heat, as well as rapid discharge of heat in periods of high demand. Recharging can be done by pumping down hot water from e.g., waste incineration. Such systems have a low carbon footprint, require limited surface infrastructure, and can easily be placed near the end-user.

As in most geoenergy applications, the geological setting is both highly complex and highly uncertain, with fractures, faults, and horizons. Robust numerical algorithms capable of accurately predicting the behavior of a geothermal system can be a key enabler for underground thermal energy storage.

In this work, we show how to practically model such systems leveraging methods from simulation of oil and gas reservoirs, including unstructured gridding, discrete fracture modelling, multisegment wells, and group control. We also demonstrate how adjoint-based methods can be used to tune model parameters so that the model fits observed data, and to find well controls that optimize storage operations.

**Full paper:** [https://doi.org/10.1144/geoenergy2023-005](https://doi.org/10.1144/geoenergy2023-005)

## Key Contributions

This work demonstrates:

- **Advanced wellbore modeling:** Comparison of simple and multisegment wellbore modelling in a 300 m deep, fractured reservoir
- **Unstructured grid generation:** Construction of a 2.5D Voronoi grid for a thermal battery with 100 wells and multiple fractures
- **Parameter optimization:** Using adjoint-based methods for model calibration and operational optimization

The research bridges the gap between traditional reservoir simulation techniques and emerging geothermal energy storage applications, providing practical tools for the design and operation of underground thermal energy storage systems.