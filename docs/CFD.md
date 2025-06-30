# CFD

Disclaimer: I am not a specialist of CFD by any mean, I use it as a comparative tool to improve my design.


All aerodynamic simulations were run using InsightCAE with OpenFOAM as the solver backend.
The setup used steady-state incompressible flow at 17 m/s with the k-omega SST turbulence model, chosen for its reliability on external flows.
Simulations prioritized design iteration and relative performance over absolute precision.

I keep the defaults when creating a new 'Numeric Wind Tunnel' (it is using the kOmegaSST model by default)

I modify only the following parameters to have enough details on the mesh:
- lmsurf: 5 when running exploratory/experimental stuff - Faster and less accurate simulation
- lmsurf: 6 for detailed simulations
- lxsurf: 7 to have further refinement, when there are small features
- v: 17 (which is the speed, it is set to 17 m.s-1 most of the time, I detail it for each run)
- np: 16 (number of cpus running in parallel)




