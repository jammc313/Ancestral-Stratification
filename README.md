The scripts in this repository can be used to simulate genetic data using msprime, under population split models that include "No Ancestral Stratification" and "Ancestral Stratification".

The purpose of this is to test the impacts of deep ancestral stratification on a method of divergence time estimation; the TTo method (https://doi.org/10.1093/genetics/iyab008).

The general structure of the split models is represented in "1_SimulatedModels.pdf".

The notebook "2_sim_ancestral_stratification_n100.ipynb" can be used to run simulations. By default, n=100 replicate simulations are run for each model. The results are used for estimating population divergence times in a population split model using the TT and TTo methods, and the robustness to deep ancestral population stratification investigated. 
