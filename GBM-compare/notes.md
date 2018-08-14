# Set up the Environment

1. Create a conda environment named `gbm` with `Xgboost` and `LightGBM` installed via `conda-forge`: `conda create -n gbm -c conda-forge xgboost lightgbm`;

2. Install additional packages used in the project: `conda install -n gbm matplotlib pandas statsmodels ipykernel`;

3. Activate the conda environment and install ipython kernel of the conda environment `gbm` to be used in jupyter: 
    
    1. `source activate gbm`
    
    2. `python -m ipykernel install --user --name gbm --display-name "Python 3 (gbm)"`;

4. To uninstall ipython kernel in the future, list all the kernels by `jupyter kernelspec list` and remove the directories;

5. Open Jupyter Lab: `jupyter lab` (no need to activate the conda environment);

6. Select the kernel `Python 3 (gbm)` for the notebooks;