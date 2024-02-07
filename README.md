# Experimental data

Descriptions of the experimental data from "Settling velocity of nearly neutrally buoyant inertial particles in turbulent vertical flow".

## Matrix
Rows: particle size

1. 0.925  mm
2. 0.780  mm
3. 0.550  mm
4. 0.390  mm
5. 0.3275 mm
6. 0.196  mm
7. 0.1155 mm
8. 0.0875 mm

Columns: Flow cases

1. LU
2. LD
3. T1
4. T2
5. T3

## Variables
Dimensions of each variable are given in the brackets, [~].

- Diameter: d_50 [m]
- Diameter_ci: Confidence interval of particle size [m]
- Particle_density: density of particle [kg/m^3]
- Fluid_density: density of fluid [kg/m^3]
- Fluid_kinematic_viscosity: kinematic viscosity of fluid [m^2/s]
- TKE_dissipation_rate: TKE dissipation rate [m^2/s^3]
- Kolmogorov_length: (Fluid_kinematic_viscosity^3/TKE_dissipation_rate)^0.25 [m]
- Kolmogorov_time: (Fluid_kinematic_viscosity/TKE_dissipation_rate)^0.5 [s]
- u_rms: rms horizontal fluid velocity [m/s]
- w_rms: rms vertical fluid velocity [m/s]
- Urms: sqrt( [u_rms^2 + 2w_rms^2]/3 ) [m/s]
- tau_p: particle response time [s]
- Stag_particle_velocity_w: particle settling velocity at stagnant fluid [m/s]
- Stag_particle_std: standard deviation of particle settling velocity at stagnant fluid [m/s]
- Particle_velocity_w: measured particle settling velocity at turbulent flow [m/s]
- Particle_std: standard deviation of measured particle settling velocity at turbulent flow [m/s]
- Slip_velocity: slip velocity between Particle_velocity_w and fluid velocity along the trajectory [m/s]
- Slip_velocity_std: standard deviation of slip velocity
- St: Stokes number (tau_p/Kolmogorov_time)
- Sv: Settling parameter (tua_p*g/Urms)
