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

O'Rourke, Patrick R; Smith, Steven J; McDuffie, Erin E; Klimont, Zbigniew; Crippa, Monica; Mott, Andrea; Wang, Shuxiao; Nicholson, Matthew B; Feng, Leyang; & Hoesly, Rachel M (2020). CEDS v_2020_09_11 Pre-Release Emission Data (v_2020_09_11) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4025316
