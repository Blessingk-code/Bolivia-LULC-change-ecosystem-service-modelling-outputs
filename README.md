# Bolivia-LULC-change-ecosystem-service-modelling-outputs
This repository contains spatial outputs from an integrated land-use and ecosystem service modelling workflow for Bolivia. The analysis combines historical land-use change, future LULC projections, and ecosystem service modelling using the InVEST suite.  The primary purpose of this repository is to provide transparent access to all raster outputs
Contents

The repository includes the following categories of raster datasets:

#1. Land Use / Land Cover (LULC)
Baseline LULC maps (1986, 2024) derived from MapBiomas
Predicted future LULC maps for:
SSP2 and SSP5 scenarios
Years 2050 and 2090
LULC under:
Business-as-usual (no intervention)
Intervention scenarios (protected area restoration rules applied)


#2. InVEST Model Outputs (Unclipped)
All ecosystem service outputs are provided in full spatial extent (not clipped to protected areas) to preserve raw model results.
Annual Water Yield
- Pixel-level water yield rasters (mm/year or m³)
- Generated across all climate and intervention scenarios
Sediment Retention (SDR)
- Soil loss (erosion)
- Sediment export
- Sediment retention rasters
Urban Flood Risk Mitigation
- Runoff retention / flood mitigation capacity
- Derived using rainfall, soil, and LULC inputs
  
#3. Scenario Structure

All outputs follow a consistent naming convention reflecting:
- Climate scenario	SSP2, SSP5
- Time horizon	2050, 2090
- Intervention	With_intervention, Without_intervention
  
#Notes on Use
- All datasets are provided before clipping to protected areas, ensuring maximum flexibility for downstream analysis.
- Raster resolution and extent are consistent across datasets to allow direct comparison.
- These outputs are intended for:Ecosystem service assessment, conservation planning and spatial analysis and modelling
  
#Methods Summary
LULC projections were generated using a combination of Random Forest suitability modelling, Markov chain transition probabilities, and Cellular Automata spatial allocation. Ecosystem services were modelled using InVEST, incorporating both land-use and climate projections (SSP2 and SSP5 for 2050 and 2090).
