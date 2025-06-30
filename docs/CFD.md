# CFD

**Disclaimer**: I am not a CFD specialist by any means. I use it as a comparative tool to guide and improve my design through iteration, not to generate fully validated aerodynamic data.

All aerodynamic simulations were run using **InsightCAE** with **OpenFOAM** as the solver backend.  
The setup uses steady-state, incompressible flow at **17m/s**, with the **k-omega SST** turbulence model, which InsightCAE applies by default in its "Numeric Wind Tunnel" module. This model is well-suited for external flow and boundary layer analysis. Simulations focused on **relative performance** and **trend validation**, rather than absolute accuracy.

## Custom Parameters

I kept most defaults and only modified a few parameters related to mesh resolution and solver speed:

- `lmsurf`:  
  - **5** for exploratory or early design runs (faster, less detailed)  
  - **6** for detailed simulations  

- `lxsurf`:  
  - **7** when small features require higher mesh refinement  

- `v`:  
  - **17** for velocity input, corresponding to 17m/s (used in most runs; stated individually per case)  

- `np`:  
  - **16** to run the solver on 16 CPU cores in parallel





