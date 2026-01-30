# Eaton and Palisades 2025 Fire: 
## Spatioeconomic Analysis in Six Southern Califrornia Counties

### Notebooks
- `pset_1_data_cleaning.ipynb`: Cleans raw data. Creates socal_commuting_flows.csv, socal_empl_wages, socal_housing, and socal_population.
- `pset_1.ipynb`: Models migration.

- `model.ipynb`:  Outlines short-run equilibrium model. (needs polishing)
- `cleaning_rf.ipynb`: Continuation of cleaning data, meant to be run after `pset_1_data_cleaning.ipynb`. Creates geodatasets, `DF_MODEL_I.csv`, `DF_MODEL_J.csv`, `DF_MODEL_IJ.csv`
- `maps.ipynb`: Creates initial maps to look at six counties of interest, their centroids, and the Eaton and Palisades 2025 fire. Outputs maps to `output/` directory.
- `solver.ipynb`: Solves for baseline equilibrium parameters, and runs counterfactual to compare.
- `plotter.ipynb`: Plots analysis of counterfactual. Outputs plots to `ouput/` directory.

### Folders
- `/output/`: stores figures for final report
- `/processed_data/`: stores intermediate datasets as well as counterfactual dataset
- `/raw_data/`: stores original raw data downloaded from gov.t sources
