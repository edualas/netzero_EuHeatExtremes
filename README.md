# netzero_EuHeatExtremes
Repository with the scripts for the analysis and figures of the paper "European heat extremes under net-zero emissions" (URL/DOI to be provided upon publication)

The code is written on Python in Jupyter Notebooks (.ipynb). The notebooks here included are the following:
- preprocess.ipynb: this script processes the model output (e.g. maximum daily temperatures) to create the relevant variables for the analysis (e.g., TXx index)
- analysis.ipynb: this script produces all figures in the paper and calculates the needed values for all tables
  
Please note that the scripts are supposed to work with directories on Gadi, NCI's supercomputer, and those need to be adjusted to work with the user's paths for the relevant files. Files can either be obtained from the Australian ESGF node or from the Zenodo dataset created for the paper ([doi: 10.5281/zenodo.15433420](https://doi.org/10.5281/zenodo.15433420)).
