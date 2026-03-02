# Electromagnetic-Thermal-Coupled-FDTD-
Electromagnetic Thermal
We are in the process of open-sourcing the simulation codes developed for this project. The first figure presents the core components of the electromagnetic field solver, including the update equations of the finite-difference time-domain (FDTD) method for advancing the magnetic field from the electric field, as well as representative code segments for implementing the plane-wave excitation source.
The second figure contains the iterative implementation of the numerical solution to the heat conduction equation. It also highlights the coupling strategy adopted in the multiphysics framework, specifically how the temperature update region is adaptively selected based on the distribution of electromagnetic power loss to improve computational efficiency.
At this stage, screenshots of several key modules are provided, while final organization and code annotation are still underway. The complete source code will be released subsequently, including:
1)	The full electromagnetic-thermal co-simulation framework;
2)	Modules implementing conformal grid techniques for accurately handling complex geometrical boundaries;
3)	Configuration files, scripts, and post-processing programs for all simulation cases presented in this work.
We hope that the open release of these resources will provide a valuable reference for researchers and developers in the fields of computational electromagnetics and multiphysics simulation.
