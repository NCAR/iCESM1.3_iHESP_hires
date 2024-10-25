# iCESM1.3_iHESP_hires

This is the isotope-enabled CESM1.3 code that has been ported to the NSF NCAR Derecho supercomputer. This code was developed for the Accelerated Scientific Discovery (ASD) project called *paleoWeather*, led by Dr. Bette Otto-Bliesner. The code was ported by Jim Edwards, with the water isotope capability implemented by Jiang Zhu and Jesse Nusbaumer and tested by Jiang Zhu.

Reference for using the code is Otto-Bliesner et al. paleoclimate Tropical Cyclones (manuscript in preparation).

Currently tested configurations include high-resolution (ne120_t12) and low-resolution (ne30_g16) fully coupled setup for preindustrial and some paleoclimates with the spectral element dynamical core in the atmosphere. You are welcome to test and tune the other configurations.

The code shares the same physical climate as the CESM1.3 used in the [MESACLIP Project](https://project.cgd.ucar.edu/projects/MESACLIP/index.html) (and the previous iHESP project). Updates from CESM1.2 and modifications for high-resolution applications are documented in [Chang et al. (2020)](https://doi.org/10.1029/2020MS002298). Notables are bug fixes in the radiation that are required for high-CO2 simulations, process rearrangements and bug fixes in microphysics, a new gravity wave scheme, a more efficient barotropic solver in the ocean, a new coupler infrastructure (Common Infrastructure for Modeling the Earth; CIME) backported from CESM2, and other tuning and small modifications.These changes are not found to impact climate sensitivity.
