The scripts in this repository can be used to simulate genetic data using msprime, under population split models that include "No Ancestral Stratification" and "Ancestral Stratification".  \

The general structure of this spit model can be viewed in "1_SimulatedModels.pdf". \\
The notebook "sim_ancestral_stratification_n100.ipynb" can be used to run simulations. By default, n=100 replicate simulations are run, and the results are used for estimating Population divergence times in a population split model.
Finally, the results under each model are used to estimate population divergence times using the TTo method (https://doi.org/10.1093/genetics/iyab008), and the method's robustness to deep ancestral population stratification investigated. 
