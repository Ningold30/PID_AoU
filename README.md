GWAS_1_DATA_PREPARATION.ipynb - used for picking out phenotypes for GWAS and generating a covariates file with ancestral PCs, filtering on genetic sex, relatedness and other QC.

Var_set.ipynb - sets up an input, output, scripts and GenData working bucket within your workspace - you just need to run this once per workspace

Var_set_2.ipynb - sets all the output of Var_set.ipynb as useable variables in Jupyter notebook - run this once per notebook

GWAS_2_GRM.ipynb - using dsub to QC genetic data before GWAS
