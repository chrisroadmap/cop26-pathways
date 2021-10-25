# cop26-pathways
Climate projections for near-term pathways provided for illustration for COP26.

## installation

### requirements
- `anaconda` for `python3`
- `python` 3.6, 3.7, 3.8 or 3.9

### python and jupyter notebooks
```
conda env create -f environment.yml
conda activate cop26-pathways
```

If you get module import errors running any of the notebooks, it's likely that your local environment is not up to date:

```
cd cop26-pathways  # path to wherever your local copy is

# get latest version
git fetch
git pull

# update environment
conda activate cop26-pathways
conda env update -f environment.yml --prune
```

## references and acknowledgements

Nicholls, Zebedee & Lewis, Jared (2021). Reduced Complexity Model Intercomparison Project (RCMIP) protocol (v5.1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4589756

O'Rourke, Patrick R; Smith, Steven J; McDuffie, Erin E; Klimont, Zbigniew; Crippa, Monica; Mott, Andrea; Wang, Shuxiao; Nicholson, Matthew B; Feng, Leyang; & Hoesly, Rachel M (2020). CEDS v_2021_04_21 Release Emission Data (v_2021_02_05) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4741285

Smith, Chris. (2021). FaIR v1.6.2 calibrated and constrained parameter set (v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.5513022

Smith C.J., P.M. Forster, S. Berger, W. Collins, B. Hall, D. Lunt, M.D. Palmer, M. Watanabe, M. Cain, G. Harris, N.J. Leach, M. Ringer, M. Zelinka, 2021. Figure and data generation for Chapter 7 of the IPCC's Sixth Assessment Report, Working Group 1 (plus assorted other contributions). Version 1.0. https://doi.org/10.5281/zenodo.5211357
