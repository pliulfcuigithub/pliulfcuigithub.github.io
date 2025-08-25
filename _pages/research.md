---
layout: archive
permalink: /research/
author_profile: true
---

{% include base_path %}

Gyrokinetic simulation of instabilities and turbulence in stellarator plasmas
===========
Stellarators are a type of magnetic confinement devices that can generate rotational transform without the plasma current. Stellarators have regained popularity in recent years after the successful construction and operation of the Wendelstein 7-X (W7-X) device in Greifswald, Germany. Just like tokamaks, turbulent transport significantly affects the plasma temperature in optimized stellarators. However, stellarators are nonaxisymmetric and the detailed turbulent fluctuations often differ from tokamaks. We have studied the linear eigenmode structure of ion temperature gradient (ITG) modes in stellarators using the global gyrokinetic [GTC](https://sun.ps.uci.edu/gtc/) simulations. We found that the ITG eigenmode structures are nonuniform on flux surfaces and can be explained from the WKB (ray-tracing) theory from Dewar and Glasser ([1983](https://doi.org/10.1063/1.864028)). Intuitively, the poloidal wavenumber of the mode becomes complex due to nonaxisymmetry, which is a distinct feature in stellarator plasmas. We plan to extend the theory to the nonlinear stage of ITG turbulence in stellarators. ([arXiv:2506.12948](https://doi.org/10.48550/arXiv.2506.12948).)

<p align='center'>
<img src='/images/GTC_linear_Rz.jpg' width='400'>
<img src='/images/GTC_linear_alphatheta.jpg'  width='391'>
</p>

Neoclassical and turbulent transport in tokamak plasmas
==========
Due to conservation laws, the change in the plasma density, momentum, and energy can be explained from the corresponding radial transport of these quantities in tokamaks. In global gyrokinetic simulations, the radial transport comes from both neoclassical (equilibrium magnetic drift) and turbulent (fluctuating ExB drift and 3D magnetic perturbations) processes. While the neoclassical transport is theoretically assumed to be small, they are often observed to be comparable with turbulent transport in global gyrokinetic simulations, and hence should be considered in order to explain the simulation results. Recently, an "orbit-flux" formulation has been developed and numerically implemented in global gyrokinetic simulations. From this formulation, we numerically demonstrate how the neoclassical transport can be driven by collisions, turbulence, and special edge effects such as the ion orbit loss. We plan to extend the formulation to stellarator plasmas. (PRL 133, [025101](https://doi.org/10.1103/PhysRevLett.133.025101) (2024).)

<p align='center'>
<img src='/images/equilibrium.jpg' width='355'>
<img src='/images/D3D_mflux.jpg'  width='400'>
</p>

Interactions between drift waves and zonal flows in magnetic confinement fusion plasmas and geophysical fluids
==========
Drift waves and zonal flows are utiquitous in magnetic confinement plasmas. Remarkably, they share similar mathematical description with Rossby waves and zonal flows in geophysical fluid dynamics, a famous example being the zonal flows on Jupiter. The wave-kinetic approach has often been used to study drift wave-zonal flow interactions, which considers wave packets as quasi-particles in phase space that interact via a collective field, i.e., the zonal flow. Recently, a Wigner-Moyal formulation has been proposed, which treats waves as quantum-like particles and retains essential “full-wave” effects. From this formulation, we theoretically explain why drift-wave turbulence is often localized in zonal flows where the local flow shear vanishes. Based on reduced fluid models, we further show that the local drift-wave instability growth rate is reduced by the zonal-flow curvature. This led to an improved understanding of the so called "Dimits shift", where drift-wave turbulence is completely extinguished by zonal flows. We plan to extend the theory to gyrokinetic plasmas. (PRL 124, [055002](https://doi.org/10.1103/PhysRevLett.124.055002) (2020).)

<p align='center'>
<img src='/images/TIstructure.jpg'  width='400'>
  <img src='/images/PropStructure.jpg'  width='525'>
</p>
