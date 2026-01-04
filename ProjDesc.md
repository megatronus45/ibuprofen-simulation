# Pharmacokinetic Simulation of Ibuprofen (PK-Sim)

This project uses **PK-Sim** to simulate the pharmacokinetics of a **single 600 mg oral dose of ibuprofen** in two virtual adult populations (younger vs. older), with the goal of examining **age-related differences in absorption and clearance**.

## Overview
- Software: PK-Sim
- Dose: 600 mg oral ibuprofen
- Formulation: Fast-dissolving tablet
- Simulation window: 24 hours
- Output: Peripheral venous plasma concentration

## Method
Two virtual adult populations were configured in PK-Sim with age-dependent physiological differences. Dissolution kinetics were adjusted to achieve ~50% release within 8 minutes, consistent with published benchmarks. Concentration–time profiles were generated and compared on a logarithmic scale.

## Results
- Younger adults exhibited faster absorption and higher peak plasma concentrations.
- Older adults showed slower absorption and reduced clearance, resulting in lower peak concentration and prolonged elimination.

These trends align with known age-related physiological changes and validate the model behavior.

## Files
- PK-Sim model: `model/Elder_vs_Younger_Ibuprofen.pksim5`
- Concentration–time plot: `figures/concentration_time_plot.png`

## Notes
This project was completed as an individual academic exercise to demonstrate familiarity with **population-based pharmacokinetic modeling** using PK-Sim.



