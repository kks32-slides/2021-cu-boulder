# Multiscale modeling of natural hazards
## MPM, LBM-DEM and ML
> Krishna Kumar (2021)

Boase Seminar Series, CU Boulder, 29th Oct 2021.

[https://kks32-slides.github.io/2021-cu-boulder/](https://kks32-slides.github.io/2021-cu-boulder/)

[![License](https://img.shields.io/badge/license-cc--by--4.0-brightgreen.svg)](https://creativecommons.org/licenses/by/4.0/)

Geotechnical hazards such as landslides cause thousands of casualties and billions of dollars in infrastructure damage worldwide. According to the US Geological Survey, the number of people and infrastructures at risk continues to increase. Geophysical hazards usually involve a multiphase flow of dense granular solids and water. Understanding the granular flow mechanics is particularly important in predicting the run-out behavior of landslides and debris flows. The granular flow dynamics involve three distinct scales: the microscopic scale, the mesoscale, and the macroscopic scale. Conventionally, granular flows are modeled as a continuum because they exhibit many collective phenomena at the macroscopic scale. Recent studies, however, suggest that a continuum law may be unable to capture the effect of inhomogeneities at the grain scale level, such as the orientation of force chains. Discrete element methods (DEM) can simulate the microstructural effects; however, they are computationally expensive. A multiscale approach helps to understand the mechanics of geophysical hazards. The DEM is used to capture the micro-scale behavior, while the macroscopic flow dynamics are modeled using a hybrid Eulerian-Lagrangian mesh-free approach called the Material Point Method (MPM). The MPM can simulate large-deformation problems without suffering from the limitations of mesh distortion effects observed in the conventional Finite Element approach. The DEM technique is coupled with the Lattice Boltzmann Method (LBM) to model the fluid-grain interactions in a submarine flow. We investigate the multiphase micromechanical origin of suction leading to unsaturated slope failures. Finally, I will present some recent studies using graph-based machine learning techniques to accelerate multiscale modeling of natural hazards.
