# iGEM-2022-Dry-Lab
Structural Modelling and Mathematical Modelling of Lead Absorbing Genetic Circuit and Oscillatory Biosensor
# Frequency-Based Oscillations in Genetic Circuit for Biosensor Construction

## Overview
This project validates the functionality of a genetic circuit used in constructing a biosensor by identifying frequency-based oscillations. We modeled the dynamics of a quorum-sensing oscillator using differential equations, focusing on the intracellular concentrations of LuxI (I), AiiA (A), internal AHL (Hi), and external AHL (He). The differential equations, derived from existing literature, simulate the reaction dynamics.

## Methodology

### System Modeling
We represent our system using a set of four differential equations. The equations consider the concentrations of various elements in the model. Key assumptions include:
- External AHL variation with position x is ignored, transforming partial differentials into ordinary differential equations.
- Constant concentration of LuxR throughout the simulation.
- G(α, τ) represents delayed protein generation, reflecting the historical concentration of internal AHL.

### Figure 1.1
(a) System of Delayed Differential Equations  
(b) Hill Function and Delay Definitions

![Figure 1.1](https://static.igem.wiki/teams/4428/wiki/model/eq1-2.png)

### Parameters
(Description of parameters and Table 1.1)

## Results
Simulation results display oscillations in the concentrations of different elements, confirming the concept of a lead-based oscillating biosensor.

### Figure 1.2
(a) Overall System Solution  
(b) Variations in LuxI Concentration

![Figure 1.2](https://static.igem.wiki/teams/4428/wiki/model/parameters-new.png)

## Analysis
- Oscillation ranges for LuxI, AiiA, and both internal and external AHL are identified.
- LuxI concentration changes indicate the period-modulating behavior of the sensor.
- Oscillations in internal AHL correlate with expected fluorescence oscillations.

## Parameter Sensitivity
We define a sensitivity score to analyze parameter impacts and provide troubleshooting insights for future wet lab experiments.

### Sensitivity Analysis
- τ (time delay constant) and d (cell density constant) are identified as critical parameters affecting oscillations.
- Detailed results and analysis in Table 1.2.

## Conclusion
The study provides computational proof for the functionality of the biosensor genetic circuit and offers guidance for future experimental setups.
